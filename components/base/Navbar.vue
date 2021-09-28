<template>
    <div class="text-black bg-yellow-300 body-font">
        <div class="flex flex-col flex-wrap items-center p-5 mx-auto md:flex-row">
            <NuxtLink
                to="/"
                class="flex items-center mb-4 font-medium text-gray-900 title-font md:mb-0"
            >
                <img class="self-center w-16 h-16" src="../../assets/img/Payvouchertsp.png" />
                <span class="ml-3 text-xl">PayVoucher</span>
            </NuxtLink>
            <div class="flex flex-wrap items-center justify-center text-lg md:ml-auto md:mr-auto"></div>
            <!-- Start search bar -->
            <div class="relative mx-auto lg:block">
                <input
                    class="h-10 px-20 pl-2 text-sm bg-white rounded-lg focus:outline-none"
                    type="search"
                    name="search"
                    placeholder="ค้นหา"
                />
                <button
                    type="submit"
                    class="absolute top-0 right-0 w-10 h-10 p-2 bg-yellow-400 rounded-r-lg button hover:bg-yellow-200 focus:outline-none"
                >
                    <svg
                        class="w-4 h-4 text-gray-600 fill-current"
                        xmlns="http://www.w3.org/2000/svg"
                        version="1.1"
                        id="Capa_1"
                        x="0px"
                        y="0px"
                        viewBox="0 0 56.966 56.966"
                        style="enable-background:new 0 0 56.966 56.966;"
                        xml:space="preserve"
                        width="512px"
                        height="512px"
                    >
                        <path
                            d="M55.146,51.887L41.588,37.786c3.486-4.144,5.396-9.358,5.396-14.786c0-12.682-10.318-23-23-23s-23,10.318-23,23  s10.318,23,23,23c4.761,0,9.298-1.436,13.177-4.162l13.661,14.208c0.571,0.593,1.339,0.92,2.162,0.92  c0.779,0,1.518-0.297,2.079-0.837C56.255,54.982,56.293,53.08,55.146,51.887z M23.984,6c9.374,0,17,7.626,17,17s-7.626,17-17,17  s-17-7.626-17-17S14.61,6,23.984,6z"
                        />
                    </svg>
                </button>
            </div>
            <!-- End search bar -->
            <!-- <NuxtLink to="Login">
                <button class="flex items-center cursor-pointer">
                    <div
                        class="rounded-full w-9 h-9 lg:w-10 lg:h-10 ring ring-yellow-600 ring-offset-0"
                    >
                        <img
                            src="../assets/img/users.png"
                            class="w-9 h-9 lg:w-10 lg:h-10 hover:opacity-80 bg-primary rounded-full p-0.5"
                        />
                    </div>
                    <span class="pl-2 pr-1">เข้าสู่ระบบ</span>
                </button>
            </NuxtLink>-->
        </div>
    </div>
</template>