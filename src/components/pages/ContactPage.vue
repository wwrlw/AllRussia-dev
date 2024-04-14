<template>
    <div>
        <div class="container">
            <div class="contact">
                <span class="red-line"></span>
                <p class="contact__headding">Контакты</p>
                <p class="contact__text">Фактический адрес: 121170, г.Москва, Кутузовский проспект 36, стр.7Б, Метро "Кутузовская" или "Парк Победы"</p>
                <p class="contact__text">Адрес для корреспонденции: 121170, г.Москва, Кутузовский пр.,36,стр.7Б (Муса АЖ) </p>
                <p class="contact__text contact__text-underline">E-mail: info@allrussia.info</p>
                <p class="contact__text">Телефоны: +7 (495) 784-73-55; +7 (926) 393-40-64</p>
            </div>
          <MapSection/>
          <NavigateComponent/>
        </div>
    </div>
</template>

<script>
  import MapSection from "@/components/Contact/MapSection.vue";
  import NavigateComponent from "@/components/layouts/NavigateComponent.vue";
  import {defineComponent} from "vue";
  export default defineComponent({
    components: { MapSection, NavigateComponent}
  })

</script>

<style class="scoped">

.container {
    max-width: 1440px;
    margin: 0 auto;
}

.contact{
    border-top: 1px solid #AAAAAA;
}

.red-line{
    display: block;
    width: 80px;
    height: 13px;
    background-color: #aa0000;
}

.contact__headding{
    text-transform: uppercase;
}

</style>