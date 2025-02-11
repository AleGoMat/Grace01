# 🚀 Mi Portafolio

[🏠 About Me](#about-me) | [📂 Projects](#projects) | [📄 CV / Resume](#cv)

---

<div id="about-me">
  <h2>About Me</h2>
  <p>¡Hola Mundo! Soy Grace, economista y profesional de analytics aplicado a riesgo de crédito para banca retail. Terminé mi Maestría en Inteligencia Analítica de Datos en Octubre de 2024, que me sirvió para darme cuenta de todo lo que me faltaba por aprender, a trabajar en equipo de verdad y a comprometerme con el aprendizaje continuo. Soy una apasionada de la aplicación del análisis de datos y métodos cuantitativos a mi tema preferido, el riesgo de crédito, que ha sido mi trabajo durante casi 7 años, y he tenido la oportunidad de abordarlo desde la banca, desde Fintech y desde el buró de crédito.</p>
</div>

<div id="projects" style="display: none;">
  <h2>📂 Projects</h2>

  <h3>🔹 <a href="https://www.datacamp.com/datalab/w/9b26cc20-77c8-42ad-82cc-5e529f813880/edit">
      Project: From Data to Dollars - Predicting Insurance Charges
  </a></h3>

  <p>
      <img src="assets/img/insurance.png" width="60%">
  </p>

  <p align="justify">
    En este proyecto desarrollamos un modelo para predecir los cargos anuales de cobertura en salud. El problema radica en que los pacientes a menudo carecen de visibilidad sobre sus posibles costos médicos, lo que dificulta una adecuada planificación financiera.
  </p>

  <p align="justify">
    Por otro lado, los prestadores de salud también enfrentan desafíos para estimar los costos totales por paciente, lo que limita la capacidad de equilibrar de manera personalizada la medicina preventiva y curativa.
  </p>

  <p align="justify">
    Utilizando <strong>técnicas de regresión</strong> (Regresión Lineal y XGBoost Regressor), analizamos los factores que impactan los costos médicos y desarrollamos un modelo predictivo que proporciona estimaciones precisas tanto para pacientes como para prestadores de salud.
  </p>

  <h4>🎯 Impacto:</h4>
  <ul>
    <li>✅ Mejor planificación financiera para los pacientes.</li>
    <li>✅ Mayor precisión en la estimación de costos anuales y mensuales.</li>
    <li>✅ Optimización en la toma de decisiones para los prestadores de salud.</li>
  </ul>

  <h3>🔹 <a href="https://github.com/tuusuario/proyecto2">Proyecto 2</a></h3>

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
