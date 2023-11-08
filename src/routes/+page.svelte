<script>
  import Card from "../lib/components/Card.svelte";
  import { landingCardInfo } from "../lib/data.js"
  import {arrayOfCards} from  "../lib/data.js"
  // allowing cards to be seen 
  let visible = true;
</script>
<h1 class="text-3xl">Importing a single card</h1>
<Card {...landingCardInfo}/>
<h1 class="text-3xl">Using a each loop to render an array of cards</h1>
<main class = "p-6 grid grid-cols-1 gap-4 justify-items-center align-items-center md:grid-cols-2 lg:grid-cols-4">
{#each arrayOfCards as card}
<Card {...card}/>
{/each}
</main>