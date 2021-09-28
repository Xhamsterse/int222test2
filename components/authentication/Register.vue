<template>
    <div class="h-screen text-black bg-yellow-300 body-font">
        <div class="container flex flex-col items-center justify-center px-5 mx-auto">
            <NuxtLink
                to="/"
                class="object-cover object-center w-5/6 mt-6 rounded lg:w-1/4 md:w-3/6"
            >
                <img alt="PayVoucher" src="../../assets/img/Payvouchertsp.png" />
            </NuxtLink>
            <div class="flex flex-col items-center w-full text-center mb-28 md:w-2/3">
                <h1 class="mb-4 text-3xl font-medium text-gray-900 title-font sm:text-4xl">ลงทะเบียน</h1>
                <div class="text-left">
                    <label class="text-sm leading-7 text-gray-600">ชื่อ - นามสกุล</label>
                    <input
                        type="text"
                        id="email"
                        name="email"
                        placeholder="ชื่อ - นามสกุล"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                    <label class="text-sm leading-7 text-gray-600">อีเมล</label>
                    <input
                        type="text"
                        id="password"
                        name="password"
                        placeholder="อีเมล"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                    <label class="text-sm leading-7 text-gray-600">หมายเลขโทรศัพท์</label>
                    <input
                        type="tel"
                        id="password"
                        name="password"
                        placeholder="หมายเลขโทรศัพท์"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                    <label class="text-sm leading-7 text-gray-600">Line ID</label>
                    <input
                        type="text"
                        id="password"
                        name="password"
                        placeholder="Line ID ของคุณ * ถ้ามี"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                </div>
                <button
                    class="px-20 py-2 my-5 text-lg text-white bg-indigo-400 border-0 rounded focus:outline-none hover:bg-indigo-600"
                >ลงทะเบียน</button>
            </div>
        </div>
    </div>
</template>

