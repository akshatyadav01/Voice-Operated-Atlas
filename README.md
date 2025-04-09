<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>🎙️ Voice-Operated Atlas</h1>
  <p>An intelligent voice-powered game interface built with Python, Arduino, and MySQL that recognizes Indian cities through speech and interacts dynamically with the user.</p>

  <div class="section">
    <h2>🛠️ Tech Stack</h2>
    <span class="tag">Python</span>
    <span class="tag">Arduino</span>
    <span class="tag">MySQL</span>
    <span class="tag">PyArduino</span>
    <span class="tag">PyWhatKit</span>
    <span class="tag">SpeechRecognition</span>
    <span class="tag">pyttsx3</span>
    <span class="tag">ttkbootstrap</span>
  </div>

  <div class="section">
    <h2>📌 Features</h2>
    <ul>
      <li>Voice-operated interactive city naming game with NLP integration.</li>
      <li>Dynamic GUI built using <code>ttkbootstrap</code> and <code>Tkinter</code>.</li>
      <li>City database includes all Indian cities categorized alphabetically.</li>
      <li>Smart AI responses using city frequency prioritization.</li>
      <li>Voice feedback using Google Text-to-Speech and pyttsx3.</li>
      <li>Graphical display of city, state, and tracking of the game.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 How It Works</h2>
    <ol>
      <li>The app prompts the user to name a city starting with a specific letter.</li>
      <li>The voice is recognized using Google Speech Recognition API.</li>
      <li>The city is verified in the database and displayed on the GUI.</li>
      <li>The system responds with another city that starts with the last letter of the user's input.</li>
      <li>Previously used cities are tracked and frequency is updated to prioritize popular cities.</li>
    </ol>
  </div>

  <div class="section">
    <h2>📷 GUI Snapshot</h2>
    <p>Refer to the <code>/screenshots</code> directory in the repo for full UI previews.</p>
  </div>

  <div class="section">
    <h2>📁 Setup Instructions</h2>
    <pre><code>git clone https://github.com/yourusername/voice-operated-atlas.git
cd voice-operated-atlas
pip install -r requirements.txt
# Ensure MySQL is running and the "India" database is set up
python atlas.py
    </code></pre>
  </div>

  <div class="section">
    <h2>📦 Dependencies</h2>
    <ul>
      <li><code>speechrecognition</code></li>
      <li><code>pyttsx3</code></li>
      <li><code>mysql-connector-python</code></li>
      <li><code>ttkbootstrap</code></li>
      <li><code>Pillow</code></li>
    </ul>
  </div>

  <div class="section">
    <h2>📄 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>.</p>
  </div>

  <div class="section">
    <h2>🤖 Future Improvements</h2>
    <ul>
      <li>Real-time analytics and leaderboard.</li>
      <li>Voice-controlled map navigation via Google Maps API.</li>
      <li>Multiplayer city-naming game mode.</li>
    </ul>
  </div>

  <hr />
  <p align="center">Made with ❤️ by <strong>You</strong></p>

</body>
</html>
