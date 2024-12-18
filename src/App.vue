<template>
  <header>
    <div class="logo__header">
      <img class="logo__img" src="./assets/logo.png" alt="">
      <div class="logo__text">
        <h1>Унитарное предприятие</h1>
        <h1>ПРОФЕССИОНАЛЬНЫЙ БУХГАЛТЕР</h1>
      </div>
    </div>
    <div class="ref">
      <a class="ref__header" href="">Главная</a>
      <a class="ref__header" href="">О компании</a>
      <a class="ref__header" href="">Контакты</a>
    </div>
  </header>
  <div class="header2">
    <img src="./assets/logo.png" alt="">
    <div class="hamburger">
      <input type="checkbox" id="hmtoggler">
      <label for="hmtoggler"></label>
      <div class="hamburger__refs">
        <a class="hamburger__ref" href="">Главная</a>
        <a class="hamburger__ref" href="">О компании</a>
        <a class="hamburger__ref" href="">Контакты</a>
      </div>
    </div>
    
  </div>
  
  <PromoItem></PromoItem>
  <div class="about_company">
    <p>О компании</p>
    <p>УП «Профессиональный бухгалтер» — ведущая компания в Республике Беларусь, специализирующаяся на подготовке квалифицированных бухгалтеров для малого бизнеса и повышении квалификации специалистов. Мы гордимся тем, что являемся партнёрами «Белорусской ассоциации бухгалтеров», что позволяет нам проводить обучение и выдавать сертификаты профессионального бухгалтера в Минске, Гомеле, Могилеве и Гродно.</p>
    <div class="company_cards">
      <div class="company_card">
        <img src="./assets/book.png" alt="">
        <p>Мы используем новейшие системы бухгалтерского учета и налогообложения, а также выпустили более 100 пособий, что позволяет сократить время обучения до 2-3 месяцев</p>
      </div>
      <div class="company_card">
        <img src="./assets/mans.png"  alt="">
        <p>Наши семинары по бухгалтерскому учету и налогообложению посещают главные бухгалтеры государственных и частных предприятий</p>
      </div>
      <div class="company_card">
        <img src="./assets/paint.png" alt="">
        <p>Более 35,000 бухгалтеров и 10,000 главных бухгалтеров подготовлено за 30 лет работы</p>
      </div>
    </div>
  </div>
  <div class="employees">
    <div class="employees__cap">
      <p>Офисы</p>
      <p class="employees__cap__mode">Режим работы</p>
      <p>Контакты</p>
    </div>
    <div class="employees__row">
      <p>Профессиональный бухгалтер<br>г. Гомель</p>
      <p class="employees__row__middle">пн-пт: 10:00 - 15:00</p>
      <p>(029) 643-40-07</p>
    </div>
    <div class="employees__row">
      <p>ИП Козловская Т.Н.<br>г. Могилев</p>
      <p class="employees__row__middle">пн-пт: 10:00 - 18:00</p>
      <p>(029) 345-10-45</p>
    </div>
    <div class="employees__row">
      <p>ИП Карпунина О.П.<br>г. Брест</p>
      <p class="employees__row__middle">пн-пт: 09:00 - 18:00</p>
      <p>(029) 728-21-63</p>
    </div>
    <div class="employees__row">
      <p>ИП Остапченя<br>г. Гродно</p>
      <p class="employees__row__middle">пн-пт: 09:00 - 18:00</p>
      <p>(029) 619-52-51</p>
    </div>
    <div class="employees__row">
      <p>ЧУП «ХартМикс»<br>г. Бобруйск</p>
      <p class="employees__row__middle">пн-пт: 09:00 - 18:00</p>
      <p>(044) 797-48-22</p>
    </div>
    <div class="employees__row">
      <p>Бухгалтерское бюро «Филин»<br>г. Минск</p>
      <p class="employees__row__middle">пн-пт: 09:00 - 18:00</p>
      <p>(017) 328-18-93,<br>(029) 889-21-27,<br>(029) 655-07-87</p>
    </div>
    <div class="employees__row">
      <p>ЧП «Тимус Технологии»<br>г. Минск</p>
      <p class="employees__row__middle">пн-пт: 09:00 - 18:00</p>
      <p>8 029 177-55-00</p>
    </div>

  </div>
  <div class="contacts">
    <div class="contacts__adress">
      <p>Наш адрес</p>
      <p><b>Почтовый адрес:</b> 220005, г. Минск, ул. Смолячкова, 9 (офис 432), а/я 22</p>
    </div>
    <div class="contacts__phone">
      <p>Телефоны</p>
      <p><b>Тел./факс:</b> (017) 396-80-80</p>
      <p>c 09:00 до 18:00 (понедельник – пятница)<br> <br></p>
      <p>+375 44 765-80-10 (А1)</p>
      <p>+375 29 565-80-10 (МТС)</p>
      <p>+375 17 396-80-10 (гор.)</p>
      <p>c 09:00 до 18:00 (понедельник – пятница)</p>
      <p><b>E-mail:</b> info@service-lux.by</p>
    </div>
    <div class="contacts__contact">
      <p>Свяжитесь с нами</p>
      <p>Для связи с нами заполните, пожалуйста, форму обратной связи:</p>
      <input type="text" value="Имя">
      <input type="email" value="Email">
      <textarea>Сообщение</textarea>
      <button>Отправить</button>
    </div>
  </div>
  <footer>
    <div class="footer__ref">
      <a href="">Главная</a>
      <a href="">О компании</a>
      <a href="">Контакты</a>
    </div>
    <div class="footer__contact">
      <p>с 9:00 до 18:00:<br>+375 44 765-80-10 (А1)<br>+375 29 565-80-10 (МТС)<br>+375 17 396-80-10 (гор.)</p>
      <p>© ПРОФЕССИОНАЛЬНЫЙ БУХГАЛТЕР, 2003-2021</p>
    </div>
  </footer>
</template>
<script>
import PromoItem from './components/PromoItem.vue';
export default {
  name: 'App',
  components: {
    PromoItem,
  }
}
</script>

<style>
@media screen and (max-width: 2440px) {
  header {
    display: flex;
  }
  .ref {
    width: 40%;
    display: flex;
    justify-content: space-between;
  }
  .company_cards {
    padding-top: 8%;
    display: flex;
    justify-content: space-between;
  }
  .company_card {
    max-width: 25%;
  }
  .company_card img {
    margin-bottom: 10%;
  }
  .employees__cap {
    font: bold 11pt Verdana, sans-serif;
    display: flex;
    text-align: left;
  }
  .employees__row {
    align-items: center;
    margin-top: 2%;
    margin-bottom: 2%;
    display: flex;
    justify-content: space-between;
    text-align: left;
  }
  .employees__row p:first-child {
    width: 45%;
  }
  .employees__row__middle {
    width: 35%;
  }
  .employees__row p:last-child {
    width: 20%;
  }
  button {
    width: 50%;
  }
  .contacts__contact input, .contacts__contact textarea {
    width: 50%;
  }
  footer {
    flex-direction: row;
  }
  .footer__ref {
    justify-content: space-between;
  }
  .footer__ref a {
    margin-bottom: 20%;
  }
  .hamburger {
    display: none;
  }
  .header2 {
    display: none;
  }
}
@media screen and (max-width: 780px) {
  header {
    display: none;
    flex-direction: row;
    flex-wrap: wrap;
  }
  .logo__header {
    justify-content: center;
    padding-bottom: 4%;
  }
  .ref {
    width: 100%;
    display: flex;
    justify-content: space-around;
  }
  .company_cards {
    padding-top: 8%;
    display: flex;
    flex-direction: column;
  }
  .company_card {
    max-width: 100%;
    margin-bottom: 15%;
  }
  .company_card img {
    margin-bottom: 5%;
  }
  .employees {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  .employees__cap {
    display: none;
  }
  .employees__row {
    width: 110pt;
    align-items: center;
    margin-top: 0%;
    margin-bottom: 2%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: left;
  }
  .employees__row p:first-child {
    width: 100%;
    padding-bottom: 4%;
  }
  .employees__row__middle {
    width: 100%;
    padding-bottom: 4%;
  }
  .employees__row p:last-child {
    width: 100%;
    padding-bottom: 10%;
  }
  button {
    width: 100%;
  }
  .contacts__contact input, .contacts__contact textarea {
    width: 100%;
  }
  footer {
    flex-direction: column;
  }
  .hamburger {
    display: flex;
  }
  .header2 {
    display: flex;
  }
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  margin: 0%;
  padding: 0%
}
header {
  background-color: #EB781D;
  justify-content: space-around;
  padding-top: 4%;
  padding-bottom: 4%;
}
.logo__img {
  width: 100px;
  height: 70px;
}
.logo__header {
  display: flex;
}
.ref__header {
  margin-top: 16pt;
}
.ref__header:link, .ref__header:visited {
  text-decoration: none;
  font: bold 11pt Verdana, sans-serif;
  color: white;
}
.ref__header:active, .ref__header:hover {
  text-decoration: none;
  font: bold 11pt Verdana, sans-serif;
  color: white;
}
.logo__text h1:first-child {
  font: bold 9pt Verdana, sans-serif;
  color: #1A26BE;
}
.logo__text h1:last-child {
  font: bold 10pt Verdana, sans-serif;
  color: white;
}
.logo__text {
  text-align: left;
}
.about_company {
  background-color: #EB781D;
  padding-left: 13%;
  padding-right: 13%;
  padding-top: 7%;
  padding-bottom: 7%;
}
.about_company p {
  margin: 0%;
  color: white;
  text-align: left;
}
.about_company p:first-child {
  font: bold 16pt Verdana, sans-serif;
  padding-bottom: 3%;
}
.about_company p:last-child {
  font: lighter 10pt Verdana, sans-serif;
}
.company_card img {
  max-width: 25%;
  display: block;
  align-items: self-start;
}
.employees {
  background-color: #EB781D;
  padding-left: 13%;
  padding-right: 13%;
  padding-bottom: 8%;
  color: white;
}
.employees p {
  margin-top: 0%;
}
.employees__cap p:first-child {
  width: 45%;
}
.employees__cap p:last-child {
  width: 20%;
}
.employees__cap__mode {
  width: 35%;
}
.employees__row p {
  margin-bottom: 0%;
}
.contacts {
  margin-top: 8%;
  padding-left: 13%;
  padding-right: 13%;
  text-align: left;
}
.contacts__adress {
  margin-bottom: 5%;
}
.contacts__adress p:first-child {
  font: bold 15pt Verdana, sans-serif;
  color: #EB781D;
}
.contacts__phone {
  margin-bottom: 5%;
}
.contacts__phone p:first-child {
  font: bold 15pt Verdana, sans-serif;
  color: #EB781D;
}
.contacts__phone p:nth-child(3),
.contacts__phone p:nth-child(4), 
.contacts__phone p:nth-child(5), 
.contacts__phone p:nth-child(6), 
.contacts__phone p:nth-child(7) {
  margin-left: 10%;
}  
.contacts__phone p:nth-child(7) {
  margin-bottom: 5%;
}
.contacts__contact p:first-child {
  font: bold 15pt Verdana, sans-serif;
  color: #EB781D;
}
.contacts__contact {
  display: flex;
  flex-direction: column;
}
.contacts__contact input, .contacts__contact textarea {
  padding-left: 2%;
  margin-bottom: 6%;
}
.contacts__contact input {
  height: 20pt;
}
.contacts__contact textarea {
  height: 100pt;
  display: flex;
  align-items: center;
}
button {
  font: lighter 14pt Verdana, sans-serif;
  padding: 1% 0% 1% 0%;
  margin: 6% 0% 6% 0%;
  border: 0px solid #EB781D;
  border-radius: 10px;
  background-color: #EB781D;
  color: white;
}
footer {
  background-color: #EB781D;
  color: white;
  padding-left: 13%;
  padding-right: 13%;
  padding-top: 10%;
  padding-bottom: 10%;
  display: flex;
}
footer a:link, footer a:visited {
  text-decoration: none;
  font: lighter 11pt Verdana, sans-serif;
  color: white;
}
footer a:active, footer a:hover {
  text-decoration: none;
  font: lighter 11pt Verdana, sans-serif;
  color: white;
}
.footer__ref {
  display: flex;
  flex-direction: column;
  text-align: left;
  width: 50%;
}
.footer__contact {
  text-align: left;
}
.hamburger {
  margin-top: 10%;
  width: 40px;
  height: 40px;
  background-image: url(./assets/ham.png);
  background-size:contain;
  background-repeat: no-repeat;
}
.hamburger > input {
  display: none;
}
.hamburger > label {
  display: block;
  width: 38px;
  height: 38px;
  padding: 0px;
  cursor: pointer;
}
.hamburger > .hamburger__refs {
  display: none;
  background-color: #EB781D;
}
.hamburger > input:checked ~ .hamburger__refs {
  display: flex;
  position:absolute;
  margin-top: 15%;
  left: 0%;
  width: 100%;
  flex-direction: column;
  text-align: left;
  padding-left: 13%;
  padding-right: 13%;
}
.hamburger__refs a {
  padding-bottom: 5%;
}
.hamburger__refs a:link, .hamburger__refs a:visited {
  text-decoration: none;
  font: bold 14pt Verdana, sans-serif;
  color: white;
}
.hamburger__refs a:active, .hamburger__refs a:hover {
  text-decoration: none;
  font: bold 14pt Verdana, sans-serif;
  color: white;
}
.header2 {
  background-color: #EB781D;
  justify-content: space-between;
  padding-left: 13%;
  padding-right: 13%;
  padding-bottom: 5%;
}
.header2 img {
  width: 30%;
  height: 20%;
  margin-top: 5%;
}
</style>
