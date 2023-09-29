# gamer
/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.destaque {
    text-align: center;
    margin: 2rem 0;
}

.destaque img {
    max-width: 100%;
}

.jogos {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    margin: 2rem 0;
}

.jogos article {
    background-color: #fff;
    padding: 1rem;
    margin: 1rem;
    text-align: center;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
}

.jogos img {
    max-width: 100%;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
}

/* Estilos responsivos */
@media (max-width: 768px) {
    .jogos article {
        width: 45%;
    }
}
