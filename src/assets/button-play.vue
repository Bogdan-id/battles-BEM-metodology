<template>
<div class="btn-block">
	<svg class="play-btn" width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M14 25.375V9.625L24.5 17.5L14 25.375ZM17.5 0C15.2019 0 12.9262 0.452651 10.803 1.33211C8.67984 2.21157 6.75066 3.50061 5.12563 5.12563C1.84374 8.40752 0 12.8587 0 17.5C0 22.1413 1.84374 26.5925 5.12563 29.8744C6.75066 31.4994 8.67984 32.7884 10.803 33.6679C12.9262 34.5474 15.2019 35 17.5 35C22.1413 35 26.5925 33.1563 29.8744 29.8744C33.1563 26.5925 35 22.1413 35 17.5C35 15.2019 34.5474 12.9262 33.6679 10.803C32.7884 8.67984 31.4994 6.75066 29.8744 5.12563C28.2493 3.50061 26.3202 2.21157 24.197 1.33211C22.0738 0.452651 19.7981 0 17.5 0Z" fill="white"/>
	</svg>
	<span class="play-btn-description">
		<slot name="play-btn-desc"></slot>
	</span>
</div>
</template>

<style scoped>
	.btn-block {
		position: absolute;
		display: inline-flex;
		flex-direction: column;
		align-items: flex-end;
		right: 27px;
		top: 27px;
	}
	.play-btn:hover {
		cursor: pointer;
	}
	.play-btn-description {
		margin-top: 10px;
		font-family: Roboto;
		font-style: normal;
		font-weight: normal;
		font-size: 14px;
		line-height: 20px;
		text-align: center;
		letter-spacing: 0.01em;
		color: white;
	}
</style>