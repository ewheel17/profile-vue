<template>
  <section id="skills">
    <div class="simple-card">
      <h2 style="width: 100%; border-bottom: solid 2px #30343F; padding-bottom: 10px;">Current Professional Stack - <b>VENM</b></h2>
      <div class="simple-card-container">
        <div class="simple-card-block" style="flex-flow: column;">
          <img class="image-type-1" src="../../assets/vue-logo.jpg" alt="Vue Logo">
          <h4 style="margin: 0px;">Vue.js</h4>
        </div>
        <div class="simple-card-block">
          <img class="image-type-2" src="../../assets/express-logo.png" alt="Express Logo">
        </div>
      </div>
      <div class="simple-card-container">
        <div class="simple-card-block">
          <img class="image-type-1" src="../../assets/nodejs-logo.png" alt="Nodejs Logo">
        </div>
        <div class="simple-card-block">
          <img class="image-type-1" src="../../assets/mongo-logo.png" alt="Mongo Logo">
        </div>
      </div>
    </div>
    <div class="simple-card" style="margin-top: 40px;">
      <h3 style="width: 100%; padding-bottom: 10px;">Some other tech/tools I enjoy using</h3>
      <div class="simple-card-container unlimited-card-container">
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-1" src="../../assets/nuxt-logo.png" alt="NUXT Logo">
        </div>
        <div class="simple-card-block unlimited-card-block" style="flex-flow: column;">
          <img class="image-type-1" src="../../assets/angular-logo.svg" alt="Angular Logo">
          <h4 style="margin: 0px;">Angular</h4>
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-2" src="../../assets/ts-logo.png" alt="Typescript Logo">
        </div>
        <div class="simple-card-block unlimited-card-block" style="flex-flow: column;">
          <img class="image-type-1" src="../../assets/vuetify-logo.png" alt="Vuetify Logo">
          <h4 style="margin: 0px;">Vuetify</h4>
        </div>
        <div class="simple-card-block unlimited-card-block" style="flex-flow: column;">
          <img class="image-type-1" src="../../assets/tailwindcss-logo.jpg" alt="Tailwind CSS Logo">
          <h4 style="margin: 0px;">Tailwind CSS</h4>
        </div>
        <div class="simple-card-block unlimited-card-block" style="flex-flow: column;">
          <img class="image-type-1" src="../../assets/apollo-logo.png" alt="Apollo Logo">
          <h4 style="margin: 0px;">Apollo</h4>
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-1" src="../../assets/gql-logo.png" alt="GraphQL Logo">
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-1" src="../../assets/aws-logo.png" alt="Amazon Web Services Logo">
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-1" src="../../assets/sql-logo.jpg" alt="SQL Logo">
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img style="height: 145px;" src="../../assets/agile-logo.png" alt="Agile Processes Logo">
        </div>
        <div class="simple-card-block unlimited-card-block">
          <img class="image-type-2" src="../../assets/jira-logo.png" alt="Jira Logo">
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "skills",
  components: {},
  methods: {}
};
</script>

<style lang="scss" scoped>
#skills {
  padding: 30px 60px;
  background: #FAFAFF;
  color: #30343F;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;

  .simple-card {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-content: flex-end;
    width: 100%;
    max-width: 1000px;
    padding: 0px 20px;
    background: white;
    text-align: center;
    border-top: solid 20px transparent;
    border-left: solid 20px transparent;
    border-right: solid 20px transparent; 
    border-bottom: solid 15px transparent;
    box-shadow: 0 0 5px #333;
    border-radius: 4px;

    .simple-card-container {
      width: 50%;
      min-width: 400px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;

      .simple-card-block {
        display: flex; 
        flex-wrap: wrap;
        align-items: center;
        min-width: 100px;

        .image-type-1 {
          height: 100px;
        }
        .image-type-2 {
          height: 75px;
        }
      }
    }
    .unlimited-card-container {
      width: 100%;

      .unlimited-card-block {
        padding: 20px;
      }
    }
  }
}

@media screen and (max-width: 1020px) {
  #skills {
    .simple-card {
      .simple-card-container {
        min-width: 290px;

        .simple-card-block {
          .image-type-1 {
            height: 70px;
          }

          .image-type-2 {
            height: 45px;
          }
        }
      }
    }
  }
}

@media screen and (max-width: 780px) {
  #skills {
    .simple-card {
      max-width: 300px;

      .simple-card-container {
        margin-bottom: 25px;
      }

      .unlimited-card-container {
        .unlimited-card-block {
          padding: 10px;
          width: 40%;
        }
      }
    }
  }
}

@media screen and (max-width: 500px) {
  #skills {
    h2 {
      font-size: 20px;
    }
    .simple-card {
      padding: 5px 10px;
      max-width: 275px;
      
      .simple-card-container {
        margin: 0px;

        .simple-card-block {
          justify-content: center;
          width: 100%;
          margin-bottom: 20px;
        }
      }

      .unlimited-card-container {
        .unlimited-card-block {
          width: 40%;
        }
      }
    }
  }
}

</style>
