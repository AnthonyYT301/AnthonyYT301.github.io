# AnthonyYT301.github.io

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurante Sabor Delicioso</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Restaurante Sabor Delicioso</h1>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="menu.html">Menú</a></li>
                <li><a href="ordenar.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <img src="imagen_principal.jpg" alt="Imagen del Restaurante">
        <div class="descripcion">
            <p>Bienvenidos a Restaurante Sabor Delicioso, donde cada plato es una obra de arte culinaria.</p>
        </div>
        <div class="oferta-del-dia">
            <h2>Oferta del Día</h2>
            <img src="oferta_dia.jpg" alt="Oferta del Día">
            <p>Disfruta de nuestro especial del día: Paella de Mariscos por solo $12.99</p>
        </div>
    </section>
    
    <footer>
        <p>Teléfonos: (123) 456-7890</p>
        <p>Dirección: Calle Principal 123, Ciudad, País</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú - Restaurante Sabor Delicioso</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="menu">
        <h2>Menú</h2>
        <img src="imagen_menu.jpg" alt="Imagen del Menú">
        
        <h3>Entradas</h3>
        <table>
            <tr>
                <th>Producto</th>
                <th>Descripción</th>
                <th>Precio</th>
            </tr>
            <tr>
                <td>Ensalada César</td>
                <td>Lechuga fresca con aderezo César, crutones y parmesano.</td>
                <td>$5.99</td>
            </tr>
            <tr>
                <td>Sopa de Tomate</td>
                <td>Deliciosa sopa cremosa de tomates frescos.</td>
                <td>$4.99</td>
            </tr>
        </table>
        
        <h3>Plato Fuerte</h3>
        <table>
            <tr>
                <th>Producto</th>
                <th>Descripción</th>
                <th>Precio</th>
            </tr>
            <tr>
                <td>Filete Mignon</td>
                <td>Filete de res a la parrilla acompañado de puré de papas.</td>
                <td>$15.99</td>
            </tr>
            <tr>
                <td>Paella de Mariscos</td>
                <td>Arroz con mariscos frescos y especias.</td>
                <td>$12.99</td>
            </tr>
        </table>
        
        <h3>Postres / Bebidas</h3>
        <table>
            <tr>
                <th>Producto</th>
                <th>Descripción</th>
                <th>Precio</th>
            </tr>
            <tr>
                <td>Tarta de Queso</td>
                <td>Deliciosa tarta de queso con mermelada de frutas.</td>
                <td>$4.99</td>
            </tr>
            <tr>
                <td>Café</td>
                <td>Café recién molido y preparado.</td>
                <td>$2.50</td>
            </tr>
        </table>
    </section>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ordenar - Restaurante Sabor Delicioso</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="contacto">
        <h2>Ordenar</h2>
        <form action="mailto:info@restaurante.com" method="post" enctype="text/plain">
            <label for="nombres">Nombres:</label>
            <input type="text" id="nombres" name="nombres" required>
            
            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>
            
            <p>Información del pedido:</p>
            <input type="radio" id="delivery" name="tipo_pedido" value="Delivery" required>
            <label for="delivery">Delivery</label>
            
            <input type="radio" id="recoger" name="tipo_pedido" value="Recoger" required>
            <label for="recoger">Recoger</label>
            
            <p>Selecciona los artículos:</p>
            <input type="checkbox" id="ensalada_cesar" name="articulos" value="Ensalada César">
            <label for="ensalada_cesar">Ensalada César ($5.99)</label><br>
            
            <input type="checkbox" id="sopa_tomate" name="articulos" value="Sopa de Tomate">
            <label for="sopa_tomate">Sopa de Tomate ($4.99)</label><br>
            
            <input type="checkbox" id="filete_mignon" name="articulos" value="Filete Mignon">
            <label for="filete_mignon">Filete Mignon ($15.99)</label><br>
            
            <input type="checkbox" id="paella_mariscos" name="articulos" value="Paella de Mariscos">
            <label for="paella_mariscos">Paella de Mariscos ($12.99)</label><br>
            
            <input type="checkbox" id="tarta_queso" name="articulos" value="Tarta de Queso">
            <label for="tarta_queso">Tarta de Queso ($4.99)</label><br>
            
            <input type="checkbox" id="cafe" name="articulos" value="Café">
            <label for="cafe">Café ($2.50)</label><br>
            
            <label for="observaciones">Observaciones:</label>
            <textarea id="observaciones" name="observaciones" rows="4" cols="50"></textarea>
            
            <button type="submit">Enviar Pedido</button>
        </form>
    </section>
</body>
</
