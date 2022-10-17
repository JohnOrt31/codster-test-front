<template>
  <div class="main">
    <div class="description" id="a">
      <div class="marks">
        <h1>"</h1>
      </div>
      <div class="phrase">
        <h1>
          "Si deseas establecer la mejor base posible, te recomiendo tomar este
          curso. La profundidad en la que entran los instuctores es increible.
          Ahora me siento tan seguro de comenzar como desarrollador
          profesional."
        </h1>
      </div>

      <div class="dev">
        <h2 id="name">John Smith</h2>
        <h2 id="position">Junior Front-end Developer</h2>
      </div>
    </div>
    <div class="person-container" id="b">
      <img src="../assets/shape_02.png" alt="Shape2" id="shape2" />
      <img src="../assets/shape_03.png" alt="Shape3" id="shape3" />
      <img src="../assets/pattern_dots.png" alt="dots" id="dots" />
      <img src="../assets/pattern_waves.png" alt="waves" id="waves" />
      <img src="../assets/buttons.png" alt="buttons" id="buttons" />

      <img
        src="../assets/person-02.png"
        alt="Front-end Developer"
        id="frontend"
      />
    </div>
  </div>
  <div class="footer">
    <img src="../assets/shape_01.png" alt="Shape1" id="shape1" />
  </div>
</template>

<script>
export default {
  name: "SlideCard",
};
</script>

<style scoped>
@media only screen and (max-width: 2000px) {
  .main {
    display: grid;
    grid-template-columns: 2fr 1.5fr;
  }

  .dev {
    display: grid;
    grid-template-columns: 1fr 2fr;
    width: 100%;
    text-align: left;
    position: relative;
    z-index: 10;
    text-align: left;
    top: -55%;
    font-size: 1em;
  }

  #name {
    font-style: normal;
    font-weight: 700;
    font-size: 21px;
    line-height: 25px;
    color: #232821;
  }

  #position {
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 25px;
    color: #aaaaaa;
  }

  .description {
    position: relative;
    z-index: 10;
    text-align: left;
    margin-left: 25em;
    margin-top: 10%;
  }
  .person-container {
    position: relative;
    margin-top: 20%;
  }

  .marks {
    position: relative;
    z-index: 1;
    font-size: 10em;
    top: -13%;
    left: 10%;
    margin: 0em;
    padding: 0rem;
    color: #e7f7e7;
    font-family: "Open Sans";
    font-style: italic;
    font-weight: 800;
    line-height: 392px;
  }

  .phrase {
    position: relative;
    z-index: 1;
    top: -55%;
  }

  .phrase h1 {
    color: #232821;
    font-size: 2.4em;
    font-style: normal;
    font-weight: 300;
    line-height: 38px;
  }

  img {
    max-width: 100%;
    height: auto;
    position: absolute;
  }

  #shape2 {
    z-index: 1;
    left: 20%;
    top: 12%;
  }

  #shape3 {
    z-index: 1;
    left: -15%;
    top: -2%;
  }

  #dots {
    z-index: 3;
    left: 47.4%;
    top: 47%;
  }

  #waves {
    z-index: 3;
    left: 16%;
    top: -4.5%;
  }

  #buttons {
    z-index: 11;
    left: 0%;
    top: 47%;
  }

  #frontend {
    z-index: 9;
    left: -10%;
    box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -webkit-box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -moz-box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
  }

  .footer {
    position: relative;
    align-self: flex-end;
    margin-left: 0em;
    text-align: left;
    margin-top: -26em;
  }
}

@media only screen and (max-width: 1700px) {
  .main {
    display: grid;
    grid-template-columns: 2fr 1.5fr;
    width: 100%;
  }

  .dev {
    display: grid;
    grid-template-columns: 1fr 2fr;
    width: 100%;
    text-align: left;
    position: relative;
    z-index: 10;
    text-align: left;
    top: -55%;
    font-size: 1em;
  }

  #name {
    font-style: normal;
    font-weight: 700;
    font-size: 21px;
    line-height: 25px;
    color: #232821;
  }

  #position {
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 25px;
    color: #aaaaaa;
  }

  .description {
    position: relative;
    z-index: 10;
    text-align: left;
    margin-left: 12em;
    margin-top: 8%;
  }
  .person-container {
    position: relative;
    margin-top: 20%;
  }

  .marks {
    position: relative;
    z-index: 1;
    font-size: 10em;
    top: -13%;
    left: 10%;
    margin: 0em;
    padding: 0rem;
    color: #e7f7e7;
    font-family: "Open Sans";
    font-style: italic;
    font-weight: 800;
  }

  .phrase {
    position: relative;
    z-index: 1;
    top: -55%;
  }

  .phrase h1 {
    color: #232821;
    font-size: 2.4em;
    font-style: normal;
    font-weight: 300;
    line-height: 38px;
  }

  img {
    max-width: 100%;
    height: auto;
    position: absolute;
  }

  #shape2 {
    z-index: 1;
    left: 30%;
    top: 12%;
  }

  #shape3 {
    z-index: 1;
    left: -15%;
    top: -2%;
  }

  #dots {
    z-index: 3;
    left: 65%;
    top: 47%;
  }

  #waves {
    z-index: 3;
    left: 23%;
    top: -4.5%;
  }

  #buttons {
    z-index: 12;
    left: 0%;
    top: 46%;
  }

  #frontend {
    z-index: 9;
    left: -10%;
    box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -webkit-box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -moz-box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
  }
}

@media only screen and (max-width: 700px) {
  .main {
    display: grid;
    grid-template-columns: 1fr;
    text-align: center;
    align-content: center;
    width: 100%;
    height: 0%;
  }

  #a {
    order: 2;
  }

  #b {
    order: 1;
  }

  .dev {
    display: grid;
    grid-template-columns: 1fr;
    width: 100%;
    z-index: 10;
    text-align: center;
    font-size: 1em;
    margin-top: 3em;
  }

  #name {
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 19px;
    color: #232821;
  }

  #position {
    margin: 0em;
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    color: #aaaaaa;
  }

  .description {
    z-index: 10;
    text-align: center;
    margin: 3em;
    margin-bottom: 7%;
  }
  .person-container {
    margin-top: 20%;
    margin-bottom: 40%;
    height: 100%;
  }

  .marks {
    position: relative;
    z-index: 1;
    font-size: 5em;
    top: -15%;
    left: 8%;
    margin: 0em;
    padding: 0rem;
    color: #e7f7e7;
    font-family: "Open Sans";
    font-style: italic;
    font-weight: 800;
  }

  .phrase {
    position: relative;
    z-index: 1;
  }

  .phrase h1 {
    color: #232821;
    font-size: 18px;
    font-style: normal;
    font-weight: 300;
    line-height: 21px;
  }

  #shape2 {
    z-index: 1;
    left: 40%;
    top: 3%;
    width: 55%;
    height: auto;
  }

  #shape3 {
    z-index: 1;
    left: 5%;
    top: -9%;
    width: 50%;
    height: auto;
  }

  #dots {
    z-index: 3;
    left: 65%;
    top: 105%;
    width: 28%;
    height: auto;
  }

  #waves {
    z-index: 3;
    left: 35%;
    top: -20%;
    width: 30%;
    height: auto;
  }

  #buttons {
    z-index: 11;
    left: 40%;
    top: 100%;
    width: 20%;
    height: auto;
  }

  #frontend {
    width: 65%;
    height: auto;
    z-index: 9;
    margin-left: 27%;
    box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -webkit-box-shadow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
    -moz-box-shaddffow: 16px 13px 27px 0px rgba(0, 0, 0, 0.38);
  }

  .footer {
    align-self: flex-end;
  }
}
</style>
