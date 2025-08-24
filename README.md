# LLM Models for Medical Educators — 2025

A lightweight GitHub Pages site that tracks leading large language models (LLMs) and practical educator-facing use cases. It foregrounds model capabilities that matter in health professions education (multimodality, long-context, reasoning), and links to primary sources and reviews.

> Scope: general-purpose frontier models (OpenAI, Google, Anthropic), strong open models (Meta, Mistral), enterprise RAG-centric (Cohere), and health-domain LLMs (Med-PaLM 2, AMIE). See references below.

## Who this is for
Medical and health professions educators, program directors, and education researchers who need a concise, citable overview when planning curricula, assessment, and faculty development.

## Quick start (GitHub Pages)
1. Create a public repo and add `index.html` (from this project).
2. Add this `README.md` for documentation.
3. In GitHub: Settings → Pages → Build from branch → `main` (root) → Save.
4. Your site will be available at `https://<username>.github.io/<repo>`.

## Customize
- Edit the **Model Cards** inside `index.html` to add or retire models.
- Keep the **References** section aligned to primary sources and peer-reviewed reviews.
- To add institutional policy links, use the “Governance and policy” list near the end of `index.html`.

## Models at a glance (snapshot: Aug 24, 2025)
| Model | Modality | Max context (tokens) | Notes |
|---|---|---:|---|
| OpenAI **GPT-5** | Text, vision, audio | Not disclosed | New default in ChatGPT with improved instruction following and reduced hallucinations; GPT-5 Pro for extended reasoning. [Ref](https://openai.com/index/introducing-gpt-5/) |
| OpenAI **GPT-4.1** (API) | Text, vision, long-context | up to 1,000,000 | Strong long-context and instruction following at lower cost vs 4o. [Ref](https://openai.com/index/gpt-4-1/) |
| Google **Gemini 2.0** | Multimodal in/out, agentic | — | Agentic features and multimodal output; Live APIs. [Ref](https://blog.google/technology/google-deepmind/google-gemini-ai-update-december-2024/) |
| Google **Gemini 1.5/Pro** | Text, vision, long-context | up to 1,000,000 | Long-context scenarios for code and large docs. [Ref](https://ai.google.dev/gemini-api/docs/long-context) |
| Anthropic **Claude 3.5 Sonnet** | Text, vision | 200,000 | Strong coding and vision; computer-use beta. [Ref](https://www.anthropic.com/news/claude-3-5-sonnet) |
| Meta **Llama 3.1 405B** | Text (open weights) | — | Large open model family for local or hosted use. [Ref](https://ai.meta.com/blog/meta-llama-3-1/) |
| **Mistral Large 2** | Text | — | Reasoning, code, multilingual improvements. [Ref](https://mistral.ai/news/mistral-large-2407) |
| Cohere **Command R+ (08-2024)** | Text | 128,000 | Optimized for RAG and tool use. [Ref](https://docs.cohere.com/docs/command-r-plus) |
| Google **Med-PaLM 2** | Text, health domain | — | Expert-level on USMLE-style items; medical focus. [Ref](https://sites.research.google/med-palm/) |
| Google **AMIE** (Nature 2025) | Text, health domain | — | Interactive assistant for differential diagnosis. [Ref](https://www.nature.com/articles/s41586-025-08869-4) |

## Evidence and cautions for educators
- Reviews of LLMs in medical education and assessment discuss opportunities and persistent limitations such as study quality and outcome measurement. See Lucas et al. 2024, Vrdoljak et al. 2025, Gordon et al. 2024, Feigerlova et al. 2025.  
- WHO guidance outlines ethics and governance considerations for large multimodal models in health.  
- AAMC resources summarize readiness, curriculum adoption, and responsible use in academic medicine.  
Full citations are in the References.

## Contributing
Please:
- Cite primary sources for claims about capabilities.  
- Prefer official documentation for specs like context length.  
- Use peer-reviewed literature for educational claims.

## License
Content is provided for scholarly use. Respect the licenses and usage terms of the models you deploy.

## References
1. OpenAI. Introducing GPT-5. 7 Aug 2025. https://openai.com/index/introducing-gpt-5/  
2. OpenAI. Introducing GPT-4.1 in the API. 14 Apr 2025. https://openai.com/index/gpt-4-1/  
3. Google DeepMind. Introducing Gemini 2.0. 11 Dec 2024. https://blog.google/technology/google-deepmind/google-gemini-ai-update-december-2024/  
4. Gemini API long-context overview. https://ai.google.dev/gemini-api/docs/long-context  
5. Anthropic. Claude 3.5 Sonnet. 21 Jun 2024. https://www.anthropic.com/news/claude-3-5-sonnet  
6. Anthropic. Computer use and 3.5 models. 22 Oct 2024. https://www.anthropic.com/news/3-5-models-and-computer-use  
7. Meta. Llama 3.1 announcement. 23 Jul 2024. https://ai.meta.com/blog/meta-llama-3-1/  
8. Mistral AI. Mistral Large 2. 24 Jul 2024. https://mistral.ai/news/mistral-large-2407  
9. Cohere. Command R+. 2024-08. https://docs.cohere.com/docs/command-r-plus  
10. Singhal K, et al. Med-PaLM program page. https://sites.research.google/med-palm/  
11. McDuff D, et al. AMIE for differential diagnosis. Nature. 2025. https://www.nature.com/articles/s41586-025-08869-4  
12. Lucas HC, et al. Systematic review of LLMs in medical education. 2024. https://pubmed.ncbi.nlm.nih.gov/38639098/  
13. Vrdoljak J, et al. Review of LLMs in medical education and healthcare. 2025. https://pmc.ncbi.nlm.nih.gov/articles/PMC11942098/  
14. Gordon M, et al. Scoping review of AI in medical education. 2024. https://www.tandfonline.com/doi/full/10.1080/0142159X.2024.2314198  
15. Feigerlova E, et al. Systematic review of AI impact in HPE. 2025. https://bmcmededuc.biomedcentral.com/articles/10.1186/s12909-025-06719-5  
16. WHO. Ethics and governance of AI for health, including LMMs. 2024–2025 updates. https://www.who.int/news/item/18-01-2024-who-releases-ai-ethics-and-governance-guidance-for-large-multi-modal-models and https://www.who.int/publications/i/item/9789240084759  
17. AAMC. Principles for responsible AI use in medical education. https://www.aamc.org/about-us/mission-areas/medical-education/principles-ai-use  
18. AAMC. Medical schools move from worrying about AI to teaching it. 15 May 2025. https://www.aamc.org/news/medical-schools-move-worrying-about-ai-teaching-it
