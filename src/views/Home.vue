<template>
    <HomePage />
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HomePage from '@/components/HomePage.vue' // @ is an alias to /src

@Options({
  components: {
    HomePage
  }
})
export default class Home extends Vue {}
</script>
