<script>
export default {
  data() {
    return {
      items: [
        {
          title: "lightning fast",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
        {
          title: "Extensible and customizable",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
        {
          title: "Multiplataform",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
        {
          title: "Find and replace",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
        {
          title: "Packages",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
        {
          title: "Open Source",
          content:
            "adipisicing iusto iste eos nobis quas. sunt perferendis odio fuga",
          icon: "",
        },
      ],
    };
  },
};
</script>

<template>
  <div id="features">
    <h1>Features.</h1>
    <br />
    <div class="grid">
      <li class="item" v-for="item in items">
        <i class="icon background-primary bi bi-box"></i>
        <div class="content">
          <h2>{{ item.title }}</h2>
          {{ item.content }}
        </div>
      </li>
    </div>
  </div>
</template>

<style>
.grid {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-evenly;
}
.item {
  width: 35vw;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: all 0.5s ease-out;
}
.item:hover .icon {
  color: cyan;
}
.icon {
  padding: 1rem;
  font-size: 2.5rem;
  margin-right: 1vw;
  transition: all 0.5s ease-out;
}
.fs-4 {
  font-size: 1.5rem;
  font-weight: bold;
}
</style>
