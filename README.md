<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pragy Mathur | Product Manager Portfolio</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Custom smooth scroll and hidden scrollbar options */
        html { scroll-behavior: smooth; }
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-[#0b0f19] text-gray-100 font-sans selection:bg-amber-500 selection:text-slate-900">

    <div id="video-overlay" class="fixed inset-0 z-50 bg-black flex items-center justify-center cursor-pointer transition-opacity duration-700 ease-in-out">
        <video id="intro-video" class="w-full h-full object-cover pointer-events-none" autoplay muted playsinline>
            <source src="intro.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        
        <div class="absolute top-6 right-6 bg-black/60 backdrop-blur-md border border-white/10 text-white/80 px-4 py-2 rounded-full text-xs font-medium tracking-wider uppercase pointer-events-auto hover:bg-white hover:text-black transition-colors">
            Skip Intro ➔
        </div>
        <div class="absolute bottom-8 text-center text-white/40 text-xs tracking-widest uppercase pointer-events-none hidden md:block">
            Click anywhere on screen to enter site
        </div>
    </div>

    <div id="main-content" class="hidden min-h-screen opacity-0 transition-opacity duration-1000 ease-in-out">
        
        <header class="sticky top-0 z-40 bg-[#0b0f19]/80 backdrop-blur-md border-b border-slate-800 px-6 py-4 flex justify-between items-center">
            <div>
                <h1 class="text-xl font-bold tracking-tight text-white uppercase">Pragy Mathur</h1>
                <p class="text-xs text-amber-500 font-medium tracking-widest uppercase">AI Product Strategy</p>
            </div>
            <a href="mailto:pragymathur12@gmail.com" class="bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold px-4 py-2 rounded text-xs tracking-wider uppercase transition-all shadow-lg shadow-amber-500/10">
                Hire Me
            </a>
        </header>

        <main class="max-w-7xl mx-auto p-4 md:p-8 grid grid-cols-1 lg:grid-cols-12 gap-8">
            
            <section class="lg:col-span-7 bg-[#111827] border border-slate-800 rounded-xl p-6 md:p-8 shadow-2xl relative overflow-hidden">
                <div class="absolute -top-40 -left-40 w-80 h-80 bg-amber-500/5 rounded-full blur-3xl pointer-events-none"></div>
                
                <div class="flex flex-wrap items-center gap-y-2 gap-x-4 border-b border-slate-800 pb-6 mb-6 text-sm text-gray-400">
                    <span class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-amber-500"></i> Jodhpur, India</span>
                    <span class="text-slate-700">|</span>
                    <a href="tel:+919509932859" class="hover:text-amber-500 transition-colors flex items-center gap-2"><i class="fa-solid fa-phone text-amber-500"></i> +91 9509932859</a>
                    <span class="text-slate-700">|</span>
                    <a href="mailto:pragymathur12@gmail.com" class="hover:text-amber-500 transition-colors flex items-center gap-2"><i class="fa-solid fa-envelope text-amber-500"></i> pragymathur12@gmail.com</a>
                </div>

                <div class="mb-8">
                    <h3 class="text-xs font-bold uppercase tracking-widest text-amber-500 mb-2">Professional Summary</h3>
                    <p class="text-gray-300 text-sm leading-relaxed">
                        Forward-thinking Integrated MBA candidate specializing in International Business, combining a strong foundation in product strategy with hands-on digital marketing execution. Highly proficient in utilizing cutting-edge AI stacks to automate product workflows, draft PRDs, and conduct deep user research.
                    </p>
                </div>

                <div class="mb-8">
                    <h3 class="text-xs font-bold uppercase tracking-widest text-amber-500 mb-3">Featured Framework</h3>
                    <div class="bg-slate-900/60 border border-slate-800 p-5 rounded-lg">
                        <h4 class="text-white font-bold text-base mb-1">UBER COMMUTE LOCK</h4>
                        <p class="text-xs text-slate-400 mb-4 uppercase tracking-wider">AI-Augmented Product Management Framework</p>
                        <ul class="space-y-2 text-xs text-gray-300 list-none pl-0">
                            <li class="flex gap-2"><span class="text-amber-500">■</span> Co-authored a comprehensive PRD via ChatPRD and Claude, purposefully engineering constraints for high-concurrency 9:00 AM API spikes.</li>
                            <li class="flex gap-2"><span class="text-amber-500">■</span> Utilized Kimi's parallel multi-agent search to analyze competitor failure states and ride-hailing churn trends 4x faster.</li>
                            <li class="flex gap-2"><span class="text-amber-500">■</span> Leveraged v0 by Vercel to generate a functional mobile UI prototype, tracking code deployments via GitHub.</li>
                        </ul>
                    </div>
                </div>

                <div class="mb-8">
                    <h3 class="text-xs font-bold uppercase tracking-widest text-amber-500 mb-4">Projects & Experience</h3>
                    <div class="space-y-6 border-l border-slate-800 pl-4 ml-2">
                        <div class="relative">
                            <div class="absolute -left-[21px] top-1 bg-amber-500 w-2.5 h-2.5 rounded-full ring-4 ring-[#111827]"></div>
                            <span class="text-[10px] uppercase font-mono tracking-wider text-slate-400">2025 - 2026</span>
                            <h4 class="text-white font-semibold text-sm">Project Lead & Producer</h4>
                            <p class="text-xs text-amber-500/90 mb-1">Independent Media Project - 'Ye Rasta Jata Kaha'</p>
                            <p class="text-xs text-gray-400">Spearheaded end-to-end production pipelines, cross-functional logistics, and digital growth marketing models for an independent release ecosystem.</p>
                        </div>
                        <div class="relative">
                            <div class="absolute -left-[21px] top-1 bg-slate-700 w-2.5 h-2.5 rounded-full ring-4 ring-[#111827]"></div>
                            <span class="text-[10px] uppercase font-mono tracking-wider text-slate-400">2020 - 2023</span>
                            <h4 class="text-white font-semibold text-sm">Web Content & Marketing Lead</h4>
                            <p class="text-xs text-amber-500/90 mb-1">Personal Brand & Digital Platforms</p>
                            <p class="text-xs text-gray-400">Managed cross-channel delivery frameworks across YouTube and web blogs, building data-backed scheduling pipelines to systematic track digital growth traffic metrics.</p>
                        </div>
                    </div>
                </div>

                <div>
                    <h3 class="text-xs font-bold uppercase tracking-widest text-amber-500 mb-3">Academic Credentials</h3>
                    <div class="bg-slate-900/40 p-4 rounded-lg border border-slate-800/60 flex justify-between items-center">
                        <div>
                            <h4 class="text-white font-bold text-sm">Parul Institute of Business Administration</h4>
                            <p class="text-xs text-gray-400">Integrated MBA (International Business) — Semester 07</p>
                        </div>
                        <span class="text-xs font-mono bg-slate-800 px-2 py-1 rounded text-amber-400 shrink-0">Exp: 2027</span>
                    </div>
                </div>
            </section>

            <section class="lg:col-span-5 flex flex-col gap-6">
                
                <div class="bg-[#111827] border border-slate-800 rounded-xl p-6 shadow-xl">
                    <h3 class="text-xs font-bold uppercase tracking-widest text-slate-400 mb-4">Registry Channels</h3>
                    <div class="grid grid-cols-2 gap-3">
                        <a href="https://linkedin.com/in/pragy-mathur-2a9393257" target="_blank" class="flex items-center justify-center gap-2 bg-[#1d2433] hover:bg-slate-800 border border-slate-700/60 p-3 rounded-lg text-xs font-semibold text-white tracking-wider uppercase transition-all group">
                            <i class="fa-brands fa-linkedin text-lg text-blue-400 group-hover:scale-110 transition-transform"></i> LinkedIn
                        </a>
                        <a href="https://github.com/pragymathur12-king" target="_blank" class="flex items-center justify-center gap-2 bg-[#1d2433] hover:bg-slate-800 border border-slate-700/60 p-3 rounded-lg text-xs font-semibold text-white tracking-wider uppercase transition-all group">
                            <i class="fa-brands fa-github text-lg text-purple-400 group-hover:scale-110 transition-transform"></i> GitHub
                        </a>
                    </div>
                </div>

                <div class="bg-[#111827] border border-slate-800 rounded-xl p-6 shadow-xl relative overflow-hidden flex-1">
                    <h3 class="text-xs font-bold uppercase tracking-widest text-amber-500 mb-4">Product Intelligence Arsenal</h3>
                    
                    <div class="space-y-4">
                        <div class="border-b border-slate-800/80 pb-3">
                            <span class="text-xs font-bold block text-white mb-1">Strategy & Feature Scoping</span>
                            <div class="flex flex-wrap gap-1.5 text-[11px] font-mono">
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Claude</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">ChatPRD</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Kimi AI</span>
                            </div>
                        </div>

                        <div class="border-b border-slate-800/80 pb-3">
                            <span class="text-xs font-bold block text-white mb-1">User Research & Discovery</span>
                            <div class="flex flex-wrap gap-1.5 text-[11px] font-mono">
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Granola AI</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Perplexity</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">NotebookLM</span>
                            </div>
                        </div>

                        <div class="border-b border-slate-800/80 pb-3">
                            <span class="text-xs font-bold block text-white mb-1">Prototyping & Infrastructure</span>
                            <div class="flex flex-wrap gap-1.5 text-[11px] font-mono">
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">v0 by Vercel</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">GitHub Architecture</span>
                            </div>
                        </div>

                        <div>
                            <span class="text-xs font-bold block text-white mb-1">Execution frameworks</span>
                            <div class="flex flex-wrap gap-1.5 text-[11px] font-mono">
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Design Thinking</span>
                                <span class="bg-slate-900 border border-slate-800 px-2 py-0.5 rounded text-gray-300">Agile Backlogs (Jira/Linear)</span>
                            </div>
                        </div>
                    </div>
                </div>
            </main>
        </div>

    <script>
        const videoOverlay = document.getElementById('video-overlay');
        const introVideo = document.getElementById('intro-video');
        const mainContent = document.getElementById('main-content');

        // Main action to skip video and animate entry into page
        function transitionToWebsite() {
            // Fade out the overlay cleanly
            videoOverlay.style.opacity = '0';
            
            // Allow background rendering smoothly
            mainContent.classList.remove('hidden');
            setTimeout(() => {
                mainContent.style.opacity = '1';
                // Completely erase screen space footprint of video layer after fade completes
                videoOverlay.remove();
            }, 50);
        }

        // Click or tap anywhere triggers skip execution
        videoOverlay.addEventListener('click', transitionToWebsite);

        // Auto transition sequence fires if video finishes on its own
        introVideo.addEventListener('ended', transitionToWebsite);
    </script>
</body>
</html>
