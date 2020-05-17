<template>
	<div class="px-2 pt-2 bg-blue-900"> 
		<div class="bg-white px-5 py-8 md:px-8">
			<div class="flex flex-row justify-between items-center py-4">
				<div><a href="" class="border-8 border-blue-900 py-3 px-3 shadow-md text-lg text-blue-900 font-semibold font-serif transition duration-500 ease-in-out hover:text-white hover:bg-blue-900 transform hover:-translate-y-1 hover:scale-125">MI</a></div>
				<div>
					<a href="" class="font-semibold text-lg px-1 py-2 rounded font-serif text-blue-900 mr-4 transition duration-500 ease-in-out hover:text-white hover:bg-blue-900 transform hover:-translate-y-1 hover:scale-125">Home</a>
					<a href="" class="font-semibold text-lg px-1 py-2 rounded font-serif text-blue-900 mr-4 transition duration-500 ease-in-out hover:text-white hover:bg-blue-900 transform hover:-translate-y-1 hover:scale-125">Blog</a>
					<a href="" class="font-semibold text-lg px-1 py-2 rounded font-serif text-blue-900  transition duration-500 ease-in-out hover:text-white hover:bg-blue-900 transform hover:-translate-y-1 hover:scale-125">Projects</a>
				</div>
			</div>


			<div class="mt-24 md:px-32">
				<h1 class="text-blue-900 text-4xl font-bold font-serif md:text-center">Hi, my name is Mazin.</h1>
				<h1 class="text-blue-900 text-4xl font-bold font-serif md:text-center"> I am a Back / Front End Developer living in AlKlakla city.</h1>
			</div>

			<div class="mt-16">
				<img class="h-full w-full object-cover md:h-64 md:object-cover" src="https://images.unsplash.com/photo-1454165205744-3b78555e5572?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60">
			</div>
			<h1 class="text-center mt-16 text-blue-900 text-4xl font-semibold font-serif md:text-5xl underline">About</h1>
			<div class="mt-8 mb-16 md:mt-8 md:px-8 py-8 border shadow-md rounded-lg bg-blue-100">
				
				<div class="grid grid-cols-2 row-gap-3 md:grid-cols-4">
					<div>
						<Fast class="ml-12 md:mx-24"></Fast>
						<div class="mt-4 px-2 md:px-8">
							<h1 class="mt-2 text-blue-800 text-center font-semibold text-lg md:text-center md:text-2xl">Fast</h1>
							<p class="mt-2 text-blue-800 text-center text-sm font-hairline leading-none md:text-center md:font-normal md:text-lg md:px-2">Fast load times and lag free interaction, my highest priority</p>
						</div>
					</div>

					<div>
						<Lamp class="ml-12 md:mx-24"></Lamp>
						<div class="mt-4 px-2">
							<h1 class="mt-2 text-blue-800 text-center font-semibold text-lg md:text-center md:text-2xl">Intuitive</h1>
							<p class="mt-2 text-blue-800 text-center text-sm font-hairline leading-none md:text-center md:font-normal md:text-lg md:px-2">Strong preference for easy to use, intuitive UX/UI.</p>
						</div>
					</div>


					<div class="mt-8 px-2 md:mt-0">
						<Screen class="ml-12 md:mx-24"></Screen>
						<div class="mt-4">
							<h1 class="mt-2 text-blue-800 text-center font-semibold text-lg md:text-center md:text-2xl">Responsive</h1>
							<p class="mt-2 text-blue-800 text-center text-sm font-hairline leading-none md:text-center md:font-normal md:text-lg md:px-2">My layouts will work on any device, big or small.</p>
						</div>
					</div>

					<div class="mt-8 md:mt-0">
						<Rocket class="ml-12 md:mx-24"></Rocket>
						<div class="mt-4 px-2 md:px-8">
							<h1 class="mt-2 text-blue-800 text-center font-semibold text-lg md:text-center md:text-2xl">Dynamic</h1>
							<p class="mt-2 text-blue-800 text-center text-sm font-hairline  leading-none md:text-center md:font-normal md:text-lg md:px-2">Websites don't have to be static, I love making pages come to life.</p>
						</div>
					</div>                   
				</div>
			</div>
			<h1 class="text-center mt-16 text-blue-900 text-4xl font-semibold font-serif md:text-5xl underline">Deeper details</h1>
			<div class="flex md:flex-row flex flex-col justify-between mt-8 px-8 py-8 gap-2 border rounded-lg shadow-2xl bg-blue-100">
				<div class="md:w-3/4 px-8 mb-8 border-b">
					<div class="flex md:flex-col flex-col items-center">
						<DefalutScreen></DefalutScreen>
						<h2 class="text-3xl mt-2 font-semibold text-gray-900">Back-end</h2>
						<p class="mt-2 font-semibold text-teal-700 text-center">I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
						<h2 class="my-2 text-2xl text-blue-700 font-smeiblod">Things I enjoy building</h2>
						<h3 class="font-semibold text-teal-700 text-center">Web apps, APIs, Tools, Automating things</h3>
						<h4 class="my-2 text-2xl text-blue-700 font-smeiblod">Technology I use</h4>
						<h2 class="font-semibold text-teal-700 ">PHP, Laravel, Mysql</h2>
					</div>

					<div class="w-full bg-grey-200 mt-16">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">PHP</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 70%">70%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Laravel</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 90%">90%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4 mb-3">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Mysql</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 60%">60%</div>
						</div>
					</div>
				</div>


				<div class="md:w-3/4 px-8 mb-4">
					<div class="flex flex-col items-center">
						<DefalutScreen></DefalutScreen>
						<h2 class="text-3xl mt-2 font-semibold text-gray-900">Front-end</h2>
						<p class="mt-2 font-semibold text-teal-700 text-center">I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
						<h2 class="my-2 text-2xl text-blue-700 font-smeiblod">Things I enjoy designing</h2>
						<h3 class="font-semibold text-teal-700 text-center">Elegant and simple UI components</h3>
						<h4 class="my-2 text-2xl text-blue-700 font-smeiblod">Technology I use</h4>
						<h2 class="font-semibold text-teal-700 ">CSS, Javascript, Vue js</h2>
					</div>

					<div class="w-full bg-grey-200 mt-16">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Javascript</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 60%">60%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Vue js</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 70%">70%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">CSS</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 65%">65%</div>
						</div>
					</div>
				</div>



				<div class="md:w-3/4 px-8">
					<div class="flex flex-col items-center">
						<DefalutScreen></DefalutScreen>
						<h2 class="text-3xl mt-2 font-semibold text-gray-900">Mentor</h2>
						<p class="mt-2 font-semibold text-teal-700 text-center">I like to code things from scratch, and enjoy bringing ideas to life in the browser.</p>
						<h2 class="my-2 text-2xl text-blue-700 font-smeiblod">Things I enjoy building</h2>
						<h3 class="font-semibold text-teal-700 text-center">Web apps, APIs, Tools, Automating things</h3>
						<h4 class="my-2 text-2xl text-blue-700 font-smeiblod">Technology I use</h4>
						<h2 class="font-semibold text-teal-700 ">PHP, Laravel, Mysql</h2>
					</div>

					<div class="w-full bg-grey-200 mt-16">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">PHP</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 70%">70%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Laravel</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 90%">90%</div>
						</div>
					</div>

					<div class="w-full bg-grey-200 mt-4">
						<h1 class="mb-2 text-lg font-semibold text-blue-800">Mysql</h1>
						<div class="shadow w-full bg-red-300 mt-2">
							<div class="bg-blue-600 text-xs leading-none py-1 text-center text-white" style="width: 60%">60%</div>
						</div>
					</div>
				</div>

				

				
			</div>
		</div>
	</div>
</template>

<script>
import Screen from '../components/icons/Screen.vue'

import DefalutScreen from '../components/icons/DefalutScreen.vue'

import Fast from '../components/icons/Fast.vue'

import Lamp from '../components/icons/Lamp.vue'

import Rocket from '../components/icons/Rocket.vue'



export default{

	components: {

		Screen,
		Fast,
		Lamp,
		Rocket,
		DefalutScreen
	}

}
</script>