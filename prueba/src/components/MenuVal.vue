<template>
  <nav class="menu-bar">
    <!-- Logo -->
    <div class="logo">
      <img src="https://us-tuna-sounds-images.voicemod.net/e3904d15-f20e-4f63-8e22-047822c5937a-1663641471979.jpg" alt="Valorant Logo" class="logo-img" />
    </div>

    <!-- Links -->
    <ul class="menu-links">
      <li><RouterLink to="/" exact-active-class="active">INICIO</RouterLink></li>
      <li><RouterLink to="/armas" exact-active-class="active">ARMAS</RouterLink></li>
      <li><RouterLink to="/agentes" exact-active-class="active">AGENTES</RouterLink></li>
      <li><RouterLink to="/skins" exact-active-class="active">SKINS</RouterLink></li>
      <li><RouterLink to="/noticias" exact-active-class="active">NOTICIAS</RouterLink></li>
    </ul>

    <!-- Icons + Botón jugar -->
    <div class="actions">
      <button class="icon-btn">🔍</button>
      <button class="icon-btn">🌐</button>
      <RouterLink to="/login" class="play-btn">JUGAR</RouterLink>
    </div>
  </nav>
</template>

<script setup>
</script>

<style scoped>
/* ===== Navbar general ===== */
.menu-bar {
  background: #111; /* Fondo negro */
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.8rem 2rem;
  position: sticky;
  top: 0;
  z-index: 1000;
}

/* ===== Logo ===== */
.logo-img {
  height: 32px;
  object-fit: contain;
}

/* ===== Links ===== */
.menu-links {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

.menu-links a {
  text-decoration: none;
  color: #fff; /* Blanco */
  font-weight: 600;
  font-size: 0.9rem;
  letter-spacing: 1px;
  transition: color 0.3s;
}

.menu-links a:hover {
  color: #ff4655; /* Rojo Valorant */
}

.active {
  color: #ff4655;
}

/* ===== Acciones (derecha) ===== */
.actions {
  display: flex;
  align-items: center;
  gap: 1rem;
}

/* Botones íconos (buscar, idioma) */
.icon-btn {
  background: #222;
  border: none;
  border-radius: 50%;
  width: 36px;
  height: 36px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  cursor: pointer;
  font-size: 1.1rem;
  transition: background 0.3s;
}

.icon-btn:hover {
  background: #333;
}

/* Botón Jugar */
.play-btn {
  background: #ff4655;
  color: #fff;
  padding: 0.5rem 1.2rem;
  border-radius: 20px;
  font-weight: bold;
  text-decoration: none;
  transition: background 0.3s;
}

.play-btn:hover {
  background: #e63c4b;
}
</style>
