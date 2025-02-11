# 🚀 Mi Portafolio

[🏠 About Me](index.md) | [📂 Projects](projects.md) | [📄 CV / Resume](cv.md)

---

<div id="about-me">
  <h2>About Me</h2>
  <p>¡Hola Mundo! Soy Grace, economista y profesional de analytics aplicado a riesgo de crédito para banca retail. Terminé mi Maestría en Inteligencia Analítica de Datos en Octubre de 2024, que me sirvió para darme cuenta de todo lo que me faltaba por aprender, a trabajar en equipo de verdad y a comprometerme con el aprendizaje continuo. Soy una apasionada de la aplicación del análisis de datos y métodos cuantitativos a mi tema preferido, el riesgo de crédito, que ha sido mi trabajo durante casi 7 años, y he tenido la oportunidad de abordarlo desde la banca, desde Fintech y desde el buró de crédito.</p>
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
