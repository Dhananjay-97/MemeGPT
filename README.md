# 🧙 MemeGPT - Your Personal Meme Generator

Generate hilarious memes with ease using MemeGPT! This application leverages the power of OpenAI's GPT models to create memes based on your text input. Simply provide a situation, topic, or story, and MemeGPT will intelligently select relevant meme templates and generate meme images with appropriate captions.

![MemeGPT Demo](https://your-demo-image-or-gif-url.com) <!-- Optional: Add your demo screenshot or GIF -->

---

## 📚 Table of Contents

- [Features](#features)
- [How to Use](#how-to-use)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Generating Memes](#generating-memes)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

---

## Features

- **AI-Powered Meme Generation**  
  Uses OpenAI's GPT models to understand your input and generate relevant meme text.

- **Variety of Meme Templates**  
  Comes pre-loaded with a selection of popular meme templates (Drake Hotline Bling, Distracted Boyfriend, Disaster Girl, and more!).

- **Easy-to-Use Web Interface**  
  Built with Streamlit for a simple and intuitive user experience.

- **Meme Image Editor**  
  Overlays generated text onto meme templates, creating ready-to-share images.

- **Image Management**  
  View and delete generated memes directly within the app.

---

## How to Use

### Prerequisites

1. **Python 3.7+** – Make sure you have Python installed on your system.
2. **pip** – Python package installer.
3. **OpenAI API Key** – You'll need an OpenAI API key to use the GPT models. Get one from [OpenAI's website](https://platform.openai.com/).
4. **Environment Variables**  
   Set your OpenAI API key as an environment variable named `OPENAI_API_KEY`. You can do this by:
   - Creating a `.env` file in the root directory and adding:
     ```
     OPENAI_API_KEY=YOUR_API_KEY_HERE
     ```
   - Or setting it directly in your system's environment variables.

---

### Installation

```bash
git clone https://github.com/Dhananjay-97/MemeGPT.git
cd MemeGPT

python -m venv venv
source venv/bin/activate  # On Linux/macOS
venv\Scripts\activate     # On Windows

pip install -r requirements.txt

streamlit run app.py
```

### Generating Memes
1. Enter Your Text
In the Streamlit app, you'll see a text area labeled "Situation, topic or article:". Enter the text you want to generate a meme about. This could be a short phrase, a topic, or even a longer story.

2. Click "Generate Memes"
Click the "Generate Memes" button. MemeGPT will use OpenAI to process your input, select suitable meme templates, and generate meme images.

3. View and Manage Memes
The generated memes will be displayed below:

View: See the generated meme images.

Delete: Click the "🗑️ Delete" button below a meme to remove it from the display.

### Dependencies
streamlit

python-dotenv

openai

Pillow (PIL)

You can find the exact versions in the requirements.txt file.

### Contributing
We welcome contributions! You can:

💡 Suggest New Meme Templates: Propose new meme formats to be added to meme_data.json.

🧠 Improve AI Prompts: Help refine the instructions in system_instructions.py to generate even better meme text.

🎨 Enhance UI/UX: Suggest or implement improvements to the Streamlit interface.

🐛 Report Bugs: Found a bug? Let us know by opening an issue!   
