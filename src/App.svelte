<script>
    import Header from './components/Header.svelte'
    import Heading from './components/Heading.svelte'
    import Persons from './components/person/Persons.svelte'
</script>

<main>
    <Header/>
    <Heading/>
    <Persons/>
</main>

<style>
    :global(body) {

    }
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

</style>
