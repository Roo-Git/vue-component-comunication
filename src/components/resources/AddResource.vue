<template>
  <base-card>
    <form action="">
      <div class="form-control">
        <label for="title">Title</label>
        <input id="title" name="title" type="text" />
      </div>
      <div class="form-control">
        <label for="title">Description</label>
        <textarea name="description" id="description" rows="3"></textarea>
      </div>
      <div class="form-control">
        <label for="link">Link</label>
        <input name="link" id="link" type="url" />
      </div>
      <div>
        <base-button></base-button>
      </div>
    </form>
  </base-card>
</template>

<script>
export default {
  name: "Add-Resource",
};
</script>
<style scoped></style>
