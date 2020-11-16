<template>
  <div id="app">
    <!-- Hero Section -->
    <section>
      <div class="relative bg-gray-200 overflow-hidden">
        <div class="max-w-screen-xl mx-auto">
          <div class="relative z-10 pb-8 bg-gray-200 sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
            <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-gray-200 transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none">
              <polygon points="50,0 100,0 50,100 0,100" />
            </svg>
            <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
              <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start">
                <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
                  <div class="flex items-center justify-between w-full md:w-auto">
                    <a href="#" aria-label="Home">
                      <img class="h-8 w-auto sm:h-10" src="./assets/mumu-icon.png" alt="Logo">
                    </a>
                  </div>
                </div>
              </nav>
            </div>
            <main class="mt-10 mx-auto max-w-screen-xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
              <div class="sm:text-center lg:text-left">
                <h2 class="text-4xl tracking-tight leading-10 font-extrabold text-gray-900 sm:text-5xl sm:leading-none md:text-6xl">
                  <span class="text-indigo-700">Tell:</span>
                  Stories Around You
                </h2>
                <p class="mt-3 text-base text-gray-700 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
                  Tell adalah tempat untuk kamu berbagi cerita yang ngga pernah kamu ceritain, 
                  dan untuk tau cerita yang belum pernah kamu dengar sebelumnya sebagai anonim.                  
                </p>
                <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
                  <div class="rounded-md shadow">
                    <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-500 focus:outline-none focus:border-indigo-700 focus:shadow-outline-indigo transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10">
                      Check it out
                    </a>
                  </div>
                </div>
              </div>
            </main>
          </div>
        </div>
        <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2 py-10 px-10">
          <img class="rounded-lg shadow-lg mb-6 md:mb-0 mx-auto" src="./assets/croods.png" alt="">
        </div>
      </div>
    </section>

    <!-- Feature Section -->
    <section>
      <div class=" bg-white">
        <div class=" container mx-auto max-w-4xl py-40 px-6">
          <div class=" md:grid grid-cols-2 gap-8 items-center">
            <div>
              <h1 class="text-4xl font-bold text-gray-800">What's On Tell?</h1>
              <p class=" text-lg mb-8 text-gray-700">
                Dengan <b>Fun Corner</b> kamu dapat ngobrol asik dengan orang asing sesuai topik yang kamu inginkan seperti games, arts, Beauty dan lainnya. 
                Kamu juga dapat menikmati atau menulis cerita sedih, memalukan atau menyenangkan dengan <b>Stories</b>, dan yang pastinya sebagai anonim
                sehingga kamu tidak perlu takut tentang orang lain mengetahui identitas mu. 
              </p>
            </div>
            <img src="./assets/feature.jpg"
            class=" rounded-lg shadow-lg w-4/5 mb-6 md:mb-0 mx-auto"
            alt="Tell Feature">
          </div>
        </div>
      </div>
    </section>

    <!-- Section -->
    <section>
      <div class=" bg-blue-800 text-white">
        <div class=" container mx-auto max-w-4xl py-40 px-6 lg:flex
         items-center space-x-10">
          <div class="lg:w-1/2">
            <h1 class=" text-4xl font-bold leading-snug mb-6">What's So Fun About That?</h1>
            <p class=" text-gray-300 leading-loose">
              Dengan Tell kamu dapat berinteraksi dengan orang lain tanpa khawatir karena identitas kamu terjaga, kamu juga dapat
              dengan bebas mengekspresikan diri dengan menulis cerita membalasa post pengguna lain dan juga chat pribadi. Kamu juga bisa menikmati
              cerita-cerita menarik yang ditulis oleh pengguna lain.
            </p>
          </div>
          <ul class="lg:w-1/2">
            <li class=" bg-blue-900 px-3 py-3 rounded-md shadow-lg text-lg mb-4">Berinteraksi dengan orang asing secara anonim</li>
            <li class=" bg-blue-900 px-3 py-3 rounded-md shadow-lg text-lg mb-4">Bebas mengekspresikan diri</li>
            <li class=" bg-blue-900 px-3 py-3 rounded-md shadow-lg text-lg mb-4">Tempat curhat tanpa merasa insecure</li>
            <li class=" bg-blue-900 px-3 py-3 rounded-md shadow-lg text-lg mb-4">Pembelajaran dari cerita pengguna lainnya</li>
            <li class=" bg-blue-900 px-3 py-3 rounded-md shadow-lg text-lg mb-4">Membantu kaum introvert menjadi lebih baik</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section>
      <div class=" bg-white">
        <div class="container mx-auto max-w-4xl px-6 py-20">  
          <h1 class=" text-4xl font-bold leading-snug mb-6">Our User's Viewpoint</h1>
        </div>
        <div class=" md:flex mx-auto max-w-4xl px-6 lg:flex space-x-3">
          <div class=" px-8 bg-white shadow-lg rounded-lg my-20 lg:w-1/3">
            <div class="flex justify-center md:justify-end -mt-16">
              <img class="w-20 h-20 object-cover rounded-full border-2 border-indigo-500" src="https://images.unsplash.com/photo-1499714608240-22fc6ad53fb2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80">
            </div>
            <div>
              <h2 class="text-gray-800 text-3xl font-semibold">MUMU LUP YUU</h2>
              <p class="mt-2 text-gray-600">
                Kaget juga sama gebrakan tim tell yang berani banget mengubah Tell jadi se-beda sekarang. Saya sih merasa Tell semakin memperjelas
                arahnya sebagai platform cerita, bukan yang lain. Aplikasi ini juga yang ternyaman
                dari aplikasi anon lain, Tell bener2 memperhatikan kenyamanan pengguna nya.
              </p>
            </div>
            <div class="flex justify-end mt-4">
              <a href="#" class="text-xl font-medium text-indigo-500">Maulana Wahadah</a>
            </div>
          </div>
          <div class=" px-8 bg-white shadow-lg rounded-lg my-20 lg:w-1/3">
            <div class="flex justify-center md:justify-end -mt-16">
              <img class="w-20 h-20 object-cover rounded-full border-2 border-indigo-500" src="./assets/naruto.jpg">
            </div>
            <div>
              <h2 class="text-gray-800 text-3xl font-semibold">Keren abizzz</h2>
              <p class="mt-2 text-gray-600">
                Keren bat aslii, mendukung dan memelihara jiwa introvertku agar tetap sehat dan tidak jadi orang yang ansos wkwkwk \(-,-)/.
                Selama gw maen ni apk dapet banyak pengalaman, Disini kita berbagi cerita dan bertukar cerita, dan ga dikit
                kita dapet pembelajaran tentang arti kehidupan dari anon2 yang ada, ga jarang juga kita dapet support/teguran di dalem tell kece ini.
              </p>
            </div>
            <div class="flex justify-end mt-4">
              <a href="#" class="text-xl font-medium text-indigo-500">Yani Malahayati</a>
            </div>
          </div>
          <div class=" px-8 bg-white shadow-lg rounded-lg my-20 lg:w-1/3">
            <div class="flex justify-center md:justify-end -mt-16">
              <img class="w-20 h-20 object-cover rounded-full border-2 border-indigo-500" src="./assets/boruto.png">
            </div>
            <div>
              <h2 class="text-gray-800 text-3xl font-semibold">Mumu salam buat baba</h2>
              <p class="mt-2 text-gray-600">
                Aku install tell dr jamannya baba, tell pertama sampe kedua dan ini ketiga. Pernah nyoba install
                apk anon lain, tapi ujung2nya balik ke tell. Adminnya kaya bener2 dengerin apa yang di mau orang2 huhu. Sekarang juga ga
                pake nearby jd bisa kenal sama anon dari berbagai kota, seneng sih hehe. Semoga tell bisa jadi lebih baik yaa.
              </p>
            </div>
            <div class="flex justify-end mt-4">
              <a href="#" class="text-xl font-medium text-indigo-500">Imam Mahdi</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Section -->
    <section>
      <div class=" bg-blue-800 text-white">
        <div class=" container mx-auto max-w-4xl py-40 px-6">
          <p class=" text-4xl text-center text-gray-300 mb-0">Still in doubt?</p>
          <p class=" text-6xl font-bold text-center text-pink-100 uppercase">Tell is completely free!!</p>
        </div>
      </div>
    </section>

    <!-- Section -->
    <section>
      <div class=" bg-white">
        <div class=" container mx-auto max-w-4xl py-24 px-6">
          <div class=" md:grid grid-cols-2 gap-8 items-center">
            <img src="./assets/bgHudya.png"
            class=" rounded-lg shadow-lg w-4/5 mb-6 md:mb-0 mx-auto"
            alt="Tell Feature">
            <div>
              <h1 class="text-4xl font-bold text-gray-900">Hudya</h1>
              <h1 class="text-2xl font-bold text-gray-700">Team Lead</h1>
              <p class=" text-lg mb-8 text-gray-700">
                I'm a developer, speaker, and teacher with a passion for web development, design,
                 and developer tools. I have taught tens of thousands of students online/in-person and am excited to share with you.
                In my spare time, I run a YouTube channel, play co-ed soccer with my wife, spend time with my dogs, and can solve a Rubik's cube in under two minutes. 
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class=" bg-white">
        <div class=" container mx-auto max-w-4xl py-10 px-6">
          <div class=" md:grid grid-cols-2 gap-8 items-center">
            <img src="./assets/bgTivo.jpg"
            class=" rounded-lg shadow-lg w-4/5 mb-6 md:mb-0 mx-auto"
            alt="Tell Feature">
            <div>
              <h1 class="text-4xl font-bold text-gray-900">Tivo</h1>
              <h1 class="text-2xl font-bold text-gray-700">CTO</h1>
              <p class=" text-lg mb-8 text-gray-700">
                I'm a developer, speaker, and teacher with a passion for web development, design,
                 and developer tools. I have taught tens of thousands of students online/in-person and am excited to share with you.
                In my spare time, I run a YouTube channel, play co-ed soccer with my wife, spend time with my dogs, and can solve a Rubik's cube in under two minutes. 
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style src="./assets/tailwind.css">
