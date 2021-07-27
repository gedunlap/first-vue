<template>
    
    <div class="bigimage">
        <img src="https://i.imgur.com/Qshg5gQ.jpg" alt="Lincoln the dog">
    </div>

</template>

<script>
export default {
    name: 'BigImage'
}
</script>

<style>

    .bigimage {
        width: 100vw;
        display: flex;
        justify-content: center;
        background-color: lightgray;
    }

    img {
        max-width: 600px;
        margin: 20px 0 20px 0;
        border-radius: 20px;
        box-shadow: 10px 5px 5px teal;
    }

    img:hover {
        position: relative;
        right: 50px;
        bottom: 50px;
        box-shadow: 50px 50px 5px teal;
    }

</style>