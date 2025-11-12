Learn Fun Typing Test

Project Overview

Learn Fun is a modern, Monkeytype-inspired web application for practicing typing speed and accuracy. Built using only vanilla HTML, CSS, and JavaScript, it features a clean, responsive interface, customizable themes, and unique dynamic content generation powered by the Google Gemini API.

This project includes advanced features like real-time WPM calculation, cross-word backspacing, dedicated sound and voice controls, and multiple test durations.

Features

Dynamic Content Generation: Users can enter a theme (e.g., "a short sci-fi story") and the Gemini API will generate a unique typing passage.

Real-Time Feedback: Shows correct (blue) and incorrect (red) letters instantly.

Customizable Experience:

Dark/Light/Retro color themes.

Multiple font options.

Test durations of 15s, 30s, 60s, and 120s.

Full Audio Control: Separate toggles for master sound (spacebar click) and word pronunciation (voice).

Advanced Typing Logic: Allows backspacing across previous words to correct errors.

Responsive Design: Optimized for desktop and mobile devices.

How to Run the Project Locally

Since this project uses client-side JavaScript, you can run it directly in your web browser.

Clone the Repository:

git clone [https://github.com/YOUR_USERNAME/learn-fun-typing-test.git](https://github.com/YOUR_USERNAME/learn-fun-typing-test.git)


Open the File: Navigate to the cloned folder and double-click index.html to open it in your browser.

⚠️ IMPORTANT: Enabling Dynamic Content Generation

The "Generate Content" feature uses the Gemini API. For security reasons, the API key must be managed by the user when running the file locally.

The key has already been inserted in the index.html file (see line ~800 in the <script> tag), so the feature should work out-of-the-box.

If you are using this code base and want to update the key or use a different one, follow these steps:

Get your Gemini API Key from Google AI Studio.

Open index.html in a text editor.

Find the const apiKey line (around line 800) and replace the existing key with your own:

const apiKey = "YOUR_NEW_API_KEY_HERE"; 


Technologies Used

HTML5: Structure and Semantics

CSS3: Styling, Theming (using CSS Variables), and Gradient Animation

JavaScript (Vanilla): Core typing logic, state management, WPM calculation, and UI control

Web Speech API: Word pronunciation

Web Audio API: Spacebar click sound

Gemini API: Dynamic content generation

License

This project is open-source. (You can add a license like MIT here if you want).