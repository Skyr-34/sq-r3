<template>
    <my-header>
    </my-header>
    <my-about>
    </my-about>
    <my-service>
    </my-service>
    <my-furniture>
    </my-furniture>
    <my-reviews>
    </my-reviews>
    <my-footer>
    </my-footer>
</template>

<script>
import MyHeader from '@/components/MyHeader.vue';
import MyAbout from '@/components/MyAbout.vue';
import MyService from '@/components/MyService.vue';
import MyFurniture from '@/components/MyFurniture.vue';
import MyReviews from '@/components/MyReviews.vue';
import MyFooter from '@/components/MyFooter.vue';

export default {
    components: {
            MyHeader, MyAbout, MyService, MyFurniture, MyReviews, MyFooter,
        }
        
    }
</script>

<style scoped>

</style>