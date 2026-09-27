<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>نور عيني ♡</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Playfair+Display:wght@500;600;700&family=Noto+Naskh+Arabic:wght@400;500;600;700&display=swap');

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: linear-gradient(135deg, #fff7f9, #f6e2e9);
  color: #4b3039;
  font-family: "Noto Naskh Arabic", serif;
}

.intro {
  position: fixed;
  inset: 0;
  background: #fff8fa;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 999;
  transition: opacity 1s ease;
}

.intro.hide {
  opacity: 0;
  pointer-events: none;
}

.intro h1 {
  font-family: "Playfair Display", serif;
  color: #94576b;
  font-size: 42px;
}

.container {
  width: 100%;
  max-width: 760px;
  margin: auto;
  padding: 25px 17px 60px;
}

.card {
  background: rgba(255,255,255,.82);
  border: 1px solid #efd7df;
  border-radius: 28px;
  padding: 25px;
  margin-bottom: 22px;
  box-shadow: 0 10px 30px rgba(110,65,80,.12);
}

.heart {
  text-align: center;
  font-size: 32px;
  color: #a35e74;
}

h1 {
  text-align: center;
  font-family: "Playfair Display", serif;
  color: #92556a;
  font-size: 40px;
  margin: 5px 0;
}

h2 {
  text-align: center;
  font-family: "Playfair Display", serif;
  color: #92556a;
  font-size: 27px;
}

.intro-text {
  text-align: center;
  color: #8b6570;
}

.memory {
  background: #fff2f5;
  border-radius: 18px;
  padding: 14px 17px;
  margin: 12px 0;
  line-height: 1.9;
  font-size: 18px;
}

.date {
  display: block;
  color: #9b5b70;
  font-family: "Cormorant Garamond", serif;
  font-size: 25px;
  font-weight: bold;
  direction: ltr;
  text-align: right;
}

.message {
  font-size: 19px;
  line-height: 2.05;
  white-space: pre-line;
}

.music {
  text-align: center;
}

button {
  border: none;
  border-radius: 999px;
  padding: 13px 25px;
  background: #995b70;
  color: white;
  font-family: inherit;
  font-size: 17px;
  cursor: pointer;
}

audio {
  width: 100%;
  margin-top: 18px;
}

.footer {
  text-align: center;
  color: #9a6a78;
  font-size: 18px;
}
</style>
</head>

<body>

<!-- شاشة البداية -->
<div class="intro" id="intro">
  <h1>My everythink ♡</h1>
</div>

<div class="container">

  <!-- العنوان -->
  <section class="card">
    <div class="heart">♡</div>
    <h1>نور عيني</h1>
    <p class="intro-text">
      حكايتنا والذكريات اللي بحبها
    </p>
  </section>

  <!-- الذكريات -->
  <section class="card">
    <h2>ذكرياتنا ♡</h2>

    <div class="memory">
      <span class="date">27/1</span>
      أول مرة شوفتني فيها كانت في استوري عيد ميلادي.
    </div>

    <div class="memory">
      <span class="date">5/2</span>
      أول مرة إنت شوفتني فيها كنت طالعة من عند معتز.
    </div>

    <div class="memory">
      <span class="date">9/2</span>
      أول مرة شوفتك فيها كانت في العربية، وكنا الصبح.
    </div>

    <div class="memory">
      <span class="date">24/2</span>
      أول مرة اتكلمنا.
    </div>

    <div class="memory">
      <span class="date">27/2</span>
      أول مرة
