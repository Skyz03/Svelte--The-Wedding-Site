<script>
  // @ts-nocheck

  import Lightbox from "./Lightbox.svelte";
  import ImageDisplay from "./ImageDisplay.svelte";

  let modalOpen = false;

  let imageShowingIndex = 0;

  const handleImgClick = (/** @type {{ target: { id: any; }; }} */ e) => {
    imageShowingIndex = Number(e.target.id);
    modalOpen = true;
  };
</script>

<!-- The Modal/Lightbox -->
{#if modalOpen}
  <Lightbox on:click={() => (modalOpen = false)} {imageShowingIndex} />
{:else}
  <ImageDisplay on:click={handleImgClick} />
{/if}

<!-- Button to open Lightbox -->
<section>
  <button class="custom-btn btn-5" on:click={() => (modalOpen = true)}>
    Lightbox
  </button>
</section>

<style lang="scss">
  section {
    width: 100%;
    text-align: center;
    margin-top: 5%;
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
    color: #000;
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
