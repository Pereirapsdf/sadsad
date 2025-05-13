body {
  font-family: Arial, sans-serif;
}

header {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
  background-color: #333;
  color: white;
}

.main-nav {
  display: flex;
  justify-content: center;
  width: 100%;
  background-color: #444;
}

.main-nav ul {
  display: flex;
  list-style: none;
}

.main-nav li {
  margin: 0 15px;
}

.main-nav a {
  color: white;
  text-decoration: none;
}

.hamburger-menu {
  display: none;
}

main {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 20px;
}

.noticia-principal {
  flex: 1 1 60%;
}

.noticia-principal img {
  width: 100%;
  height: auto;
}

.noticias-secundarias {
  flex: 1 1 35%;
}

.publicidad {
  flex: 1 1 100%;
  background-color: #f4f4f4;
  text-align: center;
  padding: 20px;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: white;
}

/* Media Queries */
@media (max-width: 768px) {
  .main-nav ul {
    display: none;
  }
  .hamburger-menu {
    display: block;
  }

  main {
    flex-direction: column;
  }

  .noticia-principal {
    flex: 1;
  }
}

@media (max-width: 480px) {
  header {
    padding: 0.5rem;
  }

  .noticia-principal h2 {
    font-size: 1.5rem;
  }
}
