<template>
    <section class="home hero is-fullheight">
    	<div class="hero-body">
    		<div class="container">
    			<h1 class="title">
    				text
    			</h1>
    			<h2 class="subtitle">
    				subtext
    			</h2>
    		</div>
    	</div>
    </section>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'
import HelloWorld from '@/components/HelloWorld.vue'

@Component({
	components: { HelloWorld }
})

export default class Home extends Vue {
  
}
</script>

<style>
</style>
