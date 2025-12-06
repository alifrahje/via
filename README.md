<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Happy Graduation Sayang</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
  </head>
  <body
    style="
      background-image: url(https://i.pinimg.com/736x/85/f6/f4/85f6f4182d181e5b70347fc2b84ccf6c.jpg);
    "
    class="flex justify-center h-screen items-center"
  >
    <div
      class="bg-white border px-10 py-8 border-4 border-gray-300 shadow-lg shadow-blue-300 rounded-xl text-center animate__animated animate__backInDown m-8 w-80"
      id="kartu"
    >
      <h1 class="text-3xl">Happy Graduation</h1>
      <h1
        class="text-4xl text-purple-500 font-bold animate__animated animate__pulse animate__infinite"
      >
        Via Rahma Dhanie
      </h1>
      <button
        class="p-2 bg-purple-600 text-white rounded mt-5 hover:bg-purple-900 transition ease-in w-full animate__animated animate__delay-1s animate__tada"
        onclick="ubahKartu()"
      >
        Klik Disini Sayang!
      </button>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
    <script>
const defaults = {
  spread: 360,
  ticks: 100,
  gravity: 0,
  decay: 0.94,
  startVelocity: 30,
  shapes: ["heart"],
  colors: ["FFC0CB", "FF69B4", "FF1493", "C71585"],
};

confetti({
  ...defaults,
  particleCount: 50,
  scalar: 2,
});

confetti({
  ...defaults,
  particleCount: 25,
  scalar: 3,
});

confetti({
  ...defaults,
  particleCount: 10,
  scalar: 4,
});
      let kartu = document.getElementById("kartu");
      function ubahKartu() {
        kartu.innerHTML = `    <h1 class="font-semibold text-wrap animate__animated animate__zoomIn">
      Selamat wisuda sayangku cintaku. Aku tahu perjalananmu nggak mudah, tapi kamu berhasil melewatinya dengan kekuatan dan keteguhan hati yang luar biasa. Walau kita dipisahkan jarak, aku selalu bangga dan selalu ada buat kamu. Hari ini bukan hanya tentang gelarmu, tapi tentang perjuanganmu yang akhirnya terbayar.

    Semoga ini jadi awal dari masa depan yang semakin cerah. Aku sayang banget sama kamu.   ❤❤❤
    </h1>
    <h2 class="mt-3 animate__animated animate__fadeIn">
      - With  love, Alif Rahman Jennof -
    </h2>
    <button
      class="p-2 bg-slate-600 text-white rounded mt-5 hover:bg-slate-900 transition ease-in w-full animate__animated animate__delay-1s animate__tada"
      onclick="refresh()"
    >
      Tutup
    </button>
    `;
      }
      function refresh() {
        location.reload();
      }
    </script>
  </body>
</html>
