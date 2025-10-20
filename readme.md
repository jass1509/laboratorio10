* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}

body {
  background-color: #f5f7fa;
  color: #333;
  line-height: 1.6;
}

header {
  background: #004aad;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

header h1 {
  font-size: 1.8rem;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}

nav a:hover,
nav a.activo {
  text-decoration: underline;
}

.hero {
  background: linear-gradient(to right, #004aad, #007bff);
  color: #fff;
  text-align: center;
  padding: 4rem 1rem;
}

.btn {
  display: inline-block;
  background: #ffb800;
  color: #000;
  padding: 0.7rem 1.5rem;
  margin-top: 1rem;
  border-radius: 5px;
  text-decoration: none;
  transition: background 0.3s;
}

.btn:hover {
  background: #ffcf33;
}

main {
  padding: 2rem;
  max-width: 1000px;
  margin: auto;
}

.servicios,
.portafolio {
  display: grid;
  gap: 1.5rem;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

.servicios article,
.portafolio article {
  background: #fff;
  border-radius: 10px;
  padding: 1rem;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  text-align: center;
}

footer {
  background: #004aad;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}

.contacto-form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 500px;
  margin: auto;
}

.contacto-form input,
.contacto-form textarea {
  padding: 0.7rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

@media (max-width: 600px) {
  header h1 {
    font-size: 1.4rem;
  }

  .hero {
    padding: 2rem 1rem;
  }
}
