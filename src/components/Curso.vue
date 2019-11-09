<template>
<div>
    <p>Cursos</p>
    <p>Aulas completas: {{aulas}}</p>
</div>
</template>
<script>
import {mapState} from 'vuex';

export default{
    data(){
        return{
            
        }
    },
    computed: mapState(["aulas"]),
    methods:{
        
    }
}
    
</script>
<style>

</style>