<script>
    import {Link} from "svelte-routing"
</script>

<nav>
	<ul>
		<li><Link to="/">Inicio</Link></li>
		<li><Link to="/articulos">Artítulos</Link></li>
		<li><Link to="/clientes">Clientes</Link></li>
	</ul>
</nav>

<style>
    nav {
        background-color: antiquewhite;
        padding: 20px;
    }
    
    ul {
        display: flex;
        justify-content: space-evenly;
        list-style-type: none;
    }
</style>