**<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocket Ranch Aussies</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; text-align: center; background-color: #5D6D7E; }
        header { background: #2B65EC; color: blue; padding: 15px; font-size: 24px; display: flex; align-items: center; justify-content: center; }
        header img { height: 80px; margin-right: 15px; }
        nav { background: #333; padding: 10px; }
        nav a { color: white; text-decoration: none; padding: 10px 15px; display: inline-block; }
        section { padding: 20px; max-width: 800px; margin: auto; }
        .puppies { display: flex; flex-wrap: wrap; justify-content: center; }
        .puppies img { width: 100%; max-width: 300px; margin: 10px; border-radius: 10px; }
        .contact-form { max-width: 400px; margin: auto; background: #f4f4f4; padding: 15px; border-radius: 5px; }
        input, textarea { width: 100%; padding: 8px; margin: 5px 0; border-radius: 5px; border: 1px solid #ccc; }
        button { background: #2B65EC; color: white; padding: 10px; border: none; cursor: pointer; border-radius: 5px; }
    </style>
</head>
<body>
    <header>
        <img src="rocket-ranch-logo.png" alt="Rocket Ranch Aussies Logo" style="height: 100px;">
        Rocket Ranch Aussies
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
</html>**
