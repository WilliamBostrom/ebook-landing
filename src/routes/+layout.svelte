<script>
  import "../app.css"

  //Istället för <slots/> används render och $props 
  let {children} = $props();
</script>

<!-- <h1>Test</h1> -->
{@render children()}