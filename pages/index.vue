<template>
  <div class="overflow-hidden bg-white">
    <div class="max-w-screen-xl mx-auto">
      <div
        class="max-w-5xl pb-8 mx-auto bg-white sm:pb-16 md:pb-20 lg:pb-28 xl:pb-32"
      >
        <!-- hero -->
        <div
          class="max-w-screen-xl px-4 mx-auto my-20 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28"
        >
          <div class="sm:text-center lg:text-left">
            <h2
              class="text-4xl font-bold text-blue-500 sm:text-5xl sm:leading-none md:text-6xl"
            >
              Temukan jawaban dari pertanyaamu.
            </h2>
            <div
              class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start"
            >
              <div class="rounded-md shadow">
                <nuxt-link
                  to="/home"
                  class="flex items-center justify-center w-full px-8 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-blue-500 border border-transparent rounded-md hover:bg-blue-500 focus:outline-none focus:shadow-outline md:py-4 md:text-lg md:px-10"
                >
                  Masuk ke beranda
                </nuxt-link>
              </div>
              <div class="mt-3 sm:mt-0 sm:ml-3">
                <a
                  :href="groupLink"
                  target="_blank"
                  class="flex items-center justify-center w-full px-8 py-3 text-base font-medium leading-6 text-blue-700 transition duration-150 ease-in-out bg-blue-100 border border-transparent rounded-md hover:text-blue-500 hover:bg-blue-50 focus:outline-none focus:shadow-outline focus:border-blue-300 md:py-4 md:text-lg md:px-10"
                >
                  Gabung grup WhatsApp
                </a>
              </div>
            </div>
          </div>
        </div>
        <!-- end hero -->
        <!-- start feature -->
        <div class="py-12 bg-white">
          <div class="max-w-screen-xl px-4 mx-auto sm:px-6 lg:px-8">
            <div class="lg:text-center">
              <p
                class="text-base font-semibold leading-6 tracking-wide text-blue-500 uppercase"
              >
                Sebuah Konsep
              </p>
              <h3
                class="mt-2 text-3xl font-extrabold leading-8 tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
              >
                Tempat untuk tanya jawab
              </h3>
              <p
                class="max-w-2xl mt-4 text-xl leading-7 text-gray-500 lg:mx-auto"
              >
                Ajukan pertanyaan apapun. Dapatkan jawabannya dari siapapun.
              </p>
            </div>

            <div class="mt-10">
              <ul class="md:grid md:grid-cols-2 md:col-gap-8 md:row-gap-10">
                <li>
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-blue-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h4 class="text-lg font-medium leading-6 text-gray-900">
                        Akses Global
                      </h4>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Dapatkan jawaban dari berbagai kalangan.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mt-10 md:mt-0">
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-blue-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h4 class="text-lg font-medium leading-6 text-gray-900">
                        Relevan
                      </h4>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Pertimbangkan jawaban yang cocok atas pertanyaanmu.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mt-10 md:mt-0">
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-blue-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M13 10V3L4 14h7v7l9-11h-7z"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h4 class="text-lg font-medium leading-6 text-gray-900">
                        Cepat
                      </h4>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Dapatkan jawaban dengan cepat.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mt-10 md:mt-0">
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-blue-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          fill="none"
                          viewBox="0 0 24 24"
                          stroke="currentColor"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h4 class="text-lg font-medium leading-6 text-gray-900">
                        Komunitas aktif
                      </h4>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Gabung grup WhatsApp untuk mengetahui apa yang terjadi
                        di belakang layar.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <!-- end feature -->
        <!-- start cta -->
        <div class="bg-gray-50">
          <div
            class="max-w-screen-xl px-4 py-12 mx-auto sm:px-6 lg:py-16 lg:px-8 lg:flex lg:items-center lg:justify-between"
          >
            <h2
              class="text-3xl font-extrabold text-gray-900 sm:text-4xl sm:leading-10"
            >
              Apakah Anda siap?
              <br />
              <span class="text-blue-500">Segera tanyakan sesuatu...</span>
            </h2>
            <div class="flex justify-center mt-8 lg:flex-shrink-0 lg:mt-0">
              <div class="inline-flex rounded-md shadow">
                <nuxt-link
                  to="/home"
                  class="inline-flex items-center justify-center px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-blue-500 border border-transparent rounded-md hover:bg-blue-500 focus:outline-none focus:shadow-outline"
                >
                  Masuk ke beranda
                </nuxt-link>
              </div>
              <div class="inline-flex ml-3 rounded-md shadow">
                <a
                  :href="groupLink"
                  target="_blank"
                  class="inline-flex items-center justify-center px-5 py-3 text-base font-medium leading-6 text-blue-500 transition duration-150 ease-in-out bg-white border border-transparent rounded-md hover:text-blue-500 focus:outline-none focus:shadow-outline"
                >
                  Gabung grup WhatsApp
                </a>
              </div>
            </div>
          </div>
        </div>
        <!-- end cta -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'landing',
  layout: 'landing',
  head: {
    title: 'Temukan jawaban dari pertanyaanmu',
  },
  data() {
    return {
      menu: false,
      groupLink: 'https://chat.whatsapp.com/I9zXvjhy5N39w25YzQVz6M',
    }
  },
  mounted() {
    this.$axios.get('wakeup')
  },
  methods: {
    toggleNav() {
      this.menu = !this.menu
    },
  },
}
</script>
