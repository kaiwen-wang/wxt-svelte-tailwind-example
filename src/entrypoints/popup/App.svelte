<script lang="ts">
  import svelteLogo from "../../assets/svelte.svg";
  import tailwindlogo from "../../assets/tailwind.svg";
  import Counter from "../../lib/Counter.svelte";
</script>

<main class="">
  <div class="grid grid-cols-3 py-4">
    <a
      class="justify-self-start group"
      href="https://wxt.dev"
      target="_blank"
      rel="noreferrer"
    >
      <img
        src="/wxt.svg"
        class="h-12 group-hover:drop-shadow-[0_0_2em_#54bc4ae0]
      transition duration-300
      "
        alt="WXT Logo"
      />
      <h1 class="mt-1 -translate-x-0.5">WXT</h1>
    </a>
    <a
      class="justify-self-center self-end group"
      href="https://tailwindcss.com/"
      target="_blank"
      rel="noreferrer"
    >
      <img
        src={tailwindlogo}
        class="h-11 group-hover:drop-shadow-[0_0_2em_rgba(98,186,243,0.87)]
    transition duration-300
    -translate-y-px translate-x-px
"
        alt="Tailwind Logo"
      />
      <h1 class="mt-1">Tailwind</h1>
    </a>
    <a
      class="justify-self-end group"
      href="https://svelte.dev"
      target="_blank"
      rel="noreferrer"
    >
      <img
        src={svelteLogo}
        class="h-12 group-hover:drop-shadow-[0_0_2em_#ff3e00aa]
      transition duration-300
      "
        alt="Svelte Logo"
      />
      <h1 class="mt-1">Svelte</h1>
    </a>
  </div>

  <div class="p-8">
    <Counter />
  </div>

  <p class="text-[#888]">Click on the logos to learn more</p>
</main>
