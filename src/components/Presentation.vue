<template>
  <div class="presentation">
    <div class="description">
      <p class="fs-3">Doomsday Editor</p>
      <p class="fs-5">
        Markdown editor<br />
        The Doomsday markdown editor.
      </p>
      <button class="btn-primary">Download</button>
    </div>
    <div class="image-preview">
      <img src="../assets/codeeditor.png" alt="Doomsday" />
    </div>
    <div class="msg">↓ Scroll Down ↓</div>
  </div>
</template>

<style>
.presentation {
  height: 80vh;
  margin: 9vh 2vw;
  padding: 0;
  display: flex;
  flex-flow: row wrap;
  align-items: center;
  justify-content: space-between;
}
.description {
  width: auto;
  text-align: center;
}
.fs-3 {
  font-size: 3rem;
}
.fs-5 {
  font-size: 1.1rem;
}
img {
  width: 65vw;
  height: auto;
}
.msg {
  margin-top: 4vh;
  width: 100vw;
  font-size: 13px;
  text-align: center;
  animation: 1s scroll-down infinite linear;
}

@keyframes scroll-down {
  0%,
  100% {
    transform: translateY(0vw);
  }

  50% {
    transform: translateY(1vh);
  }
}

@media (max-width: 550px) {
  .description {
    width: 100vw;
  }
  .image-preview {
    display: none;
  }
}
@media (min-width: 780px) and (max-width: 1400px) {
  .msg {
    display: none;
  }
  .presentación {
    height: auto;
  }
}
@media (min-width: 1100px) and (max-width: 1400px) {
  .presentation {
    height: auto;
  }
}
@media (min-width: 550px) and (max-width: 1400px) {
  .presentation {
    justify-content: center;
  }
  .description {
    width: 100vw;
  }
  img {
    width: 90vw;
  }
}
</style>
