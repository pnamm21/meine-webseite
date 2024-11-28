<template>
  <header class="main-header">
    <nav class="navigation">
      <!-- <div class="logo">
        <img src="">
      </div> -->
      <ul class="nav-links">
        <li><a href="#ueber-mich">Über mich</a></li>
        <li><a href="#themen">Themen</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "MainHeader",
};
</script>

<style scoped>
.main-header {
  background-color: #f4f4f4;
  color: rgb(255, 255, 255);
  padding: 20px;
  text-align: center;
}

.navigation {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* .logo img {
  width: 100%;
  height: 70px;
} */

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.nav-links li {
  display: inline;
}

.nav-links a {
  color: #535353;
  text-decoration: none;
  font-size: 18px;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #f4a261;
}
</style>
