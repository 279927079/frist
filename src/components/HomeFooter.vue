<!-- HomeFooter.vue -->
<template>
	<header class="footer">
		<div class="footer_inner">
			<div class="footer_cont">菜单</div>
		</div>
	</header>
</template>

<style>
	.footer {
		height: 0.88rem;
	}
	.footer_inner {
		position: fixed;
		bottom: 0;
		left: 0;
		right: 0;
		z-index: 99;
		max-width: 640px;
		height: 0.88rem;
		box-sizing: border-box;
		margin: 0 auto;
		padding: 0 0.24rem;
		border-top: 0.02rem solid #80ccd6;
		background-color: #fff;
	}
	.footer_cont {
		text-align: center;
		padding: 0 0.4rem;
		line-height: 0.86rem;
		font-size: 15px;
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;
	}
</style>