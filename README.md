<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mihir Sharma — GitHub Profile Preview & README.md</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            ghBg: '#0D1117',
            ghCard: '#161B22',
            ghBorder: '#30363D',
            electricBlue: '#58A6FF',
            violetAccent: '#7C3AED',
            ghText: '#C9D1D9',
            ghMuted: '#8B949E'
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            mono: ['Fira Code', 'monospace']
          }
        }
      }
    }
  </script>
  <style>
    body {
      background-color: #0D1117;
      color: #C9D1D9;
      font-family: 'Inter', sans-serif;
    }
    .glow-violet {
      box-shadow: 0 0 25px -5px rgba(124, 58, 237, 0.25);
    }
    .glow-blue {
      box-shadow: 0 0 25px -5px rgba(88, 166, 255, 0.2);
    }
    .border-gradient {
      border-image: linear-gradient(to right, #58A6FF, #7C3AED) 1;
    }
    /* Custom scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #0D1117;
    }
    ::-webkit-scrollbar-thumb {
      background: #30363D;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #484F58;
    }
  </style>
</head>
<body class="bg-ghBg text-ghText min-h-screen flex flex-col items-center justify-start p-2 sm:p-6 antialiased">

  <!-- Top Tab Navigation Switcher (Preview vs Raw Markdown) -->
  <header class="w-full max-w-5xl mb-6 flex flex-wrap items-center justify-between border-b border-ghBorder pb-4 px-2">
    <div class="flex items-center space-x-3 mb-2 sm:mb-0">
      <div class="w-8 h-8 rounded-full bg-gradient-to-tr from-electricBlue to-violetAccent flex items-center justify-center text-white font-bold text-sm">
        MS
      </div>
      <div>
        <h1 class="text-white font-bold text-base leading-tight">Mihir Sharma</h1>
        <p class="text-xs text-ghMuted font-mono">github.com/mihirsharma1824</p>
      </div>
    </div>
    
    <div class="flex items-center space-x-2 bg-ghCard p-1 rounded-lg border border-ghBorder text-xs font-medium">
      <button id="btn-preview" onclick="switchTab('preview')" class="px-4 py-1.5 rounded-md bg-violetAccent text-white transition-all shadow-sm">
        Live Profile Preview
      </button>
      <button id="btn-markdown" onclick="switchTab('markdown')" class="px-4 py-1.5 rounded-md text-ghMuted hover:text-white transition-all">
        Raw README.md Source
      </button>
    </div>
  </header>

  <!-- MAIN PREVIEW CONTAINER -->
  <main id="tab-preview-content" class="w-full max-w-5xl bg-ghBg border border-ghBorder rounded-2xl shadow-2xl overflow-hidden transition-all">
    
    <!-- SECTION 1: HERO -->
    <section class="relative w-full flex flex-col items-center text-center pb-8 overflow-hidden">
      <!-- Animated Header Capsule -->
      <div class="w-full overflow-hidden">
        <img 
          src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=220&section=header&text=MIHIR%20SHARMA&fontSize=46&fontColor=ffffff&animation=fadeIn" 
          alt="Mihir Sharma Banner" 
          class="w-full h-auto min-h-[160px] object-cover"
        />
      </div>

      <div class="px-4 -mt-4 sm:-mt-6 z-10 w-full max-w-3xl flex flex-col items-center">
        <!-- Animated Typing SVG -->
        <div class="my-3 flex justify-center w-full">
          <img 
            src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=AI+%26+Data+Engineer;Building+Intelligent+Systems;Exploring+LLM+Infrastructure;Engineering+Efficient+AI+Systems" 
            alt="Typing Subtitle"
            class="max-w-full h-auto"
          />
        </div>

        <!-- Tagline -->
        <p class="text-ghText font-medium text-base sm:text-lg mb-6 italic tracking-wide">
          "Engineering intelligent systems. Exploring what's possible."
        </p>

        <!-- Social Action Buttons -->
        <div class="flex flex-wrap items-center justify-center gap-3">
          <a href="https://github.com/mihirsharma1824" target="_blank" rel="noopener noreferrer" class="hover:opacity-90 transition-opacity">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge" />
          </a>
          <a href="https://linkedin.com/in/mihirsharma24" target="_blank" rel="noopener noreferrer" class="hover:opacity-90 transition-opacity">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge" />
          </a>
          <a href="mailto:mihirsharma1824@gmail.com" class="hover:opacity-90 transition-opacity">
            <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge" />
          </a>
        </div>
      </div>
    </section>

    <div class="px-4 sm:px-10 py-6 space-y-12">

      <!-- SECTION 2: BEYOND THE CODE -->
      <section class="border-t border-ghBorder/50 pt-8">
        <div class="flex items-center space-x-2 text-violetAccent text-xs font-mono font-semibold tracking-wider uppercase mb-2">
          <span>// Editorial Overview</span>
        </div>
        <h2 class="text-2xl sm:text-3xl font-bold text-white mb-4">
          I build systems, not just applications.
        </h2>
        <p class="text-ghText leading-relaxed text-sm sm:text-base max-w-4xl mb-8">
          I'm fascinated by what happens behind intelligent systems — from the way LLMs process information to how data moves through scalable infrastructure. I enjoy exploring ideas at the intersection of AI, systems engineering, and performance optimization, turning technical concepts into practical engineering solutions.
        </p>

        <!-- Technical Interest Cards Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mb-6">
          
          <div class="bg-ghCard p-4 rounded-xl border border-ghBorder hover:border-violetAccent/60 transition-all duration-300">
            <div class="text-xs font-mono text-electricBlue mb-1 font-semibold">01. ARTIFICIAL INTELLIGENCE</div>
            <h3 class="text-white font-semibold text-base mb-2">AI & Machine Learning</h3>
            <div class="flex flex-wrap gap-1.5">
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Python</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">PyTorch</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Machine Learning</span>
            </div>
          </div>

          <div class="bg-ghCard p-4 rounded-xl border border-ghBorder hover:border-violetAccent/60 transition-all duration-300">
            <div class="text-xs font-mono text-electricBlue mb-1 font-semibold">02. INFRASTRUCTURE</div>
            <h3 class="text-white font-semibold text-base mb-2">LLM Infrastructure</h3>
            <div class="flex flex-wrap gap-1.5">
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">LLMs</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Inference Optimization</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Prefix Caching</span>
            </div>
          </div>

          <div class="bg-ghCard p-4 rounded-xl border border-ghBorder hover:border-violetAccent/60 transition-all duration-300">
            <div class="text-xs font-mono text-electricBlue mb-1 font-semibold">03. RETRIEVAL & SEARCH</div>
            <h3 class="text-white font-semibold text-base mb-2">Retrieval Systems</h3>
            <div class="flex flex-wrap gap-1.5">
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">RAG</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Cache-aware Routing</span>
            </div>
          </div>

          <div class="bg-ghCard p-4 rounded-xl border border-ghBorder hover:border-violetAccent/60 transition-all duration-300">
            <div class="text-xs font-mono text-electricBlue mb-1 font-semibold">04. SERVICES</div>
            <h3 class="text-white font-semibold text-base mb-2">Backend Engineering</h3>
            <div class="flex flex-wrap gap-1.5">
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Python</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">FastAPI</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">API Development</span>
            </div>
          </div>

          <div class="bg-ghCard p-4 rounded-xl border border-ghBorder hover:border-violetAccent/60 transition-all duration-300 md:col-span-2 lg:col-span-1">
            <div class="text-xs font-mono text-electricBlue mb-1 font-semibold">05. DATA & STORAGE</div>
            <h3 class="text-white font-semibold text-base mb-2">Data Engineering</h3>
            <div class="flex flex-wrap gap-1.5">
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">MySQL</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Data Processing</span>
              <span class="px-2 py-0.5 text-xs rounded bg-ghBg text-ghMuted border border-ghBorder">Database Systems</span>
            </div>
          </div>

        </div>

        <!-- Currently In Lab Indicator -->
        <div class="inline-flex items-center space-x-3 bg-ghCard px-4 py-2 rounded-full border border-ghBorder text-xs font-mono">
          <span class="relative flex h-2.5 w-2.5">
            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span>
            <span class="relative inline-flex rounded-full h-2.5 w-2.5 bg-emerald-500"></span>
          </span>
          <span class="text-ghMuted">CURRENTLY IN THE LAB:</span>
          <span class="text-white font-semibold">CacheRag</span>
        </div>
      </section>

      <!-- SECTION 3: FEATURED PROJECT (CacheRag) -->
      <section class="border-t border-ghBorder/50 pt-8">
        <div class="bg-gradient-to-b from-ghCard to-ghBg border border-ghBorder rounded-2xl p-6 sm:p-8 relative overflow-hidden glow-violet">
          <!-- Spotlight Accent Header -->
          <div class="flex flex-wrap items-center justify-between gap-2 mb-4">
            <div class="inline-block px-3 py-1 rounded-md bg-violetAccent/20 border border-violetAccent/40 text-violetAccent text-xs font-mono font-semibold">
              FEATURED SYSTEM ARCHITECTURE
            </div>
            <a href="https://github.com/mihirsharma1824/CacheRag" target="_blank" rel="noopener noreferrer" class="text-xs font-mono text-electricBlue hover:underline flex items-center gap-1">
              View Repository →
            </a>
          </div>

          <h3 class="text-3xl font-extrabold text-white tracking-tight mb-1">
            CacheRag
          </h3>
          <p class="text-electricBlue font-medium text-sm sm:text-base mb-4">
            Cache-Aware Routing and Prefix Caching for Efficient LLM Inference
          </p>
          <p class="text-ghMuted text-xs sm:text-sm italic mb-6">
            "Making LLM serving smarter through caching and intelligent request routing."
          </p>

          <p class="text-ghText text-sm sm:text-base leading-relaxed mb-8 max-w-4xl">
            LLM inference can repeatedly process shared prompt prefixes, creating opportunities for redundant computation. CacheRag explores how cache-aware request routing and prefix caching can make inference systems more efficient.
          </p>

          <!-- 3-Column Engineering Concept Cards -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-8">
            <div class="bg-ghBg/80 p-4 rounded-xl border border-ghBorder">
              <div class="text-violetAccent font-mono text-xs font-bold mb-1">CONCEPT 01</div>
              <h4 class="text-white font-semibold text-sm mb-2">PREFIX CACHING</h4>
              <p class="text-ghMuted text-xs leading-relaxed">
                Explore reuse of previously computed shared prompt prefixes across model execution steps.
              </p>
            </div>
            <div class="bg-ghBg/80 p-4 rounded-xl border border-ghBorder">
              <div class="text-electricBlue font-mono text-xs font-bold mb-1">CONCEPT 02</div>
              <h4 class="text-white font-semibold text-sm mb-2">CACHE-AWARE ROUTING</h4>
              <p class="text-ghMuted text-xs leading-relaxed">
                Explore routing decisions that account for prompt cache locality to maximize hit rates.
              </p>
            </div>
            <div class="bg-ghBg/80 p-4 rounded-xl border border-ghBorder">
              <div class="text-emerald-400 font-mono text-xs font-bold mb-1">CONCEPT 03</div>
              <h4 class="text-white font-semibold text-sm mb-2">INFERENCE EFFICIENCY</h4>
              <p class="text-ghMuted text-xs leading-relaxed">
                Investigate ways to reduce redundant computation and improve overall serving throughput.
              </p>
            </div>
          </div>

          <!-- Architecture Workflow Visual Diagram -->
          <div class="bg-ghBg p-4 sm:p-6 rounded-xl border border-ghBorder mb-8">
            <div class="text-xs font-mono text-ghMuted mb-4 text-center sm:text-left">SYSTEM WORKFLOW DIAGRAM</div>
            <div class="flex flex-col md:flex-row items-center justify-between gap-3 text-xs font-mono">
              <div class="w-full md:w-auto px-4 py-2.5 rounded-lg bg-ghCard border border-ghBorder text-center text-ghText font-medium">
                Incoming Requests
              </div>
              <div class="text-violetAccent font-bold rotate-90 md:rotate-0">→</div>
              <div class="w-full md:w-auto px-4 py-2.5 rounded-lg bg-ghCard border border-ghBorder text-center text-ghText font-medium">
                Request Analysis
              </div>
              <div class="text-violetAccent font-bold rotate-90 md:rotate-0">→</div>
              <div class="w-full md:w-auto px-4 py-2.5 rounded-lg bg-ghCard border border-electricBlue/50 text-center text-electricBlue font-semibold bg-electricBlue/5">
                Cache-Aware Routing
              </div>
              <div class="text-violetAccent font-bold rotate-90 md:rotate-0">→</div>
              <div class="w-full md:w-auto px-4 py-2.5 rounded-lg bg-ghCard border border-violetAccent/50 text-center text-violetAccent font-semibold bg-violetAccent/5">
                Prefix Cache / Inference
              </div>
              <div class="text-violetAccent font-bold rotate-90 md:rotate-0">→</div>
              <div class="w-full md:w-auto px-4 py-2.5 rounded-lg bg-ghCard border border-ghBorder text-center text-ghText font-medium">
                LLM Response
              </div>
            </div>
          </div>

          <!-- Project Vision Statement & Call to Action -->
          <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 pt-2 border-t border-ghBorder/60">
            <div class="max-w-2xl">
              <span class="text-xs font-mono text-ghMuted uppercase font-semibold block mb-1">Project Vision</span>
              <p class="text-xs sm:text-sm text-ghText leading-relaxed">
                Build a more intelligent inference-serving workflow where cache awareness becomes part of request routing, helping explore better resource utilization and reduced redundant computation.
              </p>
            </div>
            <a href="https://github.com/mihirsharma1824/CacheRag" target="_blank" rel="noopener noreferrer" class="shrink-0 px-5 py-2.5 rounded-lg bg-violetAccent hover:bg-violet-700 text-white text-xs font-medium transition-colors shadow-lg shadow-violetAccent/20 flex items-center gap-2">
              <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
              Explore CacheRag Repo
            </a>
          </div>
        </div>
      </section>

      <!-- SECTION 4: TECH STACK -->
      <section class="border-t border-ghBorder/50 pt-8">
        <div class="flex items-center space-x-2 text-electricBlue text-xs font-mono font-semibold tracking-wider uppercase mb-2">
          <span>// STACK & TOOLING</span>
        </div>
        <h2 class="text-xl sm:text-2xl font-bold text-white mb-6">Technologies & Engineering Tools</h2>

        <!-- Skillicons CDN Renderer -->
        <div class="bg-ghCard p-6 rounded-2xl border border-ghBorder flex flex-col items-center sm:items-start space-y-4">
          <img 
            src="https://skillicons.dev/icons?i=c,cpp,py,pytorch,fastapi,mysql,html,css,git,docker&perline=5" 
            alt="Technologies Stack"
            class="max-w-full h-auto"
          />
          <div class="w-full pt-4 border-t border-ghBorder/50 flex flex-wrap gap-4 text-xs font-mono text-ghMuted">
            <span><strong class="text-white">Programming:</strong> C, C++, Python</span>
            <span><strong class="text-white">AI/ML:</strong> PyTorch</span>
            <span><strong class="text-white">Backend:</strong> FastAPI</span>
            <span><strong class="text-white">Database:</strong> MySQL</span>
            <span><strong class="text-white">Tools:</strong> Git, Docker</span>
          </div>
        </div>
      </section>

      <!-- SECTION 5: OTHER PROJECTS -->
      <section class="border-t border-ghBorder/50 pt-8">
        <div class="flex items-center space-x-2 text-violetAccent text-xs font-mono font-semibold tracking-wider uppercase mb-2">
          <span>// ADDITIONAL REPOSITORIES</span>
        </div>
        <h2 class="text-xl sm:text-2xl font-bold text-white mb-6">Other Projects</h2>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <!-- Featured Repository Card -->
          <div class="flex justify-center items-center">
            <a href="https://github.com/Samudra-Setu" target="_blank" rel="noopener noreferrer" class="w-full">
              <img 
                src="https://github-readme-stats.vercel.app/api/pin/?username=mihirsharma1824&repo=Samudra-Setu&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D" 
                alt="Samudra-Setu Repository"
                class="w-full h-auto rounded-xl hover:opacity-95 transition-opacity"
              />
            </a>
          </div>

          <!-- Clean Dash Placeholder for Future Works -->
          <div class="bg-ghBg border-2 border-dashed border-ghBorder rounded-xl p-6 flex flex-col items-center justify-center text-center min-h-[140px]">
            <div class="w-10 h-10 rounded-full bg-ghCard flex items-center justify-center text-ghMuted mb-2 font-mono text-lg">+</div>
            <h4 class="text-ghText font-medium text-sm">More Projects In Development</h4>
            <p class="text-ghMuted text-xs mt-1 max-w-xs">Exploring new concepts in AI systems & distributed data pipelines.</p>
          </div>
        </div>
      </section>

      <!-- SECTION 6: GITHUB ANALYTICS DASHBOARD -->
      <section class="border-t border-ghBorder/50 pt-8">
        <div class="flex items-center space-x-2 text-electricBlue text-xs font-mono font-semibold tracking-wider uppercase mb-2">
          <span>// ACTIVITY & METRICS</span>
        </div>
        <h2 class="text-xl sm:text-2xl font-bold text-white mb-6">GitHub Profile Insights</h2>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
          <!-- Profile Stats -->
          <div class="flex justify-center">
            <img 
              src="https://github-readme-stats.vercel.app/api?username=mihirsharma1824&show_icons=true&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D&hide_border=false" 
              alt="Mihir's GitHub Stats" 
              class="w-full h-auto rounded-xl"
            />
          </div>
          
          <!-- Top Languages -->
          <div class="flex justify-center">
            <img 
              src="https://github-readme-stats.vercel.app/api/top-langs/?username=mihirsharma1824&layout=compact&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D&hide_border=false" 
              alt="Top Languages" 
              class="w-full h-auto rounded-xl"
            />
          </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <!-- Streak Stats -->
          <div class="flex justify-center">
            <img 
              src="https://streak-stats.demolab.com?user=mihirsharma1824&theme=dark&background=161B22&border=30363D&stroke=7C3AED&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9&sideNums=C9D1D9&sideTitle=8B949E&dates=8B949E" 
              alt="GitHub Streak Stats" 
              class="w-full h-auto rounded-xl"
            />
          </div>

          <!-- Activity Graph -->
          <div class="flex justify-center">
            <img 
              src="https://github-readme-activity-graph.vercel.app/graph?username=mihirsharma1824&theme=github-compact&bg_color=161B22&color=58A6FF&line=7C3AED&point=FFFFFF&area=true&hide_border=false&border_color=30363D" 
              alt="Contribution Activity Graph" 
              class="w-full h-auto rounded-xl"
            />
          </div>
        </div>
      </section>

      <!-- SECTION 7: CONNECT & FOOTER -->
      <section class="border-t border-ghBorder/50 pt-8 text-center pb-4">
        <h2 class="text-2xl sm:text-3xl font-bold text-white mb-3">
          Let's build something meaningful.
        </h2>
        <p class="text-ghMuted text-xs sm:text-sm max-w-xl mx-auto mb-6">
          Always interested in connecting with engineers, researchers, and builders working on AI, machine learning, LLM infrastructure, and data systems.
        </p>

        <!-- Social Buttons in Footer -->
        <div class="flex flex-wrap items-center justify-center gap-3 mb-8">
          <a href="https://github.com/mihirsharma1824" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
          </a>
          <a href="https://linkedin.com/in/mihirsharma24" target="_blank" rel="noopener noreferrer">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
          </a>
          <a href="mailto:mihirsharma1824@gmail.com">
            <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
          </a>
        </div>

        <!-- Subtle Animated Wave Footer -->
        <div class="w-full overflow-hidden rounded-b-xl">
          <img 
            src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=100&section=footer" 
            alt="Footer Wave Animation" 
            class="w-full h-auto object-cover"
          />
        </div>
      </section>

    </div>
  </main>

  <!-- RAW MARKDOWN CODE TAB (Hidden by Default) -->
  <main id="tab-markdown-content" class="w-full max-w-5xl bg-ghCard border border-ghBorder rounded-2xl shadow-2xl p-4 sm:p-6 hidden">
    <div class="flex items-center justify-between mb-4 pb-3 border-b border-ghBorder">
      <span class="text-xs font-mono text-electricBlue">README.md (Ready to copy into your GitHub profile repo)</span>
      <button onclick="copyToClipboard()" class="px-3 py-1.5 rounded bg-violetAccent text-white text-xs font-medium hover:bg-violet-600 transition-colors">
        Copy Source Code
      </button>
    </div>
    <pre class="bg-ghBg p-4 rounded-xl border border-ghBorder overflow-x-auto text-xs font-mono text-ghText leading-relaxed selection:bg-violetAccent select-all"><code id="markdown-code"><!-- ==========================================
  MIHIR SHARMA — GITHUB PROFILE README
========================================== -->

<div align="center">
  <!-- Hero Animated Capsule Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=220&section=header&text=MIHIR%20SHARMA&fontSize=46&fontColor=ffffff&animation=fadeIn" width="100%" alt="Mihir Sharma Header Banner" />

  <br />

  <!-- Animated Typing Subtitle -->
  <a href="https://github.com/mihirsharma1824">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=AI+%26+Data+Engineer;Building+Intelligent+Systems;Exploring+LLM+Infrastructure;Engineering+Efficient+AI+Systems" alt="Typing Header" />
  </a>

  <p><em>"Engineering intelligent systems. Exploring what's possible."</em></p>

  <!-- Social Badges -->
  <a href="https://github.com/mihirsharma1824">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/mihirsharma24">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mihirsharma1824@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br />

---

### 💡 Beyond the Code

## **I build systems, not just applications.**

I'm fascinated by what happens behind intelligent systems — from the way LLMs process information to how data moves through scalable infrastructure. I enjoy exploring ideas at the intersection of AI, systems engineering, and performance optimization, turning technical concepts into practical engineering solutions.

<br />

<table>
  <tr>
    <td width="33%" valign="top">
      <h4>01. AI & Machine Learning</h4>
      <sub>Python • PyTorch • Machine Learning</sub>
    </td>
    <td width="33%" valign="top">
      <h4>02. LLM Infrastructure</h4>
      <sub>LLMs • Inference Optimization • Prefix Caching</sub>
    </td>
    <td width="33%" valign="top">
      <h4>03. Retrieval Systems</h4>
      <sub>RAG • Cache-aware Routing</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>04. Backend Engineering</h4>
      <sub>Python • FastAPI • API Development</sub>
    </td>
    <td width="50%" colspan="2" valign="top">
      <h4>05. Data Engineering</h4>
      <sub>MySQL • Data Processing • Database Systems</sub>
    </td>
  </tr>
</table>

<br />

> 🧪 **CURRENTLY IN THE LAB:** **CacheRag**

<br />

---

### ⚡ Featured Project: CacheRag

## **CacheRag**
#### *Cache-Aware Routing and Prefix Caching for Efficient LLM Inference*

> *"Making LLM serving smarter through caching and intelligent request routing."*

LLM inference can repeatedly process shared prompt prefixes, creating opportunities for redundant computation. **CacheRag** explores how cache-aware request routing and prefix caching can make inference systems more efficient.

<br />

<table>
  <tr>
    <td width="33%" align="center">
      <h3>PREFIX CACHING</h3>
      <p>Explore reuse of previously computed shared prompt prefixes.</p>
    </td>
    <td width="33%" align="center">
      <h3>CACHE-AWARE ROUTING</h3>
      <p>Explore routing decisions that account for cache locality.</p>
    </td>
    <td width="33%" align="center">
      <h3>INFERENCE EFFICIENCY</h3>
      <p>Investigate ways to reduce redundant computation and improve serving efficiency.</p>
    </td>
  </tr>
</table>

<br />

#### 🛠️ Conceptual System Architecture Workflow

```
Incoming Requests ──► Request Analysis ──► Cache-Aware Routing ──► Prefix Cache / Inference ──► LLM Response
```

<br />

#### 🎯 Project Vision
Build a more intelligent inference-serving workflow where cache awareness becomes part of request routing, helping explore better resource utilization and reduced redundant computation.

<br />

<div align="left">
  <a href="https://github.com/mihirsharma1824/CacheRag">
    <img src="https://img.shields.io/badge/Explore_CacheRag_Repository-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="CacheRag Repository" />
  </a>
</div>

<br />

---

### 🛠️ Tech Stack

<div align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,pytorch,fastapi,mysql,html,css,git,docker&perline=5" alt="Tech Stack" />
</div>

* **Programming:** C, C++, Python
* **AI / ML:** PyTorch
* **Backend:** FastAPI
* **Database:** MySQL
* **Web:** HTML, CSS
* **Development Tools:** Git, Docker

<br />

---

### 📦 Other Projects

<div align="center">
  <a href="https://github.com/Samudra-Setu">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mihirsharma1824&repo=Samudra-Setu&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D" alt="Samudra-Setu" />
  </a>
</div>

<br />

---

### 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mihirsharma1824&show_icons=true&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D&hide_border=false" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mihirsharma1824&layout=compact&theme=dark&bg_color=161B22&title_color=58A6FF&text_color=C9D1D9&icon_color=7C3AED&border_color=30363D&hide_border=false" width="48%" alt="Top Languages" />
</div>

<br />

<div align="center">
  <img src="https://streak-stats.demolab.com?user=mihirsharma1824&theme=dark&background=161B22&border=30363D&stroke=7C3AED&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9&sideNums=C9D1D9&sideTitle=8B949E&dates=8B949E" width="48%" alt="Streak Stats" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mihirsharma1824&theme=github-compact&bg_color=161B22&color=58A6FF&line=7C3AED&point=FFFFFF&area=true&hide_border=false&border_color=30363D" width="48%" alt="Activity Graph" />
</div>

<br />

---

<div align="center">
  <h2>Let's build something meaningful.</h2>
  <p>Always interested in connecting with engineers, researchers, and builders working on AI, machine learning, LLM infrastructure, and data systems.</p>

  <br />

  <a href="https://github.com/mihirsharma1824">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/mihirsharma24">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mihirsharma1824@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

  <br /><br />

  <img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=100&section=footer" width="100%" alt="Footer Wave" />
</div>
</code></pre>
  </main>

  <script>
    function switchTab(tab) {
      const previewBtn = document.getElementById('btn-preview');
      const markdownBtn = document.getElementById('btn-markdown');
      const previewContent = document.getElementById('tab-preview-content');
      const markdownContent = document.getElementById('tab-markdown-content');

      if (tab === 'preview') {
        previewBtn.classList.add('bg-violetAccent', 'text-white');
        previewBtn.classList.remove('text-ghMuted');
        markdownBtn.classList.remove('bg-violetAccent', 'text-white');
        markdownBtn.classList.add('text-ghMuted');

        previewContent.classList.remove('hidden');
        markdownContent.classList.add('hidden');
      } else {
        markdownBtn.classList.add('bg-violetAccent', 'text-white');
        markdownBtn.classList.remove('text-ghMuted');
        previewBtn.classList.remove('bg-violetAccent', 'text-white');
        previewBtn.classList.add('text-ghMuted');

        markdownContent.classList.remove('hidden');
        previewContent.classList.add('hidden');
      }
    }

    function copyToClipboard() {
      const codeText = document.getElementById('markdown-code').innerText;
      
      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText(codeText).then(() => {
          alert('README.md source code copied to clipboard!');
        }).catch(() => {
          fallbackCopy(codeText);
        });
      } else {
        fallbackCopy(codeText);
      }
    }

    function fallbackCopy(text) {
      const textarea = document.createElement('textarea');
      textarea.value = text;
      document.body.appendChild(textarea);
      textarea.select();
      document.execCommand('copy');
      document.body.removeChild(textarea);
      alert('README.md source code copied to clipboard!');
    }
  </script>
</body>
</html>
