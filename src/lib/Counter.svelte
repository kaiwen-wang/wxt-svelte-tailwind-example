<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  class="rounded-lg border border-transparent px-5 py-2.5 text-base font-medium font-inherit bg-[#1a1a1a] cursor-pointer transition-colors duration-250 hover:border-[#646cff] focus:outline-none focus:ring-4 focus:ring-[#646cff]"
  on:click={increment}
>
  count is {count}
</button>
