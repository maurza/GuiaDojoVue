<template>
    <v-card>
        <h1>Aquí van las imagenes</h1>
        <button @click="imprimir">Imprimir</button>
    </v-card>
</template>

<script>
export default {
    name : 'ImageList',
    props: ["items"],
    methods:{
       imprimir(){
           console.log(this.items)
       }
    }
}
</script>