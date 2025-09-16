<template>
  <main class="valorant-body">
    <!-- Sección de presentación -->
    <section class="intro">
      <h2>¿Qué es Valorant?</h2>
      <p>
        <strong>Valorant</strong> es un juego de disparos táctico en primera persona desarrollado por Riot Games.
        Combina la precisión de un FPS con habilidades únicas de personajes llamados <em>agentes</em>.
      </p>
      <a href="https://playvalorant.com/" target="_blank">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVAOCVp4IXuywnpIJzntGi6TQcUvsskwXUkQ&s" alt="Valorant Logo">
      </a>
    </section>

    <!-- Sección de agentes -->
    <section class="agents">
      <h2>Agentes</h2>
      <p>
        Cada agente tiene habilidades especiales que aportan distintas estrategias. 
        Algunos se especializan en ataque, otros en defensa o apoyo al equipo.
      </p>
      <a href="https://playvalorant.com/es-mx/agents/" target="_blank">
        <img src="https://cmsassets.rgpub.io/sanity/images/dsfx7636/news_live/a6ca137c031e56a80c52d7007406e959fcd11fb9-1920x1080.jpg" alt="Agentes de Valorant">
      </a>
    </section>

    <!-- Sección de mapas -->
    <section class="maps">
      <h2>Mapas</h2>
      <p>
        Los mapas de Valorant están diseñados para fomentar la táctica y el trabajo en equipo, 
        ofreciendo múltiples rutas y sitios de plantado de la Spike.
      </p>
      <a href="https://playvalorant.com/es-mx/maps/" target="_blank">
        <img src="https://www.exitlag.com/blog/wp-content/uploads/2024/12/valorant_maps.webp" alt="Mapas de Valorant">
      </a>
    </section>

    <!-- Sección de noticias -->
    <section class="news">
      <h2>Noticias</h2>
      <p>
        Riot Games actualiza constantemente Valorant con nuevos agentes, mapas y balances 
        para mantener el juego competitivo y fresco.
      </p>
      <a href="https://playvalorant.com/es-mx/news/" target="_blank">
        <img src="https://i.ytimg.com/vi/z4bHpH_j61g/hq720.jpg?sqp=-oaymwEXCK4FEIIDSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLBcTSOD5BRMXQCwmNV_vRKRx5mGCw" alt="Noticias de Valorant">
      </a>
    </section>
  </main>
</template>

<script>
export default {
  name: 'ValorantBody'
}
</script>

<style scoped>
.valorant-body {
  background-color: #0f1923;
  color: #d9dadb;
  padding: 40px 20px;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
}

/* Títulos */
.valorant-body h2 {
  color: #ff4655;
  margin-bottom: 10px;
}

/* Secciones */
.valorant-body section {
  margin-bottom: 50px;
}

/* Texto */
.valorant-body p {
  line-height: 1.6;
  max-width: 700px;
  margin: 0 auto 20px auto;
}

/* Imágenes con links */
.valorant-body img {
  max-width: 400px;
  border-radius: 8px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.valorant-body img:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(255, 70, 85, 0.5);
}
</style>