<template>
    <div>
        <hijoOne-component @mi_eventoNombre='SetNombre'></hijoOne-component>
        <hijoTwo-component :mynombre='nombre'></hijoTwo-component>        
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
            SetNombre(elParametroDeMiHijo){
                this.nombre = elParametroDeMiHijo;
            }
        }      
    }
</script>
