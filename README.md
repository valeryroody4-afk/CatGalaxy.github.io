<!DOCTYPE html>
<html class="light" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>CatGalaxy</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;700;800&amp;display=swap" rel="stylesheet"/>
<script>
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        primary: {
                            DEFAULT: "#3B82F6",
                            light: "#60A5FA"
                        },
                        secondary: "#EC4899",
                        accent: "#8B5CF6",
                        "background-light": "#F7F8FC",
                        "background-dark": "#111827",
                        "text-light": "#1F2937",
                        "text-dark": "#F9FAFB",
                        "text-secondary-light": "#6B7280",
                        "text-secondary-dark": "#9CA3AF",
                        "border-light": "#E5E7EB",
                        "border-dark": "#374151"
                    },
                    fontFamily: {
                        display: "Plus Jakarta Sans"
                    },
                    borderRadius: {
                        DEFAULT: "1rem",
                        lg: "2rem",
                        xl: "3rem",
                        full: "9999px"
                    }
                }
            }
        };
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings:
                'FILL' 0,
                'wght' 400,
                'GRAD' 0,
                'opsz' 24
        }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark font-display text-text-light dark:text-text-dark">
<div class="relative flex h-auto min-h-screen w-full flex-col group/design-root overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<div class="px-4 md:px-10 lg:px-40 flex flex-1 justify-center py-5">
<div class="layout-content-container flex flex-col max-w-[960px] flex-1">
<header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-border-light dark:border-border-dark px-4 sm:px-6 lg:px-10 py-3">
<div class="flex items-center gap-4 text-text-light dark:text-text-dark">
<div class="flex items-center">
</div>

<h2 class="text-text-light dark:text-text-dark text-lg font-bold leading-tight tracking-[-0.015em]"> CatGalaxy </h2>
<br>
</div>
<div class="hidden md:flex flex-1 justify-end gap-8">
<div class="flex items-center gap-9">
<a class="text-text-light dark:text-text-dark text-sm font-medium leading-normal hover:text-primary dark:hover:text-primary-light" href="#">Atracciones</a>
<a class="text-text-light dark:text-text-dark text-sm font-medium leading-normal hover:text-primary dark:hover:text-primary-light" href="#">Horarios</a>
<a class="text-text-light dark:text-text-dark text-sm font-medium leading-normal hover:text-primary dark:hover:text-primary-light" href="#">Precios</a>
<a class="text-text-light dark:text-text-dark text-sm font-medium leading-normal hover:text-primary dark:hover:text-primary-light" href="#">Mapa del Parque</a>
<a class="text-text-light dark:text-text-dark text-sm font-medium leading-normal hover:text-primary dark:hover:text-primary-light" href="#">Contacto</a>
</div>
<div class="flex gap-2">
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-gradient-to-r from-secondary to-accent text-white text-sm font-bold leading-normal tracking-[0.015em] hover:opacity-90 transition-opacity">
<a href="compra.html" class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-6 bg-gradient-to-r from-secondary to-accent text-white text-base font-bold leading-normal tracking-[0.015em] shadow-lg hover:shadow-xl transition-shadow duration-300 transform hover:scale-105">
  <span class="truncate">Comprar Boletos Ahora</span>
</a>
</button>
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-primary/10 dark:bg-primary/20 text-primary dark:text-primary-light text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary/20 dark:hover:bg-primary/30">
<span class="truncate">Iniciar Sesión</span>
</button>
</div>
</div>
<div class="md:hidden">
<button class="p-2 rounded-full hover:bg-primary/10 dark:hover:bg-primary/20 text-primary">
<span class="material-symbols-outlined">menu</span>
</button>
</div>
</header>
<main class="flex-1">
<section class="py-12 md:py-20 text-center">
<h1 class="text-4xl md:text-6xl font-extrabold tracking-tighter mb-4 text-transparent bg-clip-text bg-gradient-to-r from-primary via-secondary to-accent">¡Donde la Diversión Nunca Termina!</h1>
<p class="text-lg md:text-xl text-text-secondary-light dark:text-text-secondary-dark max-w-3xl mx-auto">
                                Descubre un mundo de emociones, aventuras y momentos inolvidables. Nuestro parque tiene algo para todos, desde las atracciones más audaces hasta espectáculos familiares y comida deliciosa.
                            </p>
</section>
<div class="flex overflow-x-auto [-ms-scrollbar-style:none] [scrollbar-width:none] [&amp;::-webkit-scrollbar]:hidden pb-8">
<div class="flex items-stretch p-4 gap-6">
<div class="flex h-full flex-1 flex-col gap-4 rounded-xl bg-background-light dark:bg-background-dark shadow-lg dark:shadow-accent/20 min-w-72 border border-border-light dark:border-border-dark">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-t-xl flex flex-col" data-alt="A group of friends laughing on a roller coaster" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCUyJ8zx5_PQO01_4mPWPsxOf4sDcoDQBNgnmOg8GLhr0I5Zalkb8o5v9DeIUTNGDtWggppk-g_DSGi0AA-un_oGdD51Wxa1Xb1Hv1YaazviHR7fIK9Razkyk9a2NawXXYvKe8SZbUy8GehcfUxeJMrX9aS3g4UN2OnYOYVbpYLtHxwUxdrQVRjkGwJvVkGHyks-AMnXklXt2Sx3c7wyJ4jhaccOArV5oo0fcrvX5cFLuPSCehZaOBy9_drc3hwKBQNCFt6WNJZrLEC");'></div>
<div class="flex flex-col flex-1 justify-between p-4 pt-0 gap-4">
<div>
<p class="text-accent text-base font-bold leading-normal">¡Vive la Aventura!</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Siente la adrenalina en nuestras emocionantes montañas rusas.</p>
</div>
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-accent/10 dark:bg-accent/20 text-accent dark:text-accent text-sm font-bold leading-normal tracking-[0.015em] hover:bg-accent/20 dark:hover:bg-accent/30">
<span class="truncate">Descubre Más</span>
</button>
</div>
</div>
<div class="flex h-full flex-1 flex-col gap-4 rounded-xl bg-background-light dark:bg-background-dark shadow-lg dark:shadow-secondary/20 min-w-72 border border-border-light dark:border-border-dark">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-t-xl flex flex-col" data-alt="Una familia emocionada sonriendo al entrar al parque de atracciones, con la vibrante entrada principal de fondo." style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAPesn2Lms3uR9_VHY-piiXjr0m3-9N58waK5cnknYhKeNxi-D8Q4ebQN1XPfq57k8lL3wmXH3nXXze1v9tOL-SypYNkyzsCh_3l0rEmkVXkIrP0a9AHt2ii1Kvuqok5JF3igkKqedgET13-1XEfRmt7pNU-LIuhPUkpq9AL88NHU4K6cRaUdIIQCqACEahy58jjT6PZ9RWTcVDZ7tnw8BgETaXScVf47OMD-JgLSrFgWEPQ0QKgGZi8vjyR1M9aAwwaaHUr_grzzsj");'></div>
<div class="flex flex-col flex-1 justify-between p-4 pt-0 gap-4">
<div>
<p class="text-secondary text-base font-bold leading-normal">Diversión para Toda la Familia</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Crea recuerdos inolvidables con atracciones para todas las edades.</p>
</div>
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-secondary/10 dark:bg-secondary/20 text-secondary dark:text-secondary text-sm font-bold leading-normal tracking-[0.015em] hover:bg-secondary/20 dark:hover:bg-secondary/30">
<span class="truncate">Descubre Más</span>
</button>
</div>
</div>
<div class="flex h-full flex-1 flex-col gap-4 rounded-xl bg-background-light dark:bg-background-dark shadow-lg dark:shadow-primary/20 min-w-72 border border-border-light dark:border-border-dark">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-t-xl flex flex-col" data-alt="Fireworks exploding over a castle at night" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCtXoCOyzC-OdZUgC_no5bdCSyosbaXUNO-G9HHojdONXxvqQ8BauvVwDZcp3QwfprVW8w0Iex8c3m1Cv9sveK9m9xXecSYgXnQhAxinA7KMjcgEUdwlU62FtBjaWMJlUYQBiZbkrcvEBGU0xeRA2tAaQ49A5sDV-owT9EkEZc7_T5hVurQO3ECo_Zbv4ZfagP32rBlENvgj9863nfLw6uMv2ToEHJdVgcCAKL0CPT0bQPx7BDLh5jh6Kbkq5dHIazdnaXWyjCPk0_b");'></div>
<div class="flex flex-col flex-1 justify-between p-4 pt-0 gap-4">
<div>
<p class="text-primary text-base font-bold leading-normal">Noches Mágicas Inolvidables</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Disfruta de espectaculares shows de fuegos artificiales cada noche.</p>
</div>
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-primary/10 dark:bg-primary/20 text-primary dark:text-primary-light text-sm font-bold leading-normal tracking-[0.015em] hover:bg-primary/20 dark:hover:bg-primary/30">
<span class="truncate">Descubre Más</span>
</button>
</div>
</div>
</div>
</div>
<h2 class="text-text-light dark:text-text-dark text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Atracciones Destacadas</h2>
<div class="grid grid-cols-[repeat(auto-fit,minmax(200px,1fr))] gap-6 p-4">
<div class="flex flex-col gap-3 pb-3">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" data-alt="A thrilling red and yellow roller coaster" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCypl7POI_a04i1eCoNAFNgJmzUdRqVrF3FkbnR0hA4Z302Bb2ky1N15xdFzFrIv53ANgNrAY0b998IM8muIYr0V9BzP-r6ZPG0JD3koSBBVtFZ5x1fjy9bmDj3RMsSFb06N95T8iKHfZhGazkNxZH50WYEQeL-f2LiEX718Op7EVpO_tAQOB4S6MxtKwKKgYNup0o0NE9GT_eryQIdimK_CTbEbNTnxDk_izuALDRbt1On6dKocWsTNQq5RPFuJxnERAMkutGCL4Ha");'></div>
<div>
<p class="text-accent font-medium leading-normal">Montaña Rusa Dragón</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Una aventura de alta velocidad con giros inesperados.</p>
</div>
</div>
<div class="flex flex-col gap-3 pb-3">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" data-alt="A large Ferris wheel against a blue sky" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuA3Qb868WujCzQLVicNPxvP3xqdV_-YBYhyp9HvNSFkd6OspLgIIoSOsah4aNu_jDgFtfl9KC-ZaXaVGGkH_agoAxmfdkeyfpi3Rmc7mfJgbXPY2o-ivPqb5UyzDrYsyosbdn2BYQQKXmj_4PjmIVcyAhqhQGpFF2uar6dmHTU8emU14VBlIzkQXV8sgqh97Nbmx-YdYtPKBKgk579C3lDOOHH9m8Hg2sn3pDJKr82EaJORaajlfc5GaTjPEA3KGUbNlYNiOg0mL389");'></div>
<div>
<p class="text-secondary font-medium leading-normal">Rueda de la Fortuna Gigante</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Disfruta de vistas panorámicas de todo el parque.</p>
</div>
</div>
<div class="flex flex-col gap-3 pb-3">
<div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" data-alt="People on a water ride getting splashed" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAqkZVzRxxVQNdltmbX2M06_2KLhaP3QVnCREZXfHmiG01mik8rWT4Mw89Y17dkJgNfhaoeUlemUWDABxsIsdCEJBzsQN3m3x9pELolF_Lz_ydGJ9pvInFa4FEkUisuZ6ukV5zrcJ0Dwb0RMwuQVIF88qi-yLOtiTrDTLebuhyVuXcpvxTUKscX8VZnenRIXPC9t5ZNvSgfXr0xKF_vAMJJK-YLPLF6oWHjEZI3MuIVVbL7lx6xGmRPAvRVWvWAqBl7Yj447rDu07aH");'></div>
<div>
<p class="text-primary font-medium leading-normal">Rápidos del Río Salvaje</p>
<p class="text-text-secondary-light dark:text-text-secondary-dark text-sm font-normal leading-normal">Un emocionante viaje acuático para refrescarte.</p>
</div>
</div>
</div>
<div class="flex px-4 py-8 justify-center">
<button class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-6 bg-gradient-to-r from-secondary to-accent text-white text-base font-bold leading-normal tracking-[0.015em] shadow-lg hover:shadow-xl transition-shadow duration-300 transform hover:scale-105">
<span class="truncate">Comprar Boletos Ahora</span>
</button>
</div>
<section class="bg-gradient-to-br from-primary/10 via-secondary/10 to-accent/10 dark:from-primary/20 dark:via-secondary/20 dark:to-accent/20 rounded-xl p-8 my-10">
<h2 class="text-2xl font-bold text-center mb-4 text-transparent bg-clip-text bg-gradient-to-r from-primary to-accent">¡Ofertas y Promociones Especiales!</h2>
<div class="grid md:grid-cols-2 gap-6 text-center">
<div class="bg-background-light/80 dark:bg-background-dark/80 p-6 rounded-lg shadow-md border border-accent/30">
<h3 class="font-bold text-lg text-accent">Paquete Familiar</h3>
<p class="text-text-secondary-light dark:text-text-secondary-dark mt-2">¡Ahorra un 20% en boletos para 4 personas! Diversión garantizada para todos.</p>
</div>
<div class="bg-background-light/80 dark:bg-background-dark/80 p-6 rounded-lg shadow-md border border-secondary/30">
<h3 class="font-bold text-lg text-secondary">Noches de Verano</h3>
<p class="text-text-secondary-light dark:text-text-secondary-dark mt-2">Disfruta del parque con un precio especial después de las 5 PM. ¡Vive la magia nocturna!</p>
</div>
</div>
</section>
</main>
<footer class="border-t border-solid border-border-light dark:border-border-dark mt-10 pt-8 pb-4 px-4 sm:px-6 lg:px-10">
<div class="grid grid-cols-2 md:grid-cols-4 gap-8">
<div>
<h4 class="font-bold mb-2 text-primary">Parque</h4>
<ul class="space-y-2">
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-primary dark:hover:text-primary-light" href="#">Sobre Nosotros</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-primary dark:hover:text-primary-light" href="#">Trabaja con Nosotros</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-primary dark:hover:text-primary-light" href="#">Prensa</a></li>
</ul>
</div>
<div>
<h4 class="font-bold mb-2 text-secondary">Ayuda</h4>
<ul class="space-y-2">
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-secondary" href="#">Preguntas Frecuentes</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-secondary" href="#">Contacto</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-secondary" href="#">Mapa del Parque</a></li>
</ul>
</div>
<div>
<h4 class="font-bold mb-2 text-accent">Legal</h4>
<ul class="space-y-2">
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-accent" href="#">Términos y Condiciones</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-accent" href="#">Política de Privacidad</a></li>
<li><a class="text-sm text-text-secondary-light dark:text-text-secondary-dark hover:text-accent" href="#">Política de Cookies</a></li>
</ul>
</div>
<div>
<h4 class="font-bold mb-2">Síguenos</h4>
<div class="flex space-x-4">
<a class="text-text-secondary-light dark:text-text-secondary-dark hover:text-primary" href="#"><svg aria-hidden="true" class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
<path clip-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" fill-rule="evenodd"></path>
</svg></a>
<a class="text-text-secondary-light dark:text-text-secondary-dark hover:text-secondary" href="#"><svg aria-hidden="true" class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
<path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.71v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
</svg></a>
<a class="text-text-secondary-light dark:text-text-secondary-dark hover:text-accent" href="#"><svg aria-hidden="true" class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
<path clip-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm3.322 8.784a.75.75 0 01.135 1.055l-3.322 4.43a.75.75 0 01-1.19.04l-1.68-1.892a.75.75 0 111.125-1.002l1.076 1.21 2.726-3.636a.75.75 0 011.056-.135z" fill-rule="evenodd"></path>
</svg></a>
</div>
</div>
</div>
<div class="text-center text-text-secondary-light dark:text-text-secondary-dark text-sm mt-8">
                            © 2025 CatGalaxy. Todos los derechos reservados.
                        </div>
</footer>
</div>
</div>
</div>
</div>
</body></html>
