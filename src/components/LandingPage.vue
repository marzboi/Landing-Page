<template>
  <div class="coming-soon-container">
    <div class="coming-soon-content">
      <div class="emoji">😊</div>
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
      font-size: 2rem;
      margin: 0;
    }

    p {
      font-size: 1.5rem;
      margin: 0;
    }

    a {
      color: black;
    }
  }
}
</style>
