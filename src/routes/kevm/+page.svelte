<script lang="ts">
    import { Avatar } from '@brainandbones/skeleton';
</script>

<svelte:head>
    <link href="https://toot.community/@kevm" rel="me" />
    <link href="https://github.com/kevm" rel="me" />
    <link href="https://youtube.com/KevinDangerMiller" rel="me" />
    <link href="https://twitter.com/kevm" rel="me" />
</svelte:head>

<div class="container mx-auto p-8 space-y-8">
	<h1>Kevin Miller </h1>
	<p>I am a software creator. I live in a small mid-western town along Lake Michigan. It is beautiful here.</p>
    <p>I'm working on becoming better at creating web sites using Front End frameworks and the open awesomness that is the Web.</p>
    <p>Checkout what I make.</p>
	<section class="flex space-x-4">
      <Avatar class="mr-4" src="/kevm/avatar.jpg" />
      <a rel="me" class="btn btn-filled-primary" href="https://github.com/kevm">GitHub</a>
      <a rel="me" class="btn btn-filled-accent" href="https://toot.community/@kevm">Mastodon</a>
      <a rel="me" class="btn btn-filled-accent" href="https://twitter.com/kevm">Twitter</a>
      <a rel="me" class="btn btn-filled-tertiary" href="https://youtube.com/KevinDangerMiller">YouTube</a>
    </section>
</div>