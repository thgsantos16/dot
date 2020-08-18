<template>
  <div class="home">

    <div class="container-fluid hero">
      <div class="row screen">
        <div class="col-lg-7 bg">
          <div class="table">
            <div class="table-cell">
              <img src="../assets/logo.png" class="logo">
              <b-button variant="primary">Quero Participar!</b-button>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="table">
            <div class="table-cell">
              <img src="../assets/box.png" class="box">
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <div class="row gray">
          <div class="table">
            <div class="table-cell">
              <h2>O que é a <img src="../assets/logo-small.png" class="logo-small"> ?</h2>
              <div class="col-lg-7 centered">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Duis pellentesque nibh ac egestas ultrices.
                Sed tempus ex pulvinar tellus varius, eget vehicula libero commodo.
                Nullam ultricies justo in risus viverra rutrum.
                Phasellus euismod tempor eros faucibus condimentum.
                Aenean vestibulum non magna vitae maximus.
                Suspendisse potenti.
                Duis rutrum purus justo, vel volutpat lorem dapibus eu.
                Ut at dignissim orci, et iaculis mauris.

                <div class="circles">
                  <div class="circle">
                    <div class="inner"></div>
                    <div class="text">Item 1</div>
                  </div>
                  <div class="circle">
                    <div class="inner"></div>
                    <div class="text">Item 2</div>
                  </div>
                  <div class="circle">
                    <div class="inner"></div>
                    <div class="text">Item 3</div>
                  </div>
                  <div class="circle">
                    <div class="inner"></div>
                    <div class="text">Item 4</div>
                  </div>

                  <div class="line"></div>
                </div>
              </div>
            </div>
          </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row bg small">
        <h2>Já estou super convencido!</h2>

        <div class="col">
          <b-button variant="primary">Quero Participar!</b-button>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row justify-content-lg-center">
        <h2>Mas o que tem na Caixa?</h2>

        <div class="col-lg-6">
          <ul>
            <li>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipiscing elit.
            </li>
            <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipisci</li>
            <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipi</li>
            <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipi</li>
            <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipisci</li>
            <li>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. consectetur adipiscing elit.
            </li>
          </ul>
        </div>

        <div class="col-lg-4">
          <img src="../assets/box.png" class="box small">
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row dark-gray smaller justify-content-lg-center">
        <div class="col-lg-auto">
          <h3>Já estou super convencido!</h3>
        </div>

        <div class="col-lg-auto">
          <b-button variant="primary" class="lefty">Quero Participar!</b-button>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row purple screen">
          <div class="table">
            <div class="table-cell">
            <h2 class="padding-top">Amou, mas precisa saber Mais?</h2>

            <div class="col-lg-4 centered">
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Duis pellentesque nibh ac egestas ultrices.
                Sed tempus ex pulvinar tellus varius, eget vehicula libero commodo.
              </p>
              <input type="text" class="form-control" placeholder="Nome">
              <input type="email" class="form-control" placeholder="E-mail">
              <b-button variant="secondary">ENVIAR</b-button>
            </div>

            <h4>Já viu tudo que precisava?</h4>

            <div class="col-lg-6 centered">
              <b-button variant="primary">Quero Participar!</b-button>
            </div>

            <div class="col-lg-6 centered last">
              2020 Todos os Direitos Reservados
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
};
</script>

<style lang="scss" scoped>

@import 'node_modules/bootstrap/scss/bootstrap';

.row {
  padding: 10vh 0;

  &.screen {
    min-height: 100vh;
    padding: 0;
  }

  &.gray {
    background-color: #EEE;
  }

  h2, h3 {
    display: block;
    width: 100%;
    text-align: center;
    font-family: Montserrat, cursive;
    color: #222;
    font-size: 4rem;
    margin-bottom: 7vh;

    &.padding-top {
      padding-top: 7vh;
    }
  }

  h3 {
    margin-bottom: 0;
    font-size: 3rem;
    padding-right: 3vw;
  }

  h4 {
    padding: 5vh 0;
    color: #FFF;
    font-family: Montserrat, cursive;
  }

  .btn-primary {
    transition: all 0.43s;
    background-color: #D3A60A;
    border-color: #D3A60A;
    color: #242414;
    font-size: 1.4rem;
    padding: 7px 4vw;

    &:hover {
      background-color: #c0c026;
    }

    &.lefty {
      float: left;

      @include media-breakpoint-down(lg) {
        float: none;
        margin: 25px 0 0;
      }
    }
  }

  .btn-secondary {
    transition: all 0.43s;
    background-color: #20202F;
    border-color: #20202F;
    color: #FFF;
    font-size: 1.4rem;
    padding: 7px 4vw;

    &:hover {
      background-color: #33334A;
    }
  }

  .centered {
    margin-left: auto;
    margin-right: auto;
  }

  .last {
    color: #FFF;
    margin-top: 16vh;
  }

  .box {
      float: left;
      width: 90%;
      margin-left: -10%;

      @include media-breakpoint-down(lg) {
        margin-left: -1%;
        margin-top: 25px;
      }
  }

  ul {
    @include media-breakpoint-down(lg) {
      padding: 0;
    }

    li {
      list-style: none;
      margin-bottom: 25px;

      &:before {
        content: "";
        width: 20px;
        height: 20px;
        display: inline-block;
        vertical-align: top;
        background: url(../assets/cube.png) no-repeat center center;
        margin: 2px 12px 0 0;
      }
    }
  }
}

.table {
  display: table;
  margin-bottom: 0;
  height: 100%;

  .table-cell {
    display: table-cell;
    vertical-align: middle;

    .logo {
      display: block;
      margin: -7vh auto 7vh;
      max-width: 70%;

      @include media-breakpoint-down(lg) {
        margin-top: -1vh;
      }
    }

    .box {
      float: left;
      width: 90%;
      margin-left: -30%;

      @include media-breakpoint-down(lg) {
        margin-left: -1%;
      }
    }
  }
}

.circles {
  padding: 8vh 0 3vh;
  font-size: 0;

  .circle {
    width: 25%;
    display: inline-block;
    vertical-align: top;

    @include media-breakpoint-down(lg) {
      width: 100%;
    }

    .inner {
      width: 10vw;
      height: 10vw;
      border-radius: 50%;
      border: 10px solid #6D0C57;
      margin: 0 auto 20px;
      background-color: #FFF;

      @include media-breakpoint-down(lg) {
        width: 43vw;
        height: 43vw;
        min-width: 205px;
        min-height: 205px;
        margin-bottom: 12px;
      }
    }

    .text {
      font-size: 1.2rem;

      @include media-breakpoint-down(lg) {
        margin-bottom: 25px;
      }
    }
  }

  .line {
    width: 85%;
    margin: calc(-5vw - 53px) auto 7vw;
    height: 12px;
    background-color: #C11C92;

    @include media-breakpoint-down(lg) {
      display: none;
    }
  }
}

</style>
