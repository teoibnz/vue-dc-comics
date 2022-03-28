<template>
    <div>
        <main>
            <div class="content-wrapper">
                <h1>Content goes Here</h1>
            </div>
        </main>
    </div>
</template>

<script>
export default {
    name : 'ContentIndex'
}
</script>

<style scoped lang="scss">

main{
    background-color: black;
    min-height: 15vh;

}

.content-wrapper{
    width: 80%;
    margin: 0 auto;
    h1{
        color: white;
    }
}
</style>