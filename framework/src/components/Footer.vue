<template>
 <footer>
     <p>{{ copyright }}</p>
</footer>   
</template>


<script>
export default {
  data() {
    return {
      copyright: "Copyright 2017 Vue ninjas"
    };
  }
};
</script>

<style scoped>
footer {
  background: #222;
  padding: 6px;
}

footer p {
    color: yellow;
    text-align: center;
}
</style>
