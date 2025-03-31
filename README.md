<h1 align="center">
  🌟 𝑯𝒐𝒍𝒂, &lt;𝒅𝒆𝒔𝒂𝒓𝒓𝒐𝒍𝒍𝒂𝒅𝒐𝒓𝒆𝒔/&gt;! 🌟
</h1>

<button onclick="toggleLanguage()">English/Español</button>

<div id="content-es">
  <p>
    - 👨‍💻 **Soy un desarrollador web recién egresado apasionado por la tecnología y la creación de soluciones innovadoras.**  
    - 🔭 **Actualmente estoy buscando oportunidades laborales en desarrollo web (frontend, backend o full stack).**  
    - 🌱 **Estoy aprendiendo y perfeccionando mis habilidades en tecnologías como JavaScript, React, Node.js, y bases de datos como MongoDB.**  
  </p>
</div>

<div id="content-en" style="display:none;">
  <p>
    - 👨‍💻 **I am a freshly graduated web developer passionate about technology and creating innovative solutions.**  
    - 🔭 **I am currently looking for job opportunities in web development (frontend, backend, or full stack).**  
    - 🌱 **I am learning and honing my skills in technologies like JavaScript, React, Node.js, and databases like MongoDB.**  
  </p>
</div>

<script>
  function toggleLanguage() {
    const esContent = document.getElementById("content-es");
    const enContent = document.getElementById("content-en");
    if (esContent.style.display === "none") {
      esContent.style.display = "block";
      enContent.style.display = "none";
    } else {
      esContent.style.display = "none";
      enContent.style.display = "block";
    }
  }
</script>
