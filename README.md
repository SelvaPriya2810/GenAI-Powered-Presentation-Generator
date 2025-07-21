# 🧠 GenAI-Powered Presentation Generator 🎨📊

This project is an AI agent that **automatically creates PowerPoint presentations** from a single topic prompt. It combines **OpenAI's GPT-4o** for slide content, **DALL·E 3** for generating relevant images, and **python-pptx** to assemble everything into a polished `.pptx` file. Built in **Google Colab**, this tool helps automate slide deck creation for business, education, and research purposes.

---

## 🚀 Features

- 🔗 One-line prompt → Full slide deck
- 🧠 Uses GPT-4o to generate slide titles, bullet points, and image prompts
- 🖼️ Uses DALL·E 3 to create custom images per slide
- 🧰 Auto-builds presentation using `python-pptx`
- 📥 Exports a downloadable `.pptx` file
- 💻 Fully runs in Google Colab — no installation needed

---

## 🛠️ Tech Stack

- [OpenAI GPT-4o](https://platform.openai.com/docs/models/gpt-4) – for slide generation
- [DALL·E 3](https://platform.openai.com/docs/guides/images) – for AI-generated visuals
- [`python-pptx`](https://python-pptx.readthedocs.io/) – to programmatically build PowerPoint files
- [Google Colab](https://colab.research.google.com/) – for cloud-based execution
- `PIL`, `requests` – for image handling and downloads

---

## 📂 How It Works

1. **User provides a topic** and number of slides
2. **GPT-4o generates**:
   - Slide titles
   - Bullet points
   - Image prompts for each slide
3. **DALL·E creates images** based on prompts
4. **Slides are built** with `python-pptx`, including images + text
5. **Presentation is saved and downloaded** as `.pptx`

---

## 📦 Installation (for local run)

```bash
pip install openai python-pptx Pillow requests
