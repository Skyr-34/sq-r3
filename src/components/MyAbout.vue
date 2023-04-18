<template>
    <div class="about">
        <div class="about__header">
            <div class="about__title">
            Learn about us
            </div>
            <div class="about__subtitle">
                Its short title here
            </div>
        </div>
        <div class="about__content">
            <div class="about__left">
                <img src="../img/room.png" alt="room">
            </div>
            <div class="about__right">
                <div class="right__text">
                    Lorem Ipsum has been the industry's standard dummy text ever to since the 1500s, type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting. type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting
                </div>
                
                <router-link to="/about">
                    <my-button  class="button">
                        More about us
                    </my-button>
                </router-link>
                
                <div class="right__advertising">
                    <div class="advertising__item">
                        <img src="../img/Amazon_logo.svg" alt="...">
                    </div>
                    <div class="advertising__item"><img src="../img/Alibaba_logo.svg" alt="..."></div>
                    <div class="advertising__item"><img src="../img/raunds.svg" alt="..."></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import MyButton from './UI/MyButton.vue';

export default {
    components: {
        MyButton,
    },
    name: "my-about",
        
    }
</script>

<style scoped>
.about {
    margin-bottom: 120px;
}
.about__header {
    margin-left: 141px;
}
.about__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 35px;

    color: #000000;
    margin-bottom: 15px;
}
.about__subtitle {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 23px;

    color: #373737;
    position: relative;
    margin-left: 77px;
    margin-bottom: 45px;
}
.about__subtitle::before {
    content: " ";
    width: 69px;
    height: 1px;
    background: #000000;
    position: absolute;
    top: 11px;
    left: -77px;
}
.about__content {
    display: flex;
}
.about__left img {
    border-radius: 0px 5px 5px 0px;
}
.about__right {
    margin-left: 30px;
}
.right__text {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 32px;

    color: #373737;

    max-width: 663px;
    margin-bottom: 30px;
}
.button {
    margin-bottom: 62px;
}
.right__advertising {
    display: flex;
    column-gap: 105px;
}
</style>