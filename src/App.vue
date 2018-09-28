<template>
  <div id="app">
    <div class="container">
      <tag-input placeholder="Entrez les tags" name="tags"/>
    </div>
  </div>
</template>

<script>
import TagInput from './components/TagInput.vue'

export default {
  name: 'App',
  components: {
    TagInput
  }
}
</script>
