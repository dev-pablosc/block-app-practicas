<template>
    <!-- component -->
    <header
        class="header sticky top-0 bg-white dark:bg-[#1A2238] shadow-md flex items-center justify-between px-8 py-02 z-20"
    >
        <!-- logo -->
        <h1 class="w-3/12">
            <a href="">
                <svg
                    viewBox="0 0 248 31"
                    class="h-6 w-auto hover:text-green-500 duration-200"
                >
                    <path
                        d="M25.517 0C18.712 0 14.46 3.382 12.758 10.146c2.552-3.382 5.529-4.65 8.931-3.805 1.941.482 3.329 1.882 4.864 3.432 2.502 2.524 5.398 5.445 11.722 5.445 6.804 0 11.057-3.382 12.758-10.145-2.551 3.382-5.528 4.65-8.93 3.804-1.942-.482-3.33-1.882-4.865-3.431C34.736 2.92 31.841 0 25.517 0zM12.758 15.218C5.954 15.218 1.701 18.6 0 25.364c2.552-3.382 5.529-4.65 8.93-3.805 1.942.482 3.33 1.882 4.865 3.432 2.502 2.524 5.397 5.445 11.722 5.445 6.804 0 11.057-3.381 12.758-10.145-2.552 3.382-5.529 4.65-8.931 3.805-1.941-.483-3.329-1.883-4.864-3.432-2.502-2.524-5.398-5.446-11.722-5.446z"
                        fill="#22C55E"
                    ></path>
                    <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M76.546 12.825h-4.453v8.567c0 2.285 1.508 2.249 4.453 2.106v3.463c-5.962.714-8.332-.928-8.332-5.569v-8.567H64.91V9.112h3.304V4.318l3.879-1.143v5.937h4.453v3.713zM93.52 9.112h3.878v17.849h-3.878v-2.57c-1.365 1.891-3.484 3.034-6.285 3.034-4.884 0-8.942-4.105-8.942-9.389 0-5.318 4.058-9.388 8.942-9.388 2.801 0 4.92 1.142 6.285 2.999V9.112zm-5.674 14.636c3.232 0 5.674-2.392 5.674-5.712s-2.442-5.711-5.674-5.711-5.674 2.392-5.674 5.711c0 3.32 2.442 5.712 5.674 5.712zm16.016-17.313c-1.364 0-2.477-1.142-2.477-2.463a2.475 2.475 0 012.477-2.463 2.475 2.475 0 012.478 2.463c0 1.32-1.113 2.463-2.478 2.463zm-1.939 20.526V9.112h3.879v17.849h-3.879zm8.368 0V.9h3.878v26.06h-3.878zm29.053-17.849h4.094l-5.638 17.849h-3.807l-3.735-12.03-3.771 12.03h-3.806l-5.639-17.849h4.094l3.484 12.315 3.771-12.315h3.699l3.734 12.315 3.52-12.315zm8.906-2.677c-1.365 0-2.478-1.142-2.478-2.463a2.475 2.475 0 012.478-2.463 2.475 2.475 0 012.478 2.463c0 1.32-1.113 2.463-2.478 2.463zm-1.939 20.526V9.112h3.878v17.849h-3.878zm17.812-18.313c4.022 0 6.895 2.713 6.895 7.354V26.96h-3.878V16.394c0-2.713-1.58-4.14-4.022-4.14-2.55 0-4.561 1.499-4.561 5.14v9.567h-3.879V9.112h3.879v2.285c1.185-1.856 3.124-2.749 5.566-2.749zm25.282-6.675h3.879V26.96h-3.879v-2.57c-1.364 1.892-3.483 3.034-6.284 3.034-4.884 0-8.942-4.105-8.942-9.389 0-5.318 4.058-9.388 8.942-9.388 2.801 0 4.92 1.142 6.284 2.999V1.973zm-5.674 21.775c3.232 0 5.674-2.392 5.674-5.712s-2.442-5.711-5.674-5.711-5.674 2.392-5.674 5.711c0 3.32 2.442 5.712 5.674 5.712zm22.553 3.677c-5.423 0-9.481-4.105-9.481-9.389 0-5.318 4.058-9.388 9.481-9.388 3.519 0 6.572 1.82 8.008 4.605l-3.34 1.928c-.79-1.678-2.549-2.749-4.704-2.749-3.16 0-5.566 2.392-5.566 5.604 0 3.213 2.406 5.605 5.566 5.605 2.155 0 3.914-1.107 4.776-2.749l3.34 1.892c-1.508 2.82-4.561 4.64-8.08 4.64zm14.472-13.387c0 3.249 9.661 1.285 9.661 7.89 0 3.57-3.125 5.497-7.003 5.497-3.591 0-6.177-1.607-7.326-4.177l3.34-1.927c.574 1.606 2.011 2.57 3.986 2.57 1.724 0 3.052-.571 3.052-2 0-3.176-9.66-1.391-9.66-7.781 0-3.356 2.909-5.462 6.572-5.462 2.945 0 5.387 1.357 6.644 3.713l-3.268 1.82c-.647-1.392-1.904-2.035-3.376-2.035-1.401 0-2.622.607-2.622 1.892zm16.556 0c0 3.249 9.66 1.285 9.66 7.89 0 3.57-3.124 5.497-7.003 5.497-3.591 0-6.176-1.607-7.326-4.177l3.34-1.927c.575 1.606 2.011 2.57 3.986 2.57 1.724 0 3.053-.571 3.053-2 0-3.176-9.66-1.391-9.66-7.781 0-3.356 2.908-5.462 6.572-5.462 2.944 0 5.386 1.357 6.643 3.713l-3.268 1.82c-.646-1.392-1.903-2.035-3.375-2.035-1.401 0-2.622.607-2.622 1.892z"
                        fill="currentColor"
                    ></path>
                </svg>
            </a>
        </h1>

        <!-- navigation -->
        <nav class="nav font-semibold">
            <ul class="flex items-center">
                <li
                    class="relative p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                    :class="{
                        ' text-green-500 border-opacity-100':
                            $route.name === 'infraestructura',
                    }"
                    @mouseover="optionsInstituto = true"
                    @mouseleave="optionsInstituto = false"
                >
                    <span class="block">El instituto</span>
                    <div
                        v-if="optionsInstituto"
                        class="absolute top-full left-0 mt-0 bg-white dark:bg-[#1A2238] shadow-md rounded border border-gray-300 dark:border-[#121726] text-white text-sm z-30 whitespace-nowrap"
                    >
                        <!-- Aquí van tus opciones de menú -->
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Quienes somos</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Misión y visión</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Personal ICTA</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Contacto</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Portafolio de servicios</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Noticias</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Calidad</a
                        >
                    </div>
                </li>
                <li
                    class="relative p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                    :class="{
                        ' text-green-500 border-opacity-100':
                            $route.name === 'infraestructura',
                    }"
                    @mouseover="optionsInfraestructura = true"
                    @mouseleave="optionsInfraestructura = false"
                >
                    <span class="block">Infraestructura</span>
                    <div
                        v-if="optionsInfraestructura"
                        class="absolute top-full left-0 mt-0 bg-white dark:bg-[#1A2238] shadow-md rounded border border-gray-300 dark:border-[#121726] text-white text-sm z-30 whitespace-nowrap"
                    >
                        <!-- Aquí van tus opciones de menú -->
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Laboratorios</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Plantas</a
                        >
                    </div>
                </li>

                <li
                    class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                    :class="{
                        ' text-green-500 border-opacity-100':
                            $route.name === 'investigacion',
                    }"
                >
                    <router-link to="investigacion">Investigacion</router-link>
                </li>

                <li
                    class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                >
                    <router-link to="404">404</router-link>
                </li>
                <li
                    class="p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                ></li>

                <!-- nav bar de extension -->
                <li
                    class="relative p-4 border-b-2 border-green-500 border-opacity-0 hover:border-opacity-100 hover:text-green-500 duration-200 cursor-pointer"
                    :class="{
                        ' text-green-500 border-opacity-100':
                            $route.name === 'extension',
                    }"
                    @mouseover="optionsExtension = true"
                    @mouseleave="optionsExtension = false"
                >
                    <span class="block">Extension</span>
                    <div
                        v-if="optionsExtension"
                        class="absolute top-full left-0 mt-0 bg-white dark:bg-[#1A2238] shadow-md rounded border border-gray-300 dark:border-[#121726] text-white text-sm z-30 whitespace-nowrap"
                    >
                        <!-- opciones de menu -->
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Educaci&oacute;n continua y permanente</a
                        >
                        <a
                            href="#"
                            class="block px-4 py-2 text-gray-500 dark:text-gray-400 dark:hover:text-green-500 hover:text-green-500"
                            >Consultor&iacute;as, asesor&iacute;as e interventor&iacute;as</a
                        >
                    </div>
                </li>
                
            </ul>
        </nav>

        <!-- buttons --->
        <div class="w-3/12 flex justify-end">
            <button
                class="text-[#1A2238] hover:bg-gray-200 dark:bg-slate-700 dark:text-white font-bold py-1 px-2 rounded transition-colors duration-300"
                @click="modeDark()"
            >
                <i class="bi bi-brightness-high-fill text-xl" v-if="isDark"></i>
                <i class="bi bi-moon-fill text-xl" v-else></i>
            </button>
        </div>
    </header>
</template>
<script>
import { computed, ref } from 'vue'
import Dropdowns from './../components/Dropdowns.vue'

export default {
    setup() {
        const isDark = ref(false)
        const optionsInstituto = ref(false)
        const optionsInfraestructura = ref(false)
        const modeDark = () => {
            const htmlElement = document.querySelector('html')

            if (htmlElement.classList.contains('dark')) {
                document.querySelector('html').classList.remove('dark')
                isDark.value = false
            } else {
                document.querySelector('html').classList.add('dark')
                isDark.value = true
            }
        }

        return { modeDark, isDark, optionsInstituto, optionsInfraestructura }
    },
    components: { Dropdowns },
}
</script>
