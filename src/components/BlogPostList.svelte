<script>
  import BlogPostListEntry from './BlogPostListEntry.svelte'
  export let activeTab;
</script>
<div>
  <h1>YOU HAVE ENTERED { activeTab } LAND!!!!!!</h1>
  <BlogPostListEntry activeTab={activeTab}/>
</div>
