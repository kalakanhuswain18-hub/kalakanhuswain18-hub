
<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kalakanhu Swain | ML Engineer</title>

  <!-- Tailwind CDN -->

  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS Animation -->

  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <style>
    /* 🌊 Animated Gradient Background */
    body {
      margin: 0;
      font-family: sans-serif;
      background: linear-gradient(-45deg, #0f2027, #203a43, #2c5364, #000428);
      background-size: 400% 400%;
      animation: gradientBG 12s ease infinite;
      color: white;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* Floating profile */
    .float {
      animation: float 4s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-12px); }
      100% { transform: translateY(0px); }
    }

    /* Glow text */
    .glow {
      color: #00ffcc;
      text-shadow: 0 0 10px #00ffcc;
    }

    /* Button hover */
    .btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px #00ffcc;
    }

    html {
      scroll-behavior: smooth;
    }
  </style>

</head>

<body class="flex items-center justify-center min-h-screen">

  <div class="text-center p-6">

```
<!-- Profile -->
<img src="https://via.placeholder.com/150"
     class="mx-auto rounded-full w-36 h-36 border-4 border-green-400 float">

<!-- Name -->
<h1 class="text-3xl mt-4 font-bold glow" data-aos="fade-up">
  👋 Hi, I'm Kalakanhu Swain
</h1>

<!-- Typing text -->
<h2 class="text-lg mt-2 text-green-300" id="typing"></h2>

<!-- Email -->
<p class="mt-2">📧 kalakanhuswain18@gmail.com</p>

<!-- Links -->
<div class="mt-4 space-x-4">
  <a href="#" class="text-green-400 hover:underline">GitHub</a>
  <a href="#" class="text-green-400 hover:underline">LinkedIn</a>
</div>

<!-- Skills -->
<div class="mt-6" data-aos="fade-up">
  <h3 class="text-xl font-semibold">⚒ Skills</h3>
  <p class="mt-2">Python | Machine Learning | Scikit-learn | Pandas | HTML | CSS | JavaScript</p>
</div>

<!-- Projects -->
<div class="mt-6" data-aos="fade-up">
  <h3 class="text-xl font-semibold">📂 Projects</h3>
  <p class="mt-2">🏠 House Price Prediction (ML Model)</p>
  <p>🤖 Voice Assistant (Jarvis)</p>
</div>

<!-- Button -->
<button class="btn mt-6 bg-green-500 px-6 py-2 rounded-lg transition">
  📄 Download Resume
</button>

<p class="mt-6 text-sm">© 2026 Kalakanhu Swain</p>
```

  </div>

  <!-- AOS Script -->

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

  <script>
    AOS.init();

    // Typing animation
    const text = "🚀 Machine Learning Engineer & Frontend Developer";
    let i = 0;
    function typing() {
      if (i < text.length) {
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(typing, 50);
      }
    }
    typing();
  </script>

</body>
</html>
