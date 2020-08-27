<template>
    <div>
        <hijoOne-component @nombre='enviarNombre'></hijoOne-component>
        <hijoTwo-component :nombre='nombre'></hijoTwo-component>        
    </div>
</template>

<script>
    export default {
        data(){
            return {
                nombre : ''
            }
        },
        methods:{
            enviarNombre(nombre){
                this.nombre = nombre;
            }
        }      
    }
</script>
