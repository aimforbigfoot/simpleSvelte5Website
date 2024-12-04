<script>
	let asdfasdfasdf = $state(0);
	let b = 4;
    let randomTextIType = $state("asdfasdf")
    


    const whenBtnIsBlicked = (a) => {
        console.log("smth was pressed")
        asdfasdfasdf += 1
    }
</script>

<h1>Welcome to SvelteKit</h1>

<button onclick={whenBtnIsBlicked}>text</button>
{asdfasdfasdf}

<input type="text" bind:value={randomTextIType} />
{randomTextIType}