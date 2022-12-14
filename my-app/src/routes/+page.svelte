<script>
  let title = 'Ninja Gaming Guide'
  const updateTitle = () => {
    title = 'Something Different'
  }


</script>



<div class="index">
  <h2>{title}</h2>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id reprehenderit eaque odit sequi deserunt aliquid tempore illo, quas rerum, accusamus fugit recusandae? Ratione sunt praesentium excepturi, quos cupiditate modi esse dignissimos ea impedit fugiat! Adipisci quasi vel alias quod quidem reiciendis assumenda eligendi laborum nemo sed at, nesciunt, officiis distinctio dolorum molestias quos voluptatibus illo hic architecto eum. Sunt laboriosam laudantium eos. Dignissimos libero maiores voluptates eos tenetur. Necessitatibus ipsum nemo quibusdam eaque? Recusandae autem ipsum, deleniti necessitatibus laboriosam voluptatem officiis. Perspiciatis eos iste, obcaecati non facilis ex mollitia expedita qui reiciendis molestias, dolor illum eveniet adipisci doloribus atque quam.</p>

  <button on:click={updateTitle}>change title</button>
  <input type="text" bind:value={title}>

  <a href="/guides">View Guides</a>
  <a href="/about">About</a>
</div>

<style>
.index {
  text-align: center;
  display: block;
  margin: 20px auto;
}

</style>
