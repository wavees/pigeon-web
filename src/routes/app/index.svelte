<script>
  import Sidebar from "../../components/Sidebar.svelte"
  import Spinner from "../../components/Spinner.svelte"
  import { onMount } from "svelte";

  let loading = true;

  onMount(() => {
    setTimeout(() => {
      loading = false;
    }, 2000);
  });
</script>

{ #if loading }
  <div style="z-index: 999; width: 100%; height: 100vh;" class="absolute bg-white flex justify-center items-center">
    <div class="flex flex-col justify-center items-center">
      <Spinner size="45" />
      <p class="text-sm">Booting up an application...</p>
    </div>
  </div>
{ /if }

<Sidebar>
  <p>Hello there!</p>
</Sidebar>