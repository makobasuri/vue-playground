<template>
  <header>
    <a href="#">Link</a>
    <a href="#">Link</a>
    <div class="logo-wrapper">
      <svg class="logo"></svg>
    </div>
    <a href="#">Link</a>
    <a href="#">Link</a>
  </header>
</template>

<style scoped>

  header {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 80px;
    width: 100%;
    background-color: darkslategrey;
    box-shadow: 4px 4px 10px -2px rgba(0, 0, 0, 0.4);
  }

  .logo-wrapper {
    margin: 24px;
    width: 100px;
    height: 100px;
    transform-origin: 50%, 50%;
    transform: rotate(45deg);
    background-color: darkslategrey;
    box-shadow: 4px 4px 20px -4px rgba(0, 0, 0, 0.4);
  }

  .logo {
    width: 100%;
    transform-origin: 50%, 50%;
    transform: rotate(-45deg);
  }

  a {
    display: flex;
    flex-direction: column;
    justify-content: center;
    border: 4px solid transparent;
    min-width: 128px;
    height: 100%;
    letter-spacing: 1px;
    color: aliceblue;
  }

  a:focus {
    border-bottom: 4px solid white;
  }

</style>
