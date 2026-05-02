<template>
  <section class="section grid grid-2" style="gap: 32px;">
    <div>
      <h1 class="section-title">Your Cart</h1>
      <div class="panel" style="display: grid; gap: 24px;">
        <div class="checkout-row" style="gap: 16px; align-items: center;">
          <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=280&q=80" alt="Hand-Thrown Ceramic Vase" style="width: 110px; border-radius: 20px; object-fit: cover;" />
          <div>
            <h3 class="card-title">Hand-Thrown Ceramic Vase</h3>
            <p class="card-subtitle">Muted Sage • Medium</p>
          </div>
          <span>$120.00</span>
        </div>
        <div class="checkout-row" style="gap: 16px; align-items: center;">
          <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=280&q=80" alt="Woven Linen Throw" style="width: 110px; border-radius: 20px; object-fit: cover;" />
          <div>
            <h3 class="card-title">Woven Linen Throw</h3>
            <p class="card-subtitle">Bone White • Standard</p>
          </div>
          <span>$185.00</span>
        </div>
        <div class="panel" style="background: #f4f3f1;">
          <p class="card-subtitle">Your order qualifies for complimentary premium shipping. Expected delivery is within 3-5 business days.</p>
        </div>
      </div>
    </div>
    <aside class="panel">
      <h2 class="section-title">Order Summary</h2>
      <div class="checkout-card">
        <div class="checkout-row"><span>Subtotal (3 items)</span><strong>$490.00</strong></div>
        <div class="checkout-row"><span>Shipping</span><span>Complimentary</span></div>
        <div class="checkout-row"><span>Estimated Tax</span><strong>$41.65</strong></div>
        <div class="checkout-row checkout-total"><span>Total</span><strong>$531.65</strong></div>
      </div>
      <div class="form-card" style="margin-top: 24px;">
        <div class="text-overline">Contact Information</div>
        <input type="email" placeholder="you@example.com" />
      </div>
      <div class="form-card" style="margin-top: 16px;">
        <div class="text-overline">Shipping Address</div>
        <div class="field-group" style="margin-top: 16px;">
          <input type="text" placeholder="First Name" />
          <input type="text" placeholder="Last Name" />
          <input type="text" placeholder="Street Address" />
          <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 16px;">
            <input type="text" placeholder="City" />
            <input type="text" placeholder="ZIP / Postal Code" />
          </div>
        </div>
      </div>
      <div class="form-card" style="margin-top: 16px;">
        <div class="text-overline">Payment Method</div>
        <div class="field-group" style="margin-top: 16px;">
          <input type="text" placeholder="Card Number" value="0000 0000 0000 0000" />
          <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 16px;">
            <input type="text" placeholder="MM/YY" />
            <input type="text" placeholder="CVC" />
          </div>
        </div>
        <button class="button-solid cta-button" style="margin-top: 24px;">Place Order • $531.65</button>
      </div>
    </aside>
  </section>
</template>
