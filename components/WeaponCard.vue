<template>
  <div class="card" :title="code" style="width: 18rem">
    <a :href="require(`@/assets/images/${imageUrl}`)" target="_blank"
      ><img
        :src="require(`@/assets/images/${imageUrl}`)"
        class="card-img-top"
        :alt="`image of a ${header}`"
      />
    </a>
    <div class="card-body d-flex justify-content-between">
      <h5 class="card-title mb-0">{{ header }}</h5>
      <Badge :text="code" />
    </div>
  </div>
</template>

<script>
import Badge from "./Badge.vue";
export default {
  name: "WeaponCard",
  props: {
    imageUrl: {
      type: String,
      required: true,
    },
    header: {
      type: String,
      required: true,
    },
    code: {
      type: String,
      required: true,
    },
  },
  data() {
    return {};
  },
  components: { Badge },
};
</script>
