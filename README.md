const frases = [
  "VOCÊ NÃO DEVIA TER ABERTO ISSO",
  "REALIDADE CORROMPIDA",
  "WUBBA LUBBA DUB DUB",
  "DIMENSÃO INSTÁVEL",
  "ERRO 404: SANIDADE"
];

function abrirPortal() {
  document.body.style.background =
    `hsl(${Math.random() * 360}, 100%, 10%)`;

  document.getElementById("texto").innerText =
    frases[Math.floor(Math.random() * frases.length)];

  document.body.classList.add("shake");

  setTimeout(() => {
    document.body.classList.remove("shake");
  }, 300);
}