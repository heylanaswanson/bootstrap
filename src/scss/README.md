body {
    font-family: "Inter", sans-serif;
    font-optical-sizing: auto;
    font-weight: normal;
    font-size: 16px;
    font-style: normal;
    color: #6f6a65;
}

h1 {
    font-family: "Playfair Display", serif;
    font-optical-sizing: auto;
    font-weight: normal;
    font-style: normal;
    font-size: 36px;
}

h2 {
    font-family: "Playfair Display", serif;
    font-optical-sizing: auto;
    font-weight: normal;
    font-style: normal;
    font-size: 24px;
}

h2.statement {
    padding: 50px 0 0;
    text-align: center;

    & .statement.homepage {
        padding: 400px 0 30px;
    }
}

h3 {
    font-family: "Playfair Display", serif;
    font-optical-sizing: auto;
    font-weight: normal;
    font-style: normal;
    font-size: 20px;
}

.logo {
    width: 200px;
    position: relative;
    bottom: 40px;
    background-image: url('../assets/images/final-logo.png');
    z-index: 2;
}

.navbar-collapse {
    position: relative;
    /* bottom: 70px; */
    text-transform: uppercase;
    font-weight: 400;
    font-size: 20px;
    z-index: 2;
}

.navbar-nav .show > .nav-link,
.navbar-nav .nav-link.active {
    color: #d48c7a;
}

.navbar-toggler {
    position: relative;
    bottom: 76px;
}


.navbar-nav .show > .nav-link {
    padding-right: 30px;
    padding-left: 30px;
}

.navbar-collapse .navbar-nav {
    position: relative;
    bottom: 60px;
    /* background-color: white; */
}

.navbar-collapse .navbar-nav .nav-item {
    padding: 20px 10px 15px;
}

.hero-image {
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: absolute;
    top: 120px;
    width: 100%;
    z-index: 1;
}

.hero-image .container {
    padding: 0 50px;
    text-align: left;
    color: #3b2f2a;
}

.hero-image.home {
    background-image: url('../assets/images/banners/home.png');
}

.hero-text {
    color: #ffffff;
    font-size: 48px;
    font-weight: bold;
    text-shadow: 2px 2px 4px #000000;
}

.hero-image h1 {
    padding-bottom: 20px;
    margin-top: 80px;
}

.hero-image h2 {}

.hero-image button {
    padding: 10px 30px;
    margin: 40px 0;
    border-radius: 5px;
    font-size: 18px;
    border: none;
}

.card {
    padding: 50px;
    background-color: #f3eee6;
    border-radius: 15px;
    margin: 0px 10px;
}

.card h2 {
    margin: 30px 0 40px;
}

p.step {
    color: #9a9a96;
    letter-spacing: 3px;
}

.image-container {
    margin-top: 50px;
}