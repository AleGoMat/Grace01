# 🚀 Mi Portafolio

[🏠 About Me](#about-me) | [📂 Projects](#projects) | [📄 CV / Resume](#cv)

---

<div id="about-me">
  <h2>About Me</h2>
  <p>¡Hola! Soy [Tu Nombre] y me especializo en Data Science, Machine Learning y estrategias de riesgo de crédito.</p>
</div>

<div id="projects" style="display: none;">
  <h2>📂 Projects</h2>
  <p>🔹 <a href="https://github.com/tuusuario/proyecto1">Proyecto 1</a></p>
  <p>🔹 <a href="https://github.com/tuusuario/proyecto2">Proyecto 2</a></p>
</div>

<div id="cv" style="display: none;">
  <h2>📄 CV / Resume</h2>
  <p>📌 <a href="https://tu-enlace-a-cv.com">Descargar mi CV en PDF</a></p>
</div>

<script>
  // Captura los clics en los enlaces y muestra la sección correspondiente
  document.querySelectorAll("a").forEach(link => {
    link.addEventListener("click", function(event) {
      if (this.getAttribute("href").startsWith("#")) {
        event.preventDefault();
        let sections = document.querySelectorAll("div[id]");
        sections.forEach(section => section.style.display = "none");
        let target = document.querySelector(this.getAttribute("href"));
        if (target) target.style.display = "block";
      }
    });
  });
</script>
