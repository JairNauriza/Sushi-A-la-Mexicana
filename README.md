<!DOCTYPE html>
<html lang="es">
<head>
    <title>Sushi a la Mexicana</title>
    <link rel="stylesheet" href="index.css">
</head>    
<body>
    <header>
    <hr>
        <h1>Sushi a la Mexicana</h1>
        <h2>Un concepto de Sushi diferente, <br> mas mexicano❤︎</h2>
    <hr>

        <div class"container">
            <nav>
                <a href="#">Introduccion</a>
                <a href="#">Menu</a>
                <a href="#">Contacto</a>
                <a href="#">¿Quienes somos?</a>
            </nav>
        </div>        
    </header>
    <hr>

    <section id="hero">
    <hr>
        <h3>El mejor Sushi de Acuña</h3>
            <button>Ordena Ya</button>
    <hr>
    </section>
    <hr>

    <selection id="El-mejor">
        <div class="container">
    
        <div class="img container"></div>
        <p>No pierdas la oportunidad de probar del mejor</p>
        <p>En Sushi a la mexicana nos proponemos dar la mejor calidad <br>en nuestros productos con los ingredientes mas frescos y de la mejor calidad</p>
        </div>
    <hr>
    </selection>

    <hr>
    <section id="Caracteristicas">
    <div class="container">
        <ul>
            <li>🍣Mas rico</li>
            <li>🍣Mas barato</li>
            <li>🍣La mejor calidad en productos</li>
        </ul>
    </div>
    </section>
    <hr>

    <section id="Quienes-somos">

    <div class="container">
        <h2>Shushi a la Mexicana</h2>
        <p>Somos un pequeño negocio tratando de llegar a la grandesa, conformado 
        por una  pequeña <br> familia, poniendo toda su atencion y dedicacion para poder cumplir el sueño <br>
        de una gran mujer</p>

    </div>
        <hr>
    </section>

    <footer>
        <div class="container">
            <p>&copy; Sushi a la mexicana 2024</p>
        </div>


    </footer>




</body>
</html>

*{
    box-sizing: border-box;
}

body{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: 0;
}

h1{font-size: 3.5em;}
h2{font-size: 2.0em;}
h3{font-size: 2em;}
p{font-size: 1.25em;}
ul{list-style: none;}
li{font-size: 1.25em;}

button{
font-size: 1.20em;
font-weight: bold;
padding: 2px 10px;
border-radius: 15px;
border: 2px solid rgba(0,0,0,0.5);
box-shadow: 2px 2px 10px rgba(0,0,0,0.5);
color: rgb(11, 14, 12);
background-color: yellow(55, 15, 216);
}

button:hover{
    background-color: rgb(139, 25, 231);
}

.container{
    max-width: 1400px;
    margin: auto;
}

header{
    background-color: rgb(210, 210, 3); 
    background-image: url(media/logo.png);
    background-repeat: no-repeat;
    background-size: 900px;
    background-position: right;
}

header .container{
    display: flex;
    flex-direction: column;
    align-items: center;
}

header nav{
    display: flex;
    flex-direction: column;
    text-align: center;
    padding: bottom 25px;
    font-size: 25px;
}

header a{
    padding: 5px 12px;
    text-decoration: none;
    font-weight: bold;
    color: black;
    background-color: rgb(245,245,245);
}

header a:hover{
    color: blue;
}


#hero{
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    flex-direction: column;
    height: 99vh;
    color: black;
    background-image: url(media/logo3.png);
    background-repeat: no-repeat;
    background-size: 1500px;
    background-position: center center;
    background-color: rgb(245, 245, 245); 
}

#hero h3{
    color: black;
}

#El-mejor{
    color: black;
}

#El-mejor .container{
    display: flex;
    align-items: left center;
    flex-direction: column-reverse;
    height: 50vh;
    color: black;
    background-image: url(media/bola.jpg);
    background-repeat: no-repeat;
    background-size: 400px;
    background-position:right;
    background-color: rgb(245, 245, 245);  
    
}

#Caracteristicas .container{
    text-align: center;
    padding: 200px 12px;
    background-image: url(media/rollos.jpg);
    background-repeat: no-repeat;
    background-size: 400px;
    background-position: left;
    background-color: rgb(245, 245, 245);  
}

#Caracteristicas li{
    margin: 16px 0px;
    font-weight: bold;
}

footer{
    background-color: rgb(230, 230, 230);
}

footer p{
    margin: 0;
    color: black;
}

footer .container{
    height: 200px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

#Quienes-somos{
    color: black;
}

#Quienes-somos .container{
    text-align: center;
    padding: 20px 12px;
    background-color: rgb(245, 245, 245); 
}

#Quienes-somos h2{
    color: rgb(156, 156, 26);
}

@media (min-width: 720px){
    header .container{
        flex-direction: row;
       justify-content: space-between;
    }
    header nav{
        flex-direction: row;
        padding-bottom: 0;
    }
}

