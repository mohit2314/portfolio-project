<template>
  <main class="main">
    <section class="home section" id="home">
      <div class="home__container container grid">
        <div class="home__data">
          <span class="home__greeting">Hello, I'm</span>
          <h1 class="home__name">Mohit Patel</h1>
          <h3 class="home__education">Full Stack Developer</h3>

          <div class="home__buttons">
            <a
              download=""
              href="../assets/pdf/Mohit-cv.pdf"
              class="button button--ghost"
            >
              Download CV
            </a>
            <a href="#about" class="button">About me</a>
          </div>
        </div>

        <div class="home__handle">
          <img src="../assets/img/home-img.jpg" alt="" class="home__img" />
        </div>

        <div class="home__social">
          <a href="https://www.linkedin.com/" class="home__social-link">
            <i class="bx bxl-linkedin-square"></i>
          </a>
          <a href="https://www.github.com/" class="home__social-link">
            <i class="bx bxl-github"></i>
          </a>
          <a href="https://www.dribbble.com/" class="home__social-link">
            <i class="bx bxl-dribbble"></i>
          </a>
        </div>

        <a href="#about" class="home__scroll">
            <i class="bx bx-mouse home__scroll-icon"></i>
            <span class="home__scroll-name">Scroll Down</span>
        </a>
      </div>
    </section>
  </main>
</template>

<script>
export default {};
</script>

<style></style>
