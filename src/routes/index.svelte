<script>
  import Header from "./header.svelte"
  import Footer from "./footer.svelte"
  import Portfolio from "./portfolio.svelte"
  import Me from "./me.svelte"
</script>

<div class="h-screen flex flex-col">
  <Header/>
  <div class=" flex flex-col flex-1 overflow-y-auto">
    <div class="flex-1 place-content-center">
      <Me/>
    </div>
    <div class="flex-1">
      <Portfolio/>
    </div>
  </div>
  <div class="">
    <Footer/>

  </div>
  
</div>