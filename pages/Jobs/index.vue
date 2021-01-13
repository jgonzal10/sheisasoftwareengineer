<template>
  <div>
    <job v-for="job in jobs" :key="job.id" :id="job.id" :job="job.name" />
  </div>
</template>
<script lang="ts">
import Job from "../../components/Job.vue";
export default {
  components: { Job },
  data() {
    return {
      jobs: [{ id: 1, name: "Java Developer" }]
    };
  },
  head() {
    return {
      title: "JENNIFER Jobs",
      metadata: [
        {
          hid: "description",
          name: "description",
          content: "Jennifer previous experience"
        }
      ]
    };
  }
};
</script>
<style></style>
