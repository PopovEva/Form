<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Fries</title>
    <link href='https://fonts.googleapis.com/css?family=Edu NSW ACT Foundation' rel='stylesheet'>
<style>
body {
    font-family: 'Edu NSW ACT Foundation';font-size: 22px;
}
</style>
<link rel="icon" type="image/x-icon" href="media/pic/icoonfries.png">
</head>
<body style="background-color: rgb(244, 196, 4);">
    <h1 style="color:rgb(247, 9, 5); text-align: center; font-size: 80px;"> John Fries <img src="media/pic/fries.png" width="100" height="100"></h1>
    ​<form style="margin-left: 20%; margin-right: 20%; text-align: center; margin-top: -5%;" action="/action_page.php;">
        <fieldset>
            <legend>Register & Place your Order:</legend> <br> 
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname"> <br>
            <label for="fname">Age:</label><br>
            <input list="age" name="age"> <br><br>
            <div style="text-align: left; margin-left: 45%;">
            <label for="Gender">Gender:</label><br>
            <input type="checkbox" id="Gender" name="Gender" value="Male">
            <label for="Male"> Male</label><br>
            <input type="checkbox" id="Gender" name="Gender" value="Female">
            <label for="Female"> Female</label><br>
            <input type="checkbox" id="Gender" name="Gender" value="Other">
            <label for="Other"> Other</label><br><br>
            </div>
            <label for="fname">Favorite Color:</label><br>
            <input type="color" name="color" value="color" id="color"> <br>
            <datalist id="age">
              <option value="0-18">
              <option value="18-35">
              <option value="35-60">
              <option value="60-120"><br>
            </datalist> <br>
            <label for="fname">Date of Birth:</label><br>
            <input type="date" name="data" id="date"> <br><br>
            <label for="fname">Delivery Address:</label><br>
            <div style="text-align: left; margin-left: 45%;">
            <input type="radio" id="Address" name="Address" value="Holon">
           <label for="html">Holon</label><br>
           <input type="radio" id="css" name="Address" value="TLV">
           <label for="css">TLV  </label><br>
           <input type="radio" id="javascript" name="Address" value="Bat Yam">
           <label for="javascript">Bat Yam</label><br><br>
           </div>
           <label for="family status">Choose a family status:</label><br>

           <select id="family status" name="family status">
           <option value="Singel">Singel</option>
           <option value="Married">Married</option>
           <option value="Divoorced">Divoorced</option>
           </select>
            <br><br>
            <label for="fname">Number of kids:</label><br>
            <input type="range" name="kids" value="range" min="1" max="15" oninput="this.nextElementSibling.value = this.value">
            <output>3</output>
            <br><br>
            <input style="color: rgb(16, 15, 15);font-size:x-large ; background-color: rgb(236, 37, 37);  " type="submit" value="Submit"> 
                  
        </fieldset>
    </form>        
</body>
</html>
