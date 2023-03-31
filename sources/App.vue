<template>
    <comment-input/>
</template>

<script>

import Comment from './components/Comment.vue';
import CommentInput from './components/CommentInput.vue';

export default {
    name: "App",
    components: { Comment, CommentInput },
    setup() {

    },
    data() {
        return {
            comments: [],
        }
    },
    beforeMount() {

    }
}
</script>

