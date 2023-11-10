<script>
    import { Router, Link, Route } from "svelte-routing";
    import Home from "./pages/home.svelte";
    import Contact from "./pages/contact.svelte";

    let url = "";
</script>

<main>
    <Router {url}>
        <Route path="/vajont-school-project/contact" component={Contact} />
        <Route path="/vajont-school-project/"><Home/></Route>
    </Router>
</main>

<style>
    :global(body) { /* this will apply to <body> */ margin: 0; padding: 0; }
</style>
