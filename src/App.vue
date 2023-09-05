<template>
	<div id="cv" class="mx-auto bg-gray-100">
		<div class="flex flex-wrap  h-full">
			<div class="w-8/12 pt-2">
				<div class="px-4">
					<div class="mx-3 mb-0">
						<div class="flex flex-wrap ">
							<div class="w-2/3 my-auto">
								<div class="text-center">
									<h1 class="h1 font-bold text-4xl">
										Peralta Vázquez Gustavo
									</h1>
									<h3 class="text-gray-400 text-2xl">
										Software Engineer
									</h3>
								</div>
							</div>
							<div class="w-1/3 m-0 p-6 text-center">
								<img
									src="@/assets/avatar.png"
									class="max-w-sm rounded border bg-white p-1 dark:border-neutral-700 dark:bg-neutral-800"
									style="max-height: 150px;" />
							</div>
						</div>
					</div>
					<div>
						<personal-statement />
						<work-experience class="mt-4" />
						<education-section style="page-break-before : always" class="mt-4" />
						<other-projects class="mt-10" />
					</div>
				</div>
			</div>
			<div class="w-4/12 bg-gray-900 pt-5">
				<div class="p-4 pt-5 text-white">
					<contact-details />
					<skills-section />
					<languages-section />
					<hobbies-section />
				</div>
			</div>
		</div>
	</div>
</template>
<script setup>
import SkillsSection from "@/components/SkillsSection.vue";
import PersonalStatement from "@/components/PersonalStatement.vue";
import WorkExperience from "@/components/WorkExperience.vue";
import EducationSection from "@/components/EducationSection.vue";
import OtherProjects from "@/components/OtherProjects.vue";
import ContactDetails from "@/components/ContactDetails.vue";
import LanguagesSection from "@/components/LanguagesSection.vue";
import HobbiesSection from "@/components/HobbiesSection.vue";
</script>