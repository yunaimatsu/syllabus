<template>
    <header>
        <a href="/"><h1>daX syllabus</h1></a>
        <nav>
            <a href="/a"><h2>About</h2></a>
            <a href="/b"><h2>Blog</h2></a>
            <a href="/c"><h2>Contact</h2></a>
        </nav>
    </header>
</template>
<style>
    header {
        /* そもそもの位置の確定 */
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        z-index: 100;
        /* height: var(--header-height); */
        height: 9em;

        /* Design */
        /* background-color: var(--bg-color-l); */
        background-color: #333;
        
        /* Flexbox properties */
        display: flex;
        flex-direction: row;
        align-items: flex-end;
        justify-content: space-between;
        
        /* color: var(--font-color-l); */
        color: #000;

        /* Border */
        /* border-bottom: var(--border-color) 1px solid; */

        /* padding-right: var(--side-space); */
        padding-right: 4em;
        /* padding-left: var(--side-space); */
        padding-left: 4em;
    }

    nav {
        display: flex;
        flex-direction: row;
        align-items: flex-end;
        justify-content: space-between;
        column-gap: 1em;
    }

    a {
		text-decoration: none;
	}
</style>