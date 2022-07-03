<script lang="ts">
</script>

<nav class="flex flex-row justify-evenly items-center px-32 shadow-sm bg-white">
  <div class="basis-3/12 flex flex-row justify-start h-14">
    <p class="text-4xl self-center font-['Cookie']">Instaclone</p>
  </div>

  <label class="relative h-14 basis-5/12 flex flex-row items-center px-12">
    <span class="sr-only">Search</span>
    <span class="absolute flex items-center pl-2">
      <i class="bi bi-search ml-4 justify-self-start text-gray-500 text-sm" />
    </span>
    <input
      class="placeholder:text-slate-400 block bg-gray-100 h-8 w-full pl-14 rounded-md
        shadow-sm focus:outline-none focus:ring-0 sm:text-sm"
      placeholder="Search"
      type="text"
      name="search"
      autocomplete="off"
    />
  </label>

  <div class="basis-4/12 flex flex-row justify-evenly items-center h-14">
    <a href="/">
      <i class="bi bi-house-door-fill text-2xl" />
    </a>
    <a href="/">
      <i class="bi bi-send text-xl" />
    </a>
    <a href="/">
      <i class="bi bi-plus-square text-xl" />
    </a>
    <a href="/">
      <i class="bi bi-compass text-xl" />
    </a>
    <a href="/">
      <i class="bi bi-heart text-xl" />
    </a>
    <a href="/">
      <i class="bi bi-person-circle text-xl text-gray-400" />
    </a>
  </div>
</nav>
