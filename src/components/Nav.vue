
<script setup lang="ts">

</script>




<template>

	<!-- <div class="fixed w-full md:px-20"> -->
		<nav class=" bg-gray-100 shadow-lg w-full fixed">
			<div class="flex justify-between items-center px-4">
				<div class="flex space-x-8">
					<div>
						<RouterLink to="/">
							<span
								class="block py-4 text-transparent bg-clip-text text-lg font-bold bg-gradient-to-r from-yellow-500 to-fuchsia-500"
							>Koobsade Bus</span>
						</RouterLink></div>
<ul class=" flex items-center justify-center space-x-8 ">
<li>
  <RouterLink to="/Home" class="ml-52 navs">Home </Routerlink>
</li>
<li>
							<RouterLink to="/Home" class="navs">Home</RouterLink>
						</li>
<li>
  <Routerlink to="/Home" class="navs">Contact us </Routerlink>
</li>

</ul>

					</div>
          <div class="space-x-2 flex">
<router-link class="btn"> Login</router-link>
<router-link class="btnsign">sing up</router-link>

          </div>
          </div>
         
          </nav>
          <!-- </div> -->

 
</template>



