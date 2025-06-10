# AI Language Learning App with GPT-4o 

## Project description 

Developed an interactive web app that supports language learners through advanced AI tools. Users can correct grammar, translate text, generate paraphrases with explanations, take CEFR-level grammar quizzes, and chat with an AI tutor.
The app is built with Streamlit and OpenAI's GPT-4o, and includes features such as:

- Dynamic cost and token usage tracking
- Secure API key handling
- Multilingual interface (Polish, English, Catalan)
- Prompt templating and JSON-based feedback for explainability
- AI-powered topic search: Learners can request real-world content (e.g., articles, videos) on topics like "ecology," automatically tailored to their selected CEFR level - enabling more relevant, interest-based learning with authentic materials.
- Scalable architecture ready for ASR (Whisper) and TTS (gTTS) integration

The project showcases practical use of LLMs in EdTech, focusing on user experience and modular design for future expansion.

---

## Project Summary
A real-time, interactive language learning tool powered by GPT-4o. The app helps users practice conversation, get corrections, learn context-based vocabulary, and receive tailored feedback - all aligned with CEFR language proficiency levels.

---

## Problem
Most language apps are rigid and template-based, with limited adaptability to learner needs. This project explores how LLMs can simulate real-life conversation, provide feedback, and personalize learning based on interests and CEFR levels.

---

## My Role
- Architected and implemented the full system logic: from prompt design to multilingual interface
- Integrated GPT-4o as a conversational tutor, ensuring grammar correction and feedback after each user input
- Designed CEFR-based complexity modulation
- Designed and tested user flows for maximum clarity and engagement

---

## Key Features
The app includes several intelligent features designed to mimic real language instruction and adapt to different learner profiles:


- **Adaptive Learning Content:**
- Users choose a topic (e.g., "climate change"), and the app generates practice content matched to their level and interest.
- **AI-Generated CEFR Grammar Quizzes:** 
- Automatically generated multiple-choice quizzes based on the selected level.  GPT-4o both creates the questions and evaluates user answers.
- **AI Tutor Mode with Task Routing**
- Users choose between three modes:  
  *Explain*: Get step-by-step grammar or vocabulary clarification  
  *Task*: Receive a writing or grammar task to complete  
  *Chat*: Engage in conversation to simulate real-world dialogue  
GPT-4o dynamically adjusts its behavior based on the selected interaction mode.
- **Paraphrasing & Correction with Explanations:**
- Input any sentence to receive corrected versions and paraphrased alternatives. GPT-4o highlights issues and explains grammar or word choice in simplified English, supporting deep understanding.
- **Smart Translation:**
- Translate between Polish, English, Catalan, German, French
- **Personal Notepad:**
- Area for taking personal notes. While currently manual, it allows learners to jot down corrections, new words, or practice goals.
- **Token and Cost Tracking:**
- Real-time session stats show how many tokens were used and the estimated OpenAI API cost - encouraging mindful use and transparency.

---

## Tools & Technologies
Python, OpenAI GPT-4o API, Streamlit, CEFR-based logic

---

## Outcomes
Simulated a private language tutor using AI, lowering access barriers to high-quality conversation practice.
Demonstrated practical, scalable use of LLMs in edtech.

---

## Limitations & Future Work

- **No ASR/TTS integration yet**: While the app is architecturally prepared for speech input (Whisper) and output (gTTS or ElevenLabs), it currently supports only text-based interaction. Adding voice capabilities would significantly enhance usability for auditory learners.

- **No automated progress tracking**: The app does not store user data or track learning metrics automatically. However, users can manually write and save notes during sessions, which enables basic self-guided review. Future versions may include optional session history and personalized feedback dashboards.

- **Token cost transparency, but no quota system**: The app tracks cost and tokens used per session, but does not impose user-level rate limits or budgets. At scale, cost control mechanisms (e.g. credit system, usage tiers) would be necessary.

- **No live user feedback loop**: The system lacks mechanisms for collecting explicit user satisfaction or correction feedback. Implementing thumbs-up/down or Likert scoring could help refine prompt quality and GPT behavior.



# [Go to the app](https://language-assistant.streamlit.app/)



