# Photography-Website
Photography Website Project Overview: Developed a responsive photography website to showcase professional photography services. The website includes an intuitive user interface, a visually appealing layout, and a dynamic image gallery. Designed to provide a seamless experience across different devices, ensuring easy navigation and accessibility.
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Pixel Arts</title>
    <link rel="stylesheet" type="text/css" href="bwp2.css">
    <link rel="icon" type="image/x-icon" href="logo.gif">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>

    <div class="container">

        <div class="header">
            <div class="icon_area">
                <img src="logo.gif" alt="logo" class="logo">
                <span class="icon_name">Pixel Photography</span>
            </div>
            <div class="menu_area">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">About Us</a></li>
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
        </div>

        <div class="content">

            <div class="main_content">
                <h2 class="main_heading">Welcome to Pixel Photography</h2>
                <p>We are a team of professional photographers who are passionate about capturing the moments of your life. 
                    We provide a wide range of services including wedding photography, event photography, portrait photography, and many more. 
                    We are dedicated to providing you with the best quality photographs that you can cherish for a lifetime.</p>
            </div>

            <h1 class="Services_heading">Services</h1>

            <div class="services">
                <div class="service_card">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Photography" width="400" height="230">
                    <p>Photography</p>
                </div>
                <div class="service_card">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Photography" width="400" height="230">
                    <p>Photography</p>
                </div>
                <div class="service_card">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Photography" width="400" height="230">
                    <p>Photography</p>
                </div>
            </div>

            <div class="about_us">
                <img src="AVENGERS WALLPAPER.jpg" alt="About Us" width="400" height="230" class="side_img">
                <div class="side_text">
                    <h1>About Us</h1>
                    <p>Photography is more than just clicking pictures—it's about freezing emotions and 
                        telling stories through light and composition. At PIXEL ARTS, 
                        we specialize in capturing the beauty of life’s most precious moments. 
                        Our mission is to create timeless images that you will cherish for a lifetime. 
                        From professional portraits to candid shots, we ensure every frame is 
                        filled with authenticity and emotion.</p>
                </div>
            </div>

            <div class="gallery">
                <h2 class="Gallery_text">Gallery</h2>
                <div class="gallery_images">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                    <img src="AVENGERS WALLPAPER.jpg" alt="Gallery Image" width="200" height="150">
                </div>
            </div>

        </div> <!-- End of content -->

        <div class="footer">
            <div class="address">
                <p>Padmanabhanagar<br>
                RR Venkatapuram<br>
                Gopalapatnam<br>
                Visakhapatnam - 530029<br>
                Andhra Pradesh<br>
                India.</p>
            </div>
            <div class="contact">
                <p>Mobile: 7901233045</p>
                <p>Email: saathwik.dabbeeru@gmail.com</p>
                <p>Instagram: saathwik_290798</p>
            </div>
        </div>

    </div> <!-- End of container -->

</body>
</html>


CSS CODE:

@import url('https://fonts.googleapis.com/css2?family=Baskervville+SC&family=Bungee+Tint&display=swap');

body {
    margin: 0;
    font-family: "Baskervville SC", serif;
    color: white;
    background-color: lightblue;
}

/* Header Section */
.header {
    height: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #35ea9c5b;
    padding: 10px 20px;
}

ul {
    display: flex;
    list-style-type: none;
    gap: 10px;
    flex-wrap: wrap;
    padding: 0;
    margin: 0;
}

li {
    padding: 5px 10px;
    border-radius: 5px;
    transition: transform 0.5s, background-color 0.5s, border-bottom 0.5s;
    color: #8de649;
}

li:hover {
    transform: scale(1.1);
    background-color: #e3f16c;
    border-bottom: 2px solid #e0e0e0;
    cursor: pointer;
}

.icon_area {
    display: flex;
    align-items: center;
    gap: 10px;
}

.icon_name {
    font-size: 30px;
    color: #2e2bd5;
    font-weight: bold;
}

.menu_area {
    margin-right: 10px;
}

/* Main Content */
.main_content {
    background-image: url('AVENGERS WALLPAPER.jpg');
    height: 900px;
    background-repeat: no-repeat;
    background-size: cover;
    text-align: center;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    flex-wrap: wrap;
    color: #e0e0e0;
}

.main_heading {
    font-family: 'Bungee Tint', cursive;
    font-size: 40px;
}

/* Services Section */
.services {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    margin-top: 20px;
    justify-content: space-evenly;
    text-align: center;
}

.Services_heading {
    text-align: center;
    font-size: 2rem;
    color: #000000;
}

.service_card {
    max-width: 400px;
    text-align: center;
    border-radius: 5px;
    background: #143750;
    padding: 10px;
    margin-bottom: 20px;
    color: #e0e0e0;
}

/* About Us Section */
.about_us {
    padding-top: 40px;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    background-color: #0f3460;
    justify-content: space-evenly;
    margin-top: 20px;
    padding: 20px;
    color: #e0e0e0;
}

.side_img {
    max-width: 400px;
}

.side_text {
    max-width: 500px;
    text-align: justify;
}

/* Gallery Section */
.gallery {
    text-align: center;
    margin-top: 20px;
}

.Gallery_text {
    width: 100%;
    font-size: 2rem;
    color: #020101;
    margin-bottom: 20px;
}

.gallery_images img {
    max-width: 200px;
    cursor: pointer;
    transition: transform 0.5s;
    margin: 5px;
    border-radius: 10px;
}

.gallery_images img:hover 
{
    transform: scale(1.1);
    border: 2px solid #24fe03;
}

/* Footer */
.footer {
    text-align: center;
    background-color: #0a0909;
    color: #fcd568;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
}

/* Responsive Design */
@media only screen and (max-width: 700px) {
    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
    }

    .side_text {
        padding: 10px;
    }

    .service_card {
        margin-bottom: 20px;
    }

    .Gallery_text {
        margin-top: 10px;
    }

    .menu_area {
        display: none;
    }
}

