<template>
<div class="container">
  <h1 class="title">𝐋𝐔𝐗𝐎𝐑𝐀</h1>
  <h2 class="subtitle">THE #1 SITE</h2>

  <!-- LINK GENERATOR -->
  <a
    href="https://app.genn.lu/auth/luxoraa"
    class="card-link"
    target="_blank"
    rel="noopener noreferrer"
  >
    <div class="card">
      <h3>🔗 Link Generator</h3>
      <p class="info">🌐 Chrome: Unflagged</p>
      <p class="info">🎵 TikTok: Unflagged</p>
    </div>
  </a>

  <!-- HIDELINK (klik seluruh kotak) -->
  <a
    href="https://v0-vercel-website-clone-topaz.vercel.app/"
    class="card-link"
    target="_blank"
    rel="noopener noreferrer"
  >
    <div class="card">
      <h3>📍 Hidelink</h3>
      <p class="info">
        💡 Don't forget to hide your link after creating one<br />
        If you did not hide it then your link would not work<br />
        <strong>(Don't hide your link if you're using it for TikTok)</strong>
      </p>
    </div>
  </a>

  <!-- DISCORD BUTTON -->
  <a
    href="https://discord.gg/BWYBef9FUM"
    class="button"
    target="_blank"
    rel="noopener noreferrer"
  >
    JOIN DISCORD
  </a>
</div>
</template>

<style scoped>
body {
background: linear-gradient(to bottom right, #0a0a0a, #1c1c1c);
font-family: 'Segoe UI', sans-serif;
margin: 0;
padding: 0;
color: white;
text-align: center;
}

.container {
max-width: 600px;
margin: 0 auto;
padding: 40px 20px;
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
background-color: rgba(255, 255, 255, 0.05);
border: 2px solid rgba(255, 255, 255, 0.1);
border-radius: 15px;
padding: 20px;
margin-bottom: 30px;
box-shadow: 0 0 15px rgba(255, 255, 255, 0.15);
transition: 0.3s ease;
}

.card:hover {
box-shadow: 0 0 25px rgba(255, 255, 255, 0.3);
transform: scale(1.02);
}

.card-link {
text-decoration: none;
color: inherit;
display: block;
}

.card h3 {
font-size: 1.5rem;
margin-bottom: 15px;
text-shadow: 0 0 8px white;
}

.info {
font-size: 1rem;
color: #ccc;
text-shadow: 0 0 5px #aaa;
line-height: 1.5;
}

.button {
display: inline-block;
padding: 15px 30px;
font-size: 1rem;
background-color: #8000ff;
color: white;
border: none;
border-radius: 10px;
cursor: pointer;
text-decoration: none;
box-shadow: 0 0 12px #a64dff;
transition: all 0.3s ease;
margin-top: 20px;
}

.button:hover {
background-color: #9900ff;
box-shadow: 0 0 20px #d580ff;
}
</style>
