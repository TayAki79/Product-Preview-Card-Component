### Creating the Mobile Version first

1. Set up the head element with the necessary inputs
  ```
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Frontend Mentor | Product preview card component</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  ```

2. Set up the global variables in style.css
  - :root colors and font-sizes
  - universal selector
  - body

3. Writing down the html markup for the body part
  ```
  <main class="container">
    <img src="./images/image-product-mobile.jpg" alt="product image" >
    <p class="preview">Preview</p>

    <h1 class="title">Gabrielle Essence Eau De Parfum</h1>
  
    <p class="desc">
      A floral, solar and voluptuous interpretation composed by Olivier Polge,
      Perfumer-Creator for the House of CHANEL.
    </p>
  
    <p class="sale-price">$149.99</p>
    <p class="regular-price">$169.99</p>
  
    <button class="add-to-cart">Add to Cart</button>
    
  </main>
  <footer>
    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">AkraDEV</a>.
    </div>
  </footer> 
  ```