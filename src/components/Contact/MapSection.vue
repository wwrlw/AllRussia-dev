<template>
 <div>
   <h2 class="maps__title">Мы на карте:</h2>
   <div class="maps container">
     <div ref="map" style="width: 800px; height: 442px"></div>
   </div>
 </div>
</template>

<script>
export default {
  mounted() {
    this.loadMap();
  },
  methods: {
    loadMap() {
      const ymaps = window.ymaps;

      ymaps.ready(() => {
        const map = new ymaps.Map(this.$refs.map, {
          center: [55.753215, 37.622504], // Координаты центра карты (Москва)
          zoom: 10, // Уровень масштабирования
        });

        // Добавление маркера на карту
        const marker = new ymaps.Placemark([55.741926, 37.524372], {
          hintContent: 'Москва',
          balloonContent: 'Столица России',
        });

        map.geoObjects.add(marker);
      });
    },
  },
};
</script>

<style scoped>
.maps {
  display: flex;

}
</style>
