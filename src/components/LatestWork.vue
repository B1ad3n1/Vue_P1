<template>
    <section class="sectionLatestWork">
        <h2 class="h2">Latest work</h2>
        <div class="divLW">
            <div class="LatestWorkCard" v-for ="item in LatestWork"
            :key="item.id"
            :pic="item.pic"
            :tags="item.tags">
            <img :src="item.pic">
            <h3>{{ item.name }}</h3>
            <p>{{ item.tags }}</p>
        </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return{
                LatestWork: [
                {id:1, pic:'/src/assets/LW1.png', name:'Project title', tags:'UI, Art drection'},
                {id:2, pic:'/src/assets/LW2.png', name:'Project title', tags:'UI, Art drection'},
                {id:3, pic:'/src/assets/LW3.png', name:'Project title', tags:'UI, Art drection'},
                {id:4, pic:'/src/assets/LW4.png', name:'Project title', tags:'UI, Art drection'},
                {id:5, pic:'/src/assets/LW5.png', name:'Project title', tags:'UI, Art drection'},
                {id:6, pic:'/src/assets/LW6.png', name:'Project title', tags:'UI, Art drection'},
                ]
            }
        },
    }
    
</script>

<style scoped>
.sectionLatestWork{
    width: 1280px;
    height: 1030px;
    padding-left: 24px;
    padding-right: 24px;
    padding-top: 42px;
    padding-bottom: 42px;
}
.divLW{
    gap: 42px;
    display: flex;
    flex-wrap: wrap;
    flex-grow: 3;
}
.LatestWorkCard{
    width: 395px;
    height: 419px;
    gap: 24px;
    align-items: center;
    text-align: center;
}
.h2{
    text-align: center;
    display: block;
}
</style>