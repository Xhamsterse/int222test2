<template>
    <div>
        <div class="overflow-hidden text-gray-600 body-font">
            <div class="container px-5 py-4 mx-auto">
                <div class="flex flex-wrap w-full">
                    <div class="w-full mb-6 lg:w-1/2 lg:mb-0">
                        <h1
                            class="mb-2 text-2xl font-medium text-gray-900 sm:text-3xl title-font"
                        >คำสั่งซื้อที่พักของคุณ</h1>
                        <div class="w-20 h-1 bg-yellow-500 rounded"></div>
                    </div>
                </div>
            </div>
            <div class="container px-5 mx-auto">
                <div class="flex flex-wrap mx-auto lg:w-4/5">
                    <img
                        alt="ecommerce"
                        class="object-cover object-center w-full h-64 rounded lg:w-1/2 lg:h-auto"
                        src="../../assets/img/hilton_pattaya.jpg"
                    />
                    <div class="w-full mt-6 lg:w-1/2 lg:pl-10 lg:py-6 lg:mt-0">
                        <h1 class="mb-1 text-3xl font-medium text-gray-900">Hilton Pattaya</h1>
                        <p class="leading-relaxed">ห้องพัก Deluxe one bedroom1 คืน สำหรับ 2 ท่าน</p>
                        <p class="leading-relaxed">> สามารถนำสัตว์เลี้ยงมาได้</p>
                        <p class="leading-relaxed">> ฟรี อาหารเช้า</p>
                        <p class="leading-relaxed">> ฟรี อาหารเย็น</p>
                        <p class="leading-relaxed">> ฟรี Mekha Pizza มูลค่า 420.-</p>
                        <p class="leading-relaxed">สามารถใช้ได้ถึง 20/12/2021</p>
                        <div class="flex items-center pb-5 mt-6 mb-5 border-b-2 border-gray-100">
                            <div class="flex">
                                <span class="mr-3">ราคา</span>
                                <span class="mr-3">5,550</span>
                                <span class="mr-3">บาท</span>
                            </div>
                            <div class="flex items-center ml-6">
                                <span class="mr-3">จำนวน</span>
                                <div class="relative">
                                    <select
                                        class="py-2 pl-3 pr-10 text-base border border-yellow-500 rounded appearance-none focus:outline-none focus:ring-2 focus:ring-indigo-200 focus:border-yellow-400"
                                    >
                                        <option>1</option>
                                        <option>2</option>
                                        <option>3</option>
                                        <option>4</option>
                                    </select>
                                    <span
                                        class="absolute top-0 right-0 flex items-center justify-center w-10 h-full text-center text-gray-600 pointer-events-none"
                                    >
                                        <svg
                                            fill="none"
                                            stroke="currentColor"
                                            stroke-linecap="round"
                                            stroke-linejoin="round"
                                            stroke-width="2"
                                            class="w-4 h-4"
                                            viewBox="0 0 24 24"
                                        >
                                            <path d="M6 9l6 6 6-6" />
                                        </svg>
                                    </span>
                                </div>
                                <span class="mx-2">ห้อง</span>
                            </div>
                        </div>
                        <div class="flex">
                            <span class="font-serif text-base text-gray-900">โค้ดส่วนลด</span>
                            <input
                                type="text"
                                class="px-3 py-2 mx-4 text-base border border-yellow-500 rounded focus:outline-none focus:ring-2 focus:ring-yellow-400 focus:border-yellow-400"
                            />

                            <button
                                class="flex px-6 py-2 text-black bg-yellow-400 border-0 rounded focus:outline-none hover:bg-yellow-300"
                            >ใช้</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
