<template>
    <div class="service">
        <div class="service__header">
            <div class="service__title">
                We provide that service
            </div>
            <div class="service__subtitle">
                It is a long established fact that a reader will be distracted by the service.
            </div>
        </div>
        <div class="service__body">
            <div class="service__item">
                <div class="item__logo">
                    <img src="../img/cargo.svg" alt="...">
                </div>
                <div class="item__title">
                    Free Delevary
                </div>
                <div class="item__text">
                    It is a long established fact that a reader will be the service.
                </div>
            </div>
            <div class="service__item">
                <div class="item__logo">
                    <img src="../img/checked.svg" alt="...">
                </div>
                <div class="item__title">
                    100% Guarnatee
                </div>
                <div class="item__text">
                    It is a long established fact that a reader will be the service.
                </div>
            </div>
            <div class="service__item">
                <div class="item__logo">
                    <img src="../img/medal.svg" alt="...">
                </div>
                <div class="item__title">
                    Best Quality
                </div>
                <div class="item__text">
                    It is a long established fact that a reader will be the service.
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.service__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 30px;
    line-height: 35px;

    color: #000000;
    margin-bottom: 15px;
}
.service__subtitle {
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
.service__subtitle::before {
    content: " ";
    width: 69px;
    height: 1px;
    background: #000000;
    position: absolute;
    top: 22px;
    left: -77px;
}

.service {
    margin-left: 141px;
    margin-bottom: 120px;
}
.service__body {
    display: flex;
    column-gap: 30px;
}
.service__item {
    width: 366px;
    padding: 12px;
    transition: 0.3s;
}
.service__item:hover {
    box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.05);
    border-radius: 5px;
    
}
.item__logo {
    height: 75px;
    width: 75px;
    background: rgba(21, 188, 224, 0.1);
    border-radius: 5px;
    align-items: center;
    text-align: center;
    display: flex;
    justify-content: center;
    margin-bottom: 15px;
}
.item__title {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 23px;

    color: #000000;
    margin-bottom: 10px;
}
.item__text {
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 30px;
   
    color: #696161;
}
</style>