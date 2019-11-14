<template>
  <div id="navbar">
    <a href="#skills">
      <button>
        Skills
      </button>
    </a>
    <a href="#portfolio">
      <button>
        Portfolio
      </button>
    </a>
    <a href="#contact">
      <button>
        Contact
      </button>
    </a>
  </div>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style lang="scss" scoped>
#navbar {
  padding: 20px 60px;
  background: #273469;
  color: white;
  display: flex;
  justify-content: flex-end;
  align-items: center;

  button {
    display: inline-block;
    border: none;
    padding: 10px 15px;
    margin: 0 10px 0px 0px;
    border-radius: 4px;
    width: 100px;
    text-decoration: none;
    background: #273469;
    color: #ffffff;
    font-family: sans-serif;
    font-size: 1rem;
    cursor: pointer;
    text-align: center;
    transition: background 250ms ease-in-out, transform 150ms ease;
    -webkit-appearance: none;
    -moz-appearance: none;
  }
  a {
    text-decoration: none;
    color: inherit;
  }

  button:hover,
  button:focus {
    background: #1E2749;
    color: white;
  }

  button:active {
    transform: scale(0.99);
  }
}

@media screen and (max-width: 750px) {
  #navbar {
    justify-content: center;
    padding: 15px 20px;
  }
}
</style>
