<template>
    <div class="furniture">
        <div class="furniture__header">
            <div class="furniture__title">
                Our Furniture
            </div>
            <div class="furniture__subtitle">
                It is a long established fact that a reader will be distracted by the service.
            </div>
        </div>
        <nav class="furniture__nav">
            <form class="search" @:submit.prevent>
                <my-input :modelValue="searchF" :plh-text="'Search on furniture'" />
                <my-button class="search__btn">
                    <img src="../img/search_white.svg" alt="...">
                </my-button>
            </form>
            <div class="nav__rubricks">
                <my-button class="button">
                    All
                </my-button>
                <my-button class="button">
                    Chair
                </my-button>
                <my-button class="button">
                    Table
                </my-button>
                <my-button class="button">
                    Bed
                </my-button>
                <my-button class="button">
                    Sofa
                </my-button>
                <my-button class="button">
                    Wardrobe
                </my-button>
                <my-button class="button">
                    Almirah
                </my-button>
                <my-button class="button">
                    Dimple
                </my-button>
                <my-button class="button">
                    Rack
                </my-button>
                <my-button class="button">
                    Stand
                </my-button>
            </div>
        </nav>
        <div class="furniture__items">
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            <div class="furniture__item">
                <div class="item__img">
                    <img src="../img/furniture1.png" alt="...">
                </div>
                <div class="item__header">
                    <div class="item__name">
                        Furniture Name
                    </div>
                    <div class="item__price">
                        $ 250
                    </div>
                </div>
                <div class="item__body">
                    <div class="item__text">
                        It is a long estiabs lished fact that a reader will be the service.
                    </div>
                    <my-button>
                        Order Now
                    </my-button>
                </div>
            </div>
            
        </div>
        <my-button>
            View All
        </my-button>
    </div>  
</template>

<script>
import MyButton from './UI/MyButton.vue';
import MyInput from './UI/MyInput.vue';

export default {
    components:
        {
            MyButton, MyInput,
    },
    methods: {
        searchF(value) {
            console.log(value); 
            }
        }
        
    }
</script>

<style scoped>

.search {
    display: flex;
}
.search__btn {
    width: 50px;
    height: 50px;
    padding: 0;
    margin: 0;
}
.button {
    background: none;
    color: #000;
    border: none;

    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;

    color: #686868;

    padding: 0;
    margin-left: 30px;
}
.button:hover {
    box-shadow: none;
    background: none;
    border: none;
}
.furniture {
    margin: 0 141px 118px;
    text-align: center;

}
.furniture__header {
    margin: 0 auto;
    width: 358px;
    margin-bottom: 55px;
}
.furniture__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 35px;
    text-align: center;

    color: #000000;
    margin-bottom: 15px;
}
.furniture__subtitle {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;

    text-align: center;

    color: #373737;

}
.furniture__nav {
    padding: 0;
    margin-bottom: 60px;
    
}

.furniture__items {
    display: flex;
    margin-bottom: 20px;
    flex-wrap: wrap;
    column-gap: 30px;
}
.furniture__item {
    width: 267px;
    display: flex;
    flex-direction: column;
    background: #F9F9F9;

    border-radius: 5px;
    transition: 0.5s;
    margin-bottom: 30px;
}

.furniture__item:hover {
    box-shadow: 8px 8px 20px rgba(39, 39, 43, 0.1);
}

.item__img {
    padding: 5px;
}
.item__img img{
    width: 257px;
    height: 172px;
    border-radius: 5px;
}
.item__header {
    display: flex;
    justify-content: space-between;
    margin: 0 10px;

    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;

    color: #373737;
    margin-bottom: 10px;
}
.item__body {
    margin: 0 10px 10px;
    
}
.item__text {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 24px;

    color: #696161;
    margin-bottom: 13px;
}
</style>