<template>
    <div class="footer">
        <div class="footer__items">
            <div class="footer__column">
                <div class="column__title">
                    SQ R3
                </div>
                <div class="column__item">
                    <div class="phone">
                        +8801760-007083
                    </div>
                </div>
                <div class="column__item">
                    <div class="mail">
                        uiuxmdomith@gmail.com
                    </div>
                </div>
                <div class="column__item">
                    <div class="column__links">
                        <a href="#" class="link">
                            <img src="../img/facebook.svg" alt="...">
                        </a>
                        <a href="#" class="link">
                            <img src="../img/instageam.svg" alt="...">
                        </a>
                        <a href="#" class="link">
                            <img src="../img/twitter.svg" alt="...">
                        </a>
                        <a href="#" class="link">
                            <img src="../img/facebook.svg" alt="...">
                        </a>
                    </div>
                </div>
            </div>
            <div class="footer__column">
                <div class="column__title">
                    Usefull Links

                </div>
                <div class="column__item">
                   <router-link to="/">Home</router-link>
                </div>
                <div class="column__item">
                    <router-link to="/about">About Us</router-link>
                </div>
                <div class="column__item">
                    <router-link to="/service">Service</router-link>
                </div>
                <div class="column__item">
                    <router-link to="/furniture">Furniture</router-link>
                </div>
            </div>
            <div class="footer__column">
                <div class="column__title">
                    FAQ
                </div>
                <div class="column__item">
                    Lorem Ipsum Dolar
                </div>
                <div class="column__item">
                    Lorem Ipsum Dolar
                </div>
                <div class="column__item">
                    Lorem Ipsum Dolar
                </div>
                <div class="column__item">
                    Lorem Ipsum Dolar
                </div>
            </div>
            <div class="footer__column">
                <div class="column__title">
                    Newsletter
                </div>
                <div class="column__item">
                    <form @submit.prevent>
                        <my-input :plh-text="'Your Email'"/>
                        <my-button>Send</my-button>
                    </form>
                </div>
                <div class="column__item">
                    <my-button>Download App</my-button>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
import MyButton from './UI/MyButton.vue';
import MyInput from './UI/MyInput.vue';


    export default {
    components:
        {
            MyButton, MyInput,
                }
    }
</script>

<style scoped>
.footer {
    background: #373737;
    padding: 80px 141px;
}
.footer__items {
    display: flex;
    column-gap: 150px;
}
.footer__column {
}
.column__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;

    color: #FFFFFF;
    margin-bottom: 30px;
}
.column__item {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
    margin-bottom: 16px;
}
.column__item a {
    color: #FFFFFF;
    text-decoration: none;
}
.phone {
}
.mail {
}
.column__links {
    display: flex;
    column-gap: 20px;
}
.link {
}
</style>