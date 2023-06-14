<script>
  import "../app.css";
  import "../app.js";
</script>
<div class="center-align">
    <h5 class="center-align">Welcome to SvelteKit with Beercss</h5>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    <button>Svelte</button>
    <button data-ui="#modal">Modal Default</button>
    <nav class="wrap modal" id="modal">
      <h5>Default modal</h5>
        <div>Some text here</div>
        <nav class="right-align">
          <button class="border">Cancel</button>
          <button>Confirm</button>
        </nav>
    </nav>
</div>

