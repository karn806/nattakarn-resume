<template lang="html">
  <div class="home">
    <nav-bar></nav-bar>
    <div class="top-row">
      <md-layout md-gutter md-align="center">
        <span id="my-name"><b>Nattakarn Klongyut</b></span>
      </md-layout>
    </div>
    <md-card class="card-container">
      <md-tabs md-right id="bg-content">
        <md-tab md-label="EN">
          <my-content></my-content>
        </md-tab>
        <!-- <md-tab md-label="TH">
          <thai-content></thai-content>
        </md-tab> -->
      </md-tabs>
    </md-card>
    <div id="foot">
      <p>dfsfsf</p>
      <p>dfsfsf</p>
      <p>dfsfsf</p>
      <p>dfsfsf</p>
    </div>
  </div>
</template>

<script>
// import router from './../router'
export default {
  name: 'home',
  components: {
    MyContent: require('./Content'),
    NavBar: require('./../NavBar'),
    ThaiContent: require('./ContentTH')
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#foot {
  color: #D0DFDD;
}
#font-tabs {
  color: black;
}
#my-name {
  font-size: 60px;
  color: #00838F;
}
#bg-content {
  background-color: #F0EFEB;
}
.card-container {
  width: 80%;
  margin: auto;
}
.top-row {
  text-align: center;
  margin-bottom: 5%;
  margin-top: 2%;
}
.left-box {
  margin-left: 50px;
}
</style>
