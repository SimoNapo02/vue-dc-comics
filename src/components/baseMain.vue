<template>
    <main>
        <div class="container">
            <p>--> Content goes here  </p>
        </div>
    </main>
</template>

<script>
export default {
  name: 'BaseMain',
};
</script>

<style lang="scss">
    main{
        background-color: var(--secondary-color);
        & p{
            color: var(--secondary-color-text);
            padding: 3.125rem 0;
        }
    }
</style>
