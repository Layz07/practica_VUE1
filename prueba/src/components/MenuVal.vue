<template>
  <nav class="menu-bar">

    <div class="logo">
      <img src="/Logo.png" alt="Valorant Logo" class="logo-img" />
      <span class="logo-text">ValorantHub</span>
    </div>

    <ul class="menu-links">
      <li>
        <RouterLink to="/" exact-active-class="active" class="inicio">Inicio</RouterLink>
      </li>
      <li>
        <RouterLink to="/armas" exact-active-class="active" class="armas">Armas</RouterLink>
      </li>
      <li>
        <RouterLink to="/agentes" exact-active-class="active" class="agentes">Agentes</RouterLink>
      </li>
      <li>
        <RouterLink to="/skins" exact-active-class="active" class="skins">Skins</RouterLink>
      </li>
    </ul>

    <div class="login-btn">
      <RouterLink to="/login">Login</RouterLink>
    </div>
  </nav>
</template>

<script setup>
</script>

<style scoped>

.menu-bar {
  background: #0f1923;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.8rem 2rem;
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.6);
  position: sticky;
  top: 0;
  z-index: 1000;
}

/* ===== Logo ===== */
.logo {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo-img {
  width: 40px;
  height: 40px;
}

.logo-text {
  font-size: 1.3rem;
  font-weight: bold;
  color: #ff4655;
  text-transform: uppercase;
  letter-spacing: 2px;
}

/* ===== Links ===== */
.menu-links {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

.menu-links li {
  font-weight: 600;
}

/* Colores por sección */
.inicio {
  color: #4cafef; /* Azul */
}

.armas {
  color: #ff4655; /* Rojo */
}

.agentes {
  color: #43ff64; /* Verde */
}

.skins {
  color: #ffb347; /* Naranja */
}

.menu-links a {
  text-decoration: none;
  transition: color 0.3s, border-bottom 0.3s;
  padding-bottom: 3px;
}

.menu-links a:hover {
  border-bottom: 2px solid currentColor;
}

/* Activo */
.active {
  border-bottom: 2px solid currentColor;
}

/* ===== Login Button ===== */
.login-btn a {
  text-decoration: none;
  background: #ff4655;
  color: #fff;
  padding: 0.5rem 1rem;
  border-radius: 6px;
  font-weight: bold;
  transition: background 0.3s;
}

.login-btn a:hover {
  background: #d93b47;
}
</style>
