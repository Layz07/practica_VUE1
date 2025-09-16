<template>
  <nav class="menu-bar">
    <div class="logo">

    </div>
    <ul class="menu-links">
      <li>
        <RouterLink to="/" exact-active-class="active">Inicio</RouterLink>
      </li>
      <li>
        <RouterLink to="/armas" exact-active-class="active">Armas</RouterLink>
      </li>
      <li>
        <RouterLink to="/agentes" exact-active-class="active">Agentes</RouterLink>
      </li>
      <li>
        <RouterLink to="/skins" exact-active-class="active">Skins</RouterLink>
      </li>
    </ul>
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

.logo {
  font-size: 1.3rem;
  font-weight: bold;
  color: #ff4655;
  text-transform: uppercase;
  letter-spacing: 2px;
}

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

.menu-links a {
  text-decoration: none;
  color: #ececec;
  transition: color 0.3s, border-bottom 0.3s;
  padding-bottom: 3px;
}

.menu-links a:hover {
  color: #ff4655;
  border-bottom: 2px solid #ff4655;
}

.active {
  color: #ff4655;
  border-bottom: 2px solid #ff4655;
}
</style>
