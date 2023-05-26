<template>
</template>

<script>
export default {

  mounted() {
    const route = useRoute()
    const id = route.params.id.split('-').slice(-1).pop();
    window.location.href = "http://likeshowbiz.com/?p=" + id;
  },

};

</script>