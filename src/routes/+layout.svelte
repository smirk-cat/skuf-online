<script lang="ts">
    import Contents from "$lib/components/navigation/contents.svelte";
    import Navbar from "$lib/components/navigation/navbar.svelte";
    import "../app.css";
</script>

<Navbar />
<Contents>
    <slot />
</Contents>