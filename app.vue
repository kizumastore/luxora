<template>
<div class="container">
  <h1 class="title">𝐋𝐔𝐗𝐎𝐑𝐀</h1>
  <h2 class="subtitle">THE #1 SITE</h2>

  <!-- LINK GENERATOR -->
  <a
    href="https://app.genn.lu/auth/luxoraa"
    class="card"
    target="_blank"
    rel="noopener noreferrer"
  >
    <h3>🔗 Link Generator</h3>
    <p>🌐 Chrome: Unflagged</p>
    <p>🎵 TikTok: Unflagged</p>
  </a>

  <!-- HIDELINK -->
  <a
    href="https://v0-vercel-website-clone-topaz.vercel.app/"
    class="card"
    target="_blank"
    rel="noopener noreferrer"
  >
    <h3>📍 Hidelink</h3>
    <p>💡 Don't forget to hide your link after creating one</p>
    <p>If you did not hide it then your link would not work</p>
    <p><strong>(Don't hide your link if you're using it for TikTok)</strong></p>
  </a>

  <!-- DISCORD BUTTON -->
  <a
    href="https://discord.gg/BWYBef9FUM"
    class="discord-button"
    target="_blank"
    rel="noopener noreferrer"
  >
    JOIN DISCORD
  </a>
</div>
</template>

<style>
body {
margin: 0;
background: #000000;
font-family: 'Segoe UI', sans-serif;
color: white;
}

.container {
text-align: center;
padding: 40px 20px;
background-color: #000;
min-height: 100vh;
}

.title {
font-size: 3rem;
font-weight: bold;
text-shadow: 0 0 20px white;
margin-bottom: 10px;
}

.subtitle {
font-size: 1.2rem;
text-shadow: 0 0 10px white;
margin-bottom: 40px;
}

.card {
display: block;
background: rgba(255, 255, 255, 0.05);
border: 1px solid rgba(255, 255, 255, 0.15);
border-radius: 15px;
padding: 25px;
margin: 20px auto;
max-width: 500px;
text-decoration: none;
color: white;
box-shadow: 0 0 15px rgba(255, 255, 255, 0.15);
transition: 0.3s ease;
}

.card:hover {
box-shadow: 0 0 30px rgba(255, 255, 255, 0.3);
transform: scale(1.03);
}

.card h3 {
font-size: 1.4rem;
margin-bottom: 10px;
text-shadow: 0 0 10px white;
}

.card p {
color: #ccc;
text-shadow: 0 0 5px #aaa;
margin: 5px 0;
}

.discord-button {
display: inline-block;
background-color: #8000ff;
padding: 15px 30px;
color: white;
font-weight: bold;
text-decoration: none;
border-radius: 10px;
box-shadow: 0 0 15px #a64dff;
transition: all 0.3s ease;
margin-top: 30px;
}

.discord-button:hover {
background-color: #9900ff;
box-shadow: 0 0 25px #d580ff;
}
</style>
