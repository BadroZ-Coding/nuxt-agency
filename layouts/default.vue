<template>
  <div>
    <nav>
      <ul>
        <li><nuxt-link to="/">Accueil</nuxt-link></li>
        <li><nuxt-link to="/services">Services</nuxt-link></li>
        <li><nuxt-link to="/contact">Contact</nuxt-link></li>
      </ul>
    </nav>
    <header>
      <h1>Pulsar Agency</h1>
    </header>
    <main>
      <nuxt/>
    </main>
    <footer>
      <p>&copy; 2024 Pulsar Agency</p>
    </footer>
  </div>
</template>

<style>
/* Style pour la barre de navigation */
nav {
  background-color: #333;
  padding: 10px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

/* Style pour l'en-tête */
header {
  background-color: #f2f2f2;
  padding: 20px;
  text-align: center;
}

/* Style pour le pied de page */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

</style>
