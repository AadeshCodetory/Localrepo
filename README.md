<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Home | Netflix</title>
    <link rel="stylesheet" href="style.css"/>
    <script src="bharat.js"> </script>
</head>
<body>
    <div class="nav">
        <div class="nav_left">
            <a href="index.html">
            <img class="nav_logo"  src="image/Netflix-Logo.png" alt="">
            </a>

        </div>
 <div class="nav_right">
     <img class="nav_avatar" src="image/smiley.jpg" alt="">
   </div>
</div>
    <header id="banner">
        <div id="banner_contents">
            <h1 id="banner_title"></h1>
            <div id="banner_button">
                <button id="banner_button">Play</button>
                <button id="banner_button">My List</button>
            </div>
            <p id="banner_discription"></p>
        </div>
        <div id="banner_fadeBottom"></div>
    </header>

    <div id="headrow">
        <div class="row">
            <h2 class="row_title"></h2>
            <div class="row_posters"></div>
        </div>
    </div>
    <script>
        window.addEventListener("scroll",function(){ 
            var nav=document.querySelector(".nav");
            nav.classList.toggle("active",window.scrollY > 0);
        })
    </script>

</body>
</html>