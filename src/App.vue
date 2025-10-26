<template>
  <nav>
    <div class="container">
      <div class="nav-container">
        <div class="logo">
          <img src="./assets/purity-transparent.png" alt="Purity Smile">
          <i class="fa-solid fa-chevron-down"></i>
        </div>
        <div class="desktop-menu">
          <ul>
            <li><a href="#">Our Products</a></li>
            <li><a href="#">The Science</a></li>
            <li><a href="#">FAQs & Support</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
      </div>
      <div class="mobile-menu">
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
        <h2>Gentle on Gums, Tough on Plaque</h2>
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
        <h2>Expert-Backed Simplicity</h2>
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
          <div class="product-item-image">
            <img src="./assets/toothbrush.png" alt="The Bio-Taper Toothbrush">
          </div>
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
          <div class="product-item-image">
            <img src="./assets/floss.png" alt="Expanding HydroFloss">
          </div>
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
          <div class="product-item-image">
            <img src="./assets/mouthwash.png" alt="GumLine Guard Rinse">
          </div>
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
        <div class="logo-social">
          <img src="./assets/footer-logo.svg" alt="PuritySmile">
          <div class="social">
            <img src="./assets/social/icons8-facebook.svg " alt="Facebook">
            <img src="./assets/social/icons8-instagram.svg" alt="Instagram">
            <img src="./assets/social/icons8-linkedin.svg" alt="Linkedin">
          </div>
        </div>
        <div class="quick-links">
          <ul>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Our Team</a></li>
            <li><a href="#">Testimonials</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
          <ul>
            <li><a href="#">Careers</a></li>
            <li><a href="#">FAQs</a></li>
            <li><a href="#">Terms & Conditions</a></li>
            <li><a href="#">Privacy Policy</a></li>
          </ul>
        </div>
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

.nav-container .logo {
  display: flex;
}

.fa-chevron-down {
  display: none;
}

.mobile-menu {
  display: none;
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
  margin-left: 50pt;
  display: grid;
  gap: 20px;
  height: 80vh;
  align-content: center;
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
  font-family: 'Wix Madefor Display', sans-serif;
  background-color: #53A9B3;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 50pt;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  margin-top: 20px;
  width: 300px;
}

.key-features {
  background: linear-gradient(180deg, #F0FEFF 0%, #E6FDFF 60%, #B3E6E9 100%);
}

.key-features .container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  height: auto;
  padding: 100px 50px;
}

.key-feature-item {
  display: grid;
  align-content: space-between;
  padding: 20px;
}

.key-feature-item h2 {
  padding: 20px;
}

.key-feature-item img {
  max-width: 100%;
}

.products {
  background: #B3E6E9  url('./assets/ornament.svg');
  /* background: linear-gradient(180deg, #B3E6E9 0%, #E2F5F6 15%, #FFFFFF 26%, #98D3DA 91%, #6FC2CC 100%) url('./assets/ornament.svg'); */
  height: auto;
}

.product-header {
  padding: 50px 0;
}

.product-header h2 {
  font-size: 40px;
  line-height: 4pc;
} 

.product-header h2:first-child {
  font-size: 30px;
}

.product-header h2 span {
  color: #53A9B3;
}

.product-items {
  display: grid;
  margin: 0 80px;
}

.product-item {
  display: grid;
  grid-template-columns: 1fr 1.7fr;
  gap: 20px;
  background-color: #fff;
  padding: 50px;
  border-radius: 30pt;
  margin: 30px;
  box-shadow: 0px 0px 10px -3px rgba(0, 0, 0, 33%);
}

.product-item-image {
  display: flex;
  justify-content: flex-start;
}

.product-item-content {
  display: grid;
  text-align: left;
  align-items: center;
}

.product-item-content h3 {
  font-size: 30px;
  font-weight: 600;
  line-height: 1pc;
}

.product-item-content p {
  font-size: 16px;
  font-weight: 400;
}

.product-item-content .category {
  color: #90ABAD;
}

.product-item-content .description {
  margin-bottom: 20px;
}

.product-item-content .price {
  display: grid;
  gap: 10px;
}

.product-item-content .price .original-price {
  text-decoration: line-through;
  color: #BA4141;
}

.product-item-content .price .discounted-price {
  font-size: 30px;
  font-weight: 600;
}

.cta {
  background: #6FC2CC url('./assets/circle.svg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  display: grid;
  align-content: center;
}

.cta-container {
  display: grid;
  gap: 30px;
  align-items: center;
  justify-content: center;
  justify-items: center;
  margin: 100px;
}

.cta-container h2 {
  font-size: 40px;
  color: #fff;
}

.cta-container h2 span {
  color: #283D65;
}

.cta-container p {
  width: 55%;
}

.cta-container button {
  font-family: 'Wix Madefor Display', sans-serif;
  background-color: #283D65;
  color: #fff;
  border: none;
  padding: 10px 20px;
  border-radius: 50pt;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  margin-top: 20px;
  width: 300px;
}

footer {
  background: #F0FEFF url('./assets/line-circle.svg');
  /* height: 70vh; */
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.footer-container {
  display: flex;
  justify-content: space-between;
  padding: 5%;
}

.quick-links {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 100px;
  text-align: left;
  margin: 20px ;
  justify-content: space-between;
}

.quick-links ul {
  display: grid;
  gap: 20px;
  height: 0;
}

.quick-links li {
  list-style: none;
}

.quick-links ul li a {
  text-decoration: none;
  color: #283D65;
}

.logo-social .social img {
    width: 30px;
  }

/* Responsive Styles for Mobile Devices */
@media screen and (max-width: 768px) {
  .container {
    padding: 0 20px;
  }

  /* Navigation */
  .nav-container {
    flex-direction: column;
    margin: 10px;
    padding: 15px;
    /* border-radius: 20px; */
  }

  .nav-container .logo {
    /* margin: 0 0 15px 0; */
    width: 120px;
  }

  .nav-container ul {
    flex-direction: column;
    gap: 15px;
    width: 100%;
  }

  .nav-container ul li {
    margin-right: 0;
    width: 100%;
    text-align: center;
  }

  .nav-container ul li:last-child {
    padding: 12px 20px;
  }

  .fa-chevron-down {
    display: flex;
    align-items: center;
    margin: 10px;
  }

  ul {
    display: block;
  }

  /* Hero Section */
  .hero {
    height: auto;
    min-height: 100vh;
    padding: 80px 0 50px 0;
  }

  .hero-container {
    margin-left: 0;
    max-width: 100%;
    padding: 20px;
    height: auto;
    min-height: 70vh;
  }

  .hero-container h1 {
    font-size: 38px;
    line-height: 1.2;
  }

  .hero-container p {
    font-size: 14px;
  }

  .hero-container button {
    width: 100%;
    max-width: 300px;
  }

  .mobile-menu {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin: 10px;
  }

  .desktop-menu {
    display: none;
  }

  /* Key Features */
  .key-features .container {
    grid-template-columns: 1fr;
    padding: 50px 20px;
    gap: 30px;
  }

  .key-feature-item {
    padding: 15px;
  }

  .key-feature-item h2 {
    font-size: 22px;
    padding: 15px 0;
  }

  .key-feature-item p {
    font-size: 14px;
  }

  /* Products Section */
  .product-header {
    padding: 30px 20px;
  }

  .product-header h2 {
    font-size: 28px;
    line-height: 1.4;
  }

  .product-header h2:first-child {
    font-size: 20px;
  }

  .product-items {
    margin: 0 20px;
  }

  .product-item {
    grid-template-columns: 1fr;
    padding: 30px 20px;
    margin: 20px 0;
    border-radius: 20px;
  }

  .product-item-image {
    justify-content: center;
  }

  .product-item-image img {
    max-width: 200px;
  }

  .product-item-content {
    text-align: center;
    gap: 15px;
  }

  .product-item-content h3 {
    font-size: 24px;
    line-height: 1.3;
  }

  .product-item-content p {
    font-size: 14px;
  }

  .product-item-content .price .discounted-price {
    font-size: 24px;
  }

  /* CTA Section */
  .cta-container {
    margin: 50px 20px;
    gap: 20px;
  }

  .cta-container h2 {
    font-size: 28px;
  }

  .cta-container p {
    width: 90%;
    font-size: 14px;
  }

  .cta-container button {
    width: 100%;
    max-width: 300px;
  }

  /* Footer */
  .footer-container {
    flex-direction: column;
    padding: 30px 20px;
    gap: 30px;
  }

  .logo-social {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }

  .logo-social img {
    max-width: 35px;
  }

  .social {
    display: flex;
    gap: 20px;
  }

  .quick-links {
    grid-template-columns: 1fr;
    gap: 30px;
    text-align: center;
    margin: 0;
  }

  .quick-links ul {
    gap: 15px;
  }
}

/* Extra Small Devices */
@media screen and (max-width: 480px) {

  .nav-container ul {
    display: flex;
  }

  .mobile-menu {
    display: flex;
    flex-direction: column;
    gap: 10px;
    margin: 10px;
    display: none;
    background-color: #fff;
  }

  .desktop-menu {
    display: none;
  }

  .mobile-menu ul li{
    list-style: none;
    padding: 10px;
  }

  .mobile-menu ul li a {
    text-decoration: none;
    color: #283D65;
  }

  .hero-container h1 {
    font-size: 45px;
  }

  .product-header h2 {
    font-size: 24px;
  }

  .product-header h2:first-child {
    font-size: 18px;
  }

  .cta-container h2 {
    font-size: 24px;
  }

  .product-item {
    padding: 20px 15px;
  }
}
</style>
