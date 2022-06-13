<template>
  <div id="download">
    <h1>Download.</h1>
    <div class="cards">
      <div class="card">
        <div class="card-header">Linux</div>
        <div class="card-body">
          <div class="btn-primary">Donwload</div>
        </div>
        <div class="card-footer text-muted">Arch, debian, fedora</div>
      </div>
      <div class="card">
        <div class="card-header">Windows</div>
        <div class="card-body">
          <div class="btn-primary">Donwload</div>
        </div>
        <div class="card-footer text-muted">Windows 8, 10, 11</div>
      </div>
      <div class="card">
        <div class="card-header">Mac</div>
        <div class="card-body">
          <div class="btn-primary">Donwload</div>
        </div>
        <div class="card-footer text-muted">MacOs 10.11+</div>
      </div>
    </div>
  </div>
</template>

<style>
.cards {
  display: flex;
  justify-content: space-between;
}
.card-header {
  text-align: center;
  font-weight: bold;
}
.card {
  padding: 5vw;
}
</style>
