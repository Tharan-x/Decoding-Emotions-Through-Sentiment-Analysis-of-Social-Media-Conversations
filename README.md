🚀 DECODING EMOTIONS THROUGH SENTIMENT ANALYSIS OF SOCIAL MEDIA CONVERSATIONS

This project leverages Natural Language Processing (NLP) to decode emotional signals from social media conversations. By analyzing public posts from platforms like Twitter, Reddit, or other forums, the system identifies whether the sentiment expressed is Positive, Negative, or Neutral.

The core engine uses the VADER Sentiment Analyzer, with added capabilities such as:

Preprocessing unstructured text data

Emotion classification

Visualizing emotion distribution

Generating a project workflow flowchart



---

🛠️ HOW TO RUN:

1. Install required libraries:
pip install -r requirements.txt


2. Run the main script:
python emotion_analysis_bert_gui.py




---

🔗 LIVE DEMO:

 https://c10383e2a176229ef5.gradio.live/

---


🖼️ INTERFACE PREVIEW:

![interface of the project](https://github.com/user-attachments/assets/d4cabefc-610e-48f9-a49f-87f7806d9647)


---


📁 Project Structure:

emotion-analysis-project/
├── emotion_analysis.py           # Main Python script
├── social_media_posts.csv        # Sample dataset
├── emotion_labeled_data.csv      # Output with labeled emotions
├── README.md                     # Project overview
├── requirements.txt              # Python dependencies
├── flowchart_pipeline.png        # Pipeline flowchart
├── emotion_distribution.png      # Emotion frequency chart



---

📌 FEATURES

Cleaned, normalized, and lemmatized text input

Emoji-aware emotion detection using VADER

Visual analytics using Seaborn and Matplotlib

Pipeline flowchart generation with Graphviz

Simple and clean GUI built with Tkinter



---

⚙️ REQUIREMENTS:

The following Python libraries are required:

torch – for deep learning (BERT or model support)

transformers – for pre-trained sentiment/emotion models

tkinter – for GUI integration (comes with Python)

matplotlib (optional) – for emotion distribution visualization


To install all dependencies:
pip install torch transformers matplotlib

> Note: tkinter is typically pre-installed in most Python distributions. If missing, install it based on your OS.




---

📊  APPLICATIONS

🎯 Public sentiment monitoring

📊 Brand analysis dashboards

🧠 Mental health insight tools

🎓 Educational demo for emotion-aware NLP


---

👤 AUTHOR

Tharanish M
Second Year B.Tech – Artificial Intelligence and Data Science


---

📄 LICENSE

This project is intended for academic use only.
