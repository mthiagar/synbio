<script>
    import "../app.css";
</script>

<header>
    <div class="navbar bg-base-100">
        <div class="flex-1">
            <a class="btn btn-ghost normal-case text-xl" href="/">SYNBIO.DEV</a>
        </div>
        <div class="flex-none">
            <ul class="menu menu-horizontal px-1">
                <li><a>Start Learning!</a></li>
                <li><a>Other Resources</a></li>
                <li><a>Blog</a></li>
                <li>
                    <details>
                        <summary> More </summary>
                        <ul class="p-2 bg-base-100">
                            <li><a>About</a></li>
                            <li><a>Donate</a></li>
                        </ul>
                    </details>
                </li>
            </ul>
        </div>
    </div>
</header>

<style>
    .navbar {
        position: absolute;
        display: block;
        top: 0;
        width: 10;
        border: 1px solid red;
        z-index: 100;
    }
    .flex-none{
        float: right;
    }
</style>
