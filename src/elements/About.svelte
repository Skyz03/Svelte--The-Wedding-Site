<script>
</script>

<section class="about-us">
  <div class="container">
    <div class="row about-us__row">
      <div class="col-lg-5 about-us__img">
        <img class="img-fluid" src="/images/wedding.jpg" alt="about-us-img" />
      </div>
      <div class="col-lg-6 about-us__text">
        <h3 class="fw-bold about-us__title">About Us</h3>
        <p class="text-muted  about-us__subtitle">
          Subha Shringar Decorations provides decoration services of various
          kinds as required by our valued customers and make the event even more
          special including balloon decoration, flower decoration and many other
          celebration items suitable for every events.
        </p>
      </div>
    </div>
  </div>
</section>

<style lang="scss">
  .about-us {
    padding: 4rem 2rem;

    &__row {
      align-items: center;
    }

    &__text {
      margin-left: 2rem;

      @media (max-width: 991.98px) {
        margin-top: 1rem;
        margin-left: 0;
      }
    }

    &__title {
      font-family: "Calligraffitti", cursive;
      font-size: 3rem;
      letter-spacing: 5px;

      @media (max-width: 575.98px) {
        font-size: 1.5rem;
      }
    }

    &__subtitle {
      text-align: justify;
      letter-spacing: 1px;
      font-size: 1.1rem;

      @media (max-width: 575.98px) {
        font-size: 0.9rem;
      }
    }
  }
</style>
