<template>
  <div class="class">
    
  </div>
</template>

<script lang="ts">
import { defineComponent, reactive, ref, toRefs } from 'vue';
import Job from './types/Job'

export default defineComponent({
  name: 'App',
  components: {},
  setup() {
    const jobs = ref<Job[]>([
      { title: 'farm worker', location: 'lon lon ranch', salary: 30000, id: '1'},
      { title: 'Vendor', location: 'Canada', salary: 48000, id: '2'},
      { title: 'Student', location: 'California', salary: 5000, id: '3'},
      { title: 'Programmer', location: 'Ohio', salary: 170000, id: '4'},
      { title: 'Engineering', location: 'Nevada', salary: 95000, id: '5'},
      { title: 'Teacher', location: 'New York', salary: 150000, id: '6'},
    ])
    return { jobs }
  },
});
</script>

<style>

</style>
