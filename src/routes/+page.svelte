<main>
	<h1>
		<span class="app">Applik<br class="mobile" />ations</span><br /><span class="fab"
			>Fabr<br class="mobile" />iken</span
		>
	</h1>
</main>

<style>
	main {
		width: 100vw;
		height: 100vh;
		display: grid;
		place-items: center;
	}

	h1 {
		margin: 0;
		font-size: 13vw;
		line-height: 1.13;
		letter-spacing: -0.025em;
		font-weight: 900;
		color: rgb(var(--text));
		user-select: none;
	}

	span {
		padding: 0 1vw;
	}

	.app {
		color: transparent;
		-webkit-background-clip: text;
		background-clip: text;
		-webkit-box-decoration-break: clone;
		box-decoration-break: clone;
		background-image: linear-gradient(to right bottom, rgb(239, 68, 68), rgb(234, 179, 8));
	}

	.fab {
		color: rgb(var(--primary));
	}

	br {
		user-select: none;
	}

	.mobile {
		display: none;
	}

	@media (orientation: portrait) {
		.mobile {
			display: block;
		}

		h1 {
			font-size: 21vw;
		}
	}

	@media (min-width: 1300px) and (orientation: landscape) {
		.mobile {
			display: none;
		}

		h1 {
			font-size: 8vw;
		}
	}
</style>
