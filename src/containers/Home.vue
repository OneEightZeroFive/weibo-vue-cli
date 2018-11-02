<template>
    <div>
        <Xheader />
        <router-view></router-view>
    </div>
</template>
<script>
import Xheader from "../components/Xheader.vue"
export default {
    components:{
        Xheader
    }
}
</script>
<style scoped>
@import url("../css/cards.css");
@import url("../css/search.css");
</style>

