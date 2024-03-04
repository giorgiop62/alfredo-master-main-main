<script>
export default {
    name: "Home",
};
</script>

<template>
    <main>
        <div class="container-fluid">
            <img src="../assets/violinome.jpg" alt="">
            <div class="title mt-5">
                <h1 class="text"> Violinista Compositore performer </h1>
            </div>
        </div>
    </main>
</template>

<style lang="scss" scoped>
.container-fluid {
    background-color: black;
    color: white;
    display: flex;
}


h1 {
    text-align: center;
    font-size: 50px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}


.grey {
    filter: grayscale(100%);
}

img {
    height: 100vh;
}



a {
    color: white;
}
</style>