<template>
    <nav class="menu">
    <ul>
        <li>
            <router-link to="/" tag="li" active-class="active" exact>
                <a>Inicio</a>
            </router-link>    
        </li>
        
        
             <router-link to="/usuario" tag="li" active-class="active" exact>
                <a >Usuario</a>
            </router-link>
           
        
    </ul>
    </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>
