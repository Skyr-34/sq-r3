<template>
    <button>
        <slot></slot>
    </button>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
button {
    background: none;
    padding: 13px 17px;
    border-radius: 5px;
    background-color: #373737;
    transition-duration: 1s;
    color: #fff;
    border: 2px solid #373737;
    font-family: 'Roboto';
    font-weight: 400;
    font-size: 18px;
}
button:hover {
    
    cursor:pointer;
    background-color: #C4C4C4;
    box-shadow: 1px 1px 10px 1px #C4C4C4;
    border: 2px solid #C4C4C4;
    color: #373737;
}
</style>