<script>
  let activePage = ''; // Track the active page
</script>

<nav>
  <ul>
    <li class={activePage === 'home' ? 'active' : ''}><a href="/">Home</a></li>
    <li class={activePage === 'scheduling' ? 'active' : ''}><a href="/scheduling">Scheduling</a></li>
    <li class={activePage === 'contact' ? 'active' : ''}><a href="/contact">Contact</a></li>
  </ul>
</nav>

<style>
  nav {
    background-color: #0000008c;
    padding: 1rem;
    display: flex;
    font-family: Arial, sans-serif;
    justify-content: center;
    z-index: 3;
    position: fixed;
    top: 0;
    width: 100%;
    box-sizing: border-box;
  }

  ul {
    list-style: none;
    display: flex;
    gap: 1rem;
    padding: 0;
    margin: 0;
  }

  li {
    padding: 0.5rem 1rem;
  }

  a {
    text-decoration: none;
    color: white;
  }

  .active a {
    font-weight: bold;
    border-bottom: 2px solid white;
  }
</style>
