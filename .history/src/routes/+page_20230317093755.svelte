<script>
  import Hero from "../components/Hero.svelte";
  import Section from "../components/Section.svelte";
  import Email from "../components/Email.svelte";
</script>

<div>
  <Hero />
  <Section />
  <Email />
  <slot />
</div>
