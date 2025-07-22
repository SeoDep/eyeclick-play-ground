<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EyeClick | Interactive Kids Entertainment Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            --brand-blue: #00529B;
            --brand-orange: #FF671F;
            --brand-green: #00A859;
            --brand-teal: #00A99D;
        }
        .cta-button {
            @apply inline-block text-white font-extrabold text-xl text-center py-5 px-12 rounded-full transition-all duration-300 ease-in-out shadow-lg hover:shadow-xl hover:-translate-y-1 bg-gradient-to-r from-[var(--brand-blue)] to-[var(--brand-teal)];
        }
        .cta-button-secondary {
            @apply inline-block bg-transparent text-[var(--brand-blue)] font-extrabold text-xl text-center py-5 px-12 rounded-full transition-all duration-300 ease-in-out border-2 border-[var(--brand-blue)] hover:bg-[var(--brand-blue)] hover:text-white hover:-translate-y-1;
        }
        .section-title {
            @apply text-6xl md:text-7xl font-black text-[var(--brand-blue)] text-center mb-4;
        }
        .section-title-underline {
            @apply w-32 h-2 bg-gradient-to-r from-[var(--brand-orange)] to-[var(--brand-green)] mx-auto rounded-full mb-16;
        }
        .icon-list-item {
            @apply flex items-start space-x-3 mb-3;
        }
        .icon-list-icon {
            @apply w-6 h-6 text-[var(--brand-blue)] mt-1 flex-shrink-0;
        }
        .video-placeholder {
            @apply relative aspect-video w-full bg-gray-200 rounded-lg overflow-hidden shadow-xl flex items-center justify-center;
        }
        .video-placeholder img {
            @apply absolute inset-0 w-full h-full object-cover;
        }
        .video-placeholder .play-icon {
            @apply absolute z-10 w-20 h-20 text-white opacity-80 transition-transform hover:scale-110 cursor-pointer;
        }
        .usp-list-item {
            @apply flex items-center text-left;
        }
        .usp-list-icon {
            @apply w-5 h-5 mr-2 text-[var(--brand-green)] flex-shrink-0;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-700">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="max-w-screen-2xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-3xl font-bold" style="color: var(--brand-blue);">EyeClick</a>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#" class="text-gray-600 hover:text-[var(--brand-blue)]">Products</a>
                <a href="#" class="text-gray-600 hover:text-[var(--brand-blue)]">Solutions</a>
                <a href="#" class="text-gray-600 hover:text-[var(--brand-blue)]">About</a>
                <a href="#" class="text-gray-600 hover:text-[var(--brand-blue)]">Contact</a>
                <a href="#" class="bg-[var(--brand-blue)] text-white px-5 py-2 rounded-full hover:bg-blue-800 transition">Get a Quote</a>
            </div>
            <button id="mobile-menu-button" class="md:hidden">
                <i data-lucide="menu" class="w-6 h-6"></i>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pb-4 text-left">
            <a href="#" class="block py-2 text-gray-600 hover:text-[var(--brand-blue)]">Products</a>
            <a href="#" class="block py-2 text-gray-600 hover:text-[var(--brand-blue)]">Solutions</a>
            <a href="#" class="block py-2 text-gray-600 hover:text-[var(--brand-blue)]">About</a>
            <a href="#" class="block py-2 text-gray-600 hover:text-[var(--brand-blue)]">Contact</a>
            <a href="#" class="block mt-2 bg-[var(--brand-blue)] text-white text-center px-5 py-2 rounded-full hover:bg-blue-800 transition">Get a Quote</a>
        </div>
    </header>

    <main>
        <!-- Breadcrumbs -->
        <div class="bg-gray-100">
            <div class="max-w-screen-2xl mx-auto px-6 py-3 text-sm">
                <a href="#" class="text-gray-600 hover:text-[var(--brand-blue)]">Home</a>
                <span class="text-gray-400 mx-2">&gt;</span>
                <span class="text-gray-800">Interactive Playground</span>
            </div>
        </div>

        <!-- Hero Section -->
        <section class="py-20 md:py-28 text-center bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h1 class="font-extrabold text-gray-900 leading-tight mb-6">
                    <span class="block text-6xl md:text-8xl">Interactive Playground</span>
                    <span class="block text-2xl md:text-4xl font-medium text-gray-600 mt-4">Fun for Kids, Growth for Family Businesses</span>
                </h1>
                <p class="max-w-5xl mx-auto text-lg md:text-xl text-gray-600">
                    <strong class="text-gray-800">EyeClick transforms any space into an interactive playground using advanced projection and motion-sensing technology.</strong> With touchless, floor- or wall-based experiences, kids are fully engaged — and businesses benefit from longer visits, happier families, and repeat customers.
                </p>
                <div class="mt-10">
                    <a href="#" class="cta-button">Get a Free Consultation</a>
                </div>
            </div>
        </section>

        <!-- Why Kids & Parents Love It -->
        <section class="py-20 bg-gray-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Why Kids — And Their Parents — Love It</h2>
                <div class="section-title-underline"></div>
                <div class="grid md:grid-cols-3 gap-8 text-left">
                    <!-- Kids Love -->
                    <div class="bg-white p-8 rounded-xl shadow-lg flex flex-col">
                        <img src="https://placehold.co/600x400/00529B/FFFFFF?text=Kids+Having+Fun+image" alt="Image Placeholder: Kids Having Fun image" class="w-full h-48 object-cover rounded-lg mb-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-blue-100 p-3 rounded-full mr-4"><i data-lucide="star" class="w-8 h-8 text-[var(--brand-blue)]"></i></div>
                            <h3 class="text-3xl font-bold text-gray-800">Kids Love</h3>
                        </div>
                        <ul class="space-y-2">
                           <li class="icon-list-item"><i data-lucide="gamepad-2" class="icon-list-icon"></i><span>Immersive games</span></li>
                           <li class="icon-list-item"><i data-lucide="move" class="icon-list-icon"></i><span>Full-body interaction</span></li>
                           <li class="icon-list-item"><i data-lucide="footprints" class="icon-list-icon"></i><span>Freedom to move</span></li>
                           <li class="icon-list-item"><i data-lucide="infinity" class="icon-list-icon"></i><span>Endless variety</span></li>
                        </ul>
                    </div>
                    <!-- Parents Love -->
                    <div class="bg-white p-8 rounded-xl shadow-lg flex flex-col">
                        <img src="https://placehold.co/600x400/00A859/FFFFFF?text=Happy+Parents+image" alt="Image Placeholder: Happy Parents image" class="w-full h-48 object-cover rounded-lg mb-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-green-100 p-3 rounded-full mr-4"><i data-lucide="heart" class="w-8 h-8 text-[var(--brand-green)]"></i></div>
                            <h3 class="text-3xl font-bold text-gray-800">Parents Love</h3>
                        </div>
                        <ul class="space-y-2">
                           <li class="icon-list-item"><i data-lucide="shield-check" class="icon-list-icon" style="color: var(--brand-green);"></i><span>Safe, hygienic, screen-free entertainment</span></li>
                           <li class="icon-list-item"><i data-lucide="smile" class="icon-list-icon" style="color: var(--brand-green);"></i><span>Keeps kids happily engaged</span></li>
                        </ul>
                    </div>
                    <!-- You'll Love -->
                    <div class="bg-white p-8 rounded-xl shadow-lg flex flex-col">
                        <img src="https://placehold.co/600x400/FF671F/FFFFFF?text=Growing+Business+image" alt="Image Placeholder: Growing Business image" class="w-full h-48 object-cover rounded-lg mb-6">
                        <div class="flex items-center mb-4">
                            <div class="bg-orange-100 p-3 rounded-full mr-4"><i data-lucide="building" class="w-8 h-8 text-[var(--brand-orange)]"></i></div>
                            <h3 class="text-3xl font-bold text-gray-800">You'll Love</h3>
                        </div>
                        <ul class="space-y-2">
                           <li class="icon-list-item"><i data-lucide="clock" class="icon-list-icon" style="color: var(--brand-orange);"></i><span>More time spent on-premise</span></li>
                           <li class="icon-list-item"><i data-lucide="trending-up" class="icon-list-icon" style="color: var(--brand-orange);"></i><span>Improved satisfaction</span></li>
                           <li class="icon-list-item"><i data-lucide="gem" class="icon-list-icon" style="color: var(--brand-orange);"></i><span>A clear point of differentiation</span></li>
                        </ul>
                    </div>
                </div>
                 <div class="text-center mt-16">
                    <a href="#" class="cta-button">Discover Our Games</a>
                </div>
            </div>
        </section>

        <!-- Problems We Solve -->
        <section class="py-20 bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Problems We Solve for Businesses</h2>
                <div class="section-title-underline"></div>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="border border-gray-200 p-8 rounded-xl text-center hover:shadow-xl transition-shadow flex flex-col">
                        <i data-lucide="users" class="w-16 h-16 text-[var(--brand-blue)] mx-auto mb-4"></i>
                        <h3 class="text-2xl font-bold mb-4 text-gray-800">Keep Children Engaged</h3>
                        <p class="text-gray-600 mb-4">Reduce parent complaints, lower staff interruptions, and eliminate idle time.</p>
                        <ul class="space-y-2 text-gray-600 mt-auto">
                            <li class="usp-list-item"><i data-lucide="user-minus" class="usp-list-icon"></i>Reduces staff workload</li>
                            <li class="usp-list-item"><i data-lucide="smile" class="usp-list-icon"></i>Boosts parent satisfaction</li>
                            <li class="usp-list-item"><i data-lucide="hourglass" class="usp-list-icon"></i>Turns waiting time into playtime</li>
                        </ul>
                    </div>
                    <div class="border border-gray-200 p-8 rounded-xl text-center hover:shadow-xl transition-shadow flex flex-col">
                        <i data-lucide="bar-chart-2" class="w-16 h-16 text-[var(--brand-blue)] mx-auto mb-4"></i>
                        <h3 class="text-2xl font-bold mb-4 text-gray-800">Increase Time on Premises</h3>
                        <p class="text-gray-600 mb-4">More time means more revenue and boosts overall satisfaction.</p>
                         <ul class="space-y-2 text-gray-600 mt-auto">
                            <li class="usp-list-item"><i data-lucide="coins" class="usp-list-icon"></i>Drives secondary spending</li>
                            <li class="usp-list-item"><i data-lucide="repeat" class="usp-list-icon"></i>Encourages repeat visits</li>
                            <li class="usp-list-item"><i data-lucide="thumbs-up" class="usp-list-icon"></i>Improves customer loyalty</li>
                        </ul>
                    </div>
                    <div class="border border-gray-200 p-8 rounded-xl text-center hover:shadow-xl transition-shadow flex flex-col">
                        <i data-lucide="rocket" class="w-16 h-16 text-[var(--brand-blue)] mx-auto mb-4"></i>
                        <h3 class="text-2xl font-bold mb-4 text-gray-800">Stand Out from Competition</h3>
                        <p class="text-gray-600 mb-4">Interactive tech adds a modern wow-factor to your brand.</p>
                         <ul class="space-y-2 text-gray-600 mt-auto">
                            <li class="usp-list-item"><i data-lucide="sparkles" class="usp-list-icon"></i>Creates a memorable experience</li>
                            <li class="usp-list-item"><i data-lucide="award" class="usp-list-icon"></i>Enhances brand image</li>
                            <li class="usp-list-item"><i data-lucide="message-square" class="usp-list-icon"></i>Generates positive word-of-mouth</li>
                        </ul>
                    </div>
                </div>
                <div class="text-center mt-16">
                    <a href="#" class="cta-button">Talk to Our Team About Your Space</a>
                </div>
            </div>
        </section>
        
        <!-- Businesses We Serve -->
        <section class="py-20 bg-gray-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Businesses We Serve</h2>
                <div class="section-title-underline"></div>
                <p class="max-w-3xl mx-auto text-center text-lg text-gray-600 mb-12">EyeClick solutions are tailored for high-traffic environments that care about families:</p>
                <div class="max-w-7xl mx-auto grid grid-cols-2 md:grid-cols-5 gap-4">
                    <a href="/solutions/malls" class="group text-center"><img src="https://placehold.co/400x400/E0E0E0/333333?text=Shopping+Mall" class="rounded-lg shadow-md w-full h-40 object-cover mb-2 transition-transform transform group-hover:scale-105" alt="Interior of a modern shopping mall"><h4 class="text-lg font-bold">Shopping Malls</h4></a>
                    <a href="/solutions/restaurants" class="group text-center"><img src="https://placehold.co/400x400/E0E0E0/333333?text=Restaurant" class="rounded-lg shadow-md w-full h-40 object-cover mb-2 transition-transform transform group-hover:scale-105" alt="A family-friendly restaurant setting"><h4 class="text-lg font-bold">Restaurants & Food Courts</h4></a>
                    <a href="/solutions/healthcare" class="group text-center"><img src="https://placehold.co/400x400/E0E0E0/333333?text=Clinic" class="rounded-lg shadow-md w-full h-40 object-cover mb-2 transition-transform transform group-hover:scale-105" alt="A clean and modern hospital waiting room"><h4 class="text-lg font-bold">Clinics & Hospitals</h4></a>
                    <a href="/solutions/hotels" class="group text-center"><img src="https://placehold.co/400x400/E0E0E0/333333?text=Hotel" class="rounded-lg shadow-md w-full h-40 object-cover mb-2 transition-transform transform group-hover:scale-105" alt="A luxury hotel resort lobby"><h4 class="text-lg font-bold">Hotels & Resorts</h4></a>
                    <a href="/solutions/education" class="group text-center"><img src="https://placehold.co/400x400/E0E0E0/333333?text=Museum" class="rounded-lg shadow-md w-full h-40 object-cover mb-2 transition-transform transform group-hover:scale-105" alt="A modern library interior with people"><h4 class="text-lg font-bold">Libraries & Museums</h4></a>
                </div>
                 <div class="text-center mt-12">
                    <a href="#" class="cta-button-secondary">Find a Solution for Your Business</a>
                </div>
            </div>
        </section>

        <!-- Our Technology -->
        <section class="py-20 bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Our Technology</h2>
                <div class="section-title-underline"></div>
                <div class="grid md:grid-cols-3 gap-8 text-left">
                    <!-- Beam -->
                    <div class="bg-gray-50 p-8 rounded-lg overflow-hidden shadow-md group">
                        <img src="https://placehold.co/800x600/00529B/FFFFFF?text=BEAM+Product" alt="Beam Interactive Floor Projection" class="w-full h-56 object-cover rounded-lg mb-6">
                        <div class="p-0">
                            <h3 class="text-3xl font-bold mb-4 text-gray-800">Beam</h3>
                            <ul class="space-y-2 list-disc list-inside">
                                <li>Ceiling-mounted interactive floor projection</li>
                                <li>Ideal for large commercial spaces</li>
                                <li>Touchless, durable, and safe experience</li>
                            </ul>
                            <a href="/products/beam" class="font-semibold text-[var(--brand-blue)] hover:underline mt-4 inline-block">Learn More &rarr;</a>
                        </div>
                    </div>
                    <!-- Beam Mobile -->
                    <div class="bg-gray-50 p-8 rounded-lg overflow-hidden shadow-md group">
                        <img src="https://placehold.co/800x600/00A859/FFFFFF?text=BEAM+Mobile+Product" alt="Beam Mobile Portable Interactive Projector" class="w-full h-56 object-cover rounded-lg mb-6">
                        <div class="p-0">
                            <h3 class="text-3xl font-bold mb-4 text-gray-800">Beam Mobile</h3>
                            <ul class="space-y-2 list-disc list-inside">
                                <li>Portable and easy-to-operate version of Beam</li>
                                <li>Perfect for events, rotating spaces, and activity stations</li>
                                <li>Quick and simple setup</li>
                            </ul>
                            <a href="/products/beam-mobile" class="font-semibold text-[var(--brand-blue)] hover:underline mt-4 inline-block">Learn More &rarr;</a>
                        </div>
                    </div>
                    <!-- Obie -->
                    <div class="bg-gray-50 p-8 rounded-lg overflow-hidden shadow-md group">
                        <img src="https://placehold.co/800x600/FF671F/FFFFFF?text=OBIE+Product" alt="Obie Interactive Wall Projector" class="w-full h-56 object-cover rounded-lg mb-6">
                        <div class="p-0">
                            <h3 class="text-3xl font-bold mb-4 text-gray-800">Obie</h3>
                            <ul class="space-y-2 list-disc list-inside">
                                <li>Wall or tabletop projection system</li>
                                <li>Designed for learning centers, kindergartens, and therapy</li>
                                <li>Educational and therapeutic games</li>
                            </ul>
                            <a href="/products/obie" class="font-semibold text-[var(--brand-blue)] hover:underline mt-4 inline-block">Learn More &rarr;</a>
                        </div>
                    </div>
                </div>
                <div class="text-center mt-16">
                    <a href="#" class="cta-button">Compare All Technologies</a>
                </div>
            </div>
        </section>

        <!-- Trusted By -->
        <section class="py-16 bg-gray-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Trusted by Leading Brands</h2>
                <div class="section-title-underline"></div>
                <div class="flex flex-wrap justify-center items-center gap-x-12 gap-y-8">
                    <img src="https://placehold.co/150x60/CCCCCC/FFFFFF?text=McDonald's" alt="McDonald's Logo" class="h-12">
                    <img src="https://placehold.co/150x60/CCCCCC/FFFFFF?text=Ronald+McDonald+House" alt="Ronald McDonald House Charities Logo" class="h-12">
                    <img src="https://placehold.co/150x60/CCCCCC/FFFFFF?text=Children’s+National" alt="Children's National Logo" class="h-12">
                    <img src="https://placehold.co/150x60/CCCCCC/FFFFFF?text=Tel+Aviv+Sourasky" alt="Tel Aviv Sourasky Medical Center Logo" class="h-12">
                    <img src="https://placehold.co/150x60/CCCCCC/FFFFFF?text=The+Grand+Resort" alt="The Grand Resort Logo" class="h-12">
                </div>
                <div class="text-center mt-16">
                    <a href="#" class="cta-button-secondary">See More Success Stories</a>
                </div>
            </div>
        </section>

        <!-- See in Action -->
        <section class="py-20 bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">See it in Action</h2>
                <div class="section-title-underline"></div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div class="video-placeholder">
                        <img src="https://placehold.co/1600x900/CCCCCC/FFFFFF?text=Action+Video+1" alt="Action video placeholder 1">
                        <i data-lucide="play-circle" class="play-icon"></i>
                    </div>
                    <div class="video-placeholder">
                        <img src="https://placehold.co/1600x900/CCCCCC/FFFFFF?text=Action+Video+2" alt="Action video placeholder 2">
                        <i data-lucide="play-circle" class="play-icon"></i>
                    </div>
                    <div class="video-placeholder">
                        <img src="https://placehold.co/1600x900/CCCCCC/FFFFFF?text=Action+Video+3" alt="Action video placeholder 3">
                        <i data-lucide="play-circle" class="play-icon"></i>
                    </div>
                    <div class="video-placeholder">
                        <img src="https://placehold.co/1600x900/CCCCCC/FFFFFF?text=Action+Video+4" alt="Action video placeholder 4">
                        <i data-lucide="play-circle" class="play-icon"></i>
                    </div>
                </div>
                <div class="text-center mt-16">
                    <a href="#" class="cta-button-secondary">View Our Full Gallery</a>
                </div>
            </div>
        </section>

        <!-- Stats -->
        <section class="py-20 bg-blue-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title" style="color: var(--brand-blue);">Stats That Speak for Themselves</h2>
                <div class="section-title-underline" style="background: linear-gradient(to right, var(--brand-orange), var(--brand-green));"></div>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center bg-white p-6 rounded-xl shadow-lg border-t-4" style="border-color: var(--brand-blue);">
                        <i data-lucide="trending-up" class="w-16 h-16 text-[var(--brand-blue)] mx-auto mb-4"></i>
                        <p class="text-5xl font-extrabold text-[var(--brand-blue)]">35%</p>
                        <p class="text-lg text-gray-600">increase in time spent on premises</p>
                    </div>
                    <div class="text-center bg-white p-6 rounded-xl shadow-lg border-t-4" style="border-color: var(--brand-green);">
                        <i data-lucide="smile" class="w-16 h-16 text-[var(--brand-green)] mx-auto mb-4"></i>
                        <p class="text-5xl font-extrabold text-[var(--brand-blue)]">87%</p>
                        <p class="text-lg text-gray-600">of parents report improved experience</p>
                    </div>
                    <div class="text-center bg-white p-6 rounded-xl shadow-lg border-t-4" style="border-color: var(--brand-orange);">
                        <i data-lucide="gamepad-2" class="w-16 h-16 text-[var(--brand-orange)] mx-auto mb-4"></i>
                        <p class="text-5xl font-extrabold text-[var(--brand-blue)]">25M+</p>
                        <p class="text-lg text-gray-600">play sessions worldwide</p>
                    </div>
                    <div class="text-center bg-white p-6 rounded-xl shadow-lg border-t-4" style="border-color: var(--brand-teal);">
                        <i data-lucide="globe" class="w-16 h-16 text-[var(--brand-teal)] mx-auto mb-4"></i>
                        <p class="text-5xl font-extrabold text-[var(--brand-blue)]">6,000+</p>
                        <p class="text-lg text-gray-600">global locations</p>
                    </div>
                </div>
                <div class="text-center mt-16">
                    <a href="#" class="cta-button">Get the Full Impact Report</a>
                </div>
            </div>
        </section>

        <!-- Testimonials -->
        <section class="py-20 bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">What Our Clients Say</h2>
                <div class="section-title-underline"></div>
                <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-8">
                    <div class="bg-gray-50 p-8 rounded-lg shadow-md flex flex-col">
                        <div class="video-placeholder mb-6">
                            <img src="https://placehold.co/1600x900/00529B/FFFFFF?text=Video+Testimonial+1" alt="Video testimonial placeholder">
                            <i data-lucide="play-circle" class="play-icon"></i>
                        </div>
                        <div class="flex text-yellow-400 mb-4">
                            <i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i>
                        </div>
                        <p class="text-lg italic text-gray-700 flex-grow">“Parents no longer ask how long the wait is — their kids are having too much fun!”</p>
                        <p class="mt-4 font-bold text-gray-800">– Clinic Manager, Pediatric Center</p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-lg shadow-md flex flex-col">
                        <div class="video-placeholder mb-6">
                            <img src="https://placehold.co/1600x900/00A859/FFFFFF?text=Video+Testimonial+2" alt="Video testimonial placeholder">
                            <i data-lucide="play-circle" class="play-icon"></i>
                        </div>
                        <div class="flex text-yellow-400 mb-4">
                            <i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i><i data-lucide="star" class="w-6 h-6 fill-current"></i>
                        </div>
                        <p class="text-lg italic text-gray-700 flex-grow">“Our restaurant has become the go-to spot for families with kids.”</p>
                        <p class="mt-4 font-bold text-gray-800">– Owner, Quick-Serve Restaurant Chain</p>
                    </div>
                </div>
                <div class="text-center mt-12">
                    <a href="#" class="cta-button-secondary">Read More Success Stories</a>
                </div>
            </div>
        </section>

        <!-- FAQ Section -->
        <section class="py-20 bg-gray-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Frequently Asked Questions</h2>
                <div class="section-title-underline"></div>
                <div class="max-w-6xl mx-auto space-y-4">
                    <details class="bg-white p-6 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-xl cursor-pointer flex justify-between items-center">
                            How much does an EyeClick system cost?
                            <i data-lucide="chevron-down" class="w-5 h-5 transition-transform transform group-open:rotate-180"></i>
                        </summary>
                        <p class="mt-4 text-gray-600">The cost varies depending on the size of the space, the chosen system, and the game package. We offer customized solutions for every budget. Contact us for an accurate quote.</p>
                    </details>
                    <details class="bg-white p-6 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-xl cursor-pointer flex justify-between items-center">
                            Does the system require regular maintenance?
                            <i data-lucide="chevron-down" class="w-5 h-5 transition-transform transform group-open:rotate-180"></i>
                        </summary>
                        <p class="mt-4 text-gray-600">Our systems are designed for high durability and require minimal maintenance. The projector is mounted on the ceiling, protected from impact, and we offer full technical support and remote service for any issue.</p>
                    </details>
                    <details class="bg-white p-6 rounded-lg shadow-sm group">
                        <summary class="font-semibold text-xl cursor-pointer flex justify-between items-center">
                            How many games are included and how often are they updated?
                            <i data-lucide="chevron-down" class="w-5 h-5 transition-transform transform group-open:rotate-180"></i>
                        </summary>
                        <p class="mt-4 text-gray-600">Each system comes with a rich library of games, and we regularly add new games to maintain interest and variety. You can upgrade your game package at any time.</p>
                    </details>
                </div>
            </div>
        </section>

        <!-- Related Articles -->
        <section class="py-20 bg-white">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Related Articles</h2>
                <div class="section-title-underline"></div>
                <div class="grid md:grid-cols-3 gap-8">
                    <a href="#" class="block bg-gray-50 rounded-lg hover:shadow-xl transition-shadow group overflow-hidden">
                        <img src="https://placehold.co/600x400/E0E0E0/333333?text=Image" alt="Image Placeholder" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="font-semibold text-[var(--brand-blue)] mb-2">[Article]</p>
                            <h4 class="text-xl font-bold text-gray-800 group-hover:text-[var(--brand-blue)]">Beam at Ronald McDonald House: Stress Relief Through Play</h4>
                        </div>
                    </a>
                    <a href="#" class="block bg-gray-50 rounded-lg hover:shadow-xl transition-shadow group overflow-hidden">
                        <img src="https://placehold.co/600x400/E0E0E0/333333?text=Image" alt="Image Placeholder" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="font-semibold text-[var(--brand-blue)] mb-2">[Article]</p>
                            <h4 class="text-xl font-bold text-gray-800 group-hover:text-[var(--brand-blue)]">Why Interactive Play Drives Loyalty in Hospitality</h4>
                        </div>
                    </a>
                    <a href="#" class="block bg-gray-50 rounded-lg hover:shadow-xl transition-shadow group overflow-hidden">
                        <img src="https://placehold.co/600x400/E0E0E0/333333?text=Image" alt="Image Placeholder" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="font-semibold text-[var(--brand-blue)] mb-2">[Article]</p>
                            <h4 class="text-xl font-bold text-gray-800 group-hover:text-[var(--brand-blue)]">Screen-Free Tech Parents Trust in the Digital Age</h4>
                        </div>
                    </a>
                </div>
                <div class="text-center mt-12">
                    <a href="#" class="cta-button">Explore All Articles</a>
                </div>
            </div>
        </section>

        <!-- Contact Form -->
        <section class="py-20 bg-gray-50">
            <div class="max-w-screen-xl mx-auto px-6">
                <h2 class="section-title">Get in Touch</h2>
                <div class="section-title-underline"></div>
                <div class="max-w-6xl mx-auto bg-white p-8 md:p-12 rounded-xl shadow-2xl">
                    <form action="#" method="POST">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                            <div>
                                <label for="name" class="block text-gray-700 font-bold mb-2">Full Name</label>
                                <input type="text" id="name" name="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-[var(--brand-blue)]" placeholder="John Doe" required>
                            </div>
                            <div>
                                <label for="email" class="block text-gray-700 font-bold mb-2">Email Address</label>
                                <input type="email" id="email" name="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-[var(--brand-blue)]" placeholder="you@example.com" required>
                            </div>
                            <div class="md:col-span-2">
                                 <label for="company" class="block text-gray-700 font-bold mb-2">Company Name</label>
                                <input type="text" id="company" name="company" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-[var(--brand-blue)]" placeholder="Your Company Inc.">
                            </div>
                            <div class="md:col-span-2">
                                <label for="message" class="block text-gray-700 font-bold mb-2">Message</label>
                                <textarea id="message" name="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-[var(--brand-blue)]" placeholder="Tell us about your space and needs..." required></textarea>
                            </div>
                        </div>
                        <div class="text-center">
                            <button type="submit" class="cta-button">Send Message</button>
                        </div>
                    </form>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="max-w-screen-2xl mx-auto px-6 py-12 text-left">
            <div class="grid md:grid-cols-4 gap-8">
                <!-- About & Links -->
                <div>
                    <h4 class="text-xl font-bold mb-4">EyeClick</h4>
                    <ul>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">About</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Careers</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Contact</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Blog</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Legal</a></li>
                    </ul>
                </div>
                <!-- Solutions -->
                <div>
                    <h4 class="text-xl font-bold mb-4">Solutions</h4>
                    <ul>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Shopping Malls</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Restaurants</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Healthcare</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-blue-400">Hotels & Resorts</a></li>
                    </ul>
                </div>
                <!-- Newsletter -->
                <div class="md:col-span-2">
                    <h4 class="text-xl font-bold mb-4">Stay in the loop</h4>
                    <p class="mb-4 text-gray-400">Join our newsletter to get the latest updates and case studies.</p>
                    <form class="flex">
                        <input type="email" placeholder="Enter your email" class="w-full px-4 py-2 rounded-l-md text-gray-800 focus:outline-none">
                        <button class="bg-[var(--brand-blue)] px-6 py-2 rounded-r-md hover:bg-blue-800">Sign Up</button>
                    </form>
                </div>
            </div>
            <div class="mt-12 border-t border-gray-700 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400">&copy; EyeClick 2025</p>
                <div class="flex space-x-4 mt-4 md:mt-0">
                    <a href="#"><i data-lucide="twitter" class="w-6 h-6 hover:text-blue-400"></i></a>
                    <a href="#"><i data-lucide="facebook" class="w-6 h-6 hover:text-blue-400"></i></a>
                    <a href="#"><i data-lucide="linkedin" class="w-6 h-6 hover:text-blue-400"></i></a>
                    <a href="#"><i data-lucide="youtube" class="w-6 h-6 hover:text-blue-400"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
