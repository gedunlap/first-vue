<template>
    
    <div>
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

    ul {
        background-color: black;
        display: flex;
        justify-content: space-between;
        align-items: center;
        list-style: none;
        border-radius: 25px;
        height: 50px;
        padding: 0 20px 0 20px;
    }

    li {
        color: white;
        font-size: 20px;
    }

</style>