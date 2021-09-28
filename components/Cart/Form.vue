<template>
    <div class="py-10 text-gray-600 body-font">
        <div class="container px-4 py-6 mx-auto bg-yellow-300 rounded-lg px-5bg-red-800">
            <div class="flex flex-col w-full text-center">
                <h1
                    class="mb-4 text-2xl font-medium text-left text-gray-900 sm:text-3xl title-font"
                >ข้อมูลลูกค้า</h1>
            </div>
            <div
                class="flex flex-col items-end w-full px-8 space-y-4 lg:w-2/3 sm:flex-row sm:space-x-4 sm:space-y-0 sm:px-0"
            >
                <div class="relative flex-grow w-full">
                    <label
                        for="full-name"
                        class="text-base leading-7 text-gray-600"
                    >กรุณากรอกชื่อและนามสกุลของผู้ซื้อ</label>
                    <input
                        type="text"
                        id="full-name"
                        name="full-name"
                        placeholder="ชื่อ - นามสกุล"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                </div>
                <div class="relative flex-grow w-full">
                    <label
                        for="lineid"
                        class="text-base leading-7 text-gray-600"
                    >กรุณากรอก Line ID *ถ้าหากมี เพื่อการสื่อสารที่ง่ายขึ้น</label>
                    <input
                        type="lineid"
                        id="lineid"
                        name="lineid"
                        placeholder="Lind ID ของคุณ"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                </div>
            </div>
            <div
                class="flex flex-col items-end w-full px-8 space-y-4 lg:w-2/3 sm:flex-row sm:space-x-4 sm:space-y-0 sm:px-0"
            >
                <div class="relative flex-grow w-full">
                    <label
                        for="email"
                        class="text-base leading-7 text-gray-600"
                    >กรุณากรอกอีเมล เพื่อส่งใบยืนยันการจองของผู้ซื้อ</label>
                    <input
                        type="email"
                        id="email"
                        name="email"
                        placeholder="อีเมล"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                </div>
                <div class="relative flex-grow w-full">
                    <label
                        for="tel"
                        class="text-base leading-7 text-gray-600"
                    >กรุณากรอก เบอร์โทรศัพท์ เพื่อในกรณีจำเป็นต้องติดต่อผู้ซื้อ</label>
                    <input
                        type="tel"
                        id="tel"
                        name="tel"
                        placeholder="เบอร์โทรศัพท์"
                        class="w-full px-3 py-1 leading-8 text-gray-700 bg-white border border-gray-300 rounded outline-none focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500"
                    />
                </div>
            </div>
        </div>
        <div class="container px-4 py-6 mx-auto my-8 bg-yellow-300 rounded-lg px-5bg-red-800">
            <div class="flex flex-col w-full text-center">
                <h1
                    class="mb-4 text-2xl font-medium text-left text-gray-900 sm:text-3xl title-font"
                >วิธีการชำระเงิน</h1>
            </div>
            <div
                class="flex flex-col items-end w-full px-8 space-y-4 lg:w-2/3 sm:flex-row sm:space-x-4 sm:space-y-0 sm:px-0"
            >
                <div class="relative flex-grow w-full px-8">
                    <img alt="Bank" src="../../assets/img/Bank.png" class="w-48 px-2 py-4" />
                    <input type="radio" id="mobilebanking" name="mobilebanking" class />
                    <label for="mobilebanking" class="text-black">โอนเงิน/แอพธนาคาร</label>
                    <br />
                    <label for="full-name" class="text-base leading-7 text-black">
                        ชำระเงินผ่านโมบายแบงก์กิ้ง อินเตอร์เน็ตแบงก์กิ้ง
                        ตู้ ATM หรือเคาน์เตอร์ธนาคารได้ทุกสาขา
                    </label>
                </div>
                <div class="relative flex-grow w-full px-8">
                    <img alt="Creditcard" src="../../assets/img/Creditcard.png" class="w-48 px-2 py-4" />
                    <input type="radio" id="mobilebanking" name="mobilebanking" class />
                    <label for="mobilebanking" class="text-black">Credit/Debit Card</label>
                    <br />
                    <label for="full-name" class="text-base leading-7 text-black">
                        ชำระเงินผ่านบัตร VISA, MasterCard หรือ JCB
                        * หากลูกค้าเลือกชำระผ่านบัตรเครติด ค่าธรรมเนียมธนาคารจะอยู่ที่ 3.0%
                    </label>
                </div>
            </div>
        </div>
        <div class="text-gray-600 body-font">
            <div class="container mx-auto">
                <div
                    class="flex flex-col items-end w-full px-8 mx-auto space-y-4 lg:w-2/3 sm:flex-row sm:space-x-4 sm:space-y-0 sm:px-0"
                >
                    <div class="relative flex-grow w-full">
                        <p for="email" class="text-xl leading-7 text-gray-600">ราคาทั้งหมด 5,500 บาท</p>
                    </div>
                    <NuxtLink to="confirm">
                        <button
                            class="px-8 py-2 text-lg text-black bg-yellow-400 border-0 rounded focus:outline-none hover:bg-yellow-300"
                        >ชำระเงิน</button>
                    </NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>