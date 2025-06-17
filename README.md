<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Synapse.AI – Smart AI Assistant</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <header class="bg-white shadow sticky top-0 z-50">
    <div class="container mx-auto flex items-center justify-between px-4 py-3">
      <div class="flex items-center space-x-2">
        <img src="https://i.imgur.com/bErDYZx.png" alt="Synapse.AI Logo" class="w-10 h-10">
        <span class="text-xl font-bold text-blue-600">Synapse.AI</span>
      </div>
      <nav class="space-x-4 text-sm">
        <a href="#about" class="text-blue-600 hover:underline">About</a>
        <a href="#install" class="hover:text-blue-600">Install</a>
        <a href="#features" class="hover:text-blue-600">Features</a>
        <a href="#roadmap" class="hover:text-blue-600">Roadmap</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container mx-auto px-4 py-10">
    <!-- Hero -->
    <section class="text-center mb-12">
      <h1 class="text-4xl font-extrabold mb-4 text-gray-900">Your Smart AI Assistant</h1>
      <p class="text-lg text-gray-700 mb-6">Built using OpenAI, Tauri, Vue.js & Tailwind CSS. <br> Experience faster, smarter virtual conversations.</p>
      <a href="https://github.com/Harshit-Xylodev/Synapse.AI" class="px-6 py-3 bg-blue-600 text-white rounded hover:bg-blue-700 transition">View on GitHub</a>
    </section>

    <!-- About -->
    <section id="about" class="mb-12">
      <h2 class="text-2xl font-bold mb-4">About Synapse.AI</h2>
      <p class="text-gray-700 leading-relaxed">
        Synapse.AI is a next-gen virtual assistant powered by OpenAI APIs. It’s built for developers and productivity lovers who want an intuitive, privacy-focused AI assistant right on their desktop — without needing to open a browser.
      </p>
    </section>

    <!-- Installation -->
    <section id="install" class="mb-12">
      <h2 class="text-2xl font-bold mb-4">Getting Started</h2>
      <pre class="bg-gray-100 p-4 rounded text-sm overflow-auto"><code># Clone the repo
git clone https://github.com/Harshit-Xylodev/Synapse.AI

# Install dependencies
yarn install

# Set your API keys
SYNAPSE_OPENAI_API_KEY=your_api_key

# Run the app
yarn dev</code></pre>
    </section>

    <!-- Features -->
    <section id="features" class="mb-12">
      <h2 class="text-2xl font-bold mb-4">Key Features</h2>
      <ul class="list-disc list-inside text-gray-700 space-y-2">
        <li>Built with Vue.js, Tauri (Rust), and Tailwind CSS</li>
        <li>OpenAI GPT & Whisper integration</li>
        <li>Image generation via DALL·E</li>
        <li>Dark mode & Mobile Responsive UI</li>
        <li>Language support and Firebase integration</li>
      </ul>
    </section>

    <!-- Roadmap -->
    <section id="roadmap" class="mb-12">
      <h2 class="text-2xl font-bold mb-4">Roadmap</h2>
      <ul class="list-disc list-inside text-gray-700 space-y-2">
        <li>✅ Dark Mode UI</li>
        <li>✅ Mobile-Friendly Layout</li>
        <li>🔄 Voice recognition (Web + Whisper)</li>
        <li>🔄 Authentication & User Profiles</li>
        <li>🔄 Auto Language Detection</li>
      </ul>
    </section>

    <!-- Contact -->
    <section id="contact" class="mb-12">
      <h2 class="text-2xl font-bold mb-4">Connect</h2>
      <p class="text-gray-700">Project by <strong>Harshit</strong> @ <a href="https://github.com/Harshit-Xylodev" class="text-blue-600 underline">Harshit-Xylodev</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/harshitxylo/" target="_blank" class="text-blue-600 underline">harshitxylo</a></p>
    </section>

  </main>

  <footer class="text-center text-sm text-gray-500 border-t py-4">
    © 2025 Synapse.AI – Open Source MIT License
  </footer>

</body>
</html>
