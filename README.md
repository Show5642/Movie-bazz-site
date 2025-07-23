<!DOCTYPE html>📁 my-video-site/
   ├── index.html
   └── myvideo.mp4
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>ভিডিও ওয়েবসাইট</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #eef2f3;
      text-align: center;
      padding: 50px;
    }
    video {
      width: 80%;
      max-width: 720px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      font-size: 18px;
      background-color: #28a745;
      color: white;
      text-decoration: none;
      border-radius: 8px;
    }
    .btn:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>

  <h1>আমার ভিডিও</h1>

  <video controls>
    <source src="myvideo.mp4" type="video/mp4">
    আপনার ব্রাউজার ভিডিও সাপোর্ট করে না।
  </video>

  <br>
  <a href="myvideo.mp4" download class="btn">🎬 ভিডিও ডাউনলোড করুন</a>

</body>
</html>
