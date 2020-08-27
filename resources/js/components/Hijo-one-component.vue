<template>
    <div class="container mt-4">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Componente Hijo Uno</div>

                    <div class="card-body">
                        <input type="text" v-model="nombre" placeholder="Escriba su nombre">
                        <button class="btn btn-success" @click='enviarNombre'>Enviar</button>
                    </div>
                </div>
            </div>
        </div>
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
            enviarNombre(){
                this.$emit('nombre',this.nombre);
            }
        }       
    }
</script>
