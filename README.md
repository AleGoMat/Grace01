# 🚀 Mi Portafolio

[🏠 About Me](index.md) | [📂 Projects](projects.md) | [📄 CV / Resume](cv.md)

---

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
