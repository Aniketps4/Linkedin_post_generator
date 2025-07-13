#  LinkedIn Post Generator

This project is an **AI-powered LinkedIn post generator** that fine-tunes `DistilGPT2` on synthetic, professionally themed LinkedIn content. It enables users to generate career-focused, insightful, and personalized LinkedIn posts through a clean and simple Gradio interface.

![Gradio Interface]


---

##  Features

- Fine-tunes a lightweight GPT-2 model (`distilgpt2`) on synthetic LinkedIn post data
- Supports multiple themes:
  - `career_advice`
  - `industry_insights`
  - `personal_achievement`
- Includes domain-specific vocabulary with synonym injection using **WordNet**
- Simple UI built with **Gradio**
- Customizable post elements like `industry`, `achievements`, and `themes`

---

##  Dependencies

Install all required packages:

```bash
pip install transformers datasets torch pandas nltk gradio


