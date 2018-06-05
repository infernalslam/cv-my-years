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
        hero-body
      </div>
    </section>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
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
