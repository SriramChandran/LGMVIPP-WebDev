# LGMVIP-WebDev-Task-1

 index.html->
    
     Index.html
   <!DOCTYPE html>
<html>
    <head>
        <title>Designing the sign in form</title>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <div class="signin">
            <form>
                <h2>Sign in</h2>
                <input type="text" placeholder="Enter username">
                <input type="text" placeholder="Enter password">
                <button class="btn">Sign In</button>
            </form>
        </div>
    </body>
</html>


Style.css


   html
{
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100vh;
}

body
{
    margin: 0;
    padding: 0;
    width: 100%;
    height: 100vh;
    background-size: cover;
    display: table;
}
.signin
{
    border: 1px solid rgba(255,255,255,0.3);
    border-radius: 5px;
    padding: 3em;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
}
h2
{
    margin-top: 0px;
    font-family: Source Sans Pro;
    font-weight: lighter;
    color:#fff;
    font-size: 50px;
    text-align: center;;
}
input
{
    display: block;
    width:320px;
    height:50px;
    background: rgba(0,0,0,0.3);
    outline: none;
    border: 1px solid rgba(0,0,-0,0.5);
    font-family: Sorce Sans Pro;
    font-weight: lighter;
    font-size: 14px;
    margin-bottom: 10px;
    padding-left: 10px;
    border-radius: 5px;
}
button 
{
    width: 332px;
    height: 50px;
    font-size: 16px;
    background: #000;
    font-weight: lighter;
    color: #fff;
    border: 0px;
    border-radius: 5px;
}
