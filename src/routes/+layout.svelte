<script lang="ts">
	import "../app.css";
	import Navbar from "$lib/components/Navbar.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen flex flex-col bg-white font-sans text-notion-gray antialiased selection:bg-[#cce9ff] selection:text-notion-black">
	<Navbar />
	<main class="flex-grow w-full">
		<slot />
	</main>
	<Footer />
</div>
