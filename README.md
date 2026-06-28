<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>بحبك يا رورو 💖</title>
<style>
body {
  margin: 0;
  height: 100vh;
  background: radial-gradient(circle at center, #000, #111, #222);
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  font-family: 'Cairo', sans-serif;
}
h1 {
  font-size: 70px;
  color: #ff66cc;
  text-shadow: 0 0 20px #ff66cc, 0 0 40px #ff99ff, 0 0 80px #ffccff;
  animation: glow 3s infinite alternate;
}
@keyframes glow {
  0% { text-shadow: 0 0 10px #ff66cc; }
  100% { text-shadow: 0 0 50px #ff99ff; }
}
.heart {
  position: absolute;
  font-size: 30px;
  color: #ff3399;
  animation: float 6s infinite ease-in-out;
}
@keyframes float {
  0% { transform: translateY(0); opacity: 1; }
  100% { transform: translateY(-100vh); opacity: 0; }
}
</style>
</head>
<body>
<h1>بحبك يا رورو 💖</h1>

<!-- قلوب متحركة -->
<div class="heart" style="left:10%; animation-delay:0s;">💞</div>
<div class="heart" style="left:30%; animation-delay:2s;">💖</div>
<div class="heart" style="left:50%; animation-delay:4s;">💘</div>
<div class="heart" style="left:70%; animation-delay:1s;">💓</div>
<div class="heart" style="left:90%; animation-delay:3s;">💗</div>

</body>
</html>
