<script>
  import { Card } from "m3-svelte";
  import { createEventDispatcher } from "svelte";

  export let data;
  const dispatch = createEventDispatcher();
</script>

<Card type="elevated">
  <div class="flex flex-col lg:flex-row">
    <p class="mr-auto">
      <abbr title="a way of hiding what a program does that might confuse ratrater">
        Obfuscation
      </abbr>
      was detected. Here's a table of the flags:
    </p>
    <table>
      {#each data as obfuscator}
        <tr>
          <td class="border-r border-outline pr-2">{obfuscator.name}</td>
          {#if obfuscator.file}
            <td class="max-w-2xl px-2 font-mono text-primary">
              <button
                on:click={() => dispatch("open", obfuscator.file)}
                class="max-w-full overflow-hidden text-ellipsis"
              >
                {obfuscator.file}
              </button>
            </td>
          {:else}
            <td class="max-w-2xl px-2 font-mono">
              <span class="max-w-full overflow-hidden text-ellipsis">{obfuscator.example}</span>
            </td>
          {/if}
        </tr>
      {/each}
    </table>
  </div>
</Card>
