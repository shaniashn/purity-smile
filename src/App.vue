<template>
  <nav>
    <div class="container">
      <div class="nav-container">
        <div class="logo">
          <img src="./assets/purity-transparent.png" alt="Purity Smile">
        </div>
        <ul>
          <li><a href="#">Our Products</a></li>
          <li><a href="#">The Science</a></li>
          <li><a href="#">FAQs & Support</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero">
    <div class="container">
      <div class="hero-container">
        <h1>Your Health Starts With a <span>Brilliant Smile.</span></h1>
        <p>Designed by dental experts, our line of floss, brushes, and specialized care products transforms your routine
          from a chore into a foundation for total well-being. Feel the difference of true clean.</p>
        <button>→ Explore the Full Collection</button>
      </div>
    </div>
  </section>
  <section class="key-features">
    <div class="container">
      <div class="key-feature-item">
        <img src="./assets/features-item-1.png" alt="Key Feature 1">
        <h2>Gentle on Gums, Tough on Plaque.</h2>
        <p>Our proprietary tapered filaments reach deep between teeth and along the gumline without the abrasive force
          that causes recession and sensitivity. Brush better, not harder.</p>
      </div>
      <div class="key-feature-item">
        <img src="./assets/features-item-2.png" alt="Key Feature 2">
        <h2>A Floss You’ll Actually Look Forward To Using</h2>
        <p>Forget painful snapping and shredding. Our silk-smooth, expanding floss glides effortlessly, collecting
          debris and leaving a refreshing minty-clean feeling you can genuinely sense.</p>
      </div>

      <div class="key-feature-item">
        <img src="./assets/features-item-3.png" alt="Key Feature 3">
        <h2>Expert-Backed Simplicity.</h2>
        <p>Stop guessing in the aisle. Every PuritySmile product is recommended by practicing dentists, ensuring that
          you’re using the safest and most effective tools for your unique oral health needs.</p>
      </div>
    </div>
  </section>
  <section class="products">
    <div class="container">
      <div class="product-header">
        <h2>The Essentials:</h2>
        <h2>Our Customer <span>Favorites!</span></h2>
      </div>
      <div class="product-items">
        <div class="product-item">
          <img src="./assets/toothbrush.png" alt="The Bio-Taper Toothbrush">
          <div class="product-item-content">
            <h3>The Bio-Taper Toothbrush</h3>
            <p class="category">Biodegradable Daily Care</p>
            <p class="description">The Bio-Taper Toothbrush features ultra-fine, tapered filaments that reach deep below
              the gumline and between teeth for a superior clean, all while using a handle crafted from sustainable,
              biodegradable materials.</p>
            <div class="price">
              <span class="original-price">$10.99</span>
              <span class="discounted-price">$7.99</span>
            </div>
          </div>
        </div>
        <div class="product-item">
          <img src="./assets/floss.png" alt="Expanding HydroFloss">
          <div class="product-item-content">
            <h3>Expanding HydroFloss</h3>
            <p class="category">Deep-Cleaning Floss</p>
            <p class="description">The Expanding HydroFloss is engineered with smart fibers that expand when wet, gently
              filling the entire space between teeth for a superior surface clean. It glides smoothly without shredding
              and is designed to lift plaque and debris, turning painful, inconsistent flossing into an easy, essential
              part of your routine.</p>
            <div class="price">
              <span class="original-price">$7.50</span>
              <span class="discounted-price">$4.50</span>
            </div>
          </div>
        </div>
        <div class="product-item">
          <img src="./assets/mouthwash.png" alt="GumLine Guard Rinse">
          <div class="product-item-content">
            <h3>GumLine Guard Rinse</h3>
            <p class="category">Specialized Care</p>
            <p class="description">GumLine Guard Rinse alcohol-free formula uses a targeted blend of natural extracts
              and dental-grade active ingredients to soothe sensitive gums and create a protective barrier. Use it daily
              as the final step in your routine to reduce inflammation, prevent irritation, and support long-term gum
              health.</p>
            <div class="price">
              <span class="original-price">$16.50</span>
              <span class="discounted-price">$12.95</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="cta">
    <div class="container">
      <div class="cta-container">
        <h2>Stay Informed. <span>Live Well.</span></h2>
        <p>Get exclusive tips from our team of dental health experts and be the first to know about new products.</p>
        <button>→ Subscribe to Our Newsletter</button>
      </div>
    </div>
  </section>
  <footer>
    <div class="container">
      <div class="footer-container">
        <h2>PuritySmile</h2>
      </div>
    </div>
  </footer>

</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
:root {
  --text-color: #283D65;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'Wix Madefor Display', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--text-color);
}

nav {
  color: var(--text-color);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}

.logo {
  width: 150px;
}

.logo img {
  width: 100%;
  height: 100%;
}

.nav-container {
  background-color: #fff;
  margin: 20px;
  padding: 10px;
  border-radius: 75pt;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-container h1 {
  font-size: 24px;
  font-weight: bold;
}

.nav-container .logo {
  margin: 0 30px;
}

.nav-container ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
  justify-content: center;
  align-items: center;
}

.nav-container ul li {
  margin-right: 50px;
  justify-content: center;
  align-items: center;
}

.nav-container ul li a {  
  color: #283D65;
  text-decoration: none;
}

.nav-container ul li:last-child {
  padding: 15px 28px;
  background-color: #53A9B3;
  border-radius: 50pt;
}

.nav-container ul li:last-child:hover {
  background-color: #1f8c98;
  box-sizing: border-box;
  transition: all 0.3s ease;
  cursor: pointer;
}

.nav-container ul li:last-child a {
  color: #fff;
}

.nav-container ul li:last-child:hover a {
  color: #fff;
  transition: all 0.3s ease;
}

.nav-container ul li a:hover {
  color: #26818b;
  transition: all 0.3s ease;
}

.hero {
  background-color: #f0f0f0;
  padding: 100px 0;
  background-image: url('./assets/hero-banner.png');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  height: 100vh;
  width: 100%;
}

.hero-container {
  text-align: left;
  max-width: 600px;
  justify-self: left;
  margin-left: 90pt;
}

.hero-container h1 {
  font-size: 70px;
  font-weight: 700;
}

.hero-container h1 span {
  color: #53A9B3;
}

.hero-container p {
  font-size: 16px;
  font-weight: 400;
}

.hero-container button {
  background-color: #53A9B3;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 50pt;
  font-size: 16px;
  font-weight: 400;
  cursor: pointer;
  margin-top: 20px;
}

.key-features {
  background: linear-gradient(180deg, #F0FEFF 0%, #E6FDFF 60%, #B3E6E9 100%);
}

.key-features .container {
  padding: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.products {
  background: linear-gradient(180deg, #B3E6E9 0%, #E2F5F6 15%, #FFFFFF 26%, #98D3DA 91%, #6FC2CC 100%), url('./assets/ornament.svg');
}

.cta {
  height: 70vh;
  background: #6FC2CC url('./assets/circle.svg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

footer {
  background: #F0FEFF url('./assets/line-circle.svg');
  height: 70vh;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

/* Responsive Styles */
/* @media screen and (max-width: 1024px) {
  .nav-container ul li {
    margin-right: 15px;
  }

  .nav-container ul li a {
    font-size: 14px;
  }
}

@media screen and (max-width: 768px) {
  .nav-container {
    margin: 15px;
    padding: 8px 15px;
  }

  .logo {
    width: 120px;
  }

  .nav-container ul li {
    margin-right: 10px;
  }

  .nav-container ul li a {
    font-size: 12px;
  }
}

@media screen and (max-width: 640px) {
  .nav-container {
    margin: 10px;
    padding: 8px 12px;
    border-radius: 50pt;
  }

  .logo {
    width: 100px;
  }

  .nav-container ul {
    flex-direction: column;
    align-items: flex-end;
    gap: 8px;
  }

  .nav-container ul li {
    margin-right: 0;
  }

  .nav-container ul li a {
    font-size: 11px;
  }
}

@media screen and (max-width: 480px) {
  .nav-container {
    flex-direction: column;
    gap: 10px;
    padding: 12px;
    text-align: center;
  }

  .logo {
    width: 80px;
  }

  .nav-container ul {
    align-items: center;
    gap: 6px;
  }

  .nav-container ul li a {
    font-size: 10px;
  }
} */

</style>
