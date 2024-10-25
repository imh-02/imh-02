
<style>

.wrapper {
    display: grid;
    grid-template-columns: auto;
    grid-template-rows: auto;
    grid-template-areas: "header" "content" "gitHubStats" "footer";
    background-color: rgb(255, 255, 255);
    padding: 20px;
    gap: 20px;
    text-align: center;
    height: 100vh;
    font: {
        family: "Gill Sans", sans-serif;
    }
}

h1{
    color: rgb(255, 255, 255);
}

.header {
    grid-area: header;
    background-color: rgb(20, 33, 61);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.content {
    grid-area: content;
    grid-template-columns: 1fr 1fr;
    background-color: rgb(255, 255, 255);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.avatar{
    grid-column: 1
}

.presentacion{
    grid-column: 2
}

.stats {
    grid-area: gitHubStats;
    background-color: rgb(20, 33, 61);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

img {
    width: 45%;
    border-radius: 10px;
}

</style>

<div class="wrapper">
    <div class="header">
        <h1>Ismael Martín</h1>
        <h2>Desarrollador Web</h2>
    </div>
    <div class="content">
        <div class="avatar">
            <img src="image/foto_perfil.jpg">
        </div>
        <div class="presentation">
        ¡Hola! Soy Ismael, graduado en Ingeniería Informática, apasionado por las diversas ramas de la informática y, en especial, el desarrollo web. Estoy siempre dispuesto a aprender integrándome en equipos profesionales. Tengo conocimientos en desarrollo con TypeScript, C++ y Python, y he trabajado con herramientas de análisis de datos como Microsoft Power BI. Además, desarrollé mi trabajo de fin de grado en el ámbito de la inteligencia artificial. Actualmente me encuentro cursando el Máster en Ingeniería Informática por la Universidad de La Laguna, con el objetivo de complementar la formación del grado y adquirir más conocimientos vinculados al perfil fullstack. 
        </div>
    </div>
    <div class="stats">
        <h2>Estadísticas de GitHub</h2>
        <img src="https://github-readme-stats.vercel.app/api?username=imh-02&show_icons=true&theme=radical">
    </div>
    <div class="footer">
        <a href="https://www.linkedin.com/in/ismael-mart%C3%ADn-herrera/">LinkedIn</a>
        <a href="https://github.com/imh-02">GitHub</a>
    </div>
</div>


<!--
**imh-02/imh-02** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
