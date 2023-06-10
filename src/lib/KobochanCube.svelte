<div class="cube">
	<div class="front surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
	<div class="back surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
	<div class="right surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
	<div class="left surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
	<div class="top surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
	<div class="bottom surface">
		<img src="kobochan.webp" width="300" height="300" alt="kobochan" loading="lazy" />
	</div>
</div>

<style>
	@keyframes rotation {
		0% {
			transform:  rotateX(-45deg) rotateY(-45deg) rotateZ(0deg);
		}
		100% {
			transform:  rotateX(315deg) rotateY(315deg) rotateZ(0deg);
		}
	}
	.surface {
		width: 100%;
		height: 100%;
		/* opacity: 50%; */
		position: absolute;
	}

	.cube {
        animation:6s linear infinite rotation;
		transform-style: preserve-3d;
		transform-origin: center;
		margin: 130px auto 130px auto;
		width: 300px;
		height: 300px;
	}

	.front {
		background-color: #ccffcc;
		transform: rotateY(-90deg) translateX(50%) rotateY(90deg);
	}

	.back {
		background-color: #ffcccc;
		transform: rotateY(-90deg) translateX(-50%) rotateY(-90deg);
	}

	.right {
		background-color: #ccccff;
		transform: translateX(50%) rotateY(90deg);
	}

	.left {
		background-color: #ffccff;
		transform: translateX(-50%) rotateY(-90deg);
	}

	.top {
		background-color: #ccffff;
		transform: translateY(-50%) rotateX(90deg);
	}

	.bottom {
		background-color: #cccc99;
		transform: translateY(50%) rotateX(-90deg);
	}
</style>
