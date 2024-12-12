# Ex.07 Restaurant Website
## Date:12-12-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## Home.html:
```
<html>
    <head>
       <title>Soul Kitchen.com
    </title>
    <style>
        header{
            
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQduwbE35QJWXRIvc82jBmsOhRQHWaOv_v2Mg&s");
            color:aliceblue;
            margin:0;
            padding: 20px 20px;
            background-position: center;
            background-size: cover;
            text-align: left;
            

            
           
            
        }
        h1{
            font-size: 80px;
            margin:0;

        }
        nav{
            position: fixed;
            top:0%;
            right:0%;
            padding: 10px;
            z-index: 1000;
            
        }
        nav ul{
            list-style:none;
            display: flex;
            padding :0;
            margin:0;
        }
        nav ul li{
            margin-left: 20px;
        }
        nav ul li a{
            color:rgb(215, 25, 15);
            font-size: 20px;
            font-style:italic;
            text-decoration: none;
        }
        body{
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: 600;
            color: darkred;
            margin: 0;
            background-image: url("https://media.istockphoto.com/id/1401659561/photo/black-blue-abstract-watercolor-dark-blue-art-background-with-space-for-design-spot-blot.jpg?s=612x612&w=0&k=20&c=d3veUEbG89ucB8BhID9pUPp2aThWEXRDDPS7Nl1GMDg=");
            background-size: cover;

            
        }
        .food{
            bottom: 30%;
            position:absolute;
            right: 5%;
            height:300px;
            width:400px;

        }
        .content{
            font-style: italic;
            font-weight: 200;
            left:5%;
            right: 35%;
            bottom:30%;
            color: aliceblue;

            position: absolute;
            font-size: 20px;
        }
        h2{
            font-size: 60px;
            font-weight: 200;
            font-style: Algerian;
            top:25%;
            left:5%;
            
            position: absolute;
        }
        footer{
            bottom:0%;
            position: fixed;
            width:100%;
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm18eBadaqCzW5XTKA-c434AR5co6NgyoT9w&s");
            text-align: center;
            font-style: arial;
            color: aliceblue;
            left:0%;
            background-size:cover;
            padding:20px;
            font-size:18px;
            


            
            
          
            

        }
       

        
    </style>
    
    </head>
    <body>
        <header>
            <h1 align="center">
                STAR KITCHEN
            </h1>
        </header>
       
        <div class="food">
            <img src="https://png.pngtree.com/png-vector/20240722/ourmid/pngtree-fast-food-snacks-desserts-and-drinks-png-image_13023793.png">

        </div>
        <h2>
            About Us
        </h2>
        
        <div class="content">
            <p>
                Welcome to <b><b>Star Kitchen</b></b>, where every dish tells a story and each flavor is crafted with passion. Located in the heart of the city, Star Kitchen is more than just a restaurant—it’s an experience of culinary artistry and heartfelt hospitality.

Our journey began with a simple goal: to create a place where people could connect over meals made with the freshest ingredients and authentic recipes. We believe that food should nourish both the body and soul, which is why we take pride in every detail, from selecting premium ingredients to curating a welcoming ambiance.




            </p>
        </div>
        

        
    

        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="Menu.html">Menu</a></li>
                <li><a href="Administrator.html">Administrator</a></li>
                <li><a href="Onlineorder.html">Online Order</a></li>  
                <li><a href="Contact.html">Contact</a></li>  
            </ul>
        </nav>
        
        <footer>
            @2024 STAR KITCHEN(S STAR ASHIL)
        </footer>
    
    

    </body>
    
</html>
```
## Menu.html:
```
<html>
    <style>
        header{
            
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQduwbE35QJWXRIvc82jBmsOhRQHWaOv_v2Mg&s");
            color:firebrick;
            margin:0;
            padding: 20px 20px;
            background-position: center;
            background-size: cover;
            text-align: left;
            

            
           
            
        }
        h1{
            font-size: 80px;
            margin:0;
        }   
        .box{
            background-image: url("https://thumbs.dreamstime.com/b/deep-blue-smoke-background-light-bright-center-34783596.jpg");
            background-size: cover;
            width:100%;
            height:100%;
            position: absolute;
        } 
        body{
            overflow-x:hidden;
            overflow-y: hidden;
            margin: 0;

        }
        .menu1{
            color:white;
            text-align: center;
            font-size: larger;
            font-weight: 100 ;
            font-style: italic;
            
        }
        .menu2{
            color:white;
            text-align: center;
            font-size: larger;
            font-weight: 100;
            font-style: italic;
            
        }
        .menu3{
            color:white;
            text-align: center;
            font-size: larger;
            font-weight: 100;
            font-style: italic;
           
        }
        h2,h3,h4{
            font-weight: 300;
            font-size: xx-large;
            font-style: arial;
            color:rgb(20, 255, 149)

        }
        .image1{
            bottom:65%;
            right:15%;
            position:absolute;
            

        }
        .image2{
            bottom:17%;
            right:10%;
            position:absolute;
        }
        .image3{
            bottom:30%;
            left:15%;
            position:absolute;
        }

        nav{
            position: fixed;
            top:0%;
            right:0%;
            padding: 10px;
            z-index: 1000;
            
        }
        nav ul{
            list-style:none;
            display: flex;
            padding :0;
            margin:0;
        }
        nav ul li{
            margin-left: 20px;
        }
        nav ul li a{
            color:rgb(215, 25, 15);
            font-size: 20px;
            font-style:italic;
            text-decoration: none;
        }
        footer{
            bottom:0%;
            position: fixed;
            width:100%;
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm18eBadaqCzW5XTKA-c434AR5co6NgyoT9w&s");
            text-align: center;
            font-style: arial;
            color: aliceblue;
            left:0%;
            background-size:cover;
            padding:20px;
            font-size:18px;
            


            
            
          
            

        }
        


    </style>
    
    <body>
        <header>
            <h1 align="center">
                STAR KITCHEN
            </h1>
        </header>
        <div class="box">
            <div class="menu1">
                <h2>
                    <b><b>Appetizers</b></b>
                </h2>    
                    <p>Bruschetta - 269<br>Stuffed Mushrooms - 349 <br>Crispy Calamari - 439 <br>Garlic Shrimp Skewers - 569</p>
                
            </div>        
            <div class="menu2"> 
                <h3>    
                    <b><b>Quick Bites</b></b>

                </h3>
                <p>Classic Burger - 199<br>Cheese Pizza - 249<br>Fried Chicken Bucket - 399<br>French Fries - 99</p>
                
                
            </div>
            <div class="menu3">
                <h4>
                    <b><b>Refreshments</b></b>
                </h4>
                <p>Green Tea - 69<br>Fresh Lemonade - 69<br>Milkshake (Vanilla/Chocolate) - 129<br>Iced Coffee - 99</p>
            </div>
            <div class="image1">
                <img src="https://png.pngtree.com/png-vector/20231018/ourmid/pngtree-fast-foods-item-png-image_10303953.png">
            </div>
            <div class="image2">
                <img src="https://png.pngtree.com/png-clipart/20230914/ourmid/pngtree-sausage-cheese-pizza-slice-three-dimensional-3d-gourmet-food-fast-food-png-image_10116852.png">
            </div>
            <div class="image3">
                <img src="https://static.vecteezy.com/system/resources/thumbnails/027/145/821/small_2x/iced-coffee-with-cream-milk-perfect-for-drink-catalog-ai-generated-png.png">

            </div>
           
            

            
        </div>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="Menu.html">Menu</a></li>
                <li><a href="Administrator.html">Administrator</a></li>
                <li><a href="Onlineorder.html">Online Order</a></li>  
                <li><a href="Contact.html">Contact</a></li>  
            </ul>
        </nav>
        <footer>
            @2024 STAR KITCHEN(S STAR ASHIL)
        </footer>

    </body>
</html>
```

## Administrator.html;
```
<html>
    <style>
        .h1{
            font-size: 100%;
            margin:0;
        }
        header{
            
            
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQduwbE35QJWXRIvc82jBmsOhRQHWaOv_v2Mg&s");
            color:rgb(226, 38, 5);
            margin: 0;
            padding: 20px 20px;
            background-position: center;
            background-size: cover;
            text-size-adjust: 100%;
            text-align: left;
            position:relative;
            
        }
        body{
            background-image: url("https://png.pngtree.com/thumb_back/fh260/background/20220225/pngtree-blue-smoke-glows-in-the-dark-image_1035687.jpg");
            background-size: cover;
            
            overflow-x:hidden;
            overflow-y: hidden;
            margin: 0;

        
        }
        .image1{
            top:20%;
            left:5%;
            position: absolute;
            width:200px;
            height:200px;
            display:flex;
            justify-content:center;
            gap:5%;
            width:90%;
            font-size: xx-large;
            font-style: arial;
         }
         .image1 img{
            width:200px;
            height:300px;
            object-fit: cover;
            
         }
         .image1 div{
            text-align: center;
         }
         .image1 p{
            margin-top: 10px;
            font-size:xx-large;
            font-weight: 100;
            color:rgb(51, 225, 12)
           
         }
         nav{
            position: fixed;
            top:0%;
            right:0%;
            padding: 10px;
            z-index: 1000;
            
        }
        nav ul{
            list-style:none;
            display: flex;
            padding :0;
            margin:0;
        }
        nav ul li{
            margin-left: 20px;
        }
        nav ul li a{
            color:rgb(215, 25, 15);
            font-size: 20px;
            font-style:italic;
            text-decoration: none;
        }

         footer{
            bottom:0%;
            position: fixed;
            width:100%;
            background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm18eBadaqCzW5XTKA-c434AR5co6NgyoT9w&s");
            text-align: center;
            font-style: arial;
            color: aliceblue;
            left:0%;
            background-size:cover;
            padding:20px;
            font-size:18px;
            


            
            
          
            

        }

    </style>
    <body>
        <header>
            <h1 align="center">
                STAR KITCHEN
            </h1>
        
    </header>
    <div class="image1">
        <div>
        <img src="Pass photo.jpg">
        <p><b><b>Chief Administrator</b></b><br>(STAR ASHIL)</p>
        </div>
        <div>
        <img src="Priyan.jpg">
        <p><b><b>HR Manager</b></b><br>(SHANMUGA PRIYAN)</p>
        </div>
        <div>
        <img src="Sajith.jpg">
        <p>
           <b><b> Marketing Head</b></b><br>(SAJITH ALI)

        </p>
        </div>
        <div>
        <img src="Vanitha.jpg">
        <p>
            <b><b>Customer Support Lead</b></b> <br> (Vanitha)
        </p>
        </div>
        <div>
        <img src="Damu.jpg">
        <p>
            <b><b>Chef</b></b><br>(DAMU)
        </p>
        </div>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="Menu.html">Menu</a></li>
                <li><a href="Administrator.html">Administrator</a></li>
                <li><a href="Onlineorder.html">Online Order</a></li>  
                <li><a href="Contact.html">Contact</a></li>  
            </ul>
        </nav>
        <footer>
            @2024 STAR KITCHEN(S STAR ASHIL)
        </footer>

    </div>
    
    </body>
</html>
```

## Onlineorder.html;
```
<html>
    <head>
        <title>Online Order - Soul Kitchen</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-image: url("https://png.pngtree.com/thumb_back/fh260/background/20220225/pngtree-blue-smoke-glows-in-the-dark-image_1035687.jpg");
                background-size: cover;
                color: aliceblue;
            }
            header {
                background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQduwbE35QJWXRIvc82jBmsOhRQHWaOv_v2Mg&s");
                padding: 20px;
                text-align: center;
                color: aliceblue;
                background-size: cover;
            }
            header h1 {
                margin: 0;
                font-size: 50px;
            }
            .order-form {
                max-width: 800px;
                margin: 50px auto;
                padding: 20px;
                background: rgba(0, 0, 0, 0.7);
                border-radius: 8px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            }
            .order-form h2 {
                text-align: center;
                font-size: 32px;
                margin-bottom: 20px;
            }
            .menu-item {
                display: flex;
                justify-content: space-between;
                margin-bottom: 15px;
                padding: 10px;
                border-bottom: 1px solid aliceblue;
            }
            .menu-item label {
                font-size: 18px;
                flex: 1;
            }
            .menu-item input {
                width: 80px;
                padding: 5px;
                font-size: 16px;
            }
            .menu-item button {
                background-color: #d74f0e;
                color: aliceblue;
                border: none;
                padding: 10px;
                cursor: pointer;
                font-size: 18px;
            }
            .menu-item button:hover {
                background-color: #c14c0c;
            }
            .total-price {
                text-align: right;
                font-size: 24px;
                margin-top: 20px;
                color: #ffcc00;
            }
            nav{
                position: fixed;
                top:0%;
                right:0%;
                padding: 10px;
                z-index: 1000;
                
            }
            nav ul{
                list-style:none;
                display: flex;
                padding :0;
                margin:0;
            }
            nav ul li{
                margin-left: 20px;
            }
            nav ul li a{
                color:rgb(215, 25, 15);
                font-size: 20px;
                font-style:italic;
                text-decoration: none;
            }
    
             footer{
                bottom:0%;
                position: fixed;
                width:100%;
                background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm18eBadaqCzW5XTKA-c434AR5co6NgyoT9w&s");
                text-align: center;
                font-style: arial;
                color: aliceblue;
                left:0%;
                background-size:cover;
                padding:20px;
                font-size:18px;
                
    
    
                
                
              
                
    
            }    
            .submit-btn {
                width: 100%;
                background-color: #d74f0e;
                padding: 15px;
                font-size: 20px;
                color: aliceblue;
                border: none;
                cursor: pointer;
                border-radius: 5px;
            }
            .submit-btn:hover {
                background-color: #c14c0c;
            }
        </style>
    </head>
    <body>
        <header>
            <h1 align="center">
                STAR KITCHEN
            </h1>

        <div class="order-form">
            <h2>Place Your Order</h2>

            
            <div class="menu-item">
                <label for="burger">Burger</label>
                <input type="number" id="burger" name="burger" min="0" value="0" onchange="updateTotal()">
                <button onclick="addToCart('burger', 120)">Add to Cart ($120)</button>
            </div>
            <div class="menu-item">
                <label for="pizza">Pizza</label>
                <input type="number" id="pizza" name="pizza" min="0" value="0" onchange="updateTotal()">
                <button onclick="addToCart('pizza', 250)">Add to Cart ($250)</button>
            </div>
            <div class="menu-item">
                <label for="pasta">Pasta</label>
                <input type="number" id="pasta" name="pasta" min="0" value="0" onchange="updateTotal()">
                <button onclick="addToCart('pasta', 150)">Add to Cart ($150)</button>
            </div>
            <div class="menu-item">
                <label for="fries">Fries</label>
                <input type="number" id="fries" name="fries" min="0" value="0" onchange="updateTotal()">
                <button onclick="addToCart('fries', 50)">Add to Cart ($50)</button>
            </div>
            <div class="menu-item">
                <label for="drink">Soft Drink</label>
                <input type="number" id="drink" name="drink" min="0" value="0" onchange="updateTotal()">
                <button onclick="addToCart('drink', 40)">Add to Cart ($40)</button>
            </div>

            <!-- Total Price -->
            <div class="total-price">
                Total Price: $<span id="total">0</span>
            </div>

            <!-- Submit Order -->
            <button class="submit-btn" onclick="submitOrder()">Submit Order</button>
        </div>

        <script>
            let totalPrice = 0;
            let itemPrices = {
                'burger': 120,
                'pizza': 250,
                'pasta': 150,
                'fries': 50,
                'drink': 40
            };

            function addToCart(item, price) {
                let quantity = document.getElementById(item).value;
                totalPrice += (price * quantity);
                updateTotal();
            }

            function updateTotal() {
                totalPrice = 0;
                for (let item in itemPrices) {
                    let quantity = document.getElementById(item).value;
                    totalPrice += (itemPrices[item] * quantity);
                }
                document.getElementById("total").textContent = totalPrice;
            }

            function submitOrder() {
                alert("Order submitted! Total amount: ₹" + totalPrice);
            }
        </script>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="Menu.html">Menu</a></li>
                <li><a href="Administrator.html">Administrator</a></li>
                <li><a href="Onlineorder.html">Online Order</a></li>  
                <li><a href="Contact.html">Contact</a></li>  
            </ul>
        </nav>
        <footer>
            @2024 STAR KITCHEN(S STAR ASHIL)
        </footer>
    </body>
</html>
```

## Contact.html:
```
<html>
    <head>
        <title>Contact Us - Soul Kitchen</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                background-image: url("https://png.pngtree.com/thumb_back/fh260/background/20220225/pngtree-blue-smoke-glows-in-the-dark-image_1035687.jpg");
                background-size: cover;
                color: aliceblue;
                margin: 0;
                padding: 0;
            }
            header {
                background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQduwbE35QJWXRIvc82jBmsOhRQHWaOv_v2Mg&s");
                padding: 20px;
                text-align: center;
                color: aliceblue;
                background-size: cover;
            }
            header h1 {
                margin: 0;
                font-size: 50px;
            }
            .contact-form {
                max-width: 600px;
                margin: 50px auto;
                padding: 20px;
                background: rgba(0, 0, 0, 0.7);
                border-radius: 8px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            }
            .contact-form h2 {
                text-align: center;
                font-size: 32px;
                margin-bottom: 20px;
            }
            .contact-form label {
                font-size: 18px;
                margin-bottom: 8px;
                display: block;
            }
            .contact-form input, .contact-form textarea {
                width: 100%;
                padding: 10px;
                margin-bottom: 15px;
                border: 1px solid #ccc;
                border-radius: 4px;
                font-size: 16px;
            }
            .contact-form input[type="submit"] {
                background-color: #d74f0e;
                color: aliceblue;
                border: none;
                padding: 12px 20px;
                cursor: pointer;
                font-size: 18px;
                width: 100%;
                border-radius: 4px;
            }
            .contact-form input[type="submit"]:hover {
                background-color: #c14c0c;
            }
            .contact-info {
                text-align: center;
                font-size: 18px;
                margin-top: 30px;
            }
            .contact-info p {
                margin: 10px 0;
            }
            nav{
                position: fixed;
                top:0%;
                right:0%;
                padding: 10px;
                z-index: 1000;
                
            }
            nav ul{
                list-style:none;
                display: flex;
                padding :0;
                margin:0;
            }
            nav ul li{
                margin-left: 20px;
            }
            nav ul li a{
                color:rgb(215, 25, 15);
                font-size: 20px;
                font-style:italic;
                text-decoration: none;
            }
            footer{
                bottom:0%;
                position: fixed;
                width:100%;
                background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSm18eBadaqCzW5XTKA-c434AR5co6NgyoT9w&s");
                text-align: center;
                font-style: arial;
                color: aliceblue;
                left:0%;
                background-size:cover;
                padding:20px;
                font-size:18px;
                
    
    
                
                
              
                
    
            }
        </style>
    </head>
    <body>

        <header>
            <h1>STAR KITCHEN - CONTACT US</h1>
        </header>

        <div class="contact-form">
            <h2>Get in Touch</h2>
            <form action="#" method="post">
               
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>

                
                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>

                
                <label for="phone">Your Phone</label>
                <input type="text" id="phone" name="phone" placeholder="Enter your phone number" required>

                
                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="4" placeholder="Write your message here" required></textarea>

                
                <input type="submit" value="Submit">
            </form>
        </div>

        
        <div class="contact-info">
            <h3>Visit Us:</h3>
            <p>Star Kitchen</p>
            <p>Tambaram,Chennai-600045</p>
            <p><strong>Phone:</strong> +91 123 456 7890</p>
            <p><strong>Email:</strong> info@soulkitchen.com</p>
            <p><strong>Hours:</strong> Mon-Sun: 10:00 AM - 10:00 PM</p>
        </div>
        <nav>
            <ul>
                <li><a href="Home.html">Home</a></li>
                <li><a href="Menu.html">Menu</a></li>
                <li><a href="Administrator.html">Administrator</a></li>
                <li><a href="Onlineorder.html">Online Order</a></li>  
                <li><a href="Contact.html">Contact</a></li>  
            </ul>
        </nav>
        <footer>
            @2024 STAR KITCHEN(S STAR ASHIL)
        </footer>

    </body>
</html>
```

## OUTPUT:
## Home.html
![alt text](star/restapp/static/1.png)

## Menu.html:
![alt text](star/restapp/static/2.png)

## Administrator.html:
![alt text](star/restapp/static/3.png)

## Onlineorder.html:
![alt text](star/restapp/static/4.png)

## Contact.html:
![alt text](star/restapp/static/5.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
