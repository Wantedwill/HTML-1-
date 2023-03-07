# HTML-1-
<!DOCTYPE html>
<html lang="pt-br">
 <head>
  <meta charset="UTF-8">
   <title> Exemplo de página HTML </title>
   <style>
body {
  font-family: Right Slab, Book;
  font-size: 16px;
  margin: 0;
  padding: 0;
}

header {
  background-color: #6AADA6;
  color: #FFF;
  padding: 10px;
}

header h1 {
  color: #FF9A6B
  margin: 0;
}

nav ul {
  margin: 0;
  padding: 0;
  list-style-type: none;
}

nav li {
  display: inline-block;
  margin-right: 20px;
}

nav a {
  color: #FFF;
  text-decoration: none;
}

nav a:hover {
  text-decoration: underline;
  text-decoration-color: #FF9A6B;
  text-decoration-line: underline;
  text-decoration-thickness: 2px;
}

section {
  padding: 20px;
}

section h2 {
  margin-top: 0;
}

footer {
  background-color: #6AADA6;
  color: #FFF;
  padding: 10px;
  text-align: center;
}
   </style>
  </head>
  <body>
    <header>
      <h1> nome: william rosa </h1>
      <nav> 
        <ul>
          <li><a href="#"> Início </a></li>
          <li><a href="#"> Sobre </a></li>
          <li><a href="#"> Contatos </a></li>
        </ul>  
      </nav>
    </header>
    <main>
      <section>
        <h2> lazer: jogos no pc </h2>
        <p> eu jogo varios tipos de jogo no pc </p>
      </section>
      <section>
        <h2> dia dia  </h2>
        <p> treinar na academia </p>
      </section>
    </main>
    <footer>
      <p> &copy; 2023 Exemplo de HTML. </p>
    </footer>
  </body>
</html>
