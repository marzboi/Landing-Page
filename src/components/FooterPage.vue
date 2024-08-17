<template>
  <footer>
    <p>© 2024 ID Productora</p>
  </footer>
</template>

<script>
export default {}
</script>

<style>
footer {
  display: flex;
  background-color: black;
  color: white;
  justify-content: center;

  @media only screen and (max-width: 450px) {
    p {
      font-size: 0.7rem;
    }
  }
}
</style>
