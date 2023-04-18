<template>
    <div class="header">
        <div class="header__bg">
        <div class="header__left">
            <div class="left__content">
                <a href="facebook.com" class="left__link">
                    <img src="../img/facebook.svg" alt="fb">
                </a>
                <a href="instagram.com" class="left__link">
                    <img src="../img/instageam.svg" alt="inst">
                </a>
                <a href="twitter.com" class="left__link">
                    <img src="../img/twitter.svg" alt="tw">
                </a>  
            </div>
            
        </div>
        
        <div class="header__right">
            <div class="right__title">
                Enjoy your life in our
                luxurious furniture
            </div>
            <div class="right__text">
                If you are looking for a furniture then you have
                come to the right place.
            </div>
            <my-button>
                Order Now
            </my-button>
        </div>
    </div>
    <div class="header__info">
        <div class="header__item">
            <div class="item__title">
                120 k
            </div>
            <div class="item__text">
                Furniture Sale
            </div>
        </div>
        <div class="header__item">
            <div class="item__title">
                98 k
            </div>
            <div class="item__text">
                Review <img src="../img/star.svg" alt="star"> (4.5)
            </div>
        </div>
        <div class="header__item">
            <div class="item__title">
                125
            </div>
            <div class="item__text">
                Furniture Categories
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
        name: "my-header",
        
    }
</script>

<style scoped>
.header {
    margin-bottom: 120px;
}
.header__bg {
    background-image: url(../img/headerBG.jpg);
    background-repeat: no-repeat;
    width: 100%;
    height: 762px;
    display: flex;
    
}
.left__link {
    margin-bottom: 40px;
    margin-left: 55px;
}
.header__left {
    display: flex;
    height: 668px;
    background: rgba(0, 0, 0, 0.15);
    backdrop-filter: blur(15px);
    min-width: 309px;
}
.left__content {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.header__left::after {
    position: absolute;
    content: " ";
    background: #000;   
    width: 309px;
    height: 262px;
    bottom: -262px;
}
.header__right {
    height: 339px;
    width: 100%;
    margin-top: 159px;
    background: linear-gradient(112.8deg, rgba(207, 207, 207, 0.26) 0%, rgba(207, 207, 207, 0.06) 92.87%);
    backdrop-filter: blur(15px);
    text-align: center;
    align-items: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.right__title {
    font-family: 'Revalia';
    font-style: normal;
    font-weight: 400;
    font-size: 36px;
    line-height: 45px;
    max-width: 500px;
    margin-bottom: 25px;
}
.right__text {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 23px;

    color: #FFFFFF;
    max-width: 412px;
    margin-bottom: 30px;
}
.header__info {
    margin-left: 309px;
    display: flex;
    height: 169px;
    align-items: center;
}
.header__item {
    margin-left: 75px;
}
.item__title {
    font-weight: 700;
    font-size: 40px;
    color: #000000;
    margin-bottom: 25px;
    text-align: center;
}
.item__text {
    font-weight: 400;
    font-size: 20px;
    color: #000000;
}
</style>