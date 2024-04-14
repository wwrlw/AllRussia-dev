<script>
export default {
  name: "mainTheme"
}
</script>

<template>
  <div >
    <div class="horizontal-line"></div>
    <div class="red-rectangle"></div>
    <h3 >ТЕМЫ</h3>
    <div class="container">
      <div class="item item_1">
        <h2>СПОРТ</h2>
        <img src="../../assets/rapper.png" alt="12">
        <p class="item_2-subtitle">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </p>
        <div class="diviver"></div>
        <p class="item_2-list">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </p>
        <div class="diviver"></div>
        <p class="item_2-list">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </p>
        <div class="diviver"></div>
        <p class="item_2-list">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
        </p>

      </div>
      <div class="item item_2">
        <h2>ТУРИЗМ</h2>
          <img src="../../assets/brige.png" alt="12">
            <p class="item_2-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
      </div>
      <div class="item item_3">
        <h2>ПАРТНЕРЫ</h2>
          <img src="../../assets/islam.png" alt="12">
            <p class="item_2-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
      </div>
      <div class="item item_4">
        <h2>ПРОЕКТЫ</h2>
          <img src="../../assets/september11.png" alt="12">
            <p class="item_2-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
            <div class="diviver"></div>
            <p class="item_2-list">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do.
            </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  max-width: 1440px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: 357px;
  padding-bottom: 300px;
}
h3 {
  font-size: 24px;
  font-weight: 500;
}

.horizontal-line {
  height: 0.3px;
  opacity: 0.4;
  width: 1440px;
  background-color: #000;
  margin: 0 auto;
}

.red-rectangle {
  width: 69px; /* ширина прямоугольника */
  height: 8px; /* высота прямоугольника */
  background-color: #AA0000; /* цвет фона прямоугольника */
  margin-bottom: 10px;
}
.diviver {
  height: 1px;
  width: 90%;
  margin-left: 5px;
  background-color: black;
}
.item_2-subtitle {
  font-family: "Roboto Condensed", sans-serif;
  font-size: 20px;
  font-weight: bold;
  width: 345px;
}
.item_2-list {
  width: 345px;
}

</style>