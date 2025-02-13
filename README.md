<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocket Ranch Aussies</title>
    <style>
        html {
            scroll-behavior: smooth;
        }
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
        nav { 
            background: #8B5E3C;
            padding: 15px;
            position: sticky;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
        }
        nav a { 
            color: #F4EDE4;
            text-decoration: none;
            padding: 12px 20px;
            font-size: 18px;
            display: inline-block;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #A67C52;
            border-radius: 5px;
        }
        #home {
            background: url('background.jpg') center/cover no-repeat;
            color: white;
            padding: 80px 20px;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
        }
        .puppies {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .puppies img {
            width: 100%;
            border-radius: 15px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .puppies img:hover {
            transform: scale(1.05);
            box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.3);
        }
        .contact-form {
            max-width: 500px;
            background: #F4EDE4;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0,0,0,0.2);
        }
        input, textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 8px;
            border: 1px solid #8B5E3C;
            font-size: 16px;
        }
        button {
            background: #8B5E3C;
            color: white;
            font-size: 18px;
            padding: 12px;
            border-radius: 8px;
            cursor: pointer;
        }
        button:hover {
            background: #A67C52;
        }
    </style>
</head>
<body>
    <header>
        <img src="RR-Logo.jpg" alt="Rocket Ranch Aussies Logo" style="height: 120px;">
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#puppies">Available Puppies</a>
        <a href="#about">About Us</a>
        
    <a href="#parents">Parents</a>
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
    
    
    <section id="parents">
        <h2>Meet the Parents</h2>
        <div class="puppies">
            <img src="parent1.jpg" alt="Parent 1 - Mini Aussie">
            <img src="parent2.jpg" alt="Parent 2 - Mini Aussie">
        </div>
        <p>Our wonderful parent dogs are loving, intelligent, and excellent examples of the Mini Aussie breed. They help ensure that our puppies inherit great temperaments and health.</p>
    </section>
</body>
</html>
