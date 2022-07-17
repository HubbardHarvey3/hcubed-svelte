<div class="px-20">
  <h1 class="text-center my-6">My Work</h1>
  <div class=" grid grid-rows-2 grid-flow-col gap-20 ">
    {#each projects as project }
      <div class="text-center rounded border-2 h-full  border-black ">
        <h1>{project.title}</h1>
        <p class="text-left text-xs">{project.description}</p>
        <h6><a target="blank" href="http://{project.url}">{project.url}</a></h6>
      </div>
    {/each}
  </div>  
</div>

<script lang="ts">
  let projects: {
    url: string,
    description: string,
    title: string 
  }[] = [
    {
      "url": "www.hcubedcoder.com",
      "description": "Super awesome site where I show off the skillz",
      "title": "Portfolio Site"
    },
    {
      "url" : "www.sound-doctrineministry.org",
      "description": "Christian Radio Program, using Angular",
      "title": "Sound Doctrine Ministry"
    },
    {
      "url" : "www.222commission.org",
      "description": "Missionary website hosted with AWS S3 and Cloudfront.",
      "title": "Missionary Website"

    }
  ];
</script>