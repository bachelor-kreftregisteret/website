<script>
    export let name;
    export let description;
    export let image;
    export let link;  // For github / linkedin etc.
</script>

<div>
    <h3>{name}</h3>
    <img src="{image}" alt="Picture of {name}">
    <p>{description}</p>
</div>

<style>
    div {
        box-sizing: border-box;
        width: 15em;
        box-shadow: 5px 5px 5px #f4f4f4;
        padding: 0 1em;
        margin: 1em;
        border: solid 1px #e2e2e2;;
        font-family: 'Arial', sans-serif;
    }

    p {

    }
</style>
