<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>我的作品集</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    h1 {
      text-align: center;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s;
    }

    .gallery img:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body>

  <h1>我的作品集</h1>

  <div class="gallery">
    <!-- Replace the following URLs with the URLs of your photos -->
    <img src="photo1.jpg" alt="Photo 1">
    <img src="photo2.jpg" alt="Photo 2">
    <img src="photo3.jpg" alt="Photo 3">
    <!-- Add more images as needed -->
  </div>

</body>
</html>
