<template>
    <nav class="bg-white shadow" role="navigation">
        <div class="container mx-auto p-4 flex flex-wrap items-center md:flex-no-wrap">
            <div class="mr-4 md:mr-8">
                <a href="#" rel="home">
                    <svg class="w-10 h-10 text-purple-600" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg">
                        <title>TailwindCSS</title>
                        <path fill="currentColor" d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"></path>
                    </svg>
                </a>
            </div>
            <div class="ml-auto md:hidden">
                <button class="flex items-center px-3 py-2 border rounded" type="button">
                    <svg class="h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <title>Menu</title>
                        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/>
                    </svg>
                </button>
            </div>
            <div class="w-full md:w-auto md:flex-grow md:flex md:items-center">
                <ul class="flex flex-col mt-4 -mx-4 pt-4 border-t md:flex-row md:items-center md:mx-0 md:mt-0 md:pt-0 md:mr-4 lg:mr-8 md:border-0">
                    <li>
                        <a class="block px-4 py-1 md:p-2 lg:px-4" href="#" title="Home">
                            <router-link to="/">Home</router-link>
                        </a>
                    </li>
                    <li>
                        <a class="block px-4 py-1 md:p-2 lg:px-4" href="#" title="About">
                            <router-link to="/about">About</router-link>
                        </a>
                    </li>
                    <li>
                        <a class="block px-4 py-1 md:p-2 lg:px-4" href="#" title="Feedback">
                            <router-link to="/feedback">Feedback</router-link>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
name: "Navigation"
}
</script>

<style scoped>

</style>
