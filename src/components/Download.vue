<script>
import "bootstrap-icons/font/bootstrap-icons.css";
</script>

<template>
  <div id="download">
    <h1>Download.</h1>
    <div class="cards">
      <div class="card">
        <div class="card-header"><i class="bi bi-fan"></i> Linux</div>
        <div class="card-body">
          <div class="btn-primary">Download</div>
        </div>
        <div class="card-footer text-muted">Arch, debian, fedora</div>
      </div>
      <div class="card">
        <div class="card-header"><i class="bi bi-windows"></i> Windows</div>
        <div class="card-body">
          <div class="btn-primary">Download</div>
        </div>
        <div class="card-footer text-muted">Windows 8, 10, 11</div>
      </div>
      <div class="card">
        <div class="card-header"><i class="bi bi-apple"></i> Mac Os</div>
        <div class="card-body">
          <div class="btn-primary">Download</div>
        </div>
        <div class="card-footer text-muted">MacOs 10.11+</div>
      </div>
    </div>
  </div>
</template>

<style>
.cards {
  display: flex;
  flex-flow: wrap row;
  justify-content: space-between;
}
.card-header {
  text-align: center;
  font-weight: bold;
}
.card {
  padding: 5vw;
}
@media (max-width: 500px) {
  .card {
    width: 100vw;
  }
}
</style>
