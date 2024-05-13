# Ex.07 Software Product Company Website
## Date:13/05/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### homepage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="homepage.css">
</head>
<body>
                
    <header>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="productpage.html">Products</a></li>
                <li><a href="peoplepage.html">People</a></li>
                <li><a href="contactpage.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner">
            <div class="content">
                <h1>Welcome to Our Website</h1>
                <h3>Artificial intelligence (AI) tools are software applications that use AI algorithms and machine learning techniques to perform tasks and solve problems. They can automate tasks, analyze data, and improve decision-making. AI tools can range from simple applications to more complex platforms that support advanced machine learning and data analysis. </h3>
            </div>
            <div class="login-form">
                <h2>Login</h2>
                <form action="login.php" method="post">
                    <label for="username">Username:</label>
                    <input type="text" id="username" name="username" required><br><br>
                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required><br><br>
                    <input type="submit" value="Login">
                </form>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 DEVELOPED BY VENKATANATHAN P R(212223240173)</p>
    </footer>
        

</body>
</html>
```
### peoplepage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People</title>
    <link rel="stylesheet" href="peoplepage.css">
</head>
<body>
    <header>
        <h1>Our Team</h1>
    </header>
    <div class="cirpic">
        <img class="small border" src="venky.jpg" width="100px">
        <img class="small border" src="bill.jpeg" width="120px" >
        <img class="small border" src="tata.avif" width="70px">
        <img class="small border" src="hyundai.jpeg" width="100px">
        <img class="small border" src="" width="100px">
        
        
    </div>
    <div class ="text">
        <table cellpadding="49">
            <tr class="head">
                <th>VENKATANTHAN</th>
                <th>BILL GATES</th>
                <th>RATAN TATA</th>
                <th>Chung Ju-yung</th>
            </tr>
        </table>
    </div>
    <div class="text2">
        <table cellpadding="68">
            <tr>
                <td>FOUNDER</td>
                <td>CO-FOUNDER</td>
                <td>CEO</td>
                <td>DIRECTOR</td>                
            </tr>
        </table>
    </div>

    </section>

    </main>
    <footer>
        <p>&copy; 2024 DEVELOPED BY VENKATANATHA P R(212223240173)</p>
    </footer>
</body>
</html>
```
### productpage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products</title>
    <link rel="stylesheet" href="productpage.css">
</head>
<body>
    <header>
        <h1>Our Products</h1>
    </header>
    <div class="languages">
        <div class="language">
            <img src="c++.jpg" alt="Programming Language 1">
            <h2>C++ PROGRAMMMING</h2>
        </div>
        <div class="language">
            <img src="python.png" alt="Programming Language 2">
            <h2>PYTHON PROGRAMMING</h2>
        </div>
        <div class="language">
            <img src="C PROGRAMMING.PNG" alt="Programming Language 3">
            <h2>C PROGRAMMING</h2>
        </div>
        <div class="language">
            <img src="JAVA.jpg" alt="Programming Language 4">
            <h2>JAVA PROGRAMMING</h2>
        </div>
        <div class="language">
            <img src="WEB.jpg" alt="Programming Language 5">
            <h2>WEB PROGRAMMING(HTML,CSS,JAVASCRIPT)</h2>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 VENKATANATHAN P R(212223240173)</p>
    </footer>
</body>
</html>
```
### contactpage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="contactpage.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <main>
        <form action="#" method="post" class="contact-form">
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div class="form-group">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
            </div>
            <button type="submit">Submit</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2024 VENKATANATHAN P R(212223240173)</p>
    </footer>
</body>
</html>
```
### homepage.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #ff0000;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
}

.image {
    max-width: 400px; 
}

.image img {
    width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

.banner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-image: url('home page1.jpeg'); /* Change 'background.jpg' to your image file */
    background-size: cover;
    height:550px;
    background-position: center;
    padding: 50px; /* Adjust padding as needed */
    color: #44ff00; /* Set text color to ensure readability */
}


.content {
    flex: 1;
}

.login-form {
    width: 200px;
    background-color: #fff;
    padding: 50px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.login-form h2 {
    text-align: center;
    margin-bottom: 20px;
}

.login-form label {
    display: block;
    margin-bottom: 5px;
}

.login-form input[type="text"],
.login-form input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
}

.login-form input[type="submit"] {
    width: 100%;
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 3px;
    cursor: pointer;
}

.login-form input[type="submit"]:hover {
    background-color: #555;
}
```
### peoplepage.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: rgb(15, 233, 233);
}

header, footer {
    background-color: #fb15c5;
    color: #0411ff;
    text-align: center;
    padding: 20px 0;
}

main {
    padding: 20px;
}

.product, .person, .contact-info {
    margin-bottom: 15px;
}

footer {
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Existing CSS styles */

.people {
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.pe
{
    margin-right:50px;
}



.person h2, .person p {
    margin: 0;
}

.cirpic{
    position:absolute;
    top:35%;
    margin-left: 70px;
    display: inline-block; /* Ensure each person is displayed inline */

    
}
.text{
    position:absolute;
    top:55%;
    margin-left:20px;
    font-size:15px;
    
}

.image {
    max-width: 400px; 
}

.image img {
    width: 100%;
    height: auto;
}

.text2{
    position:absolute;
    top:60%;
    margin-left:5px;
    font-size:10px;
}
```

### productpage.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: rgb(51, 233, 15);
}

header, footer {
    background-color: #e2ff07;
    color: #0048ff;
    text-align: center;
    padding: 20px 0;
}

main {
    padding: 20px;
}

.product, .person, .contact-info {
    margin-bottom: 20px;
}

footer {
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Additional CSS for product page */

/* Additional CSS for product page */

/* Additional CSS for product page */

.languages {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap; /* Allow items to wrap to the next line */
}

.language {
    text-align: center;
    width: 150px; /* Adjust the width of each language's container */
    margin: 20px; /* Add margin around each language */
}

.language img {
    width: 100%; /* Make the image fill the container */
    height: auto;
    border-radius: 50%; /* Make the image circular */
}


```
### contactpage.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, footer {
    background-color: #15d929;
    color: #ef1111;
    text-align: center;
    padding: 20px 0;
}

main {
    padding: 20px;
}

.product, .person, .contact-info {
    margin-bottom: 20px;
}

footer {
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Adjust styles as needed */
/* Additional CSS for contact page */

.contact-form {
    max-width: 500px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input[type="email"],
input[type="tel"],
input[type="text"],
textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

textarea {
    resize: vertical; /* Allow vertical resizing of text area */
}

button[type="submit"] {
    background-color: #007bff;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #0056b3;
}
```
## OUTPUT:

### homepage
![alt text](<Screenshot 2024-05-13 212213.png>)
### product
![alt text](<Screenshot 2024-05-13 211730.png>)
### people
![alt text](<Screenshot 2024-05-13 211748.png>)
### contact
![alt text](<Screenshot 2024-05-13 211757.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
