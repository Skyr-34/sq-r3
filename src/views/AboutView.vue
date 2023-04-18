<template>
    <my-header>
    </my-header>
    <my-about>
    </my-about>
    <my-footer>
    </my-footer>
</template>

<script>
import MyHeader from '@/components/MyHeader.vue';
import MyAbout from '@/components/MyAbout.vue';
import MyFooter from '@/components/MyFooter.vue';


export default {
    components:
    {
        MyHeader, MyAbout, MyFooter,
    },
    data() {
        return {
            mainText: 'Информация о нас',
            }
        }
    }
</script>

<style scoped>

</style>