<template>
<div>
	<nav class="main-nav">
		<ul>
			<li><router-link :to="{name:'home'}">Home</router-link></li>
			<li><router-link :to="{name:'about'}">About</router-link></li>
			<li><router-link :to="{name:'contact'}">Contact</router-link></li>
			
		</ul>
	</nav>
	
</div>	
</template>

<script>
        

export default{
	name:"Navbar",
	
	data() {
      return {
    
       }
    }

}
</script>	

<style>

</style>