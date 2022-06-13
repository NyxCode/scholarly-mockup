<script>
  import TopBar from "./top-bar/TopBar.svelte";
  import Sidebar from "./Sidebar.svelte";
  import TabBar from "./tags/TabBar.svelte";
</script>

<div class="h-full flex flex-col">
  <TopBar/>
  <div class="flex flex-row flex-grow">
    <Sidebar/>
    <div class="basis-4/5">
      <slot/>
    </div>
  </div>
</div>
