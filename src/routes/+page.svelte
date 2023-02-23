<script lang="ts">
	import './globals.sass';
	import Globe from './Globe.svelte';
</script>

<section>
	<h1>CSA</h1>
	<h2>TO THE</h2>
	<h1>WORLD</h1>
	<Globe />
</section>

<style lang="sass">
    h1, h2
        color: white

    :global(.globe)
        position: absolute

    section
        height: 100%
        display: flex
        flex-direction: column
        align-items: center
        justify-content: center

</style>
