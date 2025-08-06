## 🔍 InterroSense – Scenario-Based AI-Driven Criminal Interrogation System

**InterroSense** is an intelligent criminal interrogation platform that leverages **scenario-adaptive large language models (LLMs)** and **real-time facial micro-expression analysis** to assist law enforcement in conducting more effective, unbiased, and explainable interrogations.

### 🚀 Key Features

* 🤖 **Adaptive Interrogation Engine**: Fine-tuned **Qwen1.5-1.8B-Chat** LLM dynamically adjusts its questions based on suspect responses and non-verbal cues.
* 🎭 **Real-Time Micro-Expression Analysis**: Detects facial action units (AUs), gaze, and head pose using a MobileNetV3-based classifier trained on the **Bag-of-Lies** dataset.
* 🔀 **Multimodal Fusion**: Integrates textual and visual deception cues using weighted late fusion for real-time deception scoring.
* 📊 **Officer Dashboard (Django)**: Live feedback with deception probabilities, detected behavioral cues, and recommended next questions.
* 🧠 **Explainable AI**: Highlights the contributing factors behind each deception score for transparent decision-making.
* 💻 **Low-Cost Hardware**: Runs on standard webcam and microphone; does not require specialized sensors.

### 📚 Datasets

* **Bag-of-Lies**: Multimodal deception dataset with facial video, gaze, and audio.
* **Custom Scenario-Based Corpus**: Simulated suspect–officer dialogues and adapted legal transcripts for LLM fine-tuning.

### 💡 Why InterroSense?

> Traditional interrogations depend heavily on human intuition, which can introduce bias and fatigue. InterroSense combines NLP and CV with intelligent logic to provide **scalable, unbiased, and data-driven interrogation support**.

