body {
  background: radial-gradient(circle, #0f0, #000);
  color: #00ffcc;
  font-family: monospace;
  text-align: center;
  height: 100vh;
  overflow: hidden;
}

h1 {
  text-shadow: 0 0 10px #00ff00;
}

#portal {
  width: 200px;
  height: 200px;
  margin: 30px auto;
  border-radius: 50%;
  background: radial-gradient(circle, #00ff00, #003300);
  box-shadow: 0 0 30px #00ff00;
  animation: girar 4s linear infinite;
}

@keyframes girar {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

button {
  background: black;
  color: #00ff00;
  border: 2px solid #00ff00;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}

button:hover {
  background: #00ff00;
  color: black;
}