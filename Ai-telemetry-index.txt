<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Developer Telemetry & Operations Suite | Live Demo</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- ApexCharts & Lucide Icons -->
  <script src="https://cdn.jsdelivr.net/npm/apexcharts"></script>
  <script src="https://unpkg.com/lucide@latest"></script>

  <!-- Gumroad Overlay Checkout JS -->
  <script src="https://gumroad.com/js/gumroad.js"></script>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; }
    .font-mono { font-family: 'JetBrains Mono', monospace; }
  </style>
</head>
<body class="bg-slate-950 text-slate-100 min-h-screen flex flex-col items-center selection:bg-emerald-500 selection:text-slate-950">

  <!-- Top Sticky Navigation CTA Banner -->
  <header class="w-full bg-slate-900/90 backdrop-blur-md border-b border-slate-800 sticky top-0 z-50 px-6 py-3.5 flex items-center justify-between">
    <div class="flex items-center gap-3">
      <div class="p-2 bg-emerald-500/10 text-emerald-400 rounded-lg border border-emerald-500/20">
        <i data-lucide="cpu" class="w-5 h-5"></i>
      </div>
      <div>
        <h1 class="text-sm font-bold text-white tracking-tight">AI Telemetry & Operations Suite</h1>
        <p class="text-[11px] text-slate-400">React, Vue 3, & HTML Component Bundle</p>
      </div>
    </div>

    <!-- Gumroad Checkout Trigger Button -->
    <a 
      class="gumroad-button bg-emerald-500 hover:bg-emerald-400 text-slate-950 text-xs font-bold px-4 py-2 rounded-lg transition-all flex items-center gap-2 shadow-lg shadow-emerald-500/20 cursor-pointer"
      href="https://YOUR_GUMROAD_USERNAME.gumroad.com/l/YOUR_PRODUCT_ID"
      target="_blank"
    >
      <i data-lucide="shopping-bag" class="w-4 h-4"></i>
      Get Full Suite ($29)
    </a>
  </header>

  <!-- Hero Intro Section -->
  <section class="w-full max-w-5xl px-6 pt-12 pb-8 text-center flex flex-col items-center">
    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-slate-900 border border-slate-800 text-emerald-400 text-xs font-mono mb-4">
      <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span> Production-Ready UI Kit
    </div>
    <h2 class="text-3xl md:text-4xl font-bold tracking-tight text-white mb-3">
      Multi-Provider LLM Telemetry & Cost Control
    </h2>
    <p class="text-slate-400 text-sm md:text-base max-w-2xl">
      Plug-and-play dark-mode native components for tracking API spending, optimizing token payloads, and automating webhook threshold alerts.
    </p>
  </section>

  <!-- Main Showcase Grid -->
  <main class="w-full max-w-5xl px-6 pb-16 grid grid-cols-1 md:grid-cols-2 gap-8 items-start">

    <!-- COMPONENT 1: AI Cost & Token Gauge Preview -->
    <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-2xl flex flex-col justify-between">
      <div>
        <div class="flex items-center justify-between border-b border-slate-800 pb-4 mb-5">
          <div class="flex items-center gap-2.5">
            <div class="p-2 bg-purple-500/10 text-purple-400 rounded-lg border border-purple-500/20">
              <i data-lucide="gauge" class="w-5 h-5"></i>
            </div>
            <div>
              <h3 class="text-sm font-bold text-white">AI Cost & Token Gauge</h3>
              <p class="text-[11px] text-slate-400">Multi-Provider Budget Tracker</p>
            </div>
          </div>
          <span class="px-2 py-0.5 bg-slate-950 border border-slate-800 text-purple-400 text-[10px] font-mono rounded-full">
            Component 1
          </span>
        </div>

        <!-- Mock Gauge Visual Representation -->
        <div class="bg-slate-950 border border-slate-800/80 p-5 rounded-xl mb-4 space-y-4">
          <div class="flex justify-between items-center text-xs font-mono">
            <span class="text-slate-400">Monthly Cap Usage</span>
            <span class="text-emerald-400 font-bold">$382.50 / $500.00 (76.5%)</span>
          </div>
          <div class="w-full bg-slate-800 h-3 rounded-full overflow-hidden">
            <div class="bg-gradient-to-r from-emerald-500 to-amber-400 h-full w-[76.5%]"></div>
          </div>
          <div class="grid grid-cols-3 gap-2 pt-2 text-center font-mono">
            <div class="bg-slate-900 p-2 rounded-lg border border-slate-800">
              <span class="text-[10px] text-slate-400 block">OpenAI</span>
              <span class="text-xs font-bold text-white">$240.10</span>
            </div>
            <div class="bg-slate-900 p-2 rounded-lg border border-slate-800">
              <span class="text-[10px] text-slate-400 block">Anthropic</span>
              <span class="text-xs font-bold text-white">$115.40</span>
            </div>
            <div class="bg-slate-900 p-2 rounded-lg border border-slate-800">
              <span class="text-[10px] text-slate-400 block">Cohere</span>
              <span class="text-xs font-bold text-white">$27.00</span>
            </div>
          </div>
        </div>
      </div>
      <p class="text-xs text-slate-400 italic">Includes interactive budget slider and 14-day ApexCharts trend analysis.</p>
    </div>

    <!-- COMPONENT 2: Call Slim Card Preview -->
    <div class="bg-slate-900 border border-slate-800 rounded-2xl p-6 shadow-2xl flex flex-col justify-between">
      <div>
        <div class="flex items-center justify-between border-b border-slate-800 pb-4 mb-5">
          <div class="flex items-center gap-2.5">
            <div class="p-2 bg-emerald-500/10 text-emerald-400 rounded-lg border border-emerald-500/20">
              <i data-lucide="zap" class="w-5 h-5"></i>
            </div>
            <div>
              <h3 class="text-sm font-bold text-white">Call Slim</h3>
              <p class="text-[11px] text-slate-400">Token Optimization Telemetry</p>
            </div>
          </div>
          <span class="px-2 py-0.5 bg-slate-950 border border-slate-800 text-emerald-400 text-[10px] font-mono rounded-full">
            Component 2
          </span>
        </div>

        <div class="grid grid-cols-2 gap-3 mb-4">
          <div class="bg-slate-950 border border-slate-800/80 p-3.5 rounded-xl">
            <span class="text-[10px] uppercase font-mono text-slate-400 block mb-1">Payload Reduction</span>
            <div class="flex items-baseline gap-1">
              <span class="text-2xl font-bold font-mono text-emerald-400">-30.0%</span>
              <i data-lucide="arrow-down-right" class="w-4 h-4 text-emerald-400"></i>
            </div>
            <span class="text-[10px] text-slate-400 mt-1 block">360k Tokens Saved</span>
          </div>

          <div class="bg-slate-950 border border-slate-800/80 p-3.5 rounded-xl">
            <span class="text-[10px] uppercase font-mono text-slate-400 block mb-1">Estimated Savings</span>
            <span class="text-2xl font-bold font-mono text-white">$0.72</span>
            <span class="text-[10px] text-slate-400 mt-1 block">Direct API Cost Cut</span>
          </div>
        </div>

        <div class="bg-slate-950 border border-slate-800/80 p-4 rounded-xl space-y-2 mb-4">
          <div class="flex justify-between text-xs font-mono">
            <span class="text-slate-400">Payload Density</span>
            <span class="text-slate-200">840k / 1,200k</span>
          </div>
          <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden flex">
            <div class="bg-emerald-400 h-full w-[70%]"></div>
            <div class="bg-slate-700/50 h-full w-[30%]"></div>
          </div>
        </div>
      </div>

      <div class="grid grid-cols-2 gap-2 text-xs font-mono text-slate-400 border-t border-slate-800/80 pt-3">
        <div class="flex items-center gap-1.5">
          <i data-lucide="activity" class="w-3.5 h-3.5 text-blue-400"></i>
          <span>Latency: <strong class="text-slate-200">320ms</strong></span>
        </div>
        <div class="flex items-center gap-1.5 justify-end">
          <i data-lucide="cpu" class="w-3.5 h-3.5 text-purple-400"></i>
          <span>Rate: <strong class="text-slate-200">85/100 RPM</strong></span>
        </div>
      </div>
    </div>

  </main>

  <!-- Bottom CTA Footer -->
  <footer class="w-full bg-slate-900 border-t border-slate-800 py-8 px-6 text-center flex flex-col items-center gap-4">
    <p class="text-slate-400 text-sm">Ready to integrate these components into your React or Vue 3 app?</p>
    <a 
      class="gumroad-button bg-emerald-500 hover:bg-emerald-400 text-slate-950 text-sm font-bold px-6 py-3 rounded-xl transition-all shadow-xl shadow-emerald-500/20 flex items-center gap-2 cursor-pointer"
      href="https://YOUR_GUMROAD_USERNAME.gumroad.com/l/YOUR_PRODUCT_ID"
      target="_blank"
    >
      <i data-lucide="shopping-bag" class="w-4 h-4"></i>
      Download Full Component Suite ($29)
    </a>
    <p class="text-[11px] text-slate-600 font-mono mt-2">Includes full source code (.jsx, .vue, HTML) + README + License.</p>
  </footer>

  <script>
    // Initialize Lucide Icons
    lucide.createIcons();
  </script>
</body>
</html>
