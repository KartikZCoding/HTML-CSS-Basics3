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

```
### Here's all Images
<a href="">
    <img src="https://github.com/KartikZCoding/Other-Files/blob/29c62f9aa8abe0470d9e2d75c809940a786cf035/image-logo.png" alt="Image Icon" height="90px">
</a>
