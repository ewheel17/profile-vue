<template>
  <section id="banner">
    <h1 class="bottom-divider">Max Wheeler</h1>
    <h3>Web Developer, Biochemist, Eternal Student</h3>
  </section>
</template>

<script>
export default {
  name: "banner",
  components: {},
};
</script>

<style lang="scss" scoped>
#banner {
  height: 500px;
  padding: 0px 60px;
  background: #273469;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  
  h1 {
    font-weight: 100;
    font-size: 45px;
    margin: 0px;
  }

  h3 {
    font-weight: 100;
  }

  .bottom-divider {
    border-bottom: solid 1px white;
    padding-bottom: 10px;
  }
}

@media screen and (max-width: 750px) {
  #banner {
    height: 180px;
    padding: 0px 20px 70px 20px;

    h1 {
    font-size: 40px;
    }

    h3 {
      font-size: 15px;
    }
  }
}
</style>
