<template>
    <div class="wrapper">
        <Title>A11y | Home</Title>
        <p class="font-sans font-bold text-8xl text-center mt-16 max-sm:mt-12 text-dark max-sm:text-5xl">
            Accessibility <br> Solutions for <br> Web <span class="text-peach">Compliance</span>
        </p>
        <div class="flex justify-center items-center mt-8 font-bold text-lg gap-x-6 max-sm:flex-col max-sm:gap-2">
            <NuxtLink
                class="flex gap-x-2 bg-dark border border-dark rounded-full px-14 py-2 text-white items-center transition-colors get-started max-sm:w-[260px]"
                to="/a11y">Get Started
                <svg width="26" height="24" viewBox="0 0 26 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M13.3019 16L17.4241 12M17.4241 12L13.3019 8M17.4241 12H9.17979M23.6073 12C23.6073 17.5228 18.9934 22 13.3019 22C7.61044 22 2.99658 17.5228 2.99658 12C2.99658 6.47715 7.61044 2 13.3019 2C18.9934 2 23.6073 6.47715 23.6073 12Z"
                        stroke="#F3F3F3" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" />
                </svg>
            </NuxtLink>
            <NuxtLink
                class="flex gap-x-2 px-14 py-2 bg-light rounded-full border border-sky items-center text-dark enterprise max-sm:w-[260px]"
                to="/pricing">Enterprise
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M21 19H23V21H1V19H3V4C3 3.44772 3.44772 3 4 3H14C14.5523 3 15 3.44772 15 4V19H19V11H17V9H20C20.5523 9 21 9.44772 21 10V19ZM5 5V19H13V5H5ZM7 11H11V13H7V11ZM7 7H11V9H7V7Z"
                        class="fill-dark" />
                </svg>
            </NuxtLink>
        </div>
        <p class="text-center mt-4 text-navy font-bold text-xl max-sm:text-base max-sm:font-extrabold max-sm:leading-5">
            Seamlessly Identify and Address <br class="sm:hidden"> Accessibility Barriers <br> Across Any Website
        </p>
        <Highlight />
    </div>
</template>
<style scoped lang="scss">
.wrapper {
    background-image: url('/images/pattern.svg');
}

.get-started {
    svg {
        transition: transform 0.3s ease;
    }

    &:hover {
        @apply bg-navy border-navy;

        svg {
            transform: translateX(5px);
        }
    }
}

.enterprise {
    &:hover {
        @apply bg-sky text-white;


        svg {
            path {
                @apply fill-white;
            }
        }
    }
}
</style>