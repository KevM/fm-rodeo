<script lang="ts">
    import '@brainandbones/skeleton/themes/theme-crimson.css';
    import '@brainandbones/skeleton/styles/all.css';
    import "../app.css";

    import { AppShell, AppBar } from '@brainandbones/skeleton';
</script>
  
<AppShell slotSidebarLeft="bg-surface-500/5 w-56 p-4">
    <svelte:fragment slot="header">
        <!-- Insert the App Bar: -->
        <AppBar>
            <svelte:fragment slot="lead">
                <h1>Fm.Rodeo</h1>
            </svelte:fragment>
            <svelte:fragment slot="trail">
                <a class="btn btn-sm" href="https://github.com/kevm/fm-rodeo" target="_blank" rel="noreferrer">GitHub</a>
            </svelte:fragment>
        </AppBar>
        <!-- --- -->
    </svelte:fragment>

    <svelte:fragment slot="sidebarLeft">
	<!-- Insert the list: -->
	<nav class="list-nav">
		<ul>
			<li><a href="/#welcome">Home</a></li>
            <li><a href="/about">About</a></li>
			<li><a href="/#cast">Cast</a>
                <ul class="ml-2">
                    <li><a href="/kevm">Kevin</a></li>
                    <li><a href="/buzzbuzzplays">Buzz</a></li>
                </ul>
            </li>
        </ul>
	</nav>
	<!-- --- -->
    </svelte:fragment>

    <!-- Page Content Slot -->
    <slot />

</AppShell>