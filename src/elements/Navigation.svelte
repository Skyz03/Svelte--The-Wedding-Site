<nav class="navbar navbar-expand-lg navbar-light bg-light navigation fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img class="navigation__img" src="/images/nav-logo.png" alt="logo-img" />
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div
      class="collapse navbar-collapse justify-content-evenly"
      id="navbarSupportedContent"
    >
      <ul class="navbar-nav navigation__menu">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>

        <li class="nav-item dropdown">
          <a
            class="nav-link dropdown-toggle"
            href="#"
            id="navbarDropdown"
            role="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            Pages
          </a>
          <ul
            class="dropdown-menu navigation__dropdown"
            aria-labelledby="navbarDropdown"
          >
            <li><a class="dropdown-item" href="#">Wedding</a></li>
            <li><a class="dropdown-item" href="#">Birthday</a></li>
            <li><a class="dropdown-item" href="#">Mehdi</a></li>
            <li><a class="dropdown-item" href="#">Mehdi</a></li>
            <li><a class="dropdown-item" href="#">Mehdi</a></li>
            <li><a class="dropdown-item" href="#">Mehdi</a></li>
            <li><a class="dropdown-item" href="#">Mehdi</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<style lang="scss">
  .navigation {
    // background: #fffbd5;
    // background: -webkit-linear-gradient(to left, #b20a2c, #fffbd5);
    // background: linear-gradient(to left, #b20a2c, #fffbd5);
    background: transparent;

    &__img {
      width: 100%;
      height: 100%;
      max-width: 130px;
    }

    &__menu {
      li {
        a {
          color: #fff;
        }
      }
    }
  }

  .dropdown-menu {
    min-width: 13rem;
  }
</style>
