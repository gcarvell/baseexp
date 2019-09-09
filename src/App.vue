<template>
	<div id="app">
		<div id="header">
			<img alt="Vue logo" src="./assets/logo.png">
		</div>
		<div id="demographics">
			<p>Put your demographics here pls: <input v-model="message" placeholder="Age"></p>
			<l>
				<li> Generate random id </li>
				<li> Assign condition </li>
				<li> Fields to collect demographics </li>
				<li> Next button </li>
				<li> Save demographics </li>			
			</l>
			<hr>
		</div>
		<div id="instructions">
			<l>
				<li> Get the instruction text for the start screen </li>
				<li> Start button </li>
			</l>
			<hr>
		</div>
		<div id="trial">
			<l>
				<li> Display stimuli </li>
				<li> Collect response </li>
				<li> Give feedback </li>
				<li> Loop through trials </li>
			</l>
			<hr>
		</div>
		<div id="break">
			<l>
				<li> Get break screen text </li>
				<li> Continue button </li>
				<li> Loop through blocks </li>
			</l>
			<hr>
		</div>
		<div id="end">
			<l>
				<li> Get end screen text </li>
				<li> Exit experiment </li>
			</l>
			<hr>
		</div>
	</div>

</template>

<script>
export default {
	name: 'app',
	data: {
		butts: "Butts"
	}
}
</script>