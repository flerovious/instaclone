<script lang="ts">
  import Navbar from '$lib/components/Navbar/Navbar.svelte';
  import Post from '$lib/components/Post/Post.svelte';
</script>

<svelte:head>
  <title>Instaclone</title>
</svelte:head>

<div class="bg-neutral-50 h-full">
  <Navbar />
  {#each Array(2) as _, i}
    <Post />
  {/each}
</div>
