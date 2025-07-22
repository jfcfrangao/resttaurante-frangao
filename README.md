/* Reset simples */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: sans-serif;
  line-height: 1.6;
  color: #333;
}
/* Container centralizado */
.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 2rem 0;
}
/* Navbar */
.navbar {
  background: #c0392b;
  color: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
}
.navbar .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.logo {
  font-size: 1.5rem;
}
.nav-menu a {
  color: #fff;
  margin-left: 1rem;
  text-decoration: none;
}
.nav-toggle {
  display: none;
  background: none;
  border: none;
  font-size: 1.5rem;
  color: #fff;
}
/* Hero */
.hero {
  background: url('https://source.unsplash.com/1200x600/?restaurant,food') no-repeat center/cover;
  color: #fff;
  text-align: center;
  padding: 6rem 0;
}
.hero .btn {
  background: #e74c3c;
  color: #fff;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  border-radius: 4px;
}
/* Seções */
.section {
  padding: 4rem 0;
}
.bg-light {
  background: #f4f4f4;
}
/* Grid para menu */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
  gap: 1.5rem;
}
.card {
  background: #fff;
  padding: 1rem;
  border-radius: 4px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
.card h3 {
  margin-bottom: 0.5rem;
}
/* Formulário de reservas */
.form {
  max-width: 500px;
  margin: auto;
}
.form-group {
  margin-bottom: 1rem;
}
.form-group label {
  display: block;
  margin-bottom: 0.25rem;
}
.form-group input {
  width: 100%;
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}
.form-msg {
  margin-top: 1rem;
  font-weight: bold;
}
/* Footer */
.footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
}
/* Responsive menu */
@media (max-width: 768px) {
  .nav-menu {
    display: none;
    flex-direction: column;
    background: #c0392b;
  }
  .nav-menu a {
    padding: 1rem;
    border-top: 1px solid rgba(255,255,255,0.2);
  }
  .nav-toggle {
    display: block;
  }
  .nav-menu.show {
    display: flex;
  }
}
