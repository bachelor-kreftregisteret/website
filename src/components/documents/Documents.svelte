<script>
    import Document from './Document.svelte'
</script>

<div>
    <Document file="documents/Statusrapport.pdf" title="Statusrapport" description="Tidlig status på hva vi har gjort for å skaffe et prosjekt"/>
    <Document file="documents/Prosjektskisse.pdf" title="Prosjektskisse" description="Skisse av prosjektet og info om arbeidsgiver"/>
    <Document file="documents/Forprosjektrapport.pdf" title="Forprosjekt" description="Analyse av prosjektet og planlegging av arbeidet"/>
    <Document file="" title="Prosjektrapport" description="Sluttdokumentasjonen av prosessen"/>
</div>

<style>
    div {
        display: flex;
        flex: 0 0 100%;
        flex-flow: row wrap;
        justify-content: center;
        background-color: #000064;
        padding: 1em 0;
        margin-bottom: 2em;
    }
</style>
