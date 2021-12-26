<template>
    <section class="slider text-center position-relative">
        <div class="caption position-absolute top-50 start-50 translate-middle">
            <h3>design / development / photography</h3>
            <h1>Creativity has new level</h1>
            <a class="btn career">preview</a>
            <a class="btn career">get theme</a>
        </div>
    </section>
</template>


<style scoped>
    .slider{
        background-image: url("../assets/img/header.jpg");
        background-size: cover;
        height: 85vh;
        background-color: var(--second-color);
        background-blend-mode: multiply;
        color: var(--white);
    }
    .slider .caption .career{
        color: var(--white);
        background-color: transparent;
        border: 2px solid var(--white);
        font-weight: bold;
        font-size: calc(var(--default-font-size) + 2px);
        margin-right: 2%;
    }
    .slider .caption .career:hover{
        background-color: var(--main-color);
        transition: all 1s ease-in-out;
    }
</style>

<script>
export default{
    name: "HomeComp"
}
</script>

