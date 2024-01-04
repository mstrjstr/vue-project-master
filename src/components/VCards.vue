<script setup>
const house = [
  {
    img: {
      src: '/A-frame.jpeg',
      alt: 'A-frame'
    },
    link: {
      href: '#',
      title: 'Уютный А-фрейм'
    },
    description: 'Идеально подойдет чтобы уединиться'
  },
  {
    img: {
      src: '/first.jpg',
      alt: 'House'
    },
    link: {
      href: '#',
      title: 'Двухэтажный коттедж'
    },
    description: 'Подойдет для отдыха компанией'
  },
  {
    img: {
      src: '/somedom.jpg',
      alt: 'house'
    },
    link: {
      href: '#',
      title: 'Двухэтажный домик в лесу'
    },
    description: 'Чтобы спрятаться от городского шума'
  },
  {
    img: {
      src: '/winter.jpg',
      alt: 'winter'
    },
    link: {
      href: '#',
      title: 'Домик на горнолыжном курорте'
    },
    description: 'Для идеального вечера'
  },
  {
    img: {
      src: '/srub.jpg',
      alt: 'srub'
    },
    link: {
      href: '#',
      title: 'Дом из сруба'
    },
    description: 'Как у бабушки'
  },
  {
    img: {
      src: '/dorogo_bogato.jpg',
      alt: 'milliondeneg'
    },
    link: {
      href: '#',
      title: 'Роскошная вилла на берегу моря'
    },
    description: 'Позвольте себе окунуться в мир роскоши и комфорта'
  },
  {
    img: {
      src: '/caption.jpg',
      alt: 'kupets'
    },
    link: {
      href: '#',
      title: 'Настоящий купеческий дом'
    },
    description: 'Хранит в себе множество тайн и историй'
  },
  {
    img: {
      src: '/cyprus.jpeg',
      alt: 'cyprus'
    },
    link: {
      href: '#',
      title: 'Коттедж на Кипре'
    },
    description: 'Откройте для себя остров с тысячелетней историей'
  },
    {
    img: {
      src: '/WIP.png',
      alt: 'WIP'
    },
    link: {
      href: '#',
      title: 'Скоро здесь что-то будет'
    },
    description: 'Мы ищем для вас все больше новых предложений'
  }

]
</script>

<template>
  <section class="projects">
    <div class="container">
      <h2>
        Актуальные предложения
      </h2>
      <div class="row">
        <div class="col-sm-6 col-lg-4"
             v-for="(item, index) in house"
             :key="index"
        >
          <div class="projects__card">
            <img :src="item.img.src"
                 :alt="item.img.alt"
            >
            <a :href="item.link.href">{{ item.link.title }}</a>
            <p>{{ item.description }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>