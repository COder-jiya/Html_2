<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>
<style>
    
h1{ 
    text-align: center;
}
input{
    padding: 5px;
    margin: 10px;
    background-color: lightgoldenrodyellow;
    border-radius: 50px;
}
fieldset{
    padding: 30px;
    background-color: pink;
    margin: 50px;
    width: 400px;
    height: auto;
}
body{
    font-family: cursive;
}
</style>

<body>

<form>
    <fieldset>
        <h1>Form</h1>
    
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name"><br><BR>
  


     <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter password"><br><br>

     <label for="age">Age:</label>
     <input type="number" id="emale" name="emale" placeholder="Enter your age"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>
  

    <label for ="Gender">Gender:</label>
     <label for="male">Male:</label>
    <input type ="radio" id="male" name="gender" value="male"><br>

    <label for="female">Female:</label>
    <input type="radio" id="female" name="gender" value="female"><BR>
   

        <input type="submit" name="submit"id = "submit" value="submit">
        


    

</fieldset>
</form>
</body>
</html>
