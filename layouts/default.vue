<template>
  <div class="page-shell">
    <header class="site-header">
      <div class="nav-bar">
        <div class="nav-links hidden-md">
          <NuxtLink to="/shop" class="nav-link">Shop</NuxtLink>
          <NuxtLink to="/sell" class="nav-link">Sell</NuxtLink>
          <NuxtLink to="/about" class="nav-link">About</NuxtLink>
          <NuxtLink to="/contact" class="nav-link">Contact</NuxtLink>
        </div>
        <NuxtLink to="/" class="brand">Aura Home</NuxtLink>
        <div class="nav-actions">
          <NuxtLink to="/search" class="icon-button" aria-label="Search">
            <span class="material-symbols-outlined">search</span>
          </NuxtLink>
          <NuxtLink to="/cart" class="icon-button" aria-label="Cart">
            <span class="material-symbols-outlined">shopping_cart</span>
          </NuxtLink>
          <NuxtLink to="/account" class="icon-button" aria-label="Account">
            <span class="material-symbols-outlined">person</span>
          </NuxtLink>
        </div>
      </div>
    </header>

    <main class="page-content">
      <NuxtPage />
    </main>

    <footer class="site-footer">
      <div>Aura Home</div>
      <div class="footer-links">
        <NuxtLink to="/">Sustainability</NuxtLink>
        <NuxtLink to="/">Shipping & Returns</NuxtLink>
        <NuxtLink to="/">Privacy Policy</NuxtLink>
        <NuxtLink to="/">Store Locator</NuxtLink>
      </div>
      <div class="footer-copy">© 2024 Aura Home. Designed for quiet luxury.</div>
    </footer>
  </div>
</template>
