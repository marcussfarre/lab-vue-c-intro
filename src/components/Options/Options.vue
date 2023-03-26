<script>
    export default
    {
        name: 'Options'
    }
</script>

<template> 
    <div class="container">
        <div class="card">
            <img src="../../images/USP-1.png" alt="">
            <h3>Performant</h3>
            <p>Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.</p>
        </div>
        <div class="card">
            <img src="../../images/USP-2.png" alt="">
            <h3>Approachable</h3>
            <p>Builds on top on standard HTML, CSS and Javascript with intuitive API and world-class documentation.</p>
        </div>
        <div class="card">
            <img src="../../images/USP-3.png" alt="">
            <h3>Versatile</h3>
            <p>A rich, incrementally adoptable ecosystem that scales between a library and a full-featured network.</p>
        </div>
    </div>
</template>

<style scoped>
    .container {
        display: flex;
        justify-content: space-around;
        margin-top: 5%;
        background-color: #39B983;
        height: 40%;
        padding: 5%;
    }

    .card {
        width: 10%;
        text-align: center;
    }
    h3 {
        margin-top: 5%;
        font-size: 25px;
    }
    p {
        margin-top: 10%;
        font-family: 'Courier New', Courier, monospace;
        font-weight: bold;
    }
</style>

