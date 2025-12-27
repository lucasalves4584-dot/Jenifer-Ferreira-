# Jenifer-Ferreira-<!-- TELA DE INÍCIO COM MÚSICA -->
<section id="start">
  <h1>Jenifer 💖</h1>
  <p>
    Antes de continuar…  
    aperte o botão e entre no nosso clima 🎶
  </p>

  <button class="btn" onclick="startSurprise()">
    Iniciar surpresa ▶
  </button>
</section
<script>
  function startSurprise() {
    window.open(
      "https://open.spotify.com/track/2vT4cV3j1K0ZQ9JZ0pGk9Z",
      "_blank"
    );

    document.getElementById("start").style.display = "none";
    window.scrollTo({ top: 0, behavior: "smooth" });
  }
</script><section class="scroll">
  <h1>Sempre que essa música tocar 🎧</h1>
  <p>Lembre da nossa praia… e de nós.</p>

  <div class="spotify-card pulse">
    <img src="https://i.scdn.co/image/ab67616d0000b273c0f3a7f8b8c6dc0d9f0a8f38">

    <div class="spotify-info">
      <strong>Nossa Praia</strong>
      <span>Matheus & Kauan</span>
    </div>

    <a 
      href="https://open.spotify.com/track/2vT4cV3j1K0ZQ9JZ0pGk9Z" 
      target="_blank"
      class="spotify-play">
      ▶
    </a>
  </div>
</section>
