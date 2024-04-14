<template>
  <div>
    <div class="horizontal-line"></div>
    <div class="red-rectangle"></div>
    <div class="navigate_list">
      <ul class="navigate_list-main list">
        <li class="navigate_logo">ALLRUSSIA</li>
        <li><a href="/">О ПОРТАЛЕ</a></li>
        <li><a href="/">ПАРТНЕРЫ</a></li>
        <li><a href="/">КОНТАКТЫ</a></li>
        <li><a href="/">ПРОЕКТЫ</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentPage: ''
    };
  },
  watch: {
    '$route'(to) {
      this.currentPage = to.name;
    }
  },
  created() {
    this.currentPage = this.$route.name;
  }
};
</script>

<style scoped>
.active {
  color: red;
}

.red-rectangle {
  width: 69px; /* ширина прямоугольника */
  height: 8px; /* высота прямоугольника */
  background-color: #AA0000; /* цвет фона прямоугольника */
  margin-bottom: 10px;
}
.horizontal-line {
  height: 1px;
  width: 100%;
  background-color: #000;
  margin: 0 auto;
}
 li {
   display: flex;
   align-items: center;
   list-style-type: none;
 }
 a {
   text-decoration: none;
   color: #000000;
 }
 .navigate_list-main {
   margin: 0;
   padding: 0;
 }
 .navigate_logo {
   font-size: 24px;
   font-weight: bold;
 }

</style>