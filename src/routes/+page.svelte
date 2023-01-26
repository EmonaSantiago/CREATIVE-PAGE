<script>
</script>

<section id="homepage">
  <img
    class="background1"
    src="src/images/Schermafbeelding 2023-01-25 om 12.54.27.png"
    alt="background"
    style="width:100%;"
  />

  <section id="background2">
    <img
      class="background2"
      src="src/images/Schermafbeelding 2023-01-26 om 12.08.27.png"
      alt="background"
      style="width:100%;"
    />
  </section>

  <section id="background3">
    <img
      class="background2"
      src="src/images/Schermafbeelding 2023-01-26 om 12.48.17.png"
      alt="background"
      style="width:100%;"
    />
  </section>

  <img class="pop-left" src="src/images/klipartz.com.png" alt="pop-left" />
  <img
    class="pop-right"
    src="src/images/—Pngtree—cartoon cute explosion dialog bubble_4040022.png"
    alt="pop-right"
  />

  <section id="bubble">
    <img class="pop-center" src="src/images/pngegg (3).png" alt="pop-center" />
  </section>
</section>

<style>
  * {
    font-family: BubbleGum;
    scroll-behavior: smooth;
  }

  #homepage {
    scroll-behavior: smooth;
  }
  a {
    scroll-behavior: smooth;
    text-decoration: none;
    color: pink;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

  .pop-left {
    /* position: absolute; */
    top: -300px;
    left: -300px;
    width: 60em;
    position: fixed; /* make sure it stays put so we can see it! */

    animation: rotate 10s linear infinite;
    animation-delay: calc(var(--scroll) * -1s);
  }

  .pop-right {
    /* position: absolute; */
    bottom: -600px;
    right: -500px;
    width: 80em;
    position: fixed; /* make sure it stays put so we can see it! */

    animation: rotate 10s linear infinite;
    animation-delay: calc(var(--scroll) * -1s);
  }

  .pop-center {
    position: absolute;
    top: 30%;
    left: 40%;
    width: 20em;
    display: inline-block;
    animation: rotate 6s linear infinite;
    animation: fadeIn 5s;
  }
  @keyframes rotate {
    to {
      transform: rotate(360deg);
    }
  }

  @keyframes fadeIn {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
</style>
