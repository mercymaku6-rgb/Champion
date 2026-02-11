<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AutoParts Hub</title>
<style>
/* Reset & basics */
* {margin:0;padding:0;box-sizing:border-box;font-family:sans-serif;}
body {line-height:1.6;background:#f4f4f4;color:#333;}
a {text-decoration:none;color:#333;}
header {background:#222;color:#fff;padding:20px 0;text-align:center;}
header h1 {margin-bottom:5px;font-size:2em;}
nav ul {list-style:none;display:flex;justify-content:center;gap:20px;}
nav ul li {display:inline;}
section {padding:40px 20px;}
.container {max-width:1200px;margin:0 auto;}
h2 {margin-bottom:20px;color:#222;}
.grid {display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
.card {background:#fff;padding:20px;border-radius:10px;box-shadow:0 2px 5px rgba(0,0,0,0.1);transition:0.3s;}
.card:hover {transform:translateY(-5px);box-shadow:0 5px 15px rgba(0,0,0,0.2);}
.card img {width:100%;height:150px;object-fit:cover;border-radius:5px;margin-bottom:15px;}
footer {background:#222;color:#fff;text-align:center;padding:20px;margin-top:20px;}
button {padding:10px 20px;border:none;background:#e8491d;color:#fff;border-radius:5px;cursor:pointer;}
button:hover {background:#cf3c12;}
</style>
</head>
<body>

<header>
  <div class="container">
    <h1>AutoParts Hub</h1>
    <nav>
      <ul>
        <li><a href="#engine">Engine</a></li>
        <li><a href="#brakes">Brakes</a></li>
        <li><a href="#tires">Tires</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<section id="engine">
  <div class="container">
    <h2>Engine Parts</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Spark+Plug" alt="Spark Plug">
        <h3>Spark Plug</h3>
        <p>Essential for igniting fuel in the engine cylinders.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Oil+Filter" alt="Oil Filter">
        <h3>Oil Filter</h3>
        <p>Keeps your engine oil clean for optimal performance.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Air+Filter" alt="Air Filter">
        <h3>Air Filter</h3>
        <p>Prevents dirt and debris from entering your engine.</p>
        <button>Buy Now</button>
      </div>
    </div>
  </div>
</section>

<section id="brakes">
  <div class="container">
    <h2>Brake Parts</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Brake+Pads" alt="Brake Pads">
        <h3>Brake Pads</h3>
        <p>Provide reliable stopping power for your vehicle.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Brake+Disc" alt="Brake Disc">
        <h3>Brake Disc</h3>
        <p>Durable discs for smooth braking performance.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Brake+Fluid" alt="Brake Fluid">
        <h3>Brake Fluid</h3>
        <p>Maintains hydraulic pressure in braking system.</p>
        <button>Buy Now</button>
      </div>
    </div>
  </div>
</section>

<section id="tires">
  <div class="container">
    <h2>Tires</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=All-Season+Tire" alt="All-Season Tire">
        <h3>All-Season Tire</h3>
        <p>Reliable traction in all weather conditions.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Performance+Tire" alt="Performance Tire">
        <h3>Performance Tire</h3>
        <p>High-speed stability and superior grip for sports cars.</p>
        <button>Buy Now</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x150?text=Off-Road+Tire" alt="Off-Road Tire">
        <h3>Off-Road Tire</h3>
        <p>Durable tires built for rough terrains and adventure.</p>
        <button>Buy Now</button>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="container">
    <h2>Contact Us</h2>
    <form style="max-width:600px;margin:auto;display:flex;flex-direction:column;gap:10px;">
      <input type="text" placeholder="Your Name" required style="padding:10px;border-radius:5px;border:1px solid #ccc;">
      <input type="email" placeholder="Your Email" required style="padding:10px;border-radius:5px;border:1px solid #ccc;">
      <textarea placeholder="Message" required style="padding:10px;border-radius:5px;border:1px solid #ccc;" rows="5"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <p>&copy; 2026 AutoParts Hub. All rights reserved.</p>
</footer>

</body>
</html>
