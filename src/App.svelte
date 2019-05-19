<script>
  let value = 0;
  function handleClick() {
    value += 1;
  }
</script>

<button on:click="{handleClick}">
  Clicked {value} {value === 1 ? 'time' : 'times'}
</button>
<input type="number" bind:value />
