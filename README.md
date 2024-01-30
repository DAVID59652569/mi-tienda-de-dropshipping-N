<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Tienda de Dropshipping</title>
    <link rel="stylesheet" href="styles.css"> <!-- Enlazar tu archivo de estilos CSS -->
</head>
<body>
    <header>
        <h1>Tu Tienda de Dropshipping</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <div class="hero">
            <h2>Bienvenido a nuestra Tienda de Dropshipping</h2>
            <p>Encuentra los mejores productos y precios increíbles</p>
            <a href="#productos" class="btn">Ver Productos</a>
        </div>
    </section>

    <section id="productos">
        <div class="container">
            <h2>Nuestros Productos</h2>
            <div class="product">
                <img src="producto1.jpg" alt="Producto 1">
                <h3>Producto 1</h3>
                <p>Descripción del producto 1.</p>
                <span class="price">$XX.XX</span>
                <a href="#" class="btn">Comprar Ahora</a>
            </div>
            <div class="product">
                <img src="producto2.jpg" alt="Producto 2">
                <h3>Producto 2</h3>
                <p>Descripción del producto 2.</p>
                <span class="price">$XX.XX</span>
                <a href="#" class="btn">Comprar Ahora</a>
            </div>
            <!-- Repite esta estructura para más productos -->
        </div>
    </section>

    <section id="nosotros">
        <div class="container">
            <h2>Sobre Nosotros</h2>
            <p>Descripción de tu tienda y tu equipo.</p>
        </div>
    </section>

    <section id="contacto">
        <div class="container">
            <h2>Contacto</h2>
            <p>Información de contacto y formulario de consulta.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Tu Tienda de Dropshipping. Todos los derechos reservados.</p>
        </div>
    </footer>

</body>
</html>

/* Estilos generales */
body {
    font-family: 'IBM', sans-serif; /* Fuente IBM */
    margin: 0;
    padding: 0;
    background-color: #f2f2f2; /* Gris claro */
    color: #333; /* Negro */
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Estilos del encabezado */
header {
    background-color: #333; /* Negro */
    color: #fff; /* Blanco */
    padding: 20px 0;
}

header h1 {
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff; /* Blanco */
    text-decoration: none;
}

/* Estilos del hero */
.hero {
    text-align: center;
    padding: 100px 0;
}

.hero h2 {
    margin-bottom: 20px;
}

.hero p {
    margin-bottom: 40px;
}

/* Estilos de la sección de productos */
#productos {
    background-color: #fff; /* Blanco */
    padding: 80px 0;
}

.product {
    text-align: center;
    margin-bottom: 40px;
}

.product img {
    max-width: 100%;
}

.product h3 {
    margin-top: 20px;
}

.product .price {
    display: block;
    font-weight: bold;
    margin-top: 10px;
}

/* Estilos del footer */
footer {
    background-color: #333; /* Negro */
    color: #fff; /* Blanco */
    text-align: center;
    padding: 20px 0;
}
