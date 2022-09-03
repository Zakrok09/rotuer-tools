<nav>
    <a href="/">Home</a>
    <a href="/articlemaker">Article Editor</a>
    <a href="/articlemaker">Link Editor</a>
</nav>



<style lang="scss">
    nav {
        position: absolute;
        width: 100%;
        height: 50px;
        display: flex;
        a {
            padding: 0px 10px;
            color: hsl(0, 0%, 100%);
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            transition: 0.2s all ease-in;
        }

        a:hover {
            background-color: hsla(0, 0%, 0%, 30%);
        }
    }

    * {
        font-family: sans-serif;
    }
</style>