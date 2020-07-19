<template>
      <b-col md="3">
        <b-card
          :title="name"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Job-info"
          img-top
          tag="article"
          style="max-width:20rem"
          class="mb-4"
          footer="Card Footer"
        >
          <b-card-text>
            lorem ipsum lorem ipsum lorem ipsum bangladesh
          </b-card-text>
          <b-button varient="primary">Apply</b-button>
        </b-card>
      </b-col>
</template>

<script>
export default {
  name: "JobCard",
  props: ["name"]
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
