<template>
  <div>
    <div class="container">
      <h1>Hellenic Air Force unofficial website</h1>
      <p class="lead fst-italic">-"The best airforce in NATO"</p>
      <video
        src="../assets/videos/haf-promo.mp4"
        type="video/webm"
        autoplay="true"
        muted
        loop
        class="rounded border border-2"
        style="width: 100%; height: 100%; opacity: 0.8"
      ></video>
      <hr class="my-4" />
      <h2 class="mb-3">
        HAF, 114 Combat Wing and 332 Squadron welcome the first 6 Rafale F3R
        fighters
      </h2>
      <div
        id="carouselIndicators"
        class="carousel carousel-dark slide rounded border border-2"
        data-bs-ride="carousel"
      >
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#carouselIndicators"
            data-bs-slide-to="0"
            class="active"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselIndicators"
            data-bs-slide-to="1"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselIndicators"
            data-bs-slide-to="2"
          ></button>
        </div>
        <div class="carousel-inner rounded">
          <div class="carousel-item rounded active">
            <img
              src="../assets/images/rafale-1.jpg"
              class="d-block w-100"
              alt="rafale water salute"
            />
          </div>
          <div class="carousel-item rounded">
            <img
              src="../assets/images/rafale-3.jpg"
              class="d-block w-100"
              alt="rafale flying over Athens"
            />
          </div>
          <div class="carousel-item">
            <img
              src="../assets/images/rafale-2.jpg"
              class="d-block w-100"
              alt="rafale 114 combat wing patch"
            />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselIndicators"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselIndicators"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <a
        href="https://www.youtube.com/watch?v=8jVLQFu5H4Q"
        target="_blank"
        class="text-white mt-3"
        >watch the full ceremony</a
      >
    </div>
  </div>
</template>

<script>
export default {
  loading: {
    color: "blue",
    height: "5px",
  },
};
</script>
