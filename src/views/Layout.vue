<template>
	<div class="layout">
		<Header/>
		<router-view/>
		<Footer/>

	</div>
</template>

<script>
    import Header from "../components/Header/index";
    import Footer from "../components/Footer/index";

    export default {
        name: "Layout",
        components: {
            Header,
            Footer
        },

        data() {
            return {
            }
        },



    }
</script>

<style scoped lang="scss">

	.layout {
		display: flex;
		flex-direction: column;
		height: 100vh;
		justify-content: space-between;
	}
</style>
