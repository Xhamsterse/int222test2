<template>
    <div class="flex-col w-full md:flex md:flex-row md:min-h-screen">
        <div class="flex flex-col flex-shrink-0 w-full text-gray-700 bg-yellow-300 md:w-64">
            <div class="flex flex-row items-center justify-between flex-shrink-0 px-8 py-4">
                <p
                    class="text-2xl tracking-widest text-black uppercase rounded-lg focus:outline-none focus:shadow-outline"
                >Admin</p>
                <button class="rounded-lg md:hidden focus:outline-none focus:shadow-outline">
                    <svg fill="currentColor" viewBox="0 0 20 20" class="w-6 h-6">
                        <path
                            x-show="!open"
                            fill-rule="evenodd"
                            d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM9 15a1 1 0 011-1h6a1 1 0 110 2h-6a1 1 0 01-1-1z"
                            clip-rule="evenodd"
                        />
                        <path
                            x-show="open"
                            fill-rule="evenodd"
                            d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                            clip-rule="evenodd"
                        />
                    </svg>
                </button>
            </div>
            <div class="flex-grow px-4 pb-4 md:block md:pb-0 md:overflow-y-auto">
                <NuxtLink to="dashboard">
                    <div
                        class="block px-4 py-2 mt-2 text-sm text-black rounded-lg hover:text-gray-500 focus:text-gray-900 hover:bg-yellow-200 focus:outline-none focus:shadow-outline"
                    >Dashboard</div>
                </NuxtLink>
                <NuxtLink to="form">
                    <div
                        class="block px-4 py-2 mt-2 text-sm text-black rounded-lg hover:text-gray-500 focus:text-gray-900 hover:bg-yellow-200 focus:outline-none focus:shadow-outline"
                    >Forms</div>
                </NuxtLink>
                <NuxtLink to="/">
                    <div
                        class="block px-4 py-2 mt-2 text-sm text-black rounded-lg hover:text-gray-500 focus:text-gray-900 hover:bg-yellow-200 focus:outline-none focus:shadow-outline"
                    >Voucher</div>
                </NuxtLink>
                <NuxtLink to="/">
                    <div
                        class="block px-4 py-2 mt-2 text-sm text-black rounded-lg hover:text-gray-500 focus:text-gray-900 hover:bg-yellow-200 focus:outline-none focus:shadow-outline"
                    >Accommodation</div>
                </NuxtLink>
            </div>
        </div>

        <div class="flex flex-col flex-1 w-full">
            <div class="h-full overflow-y-auto">
                <div class="container grid px-6 mx-auto">
                    <h2 class="my-6 text-2xl text-gray-700">Form</h2>

                    <!-- New Table -->
                    <div class="w-full overflow-hidden rounded-lg shadow-xs">
                        <div class="w-full overflow-x-auto">
                            <form class="w-full max-w-lg">
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >AccoumodationName</label>
                                        <input
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border border-red-400 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                        />
                                        <p
                                            class="text-base text-red-600"
                                        >Please fill AccoumodationName</p>
                                    </div>
                                </div>
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Description</label>
                                        <textarea
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                        />
                                        <!-- <p class="text-base text-red-600">Please fill Description</p> -->
                                    </div>
                                </div>
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Type</label>
                                        <div class="relative">
                                            <select
                                                class="block w-full px-4 py-3 pr-8 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            >
                                                <option>Hotel</option>
                                                <option>Resort</option>
                                                <option>Homestay</option>
                                            </select>
                                            <div
                                                class="absolute inset-y-0 right-0 flex items-center px-2 text-gray-700 pointer-events-none"
                                            >
                                                <svg
                                                    class="w-4 h-4 fill-current"
                                                    xmlns="http://www.w3.org/2000/svg"
                                                    viewBox="0 0 20 20"
                                                >
                                                    <path
                                                        d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                                                    />
                                                </svg>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Pet</label>
                                        <div class="relative">
                                            <select
                                                class="block w-full px-4 py-3 pr-8 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            >
                                                <option>Yes</option>
                                                <option>No</option>
                                            </select>
                                            <div
                                                class="absolute inset-y-0 right-0 flex items-center px-2 text-gray-700 pointer-events-none"
                                            >
                                                <svg
                                                    class="w-4 h-4 fill-current"
                                                    xmlns="http://www.w3.org/2000/svg"
                                                    viewBox="0 0 20 20"
                                                >
                                                    <path
                                                        d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                                                    />
                                                </svg>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="w-full px-3 mb-6 md:w-1/3 md:mb-0">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Food</label>
                                        <div class="relative">
                                            <select
                                                class="block w-full px-4 py-3 pr-8 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            >
                                                <option>Have</option>
                                                <option>Haven't</option>
                                            </select>
                                            <div
                                                class="absolute inset-y-0 right-0 flex items-center px-2 text-gray-700 pointer-events-none"
                                            >
                                                <svg
                                                    class="w-4 h-4 fill-current"
                                                    xmlns="http://www.w3.org/2000/svg"
                                                    viewBox="0 0 20 20"
                                                >
                                                    <path
                                                        d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"
                                                    />
                                                </svg>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="flex flex-wrap py-4 mb-6 -mx-3">
                                    <div class="w-full px-3 mb-6 md:w-1/2 md:mb-0">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Address</label>
                                        <input
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border rounded appearance-none focus:outline-none focus:bg-white"
                                            type="text"
                                            placeholder="Accommodation Address"
                                        />
                                        <!-- <p
                                            class="text-base text-red-500"
                                        >Please fill Address</p>-->
                                    </div>
                                    <div class="w-full px-3 md:w-1/2">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >District</label>
                                        <input
                                            class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                            placeholder="Accommodation District"
                                        />
                                        <!-- <p
                                            class="text-base text-red-500"
                                        >Please fill Distinct</p>-->
                                    </div>
                                </div>
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3 mb-6 md:w-1/2 md:mb-0">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Sub District</label>
                                        <input
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border rounded appearance-none focus:outline-none focus:bg-white"
                                            type="text"
                                            placeholder="Accommodation Sub District"
                                        />
                                        <!-- <p
                                            class="text-base text-red-500"
                                        >Please fill Address</p>-->
                                    </div>
                                    <div class="w-full px-3 md:w-1/2">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Province</label>
                                        <input
                                            class="block w-full px-4 py-3 leading-tight text-gray-700 bg-gray-200 border border-gray-200 rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                            placeholder="Accommodation Province"
                                        />
                                        <!-- <p
                                            class="text-base text-red-500"
                                        >Please fill Distinct</p>-->
                                    </div>
                                </div>
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Extra Cost</label>
                                        <input
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                        />
                                        <!-- <p
                                            class="text-base text-red-600"
                                        >Please fill Extra Cost</p>-->
                                    </div>
                                </div>
                                <div class="flex flex-wrap mb-6 -mx-3">
                                    <div class="w-full px-3">
                                        <label
                                            class="block mb-2 text-base tracking-wide text-gray-700"
                                        >Google Map URL</label>
                                        <input
                                            class="block w-full px-4 py-3 mb-3 leading-tight text-gray-700 bg-gray-200 border rounded appearance-none focus:outline-none focus:bg-white focus:border-gray-500"
                                            type="text"
                                        />
                                        <!-- <p
                                            class="text-base text-red-600"
                                        >Please fill Google Map URL</p>-->
                                    </div>
                                </div>

                                <div class="w-full mb-6 md:w-1/3 md:mb-0">
                                    <h2>Select an image</h2>
                                    <input type="file" />
                                    <!-- <div
                                        class="relative px-4 py-3 leading-normal text-red-700 rounded-lg"
                                        role="alert"
                                    >
                                        <span
                                            class="absolute inset-y-0 left-0 flex items-center ml-4"
                                        >
                                            <svg class="w-4 h-4 fill-current" viewBox="0 0 20 20">
                                                <path
                                                    d="M10 18a8 8 0 100-16 8 8 0 000 16zM8.707 7.293a1 1 0 00-1.414 1.414L8.586 10l-1.293 1.293a1 1 0 101.414 1.414L10 11.414l1.293 1.293a1 1 0 001.414-1.414L11.414 10l1.293-1.293a1 1 0 00-1.414-1.414L10 8.586 8.707 7.293z"
                                                    clip-rule="evenodd"
                                                    fill-rule="evenodd"
                                                />
                                            </svg>
                                        </span>
                                        <p class="ml-6">Please fill you Image !</p>
                                    </div>
                                    <p
                                        v-if="warnImg"
                                        class="text-xl text-red-400"
                                    >Please fill you Image</p>-->
                                    <img alt class="w-30 h-30" />
                                </div>
                                <div class="flex buttons">
                                    <button
                                        class="p-1 px-4 ml-auto text-white bg-yellow-500 border rounded-lg"
                                    >SAVE</button>
                                    <button
                                        class="p-1 px-4 ml-2 text-white bg-red-500 border rounded-lg"
                                    >CANCEL</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>