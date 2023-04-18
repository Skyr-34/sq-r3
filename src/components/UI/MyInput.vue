<template>
    <input 
      type="text" 
      @input="updateValue"
      :placeholder="plhText"
    >
</template>

<script>
export default {
    name: 'my-input',
    props: {
        plhText: [String],
    },
    data() {
        return{
            placeholderText: 'blablablalb'
        }
    },
    methods: {
        updateValue(event) {  
            this.$emit('update:modelValue', event.target.value);
        }
    }
}
</script>

<style scoped>
input {
    height: 50px;
    width: 217px;
    background: #EFEFEF;
    border-radius: 5px;
    border: none;
    padding-left: 16px;

    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 18px;

    color: #686868;
}
</style>