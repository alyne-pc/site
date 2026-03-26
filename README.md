<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Alyne Carvalho - Psicanálise</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
      }
      .glass-nav {
        backdrop-filter: blur(12px);
        -webkit-backdrop-filter: blur(12px);
      }
      .reflection-mirror {
        background: rgba(32, 73, 53, 0.05);
        backdrop-filter: blur(8px);
        border-left: 3px solid #1a4a2e;
      }
      .asymmetric-grid {
        display: grid;
        grid-template-columns: repeat(12, 1fr);
      }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-fixed selection:text-on-primary-fixed">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 dark:bg-[#1a1c19]/80 backdrop-blur-md transition-colors duration-300 shadow-[0_32px_64px_rgba(0,51,26,0.04)]">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="font-serif text-xl italic text-[#1a4a2e] dark:text-[#f4f4ef]">Alyne Carvalho - Psicanálise</div>
<div class="hidden md:flex items-center gap-12">
<a class="text-[#1a4a2e] dark:text-[#87b995] font-semibold border-b-2 border-[#1a4a2e] pb-1 font-sans tracking-wide text-sm" href="#">Home</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] hover:opacity-80 transition-opacity duration-300 font-sans tracking-wide text-sm" href="#">Sobre</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] hover:opacity-80 transition-opacity duration-300 font-sans tracking-wide text-sm" href="#">Artigos</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] hover:opacity-80 transition-opacity duration-300 font-sans tracking-wide text-sm" href="#">Mídia</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] hover:opacity-80 transition-opacity duration-300 font-sans tracking-wide text-sm" href="#">Contato</a>
</div>
<button class="flex items-center gap-2 bg-primary-container text-on-primary-container px-6 py-2.5 rounded-xl font-medium hover:opacity-90 transition-all active:scale-95">
<span class="material-symbols-outlined text-[20px]" data-icon="schedule">schedule</span>
                Agendar Consulta
            </button>
</div>
</nav>
<main>
<!-- Hero Section -->
<section class="relative h-[1024px] w-full flex items-center overflow-hidden">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover scale-110" data-alt="Abstract geometric background with overlapping sharp architectural lines and structured patterns in deep forest green and moody shadows, creating a sophisticated and psychological atmosphere" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHWUD0Hg1kHhigUIlfM2UVzLchYB18uqHVKT2qqowH3PG0vw5MBGsj5vUOcHzhUV342RBh6iKDX__Vu1rkD3Is4LiUWLhu5qJPC7NJITASCMM7datNZ659okAPFZHBHMO39co3B4dCKNqD-XGsHHQEfAuhGsu5PM4orbUSDeOVQIy5V2ZLMVHwXFh0c2VGMAmwE8p0ixXnF2hhQk7VgGbLJ0FoE647uV59sjF3WNZ585nBkb7JIhrQ6mQkj6uuwDbbkCCCNCjVojg"/>
<div class="absolute inset-0 bg-gradient-to-r from-primary/80 via-primary/40 to-transparent"></div>
</div>
<div class="relative z-10 max-w-7xl mx-auto px-8 w-full">
<div class="max-w-2xl">
<h1 class="font-headline text-5xl md:text-7xl font-bold text-white leading-tight mb-6">
                        Explore o inconsciente com Alyne Carvalho
                    </h1>
<p class="text-white/90 text-xl font-light mb-10 leading-relaxed italic">
                        Psicanálise: jornada reflexiva para autoconhecimento autêntico
                    </p>
<div class="flex flex-col gap-6">
<button class="w-fit bg-[#A8D5BA] text-[#00210f] px-10 py-4 rounded-xl font-bold text-lg hover:brightness-105 transition-all shadow-xl active:scale-95">
                            Inicie sua jornada
                        </button>
<p class="text-white/60 text-xs uppercase tracking-widest font-medium">
                            Confidencialidade absoluta | Processo profundo, não soluções rápidas
                        </p>
</div>
</div>
</div>
</section>
<!-- Sobre Section -->
<section class="py-32 bg-surface">
<div class="max-w-7xl mx-auto px-8">
<div class="grid grid-cols-1 md:grid-cols-12 gap-16 items-center">
<div class="md:col-span-5 relative">
<div class="aspect-[4/5] rounded-xl overflow-hidden shadow-2xl">
<img class="w-full h-full object-cover" data-alt="Professional portrait of a 35-year-old female psychoanalyst, Alyne Carvalho. She has long, wavy dark brown hair, fair skin, and expressive, serene hazel eyes with a subtle, empathetic smile." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqLdkYJ1er22X_TfYIpVLur_I5wSPCBidZ1uJFQn5ABqdWqMC4_ZaCFeZknUqZcPBRyOM_tqKLr5SK_fve6CP62mhOE5FDs9JsUz5n5Lg8XDiecItHTpeF8ZGFceQmIs0m3gQzYnRv1X8VYX57JjHASi7FlQ_2EYn3GMbCQCzs3URXjVj8Q16JSdSLudimM_dA1KFh8tp_JZRUB-ke-3Csmmq68rQr8D0upZfk6TnGMVj5VT4dkba6Pf5ng92_3MAnx7rOQPgFC54"/>
</div>
<div class="absolute -bottom-8 -right-8 bg-primary-container p-8 rounded-xl text-on-primary-container hidden lg:block">
<p class="font-headline italic text-xl">"A fala é o caminho para o self."</p>
</div>
</div>
<div class="md:col-span-7 pl-0 md:pl-12">
<h2 class="font-headline text-4xl text-primary mb-8">O Encontro Analítico</h2>
<div class="space-y-6 text-on-surface-variant leading-relaxed text-lg">
<p>Sou psicanalista com foco em sonhos, relações e a construção do self. Entendo a clínica como um santuário de fala livre, onde o silêncio e a palavra se alternam para revelar o que está submerso.</p>
<p>Com RNTP ativo, pauto minha prática na ética rigorosa e na aliança terapêutica como base fundamental para qualquer transformação genuína.</p>
</div>
<!-- Testimonials Carousel (Simplified layout) -->
<div class="mt-16 bg-surface-container-low p-10 rounded-xl relative overflow-hidden">
<span class="material-symbols-outlined text-6xl text-primary/10 absolute -top-2 -left-2" data-icon="format_quote">format_quote</span>
<div class="relative z-10">
<p class="font-headline italic text-xl text-primary leading-relaxed">
                                    "O processo com a Alyne me permitiu enxergar padrões que eu repetia há décadas sem perceber. Uma escuta que acolhe e provoca ao mesmo tempo."
                                </p>
<p class="mt-4 text-sm font-label uppercase tracking-widest text-primary/60">— M. R., 34 anos</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Serviços Section -->
<section class="py-32 bg-surface-container-low">
<div class="max-w-7xl mx-auto px-8">
<div class="text-center mb-20">
<h2 class="font-headline text-4xl text-primary mb-4">Áreas de Escuta</h2>
<div class="h-1 w-20 bg-primary-container mx-auto mb-8"></div>
<p class="max-w-2xl mx-auto text-on-surface-variant italic">
                        Psicanálise não é terapia comportamental: mergulha no simbólico para mudanças duradouras.
                    </p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Card 1 -->
<div class="bg-surface p-10 rounded-xl hover:bg-surface-container-highest transition-colors group cursor-default">
<span class="material-symbols-outlined text-4xl text-primary mb-6 block" data-icon="flare">flare</span>
<h3 class="font-headline text-2xl text-primary mb-4">Sonhos e Inconsciente</h3>
<p class="text-on-surface-variant leading-relaxed">Exploração da linguagem onírica como porta de entrada para desejos e conflitos não formulados.</p>
</div>
<!-- Card 2 -->
<div class="bg-surface p-10 rounded-xl hover:bg-surface-container-highest transition-colors group cursor-default">
<span class="material-symbols-outlined text-4xl text-primary mb-6 block" data-icon="all_inclusive">all_inclusive</span>
<h3 class="font-headline text-2xl text-primary mb-4">Relações Afetivas</h3>
<p class="text-on-surface-variant leading-relaxed">Análise dos vínculos e repetições que moldam nossa forma de amar e ser amado no mundo.</p>
</div>
<!-- Card 3 -->
<div class="bg-surface p-10 rounded-xl hover:bg-surface-container-highest transition-colors group cursor-default">
<span class="material-symbols-outlined text-4xl text-primary mb-6 block" data-icon="architecture">architecture</span>
<h3 class="font-headline text-2xl text-primary mb-4">Autoconhecimento</h3>
<p class="text-on-surface-variant leading-relaxed">O fortalecimento do eu através da compreensão profunda da própria história e subjetividade.</p>
</div>
</div>
</div>
</section>
<!-- Processo Section (Timeline) -->
<section class="py-32 bg-surface">
<div class="max-w-5xl mx-auto px-8">
<h2 class="font-headline text-4xl text-primary text-center mb-24">O Caminho Analítico</h2>
<div class="relative">
<!-- Vertical Line -->
<div class="absolute left-1/2 top-0 bottom-0 w-[1px] bg-primary/20 -translate-x-1/2 hidden md:block"></div>
<div class="space-y-24">
<!-- Step 1 -->
<div class="relative flex flex-col md:flex-row items-center gap-8 group">
<div class="md:w-1/2 md:text-right">
<h4 class="font-headline text-xl text-primary mb-2">Entrevistas Preliminares</h4>
<p class="text-on-surface-variant">Momentos iniciais para entender a demanda e estabelecer a viabilidade da análise.</p>
</div>
<div class="z-10 w-4 h-4 rounded-full bg-primary ring-8 ring-primary/10"></div>
<div class="md:w-1/2"></div>
</div>
<!-- Step 2 -->
<div class="relative flex flex-col md:flex-row-reverse items-center gap-8 group">
<div class="md:w-1/2 md:text-left">
<h4 class="font-headline text-xl text-primary mb-2">Associação Livre</h4>
<p class="text-on-surface-variant">A técnica fundamental: falar sem censura, permitindo que o inconsciente se manifeste.</p>
</div>
<div class="z-10 w-4 h-4 rounded-full bg-primary ring-8 ring-primary/10"></div>
<div class="md:w-1/2"></div>
</div>
<!-- Step 3 -->
<div class="relative flex flex-col md:flex-row items-center gap-8 group">
<div class="md:w-1/2 md:text-right">
<h4 class="font-headline text-xl text-primary mb-2">Interpretação e Manejo</h4>
<p class="text-on-surface-variant">O analista pontua e intervém para que o analisando alcance novos sentidos para sua dor.</p>
</div>
<div class="z-10 w-4 h-4 rounded-full bg-primary ring-8 ring-primary/10"></div>
<div class="md:w-1/2"></div>
</div>
<!-- Step 4 -->
<div class="relative flex flex-col md:flex-row-reverse items-center gap-8 group">
<div class="md:w-1/2 md:text-left">
<h4 class="font-headline text-xl text-primary mb-2">Elaboração</h4>
<p class="text-on-surface-variant">O trabalho contínuo de integrar as descobertas à vida cotidiana e ao novo self.</p>
</div>
<div class="z-10 w-4 h-4 rounded-full bg-primary ring-8 ring-primary/10"></div>
<div class="md:w-1/2"></div>
</div>
</div>
</div>
</div>
</section>
<!-- Artigos Carousel (Bento-ish Grid) -->
<section class="py-32 bg-surface-container-low overflow-hidden">
<div class="max-w-7xl mx-auto px-8">
<div class="flex justify-between items-end mb-16">
<div>
<h2 class="font-headline text-4xl text-primary mb-4">Fragmentos de Reflexão</h2>
<p class="text-on-surface-variant uppercase tracking-widest text-xs">Escritos sobre a mente e a cultura</p>
</div>
<a class="text-primary font-medium hover:underline flex items-center gap-2" href="#">
                        Ver todos <span class="material-symbols-outlined text-sm" data-icon="arrow_forward">arrow_forward</span>
</a>
</div>
<div class="grid grid-cols-1 md:grid-cols-4 gap-6">
<!-- Artigo 1 -->
<div class="bg-surface rounded-xl overflow-hidden group cursor-pointer shadow-sm hover:shadow-xl transition-all">
<div class="h-48 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="ethereal abstract image of rippling water with soft light reflections, representing the fluid nature of the unconscious" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCJZG_3FfsCy12Gggp8wmmSgpuOrB0fvZg9UYPQ3hciAVCf4-4Uxi7UfDwMbZ5j1zpJIOfDJR-0ghPl3ZkSCj0CtQ3H0yMR1b2T7LWTXxRHzAps6Bh6SruAHfbGujySOfAk_5AuPd1-w3codpvfkUYeeQbu8LdoSYiaUvgaNgfHA48_-C0IlXhRgdMkAxQkVsKH_mzJrsbTNI2x7Im-32Sy3R4ENxhGcOgtZzmslJjDT6s8gnI_Skjt6BWseKtSvV16Yl3NVGYKnVw"/>
</div>
<div class="p-6">
<h4 class="font-headline text-lg text-primary mb-2">O Enigma dos Sonhos</h4>
<p class="text-sm text-on-surface-variant line-clamp-2">Por que o cérebro cria narrativas tão complexas enquanto dormimos?</p>
</div>
</div>
<!-- Artigo 2 -->
<div class="bg-surface rounded-xl overflow-hidden group cursor-pointer shadow-sm hover:shadow-xl transition-all">
<div class="h-48 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="minimalist composition of a single withered leaf on a marble surface, representing loss and the mourning process" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBNaO4l-gmIW4_soVEsNWYiikbg55zl6UyDbyi36K3VGCRRII8lrVffB0KGdPnPAg54DEN5ZNUReFVwhl56lZVX_Fff3Rys5ueH5To-hRXzQ9-vrUTp4PHM_T1k-bVA9mwKVu0Kof2QoEEqB7uXMdNAieGK2AEJzGAEtDdIxHG_vhQHMZQlEY0QWHQCwLBeLnPDRff_LMQ2uI9BKV2vdvDBM3KZeuGtAboXVpmzqt4oL-qirPCpHsSYUIcSjRxfY10rV2GTAk_NtVo"/>
</div>
<div class="p-6">
<h4 class="font-headline text-lg text-primary mb-2">Sobre o Luto e a Perda</h4>
<p class="text-sm text-on-surface-variant line-clamp-2">Como a psicanálise ajuda a processar o que não pode ser substituído.</p>
</div>
</div>
<!-- Artigo 3 -->
<div class="bg-surface rounded-xl overflow-hidden group cursor-pointer shadow-sm hover:shadow-xl transition-all">
<div class="h-48 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="abstract close-up of tangled threads in various shades of green and cream, symbolizing complex human relationships" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA_Prc5VXEDFZn1Y1XnEfFI2LYMkcF6G30UwfaSSlKqhUs-o5kuFJIfkFSSwzMdk-nmMB9pAdnpI8wyPAp2-i37po8WU2ArJX0L7Gsfzee2tmoepVRsk9ua4hI6IYCcbc-bUA125bKJKuolK9Xx8vYlBVGBMfhAlV-2eCAWxpeGdYaLXyG-wJyg2RdWE8KMslAKvt_Td_tdTBaQiVD2kiv4jneOqDl0AbTlYYuoq-KXFIJsZCK77jkh2S0H-45VhDY7YJGiOE-H9dc"/>
</div>
<div class="p-6">
<h4 class="font-headline text-lg text-primary mb-2">Vínculos Modernos</h4>
<p class="text-sm text-on-surface-variant line-clamp-2">A liquidez dos relacionamentos na era digital e o sofrimento narcísico.</p>
</div>
</div>
<!-- Artigo 4 -->
<div class="bg-surface rounded-xl overflow-hidden group cursor-pointer shadow-sm hover:shadow-xl transition-all">
<div class="h-48 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="soft blurred image of a staircase spiraling upwards into a misty light, representing the journey of self-discovery" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDjQWwXloOf85J7he49RBh-6_-JGcomwVWnce46B1m0JCnazGRK6zey58uXc076irRrDaU2k6lEy86hJE2QIyknjVf-aujy6jm6jf6JrhQ2GmeQy45nYeyjKX_ZuuqZzA8u9nhjgSpoYegjTWeEFFJRlKZj5BoSljjbkd4miUHHxN8SrtscdYCkWnEwnIzJxMzrxbgpQaRIpd-vXmzZgV5BHydQFTRHG5wNwLwVRjrznM1T-J1ptC55qJ4t-ChcT0r3sL7Rl-rqoIo"/>
</div>
<div class="p-6">
<h4 class="font-headline text-lg text-primary mb-2">A Coragem de Ser</h4>
<p class="text-sm text-on-surface-variant line-clamp-2">O encontro com a verdade subjetiva como ato de resistência.</p>
</div>
</div>
</div>
</div>
</section>
<!-- FAQ Section (Accordion) -->
<section class="py-32 bg-surface">
<div class="max-w-3xl mx-auto px-8">
<h2 class="font-headline text-4xl text-primary text-center mb-16">Perguntas sobre o Processo</h2>
<div class="space-y-4">
<div class="border-b border-outline-variant/30 pb-4">
<button class="w-full flex justify-between items-center text-left py-4 focus:outline-none group">
<span class="font-headline text-xl text-primary">Quanto tempo dura uma análise?</span>
<span class="material-symbols-outlined text-primary group-hover:rotate-45 transition-transform" data-icon="add">add</span>
</button>
<div class="max-h-0 overflow-hidden transition-all duration-300">
<p class="text-on-surface-variant pb-4 leading-relaxed">Não há um tempo pré-determinado. A psicanálise respeita o tempo lógico do sujeito, que é diferente do tempo cronológico do relógio. É um processo de maturação.</p>
</div>
</div>
<div class="border-b border-outline-variant/30 pb-4">
<button class="w-full flex justify-between items-center text-left py-4 focus:outline-none group">
<span class="font-headline text-xl text-primary">Qual a diferença entre psicanálise e psicologia?</span>
<span class="material-symbols-outlined text-primary group-hover:rotate-45 transition-transform" data-icon="add">add</span>
</button>
<div class="max-h-0 overflow-hidden transition-all duration-300">
<p class="text-on-surface-variant pb-4 leading-relaxed">Enquanto muitas psicologias focam no comportamento e na consciência, a psicanálise trabalha com o inconsciente, buscando a causa raiz e o sentido simbólico do sintoma.</p>
</div>
</div>
<div class="border-b border-outline-variant/30 pb-4">
<button class="w-full flex justify-between items-center text-left py-4 focus:outline-none group">
<span class="font-headline text-xl text-primary">As sessões podem ser online?</span>
<span class="material-symbols-outlined text-primary group-hover:rotate-45 transition-transform" data-icon="add">add</span>
</button>
<div class="max-h-0 overflow-hidden transition-all duration-300">
<p class="text-on-surface-variant pb-4 leading-relaxed">Sim, o atendimento online é possível e mantém a mesma eficácia ética e técnica, permitindo o encontro analítico independente da distância geográfica.</p>
</div>
</div>
</div>
</div>
</section>
<!-- CTA Final -->
<section class="py-32 bg-primary relative overflow-hidden">
<div class="absolute inset-0 opacity-10">
<img class="w-full h-full object-cover" data-alt="subtle organic texture resembling handmade paper or soft fabric in dark green tones" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAz8XwfcJ43xq3gJNfJaz5vn7IUZll9eqlz-jSbo897KU0qYXyOLC99wn0djczjO6VN_LP0Qky0ZyW_cNBa80G_XbGfqRQKbJh9Iz666PHDRgDOn3JvfEuWyjof1nYNM5VEZmoDLn_I16jrXZ_2x9__fgRuIC7K3bN19PcFS8kQOBgb11VKQ0SmDOiQZOFMa3DvHum4ctDbaP6LJtOiqg77lbTyM_Il86E3ssxyvcn1IJ9zP0tIotouv_4x5s_mVr72jO2Ipll9KiQ"/>
</div>
<div class="relative z-10 max-w-4xl mx-auto text-center px-8">
<h2 class="font-headline text-4xl md:text-5xl text-white mb-8">Dê o primeiro passo em direção a si mesmo</h2>
<p class="text-primary-fixed-dim text-xl mb-12 font-light italic">Agende uma conversa inicial e inicie sua jornada pelo inconsciente.</p>
<button class="bg-primary-fixed text-on-primary-fixed px-12 py-5 rounded-xl font-bold text-xl hover:brightness-105 transition-all shadow-2xl">
                    Agendar minha sessão
                </button>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef] dark:bg-[#1a1c19] transition-colors duration-300">
<div class="flex flex-col items-center gap-8 py-20 px-4 w-full text-center">
<div class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho - Psicanálise</div>
<div class="flex gap-8">
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300 font-sans text-xs uppercase tracking-[0.05rem]" href="#">Instagram</a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300 font-sans text-xs uppercase tracking-[0.05rem]" href="#">WhatsApp</a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300 font-sans text-xs uppercase tracking-[0.05rem]" href="#">Spotify</a>
</div>
<div class="max-w-2xl text-[#1a1c19]/60 font-sans text-xs uppercase tracking-[0.05rem] leading-loose">
                RNTP 4452-91 | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
            </div>
<div class="pt-8 text-[10px] text-[#1a1c19]/30 uppercase tracking-[0.2rem]">
                © 2024 Alyne Carvalho. Todos os direitos reservados.
            </div>
</div>
</footer>
</body></html>

<!-- Home - Desktop (Final Color) -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .glass-nav {
        backdrop-filter: blur(20px);
        -webkit-backdrop-filter: blur(20px);
      }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-fixed selection:text-on-primary-fixed">
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 backdrop-blur-md shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-colors duration-300">
<div class="flex justify-between items-center px-6 py-5">
<span class="font-serif text-xl italic text-[#1a4a2e]">Alyne Carvalho</span>
<button class="text-primary p-2">
<span class="material-symbols-outlined">menu</span>
</button>
</div>
</nav>
<main class="pt-20">
<section class="relative px-6 py-12 flex flex-col gap-8">
<div class="space-y-4">
<h1 class="font-headline text-4xl leading-tight text-primary">A escuta que transforma o <span class="italic">sentir</span>.</h1>
<p class="text-on-surface-variant leading-relaxed text-lg">Um espaço seguro para a exploração do inconsciente e o acolhimento da sua história singular.</p>
<div class="pt-4">
<button class="w-full py-4 bg-on-primary-container text-on-primary-fixed font-semibold rounded-xl shadow-lg flex items-center justify-center gap-2 hover:opacity-90 active:scale-95 transition-all">
                        Agendar Consulta
                        <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
</div>
<div class="relative w-full aspect-[4/5] rounded-xl overflow-hidden shadow-2xl bg-primary">
<img alt="Geometric abstract background" class="w-full h-full object-cover" data-alt="Geometric abstract pattern with clean lines and deep green tones, minimal design representing psychological structure" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDaWz7kzJ4_uhvmHh69dqRXqDyC4YvC_DQIdsfPO4tagy_bl5n3yuRi6glgkF9PDavw0RFqPNE66nIaJTCqp5DtDSpWMAsUEXl4D3K04V1MrzLfL9o1l_Qx4QTxhQrNHGKS_42VkDRQAtYoTqARffZdJEA4sH37V3eJ5LD2S6X_ncu4XjT1-c2dEmcpB8885-i3F8XJtpPT9513jmvqdGikstjibWULp8VlmSn43CVneZ1OAmOTfZ_B7VGk4yUq_qDDzy_XJ5cdybA"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/40 to-transparent"></div>
</div>
</section>
<section class="bg-surface-container-low py-20 px-6">
<div class="flex flex-col gap-8">
<div class="space-y-6">
<span class="font-label text-xs uppercase tracking-[0.2em] text-secondary">Sobre a Profissional</span>
<h2 class="font-headline text-3xl text-primary">Alyne Carvalho</h2>
<div class="relative w-full aspect-square rounded-xl overflow-hidden">
<img alt="Alyne Carvalho - Psychoanalyst" class="w-full h-full object-cover" data-alt="Professional portrait of Alyne Carvalho, a psychoanalyst with long wavy dark brown hair and a serene expression in a minimalist clinical setting." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqLdkYJ1er22X_TfYIpVLur_I5wSPCBidZ1uJFQn5ABqdWqMC4_ZaCFeZknUqZcPBRyOM_tqKLr5SK_fve6CP62mhOE5FDs9JsUz5n5Lg8XDiecItHTpeF8ZGFceQmIs0m3gQzYnRv1X8VYX57JjHASi7FlQ_2EYn3GMbCQCzs3URXjVj8Q16JSdSLudimM_dA1KFh8tp_JZRUB-ke-3Csmmq68rQr8D0upZfk6TnGMVj5VT4dkba6Pf5ng92_3MAnx7rOQPgFC54"/>
</div>
<p class="text-on-surface-variant leading-loose">Psicanalista dedicada à compreensão dos processos subjetivos. Minha prática é pautada na ética do desejo e no respeito ao tempo de cada analisando, proporcionando um ambiente de silêncio e reflexão necessários para a cura.</p>
<button class="text-primary font-semibold flex items-center gap-2 group">
                        Conheça minha trajetória
                        <span class="material-symbols-outlined group-hover:translate-x-1 transition-transform">trending_flat</span>
</button>
</div>
</div>
</section>
<section class="py-20 px-6 flex flex-col gap-12">
<div class="text-center space-y-2">
<h2 class="font-headline text-3xl text-primary">Especialidades</h2>
<div class="h-1 w-12 bg-primary-fixed-dim mx-auto"></div>
</div>
<div class="grid grid-cols-1 gap-6">
<div class="bg-surface-container p-8 rounded-xl flex flex-col gap-4 border-b-4 border-secondary/20">
<span class="material-symbols-outlined text-secondary text-3xl">psychology</span>
<h3 class="font-headline text-xl text-primary">Psicanálise Clínica</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">Atendimento individual focado na investigação do inconsciente e na resolução de conflitos internos profundos.</p>
</div>
<div class="bg-surface-container-highest p-8 rounded-xl flex flex-col gap-4 border-b-4 border-secondary/20">
<span class="material-symbols-outlined text-secondary text-3xl">filter_vintage</span>
<h3 class="font-headline text-xl text-primary">Ansiedade e Estresse</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">Apoio especializado para lidar com as pressões da vida contemporânea e encontrar equilíbrio emocional.</p>
</div>
<div class="bg-surface-container p-8 rounded-xl flex flex-col gap-4 border-b-4 border-secondary/20">
<span class="material-symbols-outlined text-secondary text-3xl">family_restroom</span>
<h3 class="font-headline text-xl text-primary">Conflitos Familiares</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">Mediação e análise das dinâmicas relacionais para promover vínculos mais saudáveis e autênticos.</p>
</div>
</div>
</section>
<section class="bg-tertiary-container py-20 px-8 text-center relative overflow-hidden">
<div class="absolute top-0 left-0 w-full h-full bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-primary/10 via-transparent to-transparent"></div>
<div class="relative z-10 flex flex-col gap-6">
<span class="material-symbols-outlined text-on-tertiary-container text-4xl opacity-50">format_quote</span>
<p class="font-headline text-2xl italic text-on-tertiary-container leading-relaxed">
                    "A psicanálise é, em essência, uma cura pelo amor."
                </p>
<cite class="font-label text-xs uppercase tracking-widest text-on-tertiary-container/70">— Sigmund Freud</cite>
</div>
</section>
<section class="py-20 px-6">
<div class="space-y-10">
<h2 class="font-headline text-3xl text-primary text-center">Relatos de Processos</h2>
<div class="flex flex-col gap-8">
<div class="bg-surface p-8 rounded-xl border-l-2 border-primary-fixed-dim italic text-on-surface-variant shadow-sm">
<p class="mb-4">"Encontrei na Alyne um porto seguro para falar o que nunca consegui dizer em outro lugar. O processo tem sido doloroso, mas profundamente libertador."</p>
<span class="text-xs font-semibold uppercase tracking-tighter text-secondary">— M. Santos</span>
</div>
<div class="bg-surface p-8 rounded-xl border-l-2 border-primary-fixed-dim italic text-on-surface-variant shadow-sm">
<p class="mb-4">"A sensibilidade da escuta dela é algo raro. Me senti acolhida desde a primeira sessão e hoje percebo mudanças reais na minha forma de viver."</p>
<span class="text-xs font-semibold uppercase tracking-tighter text-secondary">— R. Oliveira</span>
</div>
</div>
</div>
</section>
<section class="bg-primary py-20 px-6 text-center text-on-primary">
<div class="max-w-xs mx-auto space-y-8">
<h2 class="font-headline text-3xl">Inicie sua jornada hoje</h2>
<p class="opacity-80">As consultas podem ser realizadas presencialmente ou de forma remota, com total sigilo e ética.</p>
<div class="flex flex-col gap-4">
<button class="w-full py-4 bg-primary-fixed text-on-primary-fixed font-bold rounded-xl active:scale-95 transition-transform">
                        WhatsApp
                    </button>
<button class="w-full py-4 border border-outline-variant/30 text-white font-medium rounded-xl active:scale-95 transition-transform">
                        E-mail para Contato
                    </button>
</div>
</div>
</section>
</main>
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef] py-16 px-6 text-center">
<div class="flex flex-col items-center gap-10">
<div class="space-y-2">
<span class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho</span>
<p class="font-sans text-[10px] uppercase tracking-[0.1rem] text-[#1a1c19]/60 max-w-[280px] leading-relaxed">
                    RNTP 12345 | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
                </p>
</div>
<div class="flex gap-8">
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors" href="#"><span class="material-symbols-outlined">brand_awareness</span></a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors" href="#"><span class="material-symbols-outlined">chat</span></a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors" href="#"><span class="material-symbols-outlined">podcasts</span></a>
</div>
<p class="text-[10px] text-on-surface-variant/40 mt-4">© 2024 Alyne Carvalho. Todos os direitos reservados.</p>
</div>
</footer>
<div class="fixed bottom-6 right-6 z-40">
<button class="h-14 w-14 bg-secondary text-white rounded-full shadow-2xl flex items-center justify-center active:scale-90 transition-transform">
<span class="material-symbols-outlined" data-weight="fill">schedule</span>
</button>
</div>
</body></html>

<!-- Home - Mobile (Final Color) -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Inter:wght@300;400;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-nav {
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }
        .asymmetric-indent {
            margin-left: clamp(0rem, 10vw, 8rem);
        }
    </style>
</head>
<body class="bg-background text-on-surface font-body selection:bg-primary-fixed selection:text-on-primary-fixed">
<!-- Top Navigation Bar -->
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 backdrop-blur-md shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-colors duration-300">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="font-serif text-xl italic text-[#1a4a2e]">Alyne Carvalho - Psicanálise</div>
<div class="hidden md:flex items-center gap-10">
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Home</a>
<a class="text-[#1a4a2e] font-semibold border-b-2 border-[#1a4a2e] pb-1 font-sans tracking-wide text-sm" href="#">Sobre</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Artigos</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Mídia</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Contato</a>
</div>
<div class="flex items-center gap-4">
<button class="bg-primary-container text-on-primary-container px-6 py-2.5 rounded-xl font-sans text-sm font-semibold hover:opacity-80 transition-all ease-in-out duration-300 transform active:scale-95 flex items-center gap-2">
<span class="material-symbols-outlined text-lg">schedule</span>
                    Agendar Consulta
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-20">
<!-- Hero Section: Biography -->
<section class="max-w-7xl mx-auto px-8 mb-40">
<div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-start">
<div class="md:col-span-5 relative">
<div class="aspect-[4/5] bg-surface-container rounded-xl overflow-hidden shadow-sm">
<img class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" data-alt="Professional portrait of Alyne Carvalho, a psychoanalyst with long wavy dark brown hair and a serene expression in a minimalist clinical setting." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAqLdkYJ1er22X_TfYIpVLur_I5wSPCBidZ1uJFQn5ABqdWqMC4_ZaCFeZknUqZcPBRyOM_tqKLr5SK_fve6CP62mhOE5FDs9JsUz5n5Lg8XDiecItHTpeF8ZGFceQmIs0m3gQzYnRv1X8VYX57JjHASi7FlQ_2EYn3GMbCQCzs3URXjVj8Q16JSdSLudimM_dA1KFh8tp_JZRUB-ke-3Csmmq68rQr8D0upZfk6TnGMVj5VT4dkba6Pf5ng92_3MAnx7rOQPgFC54"/>
</div>
<div class="absolute -bottom-6 -right-6 p-8 bg-tertiary-container text-on-tertiary-container rounded-xl shadow-lg max-w-[280px]">
<p class="font-headline italic text-lg leading-relaxed">
                            "A análise é o encontro onde o silêncio ganha voz e a escuta se torna cura."
                        </p>
</div>
</div>
<div class="md:col-span-7 pt-12">
<span class="font-label text-xs uppercase tracking-[0.2em] text-secondary mb-4 block">Trajetória e Propósito</span>
<h1 class="font-headline text-5xl md:text-6xl text-primary leading-tight mb-8">
                        Alyne Carvalho
                    </h1>
<div class="space-y-6 text-on-surface-variant leading-relaxed max-w-xl">
<p class="text-lg">
                            Psicanalista com formação sólida e dedicada à exploração das profundezas da psique humana. Minha prática é fundamentada no acolhimento ético e na construção de um espaço de confiança absoluta.
                        </p>
<p>
                            Formada em Psicologia com especialização em Teoria Psicanalítica, minha caminhada acadêmica e clínica é marcada pelo estudo contínuo das obras de Freud e Lacan, transpondo conceitos clássicos para os desafios contemporâneos da subjetividade.
                        </p>
<p>
                            Acredito que o processo terapêutico não é apenas sobre a resolução de sintomas, mas sobre a descoberta de um novo modo de existir e de se relacionar com o próprio desejo.
                        </p>
</div>
</div>
</div>
</section>
<!-- Clinical Approach Section -->
<section class="bg-surface-container-low py-32 mb-40">
<div class="max-w-7xl mx-auto px-8">
<div class="flex flex-col md:flex-row gap-20">
<div class="md:w-1/3">
<h2 class="font-headline text-4xl text-primary sticky top-40">Abordagem Clínica</h2>
</div>
<div class="md:w-2/3 space-y-24">
<!-- Reflection Mirror: Aliança Terapêutica -->
<div class="bg-tertiary-container/10 p-12 rounded-xl relative overflow-hidden group">
<div class="absolute top-0 right-0 w-32 h-32 bg-on-tertiary-container/5 rounded-full -mr-16 -mt-16 transition-transform duration-700 group-hover:scale-150"></div>
<span class="font-label text-xs uppercase tracking-widest text-on-tertiary-container mb-6 block">O Coração do Processo</span>
<h3 class="font-headline text-3xl text-primary mb-6">Aliança terapêutica</h3>
<p class="text-on-surface-variant text-lg leading-relaxed mb-8">
                                O pilar central do meu trabalho é a construção de uma aliança terapêutica sólida. É neste vínculo de transferência e respeito mútuo que o paciente encontra a segurança necessária para desvelar suas angústias e ressignificar sua história.
                            </p>
<div class="flex items-center gap-4 text-primary font-semibold">
<span class="material-symbols-outlined">psychology</span>
<span class="text-sm">Presença ativa e escuta flutuante</span>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div class="space-y-4">
<h4 class="font-headline text-2xl text-secondary">Escuta Ética</h4>
<p class="text-on-surface-variant leading-relaxed">
                                    Uma escuta que não julga, mas que acolhe a singularidade de cada sujeito em sua totalidade.
                                </p>
</div>
<div class="space-y-4">
<h4 class="font-headline text-2xl text-secondary">Tempo do Inconsciente</h4>
<p class="text-on-surface-variant leading-relaxed">
                                    Respeito ao ritmo biográfico, permitindo que as elaborações ocorram no tempo necessário para a transformação real.
                                </p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Training/Bento Grid Section -->
<section class="max-w-7xl mx-auto px-8 mb-40">
<h2 class="font-headline text-4xl text-primary mb-16 text-center">Formação e Especialidades</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="md:col-span-2 bg-surface p-10 rounded-xl shadow-sm border border-outline-variant/15 flex flex-col justify-between group hover:bg-surface-container-highest transition-colors duration-500">
<div>
<span class="material-symbols-outlined text-primary text-4xl mb-6">school</span>
<h3 class="font-headline text-2xl text-primary mb-4">Academia e Pesquisa</h3>
<p class="text-on-surface-variant leading-relaxed max-w-md">Membro de sociedades psicanalíticas renomadas, participo ativamente de grupos de estudo sobre as psicopatologias contemporâneas e a clínica do vazio.</p>
</div>
<div class="mt-12 flex gap-4">
<span class="px-4 py-2 bg-primary-fixed text-on-primary-fixed-variant text-xs font-semibold rounded-full uppercase tracking-tighter">Psicologia Clínica</span>
<span class="px-4 py-2 bg-tertiary-fixed text-on-tertiary-fixed-variant text-xs font-semibold rounded-full uppercase tracking-tighter">Teoria Lacaniana</span>
</div>
</div>
<div class="bg-primary-container p-10 rounded-xl text-on-primary-container flex flex-col justify-center items-center text-center">
<span class="material-symbols-outlined text-5xl mb-6">history_edu</span>
<h3 class="font-headline text-2xl mb-4">Produção Intelectual</h3>
<p class="text-sm opacity-90 leading-relaxed">Autora de artigos sobre a relação entre luto, desejo e a virtualidade nos tempos modernos.</p>
</div>
<div class="bg-surface-container-high p-10 rounded-xl flex flex-col justify-between">
<h3 class="font-headline text-xl text-primary">Atendimento Adulto</h3>
<p class="text-on-surface-variant text-sm">Foco em ansiedade, depressão e questões existenciais da vida adulta.</p>
</div>
<div class="md:col-span-2 bg-[#eeeee9] p-10 rounded-xl flex items-center gap-10">
<div class="hidden sm:block w-32 h-32 rounded-full overflow-hidden shrink-0">
<div class="w-full h-full bg-gradient-to-br from-primary to-secondary opacity-20" data-alt="Abstract soft green gradient representing tranquility and professional growth"></div>
</div>
<div>
<h3 class="font-headline text-xl text-primary mb-2">Clínica Social</h3>
<p class="text-on-surface-variant text-sm">Compromisso com a democratização da psicanálise através de projetos de atendimento acessível.</p>
</div>
</div>
</div>
</section>
<!-- Testimonials Carousel (Static UI Representation) -->
<section class="bg-surface-container-low py-32 overflow-hidden">
<div class="max-w-7xl mx-auto px-8">
<h2 class="font-headline text-4xl text-primary mb-20 text-center italic">Relatos de Travessia</h2>
<div class="flex gap-8 overflow-x-auto pb-12 snap-x no-scrollbar">
<!-- Carousel Item 1 -->
<div class="min-w-[320px] md:min-w-[450px] bg-surface p-12 rounded-xl shadow-[0_32px_64px_rgba(0,51,26,0.02)] snap-center">
<span class="material-symbols-outlined text-primary-fixed-dim text-4xl mb-6">format_quote</span>
<p class="text-on-surface-variant italic leading-relaxed mb-8">
                            "Encontrei na Alyne não apenas uma profissional, mas um porto seguro onde pude finalmente dar nome ao que me doía. A aliança terapêutica que construímos foi transformadora."
                        </p>
<div class="flex items-center gap-4">
<div class="w-10 h-1 bg-primary/20"></div>
<span class="font-label text-xs uppercase tracking-widest text-secondary">M. Silva, 34 anos</span>
</div>
</div>
<!-- Carousel Item 2 -->
<div class="min-w-[320px] md:min-w-[450px] bg-surface p-12 rounded-xl shadow-[0_32px_64px_rgba(0,51,26,0.02)] snap-center">
<span class="material-symbols-outlined text-primary-fixed-dim text-4xl mb-6">format_quote</span>
<p class="text-on-surface-variant italic leading-relaxed mb-8">
                            "A sensibilidade e a precisão da escuta clínica da Alyne me permitiram atravessar momentos de profunda incerteza com mais clareza e autonomia."
                        </p>
<div class="flex items-center gap-4">
<div class="w-10 h-1 bg-primary/20"></div>
<span class="font-label text-xs uppercase tracking-widest text-secondary">R. Oliveira, 42 anos</span>
</div>
</div>
<!-- Carousel Item 3 -->
<div class="min-w-[320px] md:min-w-[450px] bg-surface p-12 rounded-xl shadow-[0_32px_64px_rgba(0,51,26,0.02)] snap-center">
<span class="material-symbols-outlined text-primary-fixed-dim text-4xl mb-6">format_quote</span>
<p class="text-on-surface-variant italic leading-relaxed mb-8">
                            "O processo é paciente e profundo. Me senti respeitado em cada silêncio e impulsionado em cada intervenção. Uma profissional de ética impecável."
                        </p>
<div class="flex items-center gap-4">
<div class="w-10 h-1 bg-primary/20"></div>
<span class="font-label text-xs uppercase tracking-widest text-secondary">A. Costa, 29 anos</span>
</div>
</div>
</div>
<div class="flex justify-center gap-3 mt-8">
<div class="w-2 h-2 rounded-full bg-primary"></div>
<div class="w-2 h-2 rounded-full bg-outline-variant"></div>
<div class="w-2 h-2 rounded-full bg-outline-variant"></div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="py-32 max-w-4xl mx-auto px-8 text-center">
<h2 class="font-headline text-3xl text-primary mb-6 italic">Inicie sua própria jornada</h2>
<p class="text-on-surface-variant mb-12">O primeiro passo é sempre o mais significativo. Estou aqui para caminhar ao seu lado.</p>
<a class="inline-flex items-center gap-3 bg-primary text-on-primary px-10 py-4 rounded-xl font-semibold hover:opacity-90 transition-all duration-300" href="#">
                Agendar entrevista inicial
                <span class="material-symbols-outlined">arrow_forward</span>
</a>
</section>
</main>
<!-- Footer -->
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef]">
<div class="flex flex-col items-center gap-8 py-20 px-4 w-full text-center">
<div class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho - Psicanálise</div>
<div class="flex gap-8">
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] font-sans text-xs uppercase tracking-[0.05rem] transition-colors duration-300" href="#">Instagram</a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] font-sans text-xs uppercase tracking-[0.05rem] transition-colors duration-300" href="#">WhatsApp</a>
<a class="text-[#1a1c19]/50 hover:text-[#1a4a2e] font-sans text-xs uppercase tracking-[0.05rem] transition-colors duration-300" href="#">Spotify</a>
</div>
<p class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/60 max-w-xl leading-relaxed">
                RNTP [number] | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
            </p>
</div>
</footer>
</body></html>

<!-- Sobre Alyne Carvalho (Final Color) -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Artigos | Alyne Carvalho - Psicanálise</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&amp;family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .ethereal-blur {
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-fixed selection:text-on-primary-fixed">
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 dark:bg-[#1a1c19]/80 backdrop-blur-md transition-colors duration-300 shadow-[0_32px_64px_rgba(0,51,26,0.04)]">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="font-serif text-xl italic text-[#1a4a2e] dark:text-[#f4f4ef]">
                Alyne Carvalho - Psicanálise
            </div>
<div class="hidden md:flex items-center gap-10">
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] transition-opacity duration-300 ease-in-out font-sans tracking-wide text-sm" href="#">Home</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] transition-opacity duration-300 ease-in-out font-sans tracking-wide text-sm" href="#">Sobre</a>
<a class="text-[#1a4a2e] dark:text-[#87b995] font-semibold border-b-2 border-[#1a4a2e] pb-1 font-sans tracking-wide text-sm" href="#">Artigos</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] transition-opacity duration-300 ease-in-out font-sans tracking-wide text-sm" href="#">Mídia</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] transition-opacity duration-300 ease-in-out font-sans tracking-wide text-sm" href="#">Contato</a>
</div>
<div class="flex items-center gap-4">
<button class="flex items-center gap-2 bg-primary-container text-on-primary px-6 py-2 rounded-xl font-medium hover:opacity-80 transition-opacity duration-300 transform active:scale-95">
<span class="material-symbols-outlined text-sm">schedule</span>
<span class="text-sm tracking-wide">Agendar Consulta</span>
</button>
</div>
</div>
</nav>
<main class="pt-32 pb-20">
<header class="max-w-7xl mx-auto px-8 mb-20 text-center md:text-left">
<div class="max-w-3xl">
<h1 class="font-headline text-5xl md:text-7xl text-primary leading-tight mb-8">Reflexões sobre o Inconsciente</h1>
<p class="text-on-surface-variant text-lg leading-relaxed font-light tracking-wide">
                    Um espaço dedicado à exploração dos processos mentais, da subjetividade e dos caminhos da cura através da palavra.
                </p>
</div>
</header>
<section class="max-w-7xl mx-auto px-8 mb-16">
<div class="flex flex-wrap gap-4 items-center border-b border-outline-variant/15 pb-8">
<span class="text-label-sm uppercase tracking-widest text-on-surface/50 font-medium mr-4">Filtrar por:</span>
<button class="px-6 py-2 rounded-full bg-primary text-on-primary text-sm font-medium transition-all">Todos</button>
<button class="px-6 py-2 rounded-full hover:bg-surface-container-high text-on-surface-variant text-sm font-medium transition-all">Sonhos</button>
<button class="px-6 py-2 rounded-full hover:bg-surface-container-high text-on-surface-variant text-sm font-medium transition-all">Transferência</button>
<button class="px-6 py-2 rounded-full hover:bg-surface-container-high text-on-surface-variant text-sm font-medium transition-all">Luto e Melancolia</button>
<button class="px-6 py-2 rounded-full hover:bg-surface-container-high text-on-surface-variant text-sm font-medium transition-all">Cultura</button>
</div>
</section>
<section class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-12 gap-y-20">
<article class="group cursor-pointer">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Ethereal abstract photography of shifting smoke patterns in soft emerald green and sand tones, dreamlike atmosphere" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBrzdcrSyCA2PIZx20f-Ek9bPkAQ8THgnOcA5oXqKgOIPF1bDPrNsq8JbIr4kTiv6Xj3GN-RogB9C4bKlRsowb5v8Sc6pNvhBGWE5WKAluM2KyAjUbKJvb3ZLZ92jZFx1AEqz8tBGNKNKqRDzOZZidT3CJfBITjS40C0SRabWmup-OWenitlAIyFm0VXmavEUwMJYXrn9tVJ4HGQmWQZe9PIb3cgzD02TgIcRHRXcSD9w1h6ZPNL5gnvtI2bWtt06ZYlyuRmXOZaKo"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Sonhos</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">O papel dos sonhos na clínica psicanalítica contemporânea</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">A manifestação do desejo através da imagem onírica e como Freud ainda nos ajuda a decifrar os enigmas da noite...</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
<article class="group cursor-pointer md:mt-12">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Close up of two translucent glasses reflecting soft natural light on a textured linen surface, symbolizing connection and reflection" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFuxRHiph5qwxDxwm2j5oidzWe0piBT41dus0AOXPn0um7yQc4WAo4dbOXihcjuDsI3p-_aseK0GOOE4CPOEHk6xrQu10PEDkDOOvCjNEByQPQLa_UOK7NREwF3I5iuZr83Y5R2vTzgwb82qCEfozHiWEeFT8IJRTwADlUTwnPx5y1Ka7lkfw-SgrDDjyJQCsuyyikCPi9iRsD1gCO-BYqZxcFWedFaCtfDwo6OWxL-SvmwYIY6edKj6R23w_s8nGK2tgsif4vpJY"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Teoria</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">Transferência: O amor que cura e o amor que resiste</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">Entender o vínculo entre analista e analisando como o motor fundamental da transformação subjetiva e seus desafios éticos.</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
<article class="group cursor-pointer">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Deep forest landscape with mist rising from the valley floor, moody and introspective visual representation of the unconscious" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDx23ja-CmDkr1CQcgDc8S235eMHCM5vNxyaqj-bsoIMIerLGhetkKFyo8WzZlpZt4nQjTPsxydjdhxpBRwT1IIoqUwjx8yHW0MqT0ei8m8RMmC1KcGjOnqePRqXurWqSVwCeG9eh0mkJnEyegGu7nGW5crGxaoSShMRcGaNsimpyewJn54VVqboUqO2URc3kbsY5AWMZLBiZFP4o-TooTt5e__ttAh1Bjic8UP61zDW0Y7KrAL31wtiXCU08sHbVe5uwrPf9Ioaq0"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Prática</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">A escuta analítica: Onde o silêncio ganha voz</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">A importância da atenção flutuante e como o analista acolhe o que não foi dito nas entrelinhas do discurso cotidiano.</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
<article class="group cursor-pointer lg:mt-[-3rem]">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Minimalist sculpture of a human profile emerging from rough stone, soft lighting highlighting textures and forms" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC5dSAtgUpNPCS6K6a07WsnCkkc1BhGVidtqCU3HUtK0CoRqzORAFTjqS7NeFx0bK7gJpUQWfaMCxAhQpgGWxWFT6zgBcgvpKJU0rwiRZ7fqSxELk0j6a_bzENJM5X3ATomYJoEbZFfAaC6F7bh4Q0IGkUl1q5EPtd1CJSxdfBs3vAhNGz-upZXRqbrQ2OQu-go-Zq_EAeHp35keKBCjf1jlePiP-OpytlMnOOh8KZfcCWH4ydkWIeUaXsyhA_5JInMDRdi2ILF1Ik"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Cultura</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">O mal-estar na civilização digitalizada</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">Reflexões sobre como as novas formas de conexão impactam o psiquismo e a formação de sintomas na atualidade.</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
<article class="group cursor-pointer md:mt-12">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Withered flower in a glass vase against a neutral background, soft dramatic light casting long shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuALFDWjKBdykai88QM8VY5Xt8Sw0T8D0IEkZCAo9WVVT_0ZIjYVNXw4-U5D-HiGl6kIU-CAqmEamW9LwfV9gSegWKLFTl8LMM6gMhK8RAYexgcLqlfcZ-aWhr6AcUiQ6X6Aftgdqdv4XuM6VQj1neNCAS5HrA5NGzQhQA9ZOwyiWF6EzrddfOfrq_Ds_3d-pDoIHQiFYV_hfsO9bh26xZ7Cg3Rf_eykLPfN6oJ8y-lEOs9SNneIVG5CA5m2fz5KMq62zWsF7MRofIo"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Luto</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">Entre a melancolia e o trabalho do luto</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">Como a psicanálise auxilia no processo de desinvestimento libidinal e na reconstrução do eu após a perda.</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
<article class="group cursor-pointer lg:mt-[-3rem]">
<div class="relative aspect-[4/5] mb-8 overflow-hidden rounded-xl bg-surface-container shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-transform duration-500 group-hover:scale-[1.02]">
<img class="w-full h-full object-cover grayscale-[0.2] transition-all duration-700 group-hover:scale-110" data-alt="Subtle ripple in a calm body of water reflecting a clear sky, minimalist and peaceful composition" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAc1wZXGZw1P-OjirTAAtn--gQk6WJ0QAUby1cDWpNkf1NsQqTqre2kuN5sNLYBo1KY4tNeFdab50Q7ExRkCW5602ArKBpgYbAoJJJK86umdAX65R3edhnaSA6skRW57EwQHGCGX-fjuftPBMFJ5iGba2OxnQLF5g-VPVnQjX_lRUHkXwLdj7AIlRAFKw9poqrjYt5vLQNKsx3edAogPFmaL4JEAFHWTmiVE6Vq9glJ4yzGTbwlv4aeChmt5Wx6g-aDAdG4E79e6zU"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
<div class="space-y-4">
<span class="text-xs uppercase tracking-widest text-secondary font-semibold">Técnica</span>
<h3 class="font-headline text-2xl text-on-surface group-hover:text-primary transition-colors">O espelho que não reflete o óbvio</h3>
<p class="text-on-surface-variant text-sm leading-relaxed line-clamp-3">A função especular do analista e a construção da identidade a partir do olhar do outro.</p>
<div class="pt-4 flex items-center text-primary gap-2 font-medium text-sm">
<span>Ler artigo</span>
<span class="material-symbols-outlined text-base">arrow_forward</span>
</div>
</div>
</article>
</section>
<section class="max-w-7xl mx-auto px-8 mt-40">
<div class="bg-tertiary-container/30 border border-outline-variant/15 p-12 md:p-20 rounded-xl relative overflow-hidden backdrop-blur-sm">
<div class="relative z-10 max-w-2xl mx-auto text-center">
<span class="material-symbols-outlined text-4xl text-on-tertiary-container mb-6 block" style="font-variation-settings: 'FILL' 1;">info</span>
<h2 class="font-headline text-3xl text-on-tertiary-container mb-6 italic">Nota sobre as reflexões</h2>
<p class="text-on-tertiary-container/80 leading-relaxed font-light italic">
                        Os textos aqui compartilhados são de caráter estritamente reflexivo e teórico. Eles visam fomentar o pensamento clínico e a curiosidade sobre a alma humana. De modo algum o conteúdo destes artigos substitui a necessidade de um processo analítico individualizado, supervisão ou consulta terapêutica profissional.
                    </p>
</div>
<div class="absolute -bottom-20 -right-20 w-80 h-80 bg-primary/5 rounded-full blur-3xl"></div>
<div class="absolute -top-20 -left-20 w-60 h-60 bg-secondary/5 rounded-full blur-3xl"></div>
</div>
</section>
</main>
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef] dark:bg-[#1a1c19]">
<div class="flex flex-col items-center gap-8 py-20 px-4 w-full text-center">
<div class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho - Psicanálise</div>
<div class="flex gap-8">
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">Instagram</a>
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">WhatsApp</a>
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">Spotify</a>
</div>
<div class="max-w-2xl font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/60 leading-relaxed">
                RNTP 0482 | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
            </div>
<div class="mt-8 text-[10px] text-on-surface/40 uppercase tracking-widest">
                © 2024 Alyne Carvalho. Todos os direitos reservados.
            </div>
</div>
</footer>
</body></html>

<!-- Artigos e Reflexões -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Mídia | Alyne Carvalho - Psicanálise</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Inter:wght@300;400;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .glass-nav {
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        .green-filter {
            filter: sepia(100%) hue-rotate(90deg) saturate(150%) brightness(40%) contrast(120%);
        }
        .reflection-mirror {
            background: rgba(32, 73, 53, 0.95);
            backdrop-filter: blur(20px);
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-fixed selection:text-on-primary-fixed">
<!-- TopNavBar -->
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 backdrop-blur-md shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-colors duration-300">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="font-serif text-xl italic text-[#1a4a2e]">Alyne Carvalho - Psicanálise</div>
<div class="hidden md:flex gap-8 items-center">
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Home</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Sobre</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Artigos</a>
<a class="text-[#1a4a2e] font-semibold border-b-2 border-[#1a4a2e] pb-1 font-sans tracking-wide text-sm" href="#">Mídia</a>
<a class="text-[#1a1c19]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Contato</a>
</div>
<div class="flex items-center gap-4">
<button class="bg-[#87b995] text-[#00210f] px-6 py-2 xl rounded-xl font-sans text-sm font-semibold hover:opacity-80 transition-opacity active:scale-95 duration-300 flex items-center gap-2">
<span class="material-symbols-outlined text-lg">schedule</span>
                    Agendar Consulta
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-20 max-w-7xl mx-auto px-8">
<!-- Hero Header -->
<header class="mb-20 space-y-6">
<h1 class="font-headline text-5xl md:text-7xl text-primary max-w-3xl leading-tight">Conteúdos para inspirar sua jornada interior</h1>
<p class="text-on-surface-variant text-lg max-w-xl font-light leading-relaxed">Uma curadoria de conversas, reflexões e explorações sobre a psiquê humana, o silêncio e o processo analítico.</p>
</header>
<!-- Featured Media (Bento Grid Style) -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-8 mb-24">
<!-- Large Featured YouTube -->
<div class="md:col-span-8 group relative overflow-hidden rounded-xl bg-surface-container shadow-sm aspect-video">
<div class="absolute inset-0 z-10 bg-gradient-to-t from-primary/80 via-transparent to-transparent opacity-60"></div>
<img alt="Vídeo Destaque" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105 green-filter" data-alt="Cinematic shot of a single candle flame in a dark room with soft smoke trails and emerald green color grading" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAg_RjvtGC3JS0hTJJ0annstfwNcMKhZj_LfaziRSfD5Z7mLemGTwyiXpDTgo-BTCkClgsA01fLgEuD9Fzw9dI_bBT3M1M_oj7JkXB3spu6Dbz6zqe0vdZ8Qkqy405djVVdwB3SAwaLXMPdxvhxwL0khqC9n2s4Hn1LuYFt9l-ZurqWETV5ikfoQkftacRFZpKZxeedH2rfApuSyXqBcQgmrT5QinLrVdlMSsQZ3fzD4TlOtWc6KHWntWfQUOcZWtql8TFjJaGcrYI"/>
<div class="absolute inset-0 z-20 flex flex-col justify-end p-10">
<span class="text-on-primary/70 text-xs uppercase tracking-widest mb-2 flex items-center gap-2">
<span class="material-symbols-outlined text-sm">play_circle</span> VÍDEO EM DESTAQUE
                    </span>
<h2 class="text-on-primary font-headline text-3xl mb-4 max-w-lg">O Silêncio como Ferramenta de Transformação</h2>
<button class="w-14 h-14 rounded-full bg-on-primary-container text-on-primary-fixed flex items-center justify-center transition-transform hover:scale-110">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">play_arrow</span>
</button>
</div>
</div>
<!-- Spotify Reflection Mirror -->
<div class="md:col-span-4 flex flex-col gap-8">
<div class="reflection-mirror p-8 rounded-xl flex flex-col justify-between flex-1">
<div>
<span class="material-symbols-outlined text-on-tertiary-container mb-4 text-3xl" style="font-variation-settings: 'FILL' 1;">format_quote</span>
<p class="font-headline text-xl text-on-tertiary-container italic leading-relaxed">
                            "A análise é o encontro entre dois silêncios que buscam uma palavra que cure."
                        </p>
</div>
<div class="pt-6 border-t border-outline-variant/15 flex items-center gap-3">
<div class="w-8 h-8 rounded-full bg-secondary-container flex items-center justify-center">
<span class="material-symbols-outlined text-sm text-on-secondary-container">podcasts</span>
</div>
<span class="text-on-tertiary-container text-xs uppercase tracking-widest">Ouça no Spotify</span>
</div>
</div>
<!-- Secondary Video -->
<div class="group relative overflow-hidden rounded-xl bg-surface-container aspect-square">
<img alt="Thumbnail" class="w-full h-full object-cover green-filter transition-transform duration-500 group-hover:scale-105" data-alt="Abstract view of dark green forest leaves with deep shadows and soft ethereal light filtering through" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCpUnwc4R47cAYBGyxlKJfpALWQT7hMAD43vqYSsQOnpFB2hb7fOb1mfyWlEI3aXW9Bk9xW5hOsbnK6X0HhcaNDV5nzo0qcB9tKywq7Q9tO1cOzdatYHdLB5GkKMsAtis5kmA1EL66nXyI-YbqGGtizXao7VnpaPJ4n-7YMhpeZN5vgBRJ1NBwDIpc9ciHLFXJl5BiYpGQdN7dYgemnf-NhpsKOwiLzMf5hvHX2PoUPKLT3QkfoqkmKI-zMFAlCG6N0gH0A-RIO-fg"/>
<div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors duration-300"></div>
<div class="absolute bottom-6 left-6 right-6">
<p class="text-on-primary font-serif text-lg leading-tight">Fragmentos do Inconsciente: Uma Conversa</p>
</div>
</div>
</div>
</section>
<!-- Media Grid Filter/Navigation -->
<div class="flex items-center gap-12 mb-12 border-b border-outline-variant/15 pb-4">
<button class="text-primary font-semibold border-b-2 border-primary pb-4 -mb-[18px] text-sm uppercase tracking-widest">Todos</button>
<button class="text-on-surface-variant hover:text-primary transition-colors pb-4 text-sm uppercase tracking-widest">Vídeos</button>
<button class="text-on-surface-variant hover:text-primary transition-colors pb-4 text-sm uppercase tracking-widest">Podcasts</button>
<button class="text-on-surface-variant hover:text-primary transition-colors pb-4 text-sm uppercase tracking-widest">Entrevistas</button>
</div>
<!-- Artistic Grid -->
<section class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-y-16 gap-x-12">
<!-- Card 1 -->
<div class="group">
<div class="relative aspect-[4/5] mb-6 overflow-hidden rounded-xl bg-surface-container-low shadow-sm">
<img alt="Media" class="w-full h-full object-cover green-filter grayscale-[30%] transition-transform duration-700 group-hover:scale-110" data-alt="Minimalist dark green ceramic vase on a wooden table in front of a soft linen background with natural window shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXUO2CmqNQn2-tLWII_e865Xr2rWRJ8YfO3FPG6ACniOGky0ZkLl9pSsZfMMpXnPxOirqdcyuVqFPdWubbHuLk7_FjI4PXoQGlNdgD5zFN8PP5fhVd3GfzELqKzu3sfBnJROzKr6qv2S02rcqKBs4zQrrUdqK6S05ePyBOg9RUa2odwRBuZ6DE0bZ7j8nxumSwPNiyvpFfLEBzxaaBFRuhQAS3B6kGmXfrK2DeGo5aBPN9ZdxNIX91mfO9P6PHYwVV7eFv-fV0Axo"/>
<div class="absolute top-4 right-4 bg-surface/90 backdrop-blur-sm p-2 rounded-full">
<span class="material-symbols-outlined text-primary text-xl">play_arrow</span>
</div>
</div>
<div class="space-y-3">
<div class="flex items-center gap-2 text-on-surface-variant text-[10px] uppercase tracking-[0.15rem]">
<span>Março 2024</span>
<span class="w-1 h-1 rounded-full bg-outline-variant"></span>
<span>Duração: 45min</span>
</div>
<h3 class="font-headline text-2xl text-primary leading-snug group-hover:text-secondary transition-colors cursor-pointer">A Arte da Escuta Analítica no Mundo Digital</h3>
</div>
</div>
<!-- Card 2 -->
<div class="group mt-8 md:mt-16">
<div class="relative aspect-[4/5] mb-6 overflow-hidden rounded-xl bg-surface-container-low shadow-sm">
<img alt="Media" class="w-full h-full object-cover green-filter transition-transform duration-700 group-hover:scale-110" data-alt="Vintage record player spinning a black vinyl disc with moody green and dark shadows highlighting the texture" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBeX-n5FTMKFxjTV48DzX5VtSmsjyIkNcFyd8olxYN8y4L34ihqhDTeU_zgCCVb5m75E8pNKLqoj9VeiD_owAV_81YJmlUFE0xxZWNW_LUFsG-2cTntVdMQ1CRTmhjR_ItK6ZWKelGWDtdEKgOUyShJtbWzv1QqRRmdQCa4RwyhH_h_Dm5jUbuFCUePhgHAtQtypu09BZ-1M1VGema7ZsgZ0lEe4afAvA4VNTt3EAUq9bQbRo3zYN2ZQJB_UdvTczBYx3VJ3ncx-LI"/>
<div class="absolute top-4 right-4 bg-surface/90 backdrop-blur-sm p-2 rounded-full">
<span class="material-symbols-outlined text-primary text-xl">podcasts</span>
</div>
</div>
<div class="space-y-3">
<div class="flex items-center gap-2 text-on-surface-variant text-[10px] uppercase tracking-[0.15rem]">
<span>Fevereiro 2024</span>
<span class="w-1 h-1 rounded-full bg-outline-variant"></span>
<span>Spotify Exclusive</span>
</div>
<h3 class="font-headline text-2xl text-primary leading-snug group-hover:text-secondary transition-colors cursor-pointer">Sonhos e Simbolismo: O Que Dizem as Imagens Noturnas</h3>
</div>
</div>
<!-- Card 3 -->
<div class="group">
<div class="relative aspect-[4/5] mb-6 overflow-hidden rounded-xl bg-surface-container-low shadow-sm">
<img alt="Media" class="w-full h-full object-cover green-filter transition-transform duration-700 group-hover:scale-110" data-alt="Handwriting on old textured paper with a fountain pen in deep forest green ink and dramatic side lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD1WYBj9eRkiS_OB1evBSzBmzI6zbSByuVPc1nYRkrqJMCOYGURgRoeSqSV0sx_sqNmU4MVmRai7r2lAt9-r4WKUmDorkR7rwxEp8-bIY9FNIiUQz38UFxLzTyAdkLzGVM2QL8RR3tehzCT_uhciX-cDfOawU-q7IdIaqjJa_4CxVCVDFcI4u4RqZqydX5He8I9lfGRphaiTUv-njkRfmqntpEwSFy7KuYB6l1V9gmn7ixXt0cAvI-S2AEV0KPOCHXQ15s14DeRY7U"/>
<div class="absolute top-4 right-4 bg-surface/90 backdrop-blur-sm p-2 rounded-full">
<span class="material-symbols-outlined text-primary text-xl">play_arrow</span>
</div>
</div>
<div class="space-y-3">
<div class="flex items-center gap-2 text-on-surface-variant text-[10px] uppercase tracking-[0.15rem]">
<span>Janeiro 2024</span>
<span class="w-1 h-1 rounded-full bg-outline-variant"></span>
<span>Entrevista</span>
</div>
<h3 class="font-headline text-2xl text-primary leading-snug group-hover:text-secondary transition-colors cursor-pointer">Psicanálise Contemporânea: Novos Desafios da Clínica</h3>
</div>
</div>
</section>
<!-- Newsletter / Reflection Section -->
<section class="mt-40 bg-surface-container-low rounded-xl p-12 md:p-20 text-center space-y-8">
<h2 class="font-headline text-3xl md:text-4xl text-primary max-w-2xl mx-auto">Receba novos conteúdos e insights diretamente em seu e-mail</h2>
<div class="max-w-md mx-auto flex flex-col sm:flex-row gap-4">
<input class="flex-1 bg-surface border-none rounded-xl px-6 py-4 text-sm focus:ring-1 focus:ring-primary-container" placeholder="seu@email.com" type="email"/>
<button class="bg-primary text-on-primary px-8 py-4 rounded-xl font-sans text-sm font-semibold hover:opacity-90 transition-opacity">Inscrever</button>
</div>
<p class="text-on-surface-variant text-xs uppercase tracking-widest opacity-60">Respeitamos seu tempo e privacidade.</p>
</section>
</main>
<!-- Footer -->
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef] dark:bg-[#1a1c19] flex flex-col items-center gap-8 py-20 px-4 text-center">
<div class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho</div>
<div class="flex gap-12 text-[#1a1c19]/50 font-sans text-xs uppercase tracking-[0.05rem]">
<a class="hover:text-[#1a4a2e] transition-colors duration-300" href="#">Instagram</a>
<a class="hover:text-[#1a4a2e] transition-colors duration-300" href="#">WhatsApp</a>
<a class="hover:text-[#1a4a2e] transition-colors duration-300" href="#">Spotify</a>
</div>
<p class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/60 max-w-lg leading-loose">
            RNTP 1245 | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
        </p>
</footer>
</body></html>

<!-- Mídia e Conteúdo -->
<!DOCTYPE html>

<html class="light" lang="pt-BR"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Agendar Consulta | Alyne Carvalho - Psicanálise</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-tertiary-fixed": "#002113",
              "secondary": "#3b6847",
              "outline": "#717971",
              "surface-container-low": "#f4f4ef",
              "on-error": "#ffffff",
              "primary": "#00331a",
              "on-background": "#1a1c19",
              "on-primary-fixed-variant": "#205033",
              "on-primary": "#ffffff",
              "on-secondary-fixed": "#00210d",
              "surface-tint": "#396849",
              "on-tertiary-fixed-variant": "#254f3a",
              "secondary-fixed": "#bcefc4",
              "surface-dim": "#dadad5",
              "surface-container-high": "#e8e8e3",
              "on-secondary": "#ffffff",
              "primary-fixed": "#bbefc8",
              "on-error-container": "#93000a",
              "primary-container": "#1a4a2e",
              "on-primary-container": "#87b995",
              "tertiary": "#053220",
              "error-container": "#ffdad6",
              "on-surface-variant": "#414942",
              "primary-fixed-dim": "#9fd2ad",
              "on-primary-fixed": "#00210f",
              "inverse-on-surface": "#f1f1ec",
              "on-surface": "#1a1c19",
              "tertiary-fixed-dim": "#a4d1b6",
              "on-secondary-container": "#416e4c",
              "on-tertiary": "#ffffff",
              "surface-container-highest": "#e3e3de",
              "on-tertiary-container": "#8cb79e",
              "tertiary-fixed": "#bfedd1",
              "surface": "#fafaf5",
              "error": "#ba1a1a",
              "tertiary-container": "#204935",
              "secondary-fixed-dim": "#a1d2aa",
              "surface-variant": "#e3e3de",
              "surface-container-lowest": "#ffffff",
              "on-secondary-fixed-variant": "#225031",
              "surface-bright": "#fafaf5",
              "secondary-container": "#bcefc4",
              "outline-variant": "#c1c9c0",
              "background": "#fafaf5",
              "inverse-surface": "#2f312e",
              "inverse-primary": "#9fd2ad",
              "surface-container": "#eeeee9"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "0.125rem", "lg": "0.25rem", "xl": "0.5rem", "full": "0.75rem"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .glass-effect {
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-secondary-container/30">
<!-- Top Navigation Bar -->
<nav class="fixed top-0 w-full z-50 bg-[#fafaf5]/80 dark:bg-[#1a1c19]/80 backdrop-blur-md shadow-[0_32px_64px_rgba(0,51,26,0.04)] transition-colors duration-300">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<a class="font-serif text-xl italic text-[#1a4a2e] dark:text-[#f4f4ef]" href="/">Alyne Carvalho - Psicanálise</a>
<div class="hidden md:flex items-center gap-10">
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Home</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Sobre</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Artigos</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Mídia</a>
<a class="text-[#1a1c19]/70 dark:text-[#f4f4ef]/70 hover:text-[#1a4a2e] font-sans tracking-wide text-sm transition-opacity duration-300" href="#">Contato</a>
</div>
<div class="flex items-center gap-4">
<button class="flex items-center gap-2 text-[#1a4a2e] dark:text-[#87b995] font-semibold border-b-2 border-[#1a4a2e] pb-1 font-sans tracking-wide text-sm transform active:scale-95 ease-in-out duration-300">
<span class="material-symbols-outlined text-base">schedule</span>
                    Agendar Consulta
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-20 px-6 max-w-7xl mx-auto">
<!-- Hero Section -->
<header class="mb-20 max-w-3xl">
<span class="font-label text-xs uppercase tracking-[0.2rem] text-secondary mb-4 block">Inicie sua jornada</span>
<h1 class="font-headline text-5xl md:text-7xl text-primary leading-tight mb-8">O silêncio que convida à escuta.</h1>
<p class="font-body text-lg text-on-surface-variant leading-relaxed">
                Agende um momento para si mesmo. A psicanálise é um processo de descoberta, onde cada palavra é um passo em direção à clareza interna.
            </p>
</header>
<!-- Bento Grid Layout for Features and Form -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
<!-- Information Panel (Asymmetric) -->
<div class="lg:col-span-4 flex flex-col gap-8">
<!-- Status Card -->
<div class="bg-surface-container-low p-10 rounded-xl">
<div class="flex items-start gap-4 mb-12">
<div class="bg-primary-container p-3 rounded-lg">
<span class="material-symbols-outlined text-on-primary-container" style="font-variation-settings: 'FILL' 1;">verified_user</span>
</div>
<div>
<h3 class="font-headline text-xl text-primary mb-2">Compromisso Ético</h3>
<p class="text-sm text-on-surface-variant leading-relaxed">Privacidade absoluta e sigilo profissional inabalável em cada atendimento.</p>
</div>
</div>
<div class="space-y-8">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">workspace_premium</span>
<span class="text-sm font-medium">Primeira sessão exploratória grátis</span>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">timer</span>
<span class="text-sm font-medium">Duração: 50min</span>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">encrypted</span>
<span class="text-sm font-medium">100% confidencial</span>
</div>
</div>
</div>
<!-- Reflection Mirror (Signature Component) -->
<div class="glass-effect bg-tertiary-container p-10 rounded-xl relative overflow-hidden group">
<div class="absolute -right-4 -top-4 opacity-10 group-hover:scale-110 transition-transform duration-700">
<span class="material-symbols-outlined text-[120px]">format_quote</span>
</div>
<p class="font-headline italic text-on-tertiary-container text-lg mb-6 leading-relaxed relative z-10">
                        "Olhar para dentro não é apenas ver o que está lá, mas permitir que o que está lá seja visto."
                    </p>
<span class="text-xs uppercase tracking-widest text-on-tertiary-container/60">Insight Psicanalítico</span>
</div>
<!-- Decorative Image -->
<div class="h-64 rounded-xl overflow-hidden grayscale contrast-125 brightness-90">
<img class="w-full h-full object-cover" data-alt="minimalist interior with a comfortable linen chair next to a large window with soft morning light and a single green plant" src="https://lh3.googleusercontent.com/aida-public/AB6AXuANyqk_H-CpfjEgcCdK8UK2D7Q41-5xrnObnKBF7gVH--Wr7XoI0mWuZzgXsMdKJjSr5f7STcAFT1f9P9I-G2b7MGaa1MQlZ4mdSNC7H5wxw9Aij0a3CmBrVNhOXpgx0i-9QqPLNKc1gPCq5_UIKAsyWJmYHT5bsgN_Areolt3DnTwvJm7hXc4jhcKFcdRbfG2mJ3JWO8FkV_6zSx1iF0Gbz7VsZqtlqMChCqMT9WpkILz0DhKWaYduJrQJSAWQvV6vDHB9M7KOPgg"/>
</div>
</div>
<!-- Form & Calendar Panel -->
<div class="lg:col-span-8 space-y-8">
<!-- Multi-step Style Form Container -->
<div class="bg-surface-container-lowest rounded-xl p-10 shadow-[0_32px_64px_rgba(0,51,26,0.02)]">
<div class="mb-12">
<h2 class="font-headline text-3xl text-primary mb-2">Solicitar Agendamento</h2>
<div class="h-0.5 w-12 bg-secondary/30"></div>
</div>
<form class="space-y-10">
<div class="grid grid-cols-1 md:grid-cols-2 gap-10">
<!-- Name Input -->
<div class="relative group">
<label class="block text-xs uppercase tracking-widest text-on-surface-variant mb-3 group-focus-within:text-primary transition-colors">Nome Completo</label>
<input class="w-full bg-transparent border-0 border-b border-outline-variant/30 py-4 focus:ring-0 focus:border-primary transition-all font-body text-on-surface placeholder:text-outline-variant/60" placeholder="Como deseja ser chamado(a)?" type="text"/>
</div>
<!-- Email Input -->
<div class="relative group">
<label class="block text-xs uppercase tracking-widest text-on-surface-variant mb-3 group-focus-within:text-primary transition-colors">E-mail para Contato</label>
<input class="w-full bg-transparent border-0 border-b border-outline-variant/30 py-4 focus:ring-0 focus:border-primary transition-all font-body text-on-surface placeholder:text-outline-variant/60" placeholder="exemplo@dominio.com" type="email"/>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-10">
<!-- Preference Select -->
<div class="relative group">
<label class="block text-xs uppercase tracking-widest text-on-surface-variant mb-3 group-focus-within:text-primary transition-colors">Preferência de Atendimento</label>
<select class="w-full bg-transparent border-0 border-b border-outline-variant/30 py-4 focus:ring-0 focus:border-primary transition-all font-body text-on-surface appearance-none">
<option>Sessão Online (Vídeo)</option>
<option>Sessão Presencial</option>
<option>Ainda não decidi</option>
</select>
<span class="material-symbols-outlined absolute right-0 bottom-4 text-outline-variant">expand_more</span>
</div>
<!-- Calendar Trigger Placeholder -->
<div class="relative group">
<label class="block text-xs uppercase tracking-widest text-on-surface-variant mb-3 group-focus-within:text-primary transition-colors">Data Sugerida</label>
<div class="w-full flex justify-between items-center bg-transparent border-0 border-b border-outline-variant/30 py-4 cursor-pointer">
<span class="text-outline-variant/60">Escolher no Calendário</span>
<span class="material-symbols-outlined text-primary">calendar_today</span>
</div>
</div>
</div>
<!-- Message -->
<div class="relative group">
<label class="block text-xs uppercase tracking-widest text-on-surface-variant mb-3 group-focus-within:text-primary transition-colors">Breve Contextualização (Opcional)</label>
<textarea class="w-full bg-transparent border-0 border-b border-outline-variant/30 py-4 focus:ring-0 focus:border-primary transition-all font-body text-on-surface placeholder:text-outline-variant/60 resize-none" placeholder="Sinta-se à vontade para compartilhar o que te traz aqui hoje..." rows="3"></textarea>
</div>
<!-- Submit Action -->
<div class="flex flex-col md:flex-row items-center justify-between gap-8 pt-6">
<div class="flex items-center gap-3 text-on-surface-variant/60 italic text-sm">
<span class="material-symbols-outlined text-sm">lock</span>
                                Seus dados estão protegidos por criptografia de ponta a ponta.
                            </div>
<button class="w-full md:w-auto px-10 py-5 bg-on-primary-container text-on-primary-fixed rounded-xl font-semibold tracking-wide hover:opacity-90 transition-all transform active:scale-95 shadow-xl shadow-on-primary-container/20" type="submit">
                                Confirmar Agendamento
                            </button>
</div>
</form>
</div>
<!-- Calendly Integration Preview Card -->
<div class="bg-surface-container rounded-xl overflow-hidden border border-outline-variant/15">
<div class="px-10 py-6 border-b border-outline-variant/15 flex justify-between items-center">
<div class="flex items-center gap-3">
<div class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></div>
<span class="text-xs uppercase tracking-widest font-semibold">Horários Disponíveis</span>
</div>
<span class="text-xs text-on-surface-variant">Sincronizado com Calendly</span>
</div>
<div class="aspect-video bg-surface-container-highest/50 flex items-center justify-center p-12">
<!-- Placeholder for actual Calendly Widget -->
<div class="text-center max-w-sm">
<span class="material-symbols-outlined text-primary/30 text-5xl mb-4">event_available</span>
<p class="text-on-surface-variant leading-relaxed italic">O calendário interativo carregará aqui para seleção exata de horários após o preenchimento dos dados básicos.</p>
</div>
</div>
</div>
</div>
</div>
</main>
<!-- Success Confirmation (Visual Representation for "Pop-up Style") -->
<!-- Note: Normally hidden, displayed here to show the requested 'confirmation pop-up style' -->
<div class="fixed inset-0 z-[100] flex items-center justify-center pointer-events-none opacity-0 transition-opacity duration-500">
<div class="bg-surface p-12 rounded-xl shadow-[0_64px_128px_rgba(0,0,0,0.1)] max-w-md w-full border border-outline-variant/10 relative">
<div class="flex flex-col items-center text-center">
<div class="w-20 h-20 bg-secondary-container text-on-secondary-container rounded-full flex items-center justify-center mb-8">
<span class="material-symbols-outlined text-4xl" style="font-variation-settings: 'FILL' 1;">check_circle</span>
</div>
<h2 class="font-headline text-2xl text-primary mb-4">Solicitação Recebida</h2>
<p class="text-on-surface-variant leading-relaxed mb-8">
                    Alyne entrará em contato em até 24h úteis via WhatsApp ou E-mail para confirmar sua sessão exploratória.
                </p>
<button class="w-full py-4 bg-primary text-on-primary rounded-xl font-medium">Voltar para Home</button>
</div>
</div>
</div>
<!-- Footer -->
<footer class="w-full border-t border-[#c1c9c0]/15 bg-[#f4f4ef] dark:bg-[#1a1c19] transition-colors duration-300">
<div class="flex flex-col items-center gap-8 py-20 px-4 w-full text-center">
<span class="font-serif text-lg text-[#1a4a2e]">Alyne Carvalho</span>
<div class="flex gap-12">
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">Instagram</a>
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">WhatsApp</a>
<a class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/50 hover:text-[#1a4a2e] transition-colors duration-300" href="#">Spotify</a>
</div>
<p class="font-sans text-xs uppercase tracking-[0.05rem] text-[#1a1c19]/60 max-w-2xl leading-loose">
                RNTP 0842 | Ética: Confidencialidade inabalável | Psicanálise: processo paciente e transformador
            </p>
</div>
</footer>
</body></html>
