## Lifestyle

<!DOCTYPE html>
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
    <img src="assets/img/icma2.png" alt="Duke Halloween">
    <div class="caption">Duke Halloween.<br>2023.11, Duke University.</div>
  </div>
  <div>
    <img src="assets/img/icma2.png" alt="Last dance in Levien Gym">
    <div class="caption">Last dance in Levien Gym :(.<br>2022.12, Columbia.</div>
  </div>
  <div>
    <img src="assets/img/icma2.png" alt="Columbia Boat Cruise Social">
    <div class="caption">Columbia Boat Cruise Social.<br>2022.09, Columbia.</div>
  </div>
  <div>
    <img src="assets/img/icma2.png" alt="Shout out to Kobe">
    <div class="caption">Shout out to Kobe.<br>2022.08, Los Angeles.</div>
  </div>
</div>

</body>
</html>
