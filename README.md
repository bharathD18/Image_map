# Ex04 Places Around Me
# Date:28.04.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
image map.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAP</title>
</head>
<body>
    <img  src="/static/map.png" width="1520" height="750" usemap="#mymap">
    <map name="mymap">
        <area shape="rect" coords="888,108,1147,231" title="Stickers Shop" href="imap1.html">
        <area shape="rect" coords="1362,139,1612,209" title="Parcel service" href="imap2.html">
        <area shape="rect" coords="176,700,406,785" title="Finance" href="imap3.html">
        <area shape="rect" coords="102,369,366,478" title="Electronic shop" href=imap4.html>
        <area shape="rect" coords="1256,403,1466,482" title="Parlor" href="imap5.html">
    </map>
</body>
</html>


imap1.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sri Ram Stickers</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color:violet;
      color: #333;
    }
    header {
      background-color:palevioletred;
      color: white;
      padding: 10px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    main {
      padding: 20px;
      text-align: center;
    }
    .image-container img {
      max-width: 100%;
      height: 500;
      width: 1000;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    .description {
      margin-top: 20px;
      font-size: 1.2rem;
      line-height: 1.6;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
      margin-top: 20px;
    }
    footer a {
      color: #ff6f61;
      text-decoration: none;
    }
    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>SRI RAM STRICKERS</h1>
    <p>Your one-stop shop for amazing stickers!</p>
  </header>
  <main>
    <div class="image-container">
      <img src="/static/stickers shop.jpg" height="500" width="800" alt="A collection of vibrant stickers">
    </div>
    <div class="description">
      <p>
        Welcome to Sri Ram Stickers! We offer a wide variety of stickers to suit every taste. Whether you’re looking for cute, trendy, or custom designs, we’ve got you covered. Our stickers are made with high-quality, durable materials to ensure they last wherever you stick them – on laptops, water bottles, notebooks, or anywhere else.
      </p>
      <p>
        Explore our collection today and find the perfect stickers to express your personality and style!
      </p>
    </div>
  </main>
  <footer>
    <p>Have questions or want to place a bulk order? Contact us!</p>
    <p>Email: <a href="mailto:contact@sriramsticker.com">contact@sriramsticker.com</a></p>
    <p>Phone: 9632587410</p>
    <p>Follow us on social media for updates and exclusive offers!</p>
  </footer>
</body>
</html>


imap2.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KPN Speed Parcel Service Center</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: beige;
        }
        header {
            background-color: burlywood;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .description {
            margin: 20px 0;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact {
            background-color:wheat;
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .contact h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to KPN Speed Parcel Service</h1>
</header>

<div class="container">
    <img src="/static/parcel service.jpg" alt="KPN Speed Parcel Service Center Image">
    <div class="description">
        <h2>About Us</h2>
        <p>
            At KPN Speed Parcel Service, we provide fast, reliable, and secure delivery solutions for both businesses and individuals. 
            With years of experience in the logistics industry, we ensure your parcels reach their destination on time and in perfect condition. 
            Whether you need local, national, or international shipping, we have tailored solutions to meet your needs. 
            Choose Swift Parcel Service for unparalleled convenience and exceptional customer service.
        </p>
    </div>
    
    <div class="contact">
        <h3>Contact Us</h3>
        <p><strong>Address:</strong> Durugam road,Kallakurichi</p>
        <p><strong>Phone:</strong> 9874563210</p>
        <p><strong>Email:</strong> support@kpnparcel.com</p>
        <p><strong>Working Hours:</strong> Mon-Fri: 8:00 AM - 6:00 PM, Sat: 9:00 AM - 3:00 PM</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 KPN Speed Parcel Service. All rights reserved.</p>
</footer>

</body>
</html>


imap3.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HDB Financial Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: skyblue;
        }
        header {
            background-color: #2b6cb0;
            color: #fff;
            padding: 20px 10px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .image-container {
            text-align: center;
            margin-bottom: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .description {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .contact-section {
            background-color: #e2e8f0;
            padding: 20px;
            border-radius: 10px;
        }
        .contact-section h2 {
            margin-top: 0;
        }
        .contact-section p {
            margin: 5px 0;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #2b6cb0;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to HDB Financial Services</h1>
</header>

<div class="container">
    <div class="image-container">
        <img src="/static/HDB FINANCIAL SERVICES .jpg" alt="Financial Services">
    </div>

    <div class="description">
        <p>At HDB Financial Services, we specialize in providing personalized financial solutions to help you achieve your goals. Our services include investment planning, retirement strategies, tax optimization, and much more. With our team of experienced professionals, we ensure that your financial future is secure and prosperous.</p>
        <p>We are committed to delivering transparent, reliable, and comprehensive financial advice tailored to your unique needs.</p>
    </div>

    <div class="contact-section">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong>Durugam road,Kallakurichi</p>
        <p><strong>Phone:</strong>9654871202</p>
        <p><strong>Email:</strong> info@hdbfinancialservices.com</p>
        <p><strong>Office Hours:</strong> Monday to Friday, 9:00 AM - 5:00 PM</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 HDB Financial Services. All rights reserved.</p>
</footer>

</body>
</html>


imap4.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electronics Shop</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color:darkgrey;
            color: #333;
        }

        header {
            background-color: #333;
            color:darkgray;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .header-logo .logo {
            width: 150px;
        }

        header nav ul {
            list-style: none;
            display: flex;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            text-decoration: none;
            color:white;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #ff6347;
        }

        
        main {
            padding: 20px;
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            margin-top: 20px;
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .description {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .contact {
            background-color:darkgrey;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .contact ul {
            list-style: none;
            padding: 0;
        }

        .contact ul li {
            font-size: 18px;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Darling Electronics and mobile shop</h1>
        <p>Your one-stop destination for all the latest gadgets and electronics.</p>
    </header>
    <main>
        <div class="image-container">
          <img src="/static/electronics shop.jpg" height="500" width="700">
        </div>
        <div class="description">
          <p>
            Welcome to our extraordinary Electronics and Mobile Shop, where cutting-edge technology meets unrivaled innovation. Step into a world of sleek, powerful gadgets that promise to elevate your digital lifestyle to new heights. From the latest smartphones that capture breathtaking moments to high-performance laptops that make work and play a seamless experience, we offer an array of products designed to impress. Immerse yourself in the brilliance of crystal-clear displays, lightning-fast processors, and stunning designs, all crafted to perfection. Whether you're a tech enthusiast or a casual user, our shop is your gateway to the future of technology. Experience a shopping journey like no other, where each product is more than just a device—it's an invitation to explore, connect, and be inspired.
          </p>
        </div>
      </main>
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to get in touch with us:</p>
        <ul>
            <li><strong>Phone:</strong>9512365870</li>
            <li><strong>Email:</strong> support@electronics-shop.com</li>
            <li><strong>Address:</strong>Durugam rd,Kallakurichi</li>
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Darling Electronics Shop. All rights reserved.</p>
    </footer>
</body>
</html>


imap5.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hair cut & Salon</title>
    <style>
       * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color:bisque;
            color: #333;
        }

        /* Header Section */
        header {
            background-color:crimson;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 20px;
        }

        main {
            padding: 20px;
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            margin-top: 20px;
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .contact {
            background-color:darksalmon;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .contact h2 {
            font-size: 28px;
            color: #e63946;
            margin-bottom: 20px;
        }

        .contact ul {
            list-style: none;
            padding: 0;
            font-size: 18px;
        }

        .contact ul li {
            margin-bottom: 10px;
        }

        /* Footer Section */
        footer {
            background-color:crimson;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }

        footer p {
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>GREEN TRENDS</h1>
        <p>Your ultimate destination for relaxation, beauty, and self-care.</p>
    </header>
    <main>
        <div class="image-container">
          <img src="/static/green trends.jpeg" alt="A collection of vibrant stickers">
        </div>
        <div class="description">
          <p>
            Step into our enchanting Haircut and Beauty Parlor, where elegance meets transformation. Each visit is an indulgent escape into a world of luxury, where skilled hands craft your dream look with precision and care. Our expert stylists weave magic with every snip, sculpting your hair into stunning works of art that effortlessly reflect your personality and style. From rejuvenating facials to indulgent hair treatments, we offer a sanctuary where beauty is celebrated and self-care is paramount. Let us envelop you in a calming atmosphere, leaving you feeling refreshed, radiant, and more confident than ever. Every moment spent with us is not just a treatment; it’s an experience designed to enhance your natural beauty and elevate your spirit.
          </p>
        </div>
      </main>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>We would love to hear from you! For appointments or inquiries, reach out to us through the following:</p>
        <ul>
            <li><strong>Phone:</strong>9874563210</li>
            <li><strong>Email:</strong> greentrends@example.com</li>
            <li><strong>Address:</strong>Durugam rd,Kallakurichi</li>
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Green Trends. All rights reserved.</p>
    </footer>
</body>
</html>

```
# OUTPUT

![Screenshot 2024-12-27 212518](https://github.com/user-attachments/assets/e304b46f-2060-4c4b-bd1a-d628aa0ee248)

![Screenshot 2024-12-27 212555](https://github.com/user-attachments/assets/87e97fb7-001f-4f81-b361-7d9c2886b841)

![Screenshot 2024-12-27 212637](https://github.com/user-attachments/assets/73b2d7a5-194f-4054-bab1-0d2bd71c3163)

![Screenshot 2024-12-27 212712](https://github.com/user-attachments/assets/e09b6a3e-7fef-4664-8972-50faec55f45b)

![Screenshot 2024-12-27 213107](https://github.com/user-attachments/assets/15996be2-8707-4165-a136-1ae02ca5b76b)

![Screenshot 2024-12-27 213233](https://github.com/user-attachments/assets/8fb7f64b-d5a6-4db3-8ae7-f27082ed02fd)

![Screenshot 2024-12-27 214257](https://github.com/user-attachments/assets/d0fac9ac-8191-4fb1-ab1c-ed9a3f0cb376)

![Screenshot 2024-12-27 214344](https://github.com/user-attachments/assets/8315c3b1-7fa2-4104-afc9-777f204a9e8b)

![Screenshot 2024-12-27 214412](https://github.com/user-attachments/assets/35297f3c-da1c-4aea-88db-f1a90e380213)

![Screenshot 2024-12-27 214448](https://github.com/user-attachments/assets/2a5dc648-d784-41df-b9cb-b99eec3568b8)


# RESULT
The program for implementing image maps using HTML is executed successfully.
