<script setup>
import Tops from './components/Tops.vue';
import Links from './components/Links.vue';
let link_1 = 'https://rosepinetheme.com/';
</script>

<template>
  <main>
    <header>
      <h1>Fonts-Jct 📚</h1>
    </header>
    <nav>
      <ul>
        <ol><a class="nav-a" href="#inicio">Inicio 📌</a></ol>
        <ol><a class="nav-a" href="#tops">Top Fuentes ✏️</a></ol>
        <ol><a class="nav-a" href="#recien">Recién Descubiertas 🧷</a></ol>
        <ol><a class="nav-a" href="#links">Links Útiles 🔗</a></ol>
      </ul>
    </nav>
    <section>
      <h2 id="inicio">Inicio 📌</h2>
      <p>
        Hey! Aquí están todas las fuentes que he ido descubriendo y usando ✨ Es como mi diario tipográfico personal
        donde
        <br>
        guardo las que más me gustan. Desde scripts suaves hasta bold llamativas, todas tienen su lugar especial jajaja
      </p>
      <hr>
      <strong>⤵️</strong>
    </section>
    <Tops id="tops" />
    <hr>
    <section class="section-f">
      <h3 id="recien">Recién Descubiertas 🧷</h3>
      <p>
        🌟 Lo Más Nuevo - Mi sección de fuentes recién llegadas, las que todavía huelen a nuevo y me tienen con
        <br> ganas de probarlas en el próximo proyecto jajaja.
      </p>
      <div>
        <button class="button-f">
          <br>
          🔗
          <a class="button-a" href="https://fonts.google.com/specimen/Audiowide?query=Audiowide" target="_blank"
            rel="noopener noreferrer">Audiowide</a>
        </button>
        <button class="button-f">
          <br>
          🖌️
          <a class="button-a" href="https://fonts.google.com/specimen/Rajdhani?query=Rajdhani" target="_blank"
            rel="noopener noreferrer">Rajdhani</a>
        </button>
        <button class="button-f">
          <br>
          ✏️
          <a class="button-a" href="https://fonts.google.com/specimen/Tektur?query=Tektur" target="_blank"
            rel="noopener noreferrer">Tektur</a>
        </button>
        <button class="button-f">
          <br>
          🧷
          <a class="button-a" href="https://fonts.google.com/specimen/Kalam?query=Kalam" target="_blank"
            rel="noopener noreferrer">Kalam</a>
        </button>
        <button class="button-f">
          <br>
          🔧
          <a class="button-a" href="https://fonts.google.com/specimen/Saira?query=Saira" target="_blank"
            rel="noopener noreferrer">Saira</a>
        </button>
        <button class="button-f">
          <br>
          📌
          <a class="button-a" href="https://fonts.google.com/specimen/Figtree" target="_blank"
            rel="noopener noreferrer">Figtree</a>
        </button>
      </div>
    </section>
    <hr>
    <Links id="links" />
    <hr>
    <footer>
      <p><strong>✨ Nota:</strong> <cite>Todas las fuentes mostradas pertenecen a sus respectivos creadores y
          propietarios.</cite>
        <br>
        <small>Este sitio es únicamente con fines personales y de investigación tipográfica. Siempre respeta las
          licencias originales jajaja</small>
      </p>
      <p><cite><strong>🎨 Diseño:</strong> Inspirado en <a href="https://rosepinetheme.com/">Rose Pine theme</a></cite>
      </p>
    </footer>
  </main>
</template>

<style scoped>
* {
  padding: 0rem;
  box-sizing: border-box;
}
</style>
