
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <title>Mensagem Especial 💌</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background-color: pink;
      color: darkred;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
      position: relative; /* referência para botoes absolutos */
    }

    .tela {
      display: none;
      padding: 20px;
    }

    .ativa {
      display: block;
    }

    .botoes {
      margin-top: 30px;
      height: auto;
    }

    button, a.botao {
      padding: 15px 25px;
      font-size: 18px;
      background-color: red;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin: 10px;
      text-decoration: none;
      display: inline-block;
      position: relative;
      user-select: none;
    }

    .fugitivo {
      position: absolute;
      transition: 0.2s;
      user-select: none;
      z-index: 100;
    }

    .corações {
      font-size: 40px;
      margin-top: 20px;
      animation: flutuar 2s infinite alternate;
    }

    @keyframes flutuar {
      from { transform: translateY(0); }
      to { transform: translateY(-20px); }
    }

    #linkMusica {
      position: fixed;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      background-color: red;
      color: white;
      padding: 15px 30px;
      border-radius: 12px;
      font-size: 20px;
      font-weight: bold;
      text-decoration: none;
      z-index: 1000;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      cursor: pointer;
      user-select: none;
      display: none;
    }

    /* Confete styles */
    .confete {
      position: fixed;
      width: 10px;
      height: 10px;
      background-color: red;
      opacity: 0.9;
      top: -10px;
      border-radius: 50%;
      pointer-events: none;
      animation-name: cairConfete;
      animation-timing-function: linear;
      animation-iteration-count: infinite;
    }

    @keyframes cairConfete {
      0% {
        transform: translateY(0) rotate(0deg);
        opacity: 0.9;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }
  </style>
</head>
<body>

  <div id="tela0" class="tela ativa">
    <h1>💖 Clique no botão abaixo para ver algo muito especial 💖</h1>
    <p><em>Eu sei q vcc jg volei mas não me da um block</em></p>
    <div class="botoes">
      <button onclick="proximaTela()">Vamos lá!</button>
    </div>
  </div>

  <div id="tela1" class="tela">
    <h1>Eu tenho uma habilidade!</h1>
    <div class="botoes">
      <button onclick="proximaTela()">Sério? Me mostra!</button>
      <button class="fugitivo" id="fug1">Nada demais...</button>
    </div>
  </div>

  <div id="tela2" class="tela">
    <h1>Eu sei descobrir o tipo sanguíneo das pessoas 😎</h1>
    <div class="botoes">
      <button onclick="proximaTela()">E qual é o meu então?</button>
      <button class="fugitivo" id="fug2">Sabe nada seu bananão</button>
    </div>
  </div>

  <div id="tela3" class="tela">
    <h1>Eu descobri que o seu é... A+</h1>
    <div class="botoes">
      <button onclick="proximaTela()">Como assim? 😳</button>
      <button class="fugitivo" id="fug3">Foda-seeeee</button>
    </div>
  </div>

  <div id="tela4" class="tela">
    <h1>A+ linda e perfeita que eu já vi 😍</h1>
    <p><em>Obgd por ter =vst até aqq</em></p>
    <div class="corações">❤️💖💕💘💝💓💞💗💟❤️‍🔥</div>
    <div class="corações">💗💖💘💓💞💝❤️💟💘💖</div>
  </div>

  <a id="linkMusica" href="https://www.tiktok.com/@oratype/video/7398738983645170950?is_from_webapp=1&sender_device=pc" target="_blank" rel="noopener noreferrer">
    🔊 Clique aqui para ouvir a música!
  </a>

  <script>
    let telaAtual = 0;
    const totalTelas = 5;

    function proximaTela() {
      document.getElementById(`tela${telaAtual}`).classList.remove('ativa');
      document.getElementById(`tela${telaAtual}`).classList.add('tela');

      telaAtual++;

      if (telaAtual >= totalTelas) {
        telaAtual = totalTelas - 1;
        return;
      }

      document.getElementById(`tela${telaAtual}`).classList.remove('tela');
      document.getElementById(`tela${telaAtual}`).classList.add('ativa');

      atualizarVisibilidadeLink();
      atualizarConfetes();
    }

    // Botões fugitivos se mexendo
    function fugirDoMouse(botao) {
      const margem = 20;
      const larguraJanela = window.innerWidth;
      const alturaJanela = window.innerHeight;

      const maxX = larguraJanela - botao.offsetWidth - margem;
      const maxY = alturaJanela - botao.offsetHeight - margem;

      const novoX = Math.floor(Math.random() * (maxX - margem)) + margem;
      const novoY = Math.floor(Math.random() * (maxY - margem)) + margem;

      botao.style.left = novoX + 'px';
      botao.style.top = novoY + 'px';
    }

    document.querySelectorAll('.fugitivo').forEach(botao => {
      fugirDoMouse(botao); // posição inicial
      botao.addEventListener('mouseenter', () => fugirDoMouse(botao));
    });

    function atualizarVisibilidadeLink() {
      const link = document.getElementById('linkMusica');
      if (telaAtual === 4) {
        link.style.display = 'inline-block';
      } else {
        link.style.display = 'none';
      }
    }

    // --- Confetes ---

    const confetes = [];
    const coresConfetes = ['#e74c3c', '#f1c40f', '#2ecc71', '#3498db', '#9b59b6', '#e67e22'];

    function criarConfete() {
      const confete = document.createElement('div');
      confete.classList.add('confete');

      // Cor aleatória
      confete.style.backgroundColor = coresConfetes[Math.floor(Math.random() * coresConfetes.length)];

      // Posição horizontal aleatória dentro da viewport
      confete.style.left = Math.random() * window.innerWidth + 'px';

      // Tempo de queda aleatório (3s a 7s)
      const duracao = 3000 + Math.random() * 4000;
      confete.style.animationDuration = duracao + 'ms';

      // Delay aleatório para dispersar confetes
      confete.style.animationDelay = Math.random() * 5000 + 'ms';

      document.body.appendChild(confete);
      confetes.push(confete);
    }

    function iniciarConfetes() {
      for (let i = 0; i < 50; i++) { // 50 confetes
        criarConfete();
      }
    }

    function removerConfetes() {
      confetes.forEach(c => c.remove());
      confetes.length = 0;
    }

    function atualizarConfetes() {
      if (telaAtual === 4) {
        iniciarConfetes();
      } else {
        removerConfetes();
      }
    }

    atualizarVisibilidadeLink();
  </script>

</body>
</html>
