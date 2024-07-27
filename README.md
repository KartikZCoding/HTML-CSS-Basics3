# Create Simple Webpage using HTML & CSS

### Here's Wireframe of WebPage
![Second Web Development.png](https://github.com/KartikZCoding/HTML-CSS-Basics3/blob/6757925a6c281e7d8d5cdfe04b5959ae0bbba873/Website%20from%20Figma.png)

### HTML Code
```HTML
<!DOCTYPE html>
<html>

<head>
    <title>Ferdi Sahim</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=League+Spartan:wght@100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
</head>

<body>
    <!-- Hero Section -->
    <div id="hero-section">
        <!-- Hero Text -->
        <div id="hero-text">
            <!-- Email or Phonr -->
            <div class="smalltext">
                (+90) 551 052 43 56
                <div style="float: right;">
                    ferdisahin@mail.com
                </div>
            </div>

            <!-- Name -->
            <div id="hi-and-name">Hi, I’m Ferdi Sahin</div>

            <!-- Title -->
            <h1>Freelance Front-end Developer and <br> Wordpress Developer</h1>

            <!-- Subtitle -->
            <div class="bigtext">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus turpis ligula, pellentesque a elit in,
                convallislaoreet metus. Sed aliquet lacinia dictum. In pharetra nunc nisi, ac aliquet est pretium non.
            </div>

            <!-- Button -->
            <button id="contact-button">Contact Me</button>
        </div>
        <!-- Her600px;e -->
        <div id="hero-image-wrapper">
            <img id="hero-image" src="Images/Image.png" alt="Person Image">
        </div>
    </div>

    <!-- Pricing -->
    <div id="pricing-section">
        <div class="overtitle">PRICING</div>

        <h2 class="section-heading">You can take a look at the pricing table based on the work I do.</h2>

        <div class="bigtext section-subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus turpis ligula, pellentesque a elit in,
            convallis laoreet metus. Sed aliquet lacinia dictum. In pharetra nunc nisi, ac aliquet est pretium non.
        </div>

        <div id="pricing-boxes">
            <div class="pricing-card">
                <div class="service">PSD to HTML</div>
                <div class="price"><span>$99</span> / per page</div>
                <div class="service-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
                <div class="service-benefit">
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                </div>
                <button class="service-button">Contact Me</button>
            </div>
            <div class="pricing-card">
                <div class="service" style="color: black;">Scetch to HTML</div>
                <div class="price"><span>$99</span> / per page</div>
                <div class="service-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
                <div class="service-benefit">
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                </div>
                <button class="snd-prcie-btn service-button" style="color: white;">Contact Me</button>
            </div>
            <div class="pricing-card">
                <div class="service">Figma to HTML</div>
                <div class="price"><span>$99</span> / per page</div>
                <div class="service-description">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</div>
                <div class="service-benefit">
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                    <label>service benefits</label>
                </div>
                <button class="service-button">Contact Me</button>
            </div>
        </div>
    </div>

    <div class="footer">
        Ferdi Sahin © 2022. All Rights Reserved.
    </div>

</body>

</html>
```
### CSS Code
```CSS
html {}

body {
    margin: 0;
    padding: 0;
    background-color: #FFF8F0;
    color: #55206D;
    font-family: Inter;
    font-weight: 400;
    line-height: 24px;
    /* max-width: 1440px; */
}

h1 {
    color: #190D37;
    font-family: "League Spartan", sans-serif;
    font-size: 48px;
    font-weight: 700;
    line-height: 50px;
    margin-top: 10px;
    margin-bottom: 30px;
}

h2 {
    color: #000;
    font-family: "League Spartan", sans-serif;
    font-size: 36px;
    font-weight: 700;
    line-height: 40px;
}

.bigtext {
    color: #331E6A;
    font-family: "Poppins", sans-serif;
    font-size: 18px;
    font-weight: 400;
    line-height: 28px;
}

#hero-section {
    display: flex;
    max-width: 1440px;
    height: 600px;
    margin: 0 auto 48px auto;
}

#hero-text {
    width: 50%;
    padding: 32px 20px 32px 50px;
}

#hero-image-wrapper {
    width: 50%;
}

#hero-image {
    height: 100%;
}

.smalltext {
    color: #000;
    font-family: "Inter", sans-serif;
    font-size: 12px;
    font-weight: 400;
    line-height: normal;
}

#hi-and-name {
    margin-top: 52px;

}

#contact-button {
    width: 138px;
    height: 44px;
    border-radius: 4px;
    background: #2F2F2F;
    color: #FFF;
    font-family: "Inter", sans-serif;
    font-size: 16px;
    font-weight: 500;
    margin-top: 20px;
}

#pricing-section {
    max-width: 1060px;
    margin: 48px auto;
}

.overtitle {
    color: #2858FF;
    font-family: Poppins;
    font-size: 12px;
    font-weight: 600;
    line-height: 18px;
    text-align: center;
    margin-bottom: 8px;
}

.section-heading {
    text-align: center;
    max-width: 700px;
    margin: 0 auto;
}

.section-subtitle {
    text-align: center;
    margin: 8px auto 48px auto;
    max-width: 700px;
}

#pricing-boxes {
    display: flex;
}

.service {
    color: #2858FF;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
}

.pricing-card {
    background-color: #fff;
    margin: 0 10px;
    border-radius: 10px;
    width: 340px;
    height: 380px;
    box-shadow: 6px 2px 25px -9px rgba(0, 0, 0, 0.10);
    padding: 20px;
    color: #8A8A8A;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    transition: 0.3s;
}

.pricing-card:hover {
    transform: scale(1.02);
}

.price span {
    color: #000;
    font-family: Poppins;
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
}

.price {
    display: flex;
    align-items: center;
    margin: 8px 0;
}

.service-description {
    width: 250px;
    line-height: 23px;
}

.service-benefit {
    display: flex;
    flex-direction: column;
    margin: 16px 0;
    gap: 14px;
}

#pricing-boxes .pricing-card:nth-child(even) {
    background-color: #FFD748;
    color: black 75% !important;
}

.snd-prcie-btn {
    background-color: black;
    color: white;
}

.service-button {
    width: 300px;
    height: 44px;
    border-radius: 4px;
    border: 2px solid #2F2F2F;
    color: #2F2F2F;
    font-family: Inter;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
}

.footer {
    width: 1222px;
    margin: 0 auto;
    text-align: center;
    padding: 20px;
    background-color: #000;
    color: #FFF;
    font-family: Poppins;
    font-size: 12px;
    font-weight: 500;
}
```
### Here's all Images
<a href="">
    <img src="https://github.com/KartikZCoding/Other-Files/blob/29c62f9aa8abe0470d9e2d75c809940a786cf035/image-logo.png" alt="Image Icon" height="90px">
</a>
