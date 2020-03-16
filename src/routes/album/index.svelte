<script>
    import Album from '../../components/Album.svelte';
    //import { createStore } from 'easy-peasy';

    let albums = [
        {
            artist: "Gustavo Cerati",
            album: "Bocanada", 
            year: 1999, 
            company: "BMG",
            image: 'https://cdn-s3.allmusic.com/release-covers/500/0000/114/0000114129.jpg'
        },
        {
            artist: "Gustavo Cerati",
            album: "Ahi vamos", 
            year: 2006, 
            company: "BMG",
            image: 'https://cdn-s3.allmusic.com/release-covers/500/0001/842/0001842168.jpg'            
        },
        {
            artist: "Gustavo Cerati",
            album: "Fuerza natural", 
            year: 2009, 
            company: "BMG",
            image: 'https://cdn-s3.allmusic.com/release-covers/500/0001/044/0001044216.jpg'
        }                
    ];

    //const store = createStore(albums);
    //console.log(store);

</script>
<style></style>


{#each albums as album}
    <Album {...album}></Album>
{/each}