<template>
  <div>
    <header>
      <img src="/Logo.svg" alt="" width="500" height="60" />
      <h2>Productora de contenidos especializada en diversidad y justicia social</h2>
    </header>
  </div>
</template>

<style lang="scss" scoped>
div {
  display: flex;
  flex-direction: column;
  background-color: black;
  width: 100%;

  header {
    display: flex;
    justify-content: space-between;
    padding: 1rem;

    img {
      margin-left: 1rem;
    }

    h2 {
      margin-right: 1rem;
      font-weight: 200;
      justify-content: center;
    }

    @media only screen and (max-width: 1350px) {
      div {
        justify-content: center;
      }

      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    @media only screen and (max-width: 600px) {
      img {
        width: 300px;
        height: 40px;
      }

      h2 {
        font-size: 0.8rem;
      }
    }
  }
}
</style>
