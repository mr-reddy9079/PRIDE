<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>.main-container{
    margin: 10px;
    border:1px solid grey;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    width:600px;
    padding: 20px;
}
.head{
    font-size: 30px;
    font-style: bold;
    font-weight: 600;
    font-family: serif;
    padding-left: 10px;
}
.Namecontainer
{
    display:flex;
    flex-direction:row;
}
.firstcont{
    display: flex;
    flex-direction: column;
    padding-left: 10px;
}
.firstname{
    color:black;
    font-size:15px;
    font-family: sans-serif;
}
#first{
color:azure;
margin:3px;
padding: 5px;
border:1px solid grey;
border-top-left-radius: 5px;
border-top-right-radius: 5px;
border-bottom-left-radius: 5px;
border-bottom-right-radius: 5px;
}
.secondcont{
    display:flex;
    flex-direction: column;
    padding-left: 20px;
    margin-left: 20px;
}
.secondname{
    color:black;
    font-size:15px;
    font-family: sans-serif;

}#last{
    color: azure;
    margin:3px;
    padding: 5px;
    border:1px solid grey;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius: 5px;
}
.emailcont{
    display:flex;
    flex-direction: column;
    padding-left: 15px;
    margin-top: 5px;
}
.emailhead{
    font-size:15px;
    font-family: sans-serif;
}
#email{
    color: azure;
    padding: 5px;
    width: 375px;
    margin-top: 3px;
    border:1px solid grey;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius: 5px;
}
#malelabel{
    margin-left: 20px;
}
.malelabel{
    font-size: 20px;
    padding-left: 10px;

}
#femalelabel{
    padding-left: 30px;
    margin-left: 20px;
}
.femalelabel{
    font-size: 20px;
    padding-left: 10px;
    
}
.radiocont{
    display:flex;
    flex-direction: row;
    
}
.citycont{
    display: flex;
    flex-direction: column;
    padding-left: 10px;
    margin-top: 5px;
}
.cityname{
    color:balck;
    font-size:15px;
    font-family: sans-serif;
}
#city{
color:azure;
margin:3px;
padding: 5px;
border:1px solid grey;
border-top-left-radius: 5px;
border-top-right-radius: 5px;
border-bottom-left-radius: 5px;
border-bottom-right-radius: 5px;
width:200px
}
.container{
    display: flex;
    flex-direction: row;
}
.citycont{
    display: flex;
    flex-direction: column;
    padding-left: 10px;
}
.cityname{
    color:black;
    font-size:15px;
    font-family: sans-serif;
}
#city{
color:azure;
margin:3px;
padding: 5px;
border:1px solid grey;
border-top-left-radius: 5px;
border-top-right-radius: 5px;
border-bottom-left-radius: 5px;
border-bottom-right-radius: 5px;
}
#dropdownMenu2{
    margin-left: 20px;
}
.passwordcontainer
{
    display:flex;
    flex-direction:row;
   
}
.createpassword{
    display: flex;
    flex-direction: column;
    padding-left: 20px;
}
.create{
    color:black;
    font-size:15px;
    font-family: sans-serif;
}
#create{
color:azure;
margin:3px;
padding: 5px;
border:1px solid grey;
border-top-left-radius: 5px;
border-top-right-radius: 5px;
border-bottom-left-radius: 5px;
border-bottom-right-radius: 5px;
}
.resetpassword{
    display:flex;
    flex-direction: column;
    padding-left: 20px;
    margin-left: 20px;
}
.reset{
    color:black;
    font-size:15px;
    font-family: sans-serif;

}#reset{
    color: azure;
    margin:3px;
    padding: 5px;
    border:1px solid grey;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border-bottom-right-radius: 5px;
}
.button{
    display: flex;
    flex-direction: column;
}
.span{
    color:blue;
}
.para{
    padding-left: 140px;
   
}
</style>
</head>
<body>
    <div>
        <div class="main-container">
            <h1 class="head">Sign up</h1>
          <div class="Namecontainer">
            <div class="firstcont">
                 <label for="first" class="firstname">First name:</label>
                 <input type="text" id="first" placeholder="Enter your first name"/>
            </div>
            <div class="secondcont">
                <label for="last" class="secondname">Last name:</label>
                <input type="text" id="last" placeholder="Enter your second name"/>
            </div>
          </div>
            <div class="emailcont">
                <label for="email" class="emailhead">Email:</label>
                <input id="email" placeholder="Enter your email"/>
                <p>we'll never share your email with anyone else</p>
            </div>
            <div class="radiocont">
                <input type="radio" id="malelabel" />
                <label for="malelabel" class="malelabel">Male</label>
                <input type="radio" id="femalelabel"/>
                <label for="femalelabel" class="femalelabel">Female</label>  
            </div>
            <div class="container">
               <div class="citycont">
                   <label for="city" class="cityname">City:</label>
                   <input type="text" id="city" />
                </div>
                <div>
                    <div class="dropdown">
                        <h1 class="cityname">Country:</h1>
                        <input type="search" id="dropdownMenu2" placeholder="united states"/>
                      </div>
                </div>
            </div>
            <div class="passwordcontainer">
                    <div class="createpassword">
                         <label for="create" class="create">Create password</label>
                         <input type="password" id="create" default/>
                    </div>
                    <div class="resetpassword">
                        <label for="reset" class="reset">Repeat password</label>
                        <input type="password" id="reset" />
                    </div>
            </div>
            <div class="button">
            <button class="btn btn-primary">Register</button>
            <div>
            <input type="checkbox" default/>
            <label>I am agree with <span class="span">terms and conditions</span></label>
            </div>
        </div>
        </div>
        <p class="para">Have an account?<span class="span">Log In</span></p>
        </div>
        
</body>
</html>
