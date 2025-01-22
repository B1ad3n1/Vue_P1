<template>
    <section class="sectionFeedBack">
        <h2 class="h2">Testimonial</h2>
        <div class="divFB">
            <div class="FeedbackCard" v-for ="item in FeedBack"
            :key="item.id"
            :pic="item.pic"
            :company="item.company"
            :raiting="item.raiting"
            :feedback="item.feedback">
            <p class="pfeedback">{{ item.feedback }}</p>
            <img :src="item.pic">
            <div class="rating">
                <img 
                    v-for="n in parseInt(item.raiting)" 
                    :key="n" 
                    src="/src/assets/star.png" 
                    alt="Star" 
                    class="star">
            </div>
            <h3>{{ item.name }}</h3>
            <p>{{ item.company }}</p>
        </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return{
                FeedBack: [
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                {id:1, pic:'/src/assets/Client1.png', name:'Gemma Nolen', company:'Google', raiting:'5', feedback:'This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com'},
                ]
            }
        },
    }
    
</script>

<style scoped>
.sectionFeedBack{
    width: 1280px;
    height: 1030px;
    padding-left: 24px;
    padding-right: 24px;
    padding-top: 42px;
    padding-bottom: 42px;
}
.divFB{
    gap: 42px;
    display: flex;
    flex-wrap: wrap;
    flex-grow: 3;
}
.FeedBackCard{
    width: 395px;
    height: 330px;
    gap: 24px;
    align-items: center;
    text-align: center;
    padding: 20px;
    display: flex;
    background-color: #F3F3F3;    
}
.h2{
    text-align: center;
}
.star {
    width: 20px;
    height: 20px;
}
.rating{
    display: flex;
}
.pfeedback{
    width: 311px;
    height: 90px;
    
}
</style>