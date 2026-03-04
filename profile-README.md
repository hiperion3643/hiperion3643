/* profile-README.md */
/* Estilo "Quantum Terminal" para Luis Enrique Muñoz Juárez */
/* Físico y Analista de Datos - Python, R, IA, SQL, LaTeX */

/* Fondo y tema general - Laboratorio digital */
body {
  background: linear-gradient(145deg, #0a0f1e 0%, #0e1a2b 100%);
  color: #c0caf5; /* Texto suave para lectura */
  font-family: 'Fira Code', 'Cascadia Code', 'Courier New', monospace;
  line-height: 1.6;
}

/* Encabezados con estilo "partícula cuántica" */
h1, h2, h3 {
  color: #7dcfff; /* Azul claro cuántico */
  border-bottom: 2px solid #ff9e64; /* Naranja neón de "reacción" */
  display: inline-block;
  padding-bottom: 8px;
  letter-spacing: -0.5px;
}

/* Efecto especial para el título principal */
h1 {
  font-size: 2.5em;
  text-shadow: 0 0 10px rgba(125, 207, 255, 0.5);
}

h1::before {
  content: "⚛️ ";
  font-size: 1.2em;
}

/* Bloques de código - como terminal de datos */
code, pre {
  background-color: #1a2639 !important; /* Fondo de terminal */
  color: #9ece6a !important; /* Verde datos */
  border-left: 4px solid #ff9e64; /* Línea naranja de advertencia científica */
  border-radius: 0px; /* Bordes rectos como pantallas CRT */
  padding: 12px !important;
  font-size: 14px;
  font-family: 'Fira Code', monospace;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}

/* Links (tu LinkedIn y email) */
a {
  color: #89ddff; /* Azul claro */
  text-decoration: none;
  transition: all 0.3s ease;
  border-bottom: 1px dotted transparent;
}

a:hover {
  color: #ff9e64; /* Se encienden en naranja */
  border-bottom: 1px dotted #ff9e64;
  text-decoration: none;
}

/* Bloques de cita - para destacar información */
blockquote {
  background: #0f1a2b;
  border-left: 4px solid #7aa2f7; /* Azul de física */
  margin: 1.5em 10px;
  padding: 1em 20px;
  border-radius: 0 8px 8px 0;
  font-style: italic;
}

/* Listas con viñetas de "byte" / terminal */
ul, ol {
  padding-left: 20px;
}

ul {
  list-style-type: none;
}

ul li {
  position: relative;
  padding-left: 5px;
}

ul li::before {
  content: "▹"; /* Símbolo de terminal */
  color: #ff9e64; /* Naranja */
  font-weight: bold;
  position: absolute;
  left: -15px;
  top: 0;
}

/* Tablas - para datos estructurados */
table {
  border-collapse: collapse;
  width: 100%;
  margin: 20px 0;
  background: #0f1a2b;
}

th {
  background-color: #1a2a3a;
  color: #7dcfff;
  padding: 12px;
  border: 1px solid #2e3f4f;
}

td {
  padding: 10px;
  border: 1px solid #2e3f4f;
}

/* Imágenes - con efecto de brillo */
img {
  border-radius: 8px;
  filter: drop-shadow(0 0 5px rgba(125, 207, 255, 0.3));
  transition: filter 0.3s ease;
}

img:hover {
  filter: drop-shadow(0 0 10px rgba(255, 158, 100, 0.5));
}

/* Línea horizontal - separadores */
hr {
  border: none;
  height: 2px;
  background: linear-gradient(90deg, #ff9e64, #7dcfff, #ff9e64);
  opacity: 0.5;
  margin: 30px 0;
}

/* Badges / insignias - si usas shields.io */
.badge {
  display: inline-block;
  padding: 4px 8px;
  background: #1a2639;
  color: #9ece6a;
  border: 1px solid #7dcfff;
  border-radius: 4px;
  font-size: 12px;
  margin: 2px;
}

/* Efecto de "carga" para el footer */
footer, .footer {
  text-align: center;
  opacity: 0.8;
  font-size: 0.9em;
  margin-top: 50px;
  padding: 20px;
  border-top: 1px dashed #2e3f4f;
}

/* Scrollbar personalizada - estilo terminal */
::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}

::-webkit-scrollbar-track {
  background: #0a0f1e;
}

::-webkit-scrollbar-thumb {
  background: #2e3f4f;
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: #ff9e64;
}

/* Resaltado de selección */
::selection {
  background: #ff9e64;
  color: #0a0f1e;
}
