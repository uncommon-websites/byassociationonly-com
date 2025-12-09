<script lang="ts">
	import "../app.css";
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<div class="bg-[#0e0e0e] min-h-screen text-[#f3f3f3] selection:bg-white selection:text-black">
    <Header />
    <main>
        <slot />
    </main>
    <Footer />
</div>
