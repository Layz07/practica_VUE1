<template>
  <footer class="footer">
    <div class="footer-content">
      <h3>Valorant Info</h3>
      <nav>
        <a href="#">Inicio</a>
        <a href="#">Agentes</a>
        <a href="#">Mapas</a>
        <a href="#">Noticias</a>
      </nav>
      <p>© 2025 Valorant Info - Página de fans, no oficial de Riot Games.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterValorant",
};
</script>

<style scoped>
.footer {
  background-color: #0f1923; /* color oscuro estilo Valorant */
  color: #fff;
  padding: 20px 10px;
  text-align: center;
  margin-top: 40px;
}

.footer-content h3 {
  margin: 0;
  font-size: 1.2rem;
  color: #ff4655; /* rojo característico de Valorant */
}

.footer-content nav {
  margin: 10px 0;
}

.footer-content nav a {
  margin: 0 10px;
  text-decoration: none;
  color: #ccc;
  transition: color 0.3s ease;
}

.footer-content nav a:hover {
  color: #ff4655;
}

.footer-content p {
  font-size: 0.85rem;
  margin-top: 10px;
  color: #888;
}
</style>

