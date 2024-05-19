<script setup lang="ts">
defineOgImageComponent('About', {
  headline: 'Greetings 👋',
  title: 'Naim\'s Blog',
  description: 'Dive into web development with me and learn Js, Ts, Vue, Nuxt, Docker, k8s',
  link: '/naim.jpg',
})
</script>

<template>
  <div class="py-5">
    <div class="sm:grid grid-cols-8 px-6 py-5 sm:py-9 gap-5 container max-w-5xl  mx-auto">
      <div class="col-span-5  max-w-md">
        <div class="flex justify-between">
          <div>
            <h1 class="text-xl sm:text-4xl  pb-2 font-bold ">
              Naim Islam
            </h1>

            <div class="my-3 space-x-2 md:space-x-3 pb-10">
              <NuxtLink
                to="https://www.facebook.com/profile.php?id=100006340875655"
                target="_blank"
                class="px-2 py-1 lg:px-3 lg:py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="Github"
              >
                <Icon name="logos:facebook" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://www.linkedin.com/in/islam-naim/"
                target="_blank"
                class="px-2 py-1 lg:px-3 lg:py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="LinkedIn"
              >
                <Icon name="devicon:linkedin" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://x.com/naimahamed5"
                target="_blank"
                class="px-2 py-1 lg:px-3 lg:py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="Twitter"
              >
                <Icon name="skill-icons:twitter" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://www.instagram.com/naim_pko"
                target="_blank"
                class="px-2 py-1 lg:px-3 lg:py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="StackOverflow"
              >
                <Icon name="skill-icons:instagram" size="1em" />
              </NuxtLink>
            </div>
          </div>
          <div class="sm:hidden block col-span-3 pb-5 dark:text-[#F1F2F4]">
            <NuxtImg
              src="/naim.jpg"
              width="125"
              height="115"
              quality="50"
              class="rounded-md"
            />
          </div>
        </div>
        <h3 class="text-base sm:text-3xl font-semibold pb-7 sm:pb-12">
          Open source journalist and Content writer
        </h3>

        <p>An open-source journalist and content writer creates and shares freely accessible and modifiable information. They emphasize transparency, collaboration, and public engagement, using community contributions and open data to produce accurate and ethical content. Their work supports the democratization of information and empowers communities through accessible journalism.</p>
      </div>
      <div class="hidden sm:block col-span-3">
        <NuxtImg
          src="/naim.jpg"
          width="450"
          height="500"
          quality="50"
          class="rounded-md"
        />
      </div>
    </div>
  </div>
</template>
