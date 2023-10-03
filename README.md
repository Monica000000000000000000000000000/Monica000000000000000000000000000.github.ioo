<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>African Leadership Academy</title>

<link rel="stylesheet"
href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Paytone+One&
family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,
800;0,900;1,100;1,200;1,300;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

<style>
    *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
    text-decoration: none;
    list-style: none;
    scroll-behavior: smooth;
}

:root{
    --bg-color: #fff;
    --text-color: #221314;
    --second-color: #5a7184;
    --main--color: #6e54fa;
    --big-font: 6rem;
    --h2-font: 3rem;
    --p-font: 1.1rem
}
body{
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.5)),url(https://preview.redd.it/4k-wallpaper-steampunk-pirate-ship-v0-8nq76z9pm0sa1.jpg?width=3840&format=pjpg&auto=webp&s=176b4467e66e11c0ec07bc8d6e00c24c43b1447d);
    background: var(--bg-color);
    color: var(--text-color);
    font-size: 14px; 
}
header{
    position: fixed;
    top: 0;
    right: 0;
    width: 100%;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: transparent;
    padding: 30px 18%;
    transition: ease .40s;
}
.logo{
    font-size: 35px;
    font-weight: 600;
    letter-spacing: 1px;
    color: var(--bg-color);
}
.navbar{
    display: flex;    
}
.navbar a{
    color: var(--bg-color);
    font-size: var(--p-font);
    font-weight: 500;
    padding: 10px 22px;
    border-radius: 4px;
    transition: ease .40s;
}
.navbar a:hover{
    background: var(--bg-color);
    color: var(--text-color);
    box-shadow: 5px 10px 30px rgb(85 85 85 / 20%);
    border-radius: 4px;
}
#menu-icon{
    color: var(--bg-color);
    font-size: 35px;
    z-index: 10001;
    cursor: pointer;
    display: none;
}
section{
    padding: 80px 18%;
}
.home{
    position: relative;
    width: auto;
    height: auto;
    background: linear-gradient(to bottom, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.4)), url(https://preview.redd.it/4k-wallpaper-steampunk-pirate-ship-v0-8nq76z9pm0sa1.jpg?width=3840&format=pjpg&auto=webp&s=176b4467e66e11c0ec07bc8d6e00c24c43b1447d);
    background-size: cover;
    background-position: center;
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    align-items: center;
}
.home-text h1{
    font-size: 70px;
    line-height: 1.2;
    color: var(--bg-color);
    font-family: 'Paytone One', sans-serif;
    letter-spacing: 4px;
    margin: 20px;
}
.home-text p{
    color: #ffffffbf;
    font-size: 20px;
    font-weight: 400;
    line-height: 38px;
    margin-bottom: 50px;
}
.home-btn{
    display: inline-block;
    font-size: 16px;
    padding: 15px 30px;
    background: #ffffffbf;
    color: var(--main--color);
    border-radius: 4px;
    transition: ease .40s;
}
.home-btn:hover{
    background: var(--bg-color);
    transform: scale(1.1);
}
header.sticky{
    background: var(--bg-color);
    padding: 10px 18%;
    box-shadow: rgba(33,35,38, 0.1) 0px 10px 10px -10px;
}
.sticky .logo{
    color: var(--text-color);
}
.sticky .navbar a{
    color: var(--text-color);
}
.text h2{
    font-size: var(--h2-font);
    line-height: 1.1;
}
.row-items {
    display: flex;
    flex-wrap: nowrap;
    overflow-x: hidden; 
}

.container-box {
    margin-right: 30px;
    margin-left: 30px;
    background:#fafafa;
    padding: 15px 15px;
    box-shadow: #000000;
    border-radius: 31px;
    transition: all .4s ease 0s;
    transition:#0000;
    cursor: pointer;
}
.container-img img{
    height: 122px;
    width: 129px;
    padding: 15px;
    background: var(--bg-color);
    margin-bottom: 15px;
    border-radius: 20px;
    cursor: pointer;
}
.container-box h4{
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 8px;
}
.container-box p{
    font-size: 15px;
    color: var(--second-color);
}
.container-box:hover{
    box-shadow: 5px 30px 56.1276px rgb(55 55 55 / 12%);
    border: 1px solid transparent(-3px);

}
.Dubai{
    display: flex; 
    flex-wrap: nowrap;
    overflow-x: hidden; 
    height: 200px;
    width: 250px; 
    border-radius: 15px;
    cursor: pointer;
}
.title{
    text-align: center;
}
.title h2{
    font-size: var(--h2-font);
    line-height: 1.2;
}
.package-content {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

.package-content .box {
    flex: 1;
    margin: 10px;
    text-align: center;
    background: var(--bg-color);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.308);
}

.package-content .box .thum {
    position: relative;
}

.package-content .box .thum img {
    max-width: 100%;
    border-radius: 8px;
}
.thum{
    position: relative;
    transition: all .3s cubic-bezier(.445, .05, .55, .95);
    will-change: filter;
    cursor: pointer;
}
.thum img{
    height: 200px;
    width: 250px;
}
.thum h3{
    position: absolute;
    font-size: 30px;
    font-weight: 600;
    text-align: right;
    color: var(--bg-color);
    top: 36px;
    right: 40px;
}
hr {
    border-color: rgb(255, 255, 255);
    display: none;
}

.dest-content{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    padding: 24px;
}
.location h4{
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 8px;
}
.location p{
    font-size: 15px;
    color: var(--second-color);
}
.thum:hover{
    filter: brightness(100%) hue-rotate(45deg);
    transform: scale(1.04);
}
.package h4 {
    font-size: 18px;
  }

</style>

</head>
<body>
    <!---header-->
    <header>
        <a href="#" class="logo">Travel</a>
        <div class="bx bx-menu" id="menu-icon"></div>
        <ul class="navbar">
            <li><a href="file:///f%3A/Documents/Programs/wepsites/ship/first.html">Home</a></li>
            <li><a href="https://monica000000000000000000000000000.github.io/" target="_blank">Esseys</a></li>
            <li><a href="https://alacademy.app.box.com/s/vu2lcahmad87rd566ykjorvkq66e6alh" target="_blank">Guide</a></li>

        </ul>
    </header>
    <!--Home section-->
    <section class="home" id="Home">
        <div class="home-text">
            <h1>African<br> Leadership <br>Academy</h1>
            <p> seeks to transform Africa by developing a powerful network of young leaders who will work together to address Africa's greatest challenges, achieve extraordinary social impact, and accelerate the continent's growth trajectory.</p>
            <a href="https://www.africanleadershipacademy.org/apply/" class="home-btn" target="_blank">Let's go now</a>
        </div>

    </section>
            <hr>
            <br>
<!--package section-->
<section class="package" id="package">
    <div class="title">
        <h2>Let's Get <br> The Information</h2>
    </div>
    <div class="package-content">
        <!-- London -->
        <div class="box">
            <div class="thum">
                <img src="https://files.oyaop.com/uploads/2016/12/African-Leadership-Academy-ALA-Fellowships-1.png"  target="_blank class="Dubai">

            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Johannesburg is ALA's home</h4>
                </div>
            </div>
        </div>

        <!-- Dubai -->
        <div class="box">
            <div class="thum">
                <img src="https://www.africanleadershipacademy.org/wp-content/uploads/2016/11/Creating-Great-Infrastructure-1.jpeg" class="Dubai">
            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Established in the year 2004</h4>
                </div>
            </div>
        </div>

        <!-- Paris -->
        <div class="box">
            <div class="thum">
                <img src="https://pbs.twimg.com/media/DeCuebXW0AAKUY1?format=png&name=900x900" class="Dubai">
            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Located in South Africa</h4>
                </div>
            </div>
        </div>
    </div>
</section>

            <hr>

<!--package section-->
<section class="package" id="package">
    <div class="title">
        <h2>Let's Get <br> More Information</h2>
    </div>
    <div class="package-content">
        <!-- London -->
        <div class="box">
            <div class="thum">
                <img src="https://www.govamedia.com/wp-content/uploads/2017/05/AfricanLeadershipAcademy.jpeg" class="Dubai">

            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Offers a two year program</h4>
                </div>

            </div>
        </div>

        <!-- Dubai -->
        <div class="box">
            <div class="thum">
                <img src="https://scontent.fcai19-2.fna.fbcdn.net/v/t39.30808-6/377444711_684913730337527_5249837573110252849_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=5614bc&_nc_ohc=OXymaTqsfPcAX8VoVQX&_nc_ht=scontent.fcai19-2.fna&oh=00_AfC1BAwT17JFaXDxXAzYf5veb797JyIw0MJkEL0z_fmFrA&oe=65189D1D" class="Dubai">

            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Diverse student body</h4>
                </div>

            </div>
        </div>

        <!-- Paris -->
        <div class="box">
            <div class="thum">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmSzY6phjcugBat3-glhWeMcnFpAUSL7zgHuXQvjmHRhjE7YBPrbW5o64J09m5NDVpdF4&usqp=CAU" class="Dubai">

            </div>
            <div class="dest-content">
                <div class="location">
                    <h4>Strong emphasis on ethics</h4>
                </div>
            </div>
        </div>
    </div>

    <script>
        function loadPage(pageUrl) {
            fetch(pageUrl)
                .then(response => response.text())
                .then(content => {
                    document.getElementById('content').innerHTML = content;
                })
                .catch(error => console.error(error));
        }
    </script>

</body>
</html>
