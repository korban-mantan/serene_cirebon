
<script>
	import Navbar from '../components/navbar.svelte';
	import Content from '../components/homeContent.svelte';
	import Footer from '../components/footer.svelte';
	import '../app.css';
</script>

<Navbar />
<slot />
<Footer />
