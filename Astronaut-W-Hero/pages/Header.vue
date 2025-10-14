<template>
  <header class="fixed top-0 left-0 w-full z-30 bg-transparent">
    <nav class="nav-header">
      <a href="#seccion1" class="font-orbit">Link Header</a>
      <a href="#seccion2" class="font-orbit">Link Header</a>
      <a href="#seccion3" class="font-orbit">Link Header</a>
    </nav>
  </header>
</template>

<style scoped>
.font-orbit {
  font-family: 'Orbit', sans-serif;
}

.nav-header {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 3rem;
  padding: 1.5rem 0;
}

.nav-header a {
  color: var(--color-texto);
  font-size: 1.25rem;
  opacity: 0.4;
  transition: all 0.3s ease;
  margin-top: 15px;
}

.nav-header a:hover {
  opacity: 1;
  transform: scale(1.05);
}

@media (max-width: 768px) {
  .nav-header {
    gap: 1.5rem;
    padding: 1rem 0;
  }

  .nav-header a {
    font-size: 0.8rem;
    opacity: 0.6;
  }
}
</style>
