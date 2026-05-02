<template>
  <div>
    <section class="section">
      <div class="grid grid-2">
        <div class="hero-card">
          <div class="hero-visual" style="background-image: url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1300&q=80');"></div>
          <div class="hero-content">
            <div class="hero-copy">
              <h1 class="section-title">Designed for quiet luxury.</h1>
              <p class="section-copy">Curated homeware pieces that blend serene minimalist aesthetics with enduring quality. Transform your space into a grounded sanctuary.</p>
              <NuxtLink to="/shop" class="button-solid">Shop Now</NuxtLink>
            </div>
          </div>
        </div>
        <div class="grid grid-2" style="gap:24px;">
          <div class="card" style="background-image: url('https://images.unsplash.com/photo-1519710164239-da123dc03ef4?auto=format&fit=crop&w=1200&q=80'); background-size: cover; min-height: 260px;"></div>
          <div class="grid grid-2" style="grid-template-columns: 1fr 1fr; gap: 24px;">
            <div class="card" style="background-image: url('https://images.unsplash.com/photo-1549187774-b4e9b0445b63?auto=format&fit=crop&w=800&q=80'); background-size: cover; min-height: 124px;"></div>
            <div class="card" style="background-image: url('https://images.unsplash.com/photo-1519710164239-da123dc03ef4?auto=format&fit=crop&w=800&q=80'); background-size: cover; min-height: 124px;"></div>
          </div>
        </div>
      </div>
    </section>

  <section class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">Explore Categories</h2>
      </div>
      <NuxtLink to="/shop" class="button-outline">View All Categories</NuxtLink>
    </div>
    <div class="product-grid">
      <NuxtLink to="/shop" class="card">
        <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1200&q=80" alt="Furniture" />
        <div class="card-body">
          <p class="badge">Featured</p>
          <h3 class="card-title">Furniture</h3>
        </div>
      </NuxtLink>
      <NuxtLink to="/shop" class="card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80" alt="Kitchen" />
        <div class="card-body">
          <h3 class="card-title">Kitchen</h3>
        </div>
      </NuxtLink>
      <NuxtLink to="/shop" class="card">
        <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=1200&q=80" alt="Decor" />
        <div class="card-body">
          <h3 class="card-title">Decor</h3>
        </div>
      </NuxtLink>
      <NuxtLink to="/shop" class="card">
        <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1200&q=80" alt="Storage" />
        <div class="card-body">
          <h3 class="card-title">Storage</h3>
        </div>
      </NuxtLink>
    </div>
  </section>

  <section class="section">
    <div class="section-header" style="margin-bottom: 24px;">
      <h2 class="section-title">Best Sellers</h2>
    </div>
    <div class="product-grid">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1493666438817-866a91353ca9?auto=format&fit=crop&w=1200&q=80" alt="Lumina Table Lamp" />
        <div class="card-body">
          <div class="card-meta">
            <h3 class="card-title">Lumina Table Lamp</h3>
            <span>$145</span>
          </div>
          <p class="card-subtitle">Muted Sage / Ceramic</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80" alt="Aura Oak Side Table" />
        <div class="card-body">
          <div class="card-meta">
            <h3 class="card-title">Aura Oak Side Table</h3>
            <span>$280</span>
          </div>
          <p class="card-subtitle">Solid Oak / Natural</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1519710164239-da123dc03ef4?auto=format&fit=crop&w=1200&q=80" alt="Serene Linen Cushions" />
        <div class="card-body">
          <div class="card-meta">
            <h3 class="card-title">Serene Linen Cushions</h3>
            <span>$85</span>
          </div>
          <p class="card-subtitle">Set of 2 / Deep Slate</p>
        </div>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80" alt="Terracotta Vase" />
        <div class="card-body">
          <div class="card-meta">
            <h3 class="card-title">Terracotta Vase</h3>
            <span>$60</span>
          </div>
          <p class="card-subtitle">Matte Finish / Sand</p>
        </div>
      </div>
    </div>
  </section>
</div>
</template>
