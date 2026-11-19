
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Maria 💗</title>
<style>
* { box-sizing: border-box; }
body {
  margin: 0;
  font-family: Georgia, serif;
  background: #fff0f5;
  color: #925d70;
  text-align: center;
}
.hero {
  padding: 65px 20px 35px;
  background: linear-gradient(#ffe0eb, #fff0f5);
}
h1 { font-size: 36px; color: #d7799c; }
h2 { color: #d7799c; }
.bear { font-size: 85px; }
.card {
  background: white;
  margin: 22px auto;
  padding: 25px;
  width: 88%;
  max-width: 480px;
  border-radius: 25px;
  box-shadow: 0 5px 18px #e8b6c8;
}
button {
  border: 0;
  border-radius: 30px;
  padding: 15px 25px;
  background: #ed9fbb;
  color: white;
  font-size: 17px;
  cursor: pointer;
}
#letter { display: none; line-height: 1.8; }
footer { padding: 30px; }
</style>
</head>
<body>

<section class="hero">
  <div class="bear">🧸</div>
  <h1>¡Feliz primer mes, Maria! 💗</h1>
  <p>Una pequeña página para alguien muy especial.</p>
  <p>🌷 19 de noviembre 🌷</p>
</section>

<div class="card">
  <h2>💕 Un mes contigo 💕</h2>
  <p>
    Puede que esta página sea pequeña,
    pero está hecha con muchísimo cariño.
    Quiero dedicarte este pequeño espacio.
  </p>
  <div style="font-size:45px">🐻🌸🐻</div>
</div>

<div class="card">
  <h2>💌 Una carta para ti</h2>
  <p>Maria, tengo algo que decirte...</p>
  <button onclick="document.getElementById('letter').style.display='block';this.style.display='none'">
    Abrir mi sorpresa 💗
  </button>
  <div id="letter">
    <p>
      Feliz primer mes, Maria. 💕
      Quiero agradecerte por cada conversación,
      cada sonrisa y cada momento bonito.
      Espero que sigamos creando muchos recuerdos
      y que este sea solamente el comienzo
      de una historia muy especial.
    </p>
    <div style="font-size:45px">🧸💗🧸</div>
    <p>Con muchísimo cariño. ❤️</p>
  </div>
</div>

<div class="card">
  <h2>🌷 Mi deseo para nosotros</h2>
  <p>Que nunca nos falten motivos para sonreír,
  momentos bonitos y nuevas aventuras.</p>
  <div style="font-size:45px">💞</div>
</div>

<footer>
  Hecho con cariño para Maria 🧸<br>
  <p>💕 19 de noviembre 💕</p>
</footer>

</body>
</html>
