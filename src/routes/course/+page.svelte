<svelte:head>
    <title>Introduction to Bioengineering</title>
    <meta name="description" content="About this app" />
</svelte:head>

<!-- 
- Template should use flexbox or grid?
- height adjustment for site
- float the website down 
- hide side panels after certin size
- Padding around contents
- Translate Markdown into the main contents page
- add example content
-->

<main class="flex-container">
    <div class="sbleft"> 
        <h1>Course Details</h1>
        <h1>Introduction</h1>
        <h1>Lecture 1</h1>
        <h1>Lecture 2</h1>
        <h1>Lecture 3</h1>
        <h1>Lecture 4</h1>
        <h1>Lecture 5</h1>
        <h1>Lecture 6</h1>

    </div>
    <div class="content"> 
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
    </div>
    <div class="sbright"> 
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
        <h1>Introduction</h1>
         
    </div>
</main>

<style>
    main{
        display: flex;
        height: 100%;
    }

    .sbleft{
        margin-top: 70px;
        height: 88vh;
        width: 25%;
        border: 1px solid red;
        background-color: darkgray;
        color: red;
    }

    .content{
        margin-top: 70px;
        height: 88vh;
        width: 60%;
        border: 1px solid red;
        background-color: antiquewhite;
    }

    .sbright{
        margin-top: 70px;
        height: 88vh;
        width: 15%;
        border: 1px solid red;
        background-color: antiquewhite;
    }

    /* main {
        background-color: aliceblue;
        display: flex;
        justify-content: center;
    }

    .content {
        position: fixed;
        height: 100%;
        left: 25%;
        width: 60%;
        flex-basis: 60%;
        margin-top: 70px;
        border: 1px solid yellow;
        background-color: aquamarine;
    }
    .sbleft {
        position: fixed;
        left:0;
        width: 25%;
        margin-top: 70px;
        min-height: 100%;
        background-color: rgb(69, 80, 66);
        border: 1px solid rgb(212, 211, 211);
    }

    .sbright {
        position: fixed;
        right: 0;
        width: 15%;
        margin-top: 70px;
        background-color: bisque;
        min-height: 100%;
    } */
</style>
