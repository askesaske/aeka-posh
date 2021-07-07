<template>
  <main class="main">

    <section class="main__section welcome-section">

      <div class="welcome-section__container">

        <div class="welcome-section__row">
          <img src="../assets/img/icons/logo.svg" alt="" class="welcome-section__logo">

          <div class="welcome-section__phone-box">

            <a href="https://wa.me/77765023636">
              <svg height="24" width="24">
                <use href="../assets/img/icons.svg#wpp"></use>
              </svg>
            </a>

            <a href="tel: +7 (776) 502 36 36">
              <svg height="24" width="24">
                <use href="../assets/img/icons.svg#phone"></use>
              </svg>
            </a>

            <a href="tel: +7 (776) 502 36 36" class="welcome-section__phone-link">+7 776 502 36 36</a>
          </div>
        </div>

        <div class="welcome-section__info">

          <div class="welcome-section__title">
            Авторский курс <br>
            “Beauty formula”
          </div>

          <div class="welcome-section__subtitle">
            Подчеркни свою красоту
          </div>

          <button class="welcome-section__btn button" v-scroll-to="{el: '#buy', duration: 700}">
            Купить курс
            <svg width="34" height="17">
              <use href="../assets/img/icons.svg#arrow"></use>
            </svg>
          </button>
        </div>

        <div class="welcome-section__socials">
          <a href="#" class="welcome-section__social">
            <svg width="24" height="24">
              <use href="../assets/img/icons.svg#inst"></use>
            </svg>
          </a>

          <a href="#" class="welcome-section__social">
            <svg width="24" height="24">
              <use href="../assets/img/icons.svg#youtube"></use>
            </svg>
          </a>

          <a href="#" class="welcome-section__social">
            <svg width="24" height="24">
              <use href="../assets/img/icons.svg#tg"></use>
            </svg>
          </a>

          <a href="#" class="welcome-section__social">
            <svg width="24" height="25">
              <use href="../assets/img/icons.svg#fb"></use>
            </svg>
          </a>
        </div>

        <img src="../assets/img/main-person.png" alt="" class="welcome-section__img">

      </div>

    </section>

    <section class="main__section about-section">

      <div class="about-section__container">
        <h2 class="about-section__heading heading-medium">
          Об авторе
        </h2>

        <div class="about-section__row">

          <img src="../assets/img/about-img2.png" alt="" class="about-section__img about-section__img--mobile">

          <div class="about-section__info">
            Привет, я <span>Айым Алтынбекова.</span>
            Я профессиональный практикующий визажист, через мои авторские курсы прошли более несколько тысячи девушек,
            которые открыли для себя профессию визажист.
            Я автор данного курса <span>“Beauty formula”</span> по визажу для себя!
            <br><br>

            <span class="about-section__italic">Сияй вместе с моей формулой красоты💫</span>

            <button class="about-section__btn button button--tr" v-scroll-to="{el: '#program', duration: 700}">
              Что входит?
              <svg width="34" height="17">
                <use href="../assets/img/icons.svg#arrow"></use>
              </svg>
            </button>
          </div>

          <img src="../assets/img/about-img.png" alt="" class="about-section__img about-section__img--desktop">

        </div>

      </div>

    </section>

    <section class="main__section program-section" id="program">
      <div class="program-section__container">

        <h2 class="program-section__heading heading-medium">
          Программа курса <br> “Beauty formula”
        </h2>

        <div class="program-section__grid">

          <div class="program-section__card">
            <div class="program-section__title">
              День первый:
            </div>

            <div class="program-section__text">
              1. Организация <br class="program-section__mobile-space">
              пространства <br>
              2. Обзор кистей <br>
              3. Разбор текстур, обзор <br>
              кремовых сухих теней
            </div>
          </div>

          <div class="program-section__card">
            <div class="program-section__title">
              День второй:
            </div>

            <div class="program-section__text">
              1. Уход, подготовка кожи к <br>
              макияжу <br>
              2. Брови <br>
              3. Тонирование, тон
            </div>
          </div>

          <div class="program-section__card">
            <div class="program-section__title">
              День третий:
            </div>

            <div class="program-section__text">
              Нюдовый макияж <br>
              (показ и отработка на <br class="program-section__mobile-space">
              моделях, <br class="program-section__mobile-space program-section__mobile-space--show"> сухая - кремовая
              <br class="program-section__mobile-space">
              коррекция)
            </div>
          </div>

          <div class="program-section__card">
            <div class="program-section__title">
              День четвёртый:
            </div>

            <div class="program-section__text">
              Возрастной лифтинг макияж <br>
              (накладные ресницы, <br class="program-section__mobile-space">
              кремовые <br class="program-section__mobile-space program-section__mobile-space--show"> тени, <br
              class="program-section__mobile-space">
              кремовая коррекция)
            </div>
          </div>

          <div class="program-section__card">
            <div class="program-section__title">
              День пятый:
            </div>

            <div class="program-section__text">
              Пигментный макияж <br>
              (работа с яркими тенями, <br>
              объемные ресницы - <br class="program-section__mobile-space">
              кукольный <br class="program-section__mobile-space program-section__mobile-space--show"> взгляд, омбре <br
              class="program-section__mobile-space">
              губы, зона <br class="program-section__mobile-space program-section__mobile-space--show"> декольте)
            </div>
          </div>

          <button class="program-section__btn button button--tr" v-scroll-to="{el: '#buy', duration: 700}">
            Купить курс
            <svg width="34" height="17">
              <use href="../assets/img/icons.svg#arrow"></use>
            </svg>
          </button>
        </div>
      </div>
    </section>

    <section class="main__section bonus-section">

      <div class="bonus-section__container">
        <h2 class="bonus-section__heading heading-medium">
          Бонусы и подарки <span>к курсу</span>
        </h2>

        <div class="bonus-section__row">

          <div class="bonus-section__card">
            <div class="bonus-section__title">
              Бонусы:
            </div>

            <div class="bonus-section__text">
              + Beauty шпаргалка <br>
              + Гайд про кисти <br>
              + Гайд про декоративную косметику <br>
              (проф, люкс, масс-маркет)
            </div>
          </div>

          <div class="bonus-section__card">
            <div class="bonus-section__title">
              Подарки:
            </div>

            <div class="bonus-section__text">
              + Сертификат на обучение <br>
              базовому курсу от Аеки Пош! <br>
              + Бьюти боксы с полным набором <br>
              декоративной косметики!
            </div>
          </div>

        </div>
      </div>

    </section>

    <section class="main__section faq-section">

      <div class="faq-section__container">

        <h2 class="faq-section__heading heading-medium">
          Вопросы - ответы
        </h2>

        <div class="faq-section__list">

          <transition-group>

            <div class="faq-section__item"
                 v-for="(q, i) in faqRU"
                 :key="q.title"
                 :class="{'faq-section__item--active' : q.show}"
                 @click="toggleRU(i)"
            >

              <div class="faq-section__row">

                <div class="faq-section__title" v-html="q.title"></div>

                <svg class="faq-section__icon"
                     width="24px"
                     height="24px"
                     :class="{'faq-section__icon--active' : q.show}"
                >
                  <use href="../assets/img/icons.svg#chevron"></use>
                </svg>

              </div>

              <div class="faq-section__text" v-show="q.show" v-html="q.text"></div>

            </div>

          </transition-group>

        </div>
      </div>

    </section>

    <section class="main__section buy-section" id="buy">
      <div class="buy-section__container">

        <h2 class="buy-section__heading heading-medium">
          Купить курс по макияжу для себя
        </h2>

        <div class="buy-section__box buy-section__box--desktop">

          <div class="buy-section__left">
            <div class="buy-section__price">
              <p>Стоимость курса:</p>
              <span>6200 тенге</span>
            </div>

            <label class="buy-section__label">
              <input type="checkbox" class="buy-section__checkbox">
              <span class="buy-section__checkmark"></span>
              <span>Я соглашаюсь с условиями оферты</span>
            </label>

            <button class="buy-section__btn button button--tr">
              Выслать чек об оплате
              <svg width="34" height="17">
                <use href="../assets/img/icons.svg#arrow"></use>
              </svg>
            </button>

            <button class="buy-section__btn button button--tr">
              Задать вопрос
              <svg width="34" height="17">
                <use href="../assets/img/icons.svg#arrow"></use>
              </svg>
            </button>
          </div>

          <div class="buy-section__right">

            <p class="buy-section__title">
              Как произвести оплату?
            </p>

            <div class="buy-section__text">
              Оплату производить на карту <br>
              <span>4400 4301 4236 6233</span> <br><br>

              Или по номеру телефона <br>
              <span>8 707 202 36 36 (KASPI)</span> <br><br>

              Обязательно скинуть <span>чек об оплате</span> и <br>
              название вашего <span>Инстаграм аккаунта</span> на <br>
              <span>WhatsApp +7 776 502 36 36</span> <br><br>

              По всем другим вопросам переходить на <br>
              <span>WhatsApp</span>
            </div>

            <img src="../assets/img/kaspi.png" alt="" class="buy-section__img">
          </div>

        </div>

        <div class="buy-section__box buy-section__box--mobile">

          <div class="buy-section__price">
            <p>Стоимость курса:</p>
            <span>6200 тенге</span>
          </div>

          <p class="buy-section__title">
            Как произвести оплату?
          </p>

          <img src="../assets/img/kaspi.png" alt="" class="buy-section__img">

          <div class="buy-section__text">
            Оплату производить на карту <br>
            <span>4400 4301 4236 6233</span> <br><br>

            Или по номеру телефона <br>
            <span>8 707 202 36 36 (KASPI)</span> <br><br>

            Обязательно скинуть <span>чек об оплате</span> и <br>
            название вашего <span>Инстаграм аккаунта</span> на <br>
            <span>WhatsApp +7 776 502 36 36</span> <br><br>

            По всем другим вопросам переходить на <br>
            <span>WhatsApp</span>
          </div>

          <label class="buy-section__label">
            <input type="checkbox" class="buy-section__checkbox">
            <span class="buy-section__checkmark"></span>
            <span>Я соглашаюсь с условиями оферты</span>
          </label>

          <button class="buy-section__btn button button--tr" @click="goWpp">
            Выслать чек об оплате
            <svg width="34" height="17">
              <use href="../assets/img/icons.svg#arrow"></use>
            </svg>
          </button>

          <button class="buy-section__btn button button--tr" @click="goWpp">
            Задать вопрос
            <svg width="34" height="17">
              <use href="../assets/img/icons.svg#arrow"></use>
            </svg>
          </button>

        </div>

      </div>

    </section>

    <button class="buy-now" v-scroll-to="{el: '#buy', duration: 700}">
      Купить курс
    </button>

  </main>
</template>

<script>
export default {
  data() {
    return {
      faqRU: [
        {
          show: false,
          title: "Кому подходит данный курс?",
          text: "Женщина в любом возрасте должна быть красивой и привлекательной. Курс подходит абсолютно всем тем, кто хочет научиться правильно красить себя, будь вам лет 16 или же 60.",
        },
        {
          show: false,
          title: "Как проходит оплата?",
          text: "Для вашего удобства мы принимаем оплату онлайн переводом Kaspi.kz по данным указным выше на этом сайте. После перевода вам лишь нужно отправить развёрнутый скрин квитанции по номеру 8776 502 3636 (можно нажать на иконку WhatsApp на этой странице). Для других стран, также переходить на WhatsApp!",
        },
        {
          show: false,
          title: "Сколько по времени будет открыт доступ ко всем материалам?",
          text: "Все видео уроки будут публиковаться на закрытой странице в Инстаграм. Доступ на страницу ровно месяц.",
        },
      ],
    };
  },
  methods: {
    toggleRU(index) {
      this.faqRU[index].show = !this.faqRU[index].show;
      for (let i = 0; i < this.faqRU.length; i++) {
        if (this.faqRU[i] !== this.faqRU[index]) {
          this.faqRU[i].show = false;
        }
      }
    },
    goWpp() {
      window.open('https://wa.me/message/QGQGYLGDBLRVC1', '_blank');
    }
  }
}
</script>

<style>

</style>
