<!doctype html>
<html lang="en">
    <head>
        <meta charset="UTF-8"
        < meta name="viewport" content="width=device-width initial-scale=1.0">
        <title>StrideX| Premium Footwear</title>
        <!--font awesome for icons-->
        <link rel="stylesheet" href="adwaid-nk-LH9ik0zJlC4-unsplash.jpg">
        <style>
            /*---css styles---*/
            :root {
                --primary-color: #1a1a1a;
                --accent-color:#e63946;
                --light-bg: #f4f4f4;
                --white: #ffffff;
                --text-color:#333;
            }

            *{
                margin:0;
                padding:0;
                box-sizing: border-box;
                font-family:'Segoe UI', Tahoma, Geneva, verdana, sans-serif;
            }
            body{
                background-color: var(--white);
                color: var(--text-color);
            }
        
            /*navigation*/
            nav {
                display:flex;
                justify-content:space-between;
                align-items: center;
                padding: 1.5rem 5%;
                background-color: var(--white);
                box-shadow: 0 2px 10px rgba(0,0,0,0.1);
                position: sticky;
                top: 0;
                z-index: 1000;
            }
            .logo{
                font-size: 1rem;
                font-weight: 100;
                color: var(--primary-color);
                text-transform: uppercase;
                letter-spacing: 1px;
            }
            .logo span{
                color: var(--accent-color);
            }
            .nav-links {
                display: flex;
                list-style: none;
            }
            .nav-links li {
                margin:0 15px;
            }
            .nav-links a{
                text-decoration: none;
                color: var(--primary-color);
                font-weight: 100;
                transition:0.3s;
            }
            .nav-links a:hover{
                color:var(--accent-color);
            }
            .nav-icons {
                font-size: 1rem;
                cursor: pointer;
            }
            .nav-icons i{
                margin-left: 15px;
                transition: 0.3s;
            }
            .nav-links i:hover{
                color:var(--accent-color);
            }
            .cart-count{
                background-color: var(--accent-color);
                color: white;
                font-size: 0.7rem;
                padding: 2px 6px;
                border-radius: 50%;
                vertical-align: top;
                margin-left: 2px;
            }
            /*hero section */
            .hero{
                height: 80vh;
                background: linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url("adwaid-nk-LH9ik0zJlC4-unsplash.jpg");
                background-size: cover;
                background-position: center;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                color: var(--white);
                padding: 0 20px;
            }
            .hero h1{
                font-size: 1rem;
                margin-bottom:20px;
                text-transform: uppercase;

            }
            .hero p{
                font-size: 1rem;
                margin-bottom: 30px;
                max-width: 100px;
            }
            .btn{
             padding: 11px 30px;
             background-color: var(--accent-color);
             color: var(--white);
             text-decoration: none;
             font-weight: bold;
             border-radius: 30px;
             transition: 0.3s;
             border: none;
             cursor:pointer;
            }
            .btn:hover{
                background-color: #c9c9c9;
                transform: translateY(-3px);
            }
            /*product section */
            .products{
            padding:4rem 5%;
            background-color:var(--light-bg);
            }
            .section-title{
            text-align:center;
            font-size:1rem;
            margin-bottom:3rem;
            color:var(--primary-color);
        }
            .product-grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:30px;
            }
            .product-card{
            background:var(--white);
            border: radius 10px;
            overflow:hidden;
            box-shadow:0.5px 15px rgba(0,0,0,0.05);
            transition:0.3s;
            position:relative;
            }
            .product-card:hover{
            transform:translateY(-10px);
            box-shadow:0 10px 20px rgba(,0,0,0,0.1);
            }
            .product-img{
            width:30%
            height: 10px;
            object-fit:cover;
            }
            .product-info{
            padding: 20px;
            }
            .product-catagory {
            font-size:0.9rem;
            color:#888;
            text-transform:uppercase;
            }
            .product-title{
            font-size:1rem;
            margin:5px 0;
            font-weight:100;
            }
            .product-price{
            color:var(--accent-color);
            font-weight:bold;
            font-size:1.1rem;
            }
            .add-btn{
            width:30%;
            padding:10px;
            background:var(primary-color);
            color:white;
            border:none;
            margin-top:15px;
            cursor:pointer;
            transitions:0.3s;
            }
            .add-btn:hover{
            background:var(--accent-color);
            }
            /*feature section */
            .features {
                display: flex;
                justify-content: space-around;
                padding: 4rem 5%;
                flex-wrap: wrap;
                text-align: center;
            }
            .feature-item{
                flex: basis 300px;
                margin-bottom: 30px;

            }
            .feature-item i{
                font-size: 1rem;
                color: var(--accent-color);
                margin-bottom: 15px;
            }
            /*footer*/
            footer {
                background-color: var(--primary-color);
                color: var(--white);
                padding: 3rem 5%;
                text-align: center;
            }
            .footer-content{
                display: flex;
                flex-direction: column;
                gap: 20px;

            }
            .social-icons a{
                color: var(--white);
                font-size: 1rem;
                margin: 0.3s;
            }
            .social-icons a:hover{
                color: var(--accent-color);
            }
            /*mpbile responsiveness*/
            @media(max-width:100px){
                .nav links{
                    display: none;/*hidden on mobile for simplicity*/
                }
                .hero h1{
                    font-size: 1rem;
                }
            }
             @keyframes myAnimation {
  from {background-color: black;}
  to {background-color: yellow;}
}
            body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f2f2f2;
        }
             header {
            background-color: red;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color:yellow;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-size: 18px;
        }

        nav a:hover {
            color:red;
        }

        section {
            text-align: center;
            padding: 40px;
        }

        button {
            background-color:yellow;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color:red;
        }

        /* Courses Section */
        #courses {
            background-color: yellow;
        }

        .course-box {
            display: inline-block;
            background-color: red;
            color: white;
            padding: 15px 25px;
            margin: 10px;
            border-radius: 8px;
            font-size: 18px;
        }

        .course-box:hover {
            background-color: yellow;
        }

        footer {
            background-color:red;
            color: white;
            text-align: center;
            padding: 10px;
        }

        </style>
    </head>
    <body>
        <!--navbar-->
        <nav><div class="logo">Stride<span>X</span></div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#products">Men</a></li>
             <li><a href="#products">Women</a></li>
              <li><a href="#products">Kids</a></li>
               <li><a href="#products">Sale</a></li>
        </ul>
    <div class="nav-icons">
<i class="fas fa-search"></i>
<i class="fas fa-user"></i>
<i class="fas fa-shopping-cart" onclick="toggleCart()"></i>
<span class="cart-count" id="cart-count">0</span>
</div>
</nav>
<!--hero section-->
<header class="hero">
    <h1>Run Beyond Limits</h1>
    <p>Experience the ultimate comfort with our new collection. Designed for performance,built for style.</p>
    <a href="#products" class="btn">Shop Collection</a>
</header>
<!--Features-->
<section class="features">
    <div class="feature-item">
        <i class="fas fa-shoe-prints"></i>
        <h3>Premium Comfort</h3>
        <p>Memory from insoles for all-day support.</p>
    </div>
    <div class="feature-item">
        <i class="fas fa-truck"></i>
        <h3>Free Shipping</h3>
        <p>On all orders over $100.</p>
        </div>
         <div class="feature-item">
        <i class="fas fa-undo"></i>
        <h3>30-Day Returns</h3>
        <p>Money-back guarantee policy.</p>
        </div>
</section>
<!--product section-->
<section class="products" id="products">
    <h2 class="section-title">Trending Now</h2>
    <div class="product-grid">
        <!--product 1-->
        <div class="product-card">
            <img src="shahab-vejdanian-EW6iwfG1uZU-unsplash.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Running</span>
            <h3 class="product-title">Nick Air Red</h3>
        <div class="product-price">$129.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 2-->
    <div class="product-card">
            <img src="fachry-zella-devandra-lXuyEh7DeC8-unsplash.jpg" class="product-img" height="100px" width="50%" >
            <div class="product-info"><span class="product-catagory">Casual</span>
            <h3 class="product-title">Urban Walker</h3>
        <div class="product-price">$89.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 3-->
    <div class="product-card">
            <img src="caroline-attwood-WtDn_TCaHqU-unsplash.jpg" class="product-img"  height="100px" width="50%">
            <div class="product-info"><span class="product-catagory">Sports</span>
            <h3 class="product-title">Blue Speedster</h3>
        <div class="product-price">$110.00</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 4-->
    <div class="product-card">
            <img src="adwaid-nk-LH9ik0zJlC4-unsplash.jpg" class="product-img"  height="100px" width="50%">
            <div class="product-info"><span class="product-catagory">training</span>
            <h3 class="product-title">Green flex</h3>
        <div class="product-price">$95.00</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 5-->
        <div class="product-card">
            <img src="pexels-melvin-buezo-1253763-2529148.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">flexible</span>
            <h3 class="product-title">High Yellow</h3>
        <div class="product-price">$150.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 6-->
        <div class="product-card">
            <img src="pexels-nagy-szabi-2441520-4066968.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Water Proof</span>
            <h3 class="product-title">Beat Balls</h3>
        <div class="product-price">$189.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 7-->
        <div class="product-card">
            <img src="pexels-ox-street-3848035-6050919.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Exercise</span>
            <h3 class="product-title">White Splash</h3>
        <div class="product-price">$250.20</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 8-->
        <div class="product-card">
            <img src="pexels-perfect-lens-12306281.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Gymnastic</span>
            <h3 class="product-title">Black Evil</h3>
        <div class="product-price">$300.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 9-->
        <div class="product-card">
            <img src="pexels-perfect-lens-8987247.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Gym</span>
            <h3 class="product-title">Black Spider</h3>
        <div class="product-price">$310.00</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 10-->
        <div class="product-card">
            <img src="pexels-perfect-lens-8987248.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Regular</span>
            <h3 class="product-title">Red Spicy</h3>
        <div class="product-price">$200.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 11-->
        <div class="product-card">
            <img src="pexels-rohit-sharma-1230131-28375818.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">EasyToWear</span>
            <h3 class="product-title">HangOver</h3>
        <div class="product-price">$160.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 12-->
        <div class="product-card">
            <img src="pexels-sneepcrew-12730128.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Walking</span>
            <h3 class="product-title">SneepCrew</h3>
        <div class="product-price">$130.00</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 13-->
        <div class="product-card">
            <img src="pexels-sneepcrew-12730145.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Rangoli</span>
            <h3 class="product-title">HolyShoe</h3>
        <div class="product-price">$140.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 14-->
        <div class="product-card">
            <img src="pexels-sneepcrew-12730145.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">HoliWear</span>
            <h3 class="product-title">StraightCrew</h3>
        <div class="product-price">$380.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
     <!--product 15-->
        <div class="product-card">
            <img src="pexels-ti-n-dung-1863739035-31507730.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Soft</span>
            <h3 class="product-title">White Feather</h3>
        <div class="product-price">$360.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 16-->
        <div class="product-card">
            <img src="pexels-alokkd1-19845610.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Clean</span>
            <h3 class="product-title">HandPlacement</h3>
        <div class="product-price">$330.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 17-->
        <div class="product-card">
            <img src="pexels-anthony-nodado-3573491-6234695.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Suitable</span>
            <h3 class="product-title">AnthonyRobber</h3>
        <div class="product-price">$370.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 18-->
        <div class="product-card">
            <img src="pexels-hamza01nsr-12725054.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Strength</span>
            <h3 class="product-title">Hamja370</h3>
        <div class="product-price">$370.70</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 19-->
        <div class="product-card">
            <img src="pexels-hipkicks-24037520-6719187.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">KickBoxing</span>
            <h3 class="product-title">HipeKicks</h3>
        <div class="product-price">$390.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 20-->
        <div class="product-card">
            <img src="pexels-hurrahsuhail-11324546.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Destroyer</span>
            <h3 class="product-title">Hurricane</h3>
        <div class="product-price">$240.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 21-->
        <div class="product-card">
            <img src="pexels-ishaanaggarwal-7926150.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Boxer</span>
            <h3 class="product-title">BrownScotch</h3>
        <div class="product-price">$315.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 22-->
        <div class="product-card">
            <img src="pexels-jose-martin-segura-benites-1422456152-27204251.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Angel</span>
            <h3 class="product-title">White Evil</h3>
        <div class="product-price">$222.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 23-->
        <div class="product-card">
            <img src="pexels-jose-martin-segura-benites-1422456152-27503504.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Blue</span>
            <h3 class="product-title">Blue Berry</h3>
        <div class="product-price">$323.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 24-->
        <div class="product-card">
            <img src="pexels-jose-martin-segura-benites-1422456152-27988923.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Shiny</span>
            <h3 class="product-title">Shiny White</h3>
        <div class="product-price">$327.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 25-->
        <div class="product-card">
            <img src="pexels-laurachouette-21070422.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Savior</span>
            <h3 class="product-title">NetWeb</h3>
        <div class="product-price">$399.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 26-->
        <div class="product-card">
            <img src="pexels-webdonut-19090.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Donar</span>
            <h3 class="product-title">WebDonar</h3>
        <div class="product-price">$337.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 27-->
        <div class="product-card">
            <img src="pexels-suherli-ferdy-1379330-5488660.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">BrownNet</span>
            <h3 class="product-title">Bounty Hunter</h3>
        <div class="product-price">$1000.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 28-->
        <div class="product-card">
            <img src="pexels-pratik-prasad-3736245-14773449.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Airal</span>
            <h3 class="product-title">AirDior</h3>
        <div class="product-price">$560.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 29-->
        <div class="product-card">
            <img src="pexels-ox-street-3848035-6050911.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Proxy</span>
            <h3 class="product-title">ProxyOx</h3>
        <div class="product-price">$700.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
    <!--product 30-->
        <div class="product-card">
            <img src="pexels-ox-street-3848035-6050919.jpg" class="product-img" height="100px" width="50%">
            
            <div class="product-info"><span class="product-catagory">Master</span>
            <h3 class="product-title">Mucambo</h3>
        <div class="product-price">$960.99</div>
        <button class="ädd-btn" onclick="addToCart()">Add To Cart</button>
        </div>
    </div>
</section>
<!--footer-->
<footer>
    <div class="footer-content">
        <div class="logo">stride<span>X</span></div>
    </div>
</footer>
<p>2025 StrideX Shoes.All rights reserved </p>
<video width="250" height="300" controls>
  <source src="uhd_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="8435088-uhd_2160_4096_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="8994347-uhd_2160_3840_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="12750860_3840_2160_24fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="13661729_3840_2160_30fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="13857295_3840_2160_60fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="14180897_3840_2160_24fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="15814654-hd_1920_1080_30fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="7883997-uhd_2160_4096_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="7166846-uhd_2160_4096_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<video width="250" height="300" controls>
  <source src="3209242-uhd_3840_2160_25fps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
<section class="contact-section">
    <div class="container">
        <!--left side:info and description-->
        <div class="contact-info">
            <h2>GET IN TOUCH </h2>
            <p class="description">Have questions about our products or need support?
                <br>
                Fill out the full form or use the contact information below.
                <br>
                We are here to help and answer any questions you might have.</p>
         <div class="info-item">
            <i class="fas fa-phone-alt"></i>
            <span>+91 8822965508</span>
         </div>
          <div class="info-item">
            <i class="fas fa-envelope"></i>
            <span>pranjaljoy88@gmail.com</span>
         </div>
          <div class="info-item">
            <i class="fas fa-map-marker-alt"></i>
            <span>Settlement Rd,Sribhumi PHE office Opposite To Circle Office
                <br>karimganj,788712
            </span>

         </div>
         <!--right side :contact form-->
         <div class="contact-form"><form action="#" method="POST">
            <h3>SEND US A MESSAGE</h3>
             <div class="input group"><input type="text" name="name" required placeholder="YOUR NAME"></div>
            <div class="input group"><input type="email" name="email" required placeholder="YOUR EMAIL"></div>
            <div class="input group"><input type="text" name="subject" required placeholder="SUBJECT"></div>
            <div class="input group"><textarea name="message" rows="5" required placeholder="YOUR MESSAGE"></textarea></div>  
          <button type="submit" class="btn-submit">ELEVATE YOUR SHOE GAME WITH OUR LATEST COLLECTION</button>
        </form></div>
        </div>
    </div>
</section>
    </body>
</html>
