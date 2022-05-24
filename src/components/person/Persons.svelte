<script>
    import Person from './Person.svelte'
    let dummytext = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras feugiat tellus in lacus tempus vestibulum."
    let dummyimg = "images/dummy_person.png"
</script>

<div class="container">
<Person name="Tom H. Basmo"/>
<Person name="Hajin Barzingi"/>
<Person name="Jørund T. Løvlien"/>
<Person name="Nikola Dordevic"/>
<Person name="Ola G. Berg"/>
</div>

<style>
    .container {
        display: flex;
        flex-flow: row wrap;
        justify-content: space-evenly;
        align-items: center;
        padding-top: 2em;
        padding-bottom: 2em;
        background-color: #FCFCFC;
    }

</style>
