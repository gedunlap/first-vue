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
        padding: 20px;
        list-style-type: none;
        border-radius: 10px;
    }

    li {
        color: white;
    }

</style>