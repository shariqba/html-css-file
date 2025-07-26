# html-css-file
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <style>
        body{
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #ffffff;
    color: #003300;
}

header{
    background-color: rgb(255, 0, 0);
    color: white;
    padding: 10px 20px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}


.hero{
    display: flex;
    justify-content: space-between;
    padding: 40px 20px;
    align-items: center;
}

.hero-text h2{
    font-size: 28px;
}

.hero-text span{
    background-color: rgb(159, 156, 167);
    padding: 2px 6px;
}

.hero-img img{
    width: 200px;
    border-radius: 20px;
}

button{
    background-color: #ff5500;
    color: white;
    border: none;
    padding: 10px 16px;
    margin-top: 10px;
    border-radius: 30px;
    cursor: pointer;
}

.about{
    text-align: center;
    padding: 40px 20px;
    background-color: #ccffcc;
}

    
.portfolio{
    padding: 40px 20px;
    background-color: #e6ffe6;
    text-align: center;
}

.portfolio-card{
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card{
    background-color: rgb(247, 248, 255);
    border: 1px solid #999;
    padding: 20px;
    border-radius: 10px;
    width: 280px;
}

.card img{
    width: 100%;
    border-radius: 6px;
}


    </style>
</head>
<body> 
    <header>
        <nav>
             <h1>M.SHARIQ</h1>
             <ul>
                <li><a href="#">home</a></li>
                <li><a href="#">about</a></li>
                <li><a href="#">portfolio</a></li>
                <li><a href="#">service</a></li>
                <li><a href="#">contact</a></li>
             </ul>
        </nav>
    </header>
    <section class="hero">
        <div clas="hero-text">
            <h2>Hey I am Shariq </br>learning full stack developer <b>SMIT</b></h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium eius quos quia reiciendis, iste consectetur placeat deserunt dolorem incidunt, accusamus cupiditate doloremque quae animi maxime quam voluptas repudiandae voluptatem minus. </p>
        </div>
        <div class="hero-img">
            <img src="Screenshot 2025-07-14 183950.jpg" alt="">
        </div>
    </section>

        <section class="about">
        <h2>About me!</h2>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatem, cumque in magni animi earum saepe quae, molestiae consequatur dicta corrupti illo commodi quia, quibusdam at. Repellendus nemo recusandae autem. Nihil.</p>
        <button>Learn more</button>
    </section>

    <section class="portfolio">
        <h2>portfolio</h2>
        <div class="portfolio-cards">
            <div class="card">
                <img src="pexels-pixabay-270632.jpg" alt="">
                <h3>Personal portfolio</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Totam ipsum ratione soluta dignissimos sequi culpa, veniam consequuntur. Amet eligendi accusantium sapiente! Sint delectus eveniet consectetur aspernatur voluptates cupiditate ducimus voluptatibus?</p>
                <button>Preview</button>
                <button>View Sources</button>
            </div>

             <div class="card">
                <img src="pexels-pixabay-270632.jpg" alt="">
                <h3>Personal portfolio</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Totam ipsum ratione soluta dignissimos sequi culpa, veniam consequuntur. Amet eligendi accusantium sapiente! Sint delectus eveniet consectetur aspernatur voluptates cupiditate ducimus voluptatibus?</p>
                <button>Preview</button>
                <button>View Sources</button>
            </div>

             <div class="card">
                <img src="pexels-pixabay-270632.jpg" alt="">
                <h3>Personal portfolio</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Totam ipsum ratione soluta dignissimos sequi culpa, veniam consequuntur. Amet eligendi accusantium sapiente! Sint delectus eveniet consectetur aspernatur voluptates cupiditate ducimus voluptatibus?</p>
                <button>Preview</button>
                <button>View Sources</button>
            </div>
        </div>
    </section>
</body>
</html>
