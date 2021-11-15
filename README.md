<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"> 
        <meta http-equiv="X-UA-Compatible" content="IE=edge"> 
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
        <link rel="preconnect" href="https://fonts.googleapis.com"> 
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
        <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto&display=swap" rel="stylesheet">
         <link rel="stylesheet" href="login.css" /> 
         <title>Login</title></head><body> 
             <!-- <img src="assets/blob_1.svg" id="blob1" /> 
                <img src="assets/blob_2.svg" id="blob2" />
                 <img src="assets/blob_3.svg" id="blob3" /> 
                 <img src="assets/blob_4.svg" id="blob4" /> -->
                  <div> <h1>hello.</h1> 
                    <select> 
                        <option>+91</option> 
                        <option>+92</option> 
                        <option>+93</option> 
                        <option>+94</option>
                     </select>
                     <input type="number" placeholder="Enter your Phone Number" /> 
                     <br /> 
                     <br /> 
                     <button>Send OTP</button>
     <br /> <br />
      <hr />
       <p> By logging in, you are accepting the <br /> terms and conditions. </p> 
    </div>
    <input class="input1" type="text" placeholder="User Name" required /> 
    <input class="input1" type="text" placeholder="Phone Number" pattern="\9[0-9]+" minlength="10" required /> 
    <input class="input1" type="email" placeholder="Enter Your Gmail" required /> 
    <input class="input1" type="password" placeholder="Enter Password" maxlength="8"required /> 
    <p>Select Option of Your Gender</p> 
    <input type="checkbox" checked />
    <span>Male</span>
    <br>
    <input type="checkbox" /><span>Female</span>
    <br> 
    <input type="checkbox" /><span>Others</span>
    <br> 
    <button type="submit">Submit</button> 
</form> body { 
    padding: 0px; 
    background-color: #edf2f7;
}
div { 
    display: inline-block;
     background-color: rgba(255,255,255, 0.7);
      padding: 40px; 
      padding-top: 20px; 
      margin-left: 15%; 
      margin-top: 5%; 
      border-radius: 10px;
       z-index: 10; 
       margin-top: 25%;
    }
    
    h1 { 
        padding: 0xp; 
        margin: 0px; 
        text-align: center; 
        font-family: 'Pacifico', cursive;
    }
button {background-color: transparent; /* border-style: solid; border-width: 2px; border-color: #7e37d8; */ 
     border: 2px solid #73378d; 
     border-radius: 20px;
      padding: 10px; 
      font-family: 'Roboto', sans-serif; 
      margin-left: 40%;
}
Input{
    padding: 10px;
     width: 200px; 
     border-radius: 25px; 
     margin-top: 15px; 
     border-top-left-radius: 0px; 
     border-bottom-left-radius: 0px; 
     border: 1px solid #EFEFEF;
    }
    select { 
        padding: 10px; 
        border-radius: 25px; 
        border-top-right-radius: 0px; 
        border-bottom-right-radius: 0px; 
        border: 1px solid #EFEFEF;
    }
select {
     padding: 10px; 
     border-radius: 25px;
      border-top-right-radius: 0px;
       border-bottom-right-radius: 0px; 
       border: 1px solid #EFEFEF;}
p { 
    text-align: center; 
    color: #BBBBBB;
}
img { 
    z-index: 1;
}
input1{ 
    display: block; 
    margin: 20px;
     margin-left: 130px; 
     padding: 10px;
    }
    input{
        margin: 10px;
         margin-left: 170px;
        }
        div{
             margin-left: 40%; 
             margin-right: 32%;
}

h2{ 
    color: rgb(240, 106, 83); 
    margin-left: 170px;
}
p{ margin-left: 120px;
}
button{
    margin-left: 170px
}
div{ 
    border: solid #05fc5c; 
    margin-top: 90px; 
    border-radius: 20px; 
    background-color: #f7bcf0;
}
body{ 
    background-color: #f5d37d;
}
form{
     margin-bottom: 30px;
    } 

</div> 
</body>
</html>
