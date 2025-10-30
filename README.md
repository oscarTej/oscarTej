<!--
README de perfil de GitHub para: oscarTej
Estilo: Creativo / Futurista
-->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="Oscar Tejerina.png" />
    <source media="(prefers-color-scheme: light)" srcset="Oscar Tejerina.png" />
    <img alt="Banner Futurista" src="assets/banner-futurista-light.png" width="100%" />
  </picture>
</p>

<h1 align="center">¡Hola, soy Oscar Tejerina! 👋</h1>
<p align="center">Desarrollador en formación (2º DAM) — orientado a <b>Android</b>, <b>Kotlin</b> y <b>Java</b>. Me gusta construir apps limpias, escalables y con un toque futurista ✨</p>

<p align="center">
  <a href="https://komarev.com/ghpvc/?username=oscarTej&style=flat&label=Vistas+del+perfil"><img src="https://komarev.com/ghpvc/?username=oscarTej&style=flat&label=Vistas+del+perfil" alt="Contador de visitas" /></a>
</p>

---

## 🚀 Sobre mí

* 🔭 Actualmente: practicando arquitectura limpia en Android (MVVM, capas, tests) y mejorando mi escritura de Kotlin.
* 🌱 Aprendiendo: **Jetpack**, **Coroutines/Flow**, **Room/SQLite**, **Firebase**, **testing con JUnit/MockK**.
* 🎯 Objetivo 2025: publicar una app Android en Play Store.
* 💬 Pregúntame sobre: estructuras de datos básicas, POO, patrones de diseño para apps móviles.

---

## 🧠 Tech Stack

<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white" />
<img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" />
<img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white" />
<img alt="Android Studio" src="https://img.shields.io/badge/Android%20Studio-3DDC84?logo=androidstudio&logoColor=white" />
<img alt="IntelliJ IDEA" src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?logo=intellijidea&logoColor=white" />
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
<img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
<img alt="Gradle" src="https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white" />
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" />
<img alt="Firebase" src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black" />

---

## 📦 Proyectos destacados

* [🦸‍♂️ Superhero API App](https://github.com/oscarTej/SuperheroAPI)
  App Android en **Kotlin** que consume la **Superhero API** para mostrar fichas de héroes, imágenes y estadísticas.

  > Incluye arquitectura **MVVM**, consumo con **Retrofit**, y caching con **Room**.

* [📚 Bibliotecca](https://github.com/oscarTej/Bibliotecca)
  Proyecto Java de **gestión de biblioteca** con operaciones CRUD y persistencia de datos.

  > Ejemplo completo de **POO**, manejo de ficheros y base de datos **SQLite**.

* [😂 Simpson API](https://github.com/oscarTej/SimpsonAPI)
  Aplicación que muestra frases y personajes icónicos de Los Simpson a través de una **API pública**.

  > Uso de **Kotlin coroutines**, **RecyclerView** y diseño con **Material Design**.

---

## 📊 Estadísticas & racha (Streak)

<p>
  <img src="https://streak-stats.demolab.com?user=oscarTej&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=oscarTej&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>

<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=oscarTej&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
</p>

---

## 🗺️ Roadmap de aprendizaje (Android/Kotlin)

* [ ] Fundamentos sólidos de Kotlin (colecciones, null safety, clases, herencia, data/sealed)
* [ ] Android: Activities/Fragments → Jetpack Navigation
* [ ] Arquitectura MVVM + UseCases + Repositorios
* [ ] Coroutines + Flow (manejo de estados)
* [ ] Persistencia con Room/SQLite
* [ ] APIs REST con Retrofit + manejo de errores
* [ ] DI (Hilt/Koin)
* [ ] Testing (JUnit/MockK, pruebas de UI)
* [ ] Publicar una app en Play Store

---

## 🌐 Conecta conmigo

<a href="https://www.linkedin.com/in/oscar-tejerina-977254310/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" /></a> <a href="https://www.tiktok.com/@ogcartswiss" target="_blank"><img alt="TikTok" src="https://img.shields.io/badge/TikTok-000000?logo=tiktok&logoColor=white" /></a>

---

## 🐍 Animación de contribuciones (Snake)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/oscarTej/oscarTej/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/oscarTej/oscarTej/output/snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/oscarTej/oscarTej/output/snake.svg" />
</picture>

<details>
<summary>⚙️ Configurar animación Snake con GitHub Actions</summary>

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *" # cada día a medianoche UTC
  workflow_dispatch: {}

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: oscarTej
          outputs: |
            dist/snake.svg
            dist/snake-dark.svg?palette=github-dark
      - name: Push Snake to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

<p align="center">Hecho con 💙 y un toque de neón futurista.</p>
