<template>
  <div>
    <section class="hero is-fullheight">
       <div class="hero-head">
         <br>
         <div class="container">
            <div class="columns is-mobile">
            <div class="column">
              <div class="bars is-2 color-yellow"></div>
            </div>
            <div class="column">
              <div class="bars color-blue"></div>
            </div>
          </div>
          <div class="columns is-mobile">
            <div class="column is-2"></div>
            <div class="column">
              <div class="bars is-2 color-red"></div>
            </div>
            <div class="column is-2">
              <div class="bars is-2 color-yellow"></div>
            </div>
            <div class="column">
              <div class="bars color-green"></div>
            </div>
          </div>
          <div class="columns is-mobile">
            <div class="column is-6"></div>
            <div class="column is-2">
              <div class="bars color-blue"></div>
            </div>
            <div class="column is-1"></div>
            <div class="column">
              <div class="bars color-yellow"></div>
            </div>
          </div>
          <div class="columns is-mobile">
            <div class="column is-10"></div>
             <div class="column">
                <div class="bars color-red"></div>
             </div>
          </div>
         </div>
      </div>
      <div class="hero-body">
        <div class="container">
          <div class="columns is-mobile">
            <div class="column line-height">
              <h7 class="is-size-6 has-text-white-bis">hi, my name is Tak</h7>
            </div>
          </div>
          <div class="columns is-mobile">
            <div class="column line-height">
              <h1 class="has-text-white-bis">myear</h1>
              <h1 class="padding-left-30 random-color">2k18</h1>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.random-color {
   color: #f1c40f;
  -webkit-animation: color 5s ease-in  0s infinite alternate running;
  -moz-animation: color 5s linear  0s infinite alternate running;
   animation: color 5s linear  0s infinite alternate running;
}
@-webkit-keyframes color {
    0% { color: #f1c40f; }
    32% { color: #e74c3c; }
    55% { color: #9b59b6; }
    76% { color: #16a085; }
    100% { color: #2ecc71; }
}
@-moz-keyframes color {
     0% { color: #f1c40f; }
    32% { color: #e74c3c; }
    55% { color: #9b59b6; }
    76% { color: #16a085; }
    100% { color: #2ecc71; }
}
@keyframes color {
  0% { color: #f1c40f; }
    32% { color: #e74c3c; }
    55% { color: #9b59b6; }
    76% { color: #16a085; }
    100% { color: #2ecc71; }
}
.padding-left-30 {
  padding-left: 30%;
}
.line-height {
  line-height: 1;
}
h1 {
  font-size: 268px;
}
.bars {
  display: block;
  position: relative;
  border-radius: 20px;
  margin-left: 25%;
  height: 30px;
  border-radius: 10px;
}
.is-2 {
  width: 250px;
}
.color-yellow {
  background-color: #f9de9a;
}
.color-blue {
  background-color: #60b8ef;
}
.color-red {
  background-color: #f8aba0;
}
.color-green {
  background-color: #a6e38c;
}

</style>
