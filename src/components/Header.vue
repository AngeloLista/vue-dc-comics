<template>
  <header>
    <div class="container d-flex-j-between">
      <figure>
        <img src="../assets/img/dc-logo.png" alt="Logo DC" />
      </figure>

      <nav>
        <ul>
          <li><a href="#">PROVA</a></li>
          <li><a href="#">PROVA</a></li>
          <li><a href="#">PROVA</a></li>
          <li><a href="#">PROVA</a></li>
          <li><a href="#">PROVA</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
figure {
  display: inline-block;
}

.d-flex-j-between {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul,
ul li {
  display: inline-block;
}
</style>