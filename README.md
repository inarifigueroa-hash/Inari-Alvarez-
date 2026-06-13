<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>🌎 Cambio Climático - Gamer</title>

<style>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(135deg, #0f0f1a, #1a0033);
    color: white;
}

/* EFECTO NEÓN */
h1, h2 {
    text-align: center;
    text-shadow: 0 0 10px #00ffff, 0 0 20px #8a2be2;
}

/* HEADER */
header {
    padding: 30px;
    background: rgba(0,0,0,0.6);
    backdrop-filter: blur(10px);
}

/* NAV */
nav {
    display: flex;
    justify-content: center;
    background: #000;
}

nav a {
    color: white;
    padding: 15px 20px;
    text-decoration: none;
    transition: 0.3s;
}

nav a:hover {
    background: #00ffff;
    color: black;
    box-shadow: 0 0 10px #00ffff;
}

/* SECCIONES */
section {
    margin: 20px;
    padding: 20px;
    border-radius: 15px;
    background: rgba(255,255,255,0.05);
    box-shadow: 0 0 15px rgba(0,255,255,0.2);
    animation: fadeIn 1s ease-in-out;
}

/* ANIMACIÓN */
@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}

/* TARJETAS */
.card {
    margin: 15px 0;
    padding: 15px;
    border-left: 5px solid #00ffff;
    background: rgba(0,0,0,0.4);
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 15px #00ffff;
}

/* IMAGEN */
img {
    width: 100%;
    border-radius: 10px;
    transition: 0.5s;
}

img:hover {
    transform: scale(1.05);
}

/* BOTÓN */
button {
    background: #8a2be2;
    border: none;
    padding: 10px 20px;
    color: white;
    cursor: pointer;
    border-radius: 10px;
    transition: 0.3s;
}

button:hover {
    background: #00ffff;
    color: black;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 15px;
    background: black;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>🌎 CAMBIO CLIMÁTICO</h1>
    <p style="text-align:center;">Modo Gamer Activado 🎮</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#tema">Tema</a>
    <a href="#desarrollo">Desarrollo</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
    <h2>📌 Inicio</h2>
    <p>Bienvenido a una versión gamer del cambio climático 😎</p>
</section>

<section id="tema">
    <h2>🧠 Tema Principal</h2>
    <p>El cambio climático es el aumento de temperatura global causado por actividades humanas.</p>
</section>

<section id="desarrollo">
    <h2>🔥 Desarrollo</h2>

    <div class="card">
        <h3>🎯 Causas</h3>
        <p>Contaminación, deforestación y uso de combustibles fósiles.</p>
    </div>

    <div class="card">
        <h3>🌊 Consecuencias</h3>
        <p>Derretimiento de hielos, cambios extremos y aumento del mar.</p>
    </div>

    <div class="card">
        <h3>🌱 Soluciones</h3>
        <p>Reciclar, usar energías limpias y cuidar el planeta.</p>
    </div>

    <h3>📷 Imagen</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Global_Warming_Map.jpg">
    
    <br><br>
    <button onclick="alert('¡Cuida el planeta 🌎🔥!')">Haz clic gamer 😎</button>
</section>

<section id="contacto">
    <h2>📩 6231011095</h2>
    <p>Nombre: Inari Emanuel Álvarez Figueroa </p>
    <p>Materia: Cultura digital </p>
    <p>Correo: Inarifigueroa@gmail.com</p>
</section>

<footer>
    <p>💻 Proyecto Escolar 2026</p>
</footer>

</body>
</html>
