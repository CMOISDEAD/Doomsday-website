<script>
import "bootstrap-icons/font/bootstrap-icons.css";
</script>

<template>
  <div id="footer" class="gradient-border-top">
    <div class="box">
      <div class="trade-mark">
        Released under the MIT License.<br />
        Copyright © 2022 Camilo Davila
      </div>
      <div class="socials">
        <ul class="list-socials">
          <li>
            <a href="https://github.com/CMOISDEAD" target="_blank">
              <i class="bi bi-github"></i>
            </a>
          </li>
          <li>
            <a href="https://twitter.com" target="_blank">
              <i class="bi bi-twitter"></i>
            </a>
          </li>
          <li>
            <a href="https://youtube.com" target="_blank">
              <i class="bi bi-youtube"></i>
            </a>
          </li>
          <li>
            <a href="https://twitch.com">
              <i class="bi bi-twitch"></i>
            </a>
          </li>
          <li>
            <a href="https://twitch.com">
              <i class="bi bi-linkedin"></i>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
#footer {
  margin: 7vh 0 0.5vh 0;
}
.box {
  margin: 2vh 2vw;
  display: flex;
  justify-content: space-around;
  font-size: 0.9rem;
}
.trade-mark {
  text-align: center;
}
ul {
  display: inline-block;
}
li {
  list-style: none;
  float: left;
}
@media (max-width: 435px) {
  .box {
    justify-content: center;
    flex-flow: row wrap;
  }
  ul {
    columns: 2;
    -webkit-columns: 2;
    -moz-columns: 2;
  }
  li {
    float: none;
  }
}
</style>
