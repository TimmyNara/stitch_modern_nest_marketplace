<template>
  <section class="section">
    <div class="section-title">Curated Collection</div>
    <p class="section-copy">Timeless pieces designed for a sanctuary home.</p>
    <div class="grid" style="grid-template-columns: 1fr; gap: 24px; margin-top: 32px;">
      <div class="form-card">
        <div class="text-overline">Search & Sort</div>
        <div class="field-group" style="margin-top: 16px;">
          <input type="search" placeholder="Search collection..." />
          <select>
            <option>Sort by: Featured</option>
            <option>Price: Low to High</option>
            <option>Price: High to Low</option>
          </select>
        </div>
      </div>
      <div class="grid-2" style="gap: 24px;">
        <div class="panel">
          <div class="text-overline">Category</div>
          <div class="field-group" style="margin-top: 18px;">
            <label><input type="checkbox" checked /> Furniture</label>
            <label><input type="checkbox" checked /> Ceramics & Decor</label>
            <label><input type="checkbox" /> Lighting</label>
            <label><input type="checkbox" /> Textiles</label>
          </div>
          <div class="text-overline" style="margin-top: 24px;">Price</div>
          <div class="field-group" style="margin-top: 18px;">
            <label><input type="radio" name="price" checked /> Under $100</label>
            <label><input type="radio" name="price" /> $100 - $500</label>
            <label><input type="radio" name="price" /> $500 - $1000</label>
            <label><input type="radio" name="price" /> Over $1000</label>
          </div>
          <div class="text-overline" style="margin-top: 24px;">Condition</div>
          <div class="field-group" style="margin-top: 18px;">
            <label><input type="checkbox" checked /> New Artifacts</label>
            <label><input type="checkbox" /> Restored Vintage</label>
          </div>
        </div>
        <div class="product-grid">
          <NuxtLink to="/product" class="card">
            <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=1200&q=80" alt="Asymmetric Bone Vase" />
            <div class="card-body">
              <div class="card-meta">
                <h3 class="card-title">Asymmetric Bone Vase</h3>
                <span>$145</span>
              </div>
              <p class="card-subtitle">Hand-thrown stoneware</p>
            </div>
          </NuxtLink>
          <NuxtLink to="/product" class="card">
            <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80" alt="Ash & Sage Lounge" />
            <div class="card-body">
              <div class="card-meta">
                <h3 class="card-title">Ash & Sage Lounge</h3>
                <span>$890</span>
              </div>
              <p class="card-subtitle">Solid wood frame</p>
            </div>
          </NuxtLink>
          <NuxtLink to="/product" class="card">
            <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1200&q=80" alt="Eclipse Floor Lamp" />
            <div class="card-body">
              <div class="card-meta">
                <h3 class="card-title">Eclipse Floor Lamp</h3>
                <span>$420</span>
              </div>
              <p class="card-subtitle">Blackened steel & glass</p>
            </div>
          </NuxtLink>
          <NuxtLink to="/product" class="card">
            <img src="https://images.unsplash.com/photo-1519710164239-da123dc03ef4?auto=format&fit=crop&w=1200&q=80" alt="Organic Linen Throw" />
            <div class="card-body">
              <div class="card-meta">
                <h3 class="card-title">Organic Linen Throw</h3>
                <span>$115</span>
              </div>
              <p class="card-subtitle">100% European linen</p>
            </div>
          </NuxtLink>
        </div>
      </div>
    </div>
  </section>
</template>
