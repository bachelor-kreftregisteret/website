<script>
    import Header from './components/Header.svelte'
    import Heading from './components/Heading.svelte'
    import Documents from './components/documents/Documents.svelte'
    import Persons from './components/person/Persons.svelte'
    import Footer from './components/Footer.svelte'
</script>

<main>
    <Heading/>
    <Header/>
    <Documents/>
    <Persons/>
    <Footer/>
</main>

<style>
    :global(body) {

    }
	main {
		text-align: center;
		padding: 0;
		margin: 0;
	}

    :global(body) {
        margin: 0;
        padding: 0;
    }

</style>
