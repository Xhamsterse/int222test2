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
          <h2 class="my-6 text-2xl text-gray-700">Dashboard</h2>
          <!-- Cards -->
          <div class="grid gap-6 mb-8 md:grid-cols-2 xl:grid-cols-4">
            <!-- Card -->
            <div class="flex items-center p-4 bg-white rounded-lg shadow-xs">
              <div class="p-3 mr-4 text-black bg-gray-300 rounded-full">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                  <path
                    d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3zM6 8a2 2 0 11-4 0 2 2 0 014 0zM16 18v-3a5.972 5.972 0 00-.75-2.906A3.005 3.005 0 0119 15v3h-3zM4.75 12.094A5.973 5.973 0 004 15v3H1v-3a3 3 0 013.75-2.906z"
                  />
                </svg>
              </div>
              <div>
                <p class="mb-2 text-sm text-black d">Total clients</p>
                <p class="text-lg text-black">8000</p>
              </div>
            </div>
            <!-- Card -->
            <div class="flex items-center p-4 bg-white rounded-lg shadow-xs">
              <div class="p-3 mr-4 bg-indigo-100 rounded-full">
                <svg
                  class="w-5 h-5 text-indigo-600"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 5v2m0 4v2m0 4v2M5 5a2 2 0 00-2 2v3a2 2 0 110 4v3a2 2 0 002 2h14a2 2 0 002-2v-3a2 2 0 110-4V7a2 2 0 00-2-2H5z"
                  />
                </svg>
              </div>
              <div>
                <p class="mb-2 text-sm text-gray-600">Total Voucher</p>
                <p class="text-lg text-gray-700">888</p>
              </div>
            </div>
            <!-- Card -->
            <div class="flex items-center p-4 bg-white rounded-lg shadow-xs">
              <div class="p-3 mr-4 text-blue-500 bg-blue-100 rounded-full">
                <svg
                  class="w-5 h-5 text-blue-500"
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
                  <path
                    d="M8 9l5 5v7h-5v-4m0 4h-5v-7l5 -5m1 1v-6a1 1 0 0 1 1 -1h10a1 1 0 0 1 1 1v17h-8"
                  />
                  <line x1="13" y1="7" x2="13" y2="7.01" />
                  <line x1="17" y1="7" x2="17" y2="7.01" />
                  <line x1="17" y1="11" x2="17" y2="11.01" />
                  <line x1="17" y1="15" x2="17" y2="15.01" />
                </svg>
              </div>
              <div>
                <p class="mb-2 text-sm text-gray-600">Total Accommodation</p>
                <p class="text-lg text-gray-700">376</p>
              </div>
            </div>
            <!-- Card -->
            <div class="flex items-center p-4 bg-white rounded-lg shadow-xs">
              <div class="p-3 mr-4 text-green-500 bg-green-100 rounded-full">
                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                  <path
                    fill-rule="evenodd"
                    d="M4 4a2 2 0 00-2 2v4a2 2 0 002 2V6h10a2 2 0 00-2-2H4zm2 6a2 2 0 012-2h8a2 2 0 012 2v4a2 2 0 01-2 2H8a2 2 0 01-2-2v-4zm6 4a2 2 0 100-4 2 2 0 000 4z"
                    clip-rule="evenodd"
                  />
                </svg>
              </div>
              <div>
                <p class="mb-2 text-sm text-gray-600">Account balance</p>
                <p class="text-lg text-gray-700">460,000 Bath</p>
              </div>
            </div>
          </div>

          <!-- New Table -->
          <div class="w-full overflow-hidden rounded-lg shadow-xs">
            <div class="w-full overflow-x-auto">
              <table class="w-full whitespace-no-wrap">
                <thead>
                  <tr
                    class="text-xs tracking-wide text-left text-white uppercase bg-indigo-400 border-b"
                  >
                    <th class="px-4 py-3">Customer</th>
                    <th class="px-4 py-3">Amount</th>
                    <th class="px-4 py-3">Status</th>
                    <th class="px-4 py-3">Date</th>
                  </tr>
                </thead>
                <tbody class="bg-white divide-y">
                  <tr class="text-gray-700">
                    <td class="px-4 py-3">
                      <div class="flex items-center text-sm">
                        <!-- Avatar with inset shadow -->
                        <div class="relative hidden w-8 h-8 mr-3 rounded-full md:block">
                          <img
                            class="object-cover w-full h-full rounded-full"
                            src="../../../assets/img/users.png"
                            alt
                            loading="lazy"
                          />
                          <div
                            class="absolute inset-0 rounded-full shadow-inner"
                            aria-hidden="true"
                          ></div>
                        </div>
                        <div>
                          <p class>Rick Roll</p>
                        </div>
                      </div>
                    </td>
                    <td class="px-4 py-3 text-sm">2,500 Bath</td>
                    <td class="px-4 py-3 text-xs">
                      <span
                        class="px-2 py-1 leading-tight text-green-700 bg-green-100 rounded-full"
                      >Approved</span>
                    </td>
                    <td class="px-4 py-3 text-sm">18/9/2021</td>
                  </tr>

                  <tr class="text-gray-700">
                    <td class="px-4 py-3">
                      <div class="flex items-center text-sm">
                        <!-- Avatar with inset shadow -->
                        <div class="relative hidden w-8 h-8 mr-3 rounded-full md:block">
                          <img
                            class="object-cover w-full h-full rounded-full"
                            src="../../../assets/img/users.png"
                            alt
                            loading="lazy"
                          />
                          <div
                            class="absolute inset-0 rounded-full shadow-inner"
                            aria-hidden="true"
                          ></div>
                        </div>
                        <div>
                          <p class>Kurt Cobain</p>
                        </div>
                      </div>
                    </td>
                    <td class="px-4 py-3 text-sm">50,000 Bath</td>
                    <td class="px-4 py-3 text-xs">
                      <span
                        class="px-2 py-1 leading-tight text-red-700 bg-red-100 rounded-full"
                      >Denied</span>
                    </td>
                    <td class="px-4 py-3 text-sm">18/9/2021</td>
                  </tr>

                  <tr class="text-gray-700">
                    <td class="px-4 py-3">
                      <div class="flex items-center text-sm">
                        <!-- Avatar with inset shadow -->
                        <div class="relative hidden w-8 h-8 mr-3 rounded-full md:block">
                          <img
                            class="object-cover w-full h-full rounded-full"
                            src="../../../assets/img/users.png"
                            alt
                            loading="lazy"
                          />
                          <div
                            class="absolute inset-0 rounded-full shadow-inner"
                            aria-hidden="true"
                          ></div>
                        </div>
                        <div>
                          <p class>Lil Pump</p>
                        </div>
                      </div>
                    </td>
                    <td class="px-4 py-3 text-sm">65,000 Bath</td>
                    <td class="px-4 py-3 text-xs">
                      <span
                        class="px-2 py-1 leading-tight text-gray-700 bg-gray-100 rounded-full"
                      >Expired</span>
                    </td>
                    <td class="px-4 py-3 text-sm">18/9/2021</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>