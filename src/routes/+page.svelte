<script lang="ts">
	import Nav from '../components/navigation/nav.svelte';
	import Footer from '../components/footer/footer.svelte';
	import Header from '../components/header/header.svelte';
	import Post from '../components/post/post.svelte';
	import axios from 'axios';
	import type { AxiosResponse, AxiosError } from 'axios';
</script>

<div class="flex flex-col h-screen ">
	<Header />
	<div class="flex-1 overflow-scroll">
		<!-- <Post />
		<Post />
		<Post />
		<Post />
		<Post />
		<Post />
		<Post />
		<Post /> -->
	</div>
	<Footer />
</div>
