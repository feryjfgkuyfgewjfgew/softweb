# Ex.07 Software Product Company Website
## Date:
## name:naresh.r
## roll:212223240104
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
```
## main html
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    <style>
        a {

            text-decoration: none;

            font-size: 20px;
            color: red;
            padding: 5%;
        }

        a:hover {
            color: black;
        }
    </style>

</head>

<body>

    <div class="row" style="height: 100px; background-color:rgba(25, 180, 246, 0.63);">



        <div class="col-2">

            <img src="logo.png" width="40%" style="padding-top: 2%;">

        </div>

        <div class="col-7" style="padding-top: 30px; ">
            <a href="new.html">Home</a>
            <a href="about.html">People</a>
            <a href="peo.html">Products</a>
            <a href="Untitled-1.html">Contact</a>

        </div>

        <div class="col-3" style="padding-top: 30px; padding-left: 100px;">

            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
            <a href=""><i class="bi bi-whatsapp"></i></a>

        </div>

    </div>

    <div>

        <img src="nsss" style="width: 100%; height: 700px;">

    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
## home
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            
            
        </style>
    </head>
<body background="nsss">
    <div class="banner">
        <br>
        
        </div>
        <div  style="align-items: center;">
            <div class="text">
                <h2 ;">InnovateSoft Solutions </h2>
                <br>
                <p> Transforming Ideas into Impartful Reality through Precision Coding and Innovation </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by Amirtha Roopa.S (212221220005) </center>
    </footer>
</body>
</html>

## product
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    <style>
        a {

            text-decoration: none;

            font-size: 20px;
            color: red;
            padding: 5%;
        }

        a:hover {
            color: black;
        }
    </style>

</head>

<body>

    <div class="row" style="height: 100px; background-color:rgba(25, 180, 246, 0.63);">



        <div class="col-2">

            <img src="logo.png" width="40%" style="padding-top: 2%;">

        </div>

        <div class="col-7" style="padding-top: 30px; ">
            <a href="new.html">Home</a>
            <a href="about.html">People</a>
            <a href="peo.html">Products</a>
            <a href="Untitled-1.html">Contact</a>

        </div>

        <div class="col-3" style="padding-top: 30px; padding-left: 100px;">

            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
            <a href=""><i class="bi bi-whatsapp"></i></a>

        </div>

    </div>

    <div>

        <img src="nsss" style="width: 100%; height: 700px;">

    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>
## contact
<body>
                    <div class="banner">
                        <br>
                        <div class="navbar">
                            <h1 class="logo"> <span>WEB</span> WORLD</h1>
                            <ul>
                                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                                <li><a href="product.html"> Products </a></li>
                                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
                            </ul>
                            <form action="" method="get">
                                <input type="text" placeholder="Enter to Search">
                                <button type="submit"> Search </button>
                            </form>
                        </div>
                        <div class="image">
                            <table cellspacing="20"> 
                                <tr align="center">
                                    <td> <img src="nsss"> </td>
                                    <td> <img src="nsss"> </td>
                                    <td> <img src="nsss"> </td>
                                    <td> <img src="nsss"> </td>
                                    <td> <img src="nsss"> </td>
                                    <td> <img src="nsss"> </td>
                                </tr>
                                <tr align="center">
                                    <th>  naresh.r</th>
                                    <th> SURENDAR </th>
                                    <th>NIRANJAN</th>
                                    <th> ROHITH </th>
                                    <th> SHYAM </th>
                                    <th> Ramos </th>
                                </tr>
                                <tr align="center">
                                    <td> CEO </td>
                                    <td> CEO, Co-Founder </td>
                                    <td> CTO, Co-Founder </td>
                                    <td> Director </td>
                                    <td> Asst. Director </td>
                                    <td> Dy. Director </td>
                                </tr>
                            </table>
                        </div>
                    </div>
                    <footer>
                        <center> Designed and Developed by RajaGopal (23002920) </center>
                    </footer>
                </body>
                </html>
```



## OUTPUT:
![image](https://github.com/feryjfgkuyfgewjfgew/softweb/assets/150319377/9b8250b6-34fa-4213-b512-8c48be87d1ed)
![Screenshot 2024-05-01 103237](https://github.com/feryjfgkuyfgewjfgew/softweb/assets/150319377/d27afe47-ef6f-4c38-a862-a800a0fb9cdd)
![Screenshot 2024-05-01 103547](https://github.com/feryjfgkuyfgewjfgew/softweb/assets/150319377/5facc226-0faa-45b7-b3e0-65841c6e9df6)
![Screenshot 2024-05-01 103427](https://github.com/feryjfgkuyfgewjfgew/softweb/assets/150319377/18fb3dd3-d860-4634-a4aa-601741a17fb9)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
