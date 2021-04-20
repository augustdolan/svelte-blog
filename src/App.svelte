<!-- App.svelte -->
<script>
  import BlogPostList from "./components/BlogPostList.svelte";
  import NavBar from './components/NavBar.svelte';
  let activeTab = 'home';

  const changeTab = (tab) => {
    activeTab = tab;
  }
</script>
<style>
 h1 {
   font-size: 30px;
 }
</style>

<div>
  <h1>"WELCOME TO HELL" -Zarah probably</h1>
  <NavBar changeTab={changeTab}/>
  <BlogPostList activeTab={activeTab} />
</div>
