<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wecome Page</title>
    <link
    href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
    rel="stylesheet"
    />
    <link
    href="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.5.0/mdb.min.css"
    rel="stylesheet"
    />
    <script
    type="text/javascript"
    src="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.5.0/mdb.min.js"
    ></script>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="index.css">
</head>
<body>

<!-- The core Firebase JS SDK is always required and must be listed first -->
<script src="https://www.gstatic.com/firebasejs/8.6.7/firebase-app.js"></script>

<!-- header section starts  -->

<header>

    <div id="menu-bar" class="fas fa-bars"></div>

    <a href="#" class="logo">karam<span>lyy</span></a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#book">book</a>
        <a href="#packages">products</a>
        <a href="#gallery">Gallery</a>
        <a href="#services">services</a>
        <a href="#contact">contact</a>
    </nav>

    <div class="icons">
        <i class="fas fa-search" id="search-btn"></i>
        <i class="fas fa-user" id="login-btn"></i>
        <a href="cart.html"><i class="fas fa-shopping-cart" data-toggle="modal" data-target="#cart"><sup><span class="total-count"></span></sup></i></a>
    </div>

    <form action="" class="search-bar-container">
        <input type="search" id="search-bar" placeholder="search here...">
        <label for="search-bar" class="fas fa-search"></label>
    </form>

</header>

<!-- header section ends -->

<!-- login form container  -->

<div class="login-form-container">

    <i class="fas fa-times" id="form-close"></i>

    <form>
        <h3>Logged In</h3>
        <center><span id="user" class="message">Hello, < email-id ></Email-id></span></center>
        <button class="btn btn-danger" onclick="logout()">Logout</button>
    </form>

</div>

<!-- home section starts  -->

<section class="home" id="home">
    <div class="success"><span>Welcome to Slash Page, You are successfully loged in!!!</span></div><br/>

    <div class="content">
        <h3>adventure is worthwhile</h3>
        <p>dicover new places with us, adventure awaits</p>
        <a href="#" class="btn">discover more</a>
    </div>

    <div class="controls">
        <span class="vid-btn active" src="videos/video1.mp4"></span>
        <span class="vid-btn" data-src="videos/video2.mp4"></span>
        <span class="vid-btn" data-src="videos/video3.mp4"></span>
        <span class="vid-btn" data-src="videos/video4.mp4"></span>
    </div>

    <div class="video-container">
        <video src="videos/video1.mp4" id="video-slider" loop autoplay muted></video>
    </div>

</section>

<!-- home section ends -->

<!-- book section starts  -->

<section class="book" id="book">

    <h1 class="heading">
        <span>b</span>
        <span>o</span>
        <span>o</span>
        <span>k</span>
        <span class="space"></span>
        <span>n</span>
        <span>o</span>
        <span>w</span>
    </h1>

    <div class="row">

        <div class="image">
            <img src="images/towfiqu-barbhuiya-Ksgjx0tyuCY-unsplash.jpg" alt="">
        </div>

        <form action="login.html">
            <div class="inputBox">
                <h3>Product Name</h3>
                <input type="text" placeholder="product name">
            </div>
            <div class="inputBox">
                <h3>how many</h3>
                <input type="number" placeholder="number of product">
            </div>
            <div class="inputBox">
                <h3>Select file</h3>
                <input type="file" id="myFile" name="filename">
            </div>
            <input type="submit" class="btn" value="book now">
            
        </form>

    </div>

</section>

<!-- book section ends -->

<!-- packages section starts  -->

<section class="packages" id="packages">

    <h1 class="heading">
        <span>P</span>
        <span>r</span>
        <span>o</span>
        <span>d</span>
        <span>u</span>
        <span>c</span>
        <span>t</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (1).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 1 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (10).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 2 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (11).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 3 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (16).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 4 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (12).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 5 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (14).jpeg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Table 6 </h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, nam!</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price"> $90.00 <span>$120.00</span> </div>
                <a href="https://rzp.io/l/8bRwaE0CI" class="btn">book now</a>
                <a href="#" data-name="Orange" data-price="0.5" class="add-to-cart btn btn-primary">Add to cart</a>
            </div>
        </div>

    </div>

</section>

<!-- packages section ends -->

<!-- gallery section starts  -->

<section class="gallery" id="gallery">

    <h1 class="heading">
        <span>g</span>
        <span>a</span>
        <span>l</span>
        <span>l</span>
        <span>e</span>
        <span>r</span>
        <span>y</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/WhatsApp Image 2021-09-16 at 9.07.54 PM (16).jpeg" alt="">
            <div class="content">
                <h3>Tables</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, tenetur.</p>
                <a href="tables.html" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/new-data-services-h0HE-fhx2wg-unsplash.jpg" alt="">
            <div class="content">
                <h3>3D Printings</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, tenetur.</p>
                <a href="3dprintings.html" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/wu-yi-Dr2klA3gVpE-unsplash.jpg" alt="">
            <div class="content">
                <h3>Lamps</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus, tenetur.</p>
                <a href="lamps.html" class="btn">see more</a>
            </div>
        </div>
    </div>

</section>

<!-- gallery section ends -->

<!-- services section starts  -->

<section class="services" id="services">

    <h1 class="heading">
        <span>s</span>
        <span>e</span>
        <span>r</span>
        <span>v</span>
        <span>i</span>
        <span>c</span>
        <span>e</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <i class="fas fa-rupee-sign"></i>
            <h3>affordable price</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>
        <div class="box">
            <i class="fas fa-tools"></i>
            <h3>Best Service</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>
        <div class="box">
            <i class="fas fa-truck"></i>
            <h3>Fast Delivery</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore commodi earum, quis voluptate exercitationem ut minima itaque iusto ipsum corrupti!</p>
        </div>

    </div>

</section>

<!-- services section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">
    
    <h1 class="heading">
        <span>c</span>
        <span>o</span>
        <span>n</span>
        <span>t</span>
        <span>a</span>
        <span>c</span>
        <span>t</span>
    </h1>

    <div class="row">

        <div class="image">
            <img src="images/quino-al-xhGMQ_nYWqU-unsplash.jpg" alt="">
        </div>

        <form action="">
            <div class="inputBox">
                <input type="text" placeholder="name">
                <input type="email" placeholder="email">
            </div>
            <div class="inputBox">
                <input type="number" placeholder="number">
                <input type="text" placeholder="subject">
            </div>
            <textarea placeholder="message" name="" id="" cols="30" rows="10"></textarea>
            <input type="submit" class="btn" value="send message">
        </form>

    </div>
    
</section>

<!-- contact section ends -->
<button class="open-button" onclick="openForm()">Chat</button>

<div class="chat-popup" id="myForm">
  <form action="" class="form-container">
    <h1>Chat</h1>

    <label for="msg"><b>Message</b></label>
    <textarea placeholder="Type message.." name="msg" required></textarea>

    <button type="submit" class="btn">Send</button>
    <button type="button" class="btn cancel" onclick="closeForm()">Close</button>
  </form>
</div>
<!-- footer section  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>about us</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda quas magni pariatur est accusantium voluptas enim nemo facilis sit debitis.</p>
        </div>
        <div class="box">
            <h3>branch locations</h3>
            <a href="#">mysore</a>
        </div>
        <div class="box">
            <h3>quick links</h3>
            <a href="#">home</a>
            <a href="#">book</a>
            <a href="#">packages</a>
            <a href="#">services</a>
            <a href="#">gallery</a>
            <a href="#">review</a>
            <a href="#">contact</a>
        </div>
        <div class="box">
            <h3>follow us</h3>
            <a href="#"><i class="fas fa-facebook">facebook</i></a>
            <a href="#"><i class="fas fa-instagram">instagram</i></a>
        </div>

    </div>

    <h1 class="credit"> created by <span> Karam Afandi</span> | all rights reserved! </h1>

</section>
<script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

<!-- custom js file link  -->
<script src="index.js"></script>

    <!-- TODO: Add SDKs for Firebase products that you want to use
        https://firebase.google.com/docs/web/setup#available-libraries -->
    <script src="https://www.gstatic.com/firebasejs/8.6.7/firebase-analytics.js"></script>
    <script src="https://www.gstatic.com/firebasejs/8.6.7/firebase-auth.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
    <script src="firebase.js"></script>
    <script src="welcome.js"></script>
    <script src="cart.js"></script>
</body>
</html>
