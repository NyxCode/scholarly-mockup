<script>
  import DeleteOutline from "svelte-material-icons/DeleteOutline.svelte"
  import TimerOutline from "svelte-material-icons/TimerOutline.svelte"
  import ClockPlusOutline from "svelte-material-icons/ClockPlusOutline.svelte"
  import BookmarkBoxMultipleOutline from "svelte-material-icons/BookmarkBoxMultipleOutline.svelte"
</script>

<div class="border bg-gray-100 h-full basis-1/5 border-t-0 shadow-xl z-30">
  <ul class="menu overflow-y-auto text-base-content">
    <!-- Sidebar content here -->
    <li><a><BookmarkBoxMultipleOutline size="1.4em"/>All Entries</a></li>
    <li><a><ClockPlusOutline size="1.4em"/>Recently Added</a></li>
    <li><a class="active"><TimerOutline size="1.4em"/>Recently Read</a></li>
    <li><a><DeleteOutline size="1.4em"/> Trash</a></li>
  </ul>
</div>