<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Full Stack Internship</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    * {
  box-sizing: border-box;
}

body {
  background: #061829;
  font-family: 'Segoe UI', sans-serif;
  color: #fff;
  text-align: center;
  margin: 0;
  padding: 0;
}

.container {
  padding: 20px;
}

h1 {
  font-size: 1.6rem;
  margin-bottom: 15px;
  color: #00e5ff;
}

.demo-button {
  background: #ff3c3c;
  color: white;
  padding: 10px 20px;
  border: none;
  font-size: 1rem;
  border-radius: 8px;
  cursor: pointer;
  margin: 15px 0;
}

h2 {
  margin: 25px 0 15px;
  font-size: 1rem;
  font-weight: normal;
  color: #ccc;
}

.tech-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-bottom: 25px;
}

.tech-box {
  background: white;
  color: black;
  border-radius: 10px;
  padding: 10px;
  width: 90px;
  text-align: center;
}

.tech-box img {
  width: 50px;
  height: 50px;
}

.tech-box p {
  margin-top: 8px;
  font-weight: bold;
  font-size: 0.9rem;
}
  </style>
</head>
<body>
  <div class="container">
    <h1>Full Stack Web Development<br>Internship Program</h1>
    <button class="demo-button" onclick="showDemoAlert()">Join the Free Demo</button>
    <h2>Master Technologies like</h2>
    
    <div class="tech-row">
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/javascript.png" alt="Express.JS">
        <p>Express.JS</p>
      </div>
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/react-native.png" alt="React.JS">
        <p>React.JS</p>
      </div>
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/nodejs.png" alt="Node.JS">
        <p>Node.JS</p>
      </div>
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/mongodb.png" alt="MongoDB">
        <p>MongoDB</p>
      </div>
    </div>

    <div class="tech-row bottom">
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/html-5.png" alt="HTML">
        <p>HTML</p>
      </div>
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/css3.png" alt="CSS">
        <p>CSS</p>
      </div>
      <div class="tech-box">
        <img src="https://img.icons8.com/color/96/000000/javascript.png" alt="JavaScript">
        <p>JavaScript</p>
      </div>
    </div>
  </div>

  <script src="script.js">
    function showDemoAlert() {
  alert("Thank you for your interest! Our team will contact you soon.");
}
  </script>
</body>
</html>
