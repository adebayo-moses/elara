<template>
  <a id="scroll-home"></a>
  <!--Nav-->
  <nav class="navbar fixed-top navbar-expand-lg navbar-dark blur">
    <div class="container-fluid">
      <button
        class="navbar-toggler hmbg"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-center"
        id="navbarSupportedContent"
      >
        <ul class="navbar-nav">
          <li class="nav-item hover-underline-animation">
            <a class="nav-link active" href="#scroll-home">home</a>
          </li>
          <li class="nav-item hover-underline-animation">
            <!-- <a class="nav-link-active" RouterLink to="/">about</RouterLink></a> -->

            <a class="nav-link active" href="#scroll-down">about me</a>
          </li>

          <li class="nav-item hover-underline-animation">
            <a
              class="nav-link active"
              aria-current="page"
              href="https://github.com/adebayo-moses/elara"
              target="blank"
              >Github</a
            >
          </li>
          <li class="nav-item hover-underline-animation">
            <a
              class="nav-link active"
              aria-current="page"
              href="https://www.linkedin.com/in/adebayo-moses/"
              target="blank"
              >LinkedIn</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!--Nav-->
  <!--Hero section-->
  <section class="hero vh-100 d-flex align-items-center bg-image">
    <div class="container">
      <div class="row">
        <div class="mx-auto text-center">
          <h1 class="display-5 text-typing">
            <span class="greet"
              ><span class="hello_msg"
                >Hello there! I am <span class="namee">Elara</span>.</span
              >
            </span>
          </h1>
        </div>
      </div>
    </div>
    <!--arrow-->
    <a href="#scroll-down" class="hero_scroll-btn">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="25"
        height="25"
        fill="currentColor"
        class="bi bi-arrow-down-circle"
        viewBox="0 0 16 16"
      >
        <path
          fill-rule="evenodd"
          d="M1 8a7 7 0 1 0 14 0A7 7 0 0 0 1 8zm15 0A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v5.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V4.5z"
        ></path>
      </svg>
    </a>
  </section>
  <a href="#scroll-down" class="hero_scroll-btn"> <!--Hero finish--> </a
  ><a id="scroll-down"></a>
  <!--About me-->

  <section class="abt container-custom vh-100">
    <div class="row ah">
      <div class="=col-12 col-sm-6 align-self-center">
        <div class="abt_content-width">
          <h1 class="h2 mb-4">about me</h1>
          <p class="mb-4">
            <span class="hello_msg"
              >Hhi everyone <span class="slash"></span> hello world,</span
            >, I'm been built by this geek namely
            <a
              class="kepler"
              href="https://twitter.com/mosessmax/"
              target="_blanck"
              >mosessmax</a
            >
            and currently work as a
            <span class="ds"> Software developer</span>, while pursuing a
            computer science degree. <br />I am also familiar with<span>
              Elara is a personal assistant powered by OPEN AI, and some efizzy
              that alllows it to serve as a peraonal assistant to you, it's
              starting on the web right now but coming soon to your PC because
              tha's where it's meant to be. just spare me 0.3 inches of your
              laptop..</span
            >
          </p>
        </div>
      </div>
      <div class="col-12 col-sm-6 d-md-flex justify-content-md-center">
        <img
          src="@/assets/elara-demo.png"
          alt="elara"
          width="450"
          height="450"
          loading="lazy"
          class="img-fluid pb-4 abt_section-thumbnail floating"
        />
      </div>
    </div>
  </section>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<script setup>
document.documentElement.classList.remove("no-js");
document.documentElement.classList.add("js");
</script>
