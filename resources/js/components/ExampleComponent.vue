<template>
    <div class="container mt-4">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Ejemplo de componente</div>

                    <div class="card-body">
                        <input type="text" v-model="nombre" placeholder="Escriba su nombre">
                        <h2 class="mt-3">Hola:{{nombre}}</h2>
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
        }        
    }
</script>
