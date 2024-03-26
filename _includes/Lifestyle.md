## Lifestyle

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Image Gallery</title>
<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 16px;
    padding: 16px;
  }
  .gallery img {
    width: 100%;
    height: auto;
  }
  .caption {
    text-align: center;
    margin-top: 4px;
  }
</style>
</head>
<body>

<div class="gallery">
  <div>
    <img src="assets/img/rcar2.jpg" alt="Presentation in RCAR2023">
    <div class="caption">Presentation at RCAR2023.<br>2023.07, Datong, China.</div>
  </div>
  <div>
    <img src="assets/img/icma3.jpg" alt="Presentation in ICMA2023">
    <div class="caption">Presentation at ICMA2023 .<br>2023.08, Harbin, China.</div>
  </div>
<!--   <div>
    <img src="assets/img/icma2.png" alt="xxx">
    <div class="caption">xxx.<br>xxx.</div>
  </div>
  <div>
    <img src="assets/img/icma2.png" alt="xxx">
    <div class="caption">xxx.<br>xxx.</div>
  </div> -->
</div>

</body>
</html>
