# web-development-wk5
website tests

* {
    margin: 0;
    padding: 0;
}

body {
    width: 100%;
    height: 100dvh;
    background-color: rgb(97, 25, 117);
}

header, footer {
    height: 15%;
    background-color: rgb(49, 0, 62);
    padding-left: 5%
}

main {
    height: 80%;
    background-color:  rgb(238, 175, 255);
}

section:first-child {
    /* first-child should be the sidebar section */
    width: 30%;
    min-width: 300px;
    background-color: aliceblue;
}

section {
    height: 100%;
}

section {
    display: inline-block;