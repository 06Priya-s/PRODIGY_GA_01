# PRODIGY_GA_01

# 🧠 GPT-2 AI Text Generator

<p>This project demonstrates how to fine-tune OpenAI's GPT-2 model on a custom dataset related to **Artificial Intelligence** and deploy it using a simple **Gradio interface**. The result is a lightweight, interactive text generator capable of producing coherent and contextually relevant text based on user prompts.</p>

---

<h2>🚀 Features</h2>

<ul>
<ol>🔁 **Fine-Tune GPT-2**: Train GPT-2 on your own dataset to adapt the model’s style and vocabulary to a specific domain (e.g., AI content).</ol>
<ol>✍️ **Text Generation Interface**: A clean Gradio-based web UI that allows users to input custom prompts and generate text interactively.</ol>
<ol>⚙️ **Custom Hyperparameters**: Adjustable generation settings including max length and temperature.</ol>
<ol>💾 **Model Saving & Loading**: Fine-tuned models and tokenizers are saved locally and reloaded for generation.</ol>
<ol>☁️ **Easy Deployment**: Ready to host on Hugging Face Spaces or other platforms for public access.</ol>
</ul>
---

<h2>## 📁 Project Structure</h2>

gpt2-ai-textgen/
│
├── ai_dataset.txt # Custom AI-related training data
├── train.py # Fine-tuning script
├── app.py # Gradio-based text generation UI
├── requirements.txt # Python dependencies
├── gpt2-ai-finetuned/ # Fine-tuned model (weights + tokenizer)
└── README.md # Project documentation
----


<h2>##📝 Training Dataset</h2>

<p>A simple text file ai_dataset.txt containing paragraphs of AI-related content was used to fine-tune GPT-2, enabling the model to better understand and generate text within this domain.
</p>

<h2>✨ Example Use Cases</h2>
<ul>
<ol>AI-related content generation</ol>
<ol>Academic writing support</ol>
<ol>Research brainstorming</ol>
<ol>Educational tool for understanding transformers</ol>
</ul>
