<script>
  export /**
   * @type {any}
   */
  let slideNo;
  export /**
   * @type {any}
   */
  let totalSlides;
  export /**
   * @type {string | null | undefined}
   */
  let image;
  export /**
   * @type {string | null | undefined}
   */
  let altTag;
  export /**
   * @type {string | null | undefined}
   */
  let attr;
</script>

<!-- Full-width images with number text -->
<div class="mySlides">
  <div class="numbertext">{slideNo} / {totalSlides}</div>
  <img src={image} alt={altTag} title={attr} />
</div>

<style>
  /* Number text (1/3 etc) */
  .numbertext {
    color: #ddd;
    font-size: 0.9rem;
    padding: 8px 12px;
    text-shadow: 1px 1px black;
    position: absolute;
    top: 0;
  }

  img {
    width: 100%;
  }
</style>
