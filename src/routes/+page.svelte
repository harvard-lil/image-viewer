<script lang="ts">
  import { page } from "$app/state";

  let searchParams: URLSearchParams = page.url.searchParams;
  let urlParam: string | null = searchParams.get("url");
</script>
