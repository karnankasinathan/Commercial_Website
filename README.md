# Ex02 Commercial Website


## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Glow Beauty Salon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="logo">Glow Beauty Salon</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
            <a href="#book" class="btn">Book Now</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Enhance Your Natural Beauty</h1>
        <p>Professional makeup, skincare & hair styling services</p>
        <button>Explore Services</button>
    </section>

    <!-- Services -->
    <section id="services" class="services">
        <h2>Our Services</h2>

        <div class="service-box">
            <h3>Hair Styling</h3>
            <p>Trendy haircuts, coloring & spa treatments</p>
            <span>Starting ₹999</span>
        </div>

        <div class="service-box">
            <h3>Bridal Makeup</h3>
            <p>Professional bridal & party makeup</p>
            <span>Starting ₹4,999</span>
        </div>

        <div class="service-box">
            <h3>Facial & Skincare</h3>
            <p>Glow facials & advanced skincare treatments</p>
            <span>Starting ₹1,499</span>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>
            Glow Beauty Salon provides premium beauty services with certified professionals.
            We focus on quality, hygiene and customer satisfaction.
        </p>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>📍 Salem, Tamil Nadu</p>
        <p>📞 +91 98765 43210</p>
        <p>📧 glowbeauty@gmail.com</p>
    </section>

    <!-- Booking -->
    <section id="book" class="booking">
        <h2>Book Appointment</h2>
        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="tel" placeholder="Phone Number" required>
            <select required>
                <option value="">Select Service</option>
                <option>Hair Styling</option>
                <option>Bridal Makeup</option>
                <option>Facial & Skincare</option>
            </select>
            <input type="date" required>
            <button type="submit">Book Now</button>
        </form>
    </section>

    <footer>
        <p>© 2026 Glow Beauty Salon | All Rights Reserved</p>
    </footer>

</body>
</html>
```

Style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #fff5f8;
    color: #333;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #ff4d88;
    padding: 15px 50px;
    color: white;
}

header nav a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
    font-weight: bold;
}

header .btn {
    background: white;
    color: #ff4d88;
    padding: 5px 10px;
    border-radius: 5px;
}

/* Hero */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9') no-repeat center center/cover;
    color: white;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.hero button {
    padding: 10px 20px;
    background: #ff4d88;
    border: none;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}

/* Services */
.services {
    text-align: center;
    padding: 50px 20px;
}

.service-box {
    background: white;
    margin: 20px auto;
    padding: 20px;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 5px 10px rgba(0,0,0,0.1);
}

/* About */
.about {
    background: #ffe6ef;
    padding: 50px 20px;
    text-align: center;
}

/* Contact */
.contact {
    padding: 50px 20px;
    text-align: center;
}

/* Booking */
.booking {
    background: white;
    padding: 50px 20px;
    text-align: center;
}

.booking form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: auto;
}

.booking input,
.booking select {
    margin: 10px 0;
    padding: 10px;
}

.booking button {
    padding: 10px;
    background: #ff4d88;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

/* Footer */
footer {
    background: #ff4d88;
    color: white;
    text-align: center;
    padding: 10px;
}
```


## OUTPUT

<img width="1876" height="1067" alt="image" src="https://github.com/user-attachments/assets/639e352e-de2d-4853-9ac8-850e2ad1a5f6" />

<img width="1600" height="875" alt="image" src="https://github.com/user-attachments/assets/b3e11bf1-3d2f-4cc1-bf41-a07dd616ae6f" />






## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
