<template>
  <div>{{msg}}</div>
</template>

<script lang="ts">
import Component from "vue-class-component";
import {Prop} from "vue-property-decorator";
import Vue from "vue";

@Component
export default class HelloUniverse extends Vue {

  @Prop({ default: 'default value' }) readonly msg!: string

}
</script>

<style scoped>

</style>
