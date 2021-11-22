<script>
	let user = "John doe"
	function halo(){
		alert("Hallo "+user)
	}
</script>

<style>
</style>

<div class="bg-blue-200 h-full flex">
	<div class="m-auto">
		<div class="text-4xl">
			Svelte + Tailwindcss + capacitor starter template 
		</div>
		<div class="flex mt-8">
			<button on:click="{halo}" class="rounded-lg m-auto bg-green-400 hover:bg-green-500 text-xl text-white py-1 px-16">
				say hallo..
			</button>
		</div>
		<div class="mt-3">
			this svelte use white vite & also include routify as router
		</div>
	</div>
</div>

