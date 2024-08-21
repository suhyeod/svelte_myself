<script>
</script>

<header>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">skills</a></li>
            <li><a href="/">contact</a></li>
        </ul>
    </nav>
</header>
<main>
    <div>
        <img class="main_img" src="/src/img/IMG_0230.jpg" alt="사진">
    </div>
</main>


<style>
    :global(*){
        padding: 0;
        margin: 0;
        list-style: none;
        text-decoration: none;
        
    }
    header{
        position: fixed;
        top: 0;
        right: 0;
    }
    nav ul{
        display: flex;
        float: right;
        justify-content: space-around;
        width: 800px;
        padding: 26px 0px;
        background-color: black;
        opacity: 0.6;
        border-radius: 0 0 0 20px;
        font-size: 16px;
        box-shadow: 1px black;
        
    }
    nav a {
        color: grey;
    }
    nav ul:hover {
        box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
        cursor: pointer;
        transition: 0.3s;
    }
    nav a:hover{
        color: white;
        transition: 0.1s;
    }
    
    
</style>