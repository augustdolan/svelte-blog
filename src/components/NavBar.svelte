<script>
  // I technically don't need tabs obj, but is it better that wa?
  export let changeTab;
</script>

<ul>
  <li on:click={() => { changeTab('home') }}>
    Home
  </li>
  <li on:click={() => { changeTab('development')}}>
    Development
  </li>
  <li on:click={() => { changeTab('journal') }}>
    Journal
  </li>
  <li on:click={() => { changeTab('artwork') }}>
    Artwork
  </li>
  <li on:click={() => { changeTab('music') }}>
    Music
  </li>
  <li on:click={() => { changeTab('bass') }}>
    Bass
  </li>
  <li on:click={() => { changeTab('about') }}>
    About
  </li>
</ul>