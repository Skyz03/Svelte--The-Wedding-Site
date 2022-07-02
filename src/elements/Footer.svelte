<footer class="footer">
  <div class="container-fluid">
    <div class="row">
      <div class="col-xl-5">
        <a
          href="/"
          class="d-flex align-items-center mb-3 link-dark text-decoration-none"
        >
          <img
            class="footer__img"
            src="/images/nav-logo.png"
            alt="footer-logo"
          />
        </a>
        <p>One stop shop for all your decortation item.</p>
      </div>

      <div class="col-xl-2">
        <h5>Services</h5>
        <ul class="nav flex-column footer__lists">
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Wedding</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Baby Shower</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Birthday</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Photography</a>
          </li>
        </ul>
      </div>

      <div class="col-xl-2">
        <h5>Services</h5>
        <ul class="nav flex-column footer__lists">
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Anniversary</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Mehdi</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Flower Decoration</a>
          </li>
          <li class="nav-item mb-2">
            <a href="#" class="nav-link p-0 text-muted">Surprise Party</a>
          </li>
        </ul>
      </div>

      <div class="col-xl-3 footer__contact">
        <h5>Contact</h5>
        <ul class="nav flex-column footer__lists">
          <li class="nav-item mb-2">
            <img src="/images/icons/call-icon.png" alt="" />
            <a href="#" class="nav-link p-0 text-muted">+977 98188768757</a>
          </li>
          <li class="nav-item mb-2">
            <img src="/images/icons/email-icon.png" alt="" />
            <a href="#" class="nav-link p-0 text-muted">info@subashringar.com</a
            >
          </li>
          <li class="nav-item mb-2">
            <img src="/images/icons/map-icon.png" alt="" />
            <a href="#" class="nav-link p-0 text-muted"
              >Banshidhar Marga, Chandol Chowk, Kathmandu</a
            >
          </li>
        </ul>
      </div>
    </div>

    <div class="d-flex justify-content-between py-4 border-top">
      <p>&copy; 2022 Company, Inc. All rights reserved.</p>
      <ul class="list-unstyled d-flex footer__lists">
        <li class="ms-3">
          <a
            class="link-dark"
            href="https://www.facebook.com/subhashringardecorations/"
          >
            <img src="/images/fb.png" alt="" />
          </a>
        </li>
        <li class="ms-3">
          <a
            class="link-dark"
            href="https://www.instagram.com/subhashringardecorations/"
          >
            <img src="/images/insta.png" alt="" />
          </a>
        </li>
      </ul>
    </div>
  </div>
</footer>

<style lang="scss">
  .footer {
    background-color: #ce3c3d;
    color: #fff;
    padding: 3rem 3rem 0;

    h5 {
      font-weight: 600;
      font-size: 1.2rem;
      letter-spacing: 0.05em;
      padding-bottom: 0.5rem;
      width: 50%;
      border-bottom: 1px solid #ffff;
    }

    &__img {
      width: 100%;
      height: 100%;
      max-width: 130px;
    }

    &__lists {
      padding: 1rem 0;
      li {
        letter-spacing: 0.07em;
        transition: all 0.5s ease-out;

        &:hover {
          opacity: 0.7;
          transform: translateY(-0.3rem);
        }
        a {
          color: #fff !important;
        }
      }
    }

    &__contact {
      li {
        display: flex;
        align-items: center;
        gap: 1rem;

        img {
          max-width: 25px;
          width: 100%;
        }
      }
    }
  }
</style>
