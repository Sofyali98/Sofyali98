</doctype/><html lang="en">

<head>welcome to mode huset.
    
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML with External JavaScript</title>
    <script src=functional data
    

// Function to display products on the webpage
function displayProducts() {
  const section = document.querySelector("section");

  products.forEach((product) => {
    const productDiv = document.createElement("div");
    productDiv.classList.add("product");

    const image = document.createElement("img");
    image.src = `product${product.id}.jpg`;
    image.alt = product.name;

    const name = document.createElement("h3");
    name.textContent = product.name;

    const price = document.createElement("p");
    price.textContent = `Price: $${50}`;

    const button = document.createElement("button");
    button.textContent = "Add to Cart";
    button.addEventListener("click", () => {
      addToCart(product);
    });
      //Function to add product to cart on the webpage
      function addproducttocart (1) 
      const section = document.querySelector("section");

  products.forEach((product) => {
    const productDiv = document.createElement("div");
    productDiv.classList.add("product");

    const image = document.createElement("img");
    image.src = `product${product.id}.jpg`;
    image.alt = product.name;

    const name = document.createElement("h3");
    name.textContent = product.name;

    const price = document.createElement("p");
    price.textContent = `Price: $${50}`;

    const button = document.createElement("button");
    button.textContent = "Add to Cart";
    button.addEventListener("click", () => {
        
        productDiv.appendChild(image);
    productDiv.appendChild(name);
    productDiv.appendChild(price);
    productDiv.appendChild(button);

    section.appendChild(productDiv);
  });
}

// Function to add a product to the cart//
function addToCart(product) {
  console.log(`Added ${dress 1} to cart.`);
    console.log(`Added ${dress 2} to cart.`);
    console.log(`Added ${dress 3} to cart.`);
          // Here you would implement the logic to add the product to the cart
  // For example, you could store the selected products in an array or object
  // and update the UI to display the cart contents
}

// Call the displayProducts function when the page loads
document.addEventListener("DOMContentLoaded", displayProducts);
>1</script>const products = [
  { id: 1, name: "dress ", price: },
  { id: 2, name: "green dress", price: },
  { id: 3, name: dress, price: }
];

    
</head>
<body>
    <h1></h1>
    
    <button onclick="myFunction()">Click Me</button>
</body>
</html>
  <title>mode huset online shop</title>
  <style>
    /* google chrome */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: <link rel= "stylesheet" href=
    "https://fonts.googleapis.com/css?family=Roboto:400,400i,700" >;
  background-color: #f5f5f5;
  margin: 0;
  padding: 0;
}

header {
  background-color: #444;
  color: #fff;
  padding: 20px;
  text-align: center;
}

nav {
  background-color: #666;
  color: #fff;
  padding: 10px;
  text-align: center;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 10px;
}

section {
  padding: 20px;
  margin: 20px;
  background-color: #fff;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.product {
  width: 30%;
  margin-bottom: 20px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

.product img {
  max-width: 100%;
  height: auto;
}

footer {
  background-color: #888;
  color: #fff;
  padding: 10px;
  text-align: center;
  position: fixed;
  bottom: 0;
  width: 100%;
}
*/
    body
    }

    font-family: Arial,
    sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    }

    header {
      background-color: #2962FF;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #668;
      color: #background-image;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: #BCAAA4;
      text-decoration: none;
      margin: 0 10px;
    }

    section {
      padding: 20px;
      margin: 20px;
      background-color: #fff;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .product {
      width: 30%;
      margin-bottom: 20px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
    }

    .product img {
      max-width: 100%;
      height: auto;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 10px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>

<body>
  <header>
    <h1>Mode huset Online Shop</h1>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Cart</a>
    <a href="#">Contact</a>
  </nav>
  <sec <div class="product">
    <img src="https://images.unsplash.com/photo-1558478800-0116c075b88d?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MTM4OTIyNzh8&ixlib=rb-4.0.3&q=85" alt="Product 1">
    <h3>dress 1</h3>
    <p>ss 24 collection </p>
    <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1657447771319-18dbf899c9b8?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MTM4OTI5NzJ8&ixlib=rb-4.0.3&q=85" alt="Product 2">
      <h3>green dress 2</h3>
      <p>flowy green dress ss24 collection</p>
      <button>Add to Cart</button>
    </div>

    <!-- Add more product divs as needed -->
    </section>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1524171275909-a99941df2e5a?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MTM4OTUwMTZ8&ixlib=rb-4.0.3&q=85 alt=" Product 3">
      <h3>traditional wear </h3>
      <p>green classy tradtional dress 3</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1649109670237-31fcefbac2b6?crop=entropy&cs=srgb&fm=jpg&ixid=M3wzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MTM4OTI5NzJ8&ixlib=rb-4.0.3&q=85" alt="Product 4">
      <h3>Product 4</h3>
      <p>green traditional dress 4</p>
      <button>Add to Cart</button>
    </div>
    <footer>

      <p>&copy; 2024 Online Shop. All rights reserved.</p>
    </footer>
</body>

</html>
  
