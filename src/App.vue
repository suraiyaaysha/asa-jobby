<template>
  <div id="app">
    <div id="nav">
      <TopHeader />
    </div>
    <router-view />
  </div>
</template>
<script>
// @ is an alias to /src
import TopHeader from "@/components/TopHeader";

export default {
  components: {
    TopHeader
  }
};
</script>