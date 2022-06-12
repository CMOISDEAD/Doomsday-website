<template>
  <div class="presentation">
    <div class="description">
      <p class="fs-3">Doomsday Editor</p>
      <p class="fs-5">
        Markdown editor<br />
        The Doomsday markdown editor.
      </p>
      <button class="btn-white">Download</button>
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
}
.btn-white {
  margin: 5vh 0;
  padding: 1vw;
  border: 1px solid white;
  border-radius: 0.5rem;
  background: white;
  color: #101010;
  font-size: 1rem;
  font-weight: bold;
  transition: all 0.5s ease-out;
}
.btn-white:hover {
  background: #171717;
  border: 1px solid #171717;
  color: white;
}
</style>
