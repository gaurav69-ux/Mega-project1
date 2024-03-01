# Mega-project1
this is registration website

-HTML CODE-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mega-Project</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav id="nav1">
          
            <div id="logo">logo</div>
            <div id="menu">
              <ul>
                <li>aaaa</li>
                <li>bbbb</li>
                <li>cccc</li>
                <li>dddd</li>
              </ul>
            </div>
      
        </nav>

    <nav id="nav2"></nav>
    </header>

    <main>

      <div id="img">
        IMAGES SECTION
      </div>

      <div id="notice-board">ALL EVENT LIST</div>


    </main>

    <footer>
      <h1 style="color: white; font-size: 50px; text-align: center;">FOOTER SECTION</h1>
    </footer>
    
</body>
</html>

-CSS CODE-

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    background-color: rgb(232, 221, 207);
}

#nav1{
    gap: 35vw;
    display: flex;
    align-items:center;
    justify-content: space-between;
    background-color: rgb(161, 72, 72);
    padding: 10px;
}

#nav2{
    background-color: red;
    padding: 20px;
}

#logo{
    padding: 2px;
    background-color: blue;
    
}

ul{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 5vw;
}

#img{
    font-size: 50px ;
    color: white;
    padding: 170px;
    background-color: rgb(122, 110, 110);
}

#notice-board{
    text-align: center;
    font-size: 50PX;
    margin: 20px 70px;
    height:90vh ;
    width: 57%;
    background-color: rgb(172, 89, 89);
    border-radius: 25px;
}

footer{
    height: 40vh;
    width: 100%;
    background-color: rgb(36, 22, 22);
}

