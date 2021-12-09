<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="/"
        ><img
          src="@/assets/images/haf-logo.png"
          class="user-select-none mb-1"
          style="height: 1em"
          alt="logo"
        />
        {{ brand }}</a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbar">
        <ul class="navbar-nav">
          <li class="nav-item">
            <NuxtLink to="/" class="nav-link">Home</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink to="/fleet" class="nav-link">Fleet</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink to="/arsenal" class="nav-link">Arsenal</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: {
    brand: String,
  },
};
</script>
