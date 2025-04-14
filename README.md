# CODEALPHA-task1-image-gallery
task 1-image gallery
<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      text-align: center;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 30px;
    }
    .gallery img {
      width: 200px;
      height: 150px;
      object-fit: cover;
      cursor: pointer;
      border-radius: 8px;
      transition: transform 0.2s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <h1>My Image Gallery</h1>
  <div class="gallery">
    <img src="https://placekitten.com/200/150" alt="Cat 1">
    <img src="https://placekitten.com/201/150" alt="Cat 2">
    <img src="https://placekitten.com/202/150" alt="Cat 3">
    <img src="https://placekitten.com/203/150" alt="Cat 4">
  </div>
</body>
</html>
