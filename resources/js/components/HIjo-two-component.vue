<template>
   <div class="container mt-4">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Componente Hijo dos</div>
                    <div class="card-body">                        
                        <h2 class="mt-3">Hola:{{mynombre}}</h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script >
    export default {
        props:['mynombre'],
        data(){
            return {
                
            }
        }        
    }
</script>