<div
  id="carouselExampleCaptions"
  class="carousel slide"
  data-bs-ride="carousel"
>
  <div class="carousel-indicators">
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="0"
      class="active"
      aria-current="true"
      aria-label="Slide 1"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="1"
      aria-label="Slide 2"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="2"
      aria-label="Slide 3"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="3"
      aria-label="Slide 4"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="4"
      aria-label="Slide 5"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleCaptions"
      data-bs-slide-to="5"
      aria-label="Slide 6"
    />
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img
        src="/images/wedding.jpg"
        class="d-block w-100 car__img"
        alt="wedding-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">WEDDING SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button>
        </a>
      </div>
    </div>
    <div class="carousel-item">
      <img
        src="/images/anniversary.jpg"
        class="d-block w-100 car__img"
        alt="anniversary-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">ANNIVERSARY SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button></a
        >
      </div>
    </div>
    <div class="carousel-item">
      <img
        src="/images/baby-shower.jpg"
        class="d-block w-100 car__img"
        alt="baby-shower-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">BABY SHOWER SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button></a
        >
      </div>
    </div>
    <div class="carousel-item">
      <img
        src="/images/mehdi.jpg"
        class="d-block w-100 car__img"
        alt="mehdi-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">MEHDI SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button></a
        >
      </div>
    </div>
    <div class="carousel-item">
      <img
        src="/images/mehdi-2.jpg"
        class="d-block w-100 car__img"
        alt="mehdi-2-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">MEHDI 2 SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button></a
        >
      </div>
    </div>
    <div class="carousel-item">
      <img
        src="/images/birthday.jpg"
        class="d-block w-100 car__img"
        alt="birthday-img"
      />
      <div class="carousel-caption  d-md-block car__caption">
        <h5 class="car__title">BIRTHDAY SERVICE</h5>
        <a href="#">
          <button class="custom-btn btn-5"><span>View More</span></button></a
        >
      </div>
    </div>
  </div>
  <button
    class="carousel-control-prev"
    type="button"
    data-bs-target="#carouselExampleCaptions"
    data-bs-slide="prev"
  >
    <span class="carousel-control-prev-icon" aria-hidden="true" />
    <span class="visually-hidden">Previous</span>
  </button>
  <button
    class="carousel-control-next"
    type="button"
    data-bs-target="#carouselExampleCaptions"
    data-bs-slide="next"
  >
    <span class="carousel-control-next-icon" aria-hidden="true" />
    <span class="visually-hidden">Next</span>
  </button>
</div>

<style lang="scss">
  @import url("https://fonts.googleapis.com/css2?family=Calligraffitti&display=swap");
  .car {
    &__caption {
      margin-bottom: 2rem;
    }

    &__title {
      font-size: 2rem;
      font-family: "Calligraffitti", cursive;
      letter-spacing: 5px;

      @media (max-width: 767.98px) {
        font-size: 1rem;
      }
    }
  }

  button {
    margin: 20px;

    @media (max-width: 575.98px) {
      margin: 10px;
    }
  }
  .custom-btn {
    width: 130px;
    height: 40px;
    color: #fff;
    border-radius: 3px;
    padding: 10px 25px;
    font-family: "Lato", sans-serif;
    font-weight: 500;
    background: transparent;
    cursor: pointer;
    transition: all 0.3s ease;
    position: relative;
    display: inline-block;
    box-shadow: inset 2px 2px 2px 0px rgba(255, 255, 255, 0.5),
      7px 7px 20px 0px rgba(0, 0, 0, 0.1), 4px 4px 5px 0px rgba(0, 0, 0, 0.1);
    outline: none;
  }

  /* 5 */
  .btn-5 {
    width: 130px;
    height: 40px;
    line-height: 42px;
    padding: 0;
    border: none;
    background: rgb(255, 27, 0);
    background: linear-gradient(
      90deg,
      rgba(46, 5, 5, 1) 0%,
      rgba(206, 60, 62, 1) 100%
    );
  }
  .btn-5:hover {
    color: #fff;
    background: transparent;
    box-shadow: none;
  }
  .btn-5:before,
  .btn-5:after {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    height: 2px;
    width: 0;
    background: red;
    box-shadow: -1px -1px 5px 0px #fff, 7px 7px 20px 0px #0003,
      4px 4px 5px 0px #0002;
    transition: 400ms ease all;
  }
  .btn-5:after {
    right: inherit;
    top: inherit;
    left: 0;
    bottom: 0;
  }
  .btn-5:hover:before,
  .btn-5:hover:after {
    width: 100%;
    transition: 800ms ease all;
  }
</style>
