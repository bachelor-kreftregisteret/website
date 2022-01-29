<script>
    import Person from './Person.svelte'
    let dummytext = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras feugiat tellus in lacus tempus vestibulum."
    let dummyimg = "images/dummy_person.png"
</script>

<div class="container">
<Person name="Tom H. Basmo" description={dummytext} image={dummyimg}/>
<Person name="Hajin Barzingi" description={dummytext} image={dummyimg}/>
<Person name="Jørund T. Løvlien" description={dummytext} image={dummyimg}/>
<Person name="Nikola Dordevic" description={dummytext} image={dummyimg}/>
<Person name="Ola G. Berg" description={dummytext} image={dummyimg}/>
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
