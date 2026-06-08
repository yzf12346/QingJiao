<script>
  export const prerender = true;
  import { Router } from "@mateothegreat/svelte5-router";
  import Home from "./routes/Home.svelte";

  const routes = [{ component: Home }];
</script>

<Router {routes} basePath="/QingJiao" />
