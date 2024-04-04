<script lang="ts">
  import type { PageData } from "./$types";

  export let data: PageData;

  const { name } = data;
</script>

<h1>Welcome, {name}</h1>
