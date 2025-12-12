# <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Game Style Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Press Start 2P', monospace;
    }body {
  background: radial-gradient(circle at top, #1b2735, #090a0f);
  color: #fff;
  min-height: 100vh;
  overflow-x: hidden;
}

header {
  text-align: center;
  padding: 40px 20px;
  border-bottom: 4px solid #00ffcc;
}

header h1 {
  font-size: 20px;
  color: #00ffcc;
  margin-bottom: 10px;
}

header p {
  font-size: 10px;
  color: #ccc;
}

.menu {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin: 30px 0;
}

.menu button {
  background: #111;
  border: 2px solid #00ffcc;
  color: #00ffcc;
  padding: 12px 18px;
  cursor: pointer;
  font-size: 10px;
  transition: all 0.2s ease;
}

.menu button:hover {
  background: #00ffcc;
  color: #000;
  transform: scale(1.05);
}

section {
  display: none;
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
  border: 2px dashed #00ffcc;
  background: rgba(0, 0, 0, 0.6);
}

section.active {
  display: block;
  animation: fadeIn 0.4s ease;
}

h2 {
  font-size: 14px;
  margin-bottom: 15px;
  color: #00ffcc;
}

p, li {
  font-size: 10px;
  line-height: 1.8;
  color: #ddd;
}

ul {
  margin-left: 20px;
}

.project {
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #444;
}

footer {
  text-align: center;
  padding: 20px;
  font-size: 8px;
  color: #777;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}

  </style>
</head>
<body>  <header>
    <h1>PLAYER ONE</h1>
    <p>Web Developer | Game Enthusiast</p>
  </header>  <div class="menu">
    <button onclick="showSection('about')">ABOUT</button>
    <button onclick="showSection('skills')">SKILLS</button>
    <button onclick="showSection('projects')">QUESTS</button>
    <button onclick="showSection('contact')">CONTACT</button>
