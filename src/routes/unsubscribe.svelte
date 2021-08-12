<script>
  import OpenGraph from "../components/open-graph.svelte";
  import GitpodIllustration from "../components/gitpod-illustration.svelte";
</script>

<style type="text/postcss">
  header {
    @apply max-w-full !important;
  }

  h1 {
    @apply text-h3 !important;
    @media (max-width: 1040px) {
      @apply mt-medium;
    }
  }
</style>

<OpenGraph
  data={{
    title: "Unsubscribed",
    description: "",
    norobots: true,
  }}
/>

<header class="card shadow-xl mb-32 text-center sm:mx-8">
  <h1 class="h5">Unsubscribed</h1>
  <p class="max-w-2xl text-large mx-auto">
    You have been sucessfully unsubscribed. If you would like to revert it,
    please go to <a
      href="https://gitpod.io/notifications"
      target="_blank"
      rel="nofollow">gitpod.io/notifications</a
    >.
  </p>
  <GitpodIllustration />
</header>
