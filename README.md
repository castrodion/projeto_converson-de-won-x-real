---------- HTML
<body>
  <img src="https://i.postimg.cc/GpCxYmvc/title.png" alt="Logo" class="logo">

  <div class="container">
    <div class="content">
      <h2>Quem ganha, ganha em Wons!</h2>
      <p> Que tal converter esse valor?</p>
      <button onclick="conversor()">Bora converter!</button>
    </div>
  </div>
  <footer>Alura - Imersão DEV - 2025</footer>
</body>


--------CSS
/* Global Styles */
body {
  background-color: black;
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  color: white;
  position: relative;
}

/* Logo Styles */
.logo {
  position: absolute;
  top: 20px;
  right: 20px;
  max-width: 150px;
  width: auto;
}

/* Container with the background image */
.container {
  background: url('https://i.postimg.cc/TY28jTqJ/bg4-ia.jpg') no-repeat center center/cover;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Content div for text and button */
.content {
  text-align: center;
  background-color: rgba(0, 0, 0, 0.5);
  padding: 20px 40px;
  border-radius: 8px;
}

.content h2 {
  margin-bottom: 20px;
}

/* Button Styles */
button {
  background-color: #ff1b7b;
  border: none;
  padding: 10px 20px;
  font-size: 1.2em;
  color: white;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #1ABC9C;
}

/* Footer Styles */
footer {
  text-align: center;
  padding: 10px;
}


----------- JS
valor = prompt("Digite um valor em wons")

umwon = 0.0040
alert ("R$" + valor * umwon)
