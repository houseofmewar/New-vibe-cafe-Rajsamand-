<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Trifold Hospitality</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: 'Poppins', sans-serif;
    background:#fff0f5;
    color:#333;
}

/* HERO SECTION */

.hero{
    height:100vh;
    background:linear-gradient(rgba(255,192,203,0.6), rgba(255,182,193,0.6)),
    url('https://images.unsplash.com/photo-1511795409834-ef04bbd61622') center/cover no-repeat;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero-content h1{
    font-family:'Playfair Display', serif;
    font-size:60px;
    letter-spacing:2px;
}

.hero-content p{
    margin:20px 0;
    font-size:18px;
}

.hero-content a{
    display:inline-block;
    padding:12px 30px;
    background:#d4af37;
    color:white;
    text-decoration:none;
    border-radius:30px;
    margin-top:15px;
    transition:0.3s;
}

.hero-content a:hover{
    background:#b8962e;
}

/* SERVICES */

.services{
    padding:80px 20px;
    text-align:center;
}

.services h2{
    font-family:'Playfair Display', serif;
    font-size:40px;
    color:#b03060;
    margin-bottom:50px;
}

.service-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
    max-width:1200px;
    margin:auto;
}

.service-box{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    transition:0.4s;
}

.service-box:hover{
    transform:translateY(-10px);
}

.service-box i{
    font-size:40px;
    color:#d4af37;
    margin-bottom:20px;
}

.service-box h3{
    color:#b03060;
    margin-bottom:15px;
}

.service-box p{
    font-size:14px;
    line-height:1.6;
}

/* WHATSAPP BUTTON */

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    font-size:24px;
    padding:15px;
    border-radius:50%;
    text-align:center;
    box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

</style>
</head>

<body>

<!-- HERO SECTION -->

<section class="hero">
    <div class="hero-content">
        <h1>Trifold Hospitality</h1>
        <p>Where Elegance Meets Impeccable Planning</p>
        <a href="https://wa.me/917023165896">Book Consultation</a>
    </div>
</section>

<!-- SERVICES SECTION -->

<section class="services">
    <h2>Our Core Services</h2>

    <div class="service-container">

        <div class="service-box">
            <i class="fas fa-clipboard-list"></i>
            <h3>RSVP Management</h3>
            <p>Complete guest tracking and confirmation management.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-calendar-check"></i>
            <h3>Event Planning</h3>
            <p>Luxury wedding and corporate event planning.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-concierge-bell"></i>
            <h3>Hospitality Desk</h3>
            <p>Professional help desk and guest assistance setup.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-truck"></i>
            <h3>Logistics Management</h3>
            <p>Transport and accommodation coordination.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-users-cog"></i>
            <h3>On-Ground Coordination</h3>
            <p>Seamless execution and vendor management.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-microphone-alt"></i>
            <h3>Production</h3>
            <p>Sound, lighting and stage setup management.</p>
        </div>

        <div class="service-box">
            <i class="fas fa-handshake"></i>
            <h3>CSM</h3>
            <p>Dedicated client service and coordination.</p>
        </div>

    </div>
</section>

<!-- WHATSAPP FLOATING BUTTON -->

<a href="https://wa.me/917023165896" class="whatsapp">
    <i class="fab fa-whatsapp"></i>
</a>

</body>
</html>
