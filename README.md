# Any Quiz Generator

<p align="center">
  <img src="img/screencapture.gif" title="screencapture" alt="screencapture">
</p>

### **Description / Rationale**
This repository demonstrates how to automatically generate quiz questions from any input text. The goal is to simplify the creation of multiple-choice quizzes using AI, making it useful for educators, trainers, or self-learners. It is completely free!

### **Instructions**
1. Input any text or upload a document (e.g., PDF).
2. The system will process the content and generate quiz questions with 4 possible answers for each.
3. Test your knowledge instantly or export the quiz as JSON, CSV, or PDF.

If there is a need to generate quiz questions continuously, just add new text and ask it to generate. It will add new questions.

<b>Note:</b> If for some reason it does not generate questions, visit this page: https://huggingface.co/spaces/Akbartus/MixtralAPI and click on "Restart this Space". If API is not used for prolonged period of time it is automatically going to a sleep mode. 

### **Tech Stack**
The project was made possible thanks to:
- HuggingFace-hosted Mixtral API
- PDF.js
- Vanilla JavaScript

### **Demo**
To see demo see this page: https://any-quiz-gen.glitch.me/
