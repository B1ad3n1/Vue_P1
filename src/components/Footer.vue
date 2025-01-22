<template>
    <footer class="footer">
    <h1 class="hfooter">Lets work together</h1>
    <div class="underh">
      <div class="underh1">
        <p class="pfooter">This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com</p>
        <div class="soc">
          <img src="../assets/discord.png">
          <img src="../assets/vector.png">
          <img src="../assets/dribbble.png">
          <img src="../assets/nstagram.png">
          <img src="../assets/behance.png">
        </div>
      </div>
      <div class="underh2">
        <p class="input1">Name</p>
        <p class="input2">Email</p>
        <button class="ButtonSubmit">Submit</button>
      </div>
    </div>
  </footer>
</template>

<script>
    export default {

    }
</script>

<style scoped>
.footer{
  width: 1280px;
  height: 426px;
  padding-left: 24px;
  padding-right: 24px;
  padding-top: 42px;
  padding-bottom: 86px;
  gap: 24px;
}

.hfooter{
  font-size: 32px;
  width: 600px;
  height: 42px;
}

.underh{
  width: 1232px;
  height: 232px;
  gap: 142px;
  display: flex;
}

.underh1{
  width: 570px;
  height: 159px;
  gap: 42px;
}

.pfooter{
  width: 570px;
  height: 81px;
}

.soc{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 360px;
  height: 36px;
  gap: 24px;
}

.underh2{
  width: 520px;
  height: 242px;
}

.input1{
  width: 520px;
  height: 59px;
  background-color: #F3F3F3;
  
}

.input2{
  width: 520px;
  height: 59px;
  background-color:#F3F3F3;
}

.ButtonSubmit{
  width: 199px;
  height: 78px;
  background-color: black;
  color: white;
}
</style>