 <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RPL STAND</title>
    <link rel="stylesheet" href="style/sksd.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300..700&display=swap" rel="stylesheet">
    <style>

      .card{
        box-shadow: 1px 4px 8px 1px rgba(1, 2, 1, 0.2);
        border-radius: 2px;
        padding: 20px;
        background-color: transparent;
        position: sticky;
        max-width: 300px;
        margin: 0 auto;
      }
       nav {
      padding: 5px;
      position: fixed; 
      top: 0;
      width: 100%; 
      z-index: 1000;
       }
       nav ul{
        padding-inline: 4rem;
        display: flex;
        gap: 2rem;
       }
      nav a {
      font-size: 18px;
      font-weight: 400;
      text-decoration: none;
      color: aqua;
    }
      nav a:hover{
        font-weight: bold;
      }
      nav li{
        list-style-type: none;
      }
      .drop {
            display: none; 
            position: absolute; 
            top: 100%; 
            left: 0;
            background-color: #007b99;
            min-width: 150px;
            border-radius: 4px;
            z-index: 1;
      }
    </style>
  
</head>
  <body>
        <header>
          
          <nav>   
            <ul class="drop">
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    
        <!-- Main Content -->
        <main>
            <section id="products" class="card-container">
                <!-- Product Card 1 -->
                <div class="card">
                  <h3>Product 1</h3>
                    <img src="asset/img/web.png" alt="Product 1">
                    <p>deskripsi</p>
                    <a href="product1.html" class="btn">View Details</a>
                </div>
    
                <!-- Product Card 2 -->
                <div class="card">
                  <h3>Product 2</h3>
                    <img src="images/product2.jpg" alt="Product 2">
                    <p>deskripsi</p>
                    <a href="product2.html" class="btn">View Details</a>
                </div>
    
                <!-- Product Card 3 -->
                <div class="card">
                  <h3>Product 3</h3>
                    <img src="images/product3.jpg" alt="Product 3">
                    <p>deskripsi</p>
                    <a href="product3.html" class="btn">View Details</a>
                </div>
    
                <!-- Product Card 4 -->
                <div class="card">
                  <h3>Product 4</h3>
                    <img src="images/product4.jpg" alt="Product 4">
                    <p>deskripsi.</p>
                    <a href="product4.html" class="btn">View Details</a>
                </div>
            </section>
        </main>
  </body>
  </html>
