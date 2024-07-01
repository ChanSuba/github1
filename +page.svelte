<center><h1>Increment and Decrement</h1></center>
<script>
  let count=1;
const increment=()=>{
    count++;
};
const decrement=()=>{
    count--;
};
</script>

<main> 
    <p>{count}</p>
    <button on:click={(increment)=> count++}>+</button>
    <button on:click={(decrement)=> count--}>-</button>
</main>
<style>
    :root{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

    }
    main{
        text-align: center;
        padding: 1em;
        margin: 0 auto;
        color: red;
        font:bolder;
    }
    h1{
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font: bolder;
        color: purple;
        margin: 20px;
        padding: 30px;
        border: 20px;
        border-color: purple;
        border-width: 3px;
        background-color: black;
    }
</style>