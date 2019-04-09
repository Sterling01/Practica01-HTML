# Practica01-MiBlog
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <meta name="keywords" content="automovilismo, formula 1, nascar, dakar" />
        <title>GX Motor</title>
    </head>
    <body>
        <header id="header">
            <a href="index.html"><img src="images/header.jpg" alt="GX Motor"></a>
            <nav>
                <ul>
                    <li><a href="index.html">Pagina Inicial</a></li>
                    <li><a href="formula1.html">Formula 1</a></li>
                    <li><a href="nascar.html">Nascar</a></li>
                    <li><a href="dakar.html">Dakar</a></li>
                    <li><a href="motogp.html">Moto GP</a></li>
                    <li><a href="acercade.html">Acerca de</a></li>           
                </ul>
            </nav>
        </header>
        <nav>
            <ul>
                <li><a href="index.html#header">Inicio</a></li>
                <li><a href="index.html#section1">Seccion 1</a></li>
                <li><a href="index.html#article">Articulo</a></li>
                <li><a href="index.html#section2">Seccion 2</a></li>
                <li><a href="index.html#footer">Informacion</a></li>       
            </ul>
        </nav>
        <section id="section1">   
            <h1>Section 1</h1>
            <article id="article">
                <table border="1">
                    <caption>Titulo de tabla</caption>
                    <tr>
                        <th rowspan="2">Tabla Avanzada</th>
                        <th colspan="2">Cabecera Multiples Columnas</th>
                    </tr>
                    <tr>
                        <th>Primera Col. Cab.</th>
                        <th>Segunda Col. Cab.</th>
                    </tr>
                    <tr>
                        <th>Fila 1</th>
                        <td>Fila 1 Columna 1</td>
                        <td>Fila 1 Columna 2</td>
                    </tr>
                    <tr>
                        <th>Fila 2</th>
                        <td>Fila 2 Columna 1</td>
                        <td>Fila 2 Columna 2</td>
                    </tr>
                    <tr>
                        <td colspan="3">Pie de tabla.</td>
                    </tr>
                </table>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/0VjWY--QdMA" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                <!--Lista ordenada-->
                <ol>
                    <li value="1">Autralia</li>
                    <li>Bahrein</li>
                    <li>China</li>
                    <li>Azerbaiyan</li>
                    <li>España</li>             
                </ol>
                <!--Lista desordenada-->
                <ul>
                    <li>Elemento 1 </li>
                    <li>Elemento 2 </li>
	                <li>Elemento 3 </li>
                    <li>Elemento 4 </li>
                    <li>Elemento 5 </li>
                </ul>
            </article>
            <aside>
                <img src="images/leclerc.jpg" alt="">
            </aside>            
            <aside>
                <img src="images/williams.jpg" alt="">
            </aside>   
        </section>        
        <section id="section2"> 
            <h1>Section 2</h1>
            <p>El <strong>automovilismo</strong> es uno de los espectáculos más populares del mundo. En la mayoría de las modalidades, los automóviles deben completar un recorrido en el menor tiempo posible, o bien recorrer un circuito la mayor cantidad de veces en un tiempo fijo. Existen otras disciplinas que tienen objetivos distintos, por ejemplo el drifting, donde los pilotos deben realizar derrapes espectaculares. El automovilismo es uno de los espectáculos más populares del mundo y algunas competiciones, como por ejemplo la <em>Fórmula 1</em>, cuentan con más seguidores que muchos otros deportes. Así mismo es el que mueve más dinero, involucrando a un gran número de empresas, fabricantes, deportistas, ingenieros y patrocinantes.<br />
            Los ingenieros desarrollan las últimas tecnologías en motores, aerodinámica, suspensión y neumáticos para lograr el máximo rendimiento; estos avances han beneficiado a la industria automotriz, con los neumáticos radiales y el turbocompresor, así como otros adelantos.</p>
            <aside>
                <img src="images/motor.jpg" alt="">
            </aside>
        </section>       
        <footer id="footer">
            <p>Stalin Santiago Figueroa Sacoto - Universidad Politecnica Salesiana</p>
            <p>Telefono: <a href="tel:+593967515856">0967515856</a></p>
            <p>Email: <a href="mailto:sfigueroas1@est.ups.edu.ec">sfigueroas1@est.ups.edu.ec</a></p>
            <p>&copy;Todos los derechos reservados</p>
            <p>Last updated at: <time datetime="2019-04-07T16:25">April 7 2019 at 4:25 p.m.</time></p>
        </footer>        
    </body>    
</html>
