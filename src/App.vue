<template>
  <ul>
    <ResourceItem
      v-for="res in storedResources"
      :key="res.id"
      :title="res.title"
      :description="res.description"
      :link="res.link"
    ></ResourceItem>
  </ul>
</template>

<script>
import ResourceItem from "./components/resources/ResourceItem.vue";
export default {
  name: "App",
  components: {
    ResourceItem,
  },
  data() {
    return {
      storedResources: [
        {
          id: "official-guide",
          title: "Official Guide",
          description: "The official Vue.js documentation",
          link: "https://vuejs.org",
        },
        {
          id: "google",
          title: "Google",
          description: "Learn to google",
          link: "https://google.org",
        },
      ],
    };
  },
};
</script>

<style></style>
