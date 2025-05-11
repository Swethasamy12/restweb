# Ex.07 Restaurant Website
## Date:

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
```
<html>
    <head>
        <title>BITE BLISS</title>
    </head>
    <style>
    body{
        background-image: url(foodpp.jpg);
        background-size: cover;
        background-position:center;
        background-blend-mode: color;
        
    }
    </style>
    <ul class="menu-items">
        <li><a href="#HOME">HOME</a></li><br>
        <li><a href="#menu">MENU</a></li>
    </ul>

        <center><h1> BITE BLISS</h1></center>
        <center><P>SAVOR THE FLAVOR,SAVOR THE MOMENT</P></center>
        <hr>
        <center><p style="font-size: medium;font-style: italic;font-weight: bold;">Welcome to Bite Bliss resturant,Where the art of fine dining meets the warmth of a home-cooked meal. Our chefs are inspired by the
             freshest ingredients and the richest flavours from around the world, crafting dishes that are both fimiliar and innovative. From the crackle of
             our wood-fired oven to the sparkle of our expertly curated wine list, every detail is designed to transport you to a place of comfort and joy.
             Whether you're gathering with friends, celebrating a special occasions, or simply savoring a quiet night out,our resturant is your HEAVEN.come,let us
            feed your body and nourish your soul.</p></center>
        <p style="font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"style="font-size:medium"><h3><center>
        <table>
            <tr>
                <td><img src="food2.jpg"></td>
                <td><img src="food3.jpg"></td>
                <td><img src="food23.jpg"></td>
            </tr>
            <tr>
                <td><h3><center>Italian Dish Lansanga<br>Price:299</center></h3></td>
                <td><h3><center>Blueberry Pie<br>Price:199</center></h3></td>
                <td><h3><center>Sausage and Pepper<br>Price:249</center></h3></td>
            </tr>
        <center>
            <tr>
                <center>INDULGE IN THE ART OF FINE DINING✔️</center><br>
            </tr>
        </center>
            <h2><center>100+ DISHES ARE AVAILABLE</center></h2>
            <h2><center>OPENING OFFER 50% Discount</center></h2>
            <hr>
            <h3>FIND IT!EAT IT!
            </h3>
        </table>
        <hr>
        <section id="menu">
            <a href="foodmenu.html">FOR MORE MENU</a>
        </section>



        <br>
        <section id="click here">
            <div class="form-container">
                <a href="food2page.html">ORDER</a>
            </div>
        </section>
```
```
<html>
<head>
    <title>Ordered People's Information</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .form-container {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #f9f9f9;
        }
        label {
            display: block;
            margin-bottom: 10px;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <center>

    <h1>Ordered People's Information</h1>

    </center>

    <div class="form-container">
        <form action="submit_form.php" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter full name" required>

            <label for="food type">food type:</label>
            <input type="number" id="food" name="food" placeholder="Enter food" required>

            <label for="address">Address:</label>
            <input type="text" id="address" name="address" placeholder="Enter address" required>

            <label for="Quantity">Quantity:</label>
            <select id="Quantity" name="Quantity" required>
                <option value="One">One</option>
                <option value="Two">Two</option>
                <option value="Three">Three></option>
            </select>

            <label for="comments">Additional Comments about food:</label>
            <textarea id="comments" name="comments" placeholder="Enter any additional comments" rows="4"></textarea>

            <button type="submit">Submit</button>
        </form>
    </div>

</body>
</html>
```
```
<html>
    <head>
        <title>FOOD MENU</title>
        <Center>
            <hr>
            <hr>
            <h1>
            <caption>BITE BLISS</caption><br>
            </h1>
            <h2> FOOD MENU</h2>
        </Center>
            <hr>
            <hr><br>
            <center>
            <h1>BRUSCHETTA:<br>
            <img src="foodmenu1.jpg"><br>Toast bread slices , toped with diced tomatoes olive oil, garlic, salt and pepper<br>
            <br>PRICE:259</h1><br><hr>
            <h1>ITALIAN PASTA:<br>
            <img src="foodmenu2.jpg"><br>Pesto pasta with basil,garlic,pine nuts,parmesan cheese<br>
            <br>PRICE:350</h1><br><hr>
            <h1>CHICKEN PARMESAN:<br>
            <img src="foodmenu3.jpg"><br>Bread chicken breasts,fry and toped with marina sauce and mozzarella cheese.Bake at 400 degree farenheit, for 15-20 mins<br
            <br>PRICE:199</h1><br><hr>
            <h1> SPAGHETTI BOLOGNESE:<br>
            <img src="foodmenu4.jpg"><br>Cooked ground beef with onion, garlic, tomatoes, and beef broth serve with spaghetti<br>
            <br>PRICE:239</h1><br><hr>
            <h1>PIZZA SAUCE MARGHERITA:<br>
            <img src="foodmenu5.jpg"><br>Top pizza with tomato sauce, mozzarella cheese, and basil leaves. Bake at 500 degree celcius , for 10-12mins<br>
            <br>PRICE:159</h1><br><hr>
            <h1>FETTUCCINE ALFEREDO:<br>
            <img src="foodmenu6.jpg"><br>Combine cooked fettuccine, butter, heavy cream, and parmesan cheese<br>
            <br>PRICE:239</h1><br><hr>
            <h1>POLLO ALLA CACCIATORA:<br>
            <img src="foodmenu7.jpg"><br>Saute chicken breast with onion, garlic, mushroom, and tomatoes. Add white wine and simmer<br>
            <br>PRICE:339</h1><br><hr>
            <h1>RISOTTO ALLA MILANESE:<br>
            <img src="foodmenu8.jpg"><br>Cook Ariborio rice with chicken broth, saffron, and butter. Stir in parmesan cheese<br>
            <br>PRICE:269</h1><br><hr>
            <h1>SPAGHETTI CARBONARA<br>
            <img src="foodmenu9.jpg"><br>With bacon or pancetta, eggs, parmesan cheese<br>
            <br>PRICE:270</h1>
            </center>
         </head>
         <body style="background-color:bisque;">
            <style>
                h1,h2{
                    font-family:Georgia, 'Times New Roman', Times, serif ;
                    font-size:x-large ;
                    font-style:bold;
                    color:black;
                }
            </style>
</html>
```


## OUTPUT:
![Screenshot 2025-05-11 115412](https://github.com/user-attachments/assets/f6e11420-b5e9-4367-bf65-a6bd719e35a6)
![Screenshot 2025-05-11 115458](https://github.com/user-attachments/assets/1fb6272a-3aaa-4cfa-9cfc-b89522aa1e3e)
![Screenshot 2025-05-11 115523](https://github.com/user-attachments/assets/1f00a7a1-9beb-480d-8806-df0d3b351864)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
