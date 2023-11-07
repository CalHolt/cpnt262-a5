<script>
export let cardTitle;
export let cardDescription;
export let cardImg; 
export let cardLink;
export let altText;
export let visible = true; 
</script>
{#if visible = true}
<figure class="max-w-xs bg-rose-900 hover:bg-rose-950 rounded-3xl p-6">
  <a href="{cardLink}">
  <img class="rounded-2xl" src="{cardImg}" alt="{altText}">
  
  <h3 class="text-white py-2"><strong>{cardTitle}</strong></h3>
 
  <p class="text-white py-2">
    <em>{cardDescription}</em>
  </p>
</a>
</figure> {:else}
<h1>still workin on it </h1>
{/if}