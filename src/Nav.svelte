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
    /* padding-left: 1em; */
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
    padding: 0em 1em;
    font-weight: 600;
    text-align: right;
  }
  li:last-child {
    padding-right: 0;
  }
  a {
    color: white;
    text-decoration: none;
  }
  a:hover {
    padding-bottom: 8px;
    border-bottom: 4px solid white;
  }
  @media screen and (max-width: 900px) {
    h1 {
      padding-left: 0.75em;
    }
    li:last-child {
      padding-right: 1em;
    }
  }
</style>
