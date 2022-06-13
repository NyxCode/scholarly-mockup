<script>
  import Sort from "svelte-material-icons/Sort.svelte"

  export let label;
</script>

<th>
  <div class="flex flex-row justify-between">
    <span>{label}</span>
    <Sort size="1.3em"/>
  </div>
</th>
