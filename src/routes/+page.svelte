<script>
  import Navbar from "../modules/+navbar.svelte";
  import Page from "./home/+page.svelte";
</script>

<style>
  #smooth {
    scroll-behavior: 'smooth';
  }
</style>

<div id="smooth" class="overflow-auto w-auto bg-slate-500">

  <div class="w-full z-10 fixed top-0" >
    <Navbar>

    </Navbar>
  </div>

  <Page>
    
  </Page>
</div>


