<script>
    export let title;
    export let description;
    export let file;
</script>

<div>
    <h3>{title}</h3>
    <p>{description}</p>
    <a href={file} download={title}>Last ned</a>
</div>
<style>
    h3 {
        margin-bottom: 0.5em;
    }
    div {
        display: flex;
        flex-flow: column nowrap;
        box-sizing: border-box;
        width: 15em;
        box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.2);
        padding: 1em;
        margin: 1em;
        background-color: #FFDC00;
    }

    a {
        box-sizing: border-box;
        border: 2px black;
        padding: 0.5em;
        margin: 0.5em 0 1em 0;
        background-color: white;
        color: black;
    }
</style>
