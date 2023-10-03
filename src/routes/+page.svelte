<main>
	<h1>
		<span class="app">Applikations</span><br /><span class="fab">Fabriken</span>
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
		font-size: 8vw;
		line-height: 1;
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

	@media (orientation: portrait) {
		h1 {
			font-size: 13vw;
		}

		br {
			display: block;
		}
	}
</style>
