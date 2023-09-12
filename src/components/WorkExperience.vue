<template>
	<div>
		<h2 class="text-2xl pb-2 font-bold  text-gray-800">{{ $t('workExperience.title') }}</h2>
		<div class="pl-4">
			<div>
				<div class="flex items-center">
					<img style="height: 1.3rem" class="mr-2 mt-1 opacity-75" src="https://avatars.githubusercontent.com/u/14634640?s=200&v=4" alt="" />
					<h3 class="text-xl">CCEO Software Development</h3>
				</div>
				<ol class="relative border-l border-gray-200 dark:border-gray-700">
					<li class="ml-4 mb-3">
						<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700" />
						<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('dates.jul') }} 2022 - {{ $t('dates.present') }}</time>
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">{{ $t('workExperience.cceo.cto.position') }}</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('workExperience.cceo.cto.responsibilities') }}
						</p>
					</li>
					<li class="ml-4">
						<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700" />
						<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('dates.sep') }} 2017 - {{ $t('dates.jul') }} 2022</time>
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">{{ $t('workExperience.cceo.developer.position') }}</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('workExperience.cceo.developer.responsibilities') }}
						</p>
					</li>
				</ol>
			</div>
			<div class="mt-5">
				<div class="flex items-center">
					<img style="height: 1.75rem" class="mr-2 mt-1 opacity-75" src="https://avatars.githubusercontent.com/u/40610817?s=200&v=4" alt="" />
					<h3 class="text-xl">MyShell Software Lab</h3>
				</div>
				<ol class="relative border-l border-gray-200 dark:border-gray-700">
					<li class="ml-4">
						<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700" />
						<time class="mb-1 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">{{ $t('dates.may') }} 2018 - {{ $t('dates.present') }}</time>
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">{{ $t('workExperience.myshell.ceo.position') }}</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('workExperience.myshell.ceo.responsibilities') }}
						</p>
					</li>
				</ol>
			</div>
		</div>
	</div>
</template>