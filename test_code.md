<!-- Html code: -->

<!DOCTYPE html>
<html>
<head>
  <title>Test Code</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <h1>Test Code -</h1>
  <button id="test-button">Click Me</button>

  <script src="script.js"></script>
</body>
</html>

<!-- CSS code: -->

body {
  background-color: #f2f2f2;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

h1 {
  text-align: center;
}

button {
  padding: 13px 24px;
  font-size: 16px;
  font-weight: 500;
  background-color: #6994c5;
  color: #fff;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #3d5a80;
}


<!-- JS code -->

const button = document.getElementById('test-button');

button.addEventListener('click', () => {
  alert('Button clicked!');
});
