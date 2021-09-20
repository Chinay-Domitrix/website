<script lang="ts">
  import ChangelogLink from "./changelog-link.svelte";

  export let date: string;
  export let href: string;
</script>

<div class="w-full md:w-4/12">
  <ChangelogLink {href}>
    <span class="mb-xx-small h3 text-black">
      {date}
    </span>
  </ChangelogLink>
</div>
