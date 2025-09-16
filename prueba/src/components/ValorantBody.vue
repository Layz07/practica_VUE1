<template>
  <main class="valorant-body">
    <!-- Sección de presentación -->
    <section class="intro">
      <h2>¿Qué es Valorant?</h2>
      <p>
        <strong>Valorant</strong> es un juego de disparos táctico en primera persona desarrollado por Riot Games.
        Combina la precisión de un FPS con habilidades únicas de personajes llamados <em>agentes</em>.
      </p>
    </section>

    <!-- Sección de agentes -->
    <section class="agents">
      <h2>Agentes</h2>
      <p>
        Cada agente tiene habilidades especiales que aportan distintas estrategias. 
        Algunos se especializan en ataque, otros en defensa o apoyo al equipo.
      </p>
    </section>

    <!-- Sección de mapas -->
    <section class="maps">
      <h2>Mapas</h2>
      <p>
        El juego cuenta con mapas diseñados para fomentar la táctica y el trabajo en equipo, 
        ofreciendo múltiples rutas y sitios de plantado de la Spike.
      </p>
    </section>

    <!-- Sección de noticias -->
    <section class="news">
      <h2>Noticias</h2>
      <p>
        Riot Games actualiza constantemente Valorant con nuevos agentes, mapas y balances 
        para mantener el juego competitivo y fresco.
      </p>
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
  background-color: #0f1923; /* fondo oscuro */
  color: #d9dadb;
  padding: 40px 20px;
  font-family: Arial, Helvetica, sans-serif;
  text-align: left;
}

/* Títulos */
.valorant-body h2 {
  color: #ff4655; /* rojo característico */
  margin-bottom: 10px;
}

/* Secciones */
.valorant-body section {
  margin-bottom: 40px;
}

/* Texto */
.valorant-body p {
  line-height: 1.6;
}
</style>
