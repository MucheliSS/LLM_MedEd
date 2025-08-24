 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 44bbb8520300472482becede33fa10bc407c0726..35573b9e061c0f64b7f4c30d2363e57d01aa2fb9 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,14 @@
-# LLM_MedEd
+# LLM_MedEd
+
+A simple static website that compares major general-purpose large language models for medical educators.
+
+## Included Models
+- ChatGPT (GPT-4o)
+- Claude 3
+- Google Gemini 1.5
+- Mistral Large
+- Qwen2
+- DeepSeek
+
+## Usage
+Open `index.html` in a web browser to view the comparison table.
 
EOF
)
