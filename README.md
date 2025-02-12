
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocket Ranch Aussies</title>
    <style>
        body { 
            font-family: 'Playfair Display', serif; 
            margin: 0; 
            padding: 0; 
            text-align: center; 
            background-color: #D2B48C; /* Warm rustic tan */
            color: #3D2B1F; /* Soft beige for better readability */
        }
        header { 
            background: #8B5E3C; /* Dark rustic green */
            color: white; 
            padding: 20px; 
            font-size: 28px; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
        }
        header img { height: 120px; margin-right: 15px; }
        nav { background: #A67C52; padding: 15px; }
        nav a { color: #F4EDE4; text-decoration: none; padding: 12px 20px; display: inline-block; font-size: 18px; }
        section { padding: 30px; max-width: 900px; margin: auto; }
        .puppies { display: flex; flex-wrap: wrap; justify-content: center; }
        .puppies img { width: 100%; max-width: 320px; margin: 15px; border-radius: 15px; box-shadow: 3px 3px 10px rgba(0,0,0,0.2); }
        .contact-form { max-width: 450px; margin: auto; background: #4F6054; padding: 20px; border-radius: 10px; }
        input, textarea { width: 100%; padding: 10px; margin: 8px 0; border-radius: 8px; border: none; background: #F4EDE4; color: #2D3E34; }
        button { background: #A67C52; color: white; padding: 12px; border: none; cursor: pointer; border-radius: 8px; font-size: 18px; }
    </style>
</head>
<body>
    <header><img src="RR-Logo.jpg" alt="Rocket Ranch Aussies Logo" style="height: 120px;">

    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#puppies">Available Puppies</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="home">
        <h1>Welcome to Rocket Ranch Aussies!</h1>
        <p>We are a family-run breeder located in Atlanta, TX, specializing in happy, well-socialized Miniature Australian Shepherds. Our puppies are raised with love and care to ensure they make the perfect companions.</p>
    </section>
    
    <section id="puppies">
        <h2>Available Puppies</h2>
        <div class="puppies">
            <img src="puppy1.jpg" alt="Blue Merle Mini Aussie">
            <img src="puppy2.jpg" alt="Red Tri Mini Aussie">
            <img src="puppy3.jpg" alt="Black Tri Mini Aussie">
            <img src="puppy4.jpg" alt="Blue Merle Mini Aussie">
            <p>Our current litter is looking for their forever homes! Contact us for more details on available puppies and upcoming litters.</p>
        </div>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>At Rocket Ranch Aussies, we absolutely love the Mini Aussie breed and are passionate about raising well-rounded puppies. We focus on early potty training, crate training, and socialization to help prepare each puppy for their forever home. Our goal is to provide loving companions who are ready to integrate smoothly into their new families.</p>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-form">
            <form action="https://formspree.io/f/YOUR_UNIQUE_CODE" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
</body>
</html>
**
