<script>
  import Close from "svelte-material-icons/Close.svelte";

  export let title;
</script>


<div class="flex flex-row px-3 border-r h-10">
  <div class="flex flex-col justify-center">
    <span class="mr-3">{title}</span>
  </div>
  <div class="flex flex-col justify-center">
    <Close size="1.4em"/>
  </div>
</div>