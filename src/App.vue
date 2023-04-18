<template>
  <nav>
    <div class="nav__logo">
      sq r3
    </div>
    <ul class="nav__menu">
      <li class="nav__link"><router-link to="/">Home</router-link></li>
      <li class="nav__link"><router-link to="/about">About</router-link></li>
      <li class="nav__link"><router-link to="/service">Service</router-link></li>
      <li class="nav__link"><router-link to="/furniture">Furniture</router-link></li>
      <li class="nav__link"><my-button>Order Now</my-button></li>
      <li class="nav__link "><my-button style="background: none; padding: 0; border: none;"><img src="./img/Search.svg" alt="search"></my-button></li>
    </ul>
  </nav>
  <router-view/>
</template>

<script>
import MyButton from './components/UI/MyButton.vue';


export default {
  components: {
    MyButton,
  },
  data() {
    return {
      value: 0,
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;

}
#app {
  max-width: 1440px;
  margin: 0 auto;
  padding: 0 35px;
  font-family: 'Roboto', sans-serif;
}


nav {
  padding: 36px 0;
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
  align-items: center;
}
.nav__logo {
  font-weight: 700;
  font-size: 25px;
  color: #000;
  text-transform: uppercase;
}
.nav__menu {
  display: flex;
  align-items: center;
}
.nav__link{
  margin-left: 35px;
  list-style-type: none;
  
}
.nav__link a {
  text-decoration: none;
  font-weight: 400;
  font-size: 18px;
  color: #000;
  transition: 0.5s;
}

.nav__link a:hover {
  background-color: #C4C4C4;
  padding: 5px 10px;
  transition: 0.5s;
  border-radius: 7px;
}


</style>
