*{
    margin: 0;
    padding: 0;
    text-decoration: none;
    list-style: none;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
   
}

/*==== Menu Barra Navegação ====*/
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding-top: 30px;
    padding-bottom: 10px;
    background: black;
    backdrop-filter: blur (10px);
    display: flex;
    align-items: center;
    z-index: 100;
}

.logo {
    font-size: 25px;
    color: teal;
    font-weight: 800;
    transition: 0.3s ease;
}

.logo:hover {
    transform: scale(1.1);
}

.cor_logo {
    color: teal;
}

.navbar {
    background-color: black; /*==== Menu Barra Navegação ====*/
}

.navbar a {
    font-size: 20px;
    color: white;
    font-weight: 500;
    margin: 0 20px;
    border-bottom: 3px solid transparent;
    transition: 0.3s ease;
    display: inline-block;
}

.navbar a:hover, .navbar a.active {
    color: darkslategray;
  transform: scale(1.1);
}

/* ==== Footer ====*/
.footer {
    position: relative;
    bottom: 0;
    width: 100%;
    padding: 40px 0;
}

.footer .social {
    text-align: right;
    padding-bottom: 25px;
    color: white;
}

.footer .social a {
    font-size: 25px;
    color: white;
    width: 40px;
    height: 40px;
    line-height: 38px;
    display: inline-block;
    text-align: center;
    border-radius: 50%;
    margin: 0 8px;
    transition: 0.3s ease;
}

.footer .social a:hover {
    border: 3px solid white;
    transform: scale(1.2) translateY(-10px);
}

/* ==== Section ====*/

.historia {
   
}
    
.servicos {
    width: 400px;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
}

h2 {
    font-size: 35px;
    color: white;
    text-align: center;
    align-items: center;
}

h2:hover {
    transform: scale(1.1);
    color: teal;
}

.promo {
    color: aliceblue;
    font-size: 18px;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
    background-image: url(img/paredeescura.jpg);
    width: 100%;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.agend {
    width: 100%;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
    background-color: black;
    
}

.blog {
    width: 100%;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
    background-color: black;
}

.contato {
    color: aliceblue;
    width: 100%;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
    background-color: rgb(29, 28, 28);
}

.contato:hover {
    color:teal;
    transform: scale(1.1);
}

.equipe {
    color: aliceblue;
    font-size: 18px;
    text-align: center;
    align-items: center;
    padding: 12% 8%;
    gap: 10em;
    background-image: url(img/parede.comlampadas.jpg);
    width: 100%;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.grid-container {
    display: grid;
    /*grid-template-columns geram 3 colunas iguais*/
    grid-template-columns: repeat(3, 1fr);
    gap:100px; /* gera um espaçamento entre imagens*/
}


