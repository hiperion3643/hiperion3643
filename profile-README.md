
---

### 2. Estilo Visual (Cambio de fondo y colores)

Para cambiar el fondo y los colores de tu perfil, necesitas usar un archivo de personalización especial. Crea un archivo llamado `profile-README.md` en la raíz de tu repositorio especial (el que tiene tu nombre).

Aquí tienes un diseño inspirado en terminales de datos y física de partículas:

```css
/* Fondo y tema general - Quantum Terminal */
body {
  background: linear-gradient(145deg, #0a0f1e 0%, #0e1a2b 100%);
  color: #c0caf5; /* Texto suave para leer */
  font-family: 'Fira Code', 'Cascadia Code', 'Courier New', monospace;
}

/* Encabezados con estilo "partícula" */
h1, h2, h3 {
  color: #7dcfff; /* Azul claro cuántico */
  border-bottom: 1px solid #ff9e64; /* Naranja neón de "reacción" */
  display: inline-block;
  padding-bottom: 5px;
}

/* Código y datos (como si fueran electrones) */
code, pre {
  background-color: #1a2639; /* Fondo de terminal más oscuro */
  color: #9ece6a; /* Verde datos */
  border-left: 3px solid #ff9e64; /* Línea naranja de advertencia científica */
  border-radius: 0px; /* Bordes rectos como pantallas CRT */
  padding: 10px;
  font-size: 14px;
}

/* Links (tu LinkedIn y email) */
a {
  color: #89ddff; /* Azul claro */
  text-decoration: none;
  transition: color 0.2s ease-in-out;
}

a:hover {
  color: #ff9e64; /* Se encienden en naranja al pasar el mouse */
  text-decoration: underline wavy #ff9e64; /* Subrayado de "oscilación" */
}

/* Bloques de tecnología */
blockquote {
  background: #0f1a2b;
  border-left: 4px solid #7aa2f7; /* Azul de física */
  margin: 1.5em 10px;
  padding: 0.5em 10px;
}

/* Listas con viñetas cuadradas "byte" */
ul {
  list-style-type: none;
  padding-left: 20px;
}

ul li::before {
  content: "▹"; /* Símbolo de terminal */
  color: #ff9e64; /* Naranja */
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-left: -1em;
}

/* La línea de "Sobre mí" con un efecto de barrido */
p {
  line-height: 1.6;
  text-shadow: 0 0 5px rgba(125, 207, 255, 0.1);
}