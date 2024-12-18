<template>
    <div class="promo">
        <div class="promo__content">
            <div class="promo__content__text">
                <h2>КУРСЫ<br>БУХГАЛТЕРА</h2>
                <p>С нуля вы научитесь вести бухгалтерский учёт и сдавать отчётность, освоите программы, сможете претендовать на повышение или найти проекты на фрилансе</p>
                <button>Записаться на курс</button>
            </div> 
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'PromoItem',

}
</script>
  
<style>
.promo {
    background-image: url(../assets/promo.png);
    background-size: cover;
    min-height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.promo__content {
    background-color: rgba(255, 255, 255, 0.5);
    margin-left: 20%;
    margin-right: 20%;
    margin-top: 20%;
    margin-bottom: 20%;
}
.promo__content h2 {
    margin: 0%;
}
.promo__content__text {
    padding: 7%;
}
.promo__content__text p {
    margin-top: 4%;
}
.promo__content__text button {
    font: bold 11pt Verdana, sans-serif;
    color: white;
    border: 0px solid #EB781D;
    border-radius: 20px;
    background-color: #EB781D;
    padding-left: 5%;
    padding-right: 5%;
    padding-top: 1%;
    padding-bottom: 1%;
}
</style>