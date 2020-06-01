<template>
  <div class="preview">
    <Logo />
  </div>
</template>

<style lang="scss" scoped>
.preview {
  background: #000;
  height: 100%;
  display: grid;
  grid-template-columns: 400px;
  grid-template-rows: 400px;
  justify-content: center;
  align-content: center;
  background: rgb(30, 70, 147);
  background: linear-gradient(
    67deg,
    rgba(30, 70, 147, 1) 0%,
    rgba(13, 22, 37, 1) 49%,
    rgba(6, 10, 19, 1) 100%
  );

  background-image: linear-gradient(
    to left top,
    #060a13,
    #080d17,
    #0a0f1a,
    #0b111d,
    #0c1320,
    #0d182a,
    #0e1d34,
    #0e223f,
    #0f2b53,
    #113468,
    #163d7d,
    #1e4693
  );
}

img,
svg {
  -webkit-user-drag: none;
}
</style>
