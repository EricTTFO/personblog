<template>
	<div id="app">
		<!--    <img alt="Vue logo" src="./assets/logo.png">-->
		<!--    <AddBlog msg="Welcome to Your Vue.js App"/>-->
		<blog-header></blog-header>
		<!--		<Show-blog></Show-blog>-->
		<!--		-->
		<router-view/>
	
	</div>
</template>

<script>
    import AddBlog from './components/AddBlog.vue'
    import ShowBlog from './components/ShowBlog.vue'
    import BlogHeader from './components/BlogHeader.vue'

    export default {
        name: 'app',
        components: {
            AddBlog,
            ShowBlog,
            BlogHeader
        }
    }
</script>

<style>
	/** {*/
	/*	margin: 0;*/
	/*	padding: 0;*/
	/*}*/
</style>
