
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PowerTechHub | Premium High-Speed Web Agency</title>
    <meta name="description" content="Custom-coded websites with 99/100 performance. Built for modern businesses.">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #050505; color: white; font-family: sans-serif; scroll-behavior: smooth; }
        .glass { background: rgba(255, 255, 255, 0.05); backdrop-filter: blur(12px); border: 1px solid rgba(255, 255, 255, 0.1); }
        .blue-glow { background: radial-gradient(circle at center, #1e40af 0%, transparent 70%); }
    </style>
</head>
<body class="blue-glow min-h-screen">

    <nav class="flex justify-between items-center p-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold tracking-tighter text-blue-500">POWERTECHHUB</div>
        <a href="https://wa.me/918619436849" class="bg-blue-600 px-6 py-2 rounded-full font-bold hover:bg-blue-700 transition shadow-lg shadow-blue-500/20">Hire Us</a>
    </nav>

    <section class="text-center py-20 px-4">
        <div class="inline-block px-4 py-1 border border-blue-500/30 rounded-full text-blue-400 text-xs font-bold mb-6 tracking-widest uppercase">Available For Sale</div>
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 italic text-blue-500">Built for Growth.</h1>
        <p class="text-gray-400 max-w-2xl mx-auto mb-10 text-lg leading-relaxed">Premium, custom-coded digital experiences that convert visitors into paying clients. High speed. Clean code. Bold design.</p>
        
        <div class="inline-flex items-center gap-2 bg-green-900/30 text-green-400 px-4 py-2 rounded-lg border border-green-500/30 mb-8">
            <span class="text-xl font-bold">99/100</span>
            <span class="text-xs font-bold uppercase tracking-widest">PageSpeed Score</span>
        </div>
    </section>

    <section class="max-w-6xl mx-auto py-12 px-4" id="work">
        <h2 class="text-3xl font-bold text-center mb-12">Our Latest Creations</h2>
        <div class="grid md:grid-cols-2 gap-8">
            <div class="rounded-3xl overflow-hidden glass aspect-video relative group border border-white/5">
                <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=800" alt="Tech Dashboard" class="w-full h-full object-cover opacity-70 group-hover:scale-105 transition duration-500">
                <div class="absolute inset-0 flex items-center justify-center font-bold text-xl bg-black/20">Tech Dashboard</div>
            </div>
            <div class="rounded-3xl overflow-hidden glass aspect-video relative group border border-white/5">
                <img src="https://images.unsplash.com/photo-1497215728101-856f4ea42174?w=800" alt="Creative Agency" class="w-full h-full object-cover opacity-70 group-hover:scale-105 transition duration-500">
                <div class="absolute inset-0 flex items-center justify-center font-bold text-xl bg-black/20">Creative Agency</div>
            </div>
        </div>
    </section>

    <section class="max-w-xl mx-auto py-20 px-4">
        <div class="glass p-8 rounded-3xl border-blue-500/30 shadow-2xl">
            <h2 class="text-2xl font-bold mb-6 text-center">Get a Free Quote (Email Us)</h2>
            <form action="https://formspree.io/f/xvgzlowy" method="POST" class="space-y-4">
                <input type="text" name="name" placeholder="Full Name" required class="w-full bg-black/40 border border-gray-800 p-4 rounded-xl outline-none focus:border-blue-500 transition">
                <input type="email" name="email" placeholder="Email Address" required class="w-full bg-black/40 border border-gray-800 p-4 rounded-xl outline-none focus:border-blue-500 transition">
                <textarea name="message" placeholder="Describe your project..." rows="4" required class="w-full bg-black/40 border border-gray-800 p-4 rounded-xl outline-none focus:border-blue-500 transition"></textarea>
                <button type="submit" class="w-full bg-blue-600 py-4 rounded-xl font-bold text-lg hover:bg-blue-700 transition shadow-lg shadow-blue-500/20">Send To My Gmail</button>
            </form>
        </div>
    </section>

    <footer class="text-center py-10 text-gray-600 border-t border-gray-900 mt-10">
        <p>© 2026 PowerTechHub Agency. Built for Speed and Sale.</p>
    </footer>

</body>
</html>
