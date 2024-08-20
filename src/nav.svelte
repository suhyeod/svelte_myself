<header class="top">
    <ul>
        <li class="nav">
            <a href="/">
                <ul class="nav_icon">
                    <li></li>
                    <li class="not"></li>
                    <li></li>
                </ul>
            </a>
        </li>
        <li>
            <a href="/">news</a>
        </li>
        <li>
          <a href="/">news</a>
        </li>
    </ul>
</header>

<style>
    :global(*) {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .top a {
      font-size: 20px;
      text-decoration: none;
      color: black;
    }
    .top {
      border-bottom: solid 1px black;
      
    }
    .top > ul {
      display: flex;
      justify-content: space-around;
      height: 80px;
      line-height: 80px;
    }
    .nav {
      display: flex;
      align-items: center;
    }
    
    .nav_icon {
        width: 30px;
    }
    .nav_icon > li {
        background-color: black;
        max-width: 30px;
        height: 2px;
        
    }

    .nav_icon > li:not(.not) {
        width: 100%;
        
    }

    .not {
        width: 70%;
        margin: 10px 0px;
    }
</style>