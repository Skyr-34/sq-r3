<template>
    <div class="reviews">
        <div class="reviews__header">
            <div class="reviews__title">
                What say clients about us
            </div>
            <div class="reviews__subtitle">
                It is a long established fact that a reader will be distracted by the service.
            </div>
        </div>
        <div class="reviews__body">
            
                <my-button class="btn">
                    <div class="arrow__left">
                        <img src="../img/arrow.svg" alt="...">
                    </div>
                </my-button>
            
            <div class="reviews__item">
                <div class="item__img">
                    <img src="../img/user1.png" alt="...">
                </div>
                <div class="item__body">
                    <div class="item__name">
                        Mr. Jone Ambrose
                    </div>
                    <div class="item__date">
                        20 - 07 - 21
                    </div>
                    <div class="item__text">
                        <span class="quotes">“</span>Lorem Ipsum has been the industry by standard dummy text ever to since the 1500s, it’s  type and scrambled it to make a type specimen book. It’s has survived not only five.<span class="quotes">”</span>
                    </div>
                    <div class="item__stars">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                    </div>
                </div>
            </div>
            <div class="reviews__item">
                <div class="item__img">
                    <img src="../img/user2.png" alt="...">
                </div>
                <div class="item__body">
                    <div class="item__name">
                        Mr. Jone Ambrose
                    </div>
                    <div class="item__date">
                        20 - 07 - 21
                    </div>
                    <div class="item__text">
                        <span class="quotes">“</span>Lorem Ipsum has been the industry by standard dummy text ever to since the 1500s, it’s  type and scrambled it to make a type specimen book. It’s has survived not only five.<span class="quotes">”</span>
                    </div>
                    <div class="item__stars">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                        <img src="../img/star.svg" alt="...">
                    </div>
                </div>
            </div>
            
                <my-button class="btn">
                    <div class="arrow__right">
                        <img src="../img/arrow.svg" alt="...">
                    </div>
                </my-button>
            
        </div>
    </div>
</template>

<script>
import MyButton from './UI/MyButton.vue';


export default {
    components: {
        MyButton,
    }
        
    }
</script>

<style scoped>

.btn {
    background: none;
    border: none;
    box-shadow: none;
    padding: 0;
    margin: 0;
}
.btn:hover {
    background: none;
    box-shadow: none;
    border: none;
}
.arrow__left {
    position: relative;
    background: rgba(55, 55, 55, 0.5);
    border-radius: 50%;
    height: 50px;
    min-width: 50px;
    margin: auto 0;
}
.arrow__left img {
    position: absolute;
    top: 13px;
    left: 17px;
}
.arrow__right {
    position: relative;
    background: rgba(55, 55, 55, 0.5);
    border-radius: 50%;
    height: 50px;
    min-width: 50px;
    margin: auto 0;
}
.arrow__right img {
    position: absolute;
    top: 13px;
    left: 17px;
    transform: rotate(180deg);
}

.reviews {
    margin: 0 141px 122px;
}
.reviews__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 35px;

    color: #000000;
    margin-bottom: 15px;
}
.reviews__subtitle {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 23px;

    color: #373737;
    position: relative;
    margin-left: 77px;
    margin-bottom: 45px;
    width: 358px;

}
.reviews__subtitle::before {
    content: " ";
    width: 69px;
    height: 1px;
    background: #000000;
    position: absolute;
    top: 22px;
    left: -77px;
}
.reviews__body {
    position: relative;
    display: flex;
    column-gap: 30px;
}
.reviews__item {
    background: #F9F9F9;
    border-radius: 5px;
    display: flex;
    border-radius: 5px;
}
.item__img{
    width: 163px;
    height: 224px;
    padding: auto 5px;
}
.item__img img {
    border-radius: 5px;
    object-fit: cover;
}
.item__body {
    margin: 15px 25px;
}
.item__name {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;

    color: #373737;
}
.item__date {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 30px;

    color: #696161;
    margin-bottom: 10px;
}
.item__text {
    font-family: 'ABeeZee';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 158.69%;
    margin-bottom: 15px;
    color:#373737;
}
.quotes {
    color: #F6DE00;
}
</style>