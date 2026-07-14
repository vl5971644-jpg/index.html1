// =======================================
// effects.js
// Efectos especiales XV Devany
// =======================================

// Brillo en el título
const titulo = document.querySelector("header h1");

if (titulo) {

    let brillo = 0;

    setInterval(() => {

        brillo += 0.08;

        titulo.style.textShadow =
            `0 0 ${20 + Math.sin(brillo) * 15}px gold,
             0 0 ${35 + Math.sin(brillo) * 10}px #d8b4ff`;

    }, 60);

}

// Destellos dorados
function crearDestello(){

    const estrella = document.createElement("div");

    estrella.innerHTML = "✨";

    estrella.style.position = "fixed";
    estrella.style.left = Math.random()*100 + "vw";
    estrella.style.top = Math.imagenes{
    max-width:500px;
    margin:40px auto;
    position:relative;
}

.imagenes img{
    display:none;
    width:100%;
    border-radius:20px;
    border:4px solid gold;
    box-shadow:0 0 30px rgba(255,215,0,.4);
    animation:fade 1s;
}

@keyframes fade{

from{
opacity:0;
transform:scale(.95);
}

to{
opacity:1;
transform:scale(1);
}

}// ======================================
// CARRUSEL AUTOMÁTICO
// XV DEVANY
// ======================================

const galeria = document.querySelector(".imagenes");

if (galeria) {

    const imagenes = galeria.querySelectorAll("img");

    let indice = 0;

    function mostrarImagen(i){

        imagenes.forEach((img,pos)=>{

            img.style.display = (pos===i) ? "block" : "none";

        });

    }

    mostrarImagen(indice);

    setInterval(()=>{

        indice++;

        if(indice>=imagenes.length){

            indice=0;

        }

        mostrarImagen(indice);

    },4000);

}<section>

<h2 class="titulo">¡Estás cordialmente invitado!</h2>

<div class="card">

<p>

Hay momentos inolvidables que se atesoran en el corazón para siempre.

Hoy quiero compartir contigo la alegría de celebrar mis

<span class="gold">XV Años</span>.

Tu presencia hará de este día un recuerdo aún más especial.

</p>

</div>

</section>

<section>

<h2 class="titulo">Mis Padres</h2>

<div class="card">

<p>

Ángel Eduardo Velázquez García

<br><br>

Yolanda Viviana Espinoza Leyva

</p>

</div>

</section>

<section>

<h2 class="titulo">Mis Padrinos</h2>

<div class="card">

<p>

Héctor Ricardo García Zavala

<br><br>

Zabdy Vanessa Pérez Leyva

</p>

</div>

</section>

<section>

<h2 class="titulo">Ceremonia Religiosa</h2>

<div class="card">

<p>

📅 1 de Agosto de 2026

<br><br>

⛪ Parroquia San Jorge

<br>

Secretaría de Recursos Hidráulicos

y Calle 24

Colonia San Jorge

<br><br>

🕕 6:00 PM

</p>

<br>

<a href="https://maps.app.goo.gl/otoboVU8MR5jkTrX8?g_st=aw"
target="_blank"
style="background:#FFD700;color:#4b0082;padding:15px 30px;border-radius:40px;text-decoration:none;font-weight:bold;">
Ver ubicación
</a>

</div>

</section>

<section>

<h2 class="titulo">Recepción</h2>

<div class="card">

<p>

📍 Granja de Eventos Los Cota

<br><br>

🕘 9:00 PM

</p>

</div>

</section>

<section>

<h2 class="titulo">Código de Vestimenta</h2>

<div class="card">

<p>

👔 Formal

</p>

</div>

</section>

<section>

<h2 class="titulo">Lluvia de Sobres</h2>

<div class="card">

<p>

🎁 El mejor regalo es tu presencia.

Si deseas obsequiarme un detalle,

agradeceré tu muestra de cariño en

<span class="gold">lluvia de sobres.</span>


</p>

</div>

</section>
iconsiconsaudioimages
