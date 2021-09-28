<template>
    <div class="w-full py-6">
        <div class="flex">
            <div class="w-1/4">
                <div class="relative mb-2">
                    <div
                        class="flex items-center w-10 h-10 mx-auto text-lg text-white bg-yellow-500 rounded-full"
                    >
                        <span class="w-full text-center text-white">
                            <svg
                                class="w-full text-white h-7"
                                viewBox="0 0 24 24"
                                stroke-width="2"
                                stroke="currentColor"
                                fill="none"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            >
                                <path stroke="none" d="M0 0h24v24H0z" />
                                <path
                                    d="M16 6h3a1 1 0 0 1 1 1v11a2 2 0 0 1 -4 0v-13a1 1 0 0 0 -1 -1h-10a1 1 0 0 0 -1 1v12a3 3 0 0 0 3 3h11"
                                />
                                <line x1="8" y1="8" x2="12" y2="8" />
                                <line x1="8" y1="12" x2="12" y2="12" />
                                <line x1="8" y1="16" x2="12" y2="16" />
                            </svg>
                        </span>
                    </div>
                </div>
                <div class="text-xs text-center md:text-base">ข้อมูลลูกค้า</div>
            </div>
            <div class="w-1/4">
                <div class="relative mb-2">
                    <div
                        class="absolute flex items-center content-center align-middle align-center"
                        style="width: calc(100% - 2.5rem - 1rem); top: 50%; transform: translate(-50%, -50%)"
                    >
                        <div
                            class="items-center flex-1 w-full align-middle bg-gray-200 rounded align-center"
                        >
                            <div class="w-0 py-1 bg-yellow-300 rounded" style="width: 100%;"></div>
                        </div>
                    </div>

                    <div
                        class="flex items-center w-10 h-10 mx-auto text-lg text-white bg-yellow-500 rounded-full"
                    >
                        <span class="w-full text-center text-white">
                            <svg
                                class="w-full text-white"
                                width="24"
                                height="24"
                                viewBox="0 0 24 24"
                                stroke-width="2"
                                stroke="currentColor"
                                fill="none"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            >
                                <path stroke="none" d="M0 0h24v24H0z" />
                                <circle cx="9" cy="7" r="4" />
                                <path d="M3 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" />
                                <path d="M16 11l2 2l4 -4" />
                            </svg>
                        </span>
                    </div>
                </div>
                <div class="text-xs text-center md:text-base">ยืนยันข้อมูล</div>
            </div>
            <div class="w-1/4">
                <div class="relative mb-2">
                    <div
                        class="absolute flex items-center content-center align-middle align-center"
                        style="width: calc(100% - 2.5rem - 1rem); top: 50%; transform: translate(-50%, -50%)"
                    >
                        <div
                            class="items-center flex-1 w-full align-middle bg-gray-200 rounded align-center"
                        >
                            <div class="w-0 py-1 bg-yellow-300 rounded" style="width: 100%;"></div>
                        </div>
                    </div>

                    <div
                        class="flex items-center w-10 h-10 mx-auto text-lg text-white bg-yellow-500 rounded-full"
                    >
                        <span class="w-full text-center text-white">
                            <svg
                                class="w-8 h-8 text-white"
                                fill="none"
                                width="24"
                                height="24"
                                viewBox="0 0 18 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                                />
                            </svg>
                        </span>
                    </div>
                </div>
                <div class="text-xs text-center md:text-base">การชำระเงิน</div>
            </div>

            <div class="w-1/4">
                <div class="relative mb-2">
                    <div
                        class="absolute flex items-center content-center align-middle align-center"
                        style="width: calc(100% - 2.5rem - 1rem); top: 50%; transform: translate(-50%, -50%)"
                    >
                        <div
                            class="items-center flex-1 w-full align-middle bg-gray-200 rounded align-center"
                        >
                            <div class="w-0 py-1 bg-yellow-300 rounded" style="width: 90%;"></div>
                        </div>
                    </div>

                    <div
                        class="flex items-center w-10 h-10 mx-auto text-lg text-white bg-white border-2 border-gray-200 rounded-full"
                    >
                        <span class="w-full text-center text-gray-600">
                            <svg
                                class="w-full fill-current"
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                width="24"
                                height="24"
                            >
                                <path
                                    class="heroicon-ui"
                                    d="M12 22a10 10 0 1 1 0-20 10 10 0 0 1 0 20zm0-2a8 8 0 1 0 0-16 8 8 0 0 0 0 16zm-2.3-8.7l1.3 1.29 3.3-3.3a1 1 0 0 1 1.4 1.42l-4 4a1 1 0 0 1-1.4 0l-2-2a1 1 0 0 1 1.4-1.42z"
                                />
                            </svg>
                        </span>
                    </div>
                </div>
                <div class="text-xs text-center md:text-base">อัพโหลดหลักฐานการชำระเงิน</div>
            </div>
        </div>
    </div>
</template>