<!DOCTYPE html> 
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Undangan Rina & Andi</title>
<style>
body{font-family:Arial;margin:0;background:#faf7f2}
.opening{position:fixed;top:0;left:0;width:100%;height:100%;background:linear-gradient(135deg,#f5e6d3,#e8d5d5);display:flex;align-items:center;justify-content:center;z-index:9999}
.card{background:white;padding:40px;border-radius:20px;text-align:center;box-shadow:0 10px 30px rgba(0,0,0,0.1)}
.btn{background:#d4a5a5;color:white;border:none;padding:15px 40px;border-radius:30px;font-size:16px}
.content{display:none}
.content.show{display:block}
.hero{background:url('https://images.unsplash.com/photo-1519741497674-611481863552?w=800') center/cover;height:100vh;display:flex;align-items:center;justify-content:center;color:white;text-align:center}
section{padding:60px 20px;max-width:800px;margin:0 auto}
h2{color:#d4a5a5;text-align:center}
.map{width:100%;height:300px;border:none;border-radius:15px}
.qris{background:#2c2c2c;color:white;padding:40px 20px;text-align:center}
.qris-box{background:white;color:#333;padding:30px;border-radius:15px;max-width:300px;margin:0 auto}
.qr{width:200px;height:200px;margin:20px auto;background:#f0f0f0;display:flex;align-items:center;justify-content:center}
footer{background:#2c2c2c;color:white;text-align:center;padding:30px}
</style>
</head>
<body>

<div class="opening" id="open">
<div class="card>
<h1>Rina & Andi</h1>
<p>15 Juni 2024</p>
<button class="btn" onclick="start()">Buka Undangan</button>
</div>
</div>

<div class="content" id="main">
<div class="hero>
<h1>We're Getting Married</h1>
</div>

<section>
<h2>Lokasi Acara</h2>
<iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.5!2d106.82!3d-6.19!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNsKwMTEnNDEuMSJTIDEwNsKwNDknMTIuMCJF!5e0!3m2!1sen!2sid!4v1"></iframe>
<br><br>
<a href="https://maps.google.com/?q=-6.1947,106.8200" style="background:#d4a5a5;color:white;padding:15px 30px;border-radius:30px;text-decoration:none;">Buka Google Maps</a>
</section>

<div class="qris">
<h2>Kirim Hadiah via QRIS</h2>
<div class="qris-box>
<div class="qr">
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=QRIS" width="200">
</div>
<p>Scan dengan GoPay/OVO/DANA</p>
</div>
</div>

<footer>
<h2>Rina & Andi</h2>
<p>Terima kasih</p>
</footer>
</div>

<script>
function start(){
document.getElementById('open').style.display='none';
document.getElementById('main').classList.add('show');
}
</script>

</body>
</html>
