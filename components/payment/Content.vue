<template>
    <div class="text-gray-600 body-font">
        <div class="container px-5 py-4 mx-auto">
            <div class="flex flex-wrap w-full">
                <div class="w-full mb-6 lg:w-1/2 lg:mb-0">
                    <h1
                        class="mb-2 text-2xl font-medium text-gray-900 sm:text-3xl title-font"
                    >ข้อมูลการโอนเงิน</h1>
                    <div class="w-20 h-1 bg-yellow-500 rounded"></div>
                </div>
            </div>
        </div>
        <div class="container px-5 py-4 mx-auto">
            <div class="flex flex-wrap -mx-4 -mb-10 text-center">
                <div class="px-4 mb-10 sm:w-1/2">
                    <div class="overflow-hidden rounded-lg max-h-128">
                        <img
                            alt="content"
                            class="object-cover object-center w-full h-full pt-2"
                            src="../../assets/img/Promptpay.jpg"
                        />
                    </div>
                    <h2
                        class="mt-6 mb-3 text-2xl font-medium text-black title-font"
                    >ชำระผ่าน QR Payment</h2>
                </div>
                <div class="px-4 mb-10 sm:w-1/2">
                    <div class="overflow-hidden rounded-lg max-h-128">
                        <img
                            alt="content"
                            class="object-cover object-center w-full h-full"
                            src="../../assets/img/LogoKbank.jpg"
                        />
                    </div>
                    <h2
                        class="mt-6 mb-3 text-2xl font-medium text-black title-font"
                    >ชำระผ่านบัญชีธนาคาร</h2>
                    <label class="text-lg leading-relaxed">
                        ธนาคาร:Kasikorn Bank (ธนาคารกสิกร)
                        เลขที่บัญชี: 0503791064
                        ชื่อบัญชี: Khcup.
                    </label>
                </div>
            </div>
        </div>
        <div class="container flex flex-wrap items-center px-5 py-4 mx-auto">
            <div class="pb-10 mb-10 text-black md:w-1/2 md:pr-12 md:py-8">
                <p class="text-xl leading-relaxed">หมายเลข Voucher ที่สั่งซื้อของคุณ: {SSNI116AE85}</p>
                <p class="text-xl leading-relaxed">จำนวนเงิน: {5,500} บาท</p>
                <p class="text-xl leading-relaxed">กรุณาระบุหมายเลข voucher ในระหว่างการโอนเงิน</p>
                <NuxtLink to="confirmpayment">
                    <button
                        class="inline-flex items-center px-8 py-2 mx-auto mt-4 text-lg bg-yellow-400 border-0 rounded focus:outline-none hover:bg-yellow-300"
                    >แนบหลักฐานการชำระเงิน</button>
                </NuxtLink>
            </div>
        </div>
    </div>
</template>