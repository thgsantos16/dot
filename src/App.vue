<template>
  <div id="app">

    <!-- This Component renders some meta tags and title -->
    <vue-headful
        title="DoT | Drinks of Tomorrow"
        description=""
        keywords="drinks, of, tomorrow, dot, Thiago, Cruz, App, DoT, bebidas"
        image="assets/scott.png"
        lang="pt-br"
    />

    <transition name="fade" appear>
      <router-view/>
    </transition>
  </div>
</template>

<style lang="scss">

@import 'node_modules/bootstrap/scss/bootstrap';
@import 'node_modules/bootstrap-vue/src/index.scss';
@import url('https://fonts.googleapis.com/css2?family=Baloo+Tamma+2&family=Roboto&family=Montserrat:wght@300&display=swap');

#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.bg {
  background-image: url(assets/bg.jpg);
  color: #FFF;

  h2 {
    color: #FFF !important;
  }
}

.dark-gray {
  background: #20202F;
  color: #FFF;

  h2, h3, h4 {
    color: #FFF !important;
  }
}

.purple {
  background-image: url(assets/bg-purple.jpg);
  color: #FFF;

  p {
    color: #FFF;
    margin-bottom: 7vh;
  }

  .form-control {
    width: 70%;
    max-width: 430px;
    margin: 20px auto;
    border: none;
    text-align: center;
    padding: 1rem 0 1rem;
    height: calc(2em + 0.8rem + 2px);
  }

  h2 {
    color: #FFF !important;
  }
}

.fade-enter-active, .fade-leave-active {
  transition: opacity .5s;
}
.fade-enter, .fade-leave-to {
  opacity: 0;
}

.slowfade-enter-active, .slowfade-leave-active {
  transition: opacity 2s;
}
.slowfade-enter, .slowfade-leave-to {
  opacity: 0;
}

</style>
