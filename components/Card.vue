<template>
  <div class="card" style="width: 18rem">
    <a :href="require(`@/assets/images/${imageUrl}`)" target="_blank"
      ><img
        :src="require(`@/assets/images/${imageUrl}`)"
        class="card-img-top"
        :alt="header"
        :title="header"
      />
    </a>

    <div class="card-body">
      <h5 class="card-title">{{ header }}</h5>
      <p class="card-text">{{ description }}</p>
    </div>
    <div class="card-footer">
      

      <Badge
        v-for="tag in tags"
        :key="tag.id"
        :text="tag.type"
        color="primary"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    imageUrl: {
      type: String,
      required: true,
    },
    header: {
      type: String,
      required: true,
    },
    description: {
      type: String,
      required: true,
    },
    tags: {
      type: Array,
      required: true,
    },
  },
  data() {
    return {};
  },
};
</script>
