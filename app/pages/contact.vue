<template>
	<div class="w-10/12 m-auto flex flex-col max-sm:w-full">
		<Title>A11y | Contact</Title>
		<div class="wrapper"></div>
		<div
			class="w-6/12 border border-sky bg-light/20 rounded-2xl max-sm:rounded max-w-[90vw] m-auto mt-20 p-10 shadow-md shadow-sky max-sm:mt-10 max-sm:p-5 max-sm:w-full"
		>
			<h2 class="text-lg uppercase font-serif ml-2">A11Y</h2>
			<h1
				class="font-sans font-bold text-6xl text-left max-sm:mt-6 text-dark max-sm:text-5xl ml-2"
			>
				Contact <span class="text-peach">Me</span>
			</h1>
			<p class="p-2 mt-4">
				Hey there! I'm always happy to hear from you. If you have any questions, or feedback
				or just want to say hi, feel free to reach out to me. Go ahead book a meeting using
				the button below.
			</p>
			<Booker class="m-auto mt-4" />
		</div>
	</div>
</template>
<style scoped>
.wrapper {
	z-index: -1;
	position: absolute;
	top: 0;
	left: 0;
	padding-top: 5rem;
	min-width: 100vw;
	min-height: 100vh;
	background: radial-gradient(100.76% 179.14% at -2.4% -2.78%, #ffffff 25.3%, #e0fbfc 100%);
}
.shadow-md.shadow-sky {
	box-shadow: 2px 4px 10px rgba(152, 193, 217, 0.25);
	backdrop-filter: blur(10px);
}
</style>
