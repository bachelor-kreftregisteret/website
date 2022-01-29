<script>
    import Person from './Person.svelte'
</script>

<div>
<Person name="Tom" description="Student"/>
<Person name="Hajin" description="Student"/>
<Person name="Jørund" description="Student"/>
<Person name="Nikola" description="Student"/>
<Person name="Ola" description="Student"/>
</div>

<style>
    div {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        flex-wrap: wrap;
        align-items: center;
    }

</style>
