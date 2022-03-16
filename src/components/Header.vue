<template>
  <header class="header" id="header">
    <nav class="nav container">
      <a href="#" class="nav__logo"> <i class="bx bxs-watch nav__logo-icon"></i> Mohit </a>

      <div class="nav__menu" id="nav-menu">
        <ul class="nav__list">
          <li class="nav__item">
            <a href="#home" class="nav__link active-link">
              <box-icon name="home-alt"></box-icon>
            </a>
          </li>
          <li class="nav__item">
            <a href="#about" class="nav__link">
              <box-icon name="user"></box-icon>
            </a>
          </li>
          <li class="nav__item">
            <a href="#skills" class="nav__link">
              <box-icon name="book"></box-icon>
            </a>
          </li>
          <li class="nav__item">
            <a href="#work" class="nav__link">
              <box-icon name="briefcase-alt-2"></box-icon>
            </a>
          </li>
          <li class="nav__item">
            <a href="#contact" class="nav__link">
              <box-icon name="message-square-detail"></box-icon>
            </a>
          </li>
        </ul>

        <div class="nav__close" id="nav-close">
          <i class="bx bx-x"></i>
        </div>
      </div>

      <div class="nav__btns">
        <!-- Theme change button -->
        <box-icon name='moon' class="change-theme" id="theme-button"></box-icon>

        <div class="nav__shop" id="cart-shop">
          <i class="bx bx-shopping-bag"></i>
        </div>

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
