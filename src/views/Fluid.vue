<template>
  <div>
    <h1>Hello World!</h1>
    <h2>{{ info }}</h2>
    <br />
    <div>
      <input type="text" />
    </div>
    <br>
    <img :src="image" alt="" width="500" />
  </div>
</template>
<script>
export default {
  data() {
    return {
      info: "Soy Fer",
      image:
        "https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Steinadler_Aquila_chrysaetos_closeup1_Richard_Bartz.jpg/1200px-Steinadler_Aquila_chrysaetos_closeup1_Richard_Bartz.jpg",
    };
  },
};
</script>
