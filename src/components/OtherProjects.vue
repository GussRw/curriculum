<template>
	<div>
		<h2 class="text-2xl pb-2 font-bold text-gray-800">{{ $t('portfolio.title') }}</h2>
		<div class="pl-4">
			<div>
				<ol class="relative border-l border-gray-200 dark:border-gray-700">
					<li class="ml-4 mt-2">
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Gussuntu</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('portfolio.gussuntu') }}
						</p>
					</li>
					<li class="ml-4 mt-2">
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Ajax Laravel Validator</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('portfolio.alv') }}
						</p>
					</li>
					<li class="ml-4 mt-2">
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Ban Abuse IPs</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('portfolio.banIP') }}
						</p>
					</li>
					<li class="ml-4 mt-2">
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">BBVA TPV</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('tpv') }}
						</p>
					</li>
					<li class="ml-4 mt-2">
						<h3 class="text-lg font-semibold text-gray-900 dark:text-white">Prefects</h3>
						<p class="text-base font-normal text-gray-500 dark:text-gray-400">
							{{ $t('portfolio.prefects') }}
						</p>
					</li>
				</ol>
			</div>
		</div>
	</div>
</template>