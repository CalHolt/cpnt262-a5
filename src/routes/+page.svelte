<script>
  import Card from "../lib/components/Card.svelte";
  import { landingCardInfo } from "../lib/data.js"
  
  let visible = true;
</script>
<Card {...landingCardInfo}/>
