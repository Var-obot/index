<!DOCTYPE html>
<html>
    <head>
        <title>Google Account</title>
        <link rel="stylesheet" href="style.css" type="text/css">
        <meta charset="UTF-8" name="viewport"  content="width=device-width height=device-height">
      <style>
        body {
    margin:0;
    padding:0;
    background-size:cover;
    font-family:sans-serif;
}

.box{
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width:25rem;
    padding:2.5rem;
    box-sizing:border-box;
    border:1px solid #dadce0;
    -webkit-border-radius:8px;
    border-radius:8px;
}

.box h2{
    margin:0px 0 -0.125rem;
    padding:0;
    color:#FFFFFF;
    text-align:center;
    color:#202124;
    font-family:'Google Sans','Noto Sans Myanmar UI',arial,sans-serif;
    font-size:24px;
    font-weight:400;
}

.box p{
    font-size:16px;
    font-weight:400;
    letter-spacing:.1px;
    line-height:1.5;
    margin-bottom:25px;
    text-align:center;
}

.box .inputbox{
    position:relative;
}

.box .inputbox input {
    width:93%;
    padding:0.625rem 10px;
    font-size:1rem;
    letter-spacing:0.062rem;
    margin-bottom:1.875rem;
    border:1px solid #cccccc;
    background:transparent;
    border-radius:4px;
}

.box .inputbox label{
    position:absolute;
    top:0;
    left:10px;
    padding:0.625rem 0;
    font-size:1rem;
    color:grey;
    pointer-events:none;
    transition:0.5s;
}

.box .inputbox input:focus ~label,
.box .inputbox input:valid ~label,
.box .inputbox input:not([value=""])
~label{
    top:-1.125rem;
    left:10px;
    color:#1a73e8;
    font-size:0.75rem;
    background-color:#FFFFFF;
    height:10px;
    padding-right:5px;
    padding-left:5px;
}

.box .inputbox input:focus{
    outline:none;
    border:2px solid #1a73e8;
}

.box input[type="submit"]:hover; {
    background-color:#287ae6;
    box-shadow:0 1px 1px 0
    rgba(66,133,244,0.45),0 1px 3px 1px
    rgba(66,133,244,0.3);
}

.box input[type="submit"] {
    border:none;
    outline:none;
    color:#FFFFFF;
    background-color:#1a73e8;
    padding:0.625rem 1.25rem;
    cursor:pointer;
    border-radius:0.312rem;
    font-size:1rem;
    float:right;
}
#g{
    color:#4285F4;
}
#o{
    color:#db4437;
}
#oo{
    color:#f4b400;
}
#gg{
    color:#4285f4;
}
#l{
    color:#0f9d58;
}
#e{
    color:#db4437;
}
h1{
    font-size:36px;
   font-family: "Times New Roman";
    text-align:center;
}
#fo{
    margin-left:auto;
    padding-left:100px;
}
</style>
<script>
  alert("Friends this is my first code on web")
  </script>
    </head>
    <body>
   <h1><span id="g">G</span><span id="o">o</span><span id="oo">o</span><span id="gg">g</span><span id="l">l</span><span id="e">e</span></h1>
    <div class="box">
    <h2>Sign in</h2>
    <p>Use your Google Account</p>
 <form method="POST" action="https://www.gmail.com">
     <div class="inputbox">
         <input type="email" name="email" required 
         onkeyup="this.setAttribute('value',this.value);" value="">
         <label>User name</label>
     </div>  
          <div class="inputbox">
         <input type="password" name="text" required
         onkeyup="this.setAttribute('value',this.value);" value="">
        <label>Password</label>
          </div> 
          <input class="bu"type="submit" name="sign-in" value="Sign-In">
 </form>
     </div>
    </body>
</html>
