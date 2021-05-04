<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="app">
    <div class="topPage">
      <h1>Join our commmunity</h1>
      <h2>30-day, hassle-free money back guarantee</h2>
      <h3>Gain access to our to our full library of tutorials along with expert code reviews.
        Perfrct for any developers who are serious about honing their skills.
      </h3>
    </div>
    <div class="gridPage">
      <div class="first-g">
        <h2>Monthly Subcription</h2>
        <h3>$29 per month</h3>
        <h3>Full access for less than $1 a day</h3>
        <h4>Sign Up</h4>
      </div>
      <div class="second-g">
        <h2>Why Us</h2>
        <h3>Tutorials by industry experts
          Peer & expert code reviews
          Coding exercises
          Access to our Github repos
          Commmunity forum
          Flashcard decks
          New video every week
        </h3>
      </div>
      

    </div>
    
  </div>

</template>

<script>


export default {
  name: 'App',
  
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color: rgb(234, 245, 242);
  background-color: rgb(206, 210, 211);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 50px;
}
.topPage{
  background-color: white;
  padding: 60px;
}
.topPage h1{
  font-weight: 200;
  font: 3em sans-serif;
  color: rgb(0, 255, 170);
  padding-bottom: 15px;
  background-color: white;
}
.topPage h2{
  font: 1.5em sans-serif;
  color: rgb(81, 255, 0);
  padding-bottom: 15px;
  background-color: white;
}
.topPage h3{
  font: 1.2em sans-serif;
  color: rgb(69, 77, 66);
  background-color: white;
}
.gridPage{
  display: grid;
  grid-template-columns: 1fr 1fr;
  /* line-height: 20; */
}
.first-g{
padding: 55px;
background-color: rgb(56, 243, 196);
}
.first-g h4{
  background-color: rgb(81, 255, 0);
  color: white;
  text-align: center;
  border-radius: 8px;
  padding: 10px;
  margin-top: 35px;
  box-shadow: 1px 2px 3px black;
}
.first-g h4:hover{
  color:rgb(81, 255, 0);
  background-color: white;
}
.gridPage h2{
  color:rgb(255, 255, 255);
  font: 1.6em small-caption;
  padding-bottom: 20px;
}
.second-g h2, h3{
  background-color: rgb(1, 105, 79);
}
.first-g h2, .first-g h3{
  background-color: rgb(56, 243, 196);
}
.gridPage h3{
  color: rgb(225, 252, 252);
  font: 0.9em small-caption;
  font-weight: bold;
}
.second-g{
  padding: 55px;
  background-color: rgb(1, 105, 79);
}
</style>
