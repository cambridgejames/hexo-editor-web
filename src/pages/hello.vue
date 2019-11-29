<template>
    <div id="main">
        <MarkdownEditor v-model="value"/>
    </div>
</template>

<script>
    import MarkdownEditor from "../components/MarkdownEditor";

  export default {
    name: "hello",
    components: {MarkdownEditor},
    created() {
    },
    methods: {

    }
  }
</script>

<style scoped>

</style>