<script>
    import Person from './Person.svelte'
    let dummytext = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras feugiat tellus in lacus tempus vestibulum. "
</script>

<div class="container">
<Person name="Tom H. Basmo" description={dummytext}/>
<Person name="Hajin Barzingi" description={dummytext}/>
<Person name="Jørund T. Løvlien" description={dummytext}/>
<Person name="Nikola Dordevic" description={dummytext}/>
<Person name="Ola G. Berg" description={dummytext}/>
</div>

<style>
    .container {
        display: flex;
        flex-flow: row wrap;
        justify-content: space-evenly;
        align-items: center;
    }

</style>
