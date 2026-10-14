<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Verdeva — Frescura natural, hecha a tu manera</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#f7f4ec;--bg2:#eee9db;--card:#fffdf8;--ink:#1c2a22;--mut:#5c6b61;--g:#2f5d46;--g2:#7fa88a;--gold:#b88a3e;--line:#dcd5c3;--hero:linear-gradient(160deg,#1f4332,#2f5d46 60%,#4d7f63);--heroink:#f7f4ec;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#101a15;--bg2:#15231c;--card:#182720;--ink:#ece8da;--mut:#9fb0a5;--g:#8fc4a1;--g2:#5e8f70;--gold:#d9ad62;--line:#2a3d32;--hero:linear-gradient(160deg,#0c1712,#17352a 60%,#245039)}}
:root[data-theme="dark"]{--bg:#101a15;--bg2:#15231c;--card:#182720;--ink:#ece8da;--mut:#9fb0a5;--g:#8fc4a1;--g2:#5e8f70;--gold:#d9ad62;--line:#2a3d32;--hero:linear-gradient(160deg,#0c1712,#17352a 60%,#245039)}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:calc(70px + env(safe-area-inset-top,0px))}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.65 Inter,system-ui,sans-serif}
h1,h2,h3{font-family:'Cormorant Garamond',Georgia,serif;font-weight:600;line-height:1.1;margin:0}
h2{font-size:clamp(2rem,5vw,3.2rem);margin-bottom:14px}h3{font-size:1.5rem}
p{margin:0 0 12px;color:var(--mut)}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:9;display:flex;justify-content:space-between;align-items:center;padding:14px 5vw;background:color-mix(in srgb,var(--bg) 88%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
nav b{font:600 1.5rem 'Cormorant Garamond',serif;letter-spacing:.12em;color:var(--g)}
nav div{display:flex;gap:22px;overflow-x:auto}nav a{color:var(--ink);text-decoration:none;font-size:.85rem;white-space:nowrap;opacity:.75}nav a:hover{opacity:1;color:var(--g)}
section{padding:90px 5vw;max-width:1180px;margin:auto}
.eyebrow{font-size:.75rem;letter-spacing:.22em;text-transform:uppercase;color:var(--gold);font-weight:600;margin-bottom:12px;display:block}
.hero{background:var(--hero);color:var(--heroink);max-width:none;text-align:center;padding:130px 5vw 110px;position:relative;overflow:hidden}
.hero:before,.hero:after{content:"";position:absolute;border-radius:50%;background:rgba(255,255,255,.05)}
.hero:before{width:520px;height:520px;top:-200px;left:-140px}.hero:after{width:380px;height:380px;bottom:-160px;right:-80px}
.hero>*{position:relative}.hero h1{font-size:clamp(3.6rem,13vw,8rem);letter-spacing:.14em;margin:10px 0}
.hero p{color:#dbe6dc;font-size:1.2rem;max-width:560px;margin:0 auto 28px}
.hero .eyebrow{color:#e3c58d}.btn{display:inline-block;padding:14px 32px;border-radius:99px;background:#f7f4ec;color:#1f4332;text-decoration:none;font-weight:600}
.names{margin-top:46px;font-size:.9rem;color:#cfdcd0;line-height:1.9}.names b{display:block;color:#fff;font-weight:500}
.alt{background:var(--bg2);max-width:none}.alt>.in{max-width:1180px;margin:auto}
.grid{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));margin-top:34px}
.card{background:var(--card);border:1px solid var(--line);border-radius:22px;padding:28px;transition:.3s}.card:hover{transform:translateY(-4px);box-shadow:0 18px 40px -22px var(--g)}
.num{font:600 3.4rem 'Cormorant Garamond',serif;color:var(--g);line-height:1}
.ico{width:46px;height:46px;border-radius:50%;background:var(--g);color:var(--bg);display:grid;place-items:center;font:600 1.2rem 'Cormorant Garamond',serif;margin-bottom:14px}
.steps{display:flex;flex-wrap:wrap;gap:14px;margin-top:30px}.steps div{flex:1 1 150px;text-align:center;background:var(--card);border:1px solid var(--line);border-radius:20px;padding:22px 12px}
.steps i{display:block;font:600 2.2rem 'Cormorant Garamond',serif;color:var(--gold);font-style:normal}
.two{display:grid;gap:40px;grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.bar{margin:12px 0}.bar span{display:flex;justify-content:space-between;font-size:.88rem;margin-bottom:5px;color:var(--ink)}
.bar div{height:9px;background:var(--line);border-radius:9px;overflow:hidden}.bar div i{display:block;height:100%;background:linear-gradient(90deg,var(--g2),var(--g));border-radius:9px}
.q{font-weight:600;font-size:1rem;color:var(--ink);margin-bottom:6px}
.stats{display:grid;gap:20px;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));margin-top:30px}
.scroll{overflow-x:auto;margin-top:26px;border-radius:20px;border:1px solid var(--line);background:var(--card)}
table{width:100%;border-collapse:collapse;min-width:520px}th,td{padding:16px 20px;text-align:left;border-bottom:1px solid var(--line);font-size:.95rem}
th{font-size:.72rem;letter-spacing:.16em;text-transform:uppercase;color:var(--gold)}tr:last-child td{border:0}td.b{font-weight:600;color:var(--g)}
.chart{display:flex;align-items:flex-end;gap:clamp(14px,4vw,44px);height:260px;margin-top:30px;padding:26px 26px 0;background:var(--card);border:1px solid var(--line);border-radius:22px}
.col{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:flex-end;height:100%}
.pair{display:flex;align-items:flex-end;gap:6px;width:100%;justify-content:center;flex:1}.pair i{width:min(38px,40%);border-radius:8px 8px 0 0;position:relative}
.pair i:first-child{background:linear-gradient(var(--g2),var(--g))}.pair i:last-child{background:linear-gradient(#e3c58d,var(--gold))}
.pair i em{position:absolute;top:-22px;left:50%;transform:translateX(-50%);font:600 .72rem Inter;font-style:normal;white-space:nowrap;color:var(--ink)}
.col small{padding:10px 0;font-size:.78rem;color:var(--mut);text-align:center}
.leg{display:flex;gap:20px;margin-top:14px;font-size:.82rem;color:var(--mut)}.leg b{display:inline-block;width:11px;height:11px;border-radius:3px;margin-right:6px}
.donut{width:210px;height:210px;border-radius:50%;background:conic-gradient(var(--g) 0 55%,var(--gold) 55% 85%,var(--g2) 85% 100%);display:grid;place-items:center;margin:auto}
.donut div{width:130px;height:130px;border-radius:50%;background:var(--card);display:grid;place-items:center;text-align:center;font:600 2.3rem/1 'Cormorant Garamond',serif;color:var(--g)}
.donut small{display:block;font:400 .7rem Inter;color:var(--mut);margin-top:4px}
.team .ico{width:64px;height:64px;font-size:1.6rem}
.invest{background:var(--hero);color:var(--heroink);max-width:none;text-align:center}.invest .in{max-width:760px;margin:auto}
.invest p{color:#dbe6dc}.invest .num{color:#fff;font-size:clamp(4rem,12vw,7rem)}
footer{text-align:center;padding:40px 5vw;font-size:.85rem;color:var(--mut)}footer a{color:var(--g)}
.note{font-size:.78rem;color:var(--mut);margin-top:14px}
</style>
</head>
<body>
<nav><b>VERDEVA</b><div><a href="#empresa">Empresa</a><a href="#mercado">Mercado</a><a href="#encuesta">Encuesta</a><a href="#finanzas">Finanzas</a><a href="#equipo">Equipo</a><a href="#inversion">Inversión</a></div></nav>

<section class="hero">
<span class="eyebrow">Frescura natural · Presentación para inversionistas</span>
<h1>VERDEVA</h1>
<p>Crea tu desodorante natural, hecho a tu manera.</p>
<a class="btn" href="#inversion">Conoce la oportunidad</a>
<div class="names">Fundado por<b>José Arturo Cervantes Andrade Castilla Villarreal</b><b>Fidel Nicolás Pablo León</b><b>Leonardo García Villalpando</b>Octubre 2026</div>
</section>

<section id="empresa">
<span class="eyebrow">La empresa</span><h2>El desodorante, convertido en experiencia</h2>
<p style="max-width:640px">Verdeva es una marca de cosmética natural donde cada persona crea el suyo. Hacemos el cuidado personal natural, divertido y accesible para todos: tú eliges cómo se siente, cómo huele y cuánto necesitas.</p>
<div class="grid">
<div class="card"><div class="ico">1</div><h3>Tú lo diseñas</h3><p>Personalizador paso a paso con vista previa en vivo.</p></div>
<div class="card"><div class="ico">2</div><h3>Natural de verdad</h3><p>Sin aluminio ni parabenos. Coco, karité, bicarbonato, almidón y aceites esenciales.</p></div>
<div class="card"><div class="ico">3</div><h3>Hecho a tu medida</h3><p>3 formas, 3 tamaños y más de 9 aromas, o tu propia mezcla.</p></div>
<div class="card"><div class="ico">4</div><h3>Menos impacto</h3><p>Cartón en lugar de plástico y producción por pedido.</p></div>
</div>
<div class="steps"><div><i>1</i>Elige tu forma</div><div><i>2</i>Elige tu tamaño</div><div><i>3</i>Elige tu aroma</div><div><i>4</i>Personaliza tu diseño</div><div><i>5</i>Recibe tu Verdeva</div></div>
</section>

<section class="alt" id="mercado"><div class="in">
<span class="eyebrow">Nuestro mercado</span><h2>Pequeño, cercano y alcanzable</h2>
<p style="max-width:640px">Arrancamos en México, vendiendo en línea y a nuestra propia comunidad. No necesitamos todo el mercado: necesitamos convencer a las primeras 75 personas de que esto funciona.</p>
<div class="stats">
<div class="card"><div class="num">~800</div><p>Personas en la comunidad escolar y círculo cercano: mercado inicial alcanzable.</p></div>
<div class="card"><div class="num">~75</div><p>Clientes meta del primer año, comprando 1–2 veces.</p></div>
<div class="card"><div class="num">15–35</div><p>Rango de edad del cliente ideal: activo y cercano al equipo.</p></div>
</div>
<div class="grid">
<div class="card"><h3>Jóvenes conscientes</h3><p>Leen etiquetas, prefieren lo natural y quieren marcas con identidad.</p></div>
<div class="card"><h3>Pieles sensibles</h3><p>Fórmulas simples, con o sin aroma, sin ingredientes agresivos.</p></div>
<div class="card"><h3>Regalos con nombre</h3><p>Producto con nombre y frase propios: original, útil y accesible.</p></div>
</div>
<p class="note">Canales: tienda en línea, redes sociales, ferias, recomendación entre amigos, ediciones para regalo y venta institucional (tiendas eco-conscientes y gimnasios).</p>
</div></section>

<section id="encuesta">
<span class="eyebrow">Encuesta propia · 40 personas</span><h2>Lo que dice nuestro público</h2>
<div class="stats" style="grid-template-columns:repeat(auto-fit,minmax(150px,1fr))">
<div><div class="num">60%</div><p>usa desodorante de barra</p></div><div><div class="num">90%</div><p>abierto a uno natural sin fragancia</p></div><div><div class="num">95%</div><p>quiere elegir la forma</p></div><div><div class="num">20%</div><p>crearía su propio aroma</p></div>
</div>
<div class="two" style="margin-top:34px" id="charts"></div>
<p class="note">Menta, amaderado y sin aroma: valores estimados por diferencia sobre las 40 respuestas.</p>
</section>

<section class="alt" id="finanzas"><div class="in">
<span class="eyebrow">Modelo y proyecciones</span><h2>Márgenes sanos desde la primera unidad</h2>
<p style="max-width:640px">Producción por lotes de 20 unidades cada tres semanas, venta directa e institucional, y reinversión del margen en materia prima. Cifras conservadoras con crecimiento gradual.</p>
<div class="scroll"><table>
<tr><th>Presentación</th><th>Costo</th><th>Precio</th><th>Margen</th></tr>
<tr><td>Clásica (tubo biodegradable, lote piloto)</td><td>$18</td><td>$65</td><td class="b">≈72%</td></tr>
<tr><td>Mayoreo / eventos (mín. 10 pzas)</td><td>$18</td><td>$48</td><td class="b">≈63%</td></tr>
</table></div>
<div class="scroll"><table>
<tr><th>Horizonte</th><th>Unidades / año</th><th>Ingresos</th><th>Utilidad estimada</th></tr>
<tr><td>Piloto actual (lote 1)</td><td>20</td><td>$1,300</td><td class="b">$940</td></tr>
<tr><td>Año 1 (~12 u./mes)</td><td>150</td><td>$9,000</td><td class="b">$6,300</td></tr>
<tr><td>Año 3 (~25 u./mes)</td><td>300</td><td>$17,400</td><td class="b">$12,000</td></tr>
<tr><td>Año 5 (~42 u./mes)</td><td>500</td><td>$27,500</td><td class="b">$18,500</td></tr>
</table></div>
<div class="chart" id="rev"></div>
<div class="leg"><span><b style="background:var(--g)"></b>Ingresos</span><span><b style="background:var(--gold)"></b>Utilidad · miles de MXN</span></div>
<div class="stats">
<div class="card"><div class="num">4 u/mes</div><p>Punto de equilibrio estimado (costos fijos casi nulos).</p></div>
<div class="card"><div class="num">Mes 1</div><p>Momento en que se alcanza el equilibrio.</p></div>
<div class="card"><div class="num">$715</div><p>Inversión de arranque ya cubierta por el equipo.</p></div>
</div>
</div></section>

<section id="equipo" class="team">
<span class="eyebrow">Equipo</span><h2>Tres fundadores, tres roles complementarios</h2>
<div class="grid">
<div class="card"><div class="ico">JA</div><h3>José Arturo Cervantes Andrade Castilla Villarreal</h3><p><b style="color:var(--g)">Dirección creativa y de marca</b><br>Identidad, diseño y presentación del producto.</p></div>
<div class="card"><div class="ico">FN</div><h3>Fidel Nicolás Pablo León</h3><p><b style="color:var(--g)">Desarrollo de producto</b><br>Formulación, materiales y control de calidad.</p></div>
<div class="card"><div class="ico">LG</div><h3>Leonardo García Villalpando</h3><p><b style="color:var(--g)">Finanzas y estrategia comercial</b><br>Costos, precios, canales y proyecciones.</p></div>
</div>
</section>

<section class="invest" id="inversion"><div class="in">
<span class="eyebrow" style="color:#e3c58d">La inversión</span>
<div class="num">$50,000 MXN</div>
<h2 style="color:#fff">a cambio del 10% de la empresa</h2>
<p>Para producir los siguientes dos lotes sin depender del margen de ventas anteriores, en una operación que ya se sostiene sola.</p>
<div class="donut" style="margin-top:34px"><div>55%<small>materia prima</small></div></div>
<p style="margin-top:22px">55% materia prima · 30% envase y etiqueta · 15% imprevistos</p>
<h3 style="color:#fff;margin-top:50px;font-size:1.9rem">Con tu inversión, Verdeva puede pasar de un proyecto escolar a la alternativa natural favorita de México — una barra a la vez.</h3>
<p style="margin-top:18px">Problema real · Solución probada · Mercado en crecimiento · Equipo comprometido</p>
<span class="eyebrow" style="color:#e3c58d;margin-top:30px">Contacto</span><a class="btn" style="margin:6px 6px" href="https://wa.me/525624477194">WhatsApp 56 2447 7194</a><a class="btn" style="margin:6px 6px;background:transparent;color:#f7f4ec;border:1px solid #f7f4ec" href="mailto:contacto@verdeva.mx">contacto@verdeva.mx</a>
</div></section>

<footer>Verdeva · Tel. <a href="tel:+525624477194">56 2447 7194</a> · Octubre 2026 · Crea tu Verdeva en <a href="https://neofiddev.github.io/verdeva">neofiddev.github.io/verdeva</a></footer>

<script>
var Q=[["¿Qué tipo de desodorante usas actualmente?",[["De barra",60],["En aerosol",15],["De crema",15],["Otro",10]]],
["¿Te interesaría uno natural sin fragancia?",[["Sí",57.5],["Tal vez",32.5],["No",10]]],
["¿Te gustaría personalizar la forma?",[["Sí",72.5],["Tal vez",22.5],["No",5]]],
["¿Qué aroma preferirías?",[["Lavanda",35],["Cítricos",20],["Personalizado",20],["Floral",15],["Menta",5],["Amaderado",2.5],["Sin aroma",2.5]]]];
document.getElementById("charts").innerHTML=Q.map(function(q){return '<div class="card"><div class="q">'+q[0]+'</div>'+q[1].map(function(r){return '<div class="bar"><span>'+r[0]+'<b>'+r[1]+'%</b></span><div><i style="width:'+r[1]+'%"></i></div></div>'}).join('')+'</div>'}).join('');
var D=[["Piloto",1.3,.94],["Año 1",9,6.3],["Año 3",17.4,12],["Año 5",27.5,18.5]];
document.getElementById("rev").innerHTML=D.map(function(d){return '<div class="col"><div class="pair"><i style="height:'+(d[1]/27.5*100)+'%"><em>'+d[1]+'k</em></i><i style="height:'+(d[2]/27.5*100)+'%"><em>'+d[2]+'k</em></i></div><small>'+d[0]+'</small></div>'}).join('');
</script>
</body>
</html>
