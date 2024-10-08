<script>
	import Watermark from '../lib/components/footer-watermark.svelte';
</script>

<svelte:head>
	<title>Global Guidelines for [BB] Servers</title>
</svelte:head>

<div id="content">
	<h2>Server Guidelines</h2>
	<p>
		These are general guidelines which can be considered global across all servers.<br />
		<strong>Please follow them.</strong>
	</p>
	<p>
		Whilst we consider ourselves more relaxed than other servers, any 'major' offences will be dealt
		with the appropriate punishment.
	</p>

	<ul>
		<li>Common sense is key.</li>
		<ul>
			<li><b>Don't be dumb.</b></li>
			<li>This does include no spamming of any kind.</li>
		</ul>
		<li>
			Use voice chat for talking, not spamming sound bites or enforcing your agendas on others.
		</li>
		<ul>
			<li>When asked to move on from a topic, we ask that you respect the request and change the subject.</li>
		</ul>
		<li>Don't dominate voice chat, allow others to talk too.</li>
		<ul><li>Do not circumvent mutes through others.</li></ul>
		<li>
			Don't be deliberately unhelpful or antagonize others, including telling people to Alt-F4 etc.
		</li>
		<li>No bypassing script enforcer / no third party cheats / exploits.</li>
		<li>No harassment of any kind.</li>
		<ul>
			<li>You can mute via the scoreboard or the /ignore social system so please use it.</li>
		</ul>
		<li>No advertising without prior permission.</li>
		<li>
			Any attempt to circumvent punishments may lead to harsher punishments being applied to your
			account.
		</li>
		<ul>
			<li>Continual attempts may lead to permanent removal from [BB] services.</li>
		</ul>
		<li>
			Don't pose as an Admin or try to represent the Admin team in their absence, use /admin to
			request assistance.
		</li>
	</ul>

	<p>
		<strong
			>Things such as obscene language are allowed as long as it's not aimed at others.
		</strong>
	</p>
	<p>This list is not exhaustive. Follow admin instructions at all times.</p>
	<p>
		These guidelines exist as your <i><strong>only</strong></i> warning, Admins are not required to warn
		you before any punishments are issued.
	</p>
	<hr />
	<p>All punishments must be appealed via the forum board or via the Discord forum, not in-game.</p>
	<p>
		Admins will typically have the bb logo (<img
			id="bblogo"
			src="./bb_admin.png"
			alt="bb admin logo"
		/>)
		<i>or</i> a solid white [BB] tag next to their name. Anyone claiming to be an admin without this
		tag is an imposter.
	</p>
</div>

<Watermark />

<style>
	:global(body) {
		background-image: url('/bg.jpg');
		background-repeat: repeat;
		display: flex;
		justify-content: center;
		align-items: center;
		background-color: #0d0e22;
		color: #ccc;
		font-family: Verdana, Geneva, sans-serif;
	}

	@media only screen and (max-width: 720px) {
		#content {
			max-width: 120vw;
			font-size: 2.5vh;
		}
	}

	#content {
		margin-top: 3px;
		text-align: center;
		background: rgba(255, 255, 255, 0.12);
		backdrop-filter: blur(5px);
		-webkit-backdrop-filter: blur(5px);
		border-radius: 10px;
		border: 1px solid rgba(255, 255, 255, 0.18);
		border-color: rgb(47, 79, 79);
		padding: 20px;
		margin: 20px;
	}

	#content ul {
		text-align: left;
	}

	ul li {
		margin: 3px;
	}

	h2 {
		text-align: center;
	}

	#bblogo {
		height: 1%;
	}
</style>
