<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página de Videojuegos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('fondo.jpeg') no-repeat center center fixed; 
            background-size: cover;
            color: #333;
        }
        header {
            background: rgba(44, 62, 80, 0.8);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: rgba(52, 73, 94, 0.8);
            padding: 10px;
        }
        nav a {
            color: #f39c12;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        section {
            background: rgba(255, 255, 255, 0.6);
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        img, video {
            max-width: 100%;
            height: auto;
        }
        .small-video {
            max-width: 600px; /* Ajusta este valor según lo que necesites */
            height: auto;
            margin: 0 auto; /* Centra el video */
            display: block;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: rgba(44, 62, 80, 0.8);
            color: white;
            width: 100%;
        }
        .download-link {
            display: inline-block;
            padding: 10px 20px;
            background-color: #e74c3c;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            margin-top: 10px;
        }
        .download-link:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página de Videojuegos</h1>
    </header>
    <nav>
        <a href="#favorites">Mis Juegos Favoritos</a>
        <a href="#projects">Proyectos de Videojuegos</a>
        <a href="#tutorial">Tutorial de Descarga</a>
        <a href="#contact">Contacto</a>
        <a href="#comentarios">Comentarios</a>
    </nav>
    <main>
        <section id="favorites">
            <h2>Juegos gratis para que no pagues xd</h2>
            <ul>
                <img src="Halo.jpeg" alt="Halo: Combat Evolved">
                <li><strong>Halo: Combat Evolved</strong> - Un mundo de acción y diversión en el online.</li>
                <a href="https://www.mediafire.com/file/94tjp1cpa5jc1yy/Halo+CE+-+Neo+Games.rar/file" target="_blank" class="download-link">Descargar desde MediaFire</a>
                <li><strong>Need for Speed Most Wanted hd</strong> - Contraseña: elenemigos.com.</li>
            </ul>
            <img src="need for speed most wanted.jpeg" alt="Need for Speed Most Wanted">
            <a href="https://www.mediafire.com/file/u46iv5di75ggj9l/Need+for+Speed+MW" target="_blank" class="download-link">Descargar desde MediaFire</a>
            <a href="https://www.mediafire.com/file/c13a1tgbre7b5u6/NFS+Most+Wanted+by+Ranchoso92.rar/file" target="_blank" class="download-link">del instalador sin codigo</a>
        </section>
        <section id="projects">
            <h2>Proyectos de Videojuegos</h2>
            <p>Aquí hay algunos de mis proyectos relacionados con videojuegos:</p>
            <ul>
                <li><strong>Proyecto 1:</strong> Un juego de plataformas en 2D.</li>
                <li><strong>Proyecto 2:</strong> Un juego de rol basado en la fantasía.</li>
                <li><strong>Proyecto 3:</strong> Un juego de estrategia por turnos.</li>
            </ul>
        </section>
        <section id="tutorial">
            <h2>Tutorial de Descarga</h2>
            <p>Sigue estos pasos para descargar el archivo correctamente:</p>
            <ol>
                <li>Haz clic en el botón de descarga proporcionado.</li>
                <li>Una vez descargado, abre el archivo comprimido (si es necesario) en tu dispositivo.</li>
                <li>Realiza la instalación o sigue las instrucciones del archivo.</li>
                <li>¡Listo! Ahora podrás disfrutar del juego.</li>
            </ol>
        </section>
        <section id="video">
            <h2>Video Tutorial de Halo</h2>
            <p>A continuación, te dejamos un video tutorial sobre cómo instalar y jugar los videojuegos.</p>
            <video controls class="small-video">
                <source src="tutohalo.mp4" type="video/mp4">
            </video>
        </section>
        <section id="video">
            <h2>Video Tutorial de Need for Speed</h2>
            <p>A continuación, te dejamos un video tutorial sobre cómo instalar y jugar los videojuegos.</p>
            <video controls class="small-video">
                <source src="tutoneed.mp4" type="video/mp4">
            </video>
             </section>
        <section id="video">
            <h2>Video Tutorial de Need for Speed</h2>
            <p>A continuación, te dejamos un video tutorial sobre cómo instalar y jugar los videojuegos.</p>
            <video controls class="small-video">
                <source src="tutrospeed.mp4" type="video/mp4">
            </video>
        </section>
        <section id="contact">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través de mi correo electrónico: moralesjimy29@gmail.com</p>
        </section>
        <section id="comentarios">
            <h2>Deja tu Comentario para agregar juegos o aplicacion</h2>
            <p>es para apoyar ese proyecto. ¡Déjanos un comentario!</p>
            <form action="https://formspree.io/f/xpwzrkdr" method="POST">
                <label for="name">Nombre:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="comment">Comentario:</label><br>
                <textarea id="comment" name="comment" rows="4" cols="50" required></textarea><br><br>

                <button type="submit">Enviar Comentario para ayudar causa</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Mi Página de Videojuegos</p>
    </footer>
</body>
</html>
