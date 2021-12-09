<template>
  <div class="home">
    <div class="wrapper first">
      <div class="mega">It's time to buy the dip.</div>
      <div class="subtitle">A wise man once said, <strong>buy the dip.</strong> We took that literally.</div>
      <a href="https://pancakeswap.finance/swap?outputCurrency=0x06b4a9f875e8bb5fa3265e91a4c6c3c49761740e&inputCurrency=" target="_blank"><div class="button">Buy the $DIP</div></a>
    </div>
    <div class="wrapper">
      <div class="mega">What is The Dip?</div>
      <div class="title">(i mean, have you not heard of it??)</div>
      <div class="sidebyside">
        <div class="text">
          <div class="subtitle">The most talked about; the hottest topic in town. Our friends over at r/wallstreetbets and Twitter talk about BUYING THE DIP all the time! Heck, even Warren Buffet has joined in on the fun. And if you're wondering what “buy The Dip” means, well look no further! You've come to the right place.
            <br/>
            <br/>
            A day in the life of a $DIP hodler is never bad, and I mean never. If markets are bad, then just buy The Dip and contribute rocket fuel. When markets become good again, then buckle up, because we're going on a trip to Europa <sub>[1]</sub>

            <br/>
            <br/>
            <sub>[1] Europa is one of Jupiter's moons, because aiming for Earth's moon isn't enough for us.</sub>
          </div>
        </div>
        <div class="image">
          <img :src="`${publicPath}assets/img/buffett.jpg`" style="width:100%;" />
        </div>
      </div>
    </div>
    <div class="wrapper red center">
      <div class="mega">White Paper</div>
      <div class="title">We got serious.</div>
      <div class="subtitle no-top">So here it is, our white paper, in a red... box.</div>
      <a :href="`${publicPath}assets/whitepaper/White Paper.pdf`" target="_blank"><div class="button white">Download our White Paper</div></a>
    </div>
    <div class="wrapper">
      <div class="mega">How can I get the $DIP??</div>
      <div class="title">That's a lovely question, I'm glad you asked. Everyone wants the $DIP, there's only so much to go around.</div>
      <div class="subtitle no-top">But fret not! Join our telegram channel now and get access to airdrops, events and much much more!</div>
      <a href="https://t.me/buythedip_official" target="_blank"><div class="button" style="color:white">Find us on Telegram</div></a>
    </div>
    <div class="wrapper red center">
      <div class="mega">How to roll with us</div>
      <div class="title">Step 1. Stonks are dipping!</div>
      <div class="subtitle no-top" >Panic.</div>
      <div class="title top-big">Step 2. Calm down.</div>
      <div class="subtitle no-top" >Realize you're wise.</div>
      <div class="title top-big">Step 3. Buy The Dip.</div>
      <div class="subtitle no-top" >And be smug about it.</div>
      <div class="title top-big">Step 4. Stonks are rising!</div>
      <div class="subtitle no-top" >Bathe in eternal glory. It's that simple.</div>
      <a href="https://pancakeswap.finance/swap?outputCurrency=0x06b4a9f875e8bb5fa3265e91a4c6c3c49761740e&inputCurrency=" target="_blank"><div class="button white">Buy the $DIP</div></a>
    </div>
    <div class="wrapper">
      <div class="mega">Tokenomics</div>
      <div class="title">60% Burnt</div>
      <div class="subtitle no-top">Because why not?</div>
      <div class="title top">30% Liquidity Pools</div>
      <div class="subtitle no-top">We've put it in the LPs all over the universe. Literally.</div>
      <div class="title top">0% Marketing</div>
      <div class="subtitle no-top">Why market when JPMorgan and Goldman Sachs does it for us? (see below)</div>
      <div class="title top">5% Community Development</div>
      <div class="subtitle no-top">Rocket fuel is pricey.</div>
      <div class="title top">5% Team</div>
      <div class="subtitle no-top">Doing this full-time is hard.</div>
    </div>
    <div class="wrapper">
      <div class="mega">Testimonials</div>
      <img :src="`${publicPath}assets/img/omgwtfbbq.png`" style="width:100%;" />
    </div>
    <div class="wrapper red">
      <div class="mega">Team</div>
      <div class="title">Jason Park</div>
      <div class="subtitle no-top">Economist, does the numbers.</div>
      <div class="title top">Nikolas Yeung</div>
      <div class="subtitle no-top">Resident tech guy. Nerd.</div>
      <div class="title top">Wesley Takahashi</div>
      <div class="subtitle no-top">Big boss. Calls the shots, very smart guy.</div>
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
a {
  color:inherit;
}
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
