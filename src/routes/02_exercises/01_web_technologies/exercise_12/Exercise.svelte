<script>
 let clicked = false;
</script>

{#if clicked ===false}
<p> You have to click the button! </p>
{:else}
<p>You have clicked the button! </p>
{/if}


<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	<!--  -->
</div>
