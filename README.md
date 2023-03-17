# Protcon

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1>Mi Página Web</h1>
      <nav>
        <ul>
          <li><a href="#productos">Productos</a></li>
          <li><a href="#servicios">Servicios</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section id="inicio">
        <h2>Bienvenidos</h2>
        <p>Texto de introducción a la página.</p>
      </section>

      <section id="productos">
        <h2>Productos</h2>
        <ul>
          <li>Producto 1</li>
          <li>Producto 2</li>
          <li>Producto 3</li>
        </ul>
      </section>

      <section id="servicios">
        <h2>Servicios</h2>
        <ul>
          <li>Servicio 1</li>
          <li>Servicio 2</li>
          <li>Servicio 3</li>
        </ul>
      </section>

      <section id="contacto">
        <h2>Contacto</h2>
        <form>
          <label for="nombre">Nombre:</label>
          <input type="text" id="nombre" name="nombre">

          <label for="email">Email:</label>
          <input type="email" id="email" name="email">

          <label for="mensaje">Mensaje:</label>
          <textarea id="mensaje" name="mensaje"></textarea>

          <input type="submit" value="Enviar">
        </form>
      </section>
    </main>

    <script src="app.js"></script>
  </body>
</html>
