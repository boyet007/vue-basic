<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ greeting() }}</p>
    </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Your first vue file..whooo"
    };
  },
  methods: {
    greeting: function() {
      return "heyy coboy";
    }
  }
};
</script>

<style>
</style>
