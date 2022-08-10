<template>
  <header>
    <div class="red"></div>
    <main>
      <div class="logo">
        <img src="flogo.png" alt="" />
      </div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><a href="#">Services</a></li>
      </ul>
    </main>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  height: 21vh;
  /* height: 5.46vh; */
  width: 100%;
  display: flex;
  flex-direction: column;
}
.red {
  width: 100%;
  height: 26%;
  /* height: 100%; */
  background-color: var(--red);
}
main {
  width: 100%;
  padding-left: 11.8%;
  padding-right: 13.5%;
  height: 74%;
  display: flex;
}
.logo {
  height: 100%;
  width: 45.5%;
  display: flex;
  align-items: center;
  padding-left: 2%;
  border: 1px solid var(--grey);
}
.logo img {
  width: 37%;
  height: 65%;
}
ul {
  width: 54.5%;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border: 1px solid var(--grey);
  border-left: 0;
  padding: 2%;
}
li {
  font-size: 0.7rem;
  font-weight: 500;
}
a {
  color: rgb(145, 145, 145);
}
</style>
