<script lang="ts">
  import NavbarLogo from './NavbarLogo.svelte';
  import NavIcons from './NavbarIcons.svelte';
  import SearchBar from './NavbarSearch.svelte';
</script>

<nav class="flex sm:justify-evenly justify-between shadow-sm bg-white sticky top-0 w-auto">
  <NavbarLogo />
  <SearchBar />
  <NavIcons />
</nav>
