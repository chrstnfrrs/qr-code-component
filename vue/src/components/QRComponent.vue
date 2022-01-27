<template>
  <main class="qr">
    <figure class="qr-code">
      <img class="qr-code-img" src="../assets/image-qr-code.png" />
    </figure>
    <section class="qr-section">
      <h1 class="qr-heading">Improve your front-end skills by building projects</h1>
      <p class="qr-body">
        Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
      </p>
    </section>
  </main>
</template>

<style lang="scss">
.qr {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 18rem;
  border-radius: 1.25rem;
  background-color: hsl(0, 0%, 100%);
  padding: 1rem;
  gap: 1.5rem;

  &-code {
    display: flex;
    margin: 0;
    &-img {
      border-radius: 0.625rem;
      height: 100%;
      width: 100%;
    }
  }

  &-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
    margin-bottom: 1.5rem;
  }

  &-heading {
    margin: 0;
    font-size: 1.375rem;
    font-weight: 700;
    text-align: center;
    letter-spacing: 1px;
    color: hsl(218, 44%, 22%);
  }

  &-body {
    margin: 0;
    text-align: center;
    font-weight: 400;
    letter-spacing: 1px;
    word-spacing: 0.19px;
    color: hsl(220, 15%, 55%);
    line-height: 1.19;
  }
}
</style>
