<template>
  <Header>
  
  </Header>
  <body>
    <ServicesList>

    </ServicesList>
    <LatestWork>

    </LatestWork>
    <FeedBack></FeedBack>
  </body>
  <Footer>

  </Footer>
</template>


<script>
import FeedBack from './components/FeedBack.vue';
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import LatestWork from './components/LatestWork.vue';
import ServicesList from './components/ServicesList.vue';

  export default {
    components: {
      Header, Footer, ServicesList, LatestWork, FeedBack
    },
  }
</script>


<style scoped>

</style>
