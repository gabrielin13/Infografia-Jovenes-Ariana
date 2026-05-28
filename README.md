📑 Contenido Educativo
La guía cubre exhaustivamente los siguientes temas basados en documentos oficiales y académicos:

Historia: Orígenes antiguos, formalización en el siglo XIX, cronología hasta la era moderna.
Reglas y Juego: Estructura del partido, manejo de balón, puntuación, faltas y cambios reglamentarios.
Equipamiento: Balones (medidas por categoría), cancha (diagrama SVG interactivo) y equipamiento adicional.
Tipos de Balonmano: Interior, Playa y variaciones (Minibalonmano, callejero).
Competiciones: Juegos Olímpicos, Campeonatos Mundiales, Continentales y nuevas reglas de competición.
Cultura: Estrategia vs. Tácticas, atractivo global, jugadores históricos y tendencias.
Estrategia y Técnicas: Diagramas SVG de formaciones ofensivas/defensivas, componentes de entrenamiento.
Lesiones y Prevención: Riesgos comunes, conmociones cerebrales y importancia del acondicionamiento físico.
🎨 Arquitectura y Personalización
El código está diseñado para ser fácilmente modificable directamente en el archivo index.html.

Modificar el Cuestionario
Busca el arreglo quizData en la sección <script> al final del archivo. Cada objeto representa una pregunta:

javascript

{
  question: "¿Tu pregunta aquí?",
  options: ["Opción A", "Opción B", "Opción C", "Opción D"],
  correct: 2, // Índice de la opción correcta (0=A, 1=B, 2=C, 3=D)
  explanation: "Explicación que se muestra al responder."
}
Cambiar la Paleta de Colores
Los colores principales están definidos en las clases de utilidad de Tailwind y en el bloque <style>:

Color de acento principal: cyan-400 (#22d3ee)
Color de acento secundario: purple-400 (#a855f7)
Fondo de superficie: #050505, #0a0a0a, #111111
♿ Accesibilidad
Uso de etiquetas semánticas (<nav>, <main>, <section>, <footer>).
Roles ARIA para componentes interactivos (role="tablist", role="tab", role="dialog", role="img").
Etiquetas aria-label descriptivas para navegación y botones.
Gestión de estados aria-selected y aria-expanded mediante JavaScript.
Contraste de colores optimizado para legibilidad sobre fondos oscuros.
📄 Licencia
Este proyecto es de código abierto y está disponible bajo la Licencia MIT.

Contenido educativo generado a partir de fuentes de investigación. El contenido no representa el punto de vista del desarrollador y puede contener inexactitudes. Considere verificar la información importante.
