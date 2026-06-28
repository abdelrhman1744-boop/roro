<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>روّرو 👑</title>
<style>
body {
  margin: 0;
  height: 100vh;
  background: radial-gradient(circle at center, #000000, #0a0a0a, #1a1a1a);
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  font-family: 'Cairo', sans-serif;
}
h1 {
  font-size: 80px;
  color: #ff00cc;
  text-shadow: 0 0 20px #ff00cc, 0 0 40px #ff66ff, 0 0 80px #ff99ff;
  animation: glow 3s infinite alternate, move 6s infinite ease-in-out;
}
@keyframes glow {
  0% { text-shadow: 0 0 10px #ff00cc, 0 0 20px #ff66ff; }
  100% { text-shadow: 0 0 40px #ff00cc, 0 0 80px #ff99ff; }
}
@keyframes move {
  0% { transform: translateY(0); }
  50% { transform: translateY(-20px); }
  100% { transform: translateY(0); }
}
</style>
</head>
<body>
<h1>روّرو 👑</h1>

<!-- موسيقى خلفية -->
<audio autoplay loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
  متصفحك لا يدعم تشغيل الصوت.
</audio>

</body>
</html>
