# nandni-rose-day
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Rose Day Nandni 🌹</title>

<style>
body{
  margin:0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(to bottom, #ff5f6d, #ffc371);
  color:white;
  text-align:center;
  overflow-x:hidden;
}

section{
  padding:60px 20px;
}

h1{
  font-size:2.6em;
}

.rose{
  font-size:4em;
  animation: float 2s infinite;
}

@keyframes float{
  0%{transform:translateY(0)}
  50%{transform:translateY(-12px)}
  100%{transform:translateY(0)}
}

.card{
  background:rgba(255,255,255,0.25);
  padding:25px;
  border-radius:20px;
  max-width:700px;
  margin:auto;
}

.gallery img{
  width:100%;
  max-width:220px;
  border-radius:20px;
  margin:10px;
}

.gallery{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
}

.heart{
  position:fixed;
  top:-10px;
  font-size:20px;
  animation: fall linear infinite;
}

@keyframes fall{
  to{
    transform:translateY(110vh);
  }
}
</style>
</head>

<body>

<!-- Background Music -->
<audio autoplay loop>
  <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_0c1b8d8f3a.mp3" type="audio/mpeg">
</audio>

<!-- Section 1 -->
<section>
  <div class="rose">🌹</div>
  <h1>Happy Rose Day Nandni</h1>
  <p>Scroll karo jaan… surprise baaki hai 💖</p>
</section>

<!-- Section 2 -->
<section>
  <div class="card">
    <p>
      <strong>Nandni ❤️</strong><br><br>
      Tum meri zindagi ka wo rose ho jiska rang kabhi fade nahi hota.<br>
      Tumhari muskaan meri duniya ko mehka deti hai.<br>
      Har pal tumhare saath ek khoobsurat kahani lagti hai.<br><br>
      Rose Day ho ya koi bhi din,<br>
      main hamesha sirf tumhara hi rahunga 🌹<br><br>
      <strong>– Tumhara pyaara dudu 💖</strong>
    </p>
  </div>
</section>

<!-- Section 3 Photos -->
<section>
  <h2>Hamari Yaadein 📸</h2>
  <div class="gallery">
    <img src="https://via.placeholder.com/300x300?text=Us+Smile+❤️">
    <img src="https://via.placeholder.com/300x300?text=Best+Moment+🌹">
    <img src="https://via.placeholder.com/300x300?text=Forever+Together+💑">
  </div>
  <p>(Apni photos baad me replace kar sakte ho)</p>
</section>

<!-- Ending -->
<section>
  <h2>I Love You Nandni 💘</h2>
  <p>Tum meri duniya ho… aaj bhi, kal bhi, hamesha ❤️</p>
</section>

<script>
for(let i=0;i<40;i++){
  let heart=document.createElement("div");
  heart.className="heart";
  heart.innerHTML="💖";
  heart.style.left=Math.random()*100+"vw";
  heart.style.animationDuration=(3+Math.random()*5)+"s";
  document.body.appendChild(heart);
}
</script>

</body>
</html>
