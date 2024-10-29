<script>

function handleClick() {
  window.location.href("https://caringh.vercel.app");
}

</script>

<style>

.container {
  display: grid;
  place-items: center;
  gap: 10px;
  height: 100%;
  width: 100%;
}

.bell {
  background: #146a9d;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 800;
}

.black {
  color: black;
}

.redirect {
  background: black;
  width: 400px;

  color: white;
  border-radius: 2px;
  /* width: 100%; */
  margin-right: 10px;
  margin-left: 10px;
  transform: opacity 0.3s ease-in, box-shadow 0.3s ease-in;
}
  
.redirect:hover {
  opacity: 0.8;
  box-shadow: 1px 1px 1px 1px grey;
}
</style>

<div class="container">
  <div>
    <h1 class="bell"> Bell </h1>
  </div>
  <h1 class="black"> Your e-bill is Ready to review </h1>
  <button class="redirect" on:click={handleClick}> CLICK HERE TO CONTINUE </button>
</div>