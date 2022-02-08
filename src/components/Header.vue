<template>
    <header>
        <div class="container d-flex-j-between">
            <figure>
                <img src="../assets/dc-logo.png" alt="DC logo">
            </figure>

            <ul>
                <li><a href="#">PROVA</a></li>
                <li><a href="#">PROVA</a></li>
                <li><a href="#">PROVA</a></li>
                <li><a href="#">PROVA</a></li>
                <li><a href="#">PROVA</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style>
    figure {
        display: inline-block;
    }

    .d-flex-j-between {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    ul,
    ul li {
        display: inline-block;
    }
</style>