# Practica001-Mi-Blog
Programacion Hipermedial
Autor: Claudio Maldonado
Fecha: 08/04/2019

•	Se crea los archivos base de html de la estructura de la pagina
 
•	La pagina index contiene información ha cerca de los videojuegos así también como un video resaltando la historia de ellos. Cada articulo contiene fechas importantes dentro de la historia de ellos.

<section>
        <h2>Historia de los videojuegos</h2>
        <article>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/mWWp4tIjXCk"></iframe>
        </article>
        <article>
            <h3>Los inicios</h3>
            <p>Durante bastante tiempo ha sido complicado señalar cual fue el primer videojuego, principalmente debido a
                las múltiples definiciones de este que se han ido estableciendo, pero se puede considerar como primer
                videojuego el Nought and crosses, también llamado OXO, desarrollado por Alexander S.Douglas en 1952. El
                juego era una versión computerizada del tres en raya que se ejecutaba sobre la EDSAC y permitía
                enfrentar a un jugador humano contra la máquina.</p>
            <p>En 1958 William Higginbotham creó, sirviéndose de un programa para el cálculo de trayectorias y un
                osciloscopio, Tennis for Two (tenis para dos): un simulador de tenis de mesa para entretenimiento de los
                visitantes de la exposición Brookhaven National Laboratory.</p>
            <p>Este videojuego fue el primero en permitir el juego entre dos jugadores humanos. Cuatro años más tarde
                Steve Russell, un estudiante del Instituto de Tecnología de Massachussets, dedicó seis meses a crear un
                juego para computadora usando gráficos vectoriales: Spacewar.</p>
            <p>En este juego, dos jugadores controlaban la dirección y la velocidad de dos naves espaciales que luchaban
                entre ellas. El videojuego funcionaba sobre un PDP-1 y fue el primero en tener un cierto éxito, aunque
                apenas fue conocido fuera del ámbito universitario.</p>
        </article>
        <article>
            <h3>1970-1979: La eclosión de los videojuegos</h3>
            <p> Un hito importante en el inicio de los videojuegos tuvo lugar en 1971 cuando Nolan Bushnell comenzó a
                comercializar Computer Space, una versión de Space War, aunque otra versión recreativa de Space War como
                fue Galaxy War puede que se le adelantara a principios de los 70 en el campus de la universidad de
                Standford. </p>
            <p>La ascensión de los videojuegos llegó con la máquina recreativa Pong que es considerada la versión
                comercial del juego Tennis for Two de Higginbotham. El sistema fue diseñado por Al Alcom para Nolan
                Bushnell en la recién fundada Atari. </p>
            <p>El juego se presentó en 1972 y fue la piedra angular del videojuego como industria. Durante los años
                siguientes se implantaron numerosos avances técnicos en los videojuegos (destacando los
                microprocesadores y los chips de memoria). Aparecieron en los salones recreativos juegos como Space
                Invaders (Taito) o Asteroids (Atari).</p>
        </article>
        <article>
            <h3>1980-1989: La década de los 8 bits</h3>
            <p>A finales de los 80 comenzaron a aparecer las consolas de 16 bits como la Mega Drive de Sega y los
                microordenadores fueron lentamente sustituidos por las computadoras personales basadas en arquitecturas
                de IBM.</p>
            <p>En 1985 apareció Super Mario Bros, que supuso un punto de inflexión en el desarrollo de los juegos
                electrónicos, ya que la mayoría de los juegos anteriores sólo contenían unas pocas pantallas que se
                repetían en un bucle y el objetivo simplemente era hacer una alta puntuación. El juego desarrollado por
                Nintendo supuso un estallido de creatividad. Por primera vez teníamos un objetivo y un final en un
                videojuego. En los años posteriores otras compañías emularon su estilo de juego.</p>
        </article>
        <article>
            <h3>1990-1999: La revolución de las 3D</h3>
            <p>A principios de los años 90 las videoconsolas dieron un importante salto técnico gracias a la competición
                de la llamada "generación de 16 bits" compuesta por la Mega Drive, la Super Nintendo Entertainmet de
                Nintendo, la PC Engine de NEC, conocida como Turbografx en occidente y la CPS Changer de (Capcom).</p>
            <p>Esta generación supuso un importante aumento en la cantidad de jugadores y la introducción de tecnologías
                como el CD-ROM, una importante evolución dentro de los diferentes géneros de videojuegos, principalmente
                gracias a las nuevas capacidades técnicas.</p>
        </article>
        <article>
            <table border="1">
                <tr>
                    <td rowspan="2"><b>Juegos</b></td>
                    <td colspan="2"><b>Generacions</b></td>
                </tr>
                <tr>
                    <td><b>Primera Gen.</b></td>
                    <td><b>Segunda Gen.</b></td>
                </tr>
                <tr>
                    <td><b>Super Mario</b></td>
                    <td>Super Mario Bros.</td>
                    <td>Super Mario Bros 2</td>
                </tr>
                <tr>
                    <td><b>Sonic</b></td>
                    <td>Sonic Adventure DX: Director's Cut</td>
                    <td>Sonic Battle</td>
                </tr>
                <tr>
                    <td colspan="3">Estas son las primeras generaciones de los juegos.</td>
                </tr>
            </table>
        </article>
        <aside>
            <img src="imagenes/publi1.jpg" alt="Steam">
        </aside>
        <aside>
            <img src="imagenes/publi2.jpg" alt="EA">
        </aside>
    </section>
 
•	Para el logo de esta pagina se utiliza una imagen dentro de la etiqueta header.
 
 <header>
    <img src="imagenes/logo.jpg" alt="logo">
 </header>

•	Para el menú de navegación entre las diferentes paginas se utiliza una lista desordenada con un hipervínculo hacia las paginas referentes.
 
    <nav>
        <ul>
            <li><a href="index.html">Inicio</a></li>
            <li><a href="accion.html">Juegos de accion</a></li>
            <li><a href="mmorpg.html">Juegos MMORPG</a></li>
            <li><a href="terror.html">Juegos de terror</a></li>
            <li><a href="mobile.html">Juegos para mobile</a></li>
        </ul>
    </nav> 
 
•	La etiqueta footer contiene información personal de derechos de autor para esto se usa la etiqueta de hipervínculo mailto y tel para hacer referencia que es un email y un teléfono de contacto.

    <footer>
        <p>Claudio Maldonado</p>
        <p>Universidad Politecnica Salesiana</p>
        <a href="mailto:cmaldonadom3@est.ups.edu.ec">cmaldonadom3@est.ups.edu.ec</a><br />
        <a href="tel:+593978781341">+593978781341</a>
        <p>Todos los derechos reservados &copy; 2019</p>
    </footer>
 
•	Se crea la estructura básica del sitio de acuerdo al diagrama propuesto también se genera los menús de navegación para el acceso a las paginas a los otros archivos .html
  
•	Se edita el header con los ipervinculos para la nevegacion entre paginas y el footer con mi información como esta sección se debe repetir en todas las paginas se crea la misma estructura.
•	Siguiente la estructura de las instrucciones se crea la tabla con datos relevantes respecto a las primeras generaciones de los juegos mas populares.

        <article>
            <table border="1">
                <tr>
                    <td rowspan="2"><b>Juegos</b></td>
                    <td colspan="2"><b>Generacions</b></td>
                </tr>
                <tr>
                    <td><b>Primera Gen.</b></td>
                    <td><b>Segunda Gen.</b></td>
                </tr>
                <tr>
                    <td><b>Super Mario</b></td>
                    <td>Super Mario Bros.</td>
                    <td>Super Mario Bros 2</td>
                </tr>
                <tr>
                    <td><b>Sonic</b></td>
                    <td>Sonic Adventure DX: Director's Cut</td>
                    <td>Sonic Battle</td>
                </tr>
                <tr>
                    <td colspan="3">Estas son las primeras generaciones de los juegos.</td>
                </tr>
            </table>
        </article>

•	También se implementa la etiqueta iframe que  permite insertar o incrustar un documento HTML dentro de un documento HTML principal. 
Los iFrames admiten diversos atributos como "AllowTransparency", que deberemos establecer a "true", que permite una visualización de la página mucho más atractiva; ya que, el fondo del iframe va a ser transparente, dejando ver el fondo original del archivo HTML principal. Para lo cual, habrá que poner el parámetro background:transparent, en la definición CSS de body, en la página a cargar en el <iframesrc='paginaACargar.html'>. paginaACargar.html 
Implementando la etiqueta y poniendo como ruta un video de YouTube podemos implementar el video en nuestro sitio.
 
        <article>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/mWWp4tIjXCk"></iframe>
        </article>
 
•	Se crea artículos con información este articulo engloba una imagen y un párrafo como descripción de una breve reseña de cada videojuego:
También contiene una tabla con la descripción de los requisitos del sistema para poder ejecutar este juego.
 
        <article id="forniteMobile">
            <h2>Fortnite</h2>
            <img src="imagenes/fortnitem.jpg" alt="Fornite Mobile">
            <p>
                Fortnite Battle Royale es un videojuego gratuito perteneciente al género de Battle Royale desarrollado y
                publicado por Epic Games. Fue lanzado como un título con acceso anticipado para Microsoft Windows,
                macOS, PlayStation 4, Xbox One el 26 de septiembre de 2017, para iOS el 2 de abril de 2018, y para
                Android el 9 de agosto. Fue lanzado en la consola Nintendo Switch el 12 de junio de 2018.1​ Es un
                spin-off de Fortnite: Salvar el Mundo, un cooperativo juego de supervivencia con elementos de
                construcción.
            </p>
            <table border="1">
                <tr>
                    <td colspan="3"><b>Requisitos</b></td>
                </tr>
                <tr>
                    <td><b>Systema</b></td>
                    <td>Android 5.0 o superior </td>
                </tr>
                <tr>
                    <td><b>RAM</b></td>
                    <td>3GB</td>
                </tr>
                <tr>
                    <td><b>SO</b></td>
                    <td colspan="2">Android / IOS</td>
                </tr>
                <tr>
                    <td><b>Espacio libre</b></td>
                    <td colspan="3">2GB</td>
                </tr>
            </table>
        </article> 
 
•	Como se puede observar la etiqueta article engloba un titulo una imagen, una descripción y la tabla de requisitos, todos las paginas siguen la misma estructura con excepción de la pagina de index esta contiene información hacerca de la historia de los vidojuegos.

•	Para la navegación entre estos artículos se implementa un id para poder identificarlo y poner como un hipervínculo:
•	Luego se procede a crear un heder y una lista desordenada para poder acceder a estos ids
 El resultado de implementar este código se pude observar en la siguiente apartado.
 
        <header>
            <ul>
                <li><a href="#pubgMobile">PUBG Mobile </a></li>
                <li><a href="#forniteMobile">Fortnite</a></li>
                <li><a href="#VainGlory">VainGlory</a></li>
            </ul>
        </header> 
 
Al dar click en cualquiera de estos ítems nos llevara al articulo relacionado gracias a los ids que se implemento
