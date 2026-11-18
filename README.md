<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Adelaida – CV</title>
<style>
:root{--color:#c0182b;--claro:#fbe0e0;--oscuro:#111;--texto:#222}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Segoe UI',Arial,Helvetica,sans-serif;background:#d9dde2;color:var(--texto);line-height:1.55;padding:20px}
.hoja{max-width:794px;margin:auto;background:#fff;box-shadow:0 4px 20px rgba(0,0,0,.25);overflow:hidden}
.cabeza{display:grid;grid-template-columns:34% 66%;background:var(--color);min-height:245px}
.foto-col{background:var(--claro);position:relative;padding:30px 0 0 30px}
.foto-col::after{content:"";position:absolute;right:0;bottom:0;width:0;height:0;border-style:solid;border-width:0 0 32px 32px;border-color:transparent transparent #fff transparent}
.foto{display:block;width:100%;aspect-ratio:1/1;max-width:215px;overflow:hidden;cursor:pointer;background:#fff}
.foto img{width:100%;height:100%;object-fit:cover;display:block}
.cambiar{display:inline-block;font-size:11px;margin-top:6px;text-decoration:underline;cursor:pointer;color:#7a0f1f}
.titulo{padding:56px 34px 20px 34px;color:#fff}
.titulo h1{font-size:34px;font-weight:800;line-height:1.1}
.titulo hr{border:0;height:4px;background:#fff;margin:14px 0}
.titulo p{font-size:13px;font-weight:700}
.cuerpo{display:grid;grid-template-columns:34% 66%}
.lateral{background:var(--claro);padding:28px 24px 40px 30px}
.principal{padding:28px 30px 40px 22px}
h2{font-size:16px;font-weight:800;text-transform:uppercase;letter-spacing:.4px;color:var(--oscuro);margin-bottom:14px;padding-top:12px;border-top:1.5px solid var(--oscuro)}
.principal h2{border-top:1px solid var(--color);margin-top:0}
.lateral section{margin-bottom:30px}
.lateral p,.lateral li{font-size:13px;margin-bottom:10px;word-break:break-word}
.lateral ul{margin-left:18px}
.dato{display:flex;gap:10px;align-items:flex-start}
.dato i{flex:none;width:22px;height:22px;background:#333;color:#fff;border-radius:4px;font-style:normal;font-size:12px;display:flex;align-items:center;justify-content:center;margin-top:1px}
.dato a{color:inherit;text-decoration:none}
.barra{height:5px;background:#fff;margin:6px 0}
.barra b{display:block;height:100%;background:var(--color)}
.trabajo{margin-bottom:22px}
.fila{display:flex;justify-content:space-between;gap:10px;font-size:13px;font-weight:700}
.fila span{font-weight:400}
.empresa{font-size:13px;color:var(--color);font-weight:700;margin:2px 0 8px}
.empresa span{color:#555;font-weight:400}
.principal ul{margin-left:18px}
.principal li{font-size:13px;margin-bottom:5px}
.principal section{margin-bottom:26px}
.estudio{font-size:13px;margin-bottom:14px}
.imprimir{display:block;margin:18px auto 0;background:var(--color);color:#fff;border:0;padding:12px 28px;border-radius:26px;font-weight:700;font-size:14px;cursor:pointer}
@media(max-width:680px){
  body{padding:0}
  .cabeza,.cuerpo{grid-template-columns:1fr}
  .foto-col{padding:24px;text-align:center}
  .foto-col::after{display:none}
  .foto{margin:auto;max-width:190px;border-radius:50%}
  .titulo{padding:22px 24px}
  .principal{padding:24px}
  .lateral{padding:24px}
}
@media print{
  @page{size:A4;margin:0}
  body{background:#fff;padding:0}
  .hoja{box-shadow:none;max-width:none}
  .imprimir,.cambiar{display:none}
  *{-webkit-print-color-adjust:exact;print-color-adjust:exact}
}
</style>
</head>
<body>
<div class="hoja">
  <div class="cabeza">
    <div class="foto-col">
      <label class="foto" id="foto-box" for="foto"><img src="foto.jpg" alt="Foto de Adelaida"></label>
      <label class="cambiar" for="foto">📷 Cambiar mi foto</label>
      <input type="file" id="foto" accept="image/*" hidden>
    </div>
    <div class="titulo">
      <h1>Adelaida</h1>
      <hr>
      <p>Asistente en minería. Persona responsable, puntual y disciplinada, comprometida con la seguridad y el trabajo en equipo. Estoy por terminar mis estudios en el Tecnológico de Santa Lucía y busco trabajar en minas como asistente, aportando mi esfuerzo y mis ganas de crecer en el sector minero.</p>
    </div>
  </div>

  <div class="cuerpo">
    <aside class="lateral">
      <section>
        <h2>Contacto</h2>
        <div class="dato"><i>📍</i><p>Perú</p></div>
        <div class="dato"><i>📞</i><p><a href="tel:+51906376533">906 376 533</a></p></div>
        <div class="dato"><i>@</i><p><a href="mailto:adelaidaquispepineda69@gmail.com">adelaidaquispepineda69@gmail.com</a></p></div>
      </section>

      <section>
        <h2>Aptitudes</h2>
        <ul>
          <li>Responsabilidad</li>
          <li>Puntualidad</li>
          <li>Disciplina</li>
          <li>Seguridad en el trabajo</li>
          <li>Trabajo en equipo</li>
        </ul>
      </section>

      <section>
        <h2>Idiomas</h2>
        <p><strong>Español</strong>: Idioma nativo</p>
        <p><strong>Inglés</strong>: Básico</p>
        <div class="barra"><b style="width:30%"></b></div>
      </section>
    </aside>

    <main class="principal">
      <section>
        <h2>Prácticas preprofesionales</h2>
        <div class="trabajo">
          <div class="fila">Prácticas técnicas <span>08/2025</span></div>
          <div class="empresa">Tecnológico de Santa Lucía <span>– Perú</span></div>
          <ul>
            <li>Ofimática.</li>
            <li>Mantenimiento.</li>
            <li>Fibra óptica.</li>
            <li>Diseño en AutoCAD.</li>
            <li>Excel.</li>
            <li>Uso de guantes y kit de herramientas.</li>
          </ul>
        </div>
      </section>

      <section>
        <h2>Formación académica</h2>
        <div class="estudio">
          <strong>Estudios en curso</strong>, 2024 – 2026<br>
          <strong>Tecnológico de Santa Lucía</strong> – Por terminar
        </div>
      </section>
    </main>
  </div>
</div>

<button class="imprimir" onclick="window.print()">Descargar CV en PDF</button>

<script>
var box=document.getElementById('foto-box'),input=document.getElementById('foto');
function mostrar(src){box.innerHTML='<img src="'+src+'" alt="Foto de Adelaida">';}
try{var g=localStorage.getItem('fotoAdelaida');if(g)mostrar(g);}catch(e){}
input.addEventListener('change',function(){
  var f=input.files[0];if(!f)return;
  var r=new FileReader();
  r.onload=function(){mostrar(r.result);try{localStorage.setItem('fotoAdelaida',r.result);}catch(e){}};
  r.readAsDataURL(f);
});
</script>
</body>
</html>
