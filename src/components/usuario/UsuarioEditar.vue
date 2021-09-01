<template>
    <div class="usuario-editar">
        <h3>editar usuario</h3>
         <p><strong>Codigo:editar</strong>{{ id }}</p>
         <p><strong>Completo:</strong>{{$route.query.completo?'sim':'não'}}</p>
         <p><strong>Lingua:</strong>{{$route.query.lingua}}</p>
    </div>
</template>

<script>
export default {
     props:['id'],

}
</script>

<style>

</style>
