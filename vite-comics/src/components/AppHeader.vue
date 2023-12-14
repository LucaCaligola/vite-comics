<template lang="">
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="Logo">
            </div>

            <ul>
                <li>Chharacters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>tv</li>
                <li>games</li>
                <li>collectibles</li>
                <li>videos</li>
                <li>fans</li>
                <li>news</li>
                <li>shop</li>

            </ul>


        </div>




    </header>
</template>
<script>
export default {
    name: 'AppHeader',
    
}
</script>

<style lang="scss" scoped>

header {
    height: 100px;
    width: 100%;
}
.container {
    height: 100%;
    width: 70%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 auto;
}

ul {
    display: flex;
    list-style: none;
}


li {
      margin-left: 1rem;
      text-transform: uppercase;
      font-size: 12px;
      &:hover {
        color: #0282F9;
        border-bottom: 2px solid #0282f9d3;
      }
    }

    .logo img {
        width: 60px;
    }
    
</style>