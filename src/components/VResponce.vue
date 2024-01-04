<script setup>
const responce = [
  {
    img: {
      src: '/chan.png',
      alt: 'Chan'
    },
    name: 'Чан'
  },
  {
    img: {
      src: '/mangal.png',
      alt: 'mangal'
    },
    name: 'Мангал'
  },
  {
    img: {
      src: '/povar.png',
      alt: 'povar'
    },
    name: 'Личный шеф-повар'
  },
  {
    img: {
      src: '/holiday.png',
      alt: 'holiday'
    },
    name: 'Праздничное оформление'
  }

]
</script>

<template>
<section class="tech">
      <div class="container">
        <h2>
          Дополнительные услуги
        </h2>
        <div class="row">
          <div class="col-6 col-md-4 col-lg-3"
               v-for="(item, index) in responce"
               :key="index"
          >
            <div class="tech__card">
              <div class="tech__card-img-wrap">
                <img :src="item.img.src" :alt="item.img.alt">
              </div>
              <div class="tech__card-name">{{item.name}}</div>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>

<style scoped>

</style>