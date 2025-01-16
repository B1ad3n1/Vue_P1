<template>
  <header>
    <div class="aheader">
      <div>
        <a class="logo">Logo</a>
      </div>
      <nav class="nav">
        <a class="nava">About</a>
        <a class="nava">Work</a>
        <a class="nava">Contact</a>
      </nav>
    </div>
    <div class="bheader">
      <div class="ab">
        <h1 class="h1">Branding | Image making </h1>
        <h1 class="h3">Visual Designer</h1>
        <p class="a">This is a template Figma file, turned into code using Anima. 
          Learn more at AnimaApp.com</p>
        <button class="ButtonContact">Contact</button>
      </div>
      <div class="pic">
        <img src="./assets/forheader.png">
      </div>
    </div>
    <div class="sponsors">
      <img src="./assets/google.png">
      <img src="./assets/nike.png">
      <img src="./assets/samsung.png">
      <img src="./assets/apple.png">
      <img src="./assets/adidas.png">
    </div>
  </header>
  <body>

  </body>
  <footer class="footer">
    <h1 class="hfooter">Lets work together</h1>
    <div class="underh">
      <div class="underh1">
        <p class="pfooter">This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com This is a template Figma file, turned into code using Anima. Learn more at AnimaApp.com</p>
        <div class="soc">
          <img src="./assets/discord.png">
          <img src="./assets/vector.png">
          <img src="./assets/dribbble.png">
          <img src="./assets/nstagram.png">
          <img src="./assets/behance.png">
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

</script>


<style scoped>
.aheader{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-left: 42px;
  padding-right: 42px;
  padding-top: 24px;
  padding-bottom: 24px;
  width: 1280px;
  height: 78px;
}

.logo{
  padding: 5px;
  font-weight: bold;
}
.nav{
  display: flex;

}
.nava{
  padding: 5px;
}

.bheader{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 1280px;
  height: 444px;
  padding-left: 42px;
  padding-right: 42px;
  padding-top: 24px;
  padding-bottom: 24px;
  gap: 68px;
}
.ab{
  width: 620px;
  height: 328px;
}

.h1{
  width: 400px;
}

.h3{
  width: 620px;
  font-size: 68px;
}

.a{
  width: 400px;
  height: 54px;
  font-size: 17px;
  line-height: 27px;
}

.ButtonContact{
  width: 211px;
  height: 78px;
  padding-left: 24px;
  padding-right: 64px;
  padding-bottom: 24px;
  padding-left: 64px;
  gap: 10px;
  background-color: black;
  color: white;
  font-size: 20px;
  text-align: center;
}

.pic{
  position: relative;
  scale: 0.7;
  padding-left: 42px;
  padding-right: 42px;
  padding-top: 24px;
  padding-bottom: 24px;
}

.sponsors{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 1280px;
  height: 130.83px;
  padding-left: 68px;
  padding-right: 68px;
  padding-top: 42px;
  padding-bottom: 42px;
}

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
