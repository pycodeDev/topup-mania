<template>
    <div>
        <!-- Content -->
        Bismillah
        <p>
            {{ nama }}
        </p>
        <button class="border text-red-500" @click.prevent="tambah()" >a</button>
        <br/>

        <Tutorial :dataTutorial="data_tutorial" />

    </div>
</template>

<script>
    export default {
    name: "HomeIndex",
    data() {
        return {
            nama: "Home Index",
            data_tutorial: "Tes anang"
        };
    },
    methods: {
        tambah() {
            this.nama = 1 + 2;
        }
    }
}
</script>