<script>
    export let artist;
    export let album;
    export let year;
    export let company;
    export let image;
</script>
<style>
    .image {
        display: inline-block;
    }
    .information {
        display: inline-block;
        vertical-align: top;
        padding: 10px;        
    }    
</style>

<div class="album">
    <div class="image">
        <img src="{image}" alt="{album}" width="300" height="300" /> 
    </div>
    <div class="information">
        <h1>{artist}</h1>
        <h2>{album}</h2>
        <h3>{year}</h3>
        <h3>{company}</h3>
    </div>
</div>