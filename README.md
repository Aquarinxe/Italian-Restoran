# Italian-Restoran
<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>La Trattoria</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,200..800;1,6..72,200..800&amp;family=Noto+Sans:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<!-- Theme Configuration -->
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#f2b90d",
                        "background-light": "#f8f8f5",
                        "background-dark": "#221e10",
                    },
                    fontFamily: {
                        "display": ["Newsreader", "serif"],
                        "body": ["Noto Sans", "sans-serif"]
                    },
                    borderRadius: {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    backgroundImage: {
                        'maroon-gradient': 'linear-gradient(to bottom, #221e10 0%, #1a160a 100%)',
                    }
                },
            },
        }
    </script>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background-light dark:bg-background-dark font-display text-slate-900 dark:text-white antialiased">
<!-- Main Container -->
<div class="relative flex h-full min-h-screen w-full flex-col overflow-x-hidden bg-background-light dark:bg-background-dark max-w-md mx-auto shadow-2xl">
<!-- Top App Bar -->
<header class="sticky top-0 z-50 bg-background-light/95 dark:bg-background-dark/95 backdrop-blur-sm border-b border-primary/20 p-4 pb-3 flex items-center justify-between">
<div class="text-primary flex size-10 shrink-0 items-center justify-center cursor-pointer hover:bg-primary/10 rounded-full transition-colors">
<span class="material-symbols-outlined text-[28px]">menu</span>
</div>
<div class="flex flex-col items-center">
<h1 class="text-slate-900 dark:text-white text-2xl font-bold tracking-tight italic">La Trattoria</h1>
<span class="text-primary text-[10px] uppercase tracking-[0.2em] font-bold">Cucina Italiana</span>
</div>
<div class="flex size-10 items-center justify-center">
<button class="relative flex items-center justify-center text-primary hover:bg-primary/10 rounded-full p-2 transition-colors">
<span class="material-symbols-outlined text-[24px]">shopping_bag</span>
<!-- Badge -->
<span class="absolute top-1 right-1 h-2 w-2 rounded-full bg-red-500"></span>
</button>
</div>
</header>
<!-- Main Content Scroll Area -->
<main class="flex-1 pb-24">
<!-- Hero Image Section -->
<div class="@container">
<div class="w-full relative h-[420px]">
<div class="absolute inset-0 bg-cover bg-center" data-alt="High quality moody photo of a rich pasta dish with parmesan and basil on a dark table" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDR6CywbgBv6Bkv6KbeYdUbOPMYzalDHmBSopaIWlzrdSSJh_0knQEPOC9m-IUnFr3AvZTHy80rbPJGh6k0s5tvYBQ1m2y_pk08mQEwHqpREf5xfek0lLiFGaE4MZaw11J59zEFpffjs1QEw1S_oLzcboOS7R1dLY_WQG9vkgA-Btbv6SL3d3aJKtsRcFaDklXQYz5Lk94Nq8R3XGxX0E1m-MNyrRmnDWh2arz1erCDkGR4anXUB94P1KZqc3rn2CYfaKAnIhDVBLE");'>
</div>
<!-- Gradient Overlay -->
<div class="absolute inset-0 bg-gradient-to-t from-background-dark via-background-dark/50 to-transparent flex flex-col justify-end p-6 pb-8">
<div class="border-l-4 border-primary pl-4 mb-2">
<span class="text-primary font-bold uppercase tracking-wider text-xs block mb-1">Taste of Summer</span>
<h2 class="text-white text-4xl font-light italic leading-tight drop-shadow-lg">
                                Authentic Flavors <br/> of the Mediterranean
                            </h2>
</div>
</div>
</div>
</div>
<!-- Welcome Text -->
<div class="px-6 py-8 text-center bg-background-light dark:bg-background-dark">
<span class="material-symbols-outlined text-primary text-4xl mb-3">restaurant</span>
<h2 class="text-slate-900 dark:text-white text-3xl font-bold italic mb-4">Benvenuti</h2>
<p class="text-slate-600 dark:text-slate-300 text-lg leading-relaxed font-light">
                    Experience the true taste of Italy in a warm, elegant atmosphere. Our chefs prepare every dish with passion, blending tradition with the finest imported ingredients.
                </p>
<div class="w-24 h-[1px] bg-primary/40 mx-auto mt-8"></div>
</div>
<!-- Action Buttons -->
<div class="px-6 pb-8">
<div class="flex gap-4">
<button class="flex-1 h-12 flex items-center justify-center gap-2 bg-transparent border border-primary text-primary hover:bg-primary/10 rounded-lg text-sm font-bold uppercase tracking-wider transition-all">
<span class="material-symbols-outlined text-[20px]">restaurant_menu</span>
                        View Menu
                    </button>
<button class="flex-1 h-12 flex items-center justify-center gap-2 bg-primary text-background-dark hover:bg-primary/90 rounded-lg text-sm font-bold uppercase tracking-wider shadow-lg shadow-primary/20 transition-all">
<span class="material-symbols-outlined text-[20px]">calendar_today</span>
                        Book Table
                    </button>
</div>
</div>
<!-- Featured Specials Horizontal Scroll -->
<div class="py-6 bg-[#1a160a]/50 border-y border-primary/10">
<div class="px-6 flex justify-between items-end mb-4">
<h3 class="text-xl font-bold italic text-white">Chef's Specials</h3>
<a class="text-primary text-xs uppercase font-bold tracking-wider hover:underline" href="#">See All</a>
</div>
<div class="flex overflow-x-auto gap-4 px-6 pb-4 scrollbar-hide snap-x">
<!-- Card 1 -->
<div class="flex-none w-[220px] snap-center group">
<div class="relative h-[280px] rounded-xl overflow-hidden shadow-lg border border-white/5">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Close up of Osso Buco with risotto" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDWHVIbu9EWALif5wLnA_nubyJX-F07Gl6WicPzAy-Xc_Uu3PRxQvp_ZG6h0wG3JJQzWKm9D-Fp5T_zOVL-ohqpmztqF5NaNh5Z2SVMY8-CcXVvA8g975QOXUAiceQ4M9CyAnhJ0YoYV-0Gq5XNUd6mZeq6zKXcgr0Y_U5uO8QKQZNwJccM-9LQis2W_nElfWHqVwgWCb59ybMIWTIArnb1M0yMDtJqIMLPz_RVy6ScruRQ_g_32m7e_l2rd6u63dLOP57juqSXl34");'></div>
<div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/20 to-transparent"></div>
<div class="absolute bottom-0 left-0 p-4 w-full">
<h4 class="text-white text-xl font-serif italic mb-1">Osso Buco</h4>
<p class="text-slate-300 text-xs line-clamp-2 mb-2">Milanese style braised veal shanks with saffron risotto.</p>
<span class="text-primary font-bold">$34</span>
</div>
</div>
</div>
<!-- Card 2 -->
<div class="flex-none w-[220px] snap-center group">
<div class="relative h-[280px] rounded-xl overflow-hidden shadow-lg border border-white/5">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Plate of fresh truffle pasta" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuD9VIWi5FuXQxKpZySNbiXzNHGHr_ejg3rQuUacsUVszFjkU-P27embqv5RCuNWlK6g7ssSPpO6TNisCAl-T67W4iY0ir_IeKJh9-CD6LdA05d6w76L9hJajQXf50b05VbdNF45jh4mv09aN3s4ob_KlB7jv-9Q4tTjfe91cGooVvGDN6Qy_ZQv099auBdvMG3JIGS55MM6LoAo_vBjJONhNaiPXDxMegmQfYA5CdDD2XPsN9P4DQ_l7iKhSuwhXAUthmote3AsMKU");'></div>
<div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/20 to-transparent"></div>
<div class="absolute bottom-0 left-0 p-4 w-full">
<h4 class="text-white text-xl font-serif italic mb-1">Tartufo Nero</h4>
<p class="text-slate-300 text-xs line-clamp-2 mb-2">House-made tagliolini with fresh black truffle shavings.</p>
<span class="text-primary font-bold">$28</span>
</div>
</div>
</div>
<!-- Card 3 -->
<div class="flex-none w-[220px] snap-center group">
<div class="relative h-[280px] rounded-xl overflow-hidden shadow-lg border border-white/5">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Tiramisu dessert on a plate" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCJuseO3-55PMVRQLaL6af3Ud_tWe5L4oyXdTmJEvsbo9zYqD33nhmnHIVoTuahrK-OT5HDF89bI-xmJiPPg-ScM9G1vGnqnoJ3VTJhUL8zclE20Z4jG2sTmUoxFhPfU689Bmzb6c2JN_e1c5yjh-45JyHTeeykAt7DGid8_k6jdSES-Zkoz57ohwg2OiO0N3XQNB0TIN9diRBtlnw9VWId34u8rSxdurriZTrDuwrR-N8pZ929OBItWzMfyLPWmyWufjqgunzcfMc");'></div>
<div class="absolute inset-0 bg-gradient-to-t from-black/90 via-black/20 to-transparent"></div>
<div class="absolute bottom-0 left-0 p-4 w-full">
<h4 class="text-white text-xl font-serif italic mb-1">Tiramisù</h4>
<p class="text-slate-300 text-xs line-clamp-2 mb-2">Classic espresso-soaked ladyfingers with mascarpone cream.</p>
<span class="text-primary font-bold">$12</span>
</div>
</div>
</div>
</div>
</div>
<!-- Our Story Section -->
<div class="px-6 py-10 relative overflow-hidden">
<!-- Decorative elements -->
<div class="absolute top-0 right-0 -mr-16 -mt-16 w-64 h-64 bg-primary/5 rounded-full blur-3xl pointer-events-none"></div>
<div class="relative z-10 flex flex-col items-center">
<span class="text-primary text-xs font-bold uppercase tracking-[0.2em] mb-2">Our Roots</span>
<h3 class="text-3xl italic font-bold mb-6 text-center">A Family Tradition</h3>
<div class="flex gap-4 mb-6">
<div class="w-full h-48 rounded-lg overflow-hidden relative">
<div class="absolute inset-0 bg-cover bg-center" data-alt="Vintage black and white photo of Italian family dining outdoors" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDLmvMT16Ue3dExPso1nxr14fqJY_FLQivhGJ_rPWr1VXCtBeks2LVd6SYqA1vXTTsPSQTFmq5YviDAXnBYi-4YsoBL_b4GWTj-XjiHTjjgt--3609pM0hfjZE8CUfz8SoiHe36B8BmkFzt-0BCVoBJlNs79ER9HJCvZKmbeZvMcj1tVUNFfVa0YBqXSeFrP-q6I7CHbdJIjzb62uPNhmsBhyZo2Yktf8dfznHbIdbb7bpxn8dnyh-HiiVob7nuyFOqW_CM_g10s-A");'></div>
</div>
</div>
<p class="text-slate-600 dark:text-slate-300 text-center leading-relaxed mb-6 font-light">
                        Founded in 1954, La Trattoria began as a small kitchen in the heart of Sicily. Today, we bring those same cherished recipes to your table, honoring the legacy of Nonna Maria.
                    </p>
<button class="text-primary flex items-center gap-1 text-sm font-bold hover:gap-2 transition-all">
                        Read Our Full Story <span class="material-symbols-outlined text-sm">arrow_forward</span>
</button>
</div>
</div>
<!-- Location / Map Preview -->
<div class="px-6 pb-12">
<div class="bg-white/5 rounded-xl border border-white/10 p-4">
<div class="flex items-center gap-3 mb-4">
<div class="bg-primary/20 p-2 rounded-full text-primary">
<span class="material-symbols-outlined text-[20px]">location_on</span>
</div>
<div>
<h4 class="font-bold text-sm">Visit Us</h4>
<p class="text-xs text-slate-400">123 Olive Garden Ave, Little Italy</p>
</div>
</div>
<div class="h-32 w-full bg-slate-800 rounded-lg overflow-hidden relative">
<div class="absolute inset-0 bg-cover bg-center grayscale opacity-60" data-alt="Map view of restaurant location" data-location="Rome, Italy" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCrXghEZwzp1U4YkVqXZV2J32sWR8DxlO48lyGadi6PGBExAAJWOyqE2cOVVfqnw_6npPYGk-LJFAC2nGVXT14j9Ax2h6zGQcIszyoNIcbJSD8Pul0BYVvnDVLTzPe6gM645Em146qYRU5qVWZRsRtjSsx6W8mfpvt9l2WwfLz35VLbxfojW-GOl8InwzBhh2lijDs0H0OIBUivJIGavhN5SNXSesGgKUKbYaRXfQMP63c9tfx22qkFiN6ywJuTnqtPwY7LiEhF9fM");'></div>
<div class="absolute inset-0 flex items-center justify-center">
<button class="bg-background-dark/80 backdrop-blur text-white px-4 py-2 rounded-full text-xs font-bold border border-white/20 hover:bg-background-dark transition">Get Directions</button>
</div>
</div>
</div>
</div>
</main>
<!-- Bottom Navigation Bar (iOS Style) -->
<nav class="fixed bottom-0 w-full max-w-md bg-background-dark/95 backdrop-blur-md border-t border-primary/20 pb-safe pt-2 px-6 z-50">
<div class="flex justify-between items-end pb-4">
<button class="flex flex-col items-center gap-1 w-16 text-primary">
<span class="material-symbols-outlined fill-1">home</span>
<span class="text-[10px] font-medium">Home</span>
</button>
<button class="flex flex-col items-center gap-1 w-16 text-slate-400 hover:text-primary transition-colors">
<span class="material-symbols-outlined">restaurant</span>
<span class="text-[10px] font-medium">Menu</span>
</button>
<!-- Floating Action Button effect for Reserve -->
<div class="relative -top-6">
<button class="flex flex-col items-center justify-center size-14 rounded-full bg-primary text-background-dark shadow-lg shadow-primary/30 border-4 border-background-dark transform transition active:scale-95">
<span class="material-symbols-outlined text-[26px]">calendar_month</span>
</button>
</div>
<button class="flex flex-col items-center gap-1 w-16 text-slate-400 hover:text-primary transition-colors">
<span class="material-symbols-outlined">favorite</span>
<span class="text-[10px] font-medium">Saved</span>
</button>
<button class="flex flex-col items-center gap-1 w-16 text-slate-400 hover:text-primary transition-colors">
<span class="material-symbols-outlined">person</span>
<span class="text-[10px] font-medium">Profile</span>
</button>
</div>
<!-- iOS Home Indicator Safe Area -->
<div class="h-1 w-1/3 bg-white/20 rounded-full mx-auto mb-2"></div>
</nav>
</div>
</body></html>
