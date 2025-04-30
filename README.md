# Practice-Project-HTML-Form-and-Video-Embedding
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel ="stylesheet" href="style.css">
    
</head>
<body>
    <h3>Registration Form</h3>
    <form action="action.php">
        <input type="text" placeholder="username">
        <br>
        <input type="password" placeholder="password">
        <br><br>
        <h3>Choose your class</h3>
        <br><br>
        <label for="id 1">
        <input type="radio" value="class X" name="class" id="id 1">classX
    </label>
    <br>
    <label for="id 2">
        <input type="radio" value="classXI" name="class" id="id 2">classXI
    </label>
    <br><br>
    <h3>Choose your subject</h3>
    <label for="Maths">
        <input type="checkbox" value="Maths" name="subject" id="101">Maths

    </label>
    <br><br>
    <label for="Physice">
        <input type="checkbox" value="Physice" name="subject" id="102">Physice

    </label>
    <br><br>
    <label for="Chemistry">
        <input type="checkbox" value="Chemistry" name="subject" id="103">Chemistry
        <br><br>
    <label for="Hindi">
        <input type="checkbox" value="Hindi" name="subject" id="104">Hindi

    </label>
    <br><br>
    <label for="Maths">
    <input type="checkbox" value="English" name="subject" id="105">English

</label>
<br><br>
<h3>Select your city</h3>
<br>
<select name="city" id="city">
    <option value="Delhi">Delhi</option>
    <option value="Pune">Pune</option>
    <option value="Banglore">Banglore</option>
    <option value="Mumbai">Mumbai</option>
</select>
<br><br>
<textarea name="feedback" id="101" placeholder="please give your valuable feedback here" row="5">
</textarea>
<br><br>
<input type="submit" value="submit">
<br><br>
<iframe width="560" height="315" src="https://www.flipkart.com/">amazon</iframe>
<br><br>
<h3>My Video</h3>
<video width="560" height="315" src="/My Video.mp4" controls loop>My Video</video>

    </form>
</html>
