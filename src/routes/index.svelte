<script>
  import Header from "./header.svelte"
  import Footer from "./footer.svelte"
  import Portfolio from "./portfolio.svelte"
  import Me from "./me.svelte"
</script>

<div class="h-screen flex flex-col overflow-y-hidden">
  <Header/>
  <div class=" flex flex-col flex-1">
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