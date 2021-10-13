<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Search Engine</title>
    <style>
      h1{
      color:white;
      background-color:green;
      text-align: center;
      font-size: 50px;
      transition: 1s;
      font-style:all;
    }
    h1:hover{
      letter-spacing: 8px;
      background-color:blue;
    }

    input{
      color:white;
      background-color:green;
      text-align: center;
      font-size: 30px;
      transition: 1s;
      font-style:all;
    }
    input:hover{
      letter-spacing: 8px;
      background-color:blue;
    }

    label{
      color:white;
      background-color:black;
      text-align: center;
      font-size: 40px;
      transition: 1s;
      font-style:all;
    }
    label:hover{
      letter-spacing: 8px;
      background-color:blue;
    }

    button{
      color: red;
      background-color:black;
      text-align: center;
      font-size: 30px;
      transition: 1s;
      font-style:all;
    }
    button:hover{
      letter-spacing: 8px;
      background-color:blue;
    }

    button {
  box-shadow: 0 16px 20px 0 rgba(0,0,0,0.2);
  transition: 1s;
  width: 20%;
  height:100%;
  box-sizing:60px;
  float:middle;
}

button:hover {
  box-shadow: 0 22px 22px 0 rgba(0,0,0,1.5);
  color:white;
  background: green;
}

.container {
  padding: 8px 16px;
}

option{
      color: red;
      background-color:black;
      text-align: center;
      font-size: 40px;
      transition: 1s;
      font-style:all;
    }
    option:hover{
      letter-spacing: 8px;
      background-color:blue;
    }

    </style>
</head>
<body>
    <h1 style="text-align: center; font-size: 50px;">Books to Read</h1>
    <p style="font-size:35px;">There are a lot of books to read for you</p>
    <a style="font-size:40px;" href="https://google.com">Click here to go to The Website</a>
    <marquee behavior="" direction="right" style="color: rgb(0, 255, 0); font-size: 50px; background:rgb(255, 0, 0);">Welcome To The Html Server V:5.19
    </marquee>

    <h1>SHOW CHECKBOXES</h1>
    <form action="/action_page.php">
      <input type="checkbox" name="" id="vechile1" name="vechile1" value="Bike"> 
      <label for="vechile1">I have a bike</label><br>
      <input type="checkbox" name="" id="vechile2" name="vechile2" value="Car"> 
      <label for="vechile2">I have a Car</label><br>
      <input type="checkbox" name="" id="vechile3" name="vechile3" value="Boat"> 
      <label for="vechile3">I have a Boat</label><br>
      <input type="submit" value="submit">

      <select>
        <option>--Select State--</option>
        <option>Andhra Pradesh</option>
    <option>Arunachal Pradesh</option>
    <option>Assam</option>
    <option>Bihar</option>
    <option>Chhattishghar</option>
    <option>Goa</option>
    <option>Gujarat</option>
    <option>Haryana</option>
    <option>Himachal Pradesh</option>
    <option>Jharkhand</option>
    <option>Karnataka</option>
    <option>Kerala</option>
    <option>Madhya Pradesh</option>
    <option>Maharashtra</option>
    <option>Manipur</option>
    <option>Meghalaya</option>
    <option>Mizoram</option>
    <option>Nagaland</option>
    <option>Odisha</option>
    <option>Punjab</option>
    <option>Rajasthan</option>
    <option>Sikkim</option>
    <option>Tamil Nadu</option>
    <option>Telangana</option>
    <option>Tripura</option>
    <option>Uttar Pradesh</option>
    <option>Uttarakhand</option>
    <option>West Bengal</option>
      </select>

      <label>Month: </label>
  <input type="month" value="month" name="month" />


    <label>Time: </label>
  <input type="time" value="time" name="time" />


    <button type="submit" value="Submit">Submit</button>
<button type="reset" value="Reset">Reset</button>


    </form>
   
</body>
</html>

<!--LOADER-->
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.loader {
  border: 16px solid red;
  border-radius: 50%;
  border-top: 16px solid #17D4FE;
  width: 120px;
  height: 120px;
  -webkit-animation: spin 2s linear infinite; /* Safari */
  animation: spin 2s linear infinite;
}

/* Safari */
@-webkit-keyframes spin {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
</style>
</head>
<body>

<h2 style="font-size: 40px; background:blue; color: yellow; text-align: center;">This Site Has Been Restoring</h2>

<div class="loader"></div> 

</body>
</html>

