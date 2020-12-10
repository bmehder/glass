<nav>
  <div class="nav-wrapper">
    <h1>Logo</h1>
    <ul>
      <li><a href=".">One</a></li>
      <li><a href=".">Two</a></li>
      <li><a href=".">Three</a></li>
    </ul>
  </div>
</nav>

<style>
  nav {
    width: 100%;
    padding: 1.5em 0;
    background: #f06;
    color: white;
  }
  h1 {
    padding-left: 1em;
  }
  .nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 960px;
    margin: auto;
  }
  ul {
    display: flex;
    justify-content: flex-end;
    list-style: none;
  }
  li {
    width: 80px;
    font-weight: 600;
  }
  a {
    color: white;
    text-decoration: none;
  }
  a:hover {
    padding-bottom: 4px;
    border-bottom: 4px solid white;
  }
</style>
