<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>230191601019</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #e6f2ff;
    margin: 0;
    padding: 10px;
  }

  .map-container {
    position: relative; /* Needed for absolute positioning of spots */
    max-width: 700px;
    margin-bottom: 20px;
  }

  .map-container img {
    max-width: 100%;
    height: auto;
    border: 2px solid #003366;
    display: block;
  }

  /* City spot markers */
  .spot {
    position: absolute;
    width: 16px;
    height: 16px;
    background: red;
    border: 2px solid #fff;
    border-radius: 50%;
    cursor: pointer;
    transform: translate(-50%, -50%);
  }

  /* Info sections */
  section {
    background: #fff;
    border: 2px solid #003366;
    padding: 10px;
    margin-bottom: 15px;
    max-width: 700px;
  }

  h2 {
    color: #003366;
    margin-top: 0;
  }

  /* Smooth scroll + highlight */
  html {
    scroll-behavior: smooth;
  }
  section:target {
    background: #cce6ff;
    border-color: #0066cc;
  }
</style>
</head>
<body>

<div class="map-container">
  <img src="map.PNG" alt="Map of England">

  <!-- Spots placed at coordinates (relative to the image size) -->
  <a href="#london" class="spot" style="top: 70%; left: 60%;" title="London"></a>
  <a href="#manchester" class="spot" style="top: 45%; left: 40%;" title="Manchester"></a>
  <a href="#liverpool" class="spot" style="top: 42%; left: 37%;" title="Liverpool"></a>
  <a href="#birmingham" class="spot" style="top: 55%; left: 48%;" title="Birmingham"></a>
</div>

<section id="london">
  <h2>London</h2>
  <p><strong>Capital city of England</strong>, famous for Big Ben, Tower Bridge, and the River Thames.</p>
</section>

<section id="manchester">
  <h2>Manchester</h2>
  <p><strong>Known for football</strong>, industrial revolution heritage, and vibrant music culture.</p>
</section>

<section id="liverpool">
  <h2>Liverpool</h2>
  <p><strong>Famous port city</strong>, home of The Beatles and Liverpool FC.</p>
</section>

<section id="birmingham">
  <h2>Birmingham</h2>
  <p><strong>Known for canals</strong>, Bullring shopping centre, and diverse culture.</p>
</section>

</body>
</html>
