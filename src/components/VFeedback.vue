<script setup>

</script>

<template>
<section class="feedback">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-xl-6">
            <div class="feedback__text">
              <h2>Есть пожелания? <br> Или появились вопросы?</h2>
              <p>Оставьте нам ваши контакты и мы обязательно с вами свяжемся</p>
            </div>
          </div>
          <div class="col-lg-9 col-xl-6">
            <form class="form">
              <label class="mb-3">
                                <textarea placeholder="Введите ваш вопрос"
                                          title="Ваш вопрос"
                                          required
                                ></textarea>
              </label>
              <div class="form__group">
                <label>
                  <input type="text"
                         placeholder="Ваше имя"
                         title="Ваше имя"
                         required
                  />
                </label>
                <label>
                  <input type="tel"
                         placeholder="+7(___)___-____"
                         pattern="[0-9]{11}"
                         maxlength="11"
                         title="Номер телефона"
                         required
                  />
                </label>
                <label>
                  <input type="email"
                         placeholder="Электронная почта"
                         title="Электронная почта"
                         required
                  />
                </label>
              </div>
              <button class="button-primary" type="submit">Отправить</button>
            </form>
          </div>
        </div>
      </div>
    </section>
</template>
<style scoped>

</style>