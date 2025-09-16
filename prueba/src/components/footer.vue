<template>
  <footer class="footer">
    <div class="footer-content">
      <!-- Logo + título -->
      <div class="footer-logo">
        <img 
          src="https://us-tuna-sounds-images.voicemod.net/e3904d15-f20e-4f63-8e22-047822c5937a-1663641471979.jpg" 
          alt="Valorant Logo"
        />
        <h3>Valorant Info</h3>
      </div>

      <!-- Navegación -->
      <nav class="footer-nav">
        <a href="#">Inicio</a>
        <a href="#">Armas</a>
        <a href="#">Mapas</a>
        <a href="#">Skins</a>
        <a href="#">Noticias</a>
      </nav>
    </div>

    <!-- Derechos -->
    <div class="footer-bottom">
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
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');

.footer {
  background-color: #0f1923;
  color: #fff;
  padding: 20px;
  margin-top: 40px;
  border-top: 2px solid #ff4655;
  font-family: 'Poppins', sans-serif; /* Tipografía moderna */
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 15px;
}

.footer-logo {
  display: flex;
  align-items: center;
  gap: 10px;
}

.footer-logo img {
  width: 35px;
  height: 35px;
}

.footer-logo h3 {
  margin: 0;
  font-size: 1.3rem;
  font-weight: 700;
  color: #ff4655;
  letter-spacing: 1px;
}

.footer-nav {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.footer-nav a {
  text-decoration: none;
  color: #ccc;
  font-weight: 500;
  transition: color 0.3s ease, transform 0.2s ease;
}

.footer-nav a:hover {
  color: #ff4655;
  transform: translateY(-2px);
}

.footer-bottom {
  text-align: center;
  margin-top: 15px;
  font-size: 0.85rem;
  color: #888;
}
</style>
