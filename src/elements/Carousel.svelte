<div
  id="carouselExampleIndicators"
  class="carousel slide"
  data-bs-ride="carousel"
>
  <div class="carousel-indicators">
    <button
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide-to="0"
      class="active"
      aria-current="true"
      aria-label="Slide 1"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide-to="1"
      aria-label="Slide 2"
    />
    <button
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide-to="2"
      aria-label="Slide 3"
    />
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active  rel">
      <img
        src="https://images.unsplash.com/photo-1532712938310-34cb3982ef74?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d2VkZGluZ3xlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60"
        class="d-block w-100 img-fluid"
        alt="..."
      />
      <div class="d-flex flex-column rand-title">
        <h1 class="">Text 2</h1>
        <button class="custom-btn btn-5"><span>Read More</span></button>
      </div>
    </div>
    <!-- <div class="carousel-item">
      <img
        src="https://images.unsplash.com/photo-1634729108541-516d16ddceec?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
        class="d-block w-100 img-fluid"
        alt="..."
      />
      <div class="d-flex h-100 align-items-center justify-content-center">
        <h1>Text 2</h1>
      </div>
    </div> -->
    <!-- <div class="carousel-item">
      <img
        src="https://images.unsplash.com/photo-1527529482837-4698179dc6ce?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
        class="d-block w-100 img-fluid"
        alt="..."
      />
      <span>asdsad</span>
    </div> -->
  </div>
  <button
    class="carousel-control-prev"
    type="button"
    data-bs-target="#carouselExampleIndicators"
    data-bs-slide="prev"
  >
    <span class="carousel-control-prev-icon" aria-hidden="true" />
    <span class="visually-hidden">Previous</span>
  </button>
  <button
    class="carousel-control-next"
    type="button"
    data-bs-target="#carouselExampleIndicators"
    data-bs-slide="next"
  >
    <span class="carousel-control-next-icon" aria-hidden="true" />
    <span class="visually-hidden">Next</span>
  </button>
</div>

<style>
  .rel {
    position: relative;
  }
  .rand-title {
    position: absolute;
    top: 50%;
    left: 48%;
  }

  button {
    margin: 20px;
  }
  .custom-btn {
    width: 130px;
    height: 40px;
    color: #fff;
    border-radius: 5px;
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
      0deg,
      rgba(255, 27, 0, 1) 0%,
      rgba(251, 75, 2, 1) 100%
    );
  }
  .btn-5:hover {
    color: #f0094a;
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
    background: #f0094a;
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
