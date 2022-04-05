<template>
  <section class="services section">
    <span class="section__subtitle">My Services</span>
    <h2 class="section__title">What I Offer</h2>

    <div class="services__container container grid">
      <div class="services__card">
        <h3 class="services__title">
          Product <br />
          Designer
        </h3>
        <span class="services__button" @click="modal1=true">
          See more <i class="bx bx-right-arrow-alt services__icon"></i>
        </span>
        <!-- Service Modal -->
        <div
          :class="['services__modal',{'active-modal':modal1}]"
        >
          <div class="services__modal-content">
            <i class="bx bx-x services__modal-close"></i>
            <h3 class="services__modal-title">
              Product <br />
              Designer
            </h3>
            <p class="services__modal-description">
              Service with more than 3 years of experience.Providing quality
              work to clients and companies.
            </p>
            <ul class="services__modal-list">
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I develop the user interface.
                </p>
              </li>
              <!-- item-2 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">Web page development.</p>
              </li>
              <!-- item-3 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I create ux element interactions.
                </p>
              </li>
              <!-- item-4 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I position your company brand.
                </p>
              </li>
              <!-- item-5 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  Design and mockups of product for companies.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!-- Card-2 -->
      <div class="services__card">
        <h3 class="services__title">
          UI/UX <br />
          Designer
        </h3>
        <span class="services__button">
          See more <i class="bx bx-right-arrow-alt services__icon"></i>
        </span>
        <!-- Service Modal -->
        <div class="services__modal">
          <div class="services__modal-content">
            <i class="bx bx-x services__modal-close"></i>
            <h3 class="services__modal-title">
              UI/UX <br />
              Designer
            </h3>
            <p class="services__modal-description">
              Service with more than 3 years of experience.Providing quality
              work to clients and companies.
            </p>
            <ul class="services__modal-list">
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I develop the user interface.
                </p>
              </li>
              <!-- item-2 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">Web page development.</p>
              </li>
              <!-- item-3 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I create ux element interactions.
                </p>
              </li>
              <!-- item-4 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I position your company brand.
                </p>
              </li>
              <!-- item-5 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  Design and mockups of product for companies.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <!-- Card-3 -->
      <div class="services__card">
        <h3 class="services__title">
          Visual <br />
          Designer
        </h3>
        <span class="services__button">
          See more <i class="bx bx-right-arrow-alt services__icon"></i>
        </span>
        <!-- Service Modal -->
        <div class="services__modal">
          <div class="services__modal-content">
            <i class="bx bx-x services__modal-close"></i>
            <h3 class="services__modal-title">
              Visual <br />
              Designer
            </h3>
            <p class="services__modal-description">
              Service with more than 3 years of experience.Providing quality
              work to clients and companies.
            </p>
            <ul class="services__modal-list">
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I develop the user interface.
                </p>
              </li>
              <!-- item-2 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">Web page development.</p>
              </li>
              <!-- item-3 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I create ux element interactions.
                </p>
              </li>
              <!-- item-4 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  I position your company brand.
                </p>
              </li>
              <!-- item-5 -->
              <li class="services__modal-item">
                <i class="bx bx-check services__modal-icon"></i>
                <p class="services__modal-info">
                  Design and mockups of product for companies.
                </p>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      modal1:false,
      serviceModals: [
        {
          title: "Front End",
          subtitle: "Development",
          description:
            "Service with more than 3 years of experience.Providing quality work to clients and companies",
          servicePoints: [
            " I develop the user interface.",
            "Web page development.",
            "I create ux element interactions.",
            "I position your company brand.",
            "Design and mockups of product for companies.",
          ],
        },
         {
          title: "Back End",
          subtitle: "Development",
          description:
            "Service with more than 3 years of experience.Providing quality work to clients and companies",
          servicePoints: [
            " I develop the user interface.",
            "Web page development.",
            "I create ux element interactions.",
            "I position your company brand.",
            "Design and mockups of product for companies.",
          ],
        },
         {
          title: "Product",
          subtitle: "Management",
          description:
            "Service with more than 3 years of experience.Providing quality work to clients and companies",
          servicePoints: [
            " I develop the user interface.",
            "Web page development.",
            "I create ux element interactions.",
            "I position your company brand.",
            "Design and mockups of product for companies.",
          ],
        },
        {
          title: "Trainings",
          subtitle: "Web Development",
          description:
            "Service with more than 3 years of experience.Providing quality work to clients and companies",
          servicePoints: [
            " I develop the user interface.",
            "Web page development.",
            "I create ux element interactions.",
            "I position your company brand.",
            "Design and mockups of product for companies.",
          ],
        },
      ],
    };
  },
};
</script>

<style></style>
