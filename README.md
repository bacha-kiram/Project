# Project
this is my part of the project
this is my way of ceating an admin for the project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMIN</title>
    <style>
        body{
            background-color: black;
                }
        
        button{
            background: linear-gradient(rgb(255, 255, 255), rgb(0, 0, 255) );
            font-size: 40px;
            border-radius: 20px;

        }
        button::before {
            position: absolute;

        }
        .x1{
            position: absolute;

            top: 50%; /* Position the text vertically in the center */
            left: 50%; /* Position the text horizontally in the center */
            transform: translate(-50%, -50%); /* Adjust to exactly center the text */
            width: 800px;
            height: 555px;
            background : transparent;
            background-color: chartreuse;
            border: 4px solid;
        }
     .box{
            font-size: 30px;
            align-items: center;
        }
        .box input{
            background: transparent;
            width: 200px;
            height: 30px;
        }
        .box input:valid{
            border-bottom-color: gray;
        }
        .f{
            font-size: 33px;
        }
    </style>
</head>
<body>
    <img src="c:\VSCode\HTML\11111111\7ynF.gif" width="100%" alt="background-image">
    <script type="text/javascript">
        
        function login() {
            var Username = document.getElementById("Username").value;
            var Password = document.getElementById("Password").value;
            var errorMessage = document.getElementById("error-message");
            var adminUsername  = "admin";
            var adminPassword  = "1234";
            if (Username === "" || Password === "") {
                alert('Please fill in both username and password');
            }
            if (Username === adminUsername && Password === adminPassword ) {
                document.write("Connexion réussie !");
                window.location.href = "file:///c:/VSCode/HTML/Untitled-1.html"; 
            } else {
                alert ("username or password incorrect.")
            }
        }    
    </script>
<center>
    <div class="x1">
    <h1> LOGIN </h1>
    <br>
    <br>
    <vid class="box">
    <label for="Username"> Username : </label>
    <input type="text" placeholder="Username" id="Username" name="Username" required>
    <br>
    <br>
    <br>
    <label for="Password"> Password : </label>
    <input type="Password" placeholder="Password" id="Password" name="Password" required>
    <br>
    <br>
    <br>
    <button onclick="login()">
       <a>Se connecter</a> 
    </button>    
    <br>
    
    
</vid class="box">
<br>
<f>Don't have an annocent ? <a href="https://www.google.com"> click here</a> </f>
    </div class="x1">
    
</center>
</body>
</html>
