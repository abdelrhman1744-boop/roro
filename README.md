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

/* القلب الكبير */
.heart {
  position: relative;
  width: 200px;
  height: 180px;
  background: #ff0066;
  transform: rotate(-45deg);
  animation: pulse 2s infinite;
  box-shadow: 0 0 40px #ff66cc, 0 0 80px #ff99ff;
}
.heart::before,
.heart::after {
  content: '';
  position: absolute;
  width: 200px;
  height: 180px;
  background: #ff0066;
  border-radius: 50%;
}
.heart::before {
  top: -100px;
