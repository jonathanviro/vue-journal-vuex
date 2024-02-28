<template>
    <div class="entry-container mb-3 pointer p-2" 
        @click="$router.push({ name:'entry', params: { id: 10 } })">
        <div class="entry-title d-flex">
            <span class="text-succes fs-5 fw-bold">28</span>
            <span class="mx-1 fs-5">02</span>
            <span class="mx-2 fw-ligth">2024, Miercoles</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum molestias ipsum sit dolorum iure fugit iusto hic beatae, numquam aliquid asperiores nam unde delectus iste doloribus laboriosam, rerum dolorem mollitia.
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    
    &::hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}
</style>