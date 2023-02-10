<script>
    import {Route} from "svelte-routing"
    import Inicio from "./Inicio.svelte";
    import Articulos from "./Articulos.svelte";
    import Clientes from "./Clientes.svelte";
</script>

<main>
    <Route path="/" component="{Inicio}"></Route>
    <Route path="/articulos" component="{Articulos}"></Route>
    <Route path="/clientes" component="{Clientes}"></Route>
</main>
