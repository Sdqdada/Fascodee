<!-- Home - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&amp;family=Manrope:wght@400;600&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "inverse-surface": "#2f3130",
                    "secondary-fixed-dim": "#e9c176",
                    "tertiary": "#000000",
                    "error-container": "#ffdad6",
                    "outline": "#75777d",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-container": "#171c20",
                    "on-error-container": "#93000a",
                    "secondary-fixed": "#ffdea5",
                    "primary": "#000000",
                    "surface-bright": "#faf9f7",
                    "on-surface": "#1a1c1b",
                    "primary-fixed": "#d8e3f9",
                    "surface-tint": "#545f72",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "on-secondary-fixed": "#261900",
                    "secondary-container": "#fed488",
                    "on-secondary-container": "#785a1a",
                    "on-tertiary-fixed": "#171c20",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-container": "#111c2c",
                    "on-primary": "#ffffff",
                    "surface-container": "#efeeec",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-tertiary-container": "#7f848a",
                    "surface": "#faf9f7",
                    "surface-container-high": "#e9e8e6",
                    "surface-dim": "#dadad8",
                    "surface-container-highest": "#e3e2e0",
                    "on-tertiary": "#ffffff",
                    "on-primary-fixed-variant": "#3d4759",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-secondary": "#ffffff",
                    "on-surface-variant": "#44474c",
                    "surface-container-low": "#f4f3f1",
                    "surface-variant": "#e3e2e0",
                    "surface-container-lowest": "#ffffff",
                    "on-error": "#ffffff",
                    "error": "#ba1a1a",
                    "background": "#faf9f7",
                    "on-background": "#1a1c1b",
                    "on-primary-container": "#798498",
                    "on-primary-fixed": "#111c2c",
                    "inverse-on-surface": "#f1f1ef",
                    "on-tertiary-fixed-variant": "#42474c"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "container-max": "1280px",
                    "margin-desktop": "64px",
                    "section-gap": "120px",
                    "base": "8px",
                    "gutter": "24px",
                    "margin-mobile": "20px"
            },
            "fontFamily": {
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "label-md": ["Manrope"],
                    "body-md": ["Manrope"],
                    "body-lg": ["Manrope"],
                    "display-lg": ["Playfair Display"]
            },
            "fontSize": {
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        #nav-drawer { transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1); }
        #nav-drawer.closed { transform: translateX(-100%); }
        #nav-overlay { transition: opacity 0.4s ease; }
        #nav-overlay.closed { opacity: 0; pointer-events: none; }
    </style>
</head>
<body class="bg-surface text-on-surface font-body-md overflow-x-hidden">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-black/40 z-[60] closed" id="nav-overlay" onclick="toggleDrawer()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-4/5 max-w-sm bg-surface z-[70] closed shadow-2xl overflow-y-auto" id="nav-drawer">
<div class="p-margin-mobile flex flex-col min-h-full">
<div class="flex justify-between items-center mb-10">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
<button class="p-2" onclick="toggleDrawer()">
<span class="material-symbols-outlined text-primary">close</span>
</button>
</div>
<nav class="flex flex-col">
<div class="flex flex-col gap-5 pb-8 border-b border-outline-variant/30">
<a class="font-headline-md text-2xl hover:text-secondary transition-colors" href="SCREEN_15">Home</a>
<a class="font-headline-md text-2xl hover:text-secondary transition-colors" href="SCREEN_4">About Us</a>
<a class="font-headline-md text-2xl hover:text-secondary transition-colors" href="SCREEN_9">Collections</a>
<a class="font-headline-md text-2xl hover:text-secondary transition-colors" href="SCREEN_11">Showroom</a>
</div>
<div class="py-8">
<span class="font-label-md text-xs text-secondary tracking-[0.2em] uppercase block mb-6 opacity-70">Material Categories</span>
<div class="flex flex-col gap-5">
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_5">Lighting</a>
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_10">Door Hardware</a>
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_6">Wardrobe Fittings</a>
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_8">Sanitary &amp; Bathrooms</a>
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_2">Kitchen</a>
<a class="font-body-lg text-lg hover:text-secondary transition-colors" href="SCREEN_12">Flooring</a>
</div>
</div>
<div class="pt-8 border-t border-outline-variant/30 mb-12">
<a class="font-headline-md text-2xl hover:text-secondary transition-colors" href="SCREEN_14">Contact Us</a>
</div>
</nav>
<div class="mt-auto pt-10 text-on-surface-variant/40 font-label-md text-[10px] uppercase tracking-widest">
                © 2024 AJILE PREMIUM FINISHES
            </div>
</div>
</aside>
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-surface/90 backdrop-blur-md border-b border-outline-variant flex items-center justify-between px-margin-mobile h-16">
<div class="flex items-center">
<button class="p-2 -ml-2 active:scale-95 transition-transform duration-200" onclick="toggleDrawer()">
<span class="material-symbols-outlined text-primary">menu</span>
</button>
</div>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
<button class="p-2 -mr-2 active:scale-95 transition-transform duration-200">
<span class="material-symbols-outlined text-primary">search</span>
</button>
</header>
<main class="pt-16 pb-24">
<!-- Hero Section -->
<section class="relative w-full h-[85vh] flex flex-col items-center justify-center px-margin-mobile text-center overflow-hidden">
<div class="absolute inset-0 z-0 bg-surface-container-low">
<img class="w-full h-full object-cover opacity-60" data-alt="A macro close-up of a luxurious hand-polished brass door handle against a dark textured mahogany background." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDPRX3PrgT0w8eCB75n4l-xJt9I5FxrYvA5p_z5zi-L3vfJf_L8prHAOn9CuRqDUb7D5aT_I3DLLB40tJEhQvxyasDkvkRMGY6F38aOxWYvZKrw0rE5gSUgLghQc9a6kXGP5RmyJPJ7zKryGQ7s34sHGCtB1wyuTXnAPG3Y0w-hBSF6JlWl5M5_uZmzEJgqU2ApVQIylug3PeAg9fusVq7vfGnxf7WjfyWvGu71jkhlWgjKuEoOcV3jiC_nXFJ2xIeCZRRkB1lFoCmn"/>
</div>
<div class="relative z-10 flex flex-col items-center">
<img alt="AJILE" class="w-48 mb-12 opacity-90" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1MJIPiSExP3H_pktEZkrl2lqVbWI6VFUZQXYENghco-jBCDW4jaq8iKQ1mV5j5umDe1thYPS6I55GpEuqVWJTNmC_VECcNsprPRWJr5gIDhqZwVJ5Lfa7sGhQpxAv1j9T9jDRqc6jEQINlPLSbDuhK2nZFAGzOTOTpacfhnJEgofrNyHz3trgT_k-ZhBexTasB1Z0Qs41tv0Qcv6D1biy5uZGt5t4NS6pn5vFUkrM2Dj2FJyj2VDWWRN7jksSbpgr85a25k6LDr-b"/>
<h1 class="font-headline-lg-mobile text-headline-lg-mobile text-primary mb-6 max-w-sm">Elevating the Art of Living in Abeokuta</h1>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xs mb-10">Curated interior finishes for the most discerning architectural projects.</p>
<div class="flex flex-col w-full gap-4 max-w-xs">
<a class="bg-primary text-on-primary py-4 px-8 font-label-md text-label-md text-center active:scale-95 transition-transform" href="SCREEN_9">EXPLORE COLLECTIONS</a>
<a class="border border-secondary text-secondary py-4 px-8 font-label-md text-label-md text-center hover:bg-secondary/5 active:scale-95 transition-transform" href="SCREEN_14">BOOK CONSULTATION</a>
</div>
</div>
</section>
<!-- Categories Carousel -->
<section class="mt-section-gap">
<div class="px-margin-mobile flex justify-between items-end mb-8">
<div>
<span class="font-label-md text-label-md text-secondary tracking-widest uppercase block mb-2">Portfolio</span>
<h2 class="font-headline-md text-headline-md text-primary">Material Categories</h2>
</div>
<a class="text-secondary font-label-md text-label-md border-b border-secondary pb-1" href="SCREEN_9">VIEW ALL</a>
</div>
<div class="flex overflow-x-auto gap-gutter px-margin-mobile hide-scrollbar snap-x snap-mandatory">
<!-- Door Hardware -->
<a class="flex-shrink-0 w-64 snap-start block group" href="SCREEN_10">
<div class="aspect-[3/4] border border-outline-variant mb-4 overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" data-alt="Sleek modern door hardware" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAySCnnbiXfiDj_DetEAwcQaMZymRQLZH-sSNA1XRO5M8Rk3ucX237D3Wka4myVbnYUBz2QMOh2gPogesK9fMgna3GJjiljzmSa9OnaE0439qDcHMnUkoBbWN-po4HGqu8AmchsS0Sh6t0C7XvHWQPm0QcA5AeBTNqbMiwmspJnTxsKyuoITk33VAZHsmQ-buMuVw3JrKfipgBAdtEl5sPGl1A8pSMEWfHLtHwdvV63TOrFLXRkaM7uCnrVFrG5Ejbzaftr_hUip2XY"/>
</div>
<h3 class="font-label-md text-label-md text-primary uppercase group-hover:text-secondary transition-colors">Door Hardware</h3>
</a>
<!-- Wardrobe -->
<a class="flex-shrink-0 w-64 snap-start block group" href="SCREEN_6">
<div class="aspect-[3/4] border border-outline-variant mb-4 overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" data-alt="Interior of a luxury walk-in closet" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCcBhhBjBTVWRW9l-_HBKlPhcznci9sHk17GfpFTxIkYi5mDALcGMJvfvdRtjmjKSl593o1sSWWEadMCisKcYu5sTd8-j0IsuZmyIYUKZnPTvPkwI-nxeAcJKyCkTpIvzYeIZCKaEPCbG9ffvxPq3fDrozc31Fz0dSu53hbRVtS1Ei5lgIu94oUyZYWl3rgVlaXAKSNmCaU2GORz-ix1m7ms-_efXVUtkt1dg6STwVAYJYZ0IZk_tHnND65l3Wya54DlZIUxy-lEl6G"/>
</div>
<h3 class="font-label-md text-label-md text-primary uppercase group-hover:text-secondary transition-colors">Wardrobe Fittings</h3>
</a>
<!-- Lighting -->
<a class="flex-shrink-0 w-64 snap-start block group" href="SCREEN_5">
<div class="aspect-[3/4] border border-outline-variant mb-4 overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" data-alt="An avant-garde sculptural lighting fixture" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDYtxNqYFPMkjC5mgTaW1RjzdaN6qgnSLfecIIIYvwUqPzVlv7lyyEdxR5PcMW4dH6z3FW76QsAc0AuOrY7EOkOv-93Kdt8IU7Bcru36oVSespyNfWfwg77eUpfm2zLkr5fL3R0ZS5dn-zSfRrsH4IEZLU8DH_TbkrLVXJ-G8AwTrNbrLCd6CFDX0q3DMNEF1lw1Os8Q7wCs0R2ICP_BBPaRDNPN6YYf3z9D_3PTnwyTRBSZieuRuqaAIOO5RQ2DeqG9WPIxHwniJSD"/>
</div>
<h3 class="font-label-md text-label-md text-primary uppercase group-hover:text-secondary transition-colors">Lighting</h3>
</a>
<!-- Kitchen -->
<a class="flex-shrink-0 w-64 snap-start block group" href="SCREEN_2">
<div class="aspect-[3/4] border border-outline-variant mb-4 overflow-hidden">
<img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" data-alt="Close up of a premium kitchen island" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAJunCxY-_Znv476xcbcEMj40BqwD0G6fJFi3s5CZ06p8PS2WJa2-y2DM1p1fjYrkn73AupKZW8YvHeee-7LIBsapYUDh8nYmUZAWIUAvfYKsYcDD2A4VS_GihisGQoYwoQKO94_PQQ-9ORm_tzDtXuOOkE-mKqlRpRChIj0RfDxVcZpQ79S_nIkKczMUfkTPWwdvCHRuQUaJipjTCTiuLH1LxEdAuv9jod5m4cYBXTWG-NyPwPMEGR31AK9TVyqP_RgZVzHqvLVT4F"/>
</div>
<h3 class="font-label-md text-label-md text-primary uppercase group-hover:text-secondary transition-colors">Kitchen</h3>
</a>
</div>
</section>
<!-- About Snippet -->
<section class="mt-section-gap px-margin-mobile py-20 bg-surface-container border-y border-outline-variant">
<div class="max-w-md">
<h2 class="font-headline-md text-headline-md text-primary mb-6">Meticulous Detail. Permanent Quality.</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-8 leading-relaxed">
                    Based in the heart of Abeokuta, AJILE is a boutique supplier of premium finishes. We source materials that don't just occupy space, but transform it into a narrative of luxury and precision.
                </p>
<div class="grid grid-cols-2 gap-8 border-t border-outline-variant pt-8">
<div>
<span class="block font-headline-md text-headline-md text-secondary">15+</span>
<span class="font-label-md text-label-md text-on-surface-variant uppercase">Global Partners</span>
</div>
<div>
<span class="block font-headline-md text-headline-md text-secondary">500+</span>
<span class="font-label-md text-label-md text-on-surface-variant uppercase">Finishes</span>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="mt-section-gap px-margin-mobile text-center">
<div class="bg-primary text-on-primary p-12 relative overflow-hidden">
<div class="relative z-10">
<h2 class="font-headline-md text-headline-md mb-6">Visit Our Showroom</h2>
<p class="font-body-md text-body-md text-on-primary/70 mb-10 max-w-xs mx-auto">Experience the texture and weight of our premium collections firsthand at our Abeokuta gallery.</p>
<a class="bg-secondary text-on-secondary py-4 px-10 font-label-md text-label-md active:scale-95 transition-transform inline-flex items-center gap-2" href="SCREEN_11">
<span>GET DIRECTIONS</span>
<span class="material-symbols-outlined text-sm">arrow_outward</span>
</a>
</div>
<!-- Decorative element -->
<div class="absolute top-0 right-0 w-32 h-32 bg-secondary opacity-20 -mr-16 -mt-16 rotate-45"></div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-section-gap px-margin-mobile border-t border-outline-variant bg-surface-container">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<a class="font-headline-md text-headline-md text-primary mb-4" href="SCREEN_15">AJILE</a>
<div class="flex flex-col gap-4 mb-8">
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">WhatsApp</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Instagram</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Showroom Policy</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Sustainability</a>
</div>
<p class="font-label-md text-label-md text-on-surface-variant/50 uppercase tracking-tighter">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
</div>
</footer>
<!-- BottomNavBar -->
<nav class="fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe md:hidden">
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full font-label-md text-label-md active:scale-90 transition-transform" href="SCREEN_15">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">home_app_logo</span>
<span>Home</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary font-label-md text-label-md active:scale-90 transition-transform" href="SCREEN_9">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span>Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary font-label-md text-label-md active:scale-90 transition-transform" href="SCREEN_11">
<span class="material-symbols-outlined">auto_stories</span>
<span>Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary font-label-md text-label-md active:scale-90 transition-transform" href="SCREEN_14">
<span class="material-symbols-outlined">chat_bubble</span>
<span>Contact</span>
</a>
</nav>
<script>
        function toggleDrawer() {
            const drawer = document.getElementById('nav-drawer');
            const overlay = document.getElementById('nav-overlay');
            drawer.classList.toggle('closed');
            overlay.classList.toggle('closed');
            document.body.classList.toggle('overflow-hidden');
        }
    </script>
</body></html>

<!-- About Us - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&amp;family=Manrope:wght@400;600&amp;display=swap" rel="stylesheet"/>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .backdrop-blur-md {
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        /* Navigation Drawer Animation */
        #nav-drawer {
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.closed {
            transform: translateX(-100%);
        }
        #nav-overlay.closed {
            opacity: 0;
            pointer-events: none;
        }
        #nav-overlay {
            transition: opacity 0.4s ease;
        }
    </style>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "inverse-surface": "#2f3130",
                    "secondary-fixed-dim": "#e9c176",
                    "tertiary": "#000000",
                    "error-container": "#ffdad6",
                    "outline": "#75777d",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-container": "#171c20",
                    "on-error-container": "#93000a",
                    "secondary-fixed": "#ffdea5",
                    "primary": "#000000",
                    "surface-bright": "#faf9f7",
                    "on-surface": "#1a1c1b",
                    "primary-fixed": "#d8e3f9",
                    "surface-tint": "#545f72",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "on-secondary-fixed": "#261900",
                    "secondary-container": "#fed488",
                    "on-secondary-container": "#785a1a",
                    "on-tertiary-fixed": "#171c20",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-container": "#111c2c",
                    "on-primary": "#ffffff",
                    "surface-container": "#efeeec",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-tertiary-container": "#7f848a",
                    "surface": "#faf9f7",
                    "surface-container-high": "#e9e8e6",
                    "surface-dim": "#dadad8",
                    "surface-container-highest": "#e3e2e0",
                    "on-tertiary": "#ffffff",
                    "on-primary-fixed-variant": "#3d4759",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-secondary": "#ffffff",
                    "on-surface-variant": "#44474c",
                    "surface-container-low": "#f4f3f1",
                    "surface-variant": "#e3e2e0",
                    "surface-container-lowest": "#ffffff",
                    "on-error": "#ffffff",
                    "error": "#ba1a1a",
                    "background": "#faf9f7",
                    "on-background": "#1a1c1b",
                    "on-primary-container": "#798498",
                    "on-primary-fixed": "#111c2c",
                    "inverse-on-surface": "#f1f1ef",
                    "on-tertiary-fixed-variant": "#42474c"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "container-max": "1280px",
                    "margin-desktop": "64px",
                    "section-gap": "120px",
                    "base": "8px",
                    "gutter": "24px",
                    "margin-mobile": "20px"
            },
            "fontFamily": {
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "label-md": ["Manrope"],
                    "body-md": ["Manrope"],
                    "body-lg": ["Manrope"],
                    "display-lg": ["Playfair Display"]
            },
            "fontSize": {
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
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
<body class="bg-background text-on-surface">
<!-- Navigation Drawer / Hamburger Menu -->
<div class="fixed inset-0 z-[100] closed" id="nav-overlay" onclick="toggleMenu()">
<div class="absolute inset-0 bg-primary/40 backdrop-blur-sm"></div>
</div>
<aside class="fixed top-0 left-0 h-full w-[85vw] max-w-sm bg-surface z-[101] shadow-2xl closed overflow-y-auto" id="nav-drawer">
<div class="p-margin-mobile border-b border-outline-variant flex justify-between items-center bg-surface-container">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="#">AJILE</a>
<button class="material-symbols-outlined text-primary p-2 active:scale-95" onclick="toggleMenu()">close</button>
</div>
<nav class="flex flex-col py-6">
<a class="px-margin-mobile py-4 font-label-md text-label-md text-primary uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Home</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">About Us</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Collections</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Showroom</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Lighting</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Door Hardware</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Wardrobe Fittings</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Sanitary &amp; Bathrooms</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Kitchen</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant/30 hover:bg-surface-container transition-colors" href="#">Flooring</a>
<a class="px-margin-mobile py-4 font-label-md text-label-md text-secondary uppercase tracking-widest hover:bg-surface-container transition-colors" href="#">Contact Us</a>
</nav>
<div class="mt-auto p-margin-mobile border-t border-outline-variant bg-surface-container-low">
<p class="font-label-md text-[10px] text-on-surface-variant uppercase tracking-tighter mb-4">Abeokuta, Ogun State</p>
<div class="flex gap-4">
<span class="material-symbols-outlined text-secondary">public</span>
<span class="material-symbols-outlined text-secondary">mail</span>
</div>
</div>
</aside>
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md border-b border-outline-variant fixed top-0 w-full z-50 flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-primary cursor-pointer active:scale-95 transition-transform duration-200" onclick="toggleMenu()">menu</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="#">AJILE</a>
</div>
<div class="hidden md:flex gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:bg-surface-container-low transition-colors duration-300 px-2 py-1" href="#">Home</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:bg-surface-container-low transition-colors duration-300 px-2 py-1" href="#">About Us</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:bg-surface-container-low transition-colors duration-300 px-2 py-1" href="#">Collections</a>
</div>
<span class="material-symbols-outlined text-primary cursor-pointer active:scale-95 transition-transform duration-200">search</span>
</header>
<main class="pt-16">
<!-- Hero Section -->
<section class="relative h-[707px] flex items-center justify-start overflow-hidden px-margin-mobile md:px-margin-desktop">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover" data-alt="A high-end luxury interior featuring polished architectural metal and premium wood finishes. The room is flooded with natural morning light through floor-to-ceiling windows, highlighting the meticulous textures of a marble floor. The atmosphere is serene, professional, and sophisticated, reflecting the meticulous curation of AJILE finishes. The color palette centers on alabaster, midnight navy, and soft gold accents." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBJYHLPe8ePmteFBvh_hSUeKt9clWaLnuFlE2g0UJWObvVvjCB7mJbPvTPlNmL35wMzr0jpsOTDCGoI7DtszQZF7nL2gxPB7r7OJajYdaGHqwwsH76iQzTxt4H_CCmGenxH9HST6yf1UeOhtAtg3n7FPsNoOVdNiQCf1uBHhkYE-sFKVBJRTIKWNl4kVB8YLbLrMldD7F7ok8n-Hpki6dZpQusWNDVUOS2lqFzL4lfqIC4mO7guQnWDoyPKgPNOfvVaxCf8n8y8BYPs"/>
<div class="absolute inset-0 bg-primary/20"></div>
</div>
<div class="relative z-10 max-w-2xl">
<h1 class="font-display-lg text-[48px] md:text-display-lg text-on-primary mb-6">Elevating the Architectural Fabric of Abeokuta</h1>
<p class="font-body-lg text-body-lg text-on-primary/90 max-w-lg mb-8">AJILE Premium Finishes bridges the gap between visionary design and tangible reality, providing curated materials for the region's most ambitious projects.</p>
<div class="flex gap-4">
<button class="bg-primary text-on-primary px-8 py-4 font-label-md text-label-md uppercase tracking-wider hover:bg-primary-container transition-colors">Our Vision</button>
</div>
</div>
</section>
<!-- The Story Section -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<div class="md:col-span-5 flex flex-col justify-center">
<span class="font-label-md text-label-md text-secondary uppercase tracking-[0.3em] mb-4">The Foundation</span>
<h2 class="font-headline-lg text-headline-lg mb-8">A Response to Quality</h2>
<p class="font-body-md text-body-md text-on-surface-variant mb-6 leading-relaxed">For years, the burgeoning architectural landscape of Abeokuta faced a persistent challenge: the scarcity of high-caliber finishing materials. Designers and builders were often forced to compromise on their vision due to unreliable supply chains and inconsistent quality.</p>
<p class="font-body-md text-body-md text-on-surface-variant mb-6 leading-relaxed">AJILE was founded as a meticulous response to this market void. We recognized that luxury isn't just about price; it's about the permanence of quality and the reliability of the source.</p>
</div>
<div class="md:col-span-7">
<div class="relative aspect-[4/3] bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700" data-alt="A meticulously organized interior design studio with material samples including exotic stones, premium wood swatches, and architectural metals. Large windows reveal a bright, high-key lighting environment that emphasizes the tactile quality of the materials. The space is clean and minimalist, utilizing a palette of whites, grays, and gold highlights to convey trust and professional expertise." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBQ5N2qh5F1_sdAcBALmVgo5x0gixUi2Zs9V04D98nm2mjlhOicZIqGvqiwkfwG4PiyBgL55u7tb5LlEkdNjZlHcWClbKItNsOuDzRt8FYdB4oT_99QtE4nFVrSnKp2rezFvCeCQiwR1V40eOM7kb-Rf7dAP30rKrcVJTm907Ob1FBD65fXculyZcerFDSQtHU614Tr5zGKFMDdIG55iCg2hRVN0xUQpsjkMdgiZOUttKRrkeyoUm7VpbGWHbyLntvWZlZyAbuZOnOe"/>
<div class="absolute bottom-0 left-0 bg-primary p-8 md:p-12 -translate-x-12 translate-y-12 hidden md:block">
<span class="text-on-primary font-display-lg text-display-lg">01</span>
<p class="text-secondary-fixed-dim font-label-md text-label-md uppercase tracking-widest mt-2">The Market Leader</p>
</div>
</div>
</div>
</div>
</section>
<!-- Competitive Advantage - Bento Grid Style -->
<section class="py-section-gap bg-surface-container-low">
<div class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="text-center mb-16">
<h2 class="font-headline-lg text-headline-lg mb-4">Our Competitive Edge</h2>
<div class="w-24 h-1 bg-secondary mx-auto"></div>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Feature 1 -->
<div class="bg-surface p-10 border border-outline-variant flex flex-col gap-6 hover:border-secondary transition-colors group">
<span class="material-symbols-outlined text-[48px] text-secondary">diamond</span>
<h3 class="font-headline-md text-headline-md">Curated Selection</h3>
<p class="font-body-md text-body-md text-on-surface-variant">We don't just supply; we curate. Every stone, wood, and metal in our showroom has been hand-selected for its aesthetic integrity and structural longevity.</p>
</div>
<!-- Feature 2 -->
<div class="bg-primary p-10 flex flex-col gap-6">
<span class="material-symbols-outlined text-[48px] text-secondary-fixed-dim">shop</span>
<h3 class="font-headline-md text-headline-md text-on-primary">Direct Import</h3>
<p class="font-body-md text-body-md text-on-primary-fixed-variant">By managing our own global supply chain and direct imports, we eliminate the middleman, ensuring both competitive pricing and absolute provenance of our materials.</p>
</div>
<!-- Feature 3 -->
<div class="bg-surface p-10 border border-outline-variant flex flex-col gap-6 hover:border-secondary transition-colors group">
<span class="material-symbols-outlined text-[48px] text-secondary">verified</span>
<h3 class="font-headline-md text-headline-md">Reliable Quality</h3>
<p class="font-body-md text-body-md text-on-surface-variant">Our quality control process is rigorous. From the quarry to your project site, we guarantee that every piece meets the AJILE standard of excellence.</p>
</div>
</div>
</div>
</section>
<!-- Image Trio - Asymmetric Layout -->
<section class="py-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto overflow-hidden">
<div class="flex flex-col md:flex-row gap-gutter items-stretch">
<div class="md:w-1/3 aspect-[3/4] overflow-hidden">
<img class="w-full h-full object-cover" data-alt="Close up of hand-polished premium wood texture with rich dark grains, reflecting soft studio lighting. The image emphasizes the tactile, luxury quality of the finish. The mood is deep and atmospheric, utilizing the brand's primary black and gold tones to showcase meticulous craftsmanship." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAhVynr77WQtzYBvC3GBk_ivuoerE5c9B7ydW1Ec7oui81BdbB3aaqbdTp4xFDU8Xm0jGbT4s7i141wtsJJPZNkF5_zAxxvAPUUCR0-TsCtoUmEo9jo5CpWQgSj_2f9DAqoR_0hMJSTa0vpDsnrB0egcirumDsoxLtKMevyylu8O0Fnl-8emDX2fLTWCtEu5u_SFJQaexrprLOXf7XT2h9Vh_BNxFX-EEbJL89N_BTYoNUvYksISupP-yh_1H3FZqIyGk0_m5MR4Mw8"/>
</div>
<div class="md:w-1/2 aspect-video overflow-hidden self-center relative">
<img class="w-full h-full object-cover" data-alt="A modern living space featuring an accent wall made of AJILE's architectural metal finishes. The lighting is focused and warm, creating high-contrast shadows that define the geometric patterns of the material. The aesthetic is modern editorial, leaning into high-end interior design photography." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCLZLqSYdpHTKi6eWKoJkCJ42wMc5-CxB52xsDYaiSxYyHyLDItgumDA6u0asajXpm_0oxCa8tQCb6ff2Caa_VoGZrVTckoQwuUTZAtghzbVunYZu7O-9esZgzZbqEIH8xuaK9E4aXovytHUnlEsuXQdIzrOSKyTmFy8E14qnuL5EJuaagfSfMZ3ZE0PcJx3tzbSy3Ng3J9zgQeWbWqTCQoDf29L_-EpMrjMfMqp50JtNr5yKpQHeT7wK-xvcFwqZkU13Zcuf46r0F4"/>
<div class="absolute inset-0 border-[24px] border-surface"></div>
</div>
<div class="md:w-1/4 aspect-[2/3] overflow-hidden self-end">
<img class="w-full h-full object-cover" data-alt="A wide-angle view of a prestigious gallery-style showroom in Abeokuta. The floor is covered in high-gloss exotic stone tiles, reflecting the minimalist ceiling lighting. The space feels open, airy, and expensive, communicating the brand's position as a premium provider for local luxury projects." src="https://lh3.googleusercontent.com/aida-public/AB6AXuA5rjOx000GaAQ8FO1BQR8VSUOT5YBIYwBOwWf3NC1swlZQz9KPBZ2TLw7QfZAGAq5IMciqiP-xzhJXuuIK11kDQrE9dxFSlOkji4RRCJCRxWlJ-Y6llK70gfMI9FYv2SHNYTl6HJ_tKjH-krTu4NmSm2V3fUPGFkik0nVmJfjrEwFUTqQWrHT4GObJ-06ZRH-0DJ-b47C-2HmJe21UsPAZAKSTO0aLnWq5pCItUBf7GBbCMiysnUzrei08Xlm3TZkfQqM0BKBs2oma"/>
</div>
</div>
</section>
<!-- Values Section -->
<section class="py-section-gap bg-surface text-center px-margin-mobile md:px-margin-desktop border-t border-outline-variant">
<div class="max-w-3xl mx-auto">
<span class="font-label-md text-label-md text-secondary uppercase tracking-[0.4em] block mb-6">Our Commitment</span>
<h2 class="font-display-lg text-display-lg mb-10 italic">"Quality is not an act, it is a habit."</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant italic mb-12">We are dedicated to supporting the architects and dreamers of Ogun State, ensuring that the finishes on their buildings are as lasting as the legacies they create.</p>
<div class="flex flex-wrap justify-center gap-12">
<div class="flex flex-col items-center">
<span class="font-headline-lg text-headline-lg text-primary">150+</span>
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest mt-2">Projects Completed</span>
</div>
<div class="flex flex-col items-center">
<span class="font-headline-lg text-headline-lg text-primary">12+</span>
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest mt-2">Material Origins</span>
</div>
<div class="flex flex-col items-center">
<span class="font-headline-lg text-headline-lg text-primary">0</span>
<span class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest mt-2">Quality Compromises</span>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="relative py-section-gap px-margin-mobile md:px-margin-desktop overflow-hidden bg-primary">
<div class="max-w-container-max mx-auto flex flex-col md:flex-row items-center justify-between gap-12 relative z-10">
<div class="text-left">
<h2 class="font-headline-lg text-headline-lg text-on-primary mb-4">Ready to refine your vision?</h2>
<p class="font-body-md text-body-md text-on-primary/70">Visit our showroom for a private consultation with our finish specialists.</p>
</div>
<button class="border border-secondary text-secondary-fixed-dim px-12 py-5 font-label-md text-label-md uppercase tracking-widest hover:bg-secondary/10 transition-colors">Book a Consultation</button>
</div>
<!-- Decorative Subtle Pattern -->
<div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: radial-gradient(#775a19 1px, transparent 1px); background-size: 40px 40px;"></div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container w-full py-section-gap px-margin-mobile border-t border-outline-variant mt-section-gap">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<div class="w-full flex flex-col md:flex-row justify-between items-start gap-12">
<div>
<a class="font-headline-md text-headline-md text-primary mb-4 uppercase tracking-[0.2em] block" href="#">AJILE</a>
<p class="font-body-md text-body-md text-on-surface-variant max-w-sm">Premium finishes curated for the architectural elite. Defining the standards of luxury living in West Africa.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 gap-12">
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase">Contact</span>
<span class="font-body-md text-body-md text-on-surface-variant hover:text-secondary cursor-pointer">WhatsApp</span>
<span class="font-body-md text-body-md text-on-surface-variant hover:text-secondary cursor-pointer">Instagram</span>
</div>
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase">Legal</span>
<span class="font-body-md text-body-md text-on-surface-variant hover:text-secondary cursor-pointer">Showroom Policy</span>
<span class="font-body-md text-body-md text-on-surface-variant hover:text-secondary cursor-pointer">Sustainability</span>
</div>
</div>
</div>
<div class="w-full border-t border-outline-variant pt-8 mt-8 flex flex-col md:flex-row justify-between items-center gap-4">
<p class="font-body-md text-body-md text-on-surface-variant">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
<div class="flex gap-6">
<span class="material-symbols-outlined text-secondary hover:opacity-80 transition-opacity cursor-pointer">public</span>
<span class="material-symbols-outlined text-secondary hover:opacity-80 transition-opacity cursor-pointer">mail</span>
</div>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile only) -->
<nav class="md:hidden bg-surface border-t border-outline-variant fixed bottom-0 w-full z-50 flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined">home_app_logo</span>
<span class="font-label-md text-label-md">Home</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined">info</span>
<span class="font-label-md text-label-md">About</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md text-label-md">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-label-md">Contact</span>
</a>
</nav>
<script>
    function toggleMenu() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('nav-overlay');
        drawer.classList.toggle('closed');
        overlay.classList.toggle('closed');
        
        // Prevent scrolling when menu is open
        if (!drawer.classList.contains('closed')) {
            document.body.style.overflow = 'hidden';
        } else {
            document.body.style.overflow = '';
        }
    }
</script>
</body></html>

<!-- Collections - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Collections Overview | AJILE Premium Finishes</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&amp;family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary-fixed-dim": "#bcc7dd",
                        "on-primary-fixed-variant": "#3d4759",
                        "on-secondary-fixed-variant": "#5d4201",
                        "inverse-surface": "#2f3130",
                        "inverse-on-surface": "#f1f1ef",
                        "secondary": "#775a19",
                        "surface-container-high": "#e9e8e6",
                        "error-container": "#ffdad6",
                        "outline-variant": "#c5c6cd",
                        "surface-container-lowest": "#ffffff",
                        "on-primary-fixed": "#111c2c",
                        "tertiary": "#000000",
                        "tertiary-fixed-dim": "#c2c7cd",
                        "primary": "#000000",
                        "surface-variant": "#e3e20e",
                        "surface": "#faf9f7",
                        "primary-fixed": "#d8e3f9",
                        "surface-container-low": "#f4f3f1",
                        "secondary-fixed-dim": "#e9c176",
                        "on-background": "#1a1c1b",
                        "on-tertiary-container": "#7f848a",
                        "tertiary-fixed": "#dfe3e9",
                        "inverse-primary": "#bcc7dd",
                        "on-primary-container": "#798498",
                        "secondary-fixed": "#ffdea5",
                        "surface-container": "#efeeec",
                        "on-tertiary-fixed-variant": "#42474c",
                        "tertiary-container": "#171c20",
                        "on-error": "#ffffff",
                        "error": "#ba1a1a",
                        "on-primary": "#ffffff",
                        "surface-tint": "#545f72",
                        "on-error-container": "#93000a",
                        "background": "#faf9f7",
                        "on-tertiary-fixed": "#171c20",
                        "on-tertiary": "#ffffff",
                        "on-surface-variant": "#44474c",
                        "on-secondary": "#ffffff",
                        "secondary-container": "#fed488",
                        "primary-container": "#111c2c",
                        "on-secondary-container": "#785a1a",
                        "surface-bright": "#faf9f7",
                        "on-secondary-fixed": "#261900",
                        "on-surface": "#1a1c1b",
                        "surface-container-highest": "#e3e2e0",
                        "surface-dim": "#dadad8",
                        "outline": "#75777d"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "gutter": "24px",
                        "base": "8px",
                        "margin-mobile": "20px",
                        "section-gap": "120px",
                        "container-max": "1280px"
                    },
                    "fontFamily": {
                        "body-lg": ["Manrope"],
                        "headline-lg-mobile": ["Playfair Display"],
                        "body-md": ["Manrope"],
                        "label-md": ["Manrope"],
                        "headline-md": ["Playfair Display"],
                        "headline-lg": ["Playfair Display"],
                        "display-lg": ["Playfair Display"]
                    },
                    "fontSize": {
                        "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                        "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                        "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                        "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .active-dot::after {
            content: '';
            display: block;
            width: 4px;
            height: 4px;
            background-color: #775a19;
            border-radius: 50%;
            margin: 4px auto 0;
        }
        body {
            min-height: max(884px, 100dvh);
        }
        /* Drawer animation */
        #navigation-drawer {
            transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #navigation-drawer.closed {
            transform: translateX(-100%);
        }
        #drawer-overlay {
            transition: opacity 0.3s ease;
        }
        #drawer-overlay.closed {
            opacity: 0;
            pointer-events: none;
        }
    </style>
</head>
<body class="bg-background text-on-surface selection:bg-secondary-container overflow-x-hidden">
<!-- Drawer Overlay -->
<div class="fixed inset-0 bg-black/50 z-[60] closed" id="drawer-overlay" onclick="toggleDrawer()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-[85%] max-w-[360px] bg-surface z-[70] closed shadow-2xl flex flex-col" id="navigation-drawer">
<div class="p-margin-mobile border-b border-outline-variant flex justify-between items-center">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
<button class="material-symbols-outlined text-primary p-2" onclick="toggleDrawer()">close</button>
</div>
<nav class="flex-1 overflow-y-auto py-8 px-margin-mobile">
<div class="space-y-1">
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_15">Home</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="#">About Us</a>
<a class="block py-3 px-2 font-body-md text-secondary font-semibold rounded bg-surface-container-low" href="#">Collections</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="#">Showroom</a>
<div class="pt-4 pb-2">
<h4 class="font-label-md text-[11px] text-secondary uppercase tracking-[0.2em] px-2 mb-2">Category Collections</h4>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_5">Lighting</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_10">Door Hardware</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_6">Wardrobe Fittings</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_8">Sanitary &amp; Bathrooms</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_2">Kitchen</a>
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_12">Flooring</a>
</div>
<div class="border-t border-outline-variant mt-4 pt-4">
<a class="block py-3 px-2 font-body-md hover:bg-surface-container-low transition-colors rounded" href="SCREEN_14">Contact Us</a>
</div>
</div>
</nav>
</aside>
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md border-b border-outline-variant fixed top-0 w-full z-50 flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-primary active:scale-95 transition-transform duration-200 p-2 hover:bg-surface-container-low" data-icon="menu" onclick="toggleDrawer()">menu</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
</div>
<div class="hidden md:flex gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="SCREEN_15">Home</a>
<a class="font-label-md text-label-md text-secondary active-dot" href="#">Collections</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="SCREEN_14">Contact</a>
</div>
<div class="flex items-center gap-2">
<button class="material-symbols-outlined text-primary active:scale-95 transition-transform duration-200 p-2 hover:bg-surface-container-low" data-icon="search">search</button>
</div>
</header>
<!-- Main Content Canvas -->
<main class="pt-32 pb-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<!-- Hero & Search -->
<section class="mb-section-gap">
<div class="max-w-3xl">
<h1 class="font-headline-lg text-headline-lg-mobile md:text-headline-lg mb-gutter text-primary">Artisanal Collections</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-12 max-w-2xl">
                Discover a curated inventory of premium finishes and architectural systems designed for the meticulous professional and the visionary homeowner.
            </p>
<!-- Search Component -->
<div class="relative group">
<input class="w-full bg-transparent border-b border-outline py-4 font-body-md text-body-md focus:outline-none focus:border-secondary transition-colors placeholder:text-outline-variant" placeholder="Search for 'PPR fittings' or 'Rainfall showers'..." type="text"/>
<button class="absolute right-0 top-1/2 -translate-y-1/2 material-symbols-outlined text-secondary" data-icon="arrow_forward">arrow_forward</button>
</div>
</div>
</section>
<!-- Collections Bento Grid -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Door Hardware -->
<a class="md:col-span-8 group cursor-pointer block" href="SCREEN_10">
<div class="relative overflow-hidden aspect-[16/9] mb-4 bg-surface-container">
<img alt="Brushed gold door handle" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuChAMSJnyCYl0dtMhuSxFZj3Sb7vTKQmWuz3tDxq7sEenKkVL0h_I6Iv7WJJbEwu7P6tSwoDdyaPGUHFlXGEdKSRG0aENPPSLxTE1DfgYXQqQViaf_Ia32Ektka3E1FndHGXk_JFVajEjrMW6WIFmrrf3uAfnLnWBZnjT3oXfbaHr9CYg4wQAIxG1DJ8QE5r9lCUsdrT8Tjp0JZUFz_QEAnVpGXKyCx0OKLjj3GLT7viBRHlPySLlqEG7mQwWN-Khbeau5_Z5gXWrIj"/>
<div class="absolute inset-0 border border-white/10"></div>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Door Hardware</h3>
<p class="font-label-md text-label-md text-secondary mt-1">LEVERS, PULLS &amp; SECURITY SYSTEMS</p>
</a>
<!-- Wardrobe Fittings -->
<a class="md:col-span-4 group cursor-pointer block" href="SCREEN_6">
<div class="relative overflow-hidden aspect-square mb-4 bg-surface-container">
<img alt="Luxury walk-in closet" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBlPCxmh0izx12b98I3EGB93God67SynmfKJlEKtR0vMVb1NMxxJCV0k82vf1vY7N15GPVbE4us5JK74BJ0Dr3mEWdrVhcZjvlc_8lwTaCSTOFHKI6nEcW_lFo9qCx3neY_Ta9Ttx8mFf0GeOdMrlTsCUvuAGapjI4upaPd3_j-fpL0OA45FOpVJukzuYtJ6nKAoupVHQS6YgEW0pJlz4P5lZ1bMkc1K3D4Ypq8mjnp6g1Sm0bquBeaviupH4csL8Vbc5G0lZknfq7C"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Wardrobe Fittings</h3>
<p class="font-label-md text-label-md text-secondary mt-1">ORGANIZATIONAL SYSTEMS</p>
</a>
<!-- Bathroom & Sanitary -->
<a class="md:col-span-4 group cursor-pointer block" href="SCREEN_8">
<div class="relative overflow-hidden aspect-square mb-4 bg-surface-container">
<img alt="Matte black shower head" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDSA7PeBHntbAAZFJyY5h0JeK4RTCvTn0xgv9OoPHZINPlyrbg48nsMWnPpjkyUYUCK_AE9T35hq8f7tg4veLYxAlIO3V7A5AUbI3Y9e06w2VzmqQ0mkBkMROiQe0pFlxN5j2XSAEeWqERHAJFLfIaH-5daBYpy7GWeNoOas-NYJN01WL6skc4sqm40BAc-aud453hXZFP9_jN_yJiqCYRYH8OqK6mL9jsb4-78YKQg9RRvsYgp307wyplYDrBMPN7O1o9Ozeg5gaus"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Bathroom &amp; Sanitary</h3>
<p class="font-label-md text-label-md text-secondary mt-1">FIXTURES &amp; PPR SYSTEMS</p>
</a>
<!-- Kitchen Systems -->
<a class="md:col-span-4 group cursor-pointer block" href="SCREEN_2">
<div class="relative overflow-hidden aspect-square mb-4 bg-surface-container">
<img alt="Chrome kitchen faucet" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCLZl37koWlE0Vqbx1Y9-C9X0VM3KRKDS2FLz-hzQL0PN09kYJWr4spZ_Edxs74EHQ_pGzkJOJduO3wiXDmN8mqYeJNeT6efLo8lgg403x7WvnmnzLcEi5TIDffGQQ6NQeTWDax3axpdDPQ9CwiSkn3XPHxiEJgmRGdF1Jy__zy4oc74ELBF-kOv_eABBPK9FKSFV4Euayk5vMi3rIIowjfYqWFr43KFF3K3dF67BN0EKOBVKb5I4jeGNGxC4ZpI6h0fny9cu32I8UC"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Kitchen Systems</h3>
<p class="font-label-md text-label-md text-secondary mt-1">CULINARY HARDWARE</p>
</a>
<!-- Lighting -->
<a class="md:col-span-4 group cursor-pointer block" href="SCREEN_5">
<div class="relative overflow-hidden aspect-square mb-4 bg-surface-container">
<img alt="Designer pendant lights" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBAPYIQLOSUjZ54MJkXsTREumxgRWGdItoh8GTdRei8yqLWAsFVqTZxFmvBd1x0PqqYYeGFs-7OgV3SODvvOCi6tiVZzmAQZtNUsXTi6_PHxFwM4Tg_opuEFpqeP1ojxsxO5M11gQ4eDOu_DDKTi8IgeDB5Ewi3g_uSaVPVqTBqTELV5Sqzzr_V8rrsCQK95xq3YBgxh0XNLSfUf1tkBO8Avgx0o94vdCrVFNgvR0kUQnvrE-TL-_zn_8weFdHqrAz_hfo8Ve7238rf"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Lighting</h3>
<p class="font-label-md text-label-md text-secondary mt-1">LUMINAIRES &amp; AUTOMATION</p>
</a>
<!-- Flooring -->
<a class="md:col-span-6 group cursor-pointer block" href="SCREEN_12">
<div class="relative overflow-hidden aspect-[4/3] mb-4 bg-surface-container">
<img alt="Premium oak flooring" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAswPZQI-2hr-U3ziI1hYZND7qkspxfX8RMazvfvc5uKf6u35t1v6cjxyZ0J1-IuJWs6mDdxpS9h2cCYpmpyHU9Y7KN5JpsYWXUqDC8LJsOpFGmRPp7Y7Py81E6JFHb0wcamgC5zg67PIfkmn5WvNmvWjmUQhb_f4Y8CJNRAtReBa4pnTLFlz-Jw9g5lT2CEEnDRKZNqk6tq-SP2hRJ8a-b7y5xGs1YD_ltxXRY_0O11Ogkm-BWPB_hbjH-1j_x2tmTVD6seGPXJF_a"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Flooring</h3>
<p class="font-label-md text-label-md text-secondary mt-1">HARDWOOD &amp; ENGINEERED PLANK</p>
</a>
<!-- Wall & Ceiling Panels -->
<a class="md:col-span-6 group cursor-pointer block" href="SCREEN_9">
<div class="relative overflow-hidden aspect-[4/3] mb-4 bg-surface-container">
<img alt="Fluted wood panels" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuANi6lOq4USYcQ9sJVhZ-rounJqxOFqHQoWsKR3r2Mtmp_yeskK7UIf20N747tXR-cR4lgdP8HqjGizTnczSOBUoRKU5LuysDQN1tPy91VpdkZyNbNxx01vZAPzB2WVU-fIiJ5-4P-OcOUKctzPAXardEYaFh2rGJYC1P2tr7l3oEAS8I99QFAj-Pz5aOiqhhWfsaPxq7y--kt99_H8HsG2qbmUQTI8MVmku9KBDGjOarGsMHcm6zA10dLuKYuTZ3xmX1VLaAwmi_Ga"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary">Wall &amp; Ceiling Panels</h3>
<p class="font-label-md text-label-md text-secondary mt-1">ARCHITECTURAL SURFACES</p>
</a>
<!-- Smart Home -->
<a class="md:col-span-8 group cursor-pointer block" href="#">
<div class="bg-primary p-12 flex flex-col justify-between h-full min-h-[400px] hover:bg-black/90 transition-colors">
<div>
<span class="font-label-md text-label-md text-secondary-fixed-dim uppercase tracking-widest">Connected Living</span>
<h3 class="font-headline-lg text-headline-lg text-white mt-4 mb-6">Smart Home Solutions</h3>
<p class="font-body-md text-body-md text-primary-fixed-dim max-w-md">Seamlessly integrate technology into your architecture with our curated range of invisible controls and intelligent systems.</p>
</div>
<div class="flex items-center gap-4 text-secondary-fixed-dim mt-8">
<span class="font-label-md text-label-md">EXPLORE SYSTEMS</span>
<span class="material-symbols-outlined" data-icon="arrow_right_alt">arrow_right_alt</span>
</div>
</div>
</a>
<!-- Tiles (Future Category) -->
<div class="md:col-span-4 group border border-outline-variant flex flex-col items-center justify-center p-12 text-center">
<span class="material-symbols-outlined text-outline-variant text-4xl mb-4" data-icon="texture">texture</span>
<h3 class="font-headline-md text-headline-md text-outline">Tiles</h3>
<p class="font-label-md text-label-md text-secondary mt-2 italic">ARRIVING WINTER 2024</p>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container border-t border-outline-variant w-full py-section-gap px-margin-mobile">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<span class="font-headline-md text-headline-md text-primary tracking-[0.2em] uppercase mb-4">AJILE</span>
<div class="grid grid-cols-2 md:grid-cols-4 gap-12 w-full">
<div class="flex flex-col gap-4">
<h4 class="font-label-md text-label-md text-primary">CONNECT</h4>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">WhatsApp</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Instagram</a>
</div>
<div class="flex flex-col gap-4">
<h4 class="font-label-md text-label-md text-primary">RESOURCES</h4>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Showroom Policy</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Sustainability</a>
</div>
<div class="md:col-span-2 flex flex-col md:items-end justify-end">
<p class="font-body-md text-body-md text-on-surface-variant uppercase tracking-wider">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
</div>
</div>
</div>
</footer>
<!-- Mobile BottomNavBar -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_15">
<span class="material-symbols-outlined" data-icon="home_app_logo">home_app_logo</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="#">
<span class="material-symbols-outlined" data-icon="auto_awesome_motion">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="#">
<span class="material-symbols-outlined" data-icon="auto_stories">auto_stories</span>
<span class="font-label-md text-[10px]">Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_14">
<span class="material-symbols-outlined" data-icon="chat_bubble">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
<script>
    function toggleDrawer() {
        const drawer = document.getElementById('navigation-drawer');
        const overlay = document.getElementById('drawer-overlay');
        const body = document.body;
        
        drawer.classList.toggle('closed');
        overlay.classList.toggle('closed');
        
        if (!drawer.classList.contains('closed')) {
            body.style.overflow = 'hidden';
        } else {
            body.style.overflow = '';
        }
    }
</script>
</body></html>

<!-- Lighting - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary": "#000000",
                    "on-surface": "#1a1c1b",
                    "on-secondary-container": "#785a1a",
                    "on-secondary": "#ffffff",
                    "on-primary": "#ffffff",
                    "on-background": "#1a1c1b",
                    "on-tertiary-container": "#7f848a",
                    "on-secondary-fixed": "#261900",
                    "tertiary": "#000000",
                    "secondary-fixed-dim": "#e9c176",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "surface-container-high": "#e9e8e6",
                    "primary-fixed": "#d8e3f9",
                    "surface-container-low": "#f4f3f1",
                    "inverse-on-surface": "#f1f1ef",
                    "primary-container": "#111c2c",
                    "on-surface-variant": "#44474c",
                    "secondary-fixed": "#ffdea5",
                    "tertiary-container": "#171c20",
                    "background": "#faf9f7",
                    "surface-variant": "#e3e2e0",
                    "secondary-container": "#fed488",
                    "on-primary-fixed": "#111c2c",
                    "error-container": "#ffdad6",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-primary-container": "#798498",
                    "inverse-surface": "#2f3130",
                    "surface-container-highest": "#e3e2e0",
                    "on-primary-fixed-variant": "#3d4759",
                    "error": "#ba1a1a",
                    "on-tertiary-fixed-variant": "#42474c",
                    "surface-tint": "#545f72",
                    "surface-container-lowest": "#ffffff",
                    "surface-bright": "#faf9f7",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-error-container": "#93000a",
                    "surface-dim": "#dadad8",
                    "surface-container": "#efeeec",
                    "on-tertiary-fixed": "#171c20",
                    "surface": "#faf9f7",
                    "on-error": "#ffffff",
                    "on-tertiary": "#ffffff",
                    "outline": "#75777d"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "section-gap": "120px",
                    "margin-mobile": "20px",
                    "margin-desktop": "64px",
                    "container-max": "1280px",
                    "base": "8px",
                    "gutter": "24px"
            },
            "fontFamily": {
                    "label-md": ["Manrope"],
                    "display-lg": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "body-lg": ["Manrope"],
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "body-md": ["Manrope"]
            },
            "fontSize": {
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        
        /* Navigation Drawer Logic */
        #nav-drawer {
            transform: translateX(-100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #nav-overlay {
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.4s ease-in-out;
        }
        #nav-overlay.open {
            opacity: 1;
            pointer-events: auto;
        }
    </style>
<style>
        body {
          min-height: max(884px, 100dvh);
        }
    </style>
</head>
<body class="bg-background text-on-surface selection:bg-secondary-container selection:text-on-secondary-container">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-black/40 z-[60]" id="nav-overlay" onclick="toggleNav()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-[320px] bg-surface z-[70] shadow-2xl overflow-y-auto hide-scrollbar flex flex-col" id="nav-drawer">
<div class="sticky top-0 bg-surface flex items-center justify-between p-6 border-b border-outline-variant/30 z-10">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="index.html">AJILE</a>
<button class="material-symbols-outlined p-2 hover:bg-surface-container-low rounded-full transition-colors" onclick="toggleNav()">close</button>
</div>
<div class="p-6 flex flex-col gap-8">
<nav class="flex flex-col">
<a class="py-3 font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="index.html">Home</a>
<a class="py-3 font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="#">About Us</a>
<a class="py-3 font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="collections.html">Collections</a>
<a class="py-3 font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="#">Showroom</a>
</nav>
<div class="pt-8 border-t border-outline-variant">
<h4 class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest mb-4">Product Categories</h4>
<div class="flex flex-col">
<a class="py-2 font-body-lg text-body-lg text-secondary flex items-center gap-2" href="#">
<span class="w-1.5 h-1.5 bg-secondary rounded-full"></span>
                        Lighting
                    </a>
<a class="py-2 font-body-lg text-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Door Hardware</a>
<a class="py-2 font-body-lg text-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Wardrobe Fittings</a>
<a class="py-2 font-body-lg text-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Sanitary &amp; Bathrooms</a>
<a class="py-2 font-body-lg text-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Kitchen</a>
<a class="py-2 font-body-lg text-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Flooring</a>
</div>
</div>
<div class="pt-8 border-t border-outline-variant pb-12">
<a class="py-3 font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="contact.html">Contact Us</a>
</div>
</div>
</aside>
<script>
        function toggleNav() {
            document.getElementById('nav-drawer').classList.toggle('open');
            document.getElementById('nav-overlay').classList.toggle('open');
        }
    </script>
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md fixed top-0 w-full z-50 border-b border-outline-variant">
<div class="flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full max-w-container-max mx-auto">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-primary hover:bg-surface-container-low transition-colors duration-300 p-2 rounded-full active:scale-95" onclick="toggleNav()">menu</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="index.html">AJILE</a>
</div>
<div class="hidden md:flex items-center gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Exotic Stone</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Premium Wood</a>
<a class="font-label-md text-label-md text-secondary border-b border-secondary pb-1" href="#">Lighting</a>
</div>
<button class="material-symbols-outlined text-primary hover:bg-surface-container-low transition-colors duration-300 p-2 rounded-full active:scale-95">search</button>
</div>
</header>
<main class="pt-24 pb-section-gap">
<!-- Breadcrumb / Back Link -->
<div class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop mb-8">
<a class="inline-flex items-center gap-2 font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors group" href="collections.html">
<span class="material-symbols-outlined text-[18px] group-hover:-translate-x-1 transition-transform">arrow_back</span>
                Back to Collections
            </a>
</div>
<!-- Hero Section -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop mb-section-gap">
<div class="flex flex-col md:flex-row gap-gutter items-end">
<div class="md:w-1/2">
<h1 class="font-display-lg text-display-lg md:text-display-lg text-primary mb-6">Sculpted Light</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-lg">
                        Our lighting collection bridges the gap between functional illumination and architectural art. Each piece is meticulously hand-finished using premium metals and artisan glass.
                    </p>
</div>
<div class="md:w-1/2 flex justify-end gap-4 overflow-x-auto hide-scrollbar pb-4">
<span class="px-6 py-2 border border-outline font-label-md text-label-md text-primary whitespace-nowrap cursor-pointer">Chandeliers</span>
<span class="px-6 py-2 border border-outline-variant font-label-md text-label-md text-on-surface-variant whitespace-nowrap cursor-pointer">Pendant Lights</span>
<span class="px-6 py-2 border border-outline-variant font-label-md text-label-md text-on-surface-variant whitespace-nowrap cursor-pointer">Architectural LED</span>
</div>
</div>
</section>
<!-- Featured Products Bento Grid -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Modern Gold Chandelier (Large Feature) -->
<div class="md:col-span-8 group cursor-pointer">
<div class="relative aspect-[16/9] overflow-hidden bg-surface-container mb-6 border border-outline-variant/30">
<img alt="A grand Modern Gold Chandelier" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCpthWEYnBdiaIiCbQH7mymSulNv1myufAf-nfl6ZI7wSYPmRm__rv3ywDbd0pKtoft5gPZ82bESZo6c8UyC4D1pjvrPcRzd6_xGtFLLeMxhKMFl69EGZ6d2Zqn1foGiL6y7WH5pESrW7NFThMMdqcjXX2BQydytoCe8ShtDH-okwHKZmtZFqOj8T5hVbHJXsefYS2E5iloJVyzcB1hkr8pw92pONEDVx6IGgcRZbLrwqvtwTOacbsKb-0poyw1M23DtGJIFjdMc-Un"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary font-label-md text-label-md px-4 py-1">FEATURED</span>
</div>
</div>
<div class="flex justify-between items-start">
<div>
<h3 class="font-headline-md text-headline-md text-primary">Modern Gold Chandelier</h3>
<p class="font-label-md text-label-md text-secondary mt-1">24K Hand-Brushed Finish</p>
</div>
<span class="font-headline-md text-headline-md text-primary">$4,200</span>
</div>
</div>
<!-- Smoky Glass Pendant -->
<div class="md:col-span-4 flex flex-col justify-between group cursor-pointer">
<div class="relative aspect-square overflow-hidden bg-surface-container mb-6 border border-outline-variant/30">
<img alt="A singular Smoky Glass Pendant" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCmaOC1T_iNCnFHpVc7JQEoNQtPipJqi1j0mQgAwUVcUli1HXd-aSdwv0njeTXEwMjljgjSme9QcKONkfgGVkjzjXHimiPhFDFD2v-wQ-GohrZzgXYB9S_Dzobn4xtEgdI7ODqBT9HSxYZ1E9DcB0Rv6TQM_HoGX9LMAQMjrVeSEvLsJ8kR2QM0XFW_HDTLMoSPUH2nnkRWL9Jebq2c_I9IBLo4uqwibrPoAWYxe5pjZhK8b9YmqevemAyq03A2KP1N7BYLm2D0-zcA"/>
</div>
<div>
<h3 class="font-headline-md text-headline-md text-primary">Smoky Glass Pendant</h3>
<p class="font-label-md text-label-md text-on-surface-variant mt-1">Hand-Blown Murano Glass</p>
<div class="mt-6 flex items-center justify-between">
<span class="font-headline-md text-headline-md text-primary">$850</span>
<button class="font-label-md text-label-md text-secondary border border-secondary px-6 py-2 hover:bg-secondary/5 transition-colors">VIEW DETAILS</button>
</div>
</div>
</div>
<!-- Recessed Linear LED (Wide Banner style) -->
<div class="md:col-span-12 mt-12 grid grid-cols-1 md:grid-cols-2 gap-gutter items-center bg-surface-container p-8 md:p-12">
<div class="relative aspect-video overflow-hidden border border-outline-variant/30">
<img alt="An ultra-modern interior hallway featuring Recessed Linear LED" class="w-full h-full object-cover transition-transform duration-700 hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDF7BIhY9KFB_IDtlyCLZHTSyDJ81lO5vWN8t6YpgH5JJRJiYmwSBg4JkfN8XZ6Wl9OFrctWY7DfyGgapMTDZUBXd_P_xOFPF2YBcupk5jRvvZwpp2UYeQ8naS9FLhtv6yCSYkAVHtgLozuZ0rKHY2R8Gm8y8pcyefJFS54VGkLedl15kzSaSvNArqAFRfCbA2ax45ee3bPebqRrdFyQxj6WOD6bZN34mrVcm5qXDRwPaoQ1BlECFIa_RnyanHiNpMd1MKiYixup3vv"/>
</div>
<div class="md:pl-12">
<span class="font-label-md text-label-md text-secondary tracking-widest uppercase mb-4 block">Architectural Systems</span>
<h3 class="font-display-lg text-[40px] leading-tight text-primary mb-6">Recessed Linear LED</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-8">
                            Engineered for seamless integration, our linear systems provide continuous, flicker-free illumination that disappears into the architecture.
                        </p>
<button class="bg-primary text-on-primary font-label-md text-label-md px-10 py-4 hover:opacity-90 transition-opacity">REQUEST SPECIFICATION</button>
</div>
</div>
</div>
</section>
<!-- Categories Section -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop mt-section-gap">
<div class="border-t border-outline-variant pt-16">
<h2 class="font-headline-lg text-headline-lg text-primary mb-12">Browse by Category</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<div class="flex flex-col gap-4 group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-highest border border-outline-variant/20">
<img alt="Luxury chandeliers" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBP11XmhUAdCXWvRTS568nPQZYYL3tQRDXPuzfj-3M7nNMq1GQfwmVkCODAj3dckj9MAE_cn7AidWhreQSKZhH8R-u-E1Z6a0-qzUUxDFnFHIoJx7FDeu5sWLq0fbLySFiRR8q3jZpH0WHsDXWu-CZWf-LFXuQpgCh3Ic7srA15upwVvOW6nijHRYmFfsGeZRdQFadZIaRxJ9pvQaeeKMZMflSRKkhaUMa76aayU9YLuqjzNEuqKwuiaNUuvb3UD1uonRALwZl6RoW_"/>
</div>
<div class="flex justify-between items-center">
<span class="font-headline-md text-headline-md">Chandeliers</span>
<span class="material-symbols-outlined text-secondary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
<div class="flex flex-col gap-4 group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-highest border border-outline-variant/20">
<img alt="Minimalist pendant lights" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCI8lDkZYMldmp4q-uK6maNhOYtZ1OddAYuxzGu6QDzUmG7kiVQMsZaTjZ9mBB8kbPqvzTTgrSWBMpsNztKn8XcH7_Zysrj0kE9YshIYlnk_mwDPsD8dW-KgM3iJNc_Y1agQDcH73KW7304oHg8TCbQy_cOoiXhGCl8ELqIrrNUD7_nSGfIWBgVOWzumFNosMbGOTPr_gwhEPD7ONSyTAwky4K6JdbquQ4lcsxtYzRzMtLUgoFsvCGWkJcZ66Jj8o32DPMdpD96bxC_"/>
</div>
<div class="flex justify-between items-center">
<span class="font-headline-md text-headline-md">Pendant Lights</span>
<span class="material-symbols-outlined text-secondary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
<div class="flex flex-col gap-4 group cursor-pointer">
<div class="aspect-[4/5] overflow-hidden bg-surface-container-highest border border-outline-variant/20">
<img alt="Architectural LED installation" class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBaiD5sFq8udzi-GK0h_m4_dMEDXRdTtGIaTqtpU58Nnj4eO8aefbkaprlN8xOgQm7J1OITcZfTEmEFZI_hlepNvpewOOPSu98wVdHVFgISF8GIvN_THNEl7YyJl-96Dp1tVMqLeeFrNCzDTfWeIWiWjpDZEJNN-XTtqnfdf523KJNS4lpt-hZy14BS8BUb-O-r8KVnOM00K4L9zEzr-d7rlC8phz8vOgBMCrDXOntvyIwgsaOORJbn_IythhCpZ_FB1IakLUIP_bJ0"/>
</div>
<div class="flex justify-between items-center">
<span class="font-headline-md text-headline-md">Architectural LED</span>
<span class="material-symbols-outlined text-secondary group-hover:translate-x-2 transition-transform">arrow_forward</span>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container w-full py-section-gap px-margin-mobile border-t border-outline-variant mt-section-gap">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<div class="font-headline-md text-headline-md text-primary mb-4 uppercase tracking-widest">AJILE</div>
<div class="grid grid-cols-1 md:grid-cols-4 w-full gap-12">
<div class="md:col-span-2">
<p class="font-body-md text-body-md text-on-surface-variant max-w-md">
                        Curating the world's most exceptional finishes for the visionary architect and the uncompromising homeowner.
                    </p>
</div>
<div class="flex flex-col gap-4">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">WhatsApp</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Instagram</a>
</div>
<div class="flex flex-col gap-4">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Showroom Policy</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Sustainability</a>
</div>
</div>
<div class="mt-16 w-full flex justify-between items-center border-t border-outline-variant pt-8">
<p class="font-body-md text-body-md text-on-surface-variant">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
<div class="flex gap-6">
<span class="material-symbols-outlined text-on-surface-variant cursor-pointer hover:text-primary">language</span>
<span class="material-symbols-outlined text-on-surface-variant cursor-pointer hover:text-primary">share</span>
</div>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant h-16 flex justify-around items-center px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors" href="index.html">
<span class="material-symbols-outlined">home</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="collections.html">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors" href="#">
<span class="material-symbols-outlined">auto_stories</span>
<span class="font-label-md text-[10px]">Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors" href="contact.html">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
</body></html>

<!-- Door Hardware - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>AJILE | Door Hardware Collection</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary": "#000000",
                        "on-surface": "#1a1c1b",
                        "on-secondary-container": "#785a1a",
                        "on-secondary": "#ffffff",
                        "on-primary": "#ffffff",
                        "on-background": "#1a1c1b",
                        "on-tertiary-container": "#7f848a",
                        "on-secondary-fixed": "#261900",
                        "tertiary": "#000000",
                        "secondary-fixed-dim": "#e9c176",
                        "inverse-primary": "#bcc7dd",
                        "tertiary-fixed-dim": "#c2c7cd",
                        "surface-container-high": "#e9e8e6",
                        "primary-fixed": "#d8e3f9",
                        "surface-container-low": "#f4f3f1",
                        "inverse-on-surface": "#f1f1ef",
                        "primary-container": "#111c2c",
                        "on-surface-variant": "#44474c",
                        "secondary-fixed": "#ffdea5",
                        "tertiary-container": "#171c20",
                        "background": "#faf9f7",
                        "surface-variant": "#e3e2e0",
                        "secondary-container": "#fed488",
                        "on-primary-fixed": "#111c2c",
                        "error-container": "#ffdad6",
                        "tertiary-fixed": "#dfe3e9",
                        "primary-fixed-dim": "#bcc7dd",
                        "on-primary-container": "#798498",
                        "inverse-surface": "#2f3130",
                        "surface-container-highest": "#e3e2e0",
                        "on-primary-fixed-variant": "#3d4759",
                        "error": "#ba1a1a",
                        "on-tertiary-fixed-variant": "#42474c",
                        "surface-tint": "#545f72",
                        "surface-container-lowest": "#ffffff",
                        "surface-bright": "#faf9f7",
                        "secondary": "#775a19",
                        "outline-variant": "#c5c6cd",
                        "on-secondary-fixed-variant": "#5d4201",
                        "on-error-container": "#93000a",
                        "surface-dim": "#dadad8",
                        "surface-container": "#efeeec",
                        "on-tertiary-fixed": "#171c20",
                        "surface": "#faf9f7",
                        "on-error": "#ffffff",
                        "on-tertiary": "#ffffff",
                        "outline": "#75777d"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "section-gap": "120px",
                        "margin-mobile": "20px",
                        "margin-desktop": "64px",
                        "container-max": "1280px",
                        "base": "8px",
                        "gutter": "24px"
                    },
                    "fontFamily": {
                        "label-md": ["Manrope"],
                        "display-lg": ["Playfair Display"],
                        "headline-md": ["Playfair Display"],
                        "body-lg": ["Manrope"],
                        "headline-lg-mobile": ["Playfair Display"],
                        "headline-lg": ["Playfair Display"],
                        "body-md": ["Manrope"]
                    },
                    "fontSize": {
                        "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                        "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}]
                    }
                }
            }
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body { background-color: #faf9f7; }
        
        /* Navigation Drawer Logic */
        #nav-drawer {
            transform: translateX(-100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #nav-overlay {
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.4s ease-in-out;
        }
        #nav-overlay.open {
            opacity: 1;
            visibility: visible;
        }
        
        /* Custom scrollbar for drawer */
        #nav-drawer::-webkit-scrollbar {
            width: 4px;
        }
        #nav-drawer::-webkit-scrollbar-thumb {
            background: #e3e2e0;
            border-radius: 2px;
        }
    </style>
</head>
<body class="bg-background text-on-surface font-body-md antialiased">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-black/50 z-[60]" id="nav-overlay" onclick="toggleNav()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-[85%] max-w-[360px] bg-surface z-[70] p-margin-mobile flex flex-col shadow-2xl overflow-y-auto" id="nav-drawer">
<div class="flex justify-between items-center mb-10 shrink-0">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="index.html">AJILE</a>
<button class="text-primary p-2 -mr-2" onclick="toggleNav()">
<span class="material-symbols-outlined">close</span>
</button>
</div>
<nav class="flex flex-col gap-1 mb-10">
<a class="font-headline-md text-[20px] py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="index.html">Home</a>
<a class="font-headline-md text-[20px] py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">About Us</a>
<a class="font-headline-md text-[20px] py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="collections.html">Collections</a>
<a class="font-headline-md text-[20px] py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">Showroom</a>
<div class="mt-4">
<h5 class="font-label-md text-on-surface-variant uppercase text-[11px] mb-2 tracking-widest">Categories</h5>
<div class="flex flex-col">
<a class="font-body-md text-on-surface py-2.5 hover:text-secondary flex justify-between items-center" href="#">Lighting <span class="material-symbols-outlined text-[18px] opacity-40">chevron_right</span></a>
<a class="font-body-md text-secondary py-2.5 flex justify-between items-center" href="door-hardware.html">Door Hardware <span class="material-symbols-outlined text-[18px]">chevron_right</span></a>
<a class="font-body-md text-on-surface py-2.5 hover:text-secondary flex justify-between items-center" href="#">Wardrobe Fittings <span class="material-symbols-outlined text-[18px] opacity-40">chevron_right</span></a>
<a class="font-body-md text-on-surface py-2.5 hover:text-secondary flex justify-between items-center" href="#">Sanitary &amp; Bathrooms <span class="material-symbols-outlined text-[18px] opacity-40">chevron_right</span></a>
<a class="font-body-md text-on-surface py-2.5 hover:text-secondary flex justify-between items-center" href="#">Kitchen <span class="material-symbols-outlined text-[18px] opacity-40">chevron_right</span></a>
<a class="font-body-md text-on-surface py-2.5 hover:text-secondary flex justify-between items-center" href="#">Flooring <span class="material-symbols-outlined text-[18px] opacity-40">chevron_right</span></a>
</div>
</div>
<a class="font-headline-md text-[20px] py-3 mt-4 border-t border-outline-variant/30 hover:text-secondary transition-colors" href="contact.html">Contact Us</a>
</nav>
<div class="mt-auto pt-8 border-t border-outline-variant/30">
<p class="font-label-md text-[10px] text-on-surface-variant uppercase tracking-widest mb-4">Inquiries</p>
<p class="font-body-md text-[14px]">concierge@ajilefinishes.com</p>
</div>
</aside>
<script>
    function toggleNav() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('nav-overlay');
        drawer.classList.toggle('open');
        overlay.classList.toggle('open');
        document.body.classList.toggle('overflow-hidden');
    }
</script>
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md border-b border-outline-variant fixed top-0 w-full z-50 flex items-center justify-between px-margin-mobile h-16 lg:px-margin-desktop">
<div class="flex items-center gap-4">
<button class="active:scale-95 transition-transform duration-200 text-primary" onclick="toggleNav()">
<span class="material-symbols-outlined">menu</span>
</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="index.html">AJILE</a>
</div>
<div class="hidden md:flex gap-8 items-center">
<a class="font-label-md text-label-md text-secondary" href="collections.html">Collections</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:bg-surface-container-low transition-colors duration-300 px-2 py-1" href="#">Showroom</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:bg-surface-container-low transition-colors duration-300 px-2 py-1" href="#">Consultation</a>
</div>
<div class="flex items-center gap-4">
<button class="active:scale-95 transition-transform duration-200 text-primary">
<span class="material-symbols-outlined">search</span>
</button>
</div>
</header>
<main class="pt-32 pb-section-gap max-w-container-max mx-auto px-margin-mobile lg:px-margin-desktop">
<!-- Back Link & Breadcrumb -->
<nav class="mb-12 flex items-center gap-2">
<a class="group flex items-center text-on-surface-variant hover:text-secondary transition-colors font-label-md text-label-md" href="collections.html">
<span class="material-symbols-outlined text-[18px] mr-1">arrow_back</span>
            Back to Collections
        </a>
</nav>
<!-- Page Header -->
<header class="mb-section-gap max-w-2xl">
<h1 class="font-display-lg text-display-lg mb-6 text-primary">Door Hardware</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant">An curated assembly of architectural precision. Our hardware collections bridge the gap between structural necessity and artisanal sculpture, defining the tactile experience of every threshold.</p>
</header>
<!-- Category Grid (Asymmetric) -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-gutter mb-section-gap">
<div class="md:col-span-8 group cursor-pointer relative overflow-hidden h-[400px]">
<img alt="A macro photograph of a luxurious solid brass door handle with a satin finish, mounted on a dark charcoal textured wood door." class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDPINESuKo6zFFVidcwORCem365nshLJOJBgv9Q_vHS4NP-j118RPFzL67F2k8jbT7C88mYkF9RLFhi4bl1VgxXm51lMogLS4Ra6-f1K-vN6eIWHQbnzmBBK2rK1n6wNZ5gAFAUT7IHN0Lablt-HLO76sFZw6_UYYrIWl7WjQ56T6mlOZLl82gVsLDxYC3FCwfIFaIvk231SJoFlj4Xi62LAHKt49VxNcgCRlSel-ROvKfm4gK2pKYTL45Pt2z8VuCIwOutzk4P7rHh"/>
<div class="absolute inset-0 bg-black/20 group-hover:bg-black/10 transition-colors"></div>
<div class="absolute bottom-8 left-8 text-white">
<h3 class="font-headline-md text-headline-md mb-2">Levers &amp; Handles</h3>
<p class="font-label-md text-label-md uppercase tracking-widest opacity-90">Tactile Sophistication</p>
</div>
</div>
<div class="md:col-span-4 flex flex-col gap-gutter">
<div class="flex-1 group cursor-pointer relative overflow-hidden min-h-[250px]">
<img alt="A sleek black biometric smart lock integrated into a minimalist white oak door." class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCOOTWzZDdcQoo6EemHIvqv3CHGNJi1Noee8Cif32kBNwUdXjTuKvpPRsmiU8G_KJFlSLD-cXKuCqRSiNXkbPBTK8gMAvgPRL72EhJlseXxk9Q7K02wqE61GcyHnmjLAP7P-TmRO4JUFHFpVfCSWHBswxw5OYsTJhRQ6kV2v3TWWaZesLrXf7XtvVY06gP8Tof0E14wtS6T8jsv85svZusS-Kvrbik9u8mmZlwI4R3FISx9jRT11CilD0d6IKDNL8WuNKz6XIcFCd6Y"/>
<div class="absolute inset-0 bg-black/10 group-hover:bg-black/5 transition-colors"></div>
<div class="absolute bottom-6 left-6 text-white">
<h3 class="font-headline-md text-headline-md text-[24px]">Locks &amp; Cylinders</h3>
</div>
</div>
<div class="flex-1 group cursor-pointer relative overflow-hidden min-h-[250px]">
<img alt="Close-up of heavy-duty concealed door hinges in a matte gunmetal finish." class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCpIMY0todBZ2vzJGw1KCX_EhOhjjs5t0LNhA-OUzKCXl9cxqTB6HC_AG5E26t7RVOj3V93LFs375kwyy7eo-VagNC0nx2qoZtx4Ny7cJVSVgafhiCMJOcr0aNpyBm-dg5MI2xXwgojFz8inZ6dcw1qwNjdCelg1zMir30DQkfQVpE0m0mI7h1rsKCV2SRqSOLPRUZBk3aXhBbyVmBuJ-TUciK1j2dSheiEigETQusHDee_e4kBdabiolpJbOBvNBKS4KUcdXRrS-gF"/>
<div class="absolute inset-0 bg-black/10 group-hover:bg-black/5 transition-colors"></div>
<div class="absolute bottom-6 left-6 text-white">
<h3 class="font-headline-md text-headline-md text-[24px]">Hinges &amp; Accessories</h3>
</div>
</div>
</div>
</section>
<!-- Featured Products -->
<section class="mb-section-gap">
<div class="flex justify-between items-end mb-12">
<h2 class="font-headline-lg text-headline-lg text-primary">Featured Selection</h2>
<button class="font-label-md text-label-md uppercase border-b border-primary pb-1">View All Hardware</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Product 1 -->
<div class="flex flex-col">
<div class="aspect-[3/4] bg-surface-container-low border border-outline-variant/30 overflow-hidden mb-6 relative group">
<img alt="Satin Brass Lever handle" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCtIGDNVIfLkXYo_4ty60sU1wlREQn3yzBPGY1MK-dYHyYrd6sK6e7qhrpJgB3H5ernSBRZFxnjCOQ8ePRjte8leVvXWcvrpmLAYv7KX8NvUmNNgxkZYC1RbYL-GowjHMaAdPak0AgWFkHA7NbFSgF6hI5ytCVq3nkmargfkZSMNtmjHnKyYmKiQCQB3B2PyFt0TCzshcvs_9fVO4yLABqdMFpZWMR-_d7FpdqEiyMWwRuLDHVW2ZOAoh-h_KojpUKrA7cXRKIXtk98"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-[10px] tracking-widest uppercase">Artisanal</span>
</div>
</div>
<div class="flex flex-col gap-2">
<p class="font-label-md text-on-surface-variant uppercase tracking-tighter text-[12px]">Collection: Legacy</p>
<h4 class="font-headline-md text-[22px] text-primary">Satin Brass Lever</h4>
<p class="font-body-md text-on-surface-variant">Hand-polished solid brass with a subtle, velvety patina that evolves over time.</p>
<div class="mt-4 flex gap-4">
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">Brass</span>
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">Hand-finished</span>
</div>
</div>
</div>
<!-- Product 2 -->
<div class="flex flex-col">
<div class="aspect-[3/4] bg-surface-container-low border border-outline-variant/30 overflow-hidden mb-6 relative group">
<img alt="Smart Biometric Lock" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAeLX6gEy1wNfglzsLIBt8Id3Aip1zNZLctbSq-xPu7SAq0imtbtJCfi-TKKu4uhNtWVV4hdvQAG6z-mMsgm-Kob8mhtkSqO00Og2ua50RkjipDqVAalkk22VGLwqh9-jDHs2RJZ4COyVcyybdle7QilFvj9DUcqv_WCPb8SvofOM24fz-BEDOsB7RcVVYzJ1uagQdM9NCHL4fu0Ivu4WZCH4ST2xRKQu909VW8gKOelYomG70Mk-1CiCQ1r85uQ2pvEDfzzEpPbMpl"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-[10px] tracking-widest uppercase">Innovate</span>
</div>
</div>
<div class="flex flex-col gap-2">
<p class="font-label-md text-on-surface-variant uppercase tracking-tighter text-[12px]">Collection: Digital Heritage</p>
<h4 class="font-headline-md text-[22px] text-primary">Smart Biometric Lock</h4>
<p class="font-body-md text-on-surface-variant">Fusing impenetrable security with a minimalist facade of aerospace-grade alloy.</p>
<div class="mt-4 flex gap-4">
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">Biometric</span>
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">Obsidian Black</span>
</div>
</div>
</div>
<!-- Product 3 -->
<div class="flex flex-col">
<div class="aspect-[3/4] bg-surface-container-low border border-outline-variant/30 overflow-hidden mb-6 relative group">
<img alt="Heavy duty concealed hinge" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDiqWP1Kxq05tzLpUebm9XttIeszVZuILwyLVSS0oNYQGIGwA1_jTPeRdnyb84ylLxWP2Pl64eP9KoFJiFdsbb--yrqzm28U6RmZVsrw1PtJBU06rLq24O7vrmNh5_EQa28eB37Tg1MrKPvEJF_ETUjlb0kTUiZmTOZ41ER2YMrp_i-yy9VzNX_EjA3lMVG5so-hHENk7rw9iDfXY941JrMX1DeYPwjmOSNTN_Kfd7NrxYfwX7iYhbssWAebiC3DaAXODl8J98LQuk8"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-[10px] tracking-widest uppercase">Invisible</span>
</div>
</div>
<div class="flex flex-col gap-2">
<p class="font-label-md text-on-surface-variant uppercase tracking-tighter text-[12px]">Collection: Structural</p>
<h4 class="font-headline-md text-[22px] text-primary">Heavy Duty Concealed Hinge</h4>
<p class="font-body-md text-on-surface-variant">The unseen anchor of architectural fluidity. Engineered for silent, weighted movement.</p>
<div class="mt-4 flex gap-4">
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">Stainless</span>
<span class="bg-surface-container text-on-surface px-2 py-0.5 text-[10px] font-label-md uppercase">3D Adjustable</span>
</div>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="bg-primary-container p-12 md:p-24 flex flex-col items-center text-center">
<h2 class="font-display-lg text-display-lg text-on-primary mb-8 max-w-3xl">Design Your Masterpiece.</h2>
<p class="font-body-lg text-on-primary-container mb-12 max-w-xl">Request a physical sample kit or book a private showroom tour with our finish specialists to experience the tactile difference of AJILE hardware.</p>
<div class="flex flex-col sm:flex-row gap-6 w-full max-w-md mx-auto">
<button class="bg-primary text-on-primary px-10 py-4 font-label-md uppercase tracking-widest hover:bg-on-surface-variant transition-colors">Request Samples</button>
<button class="border border-secondary text-secondary px-10 py-4 font-label-md uppercase tracking-widest hover:bg-secondary/10 transition-colors">Book Consultation</button>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-section-gap px-margin-mobile border-t border-outline-variant bg-surface-container">
<div class="max-w-container-max mx-auto flex flex-col md:flex-row justify-between gap-12">
<div class="flex flex-col items-start gap-4">
<span class="font-headline-md text-headline-md text-primary mb-4 tracking-[0.2em] uppercase">AJILE</span>
<p class="font-body-md text-on-surface-variant max-w-xs">Supplying the world's most meticulous developers and interior designers with finishes that endure.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 gap-gutter">
<div class="flex flex-col gap-4">
<h5 class="font-label-md text-primary uppercase text-[12px]">Network</h5>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">WhatsApp</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Instagram</a>
</div>
<div class="flex flex-col gap-4">
<h5 class="font-label-md text-primary uppercase text-[12px]">Support</h5>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Showroom Policy</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Sustainability</a>
</div>
</div>
</div>
<div class="max-w-container-max mx-auto mt-24 pt-8 border-t border-outline-variant/30">
<p class="font-label-md text-[12px] text-on-surface-variant opacity-60">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
</div>
</footer>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="index.html">
<span class="material-symbols-outlined">home</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 relative after:content-[''] after:absolute after:-bottom-2 after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="collections.html">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="contact.html">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
</body></html>

<!-- Showroom - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&amp;family=Manrope:wght@200..800&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "inverse-surface": "#2f3130",
                    "secondary-fixed-dim": "#e9c176",
                    "tertiary": "#000000",
                    "error-container": "#ffdad6",
                    "outline": "#75777d",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-container": "#171c20",
                    "on-error-container": "#93000a",
                    "secondary-fixed": "#ffdea5",
                    "primary": "#000000",
                    "surface-bright": "#faf9f7",
                    "on-surface": "#1a1c1b",
                    "primary-fixed": "#d8e3f9",
                    "surface-tint": "#545f72",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "on-secondary-fixed": "#261900",
                    "secondary-container": "#fed488",
                    "on-secondary-container": "#785a1a",
                    "on-tertiary-fixed": "#171c20",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-container": "#111c2c",
                    "on-primary": "#ffffff",
                    "surface-container": "#efeeec",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-tertiary-container": "#7f848a",
                    "surface": "#faf9f7",
                    "surface-container-high": "#e9e8e6",
                    "surface-dim": "#dadad8",
                    "surface-container-highest": "#e3e2e0",
                    "on-tertiary": "#ffffff",
                    "on-primary-fixed-variant": "#3d4759",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-secondary": "#ffffff",
                    "on-surface-variant": "#44474c",
                    "surface-container-low": "#f4f3f1",
                    "surface-variant": "#e3e2e0",
                    "surface-container-lowest": "#ffffff",
                    "on-error": "#ffffff",
                    "error": "#ba1a1a",
                    "background": "#faf9f7",
                    "on-background": "#1a1c1b",
                    "on-primary-container": "#798498",
                    "on-primary-fixed": "#111c2c",
                    "inverse-on-surface": "#f1f1ef",
                    "on-tertiary-fixed-variant": "#42474c"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "container-max": "1280px",
                    "margin-desktop": "64px",
                    "section-gap": "120px",
                    "base": "8px",
                    "gutter": "24px",
                    "margin-mobile": "20px"
            },
            "fontFamily": {
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "label-md": ["Manrope"],
                    "body-md": ["Manrope"],
                    "body-lg": ["Manrope"],
                    "display-lg": ["Playfair Display"]
            },
            "fontSize": {
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            display: inline-block;
            line-height: 1;
            text-transform: none;
            letter-spacing: normal;
            word-wrap: normal;
            white-space: nowrap;
            direction: ltr;
        }
        .backdrop-blur-nav {
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #drawer-overlay.open {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
</head>
<body class="bg-background text-on-surface font-body-md selection:bg-secondary-container selection:text-on-secondary-container overflow-x-hidden">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-primary/40 backdrop-blur-sm z-[60] opacity-0 invisible transition-all duration-300 pointer-events-none" id="drawer-overlay" onclick="toggleDrawer()"></div>
<!-- Navigation Drawer -->
<div class="fixed inset-y-0 left-0 w-[85%] max-w-xs bg-surface-container-lowest z-[70] transform -translateX-full transition-transform duration-300 ease-in-out flex flex-col shadow-2xl border-r border-outline-variant" id="nav-drawer">
<div class="h-16 flex items-center justify-between px-6 border-b border-outline-variant">
<div class="font-headline-md text-xl tracking-[0.1em] text-primary uppercase">AJILE</div>
<button class="p-2 hover:bg-surface-container transition-colors" onclick="toggleDrawer()">
<span class="material-symbols-outlined">close</span>
</button>
</div>
<div class="flex-1 overflow-y-auto py-8">
<nav class="flex flex-col gap-1 px-4 mb-6">
<a class="flex items-center gap-4 px-4 py-3 rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors" href="{{DATA:SCREEN:SCREEN_15}}">
<span class="material-symbols-outlined">home</span>
<span class="font-label-md">Home</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors" href="{{DATA:SCREEN:SCREEN_4}}">
<span class="material-symbols-outlined">info</span>
<span class="font-label-md">About Us</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors" href="{{DATA:SCREEN:SCREEN_9}}">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md">Collections</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 rounded-lg bg-secondary-container/30 text-secondary transition-colors" href="#">
<span class="material-symbols-outlined text-secondary">location_on</span>
<span class="font-label-md font-bold">Showroom</span>
</a>
</nav>
<div class="px-8 mb-4">
<span class="font-label-md text-[10px] uppercase tracking-widest text-outline">Product Categories</span>
</div>
<nav class="flex flex-col gap-1 px-4 mb-10">
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_5}}">
<span class="font-body-md">Lighting</span>
</a>
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_10}}">
<span class="font-body-md">Door Hardware</span>
</a>
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_6}}">
<span class="font-body-md">Wardrobe Fittings</span>
</a>
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_8}}">
<span class="font-body-md">Sanitary &amp; Bathrooms</span>
</a>
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_2}}">
<span class="font-body-md">Kitchen</span>
</a>
<a class="flex items-center gap-4 px-4 py-2 text-on-surface-variant hover:text-primary transition-colors text-sm" href="{{DATA:SCREEN:SCREEN_12}}">
<span class="font-body-md">Flooring</span>
</a>
</nav>
<nav class="flex flex-col gap-1 px-4 border-t border-outline-variant pt-6">
<a class="flex items-center gap-4 px-4 py-3 rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors" href="{{DATA:SCREEN:SCREEN_14}}">
<span class="material-symbols-outlined">mail</span>
<span class="font-label-md">Contact Us</span>
</a>
</nav>
</div>
</div>
<!-- TopAppBar -->
<header class="bg-surface/90 dark:bg-inverse-surface/90 backdrop-blur-md border-b border-outline-variant dark:border-outline fixed top-0 w-full z-50">
<div class="flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full max-w-container-max mx-auto">
<button class="text-primary dark:text-on-primary hover:bg-surface-container-low dark:hover:bg-inverse-surface p-2 transition-colors duration-300 active:scale-95 transition-transform duration-200" onclick="toggleDrawer()">
<span class="material-symbols-outlined">menu</span>
</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary dark:text-on-primary uppercase cursor-pointer" href="{{DATA:SCREEN:SCREEN_15}}">AJILE</a>
<div class="flex items-center gap-4">
<nav class="hidden md:flex items-center gap-8 mr-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="{{DATA:SCREEN:SCREEN_9}}">Collections</a>
<a class="font-label-md text-label-md text-secondary dark:text-secondary-fixed-dim" href="#">Showroom</a>
<a class="font-label-md text-label-md text-on-surface-variant dark:text-surface-variant hover:text-primary transition-colors" href="#">Journal</a>
</nav>
<button class="text-primary dark:text-on-primary hover:bg-surface-container-low dark:hover:bg-inverse-surface p-2 transition-colors duration-300 active:scale-95 transition-transform duration-200">
<span class="material-symbols-outlined">search</span>
</button>
</div>
</div>
</header>
<main class="pt-32 pb-section-gap">
<!-- Hero Section -->
<section class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto mb-section-gap">
<div class="max-w-3xl">
<h1 class="font-headline-lg text-headline-lg-mobile md:text-headline-lg text-primary mb-6">Curated architectural finishes for the meticulous eye.</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant mb-8">Experience a gallery of textures, from hand-polished hardware to sustainably sourced wood. Each category is a testament to our commitment to enduring quality and architectural precision.</p>
</div>
</section>
<!-- Category Grid -->
<section class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Door Hardware (Large Feature) -->
<div class="md:col-span-8 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_10}}'">
<div class="relative aspect-[16/9] overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="A high-end, minimalist door handle made of brushed dark bronze" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD3NAYhnpoZSmTSkysiyt6i3UQX3DMd8nhs2nAdoQda-QxcuCPC1yz6qwvolbBFTs5aPBuZX574Mp3IBe07F4NzvQaLrXp2g7da3zhlnWdHdCeppzT-Xjo52BTIzBCYmyDzZti7DdPXSDtz0g1O0NoSBfrm_6DUYXBrycb5B3pU3dhL7o3a061X9-TbasCQWn0DP16bGK6AluuCJDHbnQfPlTkybbHJ3QLrItGnDZRVBoz0GqTY1VS-rbsoyfMIwSCpTZThGitTqd-F"/>
<div class="absolute inset-0 bg-primary/5 group-hover:bg-transparent transition-colors duration-500"></div>
</div>
<div class="flex justify-between items-start">
<div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Door Hardware</h3>
<p class="font-body-md text-body-md text-on-surface-variant max-w-md">Precision-engineered handles and locks in artisanal finishes, designed to be the first point of contact for luxury.</p>
</div>
<div class="mt-2 h-12 w-12 border border-secondary text-secondary flex items-center justify-center group-hover:bg-secondary-fixed transition-colors">
<span class="material-symbols-outlined">arrow_outward</span>
</div>
</div>
</div>
<!-- Wardrobe Fittings (Vertical) -->
<div class="md:col-span-4 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_6}}'">
<div class="relative aspect-[3/4] overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="Detail shot of an organized luxury wardrobe" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDmTbuWXgcCFQP0SGGjwhAGkqTQeRNX2BGdUHHwWYFJpr1zd9hkSKPHt7EAtGSsNxD54nhUg4-kKGJyiybCrpCQHZBkon8dRykAZU627NjHIK8iStKh68y9zQ60Uk_3EH2s-j57DaDNOR6icKOSH_3o95fKyoThlAld5WJdh6EJUHdrhh_vyFC5RTkjD-Iha_kxSk5s7OabPfEukcmUsojr1HuEkSXrzKNHaBP8nmPqI04SdOIQFf0O8ohiGg5MuH4hJyBO6Xf53Xjt"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Wardrobe Fittings</h3>
<p class="font-body-md text-body-md text-on-surface-variant">Intelligent internal systems that marry organizational utility with the warmth of gold and slate finishes.</p>
</div>
<!-- Bathroom (Square) -->
<div class="md:col-span-4 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_8}}'">
<div class="relative aspect-square overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="A minimalist bathroom setting featuring a matte black faucet" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDa_IeV4VZw2kcBBPo3Gb8NbwJ0YGu6fbm4GjBXijGkuaQVL8R8ErqKffSviOWK4ia6yuqHiLw679mBsYOaQYLlCSgr0oH0PsMSd4kHrrX46y4MYe32h_GE2pw5mkoW2kthPZvZx3OAjuY65kwFGH0tqRRT5GDrT_6ovyTgA9Eh3pc-fwdMMGKm9xy3TZNoRqwIg9ixsjLNmiIhj82_3SuP3oOkiqZM9w0w0IG_H9BNzUTJEIRGDWAMHi45P0VRn_otrS-VyAM3nGtT"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Sanitary &amp; Bathrooms</h3>
<p class="font-body-md text-body-md text-on-surface-variant">Sleek faucets and fixtures that redefine the sanctuary of the home through sculptural form.</p>
</div>
<!-- Kitchen (Wide) -->
<div class="md:col-span-8 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_2}}'">
<div class="relative aspect-[16/9] overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="A spacious modern kitchen with a large marble island" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAajLLERSgBAZj4xUGrue9BQOWEobrNONuKzN_vPM2by9Nrj2OmXTwMRXk-coKd2vTBXlY_3jsUfhTFYPMoedrGS_OszF_hM_aKLxvxmr5Zq8i1Ken0Cwsp3K2hbd-kUogeubg_OSAix6DxOCzzt8bGbfraNeoQwT9aK6L_kKz6AzMJEHHqubM_Dm_dd-UQfNCsNicuUhqa4dlspmANXehCjOXy1-KJUToUyUF670TJQ-kI40nXLbYpEBI-sXX1lLR_8mXD0WJjuxcQ"/>
</div>
<div class="flex justify-between items-start">
<div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Kitchen</h3>
<p class="font-body-md text-body-md text-on-surface-variant max-w-md">The heart of the home, elevated with seamless hardware and high-performance surfaces.</p>
</div>
<div class="mt-2 h-12 w-12 border border-secondary text-secondary flex items-center justify-center group-hover:bg-secondary-fixed transition-colors">
<span class="material-symbols-outlined">arrow_outward</span>
</div>
</div>
</div>
<!-- Lighting (Vertical Focus) -->
<div class="md:col-span-6 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_5}}'">
<div class="relative aspect-video overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="Close-up of a designer brass pendant light" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuByX4uz0LLSTEGqAf1xmg0FzTj9pilNqR0NORcISaIeXd1drFuOSbQn2yn4jpwqaxn7nf_x05j9MobKyE50OSugTLCuDkQPXIa3eqUGOUXg24wtMJnEXOzxcRDYdAsqHhgAG121vUM0KC2rM1-B24V1efS7lX8TEfL2Zi97GFpMLJGacPRw-N6BgPiv46OGNo0vIrGVphFa8DW29-G6p5xVcZ4bHSCVMXyOuHKPsV28t9WK6KG0atHezQgPZ0tmG-0pYktMpXfHXSUC"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Lighting</h3>
<p class="font-body-md text-body-md text-on-surface-variant">Architectural illumination designed to reveal the true depth and color of your interior finishes.</p>
</div>
<!-- Flooring (Texture focus) -->
<div class="md:col-span-6 group cursor-pointer" onclick="window.location.href='{{DATA:SCREEN:SCREEN_12}}'">
<div class="relative aspect-video overflow-hidden bg-surface-container mb-6 border border-outline-variant">
<img alt="Top-down view of premium wide-plank oak flooring" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1_UXvvRgOFYqTEN2S6olnivbjBOOZaFq5xFUIuBqv7IXojqoOd8V866PNDbGnsuoy-niB68k_gpC_hSjlfB3ocz7JVXFqgzOVC7dzXNeQbVge1dOT9Ji4i5duCPBDsf9RlKyjg5Qa0xcyI-v-NbQA_RkQVFgbhzf1HB7YKRL-a5k0k_2nWfIUiS1qC74HrrXH4qzK10uxynWO68n21eOG-a4cBkeqiYlpS1YVw1ABsJwxHz0xY7sFc3MCiWM5jIjIxk5naJYMootg"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2 uppercase tracking-tight">Flooring</h3>
<p class="font-body-md text-body-md text-on-surface-variant">A foundation of luxury, from wide-plank sustainable timber to hand-cut exotic stone tiles.</p>
</div>
</div>
<!-- View All Action -->
<div class="mt-24 flex flex-col items-center">
<p class="font-label-md text-label-md text-on-surface-variant mb-8 uppercase tracking-widest text-center">Explore our complete inventory of 1,200+ exclusive finishes</p>
<button class="px-12 py-4 bg-primary text-on-primary font-label-md text-label-md uppercase tracking-widest hover:bg-on-primary-fixed-variant transition-colors duration-300" onclick="window.location.href='{{DATA:SCREEN:SCREEN_9}}'">
                    View All Collections
                </button>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container dark:bg-inverse-surface w-full py-section-gap px-margin-mobile border-t border-outline-variant dark:border-outline mt-section-gap">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<div class="font-headline-md text-headline-md text-primary dark:text-on-primary mb-4">AJILE</div>
<div class="grid grid-cols-1 md:grid-cols-4 gap-12 w-full mb-12">
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest">Connect</span>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">WhatsApp</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Instagram</a>
</div>
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest">Corporate</span>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="{{DATA:SCREEN:SCREEN_4}}">About Us</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Sustainability</a>
</div>
<div class="md:col-span-2">
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest mb-4 block">The Showroom</span>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xs">
                        Visit our flagship gallery for a personalized material consultation with our finish specialists.
                    </p>
</div>
</div>
<div class="w-full h-px bg-outline-variant mb-8"></div>
<p class="font-body-md text-body-md text-on-surface-variant">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
</div>
</footer>
<!-- Mobile Bottom Navigation -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="{{DATA:SCREEN:SCREEN_15}}">
<span class="material-symbols-outlined">home_app_logo</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="{{DATA:SCREEN:SCREEN_9}}">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="#">
<span class="material-symbols-outlined">location_on</span>
<span class="font-label-md text-[10px]">Showroom</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="{{DATA:SCREEN:SCREEN_14}}">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
<script>
    function toggleDrawer() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('drawer-overlay');
        const isOpen = drawer.classList.contains('open');
        
        if (isOpen) {
            drawer.classList.remove('open');
            drawer.classList.add('-translateX-full');
            overlay.classList.remove('open');
            overlay.classList.add('invisible');
            document.body.style.overflow = '';
        } else {
            drawer.classList.add('open');
            drawer.classList.remove('-translateX-full');
            overlay.classList.add('open');
            overlay.classList.remove('invisible');
            document.body.style.overflow = 'hidden';
        }
    }
</script>
</body></html>

<!-- Wardrobe Fittings - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&amp;family=Manrope:wght@400;500;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary": "#000000",
                    "on-surface": "#1a1c1b",
                    "on-secondary-container": "#785a1a",
                    "on-secondary": "#ffffff",
                    "on-primary": "#ffffff",
                    "on-background": "#1a1c1b",
                    "on-tertiary-container": "#7f848a",
                    "on-secondary-fixed": "#261900",
                    "tertiary": "#000000",
                    "secondary-fixed-dim": "#e9c176",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "surface-container-high": "#e9e8e6",
                    "primary-fixed": "#d8e3f9",
                    "surface-container-low": "#f4f3f1",
                    "inverse-on-surface": "#f1f1ef",
                    "primary-container": "#111c2c",
                    "on-surface-variant": "#44474c",
                    "secondary-fixed": "#ffdea5",
                    "tertiary-container": "#171c20",
                    "background": "#faf9f7",
                    "surface-variant": "#e3e2e0",
                    "secondary-container": "#fed488",
                    "on-primary-fixed": "#111c2c",
                    "error-container": "#ffdad6",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-primary-container": "#798498",
                    "inverse-surface": "#2f3130",
                    "surface-container-highest": "#e3e2e0",
                    "on-primary-fixed-variant": "#3d4759",
                    "error": "#ba1a1a",
                    "on-tertiary-fixed-variant": "#42474c",
                    "surface-tint": "#545f72",
                    "surface-container-lowest": "#ffffff",
                    "surface-bright": "#faf9f7",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-error-container": "#93000a",
                    "surface-dim": "#dadad8",
                    "surface-container": "#efeeec",
                    "on-tertiary-fixed": "#171c20",
                    "surface": "#faf9f7",
                    "on-error": "#ffffff",
                    "on-tertiary": "#ffffff",
                    "outline": "#75777d"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "section-gap": "120px",
                    "margin-mobile": "20px",
                    "margin-desktop": "64px",
                    "container-max": "1280px",
                    "base": "8px",
                    "gutter": "24px"
            },
            "fontFamily": {
                    "label-md": ["Manrope"],
                    "display-lg": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "body-lg": ["Manrope"],
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "body-md": ["Manrope"]
            },
            "fontSize": {
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #faf9f7;
            color: #1a1c1b;
        }
        #nav-drawer {
            transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.closed {
            transform: translateX(-100%);
        }
    </style>
</head>
<body class="bg-background text-on-background min-h-screen">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-primary/20 backdrop-blur-sm z-[60] hidden" id="drawer-overlay" onclick="toggleDrawer()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-[85%] max-w-[320px] bg-surface z-[70] closed shadow-2xl overflow-y-auto" id="nav-drawer">
<div class="p-margin-mobile flex flex-col h-full min-h-screen">
<div class="flex items-center justify-between mb-8">
<span class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase">AJILE</span>
<span class="material-symbols-outlined cursor-pointer" data-icon="close" onclick="toggleDrawer()">close</span>
</div>
<nav class="flex flex-col gap-5 overflow-y-auto">
<a class="font-headline-md text-headline-md hover:text-secondary transition-colors" href="SCREEN_15">Home</a>
<a class="font-headline-md text-headline-md hover:text-secondary transition-colors" href="#">About Us</a>
<a class="font-headline-md text-headline-md hover:text-secondary transition-colors" href="SCREEN_9">Collections</a>
<a class="font-headline-md text-headline-md hover:text-secondary transition-colors" href="#">Showroom</a>
<div class="mt-4 pt-4 border-t border-outline-variant">
<p class="font-label-md text-label-md text-on-surface-variant uppercase mb-4 tracking-widest">Product Categories</p>
<div class="flex flex-col gap-4">
<a class="font-body-lg text-body-lg hover:text-secondary transition-colors" href="#">Lighting</a>
<a class="font-body-lg text-body-lg hover:text-secondary transition-colors" href="#">Door Hardware</a>
<a class="font-body-lg text-body-lg text-secondary transition-colors" href="#">Wardrobe Fittings</a>
<a class="font-body-lg text-body-lg hover:text-secondary transition-colors" href="#">Sanitary &amp; Bathrooms</a>
<a class="font-body-lg text-body-lg hover:text-secondary transition-colors" href="#">Kitchen</a>
<a class="font-body-lg text-body-lg hover:text-secondary transition-colors" href="#">Flooring</a>
</div>
</div>
<a class="font-headline-md text-headline-md hover:text-secondary transition-colors mt-4 pt-4 border-t border-outline-variant" href="SCREEN_14">Contact Us</a>
</nav>
<div class="mt-auto pt-12 pb-8">
<p class="font-label-md text-[12px] text-on-surface-variant uppercase tracking-widest">Global Experience</p>
</div>
</div>
</aside>
<!-- Top Navigation -->
<nav class="fixed top-0 w-full z-50 bg-surface/90 backdrop-blur-md border-b border-outline-variant flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-primary cursor-pointer active:scale-95 transition-transform" data-icon="menu" onclick="toggleDrawer()">menu</span>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
</div>
<div class="hidden md:flex gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="SCREEN_9">Collections</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Journal</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">The Showroom</a>
</div>
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-primary cursor-pointer active:scale-95 transition-transform" data-icon="search">search</span>
</div>
</nav>
<main class="pt-24 pb-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<!-- Breadcrumb / Back Link -->
<a class="mb-12 flex items-center gap-2 group cursor-pointer w-fit" href="SCREEN_9">
<span class="material-symbols-outlined text-on-surface-variant group-hover:text-primary transition-colors text-[18px]" data-icon="arrow_back">arrow_back</span>
<span class="font-label-md text-label-md text-on-surface-variant group-hover:text-primary transition-colors uppercase tracking-wider">Back to Collections</span>
</a>
<!-- Header -->
<header class="mb-section-gap">
<h1 class="font-display-lg text-display-lg mb-6 max-w-2xl">Wardrobe Fittings</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-xl">
            A curated selection of precision-engineered hardware designed for the most demanding bespoke interiors. Our systems offer silent performance and architectural elegance.
        </p>
</header>
<!-- Bento Grid Categories -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-gutter mb-section-gap">
<div class="md:col-span-8 group relative overflow-hidden h-[500px] border border-outline-variant">
<img class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A luxurious, minimalist walk-in closet with high-end sliding glass doors and soft interior lighting. The scene highlights the precision of the Sliding Systems hardware in a neutral-toned, architectural environment." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDhbbbdjVUvRhZb6pmyLIjjGkOi5PrqNTaZXpJHSEJO3Ty3UzpwyRQcJBZPLx98ePWfECrDq8n4ZU5rdJDfXumugXjDsnNduAieVd6pSCW8q-NEr0lAXNDE4_D2jV1NIAFhd1KA-OrOlVdQS-KKEkIDIHG50V3e67E_GSAgxEJ7VC6EWoHaCnLGYzM3jFdtqPp2y8mCRSSni4VITdsLHlvs2oUaxvGHkDGA-AtdVzRofOLFRvIXAT5yzOcrAQuch-jMB-Brg1c-NF1X"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/60 to-transparent"></div>
<div class="absolute bottom-8 left-8 text-on-primary">
<h2 class="font-headline-lg text-headline-lg mb-2">Sliding Systems</h2>
<p class="font-body-md text-body-md opacity-90 mb-4">Precision tracks for effortless movement.</p>
<button class="bg-on-secondary-fixed text-on-secondary px-6 py-3 font-label-md text-label-md uppercase tracking-widest hover:bg-secondary-fixed transition-colors">Explore Category</button>
</div>
</div>
<div class="md:col-span-4 flex flex-col gap-gutter">
<div class="flex-1 group relative overflow-hidden border border-outline-variant">
<img class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A close-up view of a high-quality metal drawer runner system. The hardware is finished in a sophisticated matte champagne gold." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHb0W1cg2y5pbZ0up0_xar58LFIYwgu7ldDD-f4FFy8Z4OE3u6d6bAj05FqdbEA5HF5KaqqzP_maTJ0RVQnJBF6btipoZqmsIwFoKXawNTZ-Nr7uQ6BMNJ2bDVBUsb532ysd4uMvPOg_SPdq1-7KQXpbIITYheQ_qd3hXz1U7vXB36xlJl3SrM5tEOsDUxTOKri8updtgSaQyzykZadGniOqrilqvE6MWMVhuAyBELViVgUAJmowDHPL4wcoDXMARSnNzA8I1uACMw"/>
<div class="absolute inset-0 bg-primary/20 group-hover:bg-primary/40 transition-colors"></div>
<div class="absolute bottom-6 left-6 text-on-primary">
<h3 class="font-headline-md text-headline-md">Drawer Runners</h3>
<p class="font-label-md text-label-md uppercase opacity-80">Industrial Strength</p>
</div>
</div>
<div class="flex-1 group relative overflow-hidden border border-outline-variant">
<img class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A meticulously organized wardrobe showing high-end interior organizers and a rotating shoe rack." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDpfD3PuRxkdMTQberyc_onvhOFT0keU8Qcz-23mDpKmcrILwxIIjoJSgCnGQdr-G0jsB5IQrn9EmMH_S5DGJDliE22-Chw85TNpVVoCrBs2l5dClnJuejPhbkiMuIoBd8ZnYDUha3LtUv7vkLDo9Lndqr_6SAEs1qpEk8z6MpySpKXviI1eRe7y3y-f04Qkrm4zl5tLPJlV9Duux1t-5b5JZDo2X_OTHTvjA_g5sM61o8qprfhY5rOTRS59Z-hE1l2tVpmJ5eGKzye"/>
<div class="absolute inset-0 bg-primary/20 group-hover:bg-primary/40 transition-colors"></div>
<div class="absolute bottom-6 left-6 text-on-primary">
<h3 class="font-headline-md text-headline-md">Organizers</h3>
<p class="font-label-md text-label-md uppercase opacity-80">Bespoke Layouts</p>
</div>
</div>
</div>
</section>
<!-- Featured Products -->
<section>
<div class="flex items-end justify-between mb-12 border-b border-outline-variant pb-6">
<h2 class="font-headline-lg text-headline-lg">Featured Selection</h2>
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest cursor-pointer hover:underline">View All Products</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Product Card 1 -->
<div class="group">
<div class="aspect-[4/5] relative overflow-hidden mb-6 border border-outline-variant bg-surface-container">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="Minimalist studio photography of a Soft-close Sliding Track hardware piece." src="https://lh3.googleusercontent.com/aida-public/AB6AXuD5patk1gH6cQJPFFV7Q0h-ONWsqUFYDLcDjjGGtdzd0tDD-3bTn8xsOMQDg7zPikP0LcnvAYLnrN1EGvkKfzM9bxD75V049uCEpYj1WZWmfGvQfKKXz-UZlBp2OnFYydIp-G9uAfMfWqzoTdR6rSVpYYMaONeQFjc9x4oCC96U9uzeZegtEpcBe6kTH62ey9qUiY91QsLPylVwUQfgGxplnRjoRjERR5oOg-iRJgAZWBu6ABJMdK8nO709miaiMW2BS9fLBUjtYqvT"/>
<div class="absolute top-4 right-4 bg-surface px-3 py-1 border border-outline-variant">
<span class="font-label-md text-label-md text-primary uppercase">New</span>
</div>
</div>
<div class="space-y-2">
<p class="font-label-md text-label-md text-secondary uppercase tracking-widest">Sliding Systems</p>
<h3 class="font-headline-md text-headline-md">Soft-close Sliding Track</h3>
<div class="flex gap-2 py-2">
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">Precision Steel</span>
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">100kg Capacity</span>
</div>
<p class="font-body-md text-body-md text-on-surface-variant">Quiet operation with hydraulic damping technology.</p>
</div>
</div>
<!-- Product Card 2 -->
<div class="group">
<div class="aspect-[4/5] relative overflow-hidden mb-6 border border-outline-variant bg-surface-container">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A detailed shot of a Slim Metal Drawer Box installed in a custom cabinet." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAw_RPbytzLAP3U4k6Fu8oBXatVYMbYCKJWnRl8NY3AmSyfDZozPuqWBB3y4i-MZb7Ri_9dsxq2urr7W_ItwDTU3P9DL1LQ9F2FTPSsQzC1zY622jez84xiKwXiLod248Z_0xH0UJgV6FZGPoaNqdudyW5TH_PW6C8ggxZoOhIEOOFXt-UaESMqVyYCc52ktYp7IzAiHfY89caiDeHvi28s_GjZSkAViPr2Ql4dMwZoY96XUpoy5W10oW3CMSHRvxP2UnHEQkj7xLeg"/>
</div>
<div class="space-y-2">
<p class="font-label-md text-label-md text-secondary uppercase tracking-widest">Drawer Runners</p>
<h3 class="font-headline-md text-headline-md">Slim Metal Drawer Box</h3>
<div class="flex gap-2 py-2">
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">Architectural</span>
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">Full Extension</span>
</div>
<p class="font-body-md text-body-md text-on-surface-variant">Minimalist profile with synchronized runner motion.</p>
</div>
</div>
<!-- Product Card 3 -->
<div class="group">
<div class="aspect-[4/5] relative overflow-hidden mb-6 border border-outline-variant bg-surface-container">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A rotating shoe rack storage solution in a high-end luxury closet." src="https://lh3.googleusercontent.com/aida-public/AB6AXuD77JposnZRcHH7qvp79S_iIDkzxtszlTTvWrtSozt9UrsVO5dU7GJPjCynfhDx8jC4Eu9lxYG9vPf1EDPXDGDOfnhBQKEgM2e5XXGpdqMlEpILFMZqd_mz42p5s7xYU7suD8kppjH4GREdiiNME-eQnOjHR97voJrEV10BaD0eQZJzud3y-7O7Whozeh3z35KsxtDDkC7HC0RxNnKMYh1T-1ldvA3Ce5oCZFYiq872Qmujoy4DrSzLqiuRJ9gaNh0NQggFxj5GifIZ"/>
<div class="absolute top-4 right-4 bg-primary text-on-primary px-3 py-1">
<span class="font-label-md text-label-md uppercase">Premium</span>
</div>
</div>
<div class="space-y-2">
<p class="font-label-md text-label-md text-secondary uppercase tracking-widest">Organizers</p>
<h3 class="font-headline-md text-headline-md">Rotating Shoe Rack</h3>
<div class="flex gap-2 py-2">
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">360° Access</span>
<span class="bg-surface-container px-3 py-1 text-primary font-label-md text-[10px] uppercase tracking-tighter">Hand-Polished</span>
</div>
<p class="font-body-md text-body-md text-on-surface-variant">Space-maximizing swivel system for luxury footwear.</p>
</div>
</div>
</div>
</section>
<!-- Newsletter / Contact CTA -->
<section class="mt-section-gap bg-primary text-on-primary p-12 md:p-24 flex flex-col items-center text-center">
<h2 class="font-display-lg text-display-lg mb-8">Design Your Sanctuary</h2>
<p class="font-body-lg text-body-lg mb-12 max-w-xl opacity-80">Request a technical catalog or consult with our hardware specialists for your next architectural project.</p>
<div class="flex flex-col md:flex-row gap-gutter w-full max-w-lg">
<input class="flex-1 bg-transparent border-b border-on-primary/30 text-on-primary placeholder:text-on-primary/50 py-3 focus:outline-none focus:border-on-primary font-label-md" placeholder="YOUR EMAIL ADDRESS" type="email"/>
<button class="border border-secondary text-secondary px-8 py-3 font-label-md text-label-md uppercase tracking-widest hover:bg-secondary/10 transition-all">Submit Request</button>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-section-gap px-margin-mobile md:px-margin-desktop border-t border-outline-variant bg-surface-container pb-24 md:pb-section-gap">
<div class="max-w-container-max mx-auto flex flex-col md:flex-row justify-between gap-12">
<div class="max-w-sm">
<div class="font-headline-md text-headline-md text-primary mb-6 uppercase tracking-wider">AJILE PREMIUM FINISHES</div>
<p class="font-body-md text-body-md text-on-surface-variant mb-8">Elevating the standard of interior hardware through meticulous engineering and timeless design since 1994.</p>
<div class="flex gap-6">
<span class="font-label-md text-label-md text-secondary cursor-pointer hover:opacity-80 transition-opacity">WhatsApp</span>
<span class="font-label-md text-label-md text-secondary cursor-pointer hover:opacity-80 transition-opacity">Instagram</span>
</div>
</div>
<div class="grid grid-cols-2 gap-x-12 gap-y-4">
<h4 class="col-span-2 font-label-md text-label-md text-primary uppercase mb-2">Navigation</h4>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="SCREEN_15">Home</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="SCREEN_9">Collections</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="#">Journal</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="SCREEN_14">Contact</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="#">Showroom Policy</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="#">Sustainability</a>
</div>
</div>
<div class="max-w-container-max mx-auto mt-24 pt-8 border-t border-outline-variant flex flex-col md:flex-row justify-between items-center gap-4">
<p class="font-body-md text-body-md text-on-surface-variant text-[12px]">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
<div class="flex gap-8">
<span class="font-body-md text-body-md text-on-surface-variant text-[12px] cursor-pointer">Privacy</span>
<span class="font-body-md text-body-md text-on-surface-variant text-[12px] cursor-pointer">Terms</span>
</div>
</div>
</footer>
<!-- Mobile Navigation Bar -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1 transition-transform active:scale-90" href="SCREEN_15">
<span class="material-symbols-outlined" data-icon="home">home</span>
<span class="font-label-md text-[10px] uppercase">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 transition-transform active:scale-90 relative" href="SCREEN_9">
<span class="material-symbols-outlined" data-icon="auto_awesome_motion">auto_awesome_motion</span>
<span class="font-label-md text-[10px] uppercase">Collections</span>
<span class="absolute -bottom-1 w-1 h-1 bg-secondary rounded-full"></span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 transition-transform active:scale-90" href="SCREEN_14">
<span class="material-symbols-outlined" data-icon="chat_bubble">chat_bubble</span>
<span class="font-label-md text-[10px] uppercase">Contact</span>
</a>
</nav>
<script>
    function toggleDrawer() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('drawer-overlay');
        const isClosed = drawer.classList.contains('closed');
        
        if (isClosed) {
            drawer.classList.remove('closed');
            overlay.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        } else {
            drawer.classList.add('closed');
            overlay.classList.add('hidden');
            document.body.style.overflow = '';
        }
    }
</script>
</body></html>

<!-- Sanitary & Bathroom - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary-fixed-dim": "#bcc7dd",
                    "on-primary-fixed-variant": "#3d4759",
                    "on-secondary-fixed-variant": "#5d4201",
                    "inverse-surface": "#2f3130",
                    "inverse-on-surface": "#f1f1ef",
                    "secondary": "#775a19",
                    "surface-container-high": "#e9e8e6",
                    "error-container": "#ffdad6",
                    "outline-variant": "#c5c6cd",
                    "surface-container-lowest": "#ffffff",
                    "on-primary-fixed": "#111c2c",
                    "tertiary": "#000000",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "primary": "#000000",
                    "surface-variant": "#e3e2e0",
                    "surface": "#faf9f7",
                    "primary-fixed": "#d8e3f9",
                    "surface-container-low": "#f4f3f1",
                    "secondary-fixed-dim": "#e9c176",
                    "on-background": "#1a1c1b",
                    "on-tertiary-container": "#7f848a",
                    "tertiary-fixed": "#dfe3e9",
                    "inverse-primary": "#bcc7dd",
                    "on-primary-container": "#798498",
                    "secondary-fixed": "#ffdea5",
                    "surface-container": "#efeeec",
                    "on-tertiary-fixed-variant": "#42474c",
                    "tertiary-container": "#171c20",
                    "on-error": "#ffffff",
                    "error": "#ba1a1a",
                    "on-primary": "#ffffff",
                    "surface-tint": "#545f72",
                    "on-error-container": "#93000a",
                    "background": "#faf9f7",
                    "on-tertiary-fixed": "#171c20",
                    "on-tertiary": "#ffffff",
                    "on-surface-variant": "#44474c",
                    "on-secondary": "#ffffff",
                    "secondary-container": "#fed488",
                    "primary-container": "#111c2c",
                    "on-secondary-container": "#785a1a",
                    "surface-bright": "#faf9f7",
                    "on-secondary-fixed": "#261900",
                    "on-surface": "#1a1c1b",
                    "surface-container-highest": "#e3e2e0",
                    "surface-dim": "#dadad8",
                    "outline": "#75777d"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "margin-desktop": "64px",
                    "gutter": "24px",
                    "base": "8px",
                    "margin-mobile": "20px",
                    "section-gap": "120px",
                    "container-max": "1280px"
            },
            "fontFamily": {
                    "body-lg": ["Manrope"],
                    "headline-lg-mobile": ["Playfair Display"],
                    "body-md": ["Manrope"],
                    "label-md": ["Manrope"],
                    "headline-md": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "display-lg": ["Playfair Display"]
            },
            "fontSize": {
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            vertical-align: middle;
        }
        body {
            background-color: #faf9f7;
            color: #1a1c1b;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #efeeec;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #75777d;
        }
        /* Navigation Drawer styles */
        #nav-drawer {
            transform: translateX(-100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #nav-overlay {
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.4s ease-in-out;
        }
        #nav-overlay.open {
            opacity: 1;
            pointer-events: auto;
        }
    </style>
</head>
<body class="font-body-md text-body-md antialiased overflow-x-hidden">
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md fixed top-0 w-full z-50 border-b border-outline-variant">
<div class="flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full max-w-container-max mx-auto">
<div class="flex items-center gap-4">
<button class="active:scale-95 transition-transform duration-200 text-on-surface-variant hover:bg-surface-container-low p-2" onclick="toggleNav()">
<span class="material-symbols-outlined">menu</span>
</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
</div>
<nav class="hidden md:flex gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors duration-300" href="SCREEN_15">HOME</a>
<a class="font-label-md text-label-md text-secondary border-b border-secondary pb-1" href="SCREEN_9">COLLECTIONS</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors duration-300" href="#">JOURNAL</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors duration-300" href="SCREEN_14">CONTACT</a>
</nav>
<div class="flex items-center gap-2">
<button class="active:scale-95 transition-transform duration-200 text-primary p-2">
<span class="material-symbols-outlined">search</span>
</button>
</div>
</div>
</header>
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-black/40 z-[60]" id="nav-overlay" onclick="toggleNav()"></div>
<!-- Navigation Drawer -->
<aside class="fixed top-0 left-0 h-full w-[85%] max-w-[400px] bg-surface z-[70] shadow-2xl overflow-y-auto custom-scrollbar" id="nav-drawer">
<div class="flex flex-col min-h-full">
<div class="flex items-center justify-between p-6 border-b border-outline-variant sticky top-0 bg-surface z-10">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15" onclick="toggleNav()">AJILE</a>
<button class="p-2 hover:bg-surface-container-low rounded-full transition-colors" onclick="toggleNav()">
<span class="material-symbols-outlined">close</span>
</button>
</div>
<nav class="flex-1 px-8 py-10 flex flex-col gap-1">
<a class="font-headline-md text-2xl py-3 hover:text-secondary transition-colors border-b border-transparent hover:border-outline-variant" href="SCREEN_15">Home</a>
<a class="font-headline-md text-2xl py-3 hover:text-secondary transition-colors border-b border-transparent hover:border-outline-variant" href="#">About Us</a>
<a class="font-headline-md text-2xl py-3 text-secondary border-b border-transparent" href="SCREEN_9">Collections</a>
<!-- Category Group -->
<div class="flex flex-col gap-2 mt-4 pb-4 mb-4 border-b border-outline-variant">
<span class="font-label-md text-[10px] text-on-surface-variant uppercase tracking-[0.2em] mb-2">Our Solutions</span>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Showroom</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Lighting</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Door Hardware</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Wardrobe Fittings</a>
<a class="font-label-md text-label-md text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="SCREEN_8">Sanitary &amp; Bathrooms</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Kitchen</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary uppercase tracking-widest py-1 flex items-center gap-2" href="#">Flooring</a>
</div>
<a class="font-headline-md text-2xl py-3 hover:text-secondary transition-colors" href="SCREEN_14">Contact Us</a>
</nav>
<div class="p-8 bg-surface-container-low mt-auto">
<div class="flex flex-col gap-4">
<span class="font-label-md text-[10px] text-on-surface-variant uppercase tracking-[0.2em]">Regional Headquarters</span>
<p class="font-body-md text-sm leading-relaxed text-on-surface-variant">124 Architectural Way,<br/>Industrial District, Dubai, UAE</p>
<div class="flex gap-6 pt-2">
<a class="text-secondary hover:opacity-70 transition-opacity" href="mailto:info@ajile.ae">
<span class="material-symbols-outlined">mail</span>
</a>
<a class="text-secondary hover:opacity-70 transition-opacity" href="tel:+97140000000">
<span class="material-symbols-outlined">phone</span>
</a>
</div>
</div>
</div>
</div>
</aside>
<main class="pt-24 pb-section-gap">
<!-- Back Link and Hero Section -->
<section class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto mb-12">
<a class="inline-flex items-center gap-2 font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors mb-8 group" href="SCREEN_9">
<span class="material-symbols-outlined text-[18px] transition-transform group-hover:-translate-x-1">arrow_back</span>
            BACK TO COLLECTIONS
        </a>
<div class="flex flex-col gap-4 max-w-2xl">
<span class="font-label-md text-label-md text-secondary tracking-widest uppercase">Curated Inventory</span>
<h1 class="font-headline-lg text-headline-lg md:text-display-lg text-primary leading-tight">Plumbing &amp; Bathroom</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant">A meticulous collection of sanitary fixtures designed for architectural excellence. From artisanal faucets to precision-engineered water closets.</p>
</div>
</section>
<!-- Filters and Sorting Cluster -->
<section class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto mb-12 sticky top-16 z-40 bg-surface/80 backdrop-blur-sm py-4 border-b border-outline-variant">
<div class="flex flex-wrap items-center justify-between gap-gutter">
<div class="flex gap-4 items-center">
<span class="font-label-md text-label-md text-on-surface-variant">FILTER BY FINISH:</span>
<div class="flex gap-2">
<button class="px-4 py-1.5 border border-primary bg-primary text-on-primary font-label-md text-label-md">ALL</button>
<button class="px-4 py-1.5 border border-outline hover:border-secondary transition-colors font-label-md text-label-md">GOLD</button>
<button class="px-4 py-1.5 border border-outline hover:border-secondary transition-colors font-label-md text-label-md">MATTE BLACK</button>
<button class="px-4 py-1.5 border border-outline hover:border-secondary transition-colors font-label-md text-label-md">CHROME</button>
</div>
</div>
<div class="flex items-center gap-2">
<span class="font-label-md text-label-md text-on-surface-variant">SORT:</span>
<button class="flex items-center gap-1 font-label-md text-label-md hover:text-secondary">
                    RELEVANCE <span class="material-symbols-outlined text-[18px]">expand_more</span>
</button>
</div>
</div>
</section>
<!-- Product List Section -->
<section class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="flex flex-col gap-section-gap">
<!-- Category 01: Water Closets -->
<div class="group">
<div class="flex items-baseline gap-4 mb-8 border-b border-outline-variant pb-2">
<h2 class="font-headline-md text-headline-md text-primary uppercase tracking-tighter">01. Water Closets</h2>
<span class="font-label-md text-label-md text-secondary">ARCHITECTURAL CERAMICS</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-gutter">
<!-- WC Item 01 -->
<div class="flex flex-col gap-4">
<div class="aspect-[4/5] overflow-hidden bg-surface-container relative group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7QuBPLfgaiu7b_gerN6--OjgGM8tBV2qFCE6rZhJoxEQn0YG6fji78BSQrZ4kEFckMzXk5UEX88qCT1dYGoauExTq01zsmOCKaaiaKyoJxBTmhd4K3OSvrtHhGFsUI4KAl-NM49ZrHURsGbrM3GIimkGRtsdlTxhx4-nVPNj08axAP_AAbbFm4LGga0GIh-n3LJNKSS69HNVjP1Skr0Pn5e5QHEJYUvRGSN15gIRaURpXEk8BNqdQOQK2ctgAYDBsvjAPQyT2LQSB"/>
<div class="absolute top-4 left-4 bg-primary text-on-primary px-3 py-1 font-label-md text-label-md">ONE-PIECE</div>
</div>
<div class="flex flex-col gap-2">
<div class="flex justify-between items-start">
<h3 class="font-headline-md text-headline-md">The Monolith WC</h3>
<span class="font-body-md text-body-md text-on-surface-variant">$1,250</span>
</div>
<div class="flex gap-2">
<span class="bg-surface-container-high px-2 py-0.5 font-label-md text-[10px] uppercase tracking-wider text-primary">Solid Surface</span>
<span class="bg-surface-container-high px-2 py-0.5 font-label-md text-[10px] uppercase tracking-wider text-primary">Dual Flush</span>
</div>
<p class="text-on-surface-variant font-body-md max-w-sm">A seamless floor-mounted silhouette with a whisper-quiet soft close mechanism and Nanoglaze finish.</p>
</div>
</div>
<!-- WC Item 02 -->
<div class="flex flex-col gap-4">
<div class="aspect-[4/5] overflow-hidden bg-surface-container relative group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBWMQdskBHm1mFkGrOV357p5nApJKao2wQ2jSdCL1hAwrq2pnEy7TDVSKnXXnGBABaDGhFKclNm_VJBLUg2cz-W2mXVgbVvHAUiww05DddG1ItgJGdBfX6qMen9x79wB21Njev0DJMVnw9ROrKeTEHXdS7fj9k35_yWzwqsuEUy11m5assWoan8Ed7XzQwfk7ey15tkbgUnYN989QI_LD761ox6mqNBN9EfmpiVKNT_JijryzkmokgDVijs-ZE2Yp_3LvZ1vN2ItZN2"/>
<div class="absolute top-4 left-4 bg-secondary text-on-secondary px-3 py-1 font-label-md text-label-md">WALL-HUNG</div>
</div>
<div class="flex flex-col gap-2">
<div class="flex justify-between items-start">
<h3 class="font-headline-md text-headline-md">Apex Wall Suite</h3>
<span class="font-body-md text-body-md text-on-surface-variant">$1,480</span>
</div>
<div class="flex gap-2">
<span class="bg-surface-container-high px-2 py-0.5 font-label-md text-[10px] uppercase tracking-wider text-primary">Space Saving</span>
<span class="bg-surface-container-high px-2 py-0.5 font-label-md text-[10px] uppercase tracking-wider text-primary">Matte Finish</span>
</div>
<p class="text-on-surface-variant font-body-md max-w-sm">Elevated design for modern spatial constraints. Features a concealed tank and high-efficiency rimless flushing.</p>
</div>
</div>
</div>
</div>
<!-- Category 02: Faucets -->
<div class="group">
<div class="flex items-baseline gap-4 mb-8 border-b border-outline-variant pb-2">
<h2 class="font-headline-md text-headline-md text-primary uppercase tracking-tighter">02. Faucets &amp; Mixers</h2>
<span class="font-label-md text-label-md text-secondary">ARTISAN METALWORK</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Faucet 01 -->
<div class="flex flex-col gap-4">
<div class="aspect-square bg-surface-container-low overflow-hidden group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBvt7p4TB-MDozzrNT7EdTa_FiZVt1rUHyj1a5TTGn8lnU4uXP6bv1yjUne57K7SN-gFP0P0KBqVxoHhybfpSM2vZXembPjcq5FttnZAF_UFuhXZAm8I6Gfh_HdHpq9q0PUHe3shhTFBtYVY0g3iov8u3YEiToIc4p3wpOMK1mA4jq4Qtj53f5YCigLR66QlxEf1SRD6P88wCDaaWMOUtdt-48OKLFovn2ETesQegCEPBJSjJCeKFou1XagprSCZh9SjFVVBZUPblj1"/>
</div>
<div class="flex flex-col gap-1">
<h3 class="font-label-md text-label-md uppercase tracking-widest text-primary">Aura Tall Mixer</h3>
<p class="text-[12px] font-label-md text-secondary">FINISH: BRUSHED GOLD</p>
<p class="text-on-surface-variant font-body-md text-sm mt-2">Durable PVD finish, ceramic disc cartridge for precise control.</p>
</div>
</div>
<!-- Faucet 02 -->
<div class="flex flex-col gap-4">
<div class="aspect-square bg-surface-container-low overflow-hidden group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA2aChu8Sy28ltXx4eHtw2ZnIiEzXkLypJMcHtCFl943X1qx3V1RiASllBqQPhwqfjMITB8yV5ipR0rS7oG6Y1uLOp2JSkWzbWuGOT_Ffu5jeM1Ra8cYspCk7e-bjS-tSnNMYKG9HzfCVWALk8XvbJ8nehe2PvcopgDgzuA6eZ0rZ4QyHyO4T1D1xgF1TU-vepbbthxVsmC1F4Fpr0ERGQJ97L5NpoRYLSz1Gu3GKShnrA924IGy23sSdzcIGbHKs433IbW8bD7EEaW"/>
</div>
<div class="flex flex-col gap-1">
<h3 class="font-label-md text-label-md uppercase tracking-widest text-primary">Void Deck Tap</h3>
<p class="text-[12px] font-label-md text-secondary">FINISH: MATTE BLACK</p>
<p class="text-on-surface-variant font-body-md text-sm mt-2">Solid brass construction with a scratch-resistant volcanic matte coating.</p>
</div>
</div>
<!-- Faucet 03 -->
<div class="flex flex-col gap-4">
<div class="aspect-square bg-surface-container-low overflow-hidden group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCyPIEhKPg_zHeEpNPg8Z2UfNjKiman2Oa5whxdxIFCaMHzYsTIsCYBh9BjozwGFcGom5vgz9CgVf5TD1JuK9F1irlw4pmjhP8IVn4Oju1-a58ON8jOXmXl1Yu8JCMlmfTEULDiYb2fUsFnDsNz4WITA89C3lZ4-42zvIrjMg6G0-qT8R7lB-uvJH1b3LKoCy2RRjM1UZkf8HFIyDWQ5fHgwwo1itAAqJ4GBk8Eg5CV1hPsRLibTvBcnn3GFP4HF01mF4LngDKPbl3d"/>
</div>
<div class="flex flex-col gap-1">
<h3 class="font-label-md text-label-md uppercase tracking-widest text-primary">Heritage Flow</h3>
<p class="text-[12px] font-label-md text-secondary">FINISH: POLISHED CHROME</p>
<p class="text-on-surface-variant font-body-md text-sm mt-2">Mirror-polished chrome plating for a timeless, high-reflectivity look.</p>
</div>
</div>
</div>
</div>
<!-- Category 03: Shower Sets -->
<div class="group">
<div class="flex items-baseline gap-4 mb-8 border-b border-outline-variant pb-2">
<h2 class="font-headline-md text-headline-md text-primary uppercase tracking-tighter">03. Shower Systems</h2>
<span class="font-label-md text-label-md text-secondary">THERMOSTATIC PRECISION</span>
</div>
<div class="flex flex-col md:flex-row gap-gutter">
<!-- Rain Shower Card -->
<div class="flex-1 border border-outline-variant p-8 flex flex-col items-center text-center gap-6 group hover:border-secondary transition-colors">
<div class="w-32 h-32 rounded-full overflow-hidden mb-4">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDDvo_JDohh-qIJsPJBDSfNdyqxE42QawGqfQhAIxFI_y4xNsm86qGoXYignJuy-09todFn2l0y_ApZKLjBCF966mn5hXJc2z9PDkiltYCod2yDbsEFUWyyGsAMICjivxaZpQJ03kUjMj9GrBXSQ0TPV2sPRaSGo4K9noxhRjnlGugmriPiJ9Dq9ZOJSi-TfvkUeE6dYavS_lCHQ9QWk4NdrKiuKCYNLV6LTi4chlDUbWjjZs24FGgB9eDXZhlYOwoBRKBI3LNlmSzC"/>
</div>
<h3 class="font-headline-md text-headline-md">Rainfall Sanctuary</h3>
<p class="font-body-md text-on-surface-variant max-w-xs">A 400mm ceiling-mounted rain panel with air-infusion technology for a voluminous, soft water experience.</p>
<ul class="flex flex-col gap-2 font-label-md text-[12px] uppercase text-on-surface-variant">
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Concealed Valve</li>
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Thermostatic Control</li>
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Gold/Black Options</li>
</ul>
<button class="mt-4 border border-secondary text-secondary px-8 py-2 font-label-md text-label-md hover:bg-secondary hover:text-on-secondary transition-colors">CONFIGURE SYSTEM</button>
</div>
<!-- Concealed Set -->
<div class="flex-1 bg-primary p-8 flex flex-col items-center text-center gap-6 group">
<div class="w-32 h-32 rounded-full overflow-hidden mb-4 border border-outline-variant">
<img class="w-full h-full object-cover grayscale opacity-80" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAjjnkoCOm8Vs4V0mDevygSKhRLhWr5bGrYpDJHC3p-dCWWSpUn93PdDWbONQkxgWaQQXTPabbfqIXRs05A_engVXDuUV3vbq6otxiczrVTpoIPQuIVIX4R5ebyurV8jGwHHODv8joSRVj3xnWAPmer8RTO8mNqOg1mlZrHNcUMomcS7Jkb00d6wrSSFF8-7p-hv8CN7UMoGYIrasHLOyNu1gzMXNc-XEbvp4c9wU0ce4sHmQV14U9v8dt6ChWCvGKJS-BGJ5CWjt4w"/>
</div>
<h3 class="font-headline-md text-headline-md text-white">Axis Concealed Set</h3>
<p class="font-body-md text-on-primary-container max-w-xs">Minimalist wall-integrated hardware that reduces visual clutter. Featuring our proprietary 3-way diverter.</p>
<ul class="flex flex-col gap-2 font-label-md text-[12px] uppercase text-on-primary-container">
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Flush Mount</li>
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Anti-Scald Tech</li>
<li class="flex items-center gap-2 justify-center"><span class="material-symbols-outlined text-[16px]">check</span> Solid Brass</li>
</ul>
<button class="mt-4 bg-white text-primary px-8 py-2 font-label-md text-label-md hover:bg-secondary-fixed-dim transition-colors">REQUEST QUOTE</button>
</div>
</div>
</div>
<!-- Category 04: Vanities -->
<div class="group">
<div class="flex items-baseline gap-4 mb-8 border-b border-outline-variant pb-2">
<h2 class="font-headline-md text-headline-md text-primary uppercase tracking-tighter">04. Bespoke Vanities</h2>
<span class="font-label-md text-label-md text-secondary">ARCHITECTURAL FURNITURE</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div class="flex flex-col gap-6">
<div class="aspect-[16/9] bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD-9YB1I8vqlou0e7d_FXAEb9QV6-D3523-YjHakOiKCmSh2Gp9a5zz0XAp4RqEqesnDD6Mcajb68vjomjjuVeVfdBDHQUnbSRYhU6nHb5mQf5lw6bY2GB2hMW7PNFCmKWf8HuEI158lW9KMLjUhM6tmeMRBakR009JKbTIo6YdGQTPC2QybmDIG2rjsQJFm8QIGB3AlFc18bf1sJbvy_y-d4gSKGUumNviXQe-7BW24lxjItul-ggLIaits8ZLo8IzeLgjCMqBPPxz"/>
</div>
<div class="flex flex-col gap-3">
<div class="flex justify-between items-end">
<h3 class="font-headline-md text-headline-md">Walnut Floating Suite</h3>
<span class="font-label-md text-label-md text-on-surface-variant">FROM $2,100</span>
</div>
<p class="font-body-md text-on-surface-variant">Solid American Walnut with a moisture-resistant marine-grade finish. Topped with seamless Alpine White quartz.</p>
<div class="flex gap-4 border-t border-outline-variant pt-4">
<div>
<p class="font-label-md text-[10px] text-secondary uppercase">Material</p>
<p class="font-body-md text-sm">Solid Wood / Stone</p>
</div>
<div>
<p class="font-label-md text-[10px] text-secondary uppercase">Warranty</p>
<p class="font-body-md text-sm">15 Year Limited</p>
</div>
</div>
</div>
</div>
<div class="flex flex-col gap-6">
<div class="aspect-[16/9] bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAy28ol8qPHG6cIwVX7HFck1-IWEla0BZ4XqW9dmPBFnbvBRrFdEoHk9X0wuuBZ2RyqWPEMO1SYFA1ZsOrYlkbPHnNnyJUnQEAPUlaXNjZAutxtwzX79ON5ihgbxJ95MWW6AkakQ99v_QNED0el7RUIwBXaGLQQxqoJrVQneYvwL3NjM-EgRkJh6n8vgEEmEWCL0VtlBT_tBdWfK0fRFNcyySxo1Qk0ZIVwbPpT2YjBv1HCiUpiy6w8IrPVNogLAMsjJh_T0rzZX5k0"/>
</div>
<div class="flex flex-col gap-3">
<div class="flex justify-between items-end">
<h3 class="font-headline-md text-headline-md">Fluted Oak Double</h3>
<span class="font-label-md text-label-md text-on-surface-variant">FROM $3,450</span>
</div>
<p class="font-body-md text-on-surface-variant">Architectural fluting detail with soft-close tandem drawers and optional integrated LED lighting.</p>
<div class="flex gap-4 border-t border-outline-variant pt-4">
<div>
<p class="font-label-md text-[10px] text-secondary uppercase">Detailing</p>
<p class="font-body-md text-sm">Precision Fluted</p>
</div>
<div>
<p class="font-label-md text-[10px] text-secondary uppercase">Configurations</p>
<p class="font-body-md text-sm">Single / Double</p>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full py-section-gap px-margin-mobile border-t border-outline-variant mt-section-gap bg-surface-container">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left w-full">
<div class="font-headline-md text-headline-md text-primary mb-4 uppercase">AJILE PREMIUM FINISHES</div>
<div class="grid grid-cols-1 md:grid-cols-4 w-full gap-8 md:gap-16">
<div class="flex flex-col gap-4">
<p class="font-body-md text-on-surface-variant">The region's most curated selection of architectural finishes, plumbing, and sanitary solutions for the discerning professional.</p>
</div>
<div class="flex flex-col gap-2">
<span class="font-label-md text-label-md text-secondary uppercase mb-2">Connect</span>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">WhatsApp</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Instagram</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">LinkedIn</a>
</div>
<div class="flex flex-col gap-2">
<span class="font-label-md text-label-md text-secondary uppercase mb-2">Support</span>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Showroom Policy</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Sustainability</a>
<a class="font-body-md text-on-surface-variant hover:text-secondary transition-opacity" href="#">Technical Docs</a>
</div>
<div class="flex flex-col gap-2">
<span class="font-label-md text-label-md text-secondary uppercase mb-2">Office</span>
<p class="font-body-md text-on-surface-variant">124 Architectural Way,<br/>Industrial District, Dubai, UAE</p>
</div>
</div>
<div class="mt-12 pt-8 border-t border-outline-variant w-full flex justify-between items-center">
<p class="font-body-md text-body-md text-on-surface-variant uppercase tracking-widest text-[12px]">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
<div class="flex gap-4">
<span class="material-symbols-outlined text-secondary">diamond</span>
<span class="material-symbols-outlined text-secondary">verified</span>
</div>
</div>
</div>
</footer>
<!-- BottomNavBar -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant">
<div class="flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_15">
<span class="material-symbols-outlined">home</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="SCREEN_9">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="#">
<span class="material-symbols-outlined">auto_stories</span>
<span class="font-label-md text-[10px]">Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_14">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</div>
</nav>
<script>
    function toggleNav() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('nav-overlay');
        drawer.classList.toggle('open');
        overlay.classList.toggle('open');
        document.body.classList.toggle('overflow-hidden');
    }
</script>
</body></html>

<!-- Kitchen Systems - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Kitchen Systems | AJILE PREMIUM FINISHES</title>
<!-- Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&amp;family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "primary": "#000000",
                    "on-surface": "#1a1c1b",
                    "on-secondary-container": "#785a1a",
                    "on-secondary": "#ffffff",
                    "on-primary": "#ffffff",
                    "on-background": "#1a1c1b",
                    "on-tertiary-container": "#7f848a",
                    "on-secondary-fixed": "#261900",
                    "tertiary": "#000000",
                    "secondary-fixed-dim": "#e9c176",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "surface-container-high": "#e9e8e6",
                    "primary-fixed": "#d8e3f9",
                    "surface-container-low": "#f4f3f1",
                    "inverse-on-surface": "#f1f1ef",
                    "primary-container": "#111c2c",
                    "on-surface-variant": "#44474c",
                    "secondary-fixed": "#ffdea5",
                    "tertiary-container": "#171c20",
                    "background": "#faf9f7",
                    "surface-variant": "#e3e2e0",
                    "secondary-container": "#fed488",
                    "on-primary-fixed": "#111c2c",
                    "error-container": "#ffdad6",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-primary-container": "#798498",
                    "inverse-surface": "#2f3130",
                    "surface-container-highest": "#e3e2e0",
                    "on-primary-fixed-variant": "#3d4759",
                    "error": "#ba1a1a",
                    "on-tertiary-fixed-variant": "#42474c",
                    "surface-tint": "#545f72",
                    "surface-container-lowest": "#ffffff",
                    "surface-bright": "#faf9f7",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-error-container": "#93000a",
                    "surface-dim": "#dadad8",
                    "surface-container": "#efeeec",
                    "on-tertiary-fixed": "#171c20",
                    "surface": "#faf9f7",
                    "on-error": "#ffffff",
                    "on-tertiary": "#ffffff",
                    "outline": "#75777d"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "section-gap": "120px",
                    "margin-mobile": "20px",
                    "margin-desktop": "64px",
                    "container-max": "1280px",
                    "base": "8px",
                    "gutter": "24px"
            },
            "fontFamily": {
                    "label-md": ["Manrope"],
                    "display-lg": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "body-lg": ["Manrope"],
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "body-md": ["Manrope"]
            },
            "fontSize": {
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        .backdrop-blur-md {
            backdrop-filter: blur(12px);
        }
        /* Navigation Drawer styles */
        #nav-drawer {
            transform: translateX(-100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #nav-overlay {
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.4s ease;
        }
        #nav-overlay.open {
            opacity: 1;
            pointer-events: auto;
        }
    </style>
<style>
        body {
            min-height: max(884px, 100dvh);
        }
    </style>
</head>
<body class="bg-background text-on-surface selection:bg-secondary-container selection:text-on-secondary-container overflow-x-hidden">
<!-- Navigation Drawer -->
<div class="fixed inset-0 z-[100] flex" id="nav-drawer-container">
<div class="bg-black/40 fixed inset-0" id="nav-overlay" onclick="toggleDrawer()"></div>
<div class="bg-surface w-[85%] max-w-sm h-full relative z-[101] flex flex-col p-8 overflow-y-auto" id="nav-drawer">
<div class="flex justify-between items-center mb-12">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
<button class="p-2" onclick="toggleDrawer()">
<span class="material-symbols-outlined">close</span>
</button>
</div>
<nav class="flex flex-col gap-6">
<a class="font-headline-md text-headline-md text-primary" href="SCREEN_15">Home</a>
<a class="font-headline-md text-headline-md text-primary" href="#">About Us</a>
<a class="font-headline-md text-headline-md text-secondary" href="SCREEN_9">Collections</a>
<a class="font-headline-md text-headline-md text-primary" href="#">Showroom</a>
<div class="flex flex-col gap-4 mt-2">
<p class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest border-b border-outline-variant pb-2">Categories</p>
<div class="flex flex-col gap-4 ml-2">
<a class="font-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Lighting</a>
<a class="font-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Door Hardware</a>
<a class="font-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Wardrobe Fittings</a>
<a class="font-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Sanitary &amp; Bathrooms</a>
<a class="font-body-lg text-secondary font-medium" href="#">Kitchen</a>
<a class="font-body-lg text-on-surface hover:text-secondary transition-colors" href="#">Flooring</a>
</div>
</div>
<a class="font-headline-md text-headline-md text-primary mt-4" href="SCREEN_14">Contact Us</a>
</nav>
<div class="mt-auto pt-12 border-t border-outline-variant">
<div class="flex flex-col gap-4">
<p class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest">Connect</p>
<div class="flex gap-6">
<a class="text-on-surface-variant hover:text-secondary" href="#">Instagram</a>
<a class="text-on-surface-variant hover:text-secondary" href="#">WhatsApp</a>
</div>
</div>
</div>
</div>
</div>
<!-- TopAppBar -->
<header class="bg-surface/90 backdrop-blur-md fixed top-0 w-full z-50 border-b border-outline-variant flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full">
<div class="flex items-center gap-4">
<button class="hover:bg-surface-container-low transition-colors duration-300 p-2 active:scale-95 transition-transform duration-200" onclick="toggleDrawer()">
<span class="material-symbols-outlined text-primary">menu</span>
</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
</div>
<nav class="hidden md:flex items-center gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="SCREEN_15">Home</a>
<a class="font-label-md text-label-md text-secondary border-b border-secondary pb-1" href="SCREEN_9">Collections</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Journal</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="SCREEN_14">Contact</a>
</nav>
<div class="flex items-center">
<button class="hover:bg-surface-container-low transition-colors duration-300 p-2 active:scale-95 transition-transform duration-200">
<span class="material-symbols-outlined text-primary">search</span>
</button>
</div>
</header>
<main class="pt-16 pb-section-gap">
<!-- Navigation Back Link -->
<section class="mt-12 px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<a class="inline-flex items-center gap-2 font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors uppercase tracking-widest group" href="SCREEN_9">
<span class="material-symbols-outlined text-[18px] group-hover:-translate-x-1 transition-transform">arrow_back</span>
            Back to Collections
        </a>
</section>
<!-- Hero / Section Header -->
<section class="mt-12 px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-gutter border-b border-outline-variant pb-12">
<div class="max-w-2xl">
<span class="font-label-md text-label-md text-secondary uppercase tracking-[0.3em] mb-4 block">Professional Series</span>
<h1 class="font-display-lg text-[48px] md:text-display-lg text-primary leading-tight">Kitchen Systems</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant mt-6 leading-relaxed">
                    Meticulously engineered solutions for the culinary heart of the home. Our systems combine architectural precision with tactile luxury, ensuring every interaction is effortless and every finish is permanent.
                </p>
</div>
<div class="flex gap-4">
<button class="bg-primary text-on-primary px-8 py-4 font-label-md text-label-md uppercase tracking-widest hover:bg-on-surface-variant transition-colors duration-300">Request Catalog</button>
</div>
</div>
</section>
<!-- Category Grid -->
<section class="mt-16 px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<div class="group cursor-pointer">
<div class="overflow-hidden border border-outline-variant mb-6">
<img class="w-full aspect-[4/5] object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A high-end minimalist kitchen featuring a deep matte black quartz composite sink and a brushed gold professional faucet." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAhV6jPEEhpWtK-NzjPtkTwCaj5Q5Ljjaja4ODuJg-cUiDfsl_pbcUlnEEc2w9ViHjMVtSFaGFqvlrerTAOPxTV9rCE3-k9MhjpUwZrCKknayYJbJPsJ1IxCbNshe0PXe9tL0ZeeY1CwKO05UyibvFccsohXW1pGt05-j42GpTygNRYw4T6bHqA74GLBhIhhQVgOdBobbPAjxFq22iFoiqM90jK2paD3cpn7FlTiWwsN54QQ2s4Mpw1I42k0fAtrkK8mscbOxTwDLMd"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">Sinks &amp; Faucets</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Hand-polished finishes and ergonomic design for the modern chef.</p>
</div>
<div class="group cursor-pointer">
<div class="overflow-hidden border border-outline-variant mb-6">
<img class="w-full aspect-[4/5] object-cover transition-transform duration-700 group-hover:scale-105" data-alt="Close-up detail of architectural cabinet hardware in a rich midnight navy kitchen." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDwUtT2DG1IMGApIm9i293X1hPnEqFN_vAxbMiAnU5L5wSLwJ6gSJbMYjMijGhScPiyzfCwbRdigLqp8_CQ-SHTIqZIrXCfC1utopmnGxXuV-LGDKptfP5jnYiZe9-LVxhqQmWtyYryA6dO92F6s8F_cxgDe-pTn-gtnVdqBSVU8AVa1JwIAlOp3EfRc6oQB7Kjmvrpyzn0LyBtZ0rrF8-f38wSiBH1CUV9IwALk29A2WyYlsQ37vof6izJ4J77ltIKUYlgk6lebTKq"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">Cabinet Hardware</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">The jewelry of the kitchen, machined from solid metals with precision.</p>
</div>
<div class="group cursor-pointer">
<div class="overflow-hidden border border-outline-variant mb-6">
<img class="w-full aspect-[4/5] object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A sophisticated kitchen pantry featuring organized storage solutions." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBjsRpnXcxxICZLwW6MqEyBI8dzoh9XjkD1vza8tVPrvCEh7a5IdIRFFel7fi4SanTe6lNpvdiliH8_E6YkEpZEh5Ky1trhDRqe0bHaht96H0OJFUpp6B_DBRsfIjwDDFEoMboBLRzKd0H5jrLhvgneISb-JEOG3IPEL6u1zGKE0yJ2Y65ruwfZ2RdGWoBlaWFgDBJGLxo9FhRHBRsZ_AzC8B61WCyUTiEMM5aPoTZ_hKpslxKHvZIRRtz6F5wQTbXaU1fYVCHzcSNg"/>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-2">Storage Solutions</h3>
<p class="font-body-md text-body-md text-on-surface-variant line-clamp-2">Intelligent internal systems designed to maximize efficiency and elegance.</p>
</div>
</div>
</section>
<!-- Featured Products - Bento Layout -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="mb-12 text-center md:text-left">
<span class="font-label-md text-label-md text-secondary uppercase tracking-[0.3em] mb-4 block">Curated Selection</span>
<h2 class="font-headline-lg text-headline-lg md:text-headline-lg text-primary">Featured Essentials</h2>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- Main Feature -->
<div class="md:col-span-8 group relative bg-surface-container border border-outline-variant p-1 flex flex-col">
<div class="relative flex-grow overflow-hidden">
<img class="w-full h-[500px] object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A large, luxury kitchen island featuring a black Quartz Composite Sink." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBm74-L8SPESdOiTQgEDGjew558yx7I5Yt0F8rTQDFXE1j9Td9nMTXFnEaNYBuUNWDjO9VQnpBnDUvEqp4gJl8cdCR13pfIqBhBg8kBydv5o9h4nibL48dIsd6m2xBi90nGo0Klg9Eiz4PG4DNLllN_sE5UEgEpGsvBo77ptOLwpP456QKYxFlxfZnOG-zhdoT1LEHOHuRURTfYQ3xu-yrSg30NgqFffMPu-soA-VkS-1juhM6BIhubffycbQzj_uo9QJxrwNZWRwj9"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500 flex flex-col justify-end p-12">
<h4 class="font-headline-md text-headline-md text-on-primary mb-2">Quartz Composite Sink</h4>
<p class="font-body-md text-body-md text-on-primary/80 mb-6">Heat-resistant, anti-bacterial, and architectural in form.</p>
<button class="w-fit border border-on-primary text-on-primary px-8 py-3 font-label-md text-label-md uppercase tracking-widest hover:bg-on-primary hover:text-primary transition-all">View Details</button>
</div>
</div>
<div class="p-8 md:hidden">
<h4 class="font-headline-md text-headline-md text-primary">Quartz Composite Sink</h4>
</div>
</div>
<!-- Side Feature 1 -->
<div class="md:col-span-4 flex flex-col gap-gutter">
<div class="flex-grow bg-surface-container-low border border-outline-variant p-6 group cursor-pointer flex flex-col">
<div class="overflow-hidden mb-6 flex-grow">
<img class="w-full h-[200px] object-cover transition-transform duration-500 group-hover:scale-110" data-alt="Extreme close-up of a Pull-out Professional Faucet with a brushed steel finish." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDF7s6j1o7F7-Fe49AxdJwCXlbh5a1JOtLcyZ9fCA3gJqkeIKajVor8n-FeUCk4J5Fqyp9AfUF-0sSMKDuYzdljS9J3SLPUiOc_3ku5pkpjCZViaDZFvKT7JQzHGb-iQ71QLBtp-79xhf9ucs-MLuOts6kHpPh0PSVk8lnsj_flxXR2MTikBAffqcM3UmXF1Z-qb8T0RVrqEiuvj0odizpnRzm9CtAiCRL5AKTidta4TGTjCkEQ3h_KKQ5ayKJ95oKCvOuJNsf20qJL"/>
</div>
<div>
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest mb-2 block">Professional Grade</span>
<h4 class="font-headline-md text-headline-md text-primary mb-2">Pull-out Professional Faucet</h4>
<p class="font-body-md text-body-md text-on-surface-variant">Dual-mode sprayer with ceramic disc technology.</p>
</div>
</div>
<div class="flex-grow bg-primary text-on-primary p-8 flex flex-col justify-between border border-primary group">
<div class="mb-8">
<span class="material-symbols-outlined text-secondary-fixed-dim text-4xl mb-4" data-weight="fill">auto_awesome</span>
<h4 class="font-headline-md text-headline-md mb-2">Corner Carousel System</h4>
<p class="font-body-md text-body-md text-on-primary/60">Maximize unreachable spaces with fluid motion technology.</p>
</div>
<a class="font-label-md text-label-md uppercase tracking-[0.2em] flex items-center gap-2 group-hover:translate-x-2 transition-transform" href="#">
                        Explore Engineering <span class="material-symbols-outlined text-[18px]">trending_flat</span>
</a>
</div>
</div>
</div>
</section>
<!-- Newsletter / Contact CTA -->
<section class="mt-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto bg-surface-container py-24 flex flex-col items-center text-center">
<h2 class="font-headline-lg text-headline-lg text-primary max-w-2xl mb-6">Defining the kitchen with architectural permanence.</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-xl mb-12">Join our professional network to receive curated material samples and technical specifications for your next project.</p>
<form class="w-full max-w-md flex flex-col gap-8">
<div class="relative group">
<input class="w-full bg-transparent border-0 border-b border-outline py-4 px-0 font-label-md text-label-md text-primary focus:ring-0 focus:border-secondary placeholder:text-outline transition-all uppercase tracking-widest" placeholder="YOUR EMAIL ADDRESS" type="email"/>
</div>
<button class="bg-primary text-on-primary w-full py-5 font-label-md text-label-md uppercase tracking-[0.3em] hover:bg-on-surface-variant transition-colors">Join AJILE Professional</button>
</form>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container w-full py-section-gap px-margin-mobile border-t border-outline-variant mt-section-gap">
<div class="flex flex-col md:flex-row items-start justify-between gap-gutter max-w-container-max mx-auto">
<div class="flex flex-col items-start gap-4">
<a class="font-headline-md text-headline-md text-primary uppercase tracking-[0.2em] mb-4" href="SCREEN_15">AJILE</a>
<p class="font-body-md text-body-md text-on-surface-variant max-w-xs mb-8">Curating the world's finest architectural finishes for the most discerning interiors.</p>
<div class="flex gap-6">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Instagram</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">WhatsApp</a>
</div>
</div>
<div class="grid grid-cols-2 gap-16">
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase tracking-widest mb-2">Systems</span>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="SCREEN_9">Kitchen</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Stone</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Wood</a>
</div>
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase tracking-widest mb-2">Support</span>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Showroom Policy</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="#">Sustainability</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-secondary transition-colors" href="SCREEN_14">Contact</a>
</div>
</div>
</div>
<div class="max-w-container-max mx-auto mt-24 pt-8 border-t border-outline-variant/30 flex flex-col md:flex-row justify-between items-center gap-4">
<span class="font-body-md text-body-md text-on-surface-variant/60 uppercase tracking-widest">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</span>
<div class="flex gap-8">
<a class="font-label-md text-label-md text-on-surface-variant/60 hover:text-primary transition-colors" href="#">Privacy</a>
<a class="font-label-md text-label-md text-on-surface-variant/60 hover:text-primary transition-colors" href="#">Terms</a>
</div>
</div>
</footer>
<!-- BottomNavBar (Mobile only) -->
<nav class="md:hidden bg-surface fixed bottom-0 w-full z-50 border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="SCREEN_15">
<span class="material-symbols-outlined">home_app_logo</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary dark:text-secondary-fixed-dim flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full active:scale-90 transition-transform" href="SCREEN_9">
<span class="material-symbols-outlined">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="#">
<span class="material-symbols-outlined">auto_stories</span>
<span class="font-label-md text-[10px]">Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1 hover:text-primary transition-colors active:scale-90 transition-transform" href="SCREEN_14">
<span class="material-symbols-outlined">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
<script>
    function toggleDrawer() {
        const drawer = document.getElementById('nav-drawer');
        const overlay = document.getElementById('nav-overlay');
        drawer.classList.toggle('open');
        overlay.classList.toggle('open');
        document.body.classList.toggle('overflow-hidden');
    }
</script>
</body></html>

<!-- Flooring - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary": "#000000",
                        "on-surface": "#1a1c1b",
                        "on-secondary-container": "#785a1a",
                        "on-secondary": "#ffffff",
                        "on-primary": "#ffffff",
                        "on-background": "#1a1c1b",
                        "on-tertiary-container": "#7f848a",
                        "on-secondary-fixed": "#261900",
                        "tertiary": "#000000",
                        "secondary-fixed-dim": "#e9c176",
                        "inverse-primary": "#bcc7dd",
                        "tertiary-fixed-dim": "#c2c7cd",
                        "surface-container-high": "#e9e8e6",
                        "primary-fixed": "#d8e3f9",
                        "surface-container-low": "#f4f3f1",
                        "inverse-on-surface": "#f1f1ef",
                        "primary-container": "#111c2c",
                        "on-surface-variant": "#44474c",
                        "secondary-fixed": "#ffdea5",
                        "tertiary-container": "#171c20",
                        "background": "#faf9f7",
                        "surface-variant": "#e3e2e0",
                        "secondary-container": "#fed488",
                        "on-primary-fixed": "#111c2c",
                        "error-container": "#ffdad6",
                        "tertiary-fixed": "#dfe3e9",
                        "primary-fixed-dim": "#bcc7dd",
                        "on-primary-container": "#798498",
                        "inverse-surface": "#2f3130",
                        "surface-container-highest": "#e3e2e0",
                        "on-primary-fixed-variant": "#3d4759",
                        "error": "#ba1a1a",
                        "on-tertiary-fixed-variant": "#42474c",
                        "surface-tint": "#545f72",
                        "surface-container-lowest": "#ffffff",
                        "surface-bright": "#faf9f7",
                        "secondary": "#775a19",
                        "outline-variant": "#c5c6cd",
                        "on-secondary-fixed-variant": "#5d4201",
                        "on-error-container": "#93000a",
                        "surface-dim": "#dadad8",
                        "surface-container": "#efeeec",
                        "on-tertiary-fixed": "#171c20",
                        "surface": "#faf9f7",
                        "on-error": "#ffffff",
                        "on-tertiary": "#ffffff",
                        "outline": "#75777d"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "section-gap": "120px",
                        "margin-mobile": "20px",
                        "margin-desktop": "64px",
                        "container-max": "1280px",
                        "base": "8px",
                        "gutter": "24px"
                    },
                    "fontFamily": {
                        "label-md": ["Manrope"],
                        "display-lg": ["Playfair Display"],
                        "headline-md": ["Playfair Display"],
                        "body-lg": ["Manrope"],
                        "headline-lg-mobile": ["Playfair Display"],
                        "headline-lg": ["Playfair Display"],
                        "body-md": ["Manrope"]
                    },
                    "fontSize": {
                        "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                        "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                        "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                        "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                        "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                        "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                        "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #faf9f7;
            color: #1a1c1b;
            min-height: max(884px, 100dvh);
        }
        #nav-drawer {
            transform: translateX(-100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-drawer.open {
            transform: translateX(0);
        }
        #nav-overlay {
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.4s ease, visibility 0.4s ease;
        }
        #nav-overlay.open {
            opacity: 1;
            visibility: visible;
        }
        .nav-link-stagger {
            opacity: 0;
            transform: translateY(10px);
            transition: opacity 0.4s ease, transform 0.4s ease;
        }
        #nav-drawer.open .nav-link-stagger {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-background text-on-surface overflow-x-hidden">
<!-- Navigation Drawer Overlay -->
<div class="fixed inset-0 bg-black/40 z-[60] backdrop-blur-sm" id="nav-overlay" onclick="toggleDrawer()"></div>
<!-- Navigation Drawer -->
<aside class="fixed left-0 top-0 h-full w-[320px] bg-surface z-[70] shadow-2xl flex flex-col p-8 overflow-y-auto" id="nav-drawer">
<div class="flex justify-between items-center mb-10">
<span class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase">AJILE</span>
<button class="material-symbols-outlined cursor-pointer p-2 hover:bg-surface-container-low transition-colors" data-icon="close" onclick="toggleDrawer()">close</button>
</div>
<nav class="flex flex-col gap-5">
<a class="nav-link-stagger font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="SCREEN_15" style="transition-delay: 100ms;">Home</a>
<a class="nav-link-stagger font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="#" style="transition-delay: 150ms;">About Us</a>
<a class="nav-link-stagger font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="SCREEN_9" style="transition-delay: 200ms;">Collections</a>
<a class="nav-link-stagger font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="#" style="transition-delay: 250ms;">Showroom</a>
<div class="h-px bg-outline-variant my-2"></div>
<div class="flex flex-col gap-4 pl-4">
<a class="nav-link-stagger font-label-md text-label-md text-on-surface-variant hover:text-primary" href="#" style="transition-delay: 300ms;">Lighting</a>
<a class="nav-link-stagger font-label-md text-label-md text-on-surface-variant hover:text-primary" href="#" style="transition-delay: 350ms;">Door Hardware</a>
<a class="nav-link-stagger font-label-md text-label-md text-on-surface-variant hover:text-primary" href="#" style="transition-delay: 400ms;">Wardrobe Fittings</a>
<a class="nav-link-stagger font-label-md text-label-md text-on-surface-variant hover:text-primary" href="#" style="transition-delay: 450ms;">Sanitary &amp; Bathrooms</a>
<a class="nav-link-stagger font-label-md text-label-md text-on-surface-variant hover:text-primary" href="#" style="transition-delay: 500ms;">Kitchen</a>
<a class="nav-link-stagger font-label-md text-label-md text-secondary" href="#" style="transition-delay: 550ms;">Flooring</a>
</div>
<div class="h-px bg-outline-variant my-2"></div>
<a class="nav-link-stagger font-headline-md text-headline-md text-primary hover:text-secondary transition-colors" href="SCREEN_14" style="transition-delay: 600ms;">Contact Us</a>
</nav>
</aside>
<!-- Top Navigation Shell -->
<header class="bg-surface/90 backdrop-blur-md border-b border-outline-variant fixed top-0 w-full z-50 flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-primary cursor-pointer hover:bg-surface-container-low transition-colors p-2" data-icon="menu" onclick="toggleDrawer()">menu</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="SCREEN_15">AJILE</a>
</div>
<nav class="hidden md:flex items-center gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Exotic Stone</a>
<a class="font-label-md text-label-md text-secondary border-b border-secondary pb-1" href="#">Flooring</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Architectural Metal</a>
</nav>
<div class="flex items-center gap-2">
<button class="material-symbols-outlined text-primary cursor-pointer hover:bg-surface-container-low transition-colors p-2" data-icon="search">search</button>
</div>
</header>
<main class="pt-24 pb-section-gap">
<!-- Hero Section -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop mb-section-gap">
<div class="flex flex-col gap-6 max-w-2xl">
<a class="flex items-center gap-2 font-label-md text-label-md text-secondary hover:opacity-80 transition-opacity" href="SCREEN_9">
<span class="material-symbols-outlined text-sm" data-icon="arrow_back">arrow_back</span>
                    Back to Collections
                </a>
<h1 class="font-display-lg text-display-lg md:text-display-lg text-primary">Flooring Masterpieces</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant">An curated selection of high-performance SPC Vinyl, sustainable Hardwoods, and architectural Trims designed for the most discerning interiors.</p>
</div>
</section>
<!-- Categories Bento Grid -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop mb-section-gap">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter">
<!-- SPC Vinyl -->
<div class="md:col-span-8 group cursor-pointer relative overflow-hidden h-[500px] border border-outline-variant">
<img alt="SPC Vinyl Category" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCAgNgbcGeUf9T54jvhfOwCHqpONWSH5UVnG0DRcRRmx_XEYFUC920IhCtKyEalDnn_1qwac177V0voIrqgC52YAlkRLHtSKqtuwJQtt3bNrJrQVi952NpZbszlBai3Krr-EXjOOsomyuzjQC_Xoh8Ob9tBm0gJxRX1R1RIc5QJ3SorU3fKN7VhcT7C5yK2BSb-Ch3vxCS8pCQug6BtdYrPx3pI5NbzpVEgN1iw8qGmYPOikoNvoUtBy4Mx1BbnYoSR-uGHCJFzUvEa"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent flex flex-col justify-end p-10">
<span class="font-label-md text-label-md text-secondary-fixed mb-2 uppercase tracking-widest">Performance Series</span>
<h2 class="font-headline-lg text-headline-lg text-white mb-4">SPC Vinyl</h2>
<div class="h-0.5 w-12 bg-secondary group-hover:w-24 transition-all duration-300"></div>
</div>
</div>
<!-- Hardwood -->
<div class="md:col-span-4 group cursor-pointer relative overflow-hidden h-[500px] border border-outline-variant">
<img alt="Hardwood Category" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBGsje34E7ChZXGLpVzSymRegq9U8dVmO0CIgKdFDbTpjzvqKURLUraPxZKcBWLb18OcPkaqx3-jH92iP1_J0gBEBqdqHHiFmmAW3iNMk3J5y3NGtiU-LWE_YMxapW92kuSrNVyUjuecmra4AM0lvOwcw8PYInCDAI4V-gid_ot6Fw-v9N0xbAnerRzRypcHsdaZgyQ0XoTvzJ-53g8ynO647E4ndQDmpcKewLqBDwyjmE4cO5aaXLif1NLbW_15RNbecpFHbNHmq9u"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent flex flex-col justify-end p-10">
<span class="font-label-md text-label-md text-secondary-fixed mb-2 uppercase tracking-widest">Natural Heritage</span>
<h2 class="font-headline-lg text-headline-lg text-white mb-4">Hardwood</h2>
<div class="h-0.5 w-12 bg-secondary group-hover:w-24 transition-all duration-300"></div>
</div>
</div>
<!-- Trims & Skirting -->
<div class="md:col-span-12 group cursor-pointer relative overflow-hidden h-[300px] border border-outline-variant">
<img alt="Trims &amp; Skirting Category" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCI9ULCG41Kbt42aeKdbQUjpeKBHp-LjqUASCQSgz1MajoivztpsJckbpWzYTT37Fj2pCe58pWA7I4tK2V25RES_y2uD-22c3jH6Fm8IUMbGNwzFG4uq8qBTwyDoWjYobr8kaY47ttPztx2VB8Eo2deAQ1zSyFJr0qdbq2YkIeq8vKgo09FrFMd8IBSYFEhsvtw1e7s66q_bzSZv0z7aZRHaLvVzu0zskN8Z7A4InjA2Z9sJWMYhE_FOSYCLiu0PvAlCg3Fdeq6gWAY"/>
<div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent flex flex-col justify-end p-10">
<span class="font-label-md text-label-md text-secondary-fixed mb-2 uppercase tracking-widest">Finishing Details</span>
<h2 class="font-headline-lg text-headline-lg text-white mb-4">Trims &amp; Skirting</h2>
<div class="h-0.5 w-12 bg-secondary group-hover:w-24 transition-all duration-300"></div>
</div>
</div>
</div>
</section>
<!-- Featured Products -->
<section class="bg-surface-container py-section-gap">
<div class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop">
<div class="flex justify-between items-end mb-16">
<div>
<span class="font-label-md text-label-md text-secondary uppercase tracking-widest">Handpicked Selection</span>
<h2 class="font-headline-lg text-headline-lg text-primary mt-2">Featured Products</h2>
</div>
<button class="hidden md:block border border-secondary text-secondary px-8 py-3 font-label-md text-label-md hover:bg-secondary/5 transition-colors">View All Products</button>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-gutter">
<!-- Product 1 -->
<div class="flex flex-col group">
<div class="relative aspect-[3/4] overflow-hidden bg-surface-container-low mb-6 border border-outline-variant">
<img alt="Natural Oak SPC" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA3YEyfGvfPH0BOnV9g8rbMTJPpt0pK0vD-uAReRkSOCDsZ7SG9TSXu-bSPOys5We3CdzC-JDF75XPm4BBTmku354KTxE_yw6Bp_z0cssn4sh9VwtajKzF25EKTu0j66iTiVGFoy4Dy65Gv1AaDR3ph1mPwEvyxKPX6HsCVbFefE0THG9Pcfww1mfbrLpVBDhNCaQmoA7EN3Yq70kjRAFKmks5yPkpDOM8kwjq198mFE6KcjXtiIPr4FxDQrYraZ8VKwuHdFpoYucFW"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-label-md">SPC VINYL</span>
</div>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-1">Natural Oak SPC</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">Waterproof, ultra-durable stone polymer core with authentic grain.</p>
<div class="flex gap-2">
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Eco-Friendly</span>
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Sound-Absorbing</span>
</div>
</div>
<!-- Product 2 -->
<div class="flex flex-col group">
<div class="relative aspect-[3/4] overflow-hidden bg-surface-container-low mb-6 border border-outline-variant">
<img alt="Smoked Walnut Plank" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD25BMNGoNls0Ox3bMMArLkFaM236gSIeQOpe_L8rlpuwaXUkQH_p07PmojUACXegCx05RVKzTKc0o-HCJq4lVa7inacjjjbil7sGRmUYzfQMewbtWuVtdu_puRNObP-_EZFmrBR2yshkvjj06X5zIKqsCqaOMO36U74WAjsBGcj-p70kr28igXxAM7f59cwQJ7lIfz-nbeoBlbjv-K5vOY8vdM-fiUmUkKHUDRjhXerWVTcBJpx3zW758uxyTb3Z2BEzuH9sgo7gH8"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-label-md">HARDWOOD</span>
</div>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-1">Smoked Walnut Plank</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">European Walnut, smoked for deep color consistency and hand-oiled.</p>
<div class="flex gap-2">
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Hand-Polished</span>
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Sustainable</span>
</div>
</div>
<!-- Product 3 -->
<div class="flex flex-col group">
<div class="relative aspect-[3/4] overflow-hidden bg-surface-container-low mb-6 border border-outline-variant">
<img alt="Brushed Brass Trim" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD3loVqhcv74LO86xgyfgpl2-rfK7fqnOYjfgRvqhZBjSo59lys4MySn4Pk8pznx-zNQyBnxXpIsa6WrY7mHJAfOYuXeS_hBlXQyER7uFercQ4aOhjBkwW8TLbGTeM55v1XN6yn-9KiDbE1gzEwDfu4B9jMvFmR7hb3T7z3Gd2hARmeUv7CW5mYScTG5RqprLlekMQTkaTxpWatTvmJG1J4EEaAC7vpaJPFWijV_5aoCGsRp9ETF0I297QHuOKxfyC_hK9LGAmkFfz1"/>
<div class="absolute top-4 right-4">
<span class="bg-primary text-on-primary px-3 py-1 font-label-md text-label-md">METAL TRIM</span>
</div>
</div>
<h3 class="font-headline-md text-headline-md text-primary mb-1">Brushed Brass Trim</h3>
<p class="font-body-md text-body-md text-on-surface-variant mb-4">PVD coated solid brass transition for a seamless luxury finish.</p>
<div class="flex gap-2">
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Architectural</span>
<span class="bg-surface-container-highest text-primary px-3 py-1 font-label-md text-[12px] uppercase tracking-tighter">Heavy Duty</span>
</div>
</div>
</div>
</div>
</section>
<!-- Consultation CTA -->
<section class="max-w-container-max mx-auto px-margin-mobile md:px-margin-desktop my-section-gap">
<div class="bg-primary text-on-primary p-12 md:p-24 flex flex-col items-center text-center">
<span class="font-label-md text-label-md text-secondary-fixed uppercase tracking-widest mb-6">Experience Excellence</span>
<h2 class="font-display-lg text-headline-lg md:text-display-lg mb-8 max-w-3xl">Ready to transform your architectural space?</h2>
<div class="flex flex-col md:flex-row gap-6">
<button class="bg-secondary text-white px-10 py-4 font-label-md text-label-md hover:bg-secondary/90 transition-colors">Request a Sample Kit</button>
<button class="border border-white text-white px-10 py-4 font-label-md text-label-md hover:bg-white/10 transition-colors">Book a Consultation</button>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="bg-surface-container border-t border-outline-variant mt-section-gap w-full py-section-gap px-margin-mobile">
<div class="flex flex-col items-start gap-gutter max-w-container-max mx-auto text-left">
<div class="font-headline-md text-headline-md text-primary mb-4">AJILE PREMIUM FINISHES</div>
<div class="grid grid-cols-1 md:grid-cols-4 gap-12 w-full mb-12">
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase">Contact</span>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="SCREEN_14">WhatsApp</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="SCREEN_14">Instagram</a>
</div>
<div class="flex flex-col gap-4">
<span class="font-label-md text-label-md text-primary uppercase">Information</span>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="#">Showroom Policy</a>
<a class="font-body-md text-body-md text-on-surface-variant hover:text-secondary" href="#">Sustainability</a>
</div>
<div class="md:col-span-2">
<span class="font-label-md text-label-md text-primary uppercase mb-4 block">Our Newsletter</span>
<div class="flex border-b border-outline">
<input class="bg-transparent border-none focus:ring-0 w-full font-body-md py-2" placeholder="Your architectural inquiry" type="email"/>
<button class="font-label-md text-secondary px-4">JOIN</button>
</div>
</div>
</div>
<div class="font-body-md text-body-md text-on-surface-variant opacity-60">
                © 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.
            </div>
</div>
</footer>
<!-- Mobile Bottom Nav -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_15">
<span class="material-symbols-outlined" data-icon="home">home</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="SCREEN_9">
<span class="material-symbols-outlined" data-icon="auto_awesome_motion">auto_awesome_motion</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="#">
<span class="material-symbols-outlined" data-icon="auto_stories">auto_stories</span>
<span class="font-label-md text-[10px]">Journal</span>
</a>
<a class="text-on-surface-variant flex flex-col items-center gap-1" href="SCREEN_14">
<span class="material-symbols-outlined" data-icon="chat_bubble">chat_bubble</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
<script>
        function toggleDrawer() {
            const drawer = document.getElementById('nav-drawer');
            const overlay = document.getElementById('nav-overlay');
            drawer.classList.toggle('open');
            overlay.classList.toggle('open');
            document.body.classList.toggle('overflow-hidden');
        }
    </script>
</body></html>

<!-- Contact Us - Ajile Premium Finishes -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&amp;family=Manrope:wght@400;600&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "inverse-surface": "#2f3130",
                    "secondary-fixed-dim": "#e9c176",
                    "tertiary": "#000000",
                    "error-container": "#ffdad6",
                    "outline": "#75777d",
                    "inverse-primary": "#bcc7dd",
                    "tertiary-container": "#171c20",
                    "on-error-container": "#93000a",
                    "secondary-fixed": "#ffdea5",
                    "primary": "#000000",
                    "surface-bright": "#faf9f7",
                    "on-surface": "#1a1c1b",
                    "primary-fixed": "#d8e3f9",
                    "surface-tint": "#545f72",
                    "tertiary-fixed-dim": "#c2c7cd",
                    "on-secondary-fixed": "#261900",
                    "secondary-container": "#fed488",
                    "on-secondary-container": "#785a1a",
                    "on-tertiary-fixed": "#171c20",
                    "tertiary-fixed": "#dfe3e9",
                    "primary-container": "#111c2c",
                    "on-primary": "#ffffff",
                    "surface-container": "#efeeec",
                    "secondary": "#775a19",
                    "outline-variant": "#c5c6cd",
                    "primary-fixed-dim": "#bcc7dd",
                    "on-tertiary-container": "#7f848a",
                    "surface": "#faf9f7",
                    "surface-container-high": "#e9e8e6",
                    "surface-dim": "#dadad8",
                    "surface-container-highest": "#e3e2e0",
                    "on-tertiary": "#ffffff",
                    "on-primary-fixed-variant": "#3d4759",
                    "on-secondary-fixed-variant": "#5d4201",
                    "on-secondary": "#ffffff",
                    "on-surface-variant": "#44474c",
                    "surface-container-low": "#f4f3f1",
                    "surface-variant": "#e3e2e0",
                    "surface-container-lowest": "#ffffff",
                    "on-error": "#ffffff",
                    "error": "#ba1a1a",
                    "background": "#faf9f7",
                    "on-background": "#1a1c1b",
                    "on-primary-container": "#798498",
                    "on-primary-fixed": "#111c2c",
                    "inverse-on-surface": "#f1f1ef",
                    "on-tertiary-fixed-variant": "#42474c"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "container-max": "1280px",
                    "margin-desktop": "64px",
                    "section-gap": "120px",
                    "base": "8px",
                    "gutter": "24px",
                    "margin-mobile": "20px"
            },
            "fontFamily": {
                    "headline-lg-mobile": ["Playfair Display"],
                    "headline-md": ["Playfair Display"],
                    "headline-lg": ["Playfair Display"],
                    "label-md": ["Manrope"],
                    "body-md": ["Manrope"],
                    "body-lg": ["Manrope"],
                    "display-lg": ["Playfair Display"]
            },
            "fontSize": {
                    "headline-lg-mobile": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-md": ["28px", {"lineHeight": "36px", "fontWeight": "500"}],
                    "headline-lg": ["40px", {"lineHeight": "48px", "fontWeight": "600"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.05em", "fontWeight": "600"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "display-lg": ["64px", {"lineHeight": "72px", "letterSpacing": "-0.02em", "fontWeight": "700"}]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 300, 'GRAD' 0, 'opsz' 24;
        }
        input:focus, textarea:focus, select:focus {
            outline: none;
            border-color: #775a19 !important;
        }
        body {
          min-height: max(884px, 100dvh);
        }
        #nav-drawer {
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        #nav-overlay {
            transition: opacity 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
    </style>
</head>
<body class="bg-background text-on-surface selection:bg-secondary-container">
<!-- Navigation Drawer -->
<div class="fixed inset-0 bg-black/50 z-[60] opacity-0 pointer-events-none" id="nav-overlay" onclick="toggleDrawer()"></div>
<aside class="fixed top-0 left-0 bottom-0 w-[85%] max-w-[400px] bg-surface z-[70] transform -translate-x-full border-r border-outline-variant overflow-y-auto" id="nav-drawer">
<div class="p-margin-mobile flex flex-col h-full">
<div class="flex items-center justify-between mb-8">
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary uppercase" href="#">AJILE</a>
<button class="material-symbols-outlined p-2 hover:bg-surface-container-low transition-colors" onclick="toggleDrawer()">close</button>
</div>
<nav class="flex flex-col gap-1">
<a class="font-headline-md text-xl py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">Home</a>
<a class="font-headline-md text-xl py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">About Us</a>
<a class="font-headline-md text-xl py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">Collections</a>
<a class="font-headline-md text-xl py-3 border-b border-outline-variant/30 hover:text-secondary transition-colors" href="#">Showroom</a>
<div class="pt-6 mt-2">
<p class="font-label-md text-label-md text-on-surface-variant uppercase tracking-widest mb-4">Categories</p>
<div class="flex flex-col gap-1">
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Lighting</a>
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Door Hardware</a>
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Wardrobe Fittings</a>
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Sanitary &amp; Bathrooms</a>
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Kitchen</a>
<a class="font-body-lg py-2 hover:text-secondary transition-colors" href="#">Flooring</a>
</div>
</div>
<a class="font-headline-md text-xl py-6 mt-4 border-t border-outline-variant text-secondary" href="#">Contact Us</a>
</nav>
<div class="mt-auto pt-12">
<p class="font-body-md text-on-surface-variant text-xs italic tracking-widest">ARTISANAL EXCELLENCE</p>
<p class="font-body-md text-on-surface-variant text-[10px] mt-1 uppercase">© 2024 AJILE PREMIUM FINISHES</p>
</div>
</div>
</aside>
<script>
        function toggleDrawer() {
            const drawer = document.getElementById('nav-drawer');
            const overlay = document.getElementById('nav-overlay');
            const isOpen = !drawer.classList.contains('-translate-x-full');
            
            if (isOpen) {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('opacity-0', 'pointer-events-none');
                overlay.classList.remove('opacity-100', 'pointer-events-auto');
                document.body.style.overflow = '';
            } else {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('opacity-0', 'pointer-events-none');
                overlay.classList.add('opacity-100', 'pointer-events-auto');
                document.body.style.overflow = 'hidden';
            }
        }
    </script>
<!-- TopAppBar -->
<header class="bg-surface/90 dark:bg-inverse-surface/90 backdrop-blur-md fixed top-0 w-full z-50 border-b border-outline-variant dark:border-outline">
<div class="flex items-center justify-between px-margin-mobile md:px-margin-desktop h-16 w-full max-w-container-max mx-auto">
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-primary dark:text-on-primary hover:bg-surface-container-low dark:hover:bg-inverse-surface transition-colors duration-300 p-2 active:scale-95" onclick="toggleDrawer()">menu</button>
<a class="font-headline-md text-headline-md tracking-[0.2em] text-primary dark:text-on-primary uppercase" href="#">AJILE</a>
</div>
<div class="flex items-center gap-6">
<nav class="hidden md:flex items-center gap-8">
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">Home</a>
<a class="font-label-md text-label-md text-on-surface-variant hover:text-primary transition-colors" href="#">About Us</a>
<a class="font-label-md text-label-md text-secondary border-b border-secondary pb-1" href="#">Contact</a>
</nav>
<button class="material-symbols-outlined text-primary dark:text-on-primary hover:bg-surface-container-low dark:hover:bg-inverse-surface transition-colors duration-300 p-2 active:scale-95">search</button>
</div>
</div>
</header>
<main class="pt-32 pb-section-gap px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<!-- Hero Section -->
<section class="mb-section-gap grid grid-cols-1 md:grid-cols-12 gap-gutter items-end">
<div class="md:col-span-7">
<h2 class="font-display-lg text-display-lg mb-8">Let’s define your space.</h2>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-xl">
                    Whether you are an architect detailing a new landmark or a homeowner curating your sanctuary, our team is ready to provide technical expertise and aesthetic guidance.
                </p>
</div>
<div class="md:col-span-5 hidden md:block">
<div class="aspect-[4/3] bg-surface-container overflow-hidden">
<img class="w-full h-full object-cover" data-alt="A close-up shot of architectural premium finishes featuring textured gold metal and dark charcoal wood grain panels." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAtwrgY0Qrg3XwT13SVbThmFZrEW_wHujD7dxAAg9D5bavzRJ2TryNlphH-OKF2lVv42FBPIm8JRbD-i38Varb9bx4brzyON4q1dCnR0bsRrT1sfCHj7nXqibZFdZoQ0kSXXrhCT-WFjbC_rweCr6If88v3X7J-NGjnKT-WFihcQ5ciD9pmW04iLzrSDPcme6an6EMxmXXY9ZHFmIoSs6rxOdVfQhmpn8hfJgQDGtTbFbF2rznwgO-Vix_C2zkyi76Yr8FSBiMIsPmr"/>
</div>
</div>
</section>
<!-- Contact Grid -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-gutter lg:gap-16">
<!-- Left: Contact Methods -->
<div class="lg:col-span-5 space-y-12">
<div>
<h3 class="font-label-md text-label-md uppercase tracking-widest text-secondary mb-6">Direct Channels</h3>
<div class="space-y-4">
<a class="flex items-center justify-between group py-4 border-b border-outline-variant hover:border-secondary transition-colors" href="#">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">call</span>
<span class="font-body-md text-body-md">+1 (234) 567-8900</span>
</div>
<span class="material-symbols-outlined text-outline group-hover:text-secondary transition-transform group-hover:translate-x-1">arrow_forward</span>
</a>
<a class="flex items-center justify-between group py-4 border-b border-outline-variant hover:border-secondary transition-colors" href="#">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">chat_bubble</span>
<span class="font-body-md text-body-md">WhatsApp Support</span>
</div>
<span class="material-symbols-outlined text-outline group-hover:text-secondary transition-transform group-hover:translate-x-1">arrow_forward</span>
</a>
<a class="flex items-center justify-between group py-4 border-b border-outline-variant hover:border-secondary transition-colors" href="#">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">camera</span>
<span class="font-body-md text-body-md">@ajile_finishes</span>
</div>
<span class="material-symbols-outlined text-outline group-hover:text-secondary transition-transform group-hover:translate-x-1">arrow_forward</span>
</a>
</div>
</div>
<div class="bg-primary p-8 text-on-primary">
<h3 class="font-headline-md text-headline-md text-secondary-fixed-dim mb-4">The Showroom</h3>
<p class="font-body-md text-body-md opacity-80 mb-8">
                        Experience our complete library of exotic stones and architectural metals in person. By appointment only.
                    </p>
<div class="space-y-2 mb-8">
<p class="font-label-md text-label-md uppercase tracking-wider">Address</p>
<p class="font-body-md text-body-md">452 Architectural Way, Suite 100<br/>Design District, NY 10013</p>
</div>
<button class="w-full py-4 bg-transparent border border-secondary-fixed-dim text-secondary-fixed-dim font-label-md text-label-md hover:bg-secondary-fixed-dim/10 transition-colors">
                        BOOK A PRIVATE TOUR
                    </button>
</div>
</div>
<!-- Right: Inquiry Form -->
<div class="lg:col-span-7 bg-surface-container-lowest p-8 md:p-12 border border-outline-variant">
<h3 class="font-headline-md text-headline-md mb-8">Project Inquiry</h3>
<form class="space-y-10">
<div class="relative">
<label class="block font-label-md text-label-md text-on-surface-variant uppercase mb-2">Full Name</label>
<input class="w-full bg-transparent border-b border-outline-variant py-3 font-body-md text-body-md focus:border-secondary transition-colors" placeholder="John Doe" type="text"/>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-gutter">
<div class="relative">
<label class="block font-label-md text-label-md text-on-surface-variant uppercase mb-2">Email Address</label>
<input class="w-full bg-transparent border-b border-outline-variant py-3 font-body-md text-body-md focus:border-secondary transition-colors" placeholder="email@example.com" type="email"/>
</div>
<div class="relative">
<label class="block font-label-md text-label-md text-on-surface-variant uppercase mb-2">Service Interest</label>
<select class="w-full bg-transparent border-b border-outline-variant py-3 font-body-md text-body-md focus:border-secondary transition-colors appearance-none cursor-pointer">
<option>Lighting</option>
<option>Door Hardware</option>
<option>Wardrobe Fittings</option>
<option>Sanitary &amp; Bathrooms</option>
<option>Kitchen</option>
<option>Flooring</option>
<option>General Inquiry</option>
</select>
</div>
</div>
<div class="relative">
<label class="block font-label-md text-label-md text-on-surface-variant uppercase mb-2">Message</label>
<textarea class="w-full bg-transparent border-b border-outline-variant py-3 font-body-md text-body-md focus:border-secondary transition-colors resize-none" placeholder="Tell us about your project requirements..." rows="4"></textarea>
</div>
<div class="flex flex-col md:flex-row items-start md:items-center justify-between gap-6 pt-4">
<p class="font-body-md text-body-md text-on-surface-variant italic">We typically respond within 24 hours.</p>
<button class="bg-primary text-on-primary px-12 py-4 font-label-md text-label-md tracking-widest hover:opacity-90 active:scale-95 transition-all" type="submit">
                            SEND INQUIRY
                        </button>
</div>
</form>
</div>
</div>
</main>
<!-- Footer -->
<footer class="w-full py-section-gap px-margin-mobile md:px-margin-desktop border-t border-outline-variant mt-section-gap bg-surface-container">
<div class="max-w-container-max mx-auto flex flex-col items-start gap-gutter">
<h2 class="font-headline-md text-headline-md text-primary tracking-[0.2em] uppercase mb-4">AJILE</h2>
<div class="grid grid-cols-2 md:grid-cols-4 gap-gutter w-full mb-12">
<div class="flex flex-col gap-2">
<span class="font-label-md text-label-md text-on-surface-variant cursor-pointer hover:text-primary transition-colors">WhatsApp</span>
<span class="font-label-md text-label-md text-on-surface-variant cursor-pointer hover:text-primary transition-colors">Instagram</span>
</div>
<div class="flex flex-col gap-2">
<span class="font-label-md text-label-md text-on-surface-variant cursor-pointer hover:text-primary transition-colors">Showroom Policy</span>
<span class="font-label-md text-label-md text-on-surface-variant cursor-pointer hover:text-primary transition-colors">Sustainability</span>
</div>
</div>
<p class="font-body-md text-body-md text-on-surface-variant uppercase tracking-widest">© 2024 AJILE PREMIUM FINISHES. ALL RIGHTS RESERVED.</p>
</div>
</footer>
<!-- BottomNavBar (Mobile only) -->
<nav class="md:hidden fixed bottom-0 w-full z-50 bg-surface border-t border-outline-variant flex justify-around items-center h-16 px-4 pb-safe">
<a class="text-on-surface-variant hover:text-primary flex flex-col items-center gap-1 transition-colors" href="#">
<span class="material-symbols-outlined">home</span>
<span class="font-label-md text-[10px]">Home</span>
</a>
<a class="text-on-surface-variant hover:text-primary flex flex-col items-center gap-1 transition-colors" href="#">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-label-md text-[10px]">Collections</span>
</a>
<a class="text-secondary flex flex-col items-center gap-1 after:content-[''] after:w-1 after:h-1 after:bg-secondary after:rounded-full" href="#">
<span class="material-symbols-outlined">mail</span>
<span class="font-label-md text-[10px]">Contact</span>
</a>
</nav>
</body></html>
