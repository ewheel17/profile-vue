<template>
  <div id="about">
    <div class="card">
      <h3>
        Welcome to my website! Thanks for stopping by to learn a little bit
        about me and what's been keeping me busy.
      </h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "about",
  components: {},
};
</script>

<style lang="scss" scoped>
#about {
  background: #FAFAFF;
  color: #30343F;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0px 60px;
  margin-bottom: 20px;

  .card {
    width: 100%;
    max-width: 800px;
    margin-top: -50px;
    padding: 10px 20px;
    background: #E4D9FF;
    border-top: solid 20px transparent;
    border-left: solid 20px #086375;
    border-right: solid 20px #086375; 
    border-bottom: solid 15px transparent;
    box-shadow: 0 0 15px #333;
    border-radius: 4px;
  }
}

@media screen and (max-width: 750px) {
  #about {
    padding: 0px 20px;

    .card {
      padding: 0px 10px;
      background: #E4D9FF;

      h3 {
        font-size: 15px;
      }
    }
  }
}
</style>
