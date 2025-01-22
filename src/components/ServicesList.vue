<template>
    <section class="sectionService">
        <div class="ServiceCard" v-for ="item in services"
      :key="item.id"
      :pic="item.pic"
      :name="item.name"
      :description="item.description">
        <img :src="item.pic">
        <h3>{{ item.name }}</h3>
        <p>{{ item.description }}</p>
    
    </div>
    </section>
</template>

<script>
    export default {
        data() {
            return{
                services: [
                {id:1, pic:'/src/assets/service1.png', name:'Product Design', description:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:2, pic:'/src/assets/service2.png', name:'Visual Design', description:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:3, pic:'/src/assets/service3.png', name:'Art Derection', description:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                ]
            }
        },
    }
</script>

<style scoped>
.sectionService{
    width: 1280px;
    height: 513px;
    padding-left: 24px;
    padding-right: 24px;
    padding-top: 42px;
    padding-bottom: 42px;
    gap: 42px;
    display: flex;
}
.ServiceCard{
    width: 395px;
    height: 429px;
    padding-left: 42px;
    padding-right: 42px;
    padding-top: 64px;
    padding-bottom: 64px;
    gap: 42px;
    align-items: center;
    text-align: center;
}
</style>