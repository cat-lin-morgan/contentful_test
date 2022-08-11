<template>
    <div class="header-wrapper">
        <div class="logo">
            <a href="">EXTRA LOGO</a>
        </div>
        <div calss="nav">
            <a href="">BLOG</a>
            <a href="">FAQs</a>
            <button>Apply Rn!</button>
        </div>
    </div>
</template>

<script>

    export default {
        name: 'Header'
    }

</script>

<style scoped>
.header-wrapper {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap; 
    align-items: center;
}

.logo {
    color: black;
}

.logo:hover {
    color: black;
    text-decoration: none;
}

a {
    padding: 0 20px 0 20px;
    color: black;
    font-weight: bold;
}


</style>