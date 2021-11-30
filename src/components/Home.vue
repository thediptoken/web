<template>
  <div class="home">
    <div class="wrapper first">
      <div class="mega">It's time to buy the dip.</div>
      <div class="subtitle">A wise man once said, <strong>buy the dip.</strong> We took that literally.</div>
      <div class="button">Buy the $DIP - Coming soon.</div>
    </div>
    <div class="wrapper">
      <div class="mega">What is The Dip?</div>
      <div class="title">(i mean, have you not heard of it??)</div>
      <div class="sidebyside">
        <div class="text">
          <div class="subtitle">We are the most talked about token everywhere. r/wallstreetbets, Twitter and even Warren Buffet talks about BUYING THE DIP! If you have ever heard of the saying “buy The Dip”, well look no further! You've come to the right place.
            <br/>
            <br/>
            If you are in this together with us, there can never be a bad day for you. If markets are bad, just buy The Dip and fuel our rocket. Once markets become good again, then off we go!
          </div>
        </div>
        <div class="image">
          <img :src="`${publicPath}assets/img/buffett.jpg`" style="width:100%;" />
        </div>
      </div>
    </div>
    <div class="wrapper red center">
      <div class="mega">How we roll</div>
      <div class="title">Step 1. Stonks are dipping!</div>
      <div class="subtitle no-top" >Panic.</div>
      <div class="title top-big">Step 2. Calm down.</div>
      <div class="subtitle no-top" >Realize you're wise.</div>
      <div class="title top-big">Step 3. Buy The Dip.</div>
      <div class="subtitle no-top" >And be smug about it.</div>
      <div class="title top-big">Step 4. Stonks are rising!</div>
      <div class="subtitle no-top" >Bathe in eternal glory.</div>
      <div class="button white">Coming Soon</div>
    </div>
    <div class="wrapper">
      <div class="mega">Tokenomics</div>
      <div class="title">50% Burnt</div>
      <div class="subtitle no-top">Because why not?</div>
      <div class="title top">40% Liquidity</div>
      <div class="subtitle no-top">We've put it in the LPs all over the universe. Literally.</div>
      <div class="title top">0% Marketing</div>
      <div class="subtitle no-top">Why market when JPMorgan and Goldman Sachs does it for us? (see below)</div>
      <div class="title top">5% Future Development</div>
      <div class="subtitle no-top">Rocket fuel is pricey.</div>
      <div class="title top">5% Team</div>
      <div class="subtitle no-top">Doing this full-time is hard.</div>
    </div>
    <div class="wrapper">
      <div class="mega">Testimonials</div>
      <img :src="`${publicPath}assets/img/omgwtfbbq.png`" style="width:100%;" />
    </div>
    <div class="wrapper first center">
      <div class="mega center">Roll with us</div>
      <div class="swrapper">
        <div class="social">
          <a href="https://twitter.com/thediptoken">
            <img :src="`${publicPath}assets/img/twitter-logo.svg`">
          </a>
        </div>
        <div class="social">
          <a href="https://bscscan.com/token/0x06b4a9f875e8bb5fa3265e91a4c6c3c49761740e">
            <img :src="`${publicPath}assets/img/web-icon.svg`">
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script src="https://kit.fontawesome.com/fa7221f93f.js" crossorigin="anonymous"></script>
<script>
export default {
  name: 'Home',
  props: {
    msg: String
  },data () {
  return {
    publicPath: process.env.BASE_URL
  }
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sidebyside {
  display:flex;
}
.text {
  width:60%;
}
.image {
  padding:0 20px;
  width:40%;
}
.swrapper {
  width:100%;
  align-items:center;
  display:flex;
  justify-content:center;
}
.social {
  background-color:#A1051D;
  padding:10px;
  border-radius:25px;
  height:20px;
  margin:10px;
}
div.home {
  font-family:'Poppins';
  height: auto;
  background-color:#000;
  display:flex;
  flex-direction:column;
  align-items: center;
  padding: 100px 0;
}
div.wrapper {
  max-width: 800px;
  width:100%;
  background-color: #FDFDFD;
  border-radius: 20px;
  padding: 60px;
  margin: 40px 0;
}
.wrapper.first {
  background-color:transparent;
  color:#fff;
}
.wrapper.red {
  background-color:#A1051D;
  color:#fff;
}
.center {

  text-align:center;
}
.mega {
  font-family:Abril;
    font-weight:bold;
    font-size:48px;
    line-height:48px;
    padding-bottom:36px;
}
.title {
  font-weight:bold;

  font-size:20px;
}
.button {
  background-color:#A1051D;
  padding:10px 35px;
  border-radius:50px;
  margin:30px 0;
  display:inline-block;
  font-weight:bold;
}
.button.white {
  background:#fff;

  color:#A1051D;
  padding:10px 20px;
  border-radius:50px;
  margin:30px 0;
  display:inline-block;

}
.subtitle {
  position:relative;
  font-size:16px;
  line-height:32px;
  margin-top:40px;
}

div.skill-category .writeup i {
  font-size: 0.8rem;
  color: #777;
}

.top {
  margin-top:20px;
}
.top-big {
  margin-top:40px;
}
.no-top {
  margin-top:0px;
}
</style>
