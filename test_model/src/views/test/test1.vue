<template>
    <article>
        <div>
            <p>段落 1</p> <!-- 这是第一个子元素 -->
            <p>段落 2</p>
            <p>段落 2</p>
            <p>段落 2</p>
        </div>
        <section>
            <h2>标题 1</h2> <!-- 这是第一个子元素 -->
            <h2>标题 2</h2>
        </section>
    </article>
</template>

<script setup>

</script>

<style lang="scss">
article *:first-child {
    color: red;
}

article :first-child {
    color: blue;
    /* 仅选择 article 的第一个直接子元素 */
}
</style>