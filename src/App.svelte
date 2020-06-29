<script>
import Space from './Space.svelte';
</script>

<main>
 <h1>
 Tic Tac Toe
 </h1>
 <h2>Number of people playing: </h2>
 <h2>Player X</h2>
 <div class="row">
<Space space="X" />
<Space space="X" />
<Space space="X" />
</div>
<div class="row">
<Space space="X" />
<Space space="X" />
<Space space="X" />
</div>
<div class="row">
<Space space="X" />
<Space space="X" />
<Space space="X" />
</div>
<button>New Game</button>
</main>





<style>
main{
    width:475px;
    margin: 0 auto;
    border: 0px black solid;
    height:1000px;
}
.row{
    display: flex;
}
button{
    width:100%;
    margin-top:20px;
    border-radius:0;
    background-color: lightblue;
    font-size:30px;
    cursor:pointer;
    border:none;
}
button:hover{
    outline: none;
}
</style>