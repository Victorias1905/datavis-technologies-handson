<script>
	const videos = [
		{ url: 'https://www.youtube.com/watch?v=S4bn6gg-BmE', name: 'Messi' },
		{ url: 'https://www.youtube.com/watch?v=MD6WXsjdcsY', name: 'Ronaldo' },
		{ url: 'https://www.youtube.com/watch?v=yTGr45ZQRdA', name: 'Neymar' }
	];
</script>

<div>
	<h5>Famous soccer players:</h5>
	<!--  -->
</div>
<ul>
{#each videos as item}
<li>{item.name} <a href=({item.url}) target="_blank" rel="noopener noreferrer">{item.url}</a></li>
{/each}
</ul>
