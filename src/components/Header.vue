<template>
  <header class="header" id="header">
    <nav class="nav container">
      <a href="#" class="nav__logo"> Mohit </a>

      <div class="nav__menu" id="nav-menu">
        <ul class="nav__list">
          <li class="nav__item">
            <a href="#home" class="nav__link active-link">
              <i class='bx bx-home-alt'></i>
            </a>
          </li>
          <li class="nav__item">
            <a href="#about" class="nav__link">
              <i class='bx bx-user'></i>
              <!-- <box-icon name="user"></box-icon> -->
            </a>
          </li>
          <li class="nav__item">
            <a href="#skills" class="nav__link">
              <i class='bx bx-book'></i>
              <!-- <box-icon name="book"></box-icon> -->
            </a>
          </li>
          <li class="nav__item">
            <a href="#work" class="nav__link">
              <i class='bx bx-briefcase-alt-2'></i>
              <!-- <box-icon name="briefcase-alt-2"></box-icon> -->
            </a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">
              <i class='bx bx-message-square-detail'></i>
              <!-- <box-icon name="message-square-detail"></box-icon> -->
            </a>
          </li>
        </ul>
      </div>

      <div class="nav__btns">
        <!-- Theme change button -->
        <box-icon name='moon' class="change-theme" id="theme-button"></box-icon>


        <div class="nav__toggle" id="nav-toggle">
          <i class="bx bx-grid-alt"></i>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style></style>
