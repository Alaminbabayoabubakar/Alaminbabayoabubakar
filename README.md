- 👋 Hi, I’m @Alaminbabayoabubakar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Alaminbabayoabubakar/Alaminbabayoabubakar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alamin Market</title>
    <link rel="icon" href="image/A3.jpg" type="icon" id="home" border-radius="50%">
    <style>
        /* Global Styles */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #000000;
            background-color: #f9f9f9;
        }
                    
                    
        /* Header Styles */
        header {
            background-color: #512bff;
            color: #fff;
            padding: 1em;
            text-align: center;
            font-weight: bold;
          
        }
        
        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-between;
        }
        
        header nav ul li {
            margin-right: 30px;
        }
        
        header nav a {
            color: #fff;
            text-decoration: none;
        }
        
        /* Search Bar Styles */
        .search-bar {
            background-color: #f0f0f0;
            padding: 1em;
            display: flex;
            justify-content: center;
        }
        
        .search-bar form {
            display: flex;
        }
        
        #search-input {
            width: 100%;
            padding: 10px;
            font-size: 16px;
         border: 1px solid #512bff;
            border-radius: 5px 0 0 5px;
        }
        
        #search-btn {
            background-color: #512bff;
            color: #fff;
            border: none;
            padding: 10px;
            font-size: 16px;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
        }
        
        /* Hero Styles */
        .hero {
            background-image: linear-gradient(to bottom, #512bff, #512bff);
            background-size: 100% 300px;
            background-position: 0% 100%;
            height: 300px;
            justify-content: center;
            align-items: center;
            color: #fff;
        }
        
        .hero h1 {
            font-size: 46px;
        }
        
        /* Product List Styles */
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .product {
            background-color: #fff;
            margin: 20px;
            padding: 20px;
            border: 1px solid #512bff;
            width: calc(25% - 40px);
        }
        
        .product img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        
        .product h3 {
            font-size: 18px;
            margin-bottom: 10px;
        }
        
        .product p {
            font-size: 16px;
            margin-bottom: 20px;
        }
        
.add-to-cart {
         background-color: #512bff;
         color: #fff;
         border: none;
         padding: 10px 20px;
         font-size: 16px;
         cursor: pointer;
        }
        
        /* Cart Styles */
        .cart-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .cart-item {
            background-color: #fff;
            margin: 20px;
            padding: 20px;
            border: 1px solid #512bff;
            width: calc(50% - 40px);
        }
        
        .cart-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        
        .cart-item h3 {
            font-size: 18px;
            margin-bottom: 10px;
        }
        
        .cart-item p {
            font-size: 16px;
            margin-bottom: 20px;
        }
        button { [Class="add-to-cart"]
        background-color:#512bff;
         color: #512bff;
         border:2px solid#512bff;
         padding: 10px 20px;
         font-size: 16px;
         cursor: pointer;
        }
            /* Checkout Styles */
    .checkout {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
    
    .checkout form {
        display: flex;
    }
    
    .checkout label {
        margin-bottom: 10px;
        font-weight: bold;
    }
    
    .checkout input {
        width: 100%;
        padding: 10px;
        font-size: 16px;
        border: none;
        border-radius: 5px;
        margin-bottom: 20px;
    }
    
    .checkout button {
        background-color: #512bff;
        color: #fff;
        padding: 10px 20px;
        border: none;
        cursor: pointer;
    }
    
    /* Footer Styles */
    footer {
        background-color: #512bff;
        color: #fff;
        padding: 1em;
        text-align: center;
        clear: both;
    }
</style>
</head>

<body>
<header>
<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#products">Products</a></li>
<li><a href="#cart">Cart</a></li>
<li><a href="#checkout">Checkout</a></li>
</ul>
</nav>
</header>
<!-- Home Section -->
<section id="home">
    <div class="hero">
        <center><h1>Welcome to Alamin Market</h1>
       <h3> <p>Shop from our vast collection of products</p></h3>
        <button style="background-color: #fff;color: #512bff;padding: 10px 20px;border: none;cursor: pointer;">Explore Now</button></center>
    </div>

    <!-- Search Bar Section -->
    <section class="search-bar">
        <h2>Search products</h2>
        <form id="search-form">
            <input type="text" id="search-input" placeholder="Search...">
            <button id="search-btn">Search</button>
        </form>
        <div id="search-results"></div>
    </section>
    <section class="product-list">
        <div class="product-container">
            <!-- Product list will be generated dynamically -->
        </div>
    </section>
</section>

<!-- Products Section -->
<section id="products">
    <h1>Products</h1>
    <div class="product-container">
        <div class="product">
           <a href="image/W.jpg"><img src="image/W.jpg" alt="SmartWatch X5000"></a>
            <h3>SmartWatch X5000</h3>
            <p>$8.19</p>
            <button class="add-to-cart" data-product-id="1" data-product-name="SmartWatch X5000" data-product-price="8.19" data-product-image="image/W.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/W2.jpg"><img src="image/W2.jpg" alt="SmartWatch X5001"></a>
            <h3>SmartWatch X5001</h3>
            <p>$8.99</p>
            <button class="add-to-cart" data-product-id="2" data-product-name="SmartWatch X5001" data-product-price="8.99" data-product-image="image/W2.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/rice.jpeg"><img src="image/rice.jpeg" alt="Rice"></a>
            <h3>Rice</h3>
            <p>$2.99</p>
            <button class="add-to-cart" data-product-id="3" data-product-name="Rice" data-product-price="2.99" data-product-image="image/rice.jpeg">Add to Cart</button>
        </div>
        <div class="product">
           <a href="image/be.jpeg"> <img src="image/be.jpeg" alt="Beans"></a>
            <h3>Beans</h3>
            <p>$2.99</p>
            <button class="add-to-cart" data-product-id="4" data-product-name="Beans" data-product-price="1.55" data-product-image="image/be.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/M.jpg"><img src="image/M.jpg" alt="Manja"></a>
            <h3>Manja</h3>
            <p>$1.29</p>
            <button class="add-to-cart" data-product-id="5" data-product-name="Manja" data-product-price="1.29" data-product-image="image/M.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Mg.jpeg"><img src="image/Mg.jpeg" alt="Groundnt oil"></a>
            <h3>Groundnt oil</h3>
            <p>$1.30</p>
            <button class="add-to-cart" data-product-id="6" data-product-name="Groundnt oil" data-product-price="1.30" data-product-image="image/Mg.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Mz.jpeg"><img src="image/Mz.jpeg" alt="Maize"></a>
            <h3>Maize</h3>
            <p>$0.99</p>
            <button class="add-to-cart" data-product-id="7" data-product-name="Maize" data-product-price="0.99" data-product-image="image/Mz.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/pure.jpeg"><img src="image/pure.jpeg" alt="Pure Water"></a>
            <h3>Pure Water</h3>
            <p>$0.10</p>
            <button class="add-to-cart" data-product-id="8" data-product-name="Pure Water" data-product-price="0.10" data-product-image="image/pure.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ms.jpeg"><img src="image/Ms.jpeg" alt="Milo Sachet"></a>
            <h3>Milo Sachet</h3>
            <p>$2.99</p>
            <button class="add-to-cart" data-product-id="9" data-product-name="Milo Sachet" data-product-price="0.20" data-product-image="image/Ms.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Milo2.jpeg"><img src="image/Milo2.jpeg" alt="Milo Metal"></a>
            <h3>Milo Metal</h3>
            <p>$2.99</p>
            <button class="add-to-cart" data-product-id="10" data-product-name="Milo Metal" data-product-price="2.80" data-product-image="image/Milo2.jpeg">Add to Cart</button>
        </div>
        <div class="product">
           <a href="image/ice2.jpeg"> <img src="image/ice2.jpeg" alt="Ice"></a>
            <h3>Ice</h3>
            <p>$0.19</p>
            <button class="add-to-cart" data-product-id="11" data-product-name="Ice" data-product-price="0.19" data-product-image="image/ice2.jpeg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/boo.jpeg"><img src="image/boo.jpeg" alt="Books"></a>
            <h3>Books</h3>
            <p>$1.50</p>
            <button class="add-to-cart" data-product-id="12" data-product-name="Books" data-product-price="1.50" data-product-image="image/boo.jpeg">Add to Cart</button>
        </div>
        <div class="product">
           <a href="image/cpu.jpeg"> <img src="image/cpu.jpeg" alt="System Unit"></a>
            <h3>System Unit</h3>
            <p>$23.99</p>
            <button class="add-to-cart" data-product-id="13" data-product-name="System Unit" data-product-price="23.80" data-product-image="image/cpu.jpeg">Add to Cart</button>
        </div>
        <div class="product">
           <a href="image/tv.jpeg"> <img src="image/tv.jpeg" alt="Television"></a>
            <h3>Television</h3>
            <p>$20.50</p>
            <button class="add-to-cart" data-product-id="14" data-product-name="Television" data-product-price="20.50" data-product-image="image/tv.jpeg">Add to Cart</button>
        </div>
        <div class="product">
           <a href="image/C1.webp"> <img src="image/C1.webp" alt="Clothing"></a>            <h3>Clothing</h3>
            <p>$5.80</p>
            <button class="add-to-cart" data-product-id="15" data-product-name="Clothing" data-product-price="5.80" data-product-image="image/C1.webp">Add to Cart</button>
        </div>
        <div class="product">
 <a href="image/C2.webp"><img src="image/C2.webp" alt="Clothing"></a>
            <h3>Clothing</h3>
            <p>$6.82</p>
           <button class="add-to-cart" data-product-id="16" data-product-name="Clothing" data-product-price="6.82" data-product-image="image/C2.webp" >Add to Cart</button>
        </div>  
        <div class="product">            <a href="image/Ho1.jpg"><img src="image/Ho1.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland 1</h3>
            <p>$18.18</p>
            <button class="add-to-cart" data-product-id="17" data-product-name="Segi Holland" data-product-price="18.18" data-product-image="image/Ho1.jpg">Add to Cart</button>
        </div>
        <div class="product">            <a href="image/Ho2.jpg"><img src="image/Ho2.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland</h3>
            <p>$18.17</p>
            <button class="add-to-cart" data-product-id="18" data-product-name="Segi Holland" data-product-price="18.17" data-product-image="image/Ho2.jpg">Add to Cart</button>
        </div>
        <div class="product">            <a href="image/Ho3.jpg"><img src="image/Ho3.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland 3</h3>
            <p>$18.16</p>
            <button class="add-to-cart" data-product-id="19" data-product-name="Segi Holland" data-product-price="18.16" data-product-image="image/Ho3.jpg">Add to Cart</button>
        </div>
       <div class="product">
            <a href="image/Ho4.jpg"><img src="image/Ho4.jpg" alt="Segi Holland 4"></a>
            <h3>Segi Holland</h3>
            <p>$18.15</p>
            <button class="add-to-cart" data-product-id="20" data-product-name="Segi Holland 4" data-product-price="18.15" data-product-image="image/Ho4.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ho5.jpg"><img src="image/Ho5.jpg" alt="Segi Holland 5"></a>
            <h3>Segi Holland</h3>
            <p>$18.14</p>
            <button class="add-to-cart" data-product-id="21" data-product-name="Segi Holland" data-product-price="18.14" data-product-image="image/Ho5.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ho6.jpg"><img src="image/Ho6.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland</h3>
            <p>$18.13</p>
            <button class="add-to-cart" data-product-id="22" data-product-name="Segi Holland" data-product-price="18.13" data-product-image="image/Ho6.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ho7.jpg"><img src="image/Ho7.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland</h3>
            <p>$18.12</p>
            <button class="add-to-cart" data-product-id="23" data-product-name="Segi Holland" data-product-price="18.12" data-product-image="image/Ho7.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ho8.jpg"><img src="image/Ho8.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland</h3>
            <p>$18.11</p>
            <button class="add-to-cart" data-product-id="24" data-product-name="Segi Holland" data-product-price="18.11" data-product-image="image/Ho8.jpg">Add to Cart</button>
        </div>
       <div class="product">
            <a href="image/Ho9.jpg"><img src="image/Ho9.jpg" alt="Segi Holland"></a>
            <h3>Segi Holland</h3>
            <p>$18.10</p>
            <button class="add-to-cart" data-product-id="25" data-product-name="Segi Holland" data-product-price="18.10" data-product-image="image/Ho9.jpg">Add to Cart</button>
        </div>          
        <div class="product">
            <a href="image/Sho1.jpg"><img src="image/Sho1.jpg" alt="Shoes Female"></a>
            <h3>Shoes Female</h3>
            <p>$16.10</p>
            <button class="add-to-cart" data-product-id="26" data-product-name="Shoes Female" data-product-price="16.10" data-product-image="image/Sho1.jpg">Add to Cart</button>
        </div>  
        <div class="product">
            <a href="image/Sho2.jpg"><img src="image/Sho2.jpg" alt="Shoes Sneakers"></a>
            <h3>Shoes Sneakers</h3>
            <p>$14.10</p>
            <button class="add-to-cart" data-product-id="27" data-product-name="Shoes Sneakers" data-product-price="14.10" data-product-image="image/Sho2.jpg">Add to Cart</button>
        </div>  
        <div class="product">
            <a href="image/Sho3.jpg"><img src="image/Sho3.jpg" alt="Shoes"></a>
            <h3>Shoes</h3>
            <p>$17.10</p>
            <button class="add-to-cart" data-product-id="28" data-product-name="Shoes" data-product-price="17.10" data-product-image="image/Sho3.jpg">Add to Cart</button>
        </div>                 
      <div class="product">
            <a href="image/Ge1.jpg"><img src="image/Ge1.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$12.8</p>
            <button class="add-to-cart" data-product-id="29" data-product-name="Gezina" data-product-price="12.8" data-product-image="image/Ge1.jpg">Add to Cart</button>
        </div> 
      <div class="product">
            <a href="image/Ge2.jpg"><img src="image/Ge2.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$12.10</p>
            <button class="add-to-cart" data-product-id="30" data-product-name="Gezina" data-product-price="12.10" data-product-image="image/Ge2.jpg">Add to Cart</button>
        </div> 
       <div class="product">
            <a href="image/Ge3.jpg"><img src="image/Ge3.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$10.10</p>
            <button class="add-to-cart" data-product-id="31" data-product-name="Gezina" data-product-price="10.10" data-product-image="image/Ge3.jpg">Add to Cart</button>
        </div> 
       <div class="product">
            <a href="image/Ge4.jpg"><img src="image/Ge4.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$16.10</p>
            <button class="add-to-cart" data-product-id="32" data-product-name="Gezina" data-product-price="16.10" data-product-image="image/Ge4.jpg">Add to Cart</button>
        </div> 
       <div class="product">
            <a href="image/G5.jpg"><img src="image/G5.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$13.10</p>
            <button class="add-to-cart" data-product-id="33" data-product-name="Gezina" data-product-price="13.10" data-product-image="image/G5.jpg">Add to Cart</button>
        </div> 
       <div class="product">
            <a href="image/Ge6.jpg"><img src="image/Ge6.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$11.10</p>
            <button class="add-to-cart" data-product-id="34" data-product-name="Gezina" data-product-price="11.10" data-product-image="image/Ge6.jpg">Add to Cart</button>
        </div> 
        <div class="product">
            <a href="image/Ge7.jpg"><img src="image/Ge7.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$19.10</p>
            <button class="add-to-cart" data-product-id="35" data-product-name="Gezina" data-product-price="19.10" data-product-image="image/Ge7.jpg">Add to Cart</button>
        </div> 
        <div class="product">
            <a href="image/Ge8.jpg"><img src="image/Ge8.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$17.10</p>
            <button class="add-to-cart" data-product-id="36" data-product-name="Gezina" data-product-price="17.10" data-product-image="image/Ge8.jpg">Add to Cart</button>
        </div>
        <div class="product">
            <a href="image/Ge9.jpg"><img src="image/Ge9.jpg" alt="Gezina"></a>
            <h3>Gezina</h3>
            <p>$17.10</p>
            <button class="add-to-cart" data-product-id="37" data-product-name="Gezina" data-product-price="9.10" data-product-image="image/Ge9.jpg">Add to Cart</button>
        </div>       
        <div class="product">
            <a href="image/Iphone X.jpg"><img src="image/Iphone X.jpg" alt="Iphone X"></a>
            <h3>Iphone X</h3>
            <p>$50.10</p>
            <button class="add-to-cart" data-product-id="38" data-product-name="Iphone X" data-product-price="50.10" data-product-image="image/Iphone X.jpg">Add to Cart</button>
        </div>
       <div class="product">
            <a href="image/Iphone xr.jpg"><img src="image/Iphone xr.jpg" alt="Iphone xr"></a>
            <h3>Iphone xr</h3>
            <p>$40.10</p>
            <button class="add-to-cart" data-product-id="39" data-product-name="Iphone xr" data-product-price="40.10" data-product-image="image/Iphone xr.jpg">Add to Cart</button>
        </div>        
       <div class="product">
            <a href="image/Infinix SMART50.jpg"><img src="image/Infinix SMART50.jpg" alt="Gezina"></a>
            <h3>Infinix SMART50</h3>
            <p>$70.10</p>
            <button class="add-to-cart" data-product-id="40" data-product-name="Infinix SMART50" data-product-price="70.10" data-product-image="image/Infinix SMART50.jpg">Add to Cart</button>
        </div>
       <div class="product">
            <a href="image/Infinix SMART9.jpg"><img src="image/Infinix SMART9.jpg" alt="Infinix SMART9"></a>
            <h3>Infinix SMART9</h3>
            <p>$50.10</p>
            <button class="add-to-cart" data-product-id="41" data-product-name="Infinix SMART9" data-product-price="50.10" data-product-image="image/Infinix SMART9.jpg">Add to Cart</button>
        </div> 
        <div class="product">
            <a href="image/Infinix Hot10.jpg"><img src="image/Infinix Hot10.jpg" alt="Infinix Hot10"></a>
            <h3>Infinix Hot10</h3>
            <p>$30.10</p>
            <button class="add-to-cart" data-product-id="42" data-product-name="Infinix Hot10" data-product-price="30.10" data-product-image="image/Infinix Hot10.jpg">Add to Cart</button>
        </div>        
        <div class="product">
            <a href="image/Techno Spack20.jpg"><img src="image/Techno Spack20.jpg" alt="Techno Spack20"></a>
            <h3>Techno Spack20</h3>
            <p>$70.10</p>
            <button class="add-to-cart" data-product-id="43" data-product-name="Techno Spack20" data-product-price="70.10" data-product-image="image/Techno Spack20.jpg">Add to Cart</button>
        </div>
        
       <div class="product">
            <a href="image/W3.jpg"><img src="image/W3.jpg" alt="SmartWatch X2000"></a>
            <h3>SmartWatch X2000</h3>
            <p>$20.5</p>
            <button class="add-to-cart" data-product-id="44" data-product-name="SmartWatch X2000" data-product-price="20.5" data-product-image="image/W3.jpg">Add to Cart</button>
        </div>               
        <!-- Rest of the products -->
    </div>
</section>

<!-- Cart Section -->
<section id="cart">
    <h1>Cart</h1>
    <div class="cart-container">
        <!-- Cart items will be generated dynamically -->
    </div>
    <button style="background-color: #512bff;color: #fff;padding: 10px 20px;border: none;cursor: pointer;border: 1px solid #512bff;">Checkout</button>
</section>

<!-- Checkout Section -->
<section id="checkout">
    <h1>Checkout</h1>
    <form>
        <label for="name">Name:</label>
        <br>
        <input type="text" id="name" name="name" style="width: 100%;padding: 18px;font-size: 16px; border: none;border-radius: 5px;margin-bottom: 20px;border: 1px solid #512bff;">
        <br>
        <label for="email">Email:</label>
        <br>
        <input type="email" id="email" name="email" style="width: 100%;padding: 18px;font-size: 16px; border: none;border-radius: 5px;margin-bottom: 20px;border: 1px solid #512bff;">
         <br>
    <label for="address">Address:</label>
    <br>
    <input type="text" id="address" name="address" style="width: 100%;padding: 18px;font-size: 16px; border: none;border-radius: 5px;margin-bottom: 20px;border: 1px solid #512bff;">
    <br>
    <button style="background-color: #512bff;color: #fff;padding: 10px 20px;border: none;cursor: pointer;">Complete Purchase</button>
</form>
</section>
<br>
<footer>
<p>&copy; 2024 Alamin Market</p>
</footer>

<script>
// Add event listener to cart buttons
document.addEventListener("DOMContentLoaded", function() {
const cartButtons = document.querySelectorAll(".add-to-cart");
cartButtons.forEach(button => {
button.addEventListener("click", addToCart);
});
});

// Add product to cart
function addToCart(event) {
    const productId = event.target.dataset.productId;
    const productName = event.target.dataset.productName;
    const productPrice = event.target.dataset.productPrice;
    const productImage = event.target.dataset.productImage;
    const productQuantity = 1;

    // Update cart data
    const cartData = getCartData();
    if (cartData[productId]) {
        cartData[productId].quantity += productQuantity;
    } else {
        cartData[productId] = {
            name: productName,
            price: productPrice,
            image: productImage,
            quantity: productQuantity,
        };
    }
    localStorage.setItem("cart", JSON.stringify(cartData));
    updateCartUI();
}

// Get cart data from local storage
function getCartData() {
    const cartData = localStorage.getItem("cart");
    return cartData ? JSON.parse(cartData) : {};
}

// Update cart UI
function updateCartUI() {
    const cartContainer = document.querySelector(".cart-container");
    const cartData = getCartData();
    cartContainer.innerHTML = "";
    let totalCost = 0;
    Object.keys(cartData).forEach(productId => {
        const product = cartData[productId];
        const cartItem = document.createElement("div");
        cartItem.classList.add("cart-item");
        cartItem.innerHTML = `
            <img src="${product.image}" alt="${product.name}">
            <h3>${product.name}</h3>
            <p>$${product.price}</p>
            <p>Quantity: ${product.quantity}</p>
            <button class="remove-btn" data-product-id="${productId}">Remove</button>
        `;
        cartContainer.appendChild(cartItem);
        totalCost += product.price * product.quantity;
    });
    cartContainer.innerHTML += `<p>Total: $${totalCost}</p>`;

    const removeBtns = document.querySelectorAll(".remove-btn");
    removeBtns.forEach(btn => {
        btn.addEventListener("click", removeProduct);
    });
}

// Remove product from cart
function removeProduct(event) {
    const productId = event.target.dataset.productId;
    const cartData = getCartData();
    delete cartData[productId];
    localStorage.setItem("cart", JSON.stringify(cartData));
    updateCartUI();
}

// Search products
document.getElementById("search-btn").addEventListener("click", searchProducts);

function searchProducts() {
    const searchInput = document.getElementById("search-input");
    const searchQuery = searchInput.value.trim().toLowerCase();
    const products = document.querySelectorAll(".product");
    products.forEach(product => {
        const productName = product.querySelector("h3").textContent.toLowerCase();
        if (productName.includes(searchQuery)) {
            product.style.display = "block";
        } else {
            product.style.display = "none";
        }
    });
}
</script>
</body>
</html>
