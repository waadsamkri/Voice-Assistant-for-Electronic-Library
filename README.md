# Voice Assistant for Electronic Library

This project is a simple **voice assistant** designed for an electronic library. It allows users to ask questions by speaking in Arabic, then provides both a written and spoken response about the library's services and information.

---

## How It Works

The assistant follows these core steps to fulfill the task requirements:

1. **Convert Audio Input to Text**  
   Using the browser's native **Web Speech API** (`SpeechRecognition`), the app listens to the user's spoken question and transcribes it into text.

2. **Generate a Response Using a Language Model**  
   Currently, the assistant uses a local keyword matching approach on predefined questions and answers.  
   This can be easily replaced with an API call to any Large Language Model (LLM) service such as **Cohere**, **OpenAI GPT**, or others to generate more flexible and accurate answers.

3. **Convert Response Text to Audio**  
   The app uses the browser's **SpeechSynthesis API** to read the assistant’s response aloud in Arabic.

---

## Included Files

- `index.html`: The main HTML file containing the user interface, styles, and JavaScript logic for voice recognition and response.

---

## How to Run Locally

1. Download or clone this repository.
2. Open the `index.html` file in a modern web browser (Google Chrome recommended).
3. When prompted, allow microphone access.
4. Click the **"ابدأ التحدث"** button and ask your question in Arabic.
5. The assistant will transcribe your speech, find the matching answer, display it, and read it out loud.

---

## Uploading to GitHub

To share this project on GitHub and host it:

1. Create a new GitHub repository.
2. Upload the project files (`index.html`).
3. Commit and push your changes.
4. (Optional) Enable **GitHub Pages** from the repository settings to host your assistant online for free.

---

## Future Improvements

- Integrate an external LLM API like **Cohere** or **OpenAI GPT** to generate more accurate and dynamic responses instead of static keyword matching.
- Improve voice recognition accuracy and handle more complex questions.
- Add multi-language support and enhance UI/UX for better user experience.

---


