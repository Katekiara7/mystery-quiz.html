https://yourusername.github.io/mystery-it-game/
# Create a downloadable HTML file with the current mystery quiz content
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>1st Year IT Mystery Quiz</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 20px; background: #f2f2f2; }
    .quiz-box { background: white; border-radius: 12px; padding: 20px; margin-bottom: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
    .question { font-size: 18px; font-weight: bold; }
    .option { margin: 8px 0; cursor: pointer; padding: 8px; background: #eee; border-radius: 8px; transition: 0.3s; }
    .option:hover { background: #ddd; }
    .reveal { margin-top: 10px; color: green; font-weight: bold; display: none; }
    button { margin-top: 10px; padding: 6px 10px; border: none; background: #333; color: white; border-radius: 6px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>🕵️‍♂️ Mystery IT Quiz for 1st Year College</h1>
  <p>Click "Reveal Answer" only after you’ve made your choice!</p>

  <div id="quiz"></div>

  <script>
    const questions = [
      { q: "What does CPU stand for?", a: "Central Processing Unit", options: ["Central Process Utility", "Central Processing Unit", "Computer Primary Unit", "Core Process User"] },
      { q: "Which language is used for web development?", a: "HTML", options: ["Pascal", "HTML", "Python", "C++"] },
      { q: "What does RAM stand for?", a: "Random Access Memory", options: ["Read Access Mode", "Random Access Memory", "Run Active Memory", "Ready All Mode"] }
    ];

    const quiz = document.getElementById("quiz");

    questions.forEach((item, index) => {
      const box = document.createElement("div");
      box.className = "quiz-box";

      const q = document.createElement("div
 
