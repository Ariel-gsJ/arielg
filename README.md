<html>

<head></head>

<title>app para saber como afecta la Ia en la sociedad</title>



<style>/* Estilo general y fondo */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Poppins", sans-serif;
  background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
  color: #333;
  min-height: 100vh;
}

/* Barra de navegación */
nav {
  display: flex;
  justify-content: center;
  gap: 2rem;
  background: linear-gradient(to right, #00c6ff, #0072ff);
  padding: 1rem 0;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

nav a {
  color: #f0f0f0;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  position: relative;
  padding: 0.5rem;
  transition: 0.3s;
}

nav a:hover {
  color: #ffeb3b;
}

nav a.active {
  color: #ffffff;
  font-weight: bold;
  border-bottom: 2px solid #ffffff;
}

/* Contenedor principal */
main {
  max-width: 800px;
  margin: 2rem auto;
  background: #ffffff;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
  animation: fadeIn 0.6s ease;
}

/* Títulos */
h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #0072ff;
}

/* Formularios */
form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

input, textarea {
  padding: 0.9rem;
  font-size: 1rem;
  border: 2px solid #ddd;
  border-radius: 8px;
  transition: 0.3s;
}

input:focus, textarea:focus {
  outline: none;
  border-color: #0072ff;
  box-shadow: 0 0 5px #00c6ff88;
}

button {
  background: linear-gradient(to right, #00c6ff, #0072ff);
  color: white;
  padding: 0.9rem;
  border: none;
  border-radius: 8px;
  font-size: 1rem;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: linear-gradient(to right, #0072ff, #00c6ff);
  transform: scale(1.03);
}

/* Lista de productos */
ul {
  list-style: none;
  padding-left: 1rem;
}

ul li {
  background: #f0f8ff;
  margin-bottom: 0.5rem;
  padding: 0.7rem 1rem;
  border-left: 4px solid #00c6ff;
  border-radius: 6px;
}

/* Animación de aparición */
@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: none;
  }
}</style>

<body>
<button></button>






<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cómo afecta la IA en la sociedad</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="navbar">
        <div class="logo">IA Sociedad</div>
        <nav>
            <a href="#productos">Productos</a>
            <a href="#servicios">Servicios</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section class="hero" id="hero">
        <img
            src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1200&q=80"
            alt="Impacto de la IA en la sociedad"
            class="hero-image"
        >
        <div class="hero-content">
            <h1>Cómo afecta la IA en la sociedad</h1>
            <p>
                La inteligencia artificial (IA) está transformando la vida moderna a pasos agigantados. Descubre cómo impacta en la educación, salud, trabajo y vida diaria, generando nuevos retos y oportunidades para todos.
            </p>
            <a href="#contacto" class="cta-btn">¡Contáctanos para saber más!</a>
        </div>
    </section>

    <main>
        <section id="productos" class="productos">
            <h2>Productos impulsados por IA</h2>
            <div class="productos-grid">
                <div class="producto-card">
                    <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="Asistente Virtual">
                    <h3>Asistente Virtual</h3>
                    <p>Solución de IA para atención al cliente 24/7.</p>
                </div>
                <div class="producto-card">
                    <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="Sistema de Diagnóstico Médico">
                    <h3>Sistema de Diagnóstico Médico</h3>
                    <p>IA que ayuda a médicos con diagnósticos precisos.</p>
                </div>
                <div class="producto-card">
                    <img src="https://images.unsplash.com/photo-1503676382389-4809596d5290?auto=format&fit=crop&w=400&q=80" alt="Plataforma Educativa Inteligente">
                    <h3>Plataforma Educativa Inteligente</h3>
                    <p>Personaliza el aprendizaje para cada estudiante.</p>
                </div>
            </div>
        </section>

        <section id="servicios" class="servicios">
            <h2>Servicios</h2>
            <div class="servicios-list">
                <div class="servicio-card">
                    <h3>Consultoría en IA</h3>
                    <p>Te asesoramos en la integración de IA en tu empresa.</p>
                </div>
                <div class="servicio-card">
                    <h3>Desarrollo de Chatbots</h3>
                    <p>Creamos asistentes virtuales personalizados para tu negocio.</p>
                </div>
                <div class="servicio-card">
                    <h3>Análisis de Datos con IA</h3>
                    <p>Transforma tus datos en información valiosa mediante IA.</p>
                </div>
            </div>
        </section>

        <section id="contacto" class="contacto">
            <h2>Contacto</h2>
            <form autocomplete="off">
                <input type="text" name="nombre" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu correo electrónico" required>
                <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <footer>
        <small>© 2025 - Landing Page: Cómo afecta la IA en la sociedad</small>
    </footer>
</body>
</html>


</body>

 

<name> ¿Comó afecta la IA en la sociedad? </name>


</html> 
