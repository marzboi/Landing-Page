<template>
  <div class="coming-soon-container">
    <div class="coming-soon-content">
      <div class="emoji"><img src="/public/face-content.svg" alt="" /></div>
      <h1>Coming soon</h1>
      <p>Estamos todavía under construction.</p>
      <p>
        Mientras tanto, puedes escribirnos a
        <a href="mailto:hola@idproductora.com">hola@idproductora.com</a>
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.coming-soon-container {
  color: black;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  flex-grow: 2;

  .coming-soon-content {
    text-align: center;

    .emoji {
      font-size: 3rem;
    }

    h1 {
      font-size: 4rem;
      margin: 0;
    }

    p {
      font-size: 2rem;
      margin: 0;
    }

    a {
      color: black;
    }

    @media only screen and (max-width: 600px) {
      h1 {
        font-size: 3rem;
      }
    }
    @media only screen and (max-width: 450px) {
      h1 {
        font-size: 2rem;
      }

      p {
        font-size: 1rem;
      }
    }

    @media only screen and (max-width: 300px) {
      h1 {
        font-size: 1rem;
      }

      p {
        font-size: 0.8rem;
      }
    }
  }
}
</style>
