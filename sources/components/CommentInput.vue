<template>
    <input ref="input_field">
</template>

<script>

export default {
    name: "CommentInput",
    props: ["modelValue"],
    setup() {
        return {};
    },
    data() {
        return {};
    },
    emits: ['update:modelValue', "submit"]
}
</script>