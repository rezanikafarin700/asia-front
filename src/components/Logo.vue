<template>
	<div>
		<div class="parent">
			<div class="parent__line">
				<div class="parent__sqr"></div>
				<div class="parent__sqr"></div>
				<div class="parent__sqr"></div>
			</div>
		</div>
	</div>
</template>

<script>
    export default {
        name: "Logo"
    }
</script>

<style scoped lang="scss">

	.parent{
		width: 100px;
		height: 24px;
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 0 0 15px 0;

		&__line{
			width: 100%;
			height: 1px;
			background-color: #999999;
			display: flex;
			justify-content: center;
			align-items: center;
		}

		&__sqr{
			width: 15px;
			height: 15px;
			border: 1px solid #999999;
			transform: rotate(45deg);
			margin: 0 0 0 5px;
		}

	}

</style>
