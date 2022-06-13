<script>
  import CurrentUser from "./CurrentUser.svelte";
  import SearchBar from "./SearchBar.svelte";
</script>

<div class="flex flex-row justify-between p-3 border-b bg-base-100 z-40">
  <div class="flex flex-row basis-1/2">
    <img src="/logo.svg" width="100px" class="mr-6"/>
    <div class="flex flex-col justify-center">
      <span class="text-3xl font-bold">
        Scholarly
      </span>
    </div>
  </div>
  <div class="flex flex-row justify-end basis-1/3">
    <SearchBar/>
    <CurrentUser/>
  </div>
</div>