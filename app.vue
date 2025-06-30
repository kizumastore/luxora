<template>
  <div class="min-h-screen flex flex-col items-center justify-center bg-black text-white relative overflow-hidden">

    <!-- Background Stars -->
    <div class="absolute w-full h-full bg-[url('https://i.ibb.co/7rLZgXt/stars.gif')] bg-cover bg-center opacity-30 z-0"></div>

    <!-- Container -->
    <div class="z-10 w-full max-w-2xl p-6 rounded-xl border border-cyan-500 shadow-lg shadow-cyan-500/20 bg-black/80 backdrop-blur-lg mt-10">

      <!-- Logo and Title -->
      <div class="text-center mb-6">
        <div class="text-4xl font-bold flex items-center justify-center gap-2 text-cyan-400">
          <span>🔷</span> Luxora <span>🔷</span>
        </div>
        <a
          href="https://discord.gg/BWYBef9FUM"
          class="mt-4 inline-block bg-white text-black font-bold py-2 px-6 rounded hover:bg-gray-200 transition"
          target="_blank"
        >
          <span>💬</span> Join Discord
        </a>
      </div>

      <!-- Generator Section -->
      <div class="text-center mb-6">
        <h2 class="text-lg font-semibold mb-2 text-cyan-300">MAIN GENERATOR</h2>
        <div class="flex justify-around text-sm mb-4">
          <span>🌐 TikTok - supported</span>
          <span>🌐 Chrome - supported</span>
        </div>
        <div class="flex justify-around mb-2">
          <a
            href="https://app.genn.lu/auth/luxoraa"
            class="bg-yellow-400 text-black px-4 py-2 rounded font-bold shadow-md hover:bg-yellow-300"
          >⚡ Generator</a>
          <button
            class="bg-green-500 text-black px-4 py-2 rounded font-bold shadow-md hover:bg-green-400"
          >♻️ Refresher</button>
        </div>
        <p class="text-xs italic text-gray-400">
          If the Sites are down or Flagged be Patient as we are aware of this and working on fixing it asap
        </p>
      </div>

      <!-- Tutorial Section -->
      <div class="text-center mt-6">
        <h2 class="text-lg font-semibold text-cyan-300">✨ Beaming Tutorial ✨</h2>
        <details class="mt-2 bg-white text-black rounded p-2">
          <summary class="cursor-pointer font-medium">📁 Tutorials</summary>
          <ul class="list-disc list-inside mt-2 text-left">
            <li><a href="https://yourlink.com/pc-tutorial" target="_blank" class="text-blue-600 hover:underline">💻 PC Tutorial</a></li>
            <li><a href="https://yourlink.com/mobile-tutorial" target="_blank" class="text-blue-600 hover:underline">📱 Mobile Tutorial</a></li>
          </ul>
        </details>
      </div>

    </div>
  </div>
</template>

<style>
body {
  font-family: 'Segoe UI', sans-serif;
}
</style>
