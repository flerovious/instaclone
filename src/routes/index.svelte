<script lang="ts">
  import Navbar from '$lib/components/Navbar.svelte';
  import Post from '$lib/components/Post/Post.svelte';
</script>

<svelte:head>
  <title>Instaclone</title>
</svelte:head>

<div class="bg-neutral-50 min-h-screen">
  <Navbar />
  <Post />
</div>
