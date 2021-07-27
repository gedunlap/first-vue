<template>
    
    <div class="navbar">
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contact</li>
            <li>Appointments</li>
        </ul>
    </div>

</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>

    .navbar {
        background-color: black;
        height: 100px;
    }

    ul {
        display: flex;
        justify-content: space-between;
        align-items: center;
        list-style: none;
        height: 100px;
        border-radius: 25px;
        padding: 0 20px 0 20px;
    }

    li {
        color: white;
        font-size: 20px;
    }

</style>