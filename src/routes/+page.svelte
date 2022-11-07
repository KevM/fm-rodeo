<script lang="ts">
	import { goto } from '$app/navigation';
    import { Avatar } from '@brainandbones/skeleton';
</script>

<div class="container mx-auto p-8 space-y-8">
	<h1 id="welcome">Welcome</h1>
	<p>You've found a great place to listen to amazing rodeos with FM quality.</p>
	<hr />
	<section class="card card-body">
		<p>Thank you for visiting with us. Send us a shout on your favorite social if you like what you see.</p>
	</section>
	<hr />
    <h2 id="cast">Cast of Characters</h2>
    <p>Each of our content creators have their own sub site here at Fm.Rodeo. Please click below to enjoy their creations.</p>
	<section class="flex space-x-4 min">
        <button class="btn bg-primary-500/30 btn-base ring-2 ring-primary-500 ring-inset text-surface-500">
            <a href="/kevm"><Avatar class="mr-4" src="/kevm/avatar.jpg" /> Kevin Miller</a>
        </button>

        <button class="btn bg-primary-500/30 btn-base ring-2 ring-primary-500 ring-inset text-surface-500">
			<a href="/buzzbuzzplays"><Avatar class="mr-4" src="/buzzbuzzplays/avatar.jpg" /> BuzzBuzzPlays</a>
        </button>

    </section>
</div>