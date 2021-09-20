<script lang="ts">
  export let href: string;
</script>

<style type="text/postcss">
  a {
    @apply no-underline;
  }

  a:hover,
  a:focus {
    @apply underline;
    text-decoration-thickness: 2px;
  }
</style>

<a {href} class="text-black font-semibold  transition-all duration-200">
  <slot />
</a>
