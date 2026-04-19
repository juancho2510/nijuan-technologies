<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NIJUAN TECHNOLOGIES</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #0a0a0a;
    color: white;
}

header {
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(180deg, #000000, #111111);
}

header h1 {
    color: gold;
    font-size: 40px;
    margin-bottom: 10px;
}

header p {
    color: #ccc;
    font-size: 18px;
}

.section {
    padding: 60px 20px;
    text-align: center;
}

.section h2 {
    color: gold;
    margin-bottom: 20px;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.card {
    background: #111;
    border: 1px solid gold;
    border-radius: 10px;
    padding: 20px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    background: #1a1a1a;
}

footer {
    text-align: center;
    padding: 30px;
    background: black;
    color: #aaa;
}
</style>

</head>

<body>

<header>
      <img src="logo.png" class="logo">
    <h1>NIJUAN TECHNOLOGIES</h1>
    <p>Hechos para servir; comprometidos a asistir</p>
</header>

<section class="section">
    <h2>Sobre Nosotros</h2>
    <p>Desarrollamos soluciones tecnológicas enfocadas en optimizar procesos y mejorar la eficiencia de las empresas mediante software moderno y confiable.</p>
</section>

<section class="section">
    <h2>Servicios</h2>
    <div class="services">
        <div class="card">Desarrollo de software a medida</div>
        <div class="card">Aplicaciones móviles</div>
        <div class="card">Aplicaciones web</div>
        <div class="card">Automatización de procesos</div>
        <div class="card">Integración de sistemas</div>
        <div class="card">Soporte y mantenimiento</div>
    </div>
</section>

<section class="section">
    <h2>Contacto</h2>
    <p>Email: contacto@nijuan.com</p>
    <p>Tel: 3229109730</p>
</section>

<footer>
    <p>© 2026 NIJUAN TECHNOLOGIES - Todos los derechos reservados</p>
</footer>

</body>
</html>
