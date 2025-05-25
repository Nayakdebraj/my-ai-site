
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Video Generator</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0e0e0e;
      color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      color: #00ffff;
    }
    form {
      max-width: 800px;
      margin: 20px auto;
      background: #1c1c1c;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ffff44;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input[type="text"], textarea, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #555;
      background-color: #222;
      color: #f5f5f5;
    }
    input[type="file"] {
      margin-top: 10px;
      color: #f5f5f5;
    }
    button {
      margin-top: 20px;
      padding: 12px 20px;
      background-color: #00ffff;
      color: #000;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #00dddd;
    }
    .section {
      margin-bottom: 25px;
    }
    h2 {
      color: #00ffff;
    }
  </style>
</head>
<body>
  <header>
    <h1>🌌 AI Video Generator</h1>
  </header>
  <form>
    <div class="section">
      <h2>🗂 Input Options</h2>
      <label>Paste blog/article URL:</label>
      <input type="text" placeholder="Enter URL here..." />

      <label>Or paste your own script/text:</label>
      <textarea rows="4" placeholder="Enter custom text..."></textarea>

      <label>Or upload .txt or .docx file:</label>
      <input type="file" />
    </div>

    <div class="section">
      <h2>🗣️ Voiceover Options</h2>
      <label>Voice Gender:</label>
      <select>
        <option>Male</option>
        <option>Female</option>
        <option>Neutral</option>
      </select>

      <label>Voice Accent:</label>
      <select>
        <option>US</option>
        <option>UK</option>
        <option>Indian</option>
        <option>Australian</option>
      </select>

      <label>Speed:</label>
      <select>
        <option>Normal</option>
        <option>Slow</option>
        <option>Fast</option>
      </select>

      <label>Pitch:</label>
      <select>
        <option>Normal</option>
        <option>Low</option>
        <option>High</option>
      </select>
    </div>

    <div class="section">
      <h2>🧑‍💻 AI Avatar Options</h2>
      <label>Select Avatar:</label>
      <select>
        <option>None (Just Images Video)</option>
        <option>Male Avatar</option>
        <option>Female Avatar</option>
        <option>Animated Avatar (Mouth + Body Movement)</option>
      </select>
    </div>

    <div class="section">
      <h2>📏 Video Format</h2>
      <label>Select Video Size:</label>
      <select>
        <option>16:9 (YouTube/Desktop)</option>
        <option>9:16 (Reels/Shorts)</option>
        <option>1:1 (Square)</option>
        <option>4:5 (Insta/Facebook)</option>
      </select>
    </div>

    <div class="section">
      <h2>📤 Output Options</h2>
      <label>After video is ready:</label>
      <select>
        <option>View in browser</option>
        <option>Download the video</option>
        <option>Generate shareable link</option>
      </select>
    </div>

    <button type="submit">🚀 Generate AI Video</button>
  </form>
</body>
</html>
