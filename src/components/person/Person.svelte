<script>
    export let name;
    export let description;
    export let image;
    export let link;  // For github / linkedin etc.
</script>

<div class="box">
    <p>{name}</p>
    <p>{description}</p>
</div>

<style>
    div {
        box-sizing: border-box;
        width: 15em;
        border: 5px solid #000064;
        border-radius: 1em;
        box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.2);
        padding: 0 1em;
        margin: 1em;
        background-color: #F4F4F4;
    }

    p {

    }
</style>
