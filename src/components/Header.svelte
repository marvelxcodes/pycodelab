<script lang="ts">
	
</script>

<header class="h-16 w-screen fixed top-0 px-6 md:px-10 flex items-center bg-black border-b">
	<img
		draggable={false}
		src="/logo.png"
		alt="Pycodelab Logo"
		class="h-10 aspect-square select-none"
	/>
	<h1 class="text-white ml-3 font-semibold flex select-none">
		&lt;&nbsp;
		<h3 class="typewriting-effect">PYCODELAB</h3>
		&nbsp;&gt;
	</h1>
	<div class="flex-1 h-full flex items-center justify-end">
		<svg
			xmlns="http://www.w3.org/2000/svg"
			viewBox="0 0 24 24"
			fill="currentColor"
			class="options"
		>
			<path
				fill-rule="evenodd"
				d="M9.53 2.47a.75.75 0 010 1.06L4.81 8.25H15a6.75 6.75 0 010 13.5h-3a.75.75 0 010-1.5h3a5.25 5.25 0 100-10.5H4.81l4.72 4.72a.75.75 0 11-1.06 1.06l-6-6a.75.75 0 010-1.06l6-6a.75.75 0 011.06 0z"
				clip-rule="evenodd"
			/>
		</svg>

		<svg
			xmlns="http://www.w3.org/2000/svg"
			viewBox="0 0 24 24"
			fill="currentColor"
			class="options"
		>
			<path
				fill-rule="evenodd"
				d="M14.47 2.47a.75.75 0 011.06 0l6 6a.75.75 0 010 1.06l-6 6a.75.75 0 11-1.06-1.06l4.72-4.72H9a5.25 5.25 0 100 10.5h3a.75.75 0 010 1.5H9a6.75 6.75 0 010-13.5h10.19l-4.72-4.72a.75.75 0 010-1.06z"
				clip-rule="evenodd"
			/>
		</svg>

		<svg
			xmlns="http://www.w3.org/2000/svg"
			viewBox="0 0 24 24"
			fill="currentColor"
			class="options"
		>
			<path
				fill-rule="evenodd"
				d="M4.5 5.653c0-1.426 1.529-2.33 2.779-1.643l11.54 6.348c1.295.712 1.295 2.573 0 3.285L7.28 19.991c-1.25.687-2.779-.217-2.779-1.643V5.653z"
				clip-rule="evenodd"
			/>
		</svg>
	</div>
</header>

<style>
	@keyframes carnet-blink {
		0% {
			opacity: 0;
		}
		30% {
			opacity: 1;
		}
	}

	@keyframes text {
		0% {
			width: 0%;
		}
		30% {
			width: 100%;
		}
	}

	.typewriting-effect {
		position: relative;
		animation: text 5s infinite;
		overflow-x: hidden;
	}

	.typewriting-effect::after {
		content: "|";
		width: 1px;
		height: 100%;
		animation: carnet-blink 1s infinite;
	}
</style>
