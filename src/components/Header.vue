<script setup>
import {ArrowRightIcon, ChevronDoubleDownIcon} from '@heroicons/vue/solid'
</script>
<template>
	<section class="bg-gray-200 flex flex-col justify-center items-center md:px-20 min-h-screen">
		<div class="flex flex-col w-full py-12 px-4 lg:px-0 justify-center items-center">
			<p class="text-2xl text-gray-800 font-medium">哈囉！我是<span class="text-blue-400">林子皓</span></p>
			<h1 class="text-5xl text-right text-gray-800 mt-1 font-extrabold">
				我是一個遊手好閒的房間隱士
			</h1>
			<p class="text-lg text-gray-600 font-light pt-8">
				[關在房間裡最適合我]
			</p>
			<a
				href="#contact"
				class="mt-3 flex items-center text-xl font-regular pb-2">
				聯絡資訊
				<ArrowRightIcon class="ml-1 w-5 h-5"/>
			</a>
		</div>

		<a href="#activities" class="animate-bounce cursor-pointer">
			<chevron-double-down-icon class="w-16 h-16"/>
		</a>
	</section>
</template>
