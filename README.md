<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atlas Maintenance - Total Property Upkeep: Inside & Out</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .service-card { transition: all 0.3s ease; }
        .service-card:hover { transform: translateY(-5px); box-shadow: 0 15px 25px rgba(0, 0, 0, 0.15); }
        .btn-primary { transition: all 0.2s ease; }
        .btn-primary:active { transform: scale(0.98); }
        /* Custom SVG for maintenance icon */
        .wrench-icon { fill: none; stroke: currentColor; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round; }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'atlas-blue': '#1e3a8a', /* Dark Blue for reliability */
                        'atlas-light': '#3b82f6', /* Blue for action */
                        'atlas-green': '#10b981', /* Green for outdoor services */
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gray-50">

    <header class="bg-white shadow-md sticky top-0 z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <svg class="w-8 h-8 text-atlas-blue" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path class="wrench-icon" d="M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z" />
                    <path class="wrench-icon" d="M15 9L9 15" />
                    <path class="wrench-icon" d="M18 6L16.5 7.5" />
                    <path class="wrench-icon" d="M7.5 16.5L6 18" />
                    <path class="wrench-icon" d="M16.5 7.5L18 6" />
                    <path class="wrench-icon" d="M7.5 16.5L6 18" />
                </svg>
                <span class="text-2xl font-extrabold text-atlas-blue">ATLAS</span>
                <span class="text-2xl font-light text-gray-700">Maintenance</span>
            </div>
            <a href="#contact" class="hidden sm:inline-block bg-atlas-light text-white px-4 py-2 rounded-lg font-medium hover:bg-atlas-blue btn-primary shadow-lg">
                Get a Free Quote
            </a>
        </div>
    </header>

    <section class="relative bg-gray-900 overflow-hidden">
        <div class="absolute inset-0">
            <img src="https://placehold.co/1200x800/1e3a8a/ffffff?text=Total+Property+Maintenance" 
                 class="w-full h-full object-cover opacity-50" 
                 onerror="this.src='https://placehold.co/1200x800/1e3a8a/ffffff?text=Total+Property+Maintenance';">
        </div>
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 sm:py-32 text-center">
            <h1 class="text-5xl sm:text-7xl font-extrabold tracking-tight text-white shadow-text">
                Inside-Out <span class="text-atlas-light">Property Upkeep.</span>
            </h1>
            <p class="mt-4 max-w-2xl mx-auto text-xl text-gray-300">
                From **lawn care** to **general repairs**, Atlas is your single source for reliable maintenance services.
            </p>
            <div class="mt-10 flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6">
                <a href="#services" class="bg-atlas-light text-white px-8 py-4 rounded-xl text-lg font-bold hover:bg-atlas-blue btn-primary shadow-xl">
                    See All Services
                </a>
                <a href="#contact" class="bg-white text-atlas-blue px-8 py-4 rounded-xl text-lg font-bold hover:bg-gray-200 btn-primary shadow-xl">
                    Book a Consultation
                </a>
            </div>
        </div>
    </section>

    <section id="services" class="py-16 sm:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-4xl font-extrabold text-gray-900">Comprehensive Maintenance Services</h2>
            <p class="mt-4 text-xl text-gray-600">
                We specialize in keeping residential and commercial properties running and looking great, inside and out.
            </p>

            <div class="mt-12 grid grid-cols-1 md:grid-cols-4 gap-8">
                
                <div class="service-card p-6 bg-gray-50 rounded-xl shadow-lg border-t-4 border-atlas-green">
                    <div class="w-12 h-12 mx-auto bg-atlas-green/20 p-3 rounded-full text-atlas-green mb-4">
                         <svg class="w-full h-full" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 21.5V2m-2 15h4M4 17s.5-2 2-3c1.5-1 4-2 6-2s4.5 1 6 2c1.5 1 2 3 2 3M20 17H4"/></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900">Lawn & Yard Care</h3>
                    <p class="mt-3 text-gray-600">
                        Routine mowing, trimming, edging, seasonal cleanup, and small landscaping tasks to keep your curb appeal high.
                    </p>
                </div>

                <div class="service-card p-6 bg-gray-50 rounded-xl shadow-lg border-t-4 border-atlas-green">
                    <div class="w-12 h-12 mx-auto bg-atlas-green/20 p-3 rounded-full text-atlas-green mb-4">
                        <svg class="w-full h-full" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 17.5228 6.47715 22 12 22Z"/><path d="M15 9l-6 6M10 9l-1 1M15 14l1 1"/></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900">Exterior Cleaning</h3>
                    <p class="mt-3 text-gray-600">
                        Professional **pressure washing** for driveways, patios, and siding. Also includes expert **window cleaning**.
                    </p>
                </div>
                
                <div class="service-card p-6 bg-gray-50 rounded-xl shadow-lg border-t-4 border-atlas-light">
                    <div class="w-12 h-12 mx-auto bg-atlas-light/20 p-3 rounded-full text-atlas-blue mb-4">
                        <svg class="wrench-icon w-full h-full" viewBox="0 0 24 24"><path d="M10 20l4-16m4 4l4 4-4 4M6 8l-4 4 4 4"/></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900">General Interior Repairs</h3>
                    <p class="mt-3 text-gray-600">
                        Fixing leaks, patching drywall, installing light fixtures, painting touch-ups, and managing interior to-do lists.
                    </p>
                </div>

                <div class="service-card p-6 bg-gray-50 rounded-xl shadow-lg border-t-4 border-atlas-light">
                    <div class="w-12 h-12 mx-auto bg-atlas-light/20 p-3 rounded-full text-atlas-blue mb-4">
                        <svg class="wrench-icon w-full h-full" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"/><line x1="12" y1="8" x2="12" y2="16"/><line x1="8" y1="12" x2="16" y2="12"/></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900">Preventative Upkeep</h3>
                    <p class="mt-3 text-gray-600">
                        Seasonal property checks, regular gutter cleaning, securing loose railings, and general maintenance plans.
                    </p>
                </div>

            </div>
            <div class="mt-12">
                <a href="#contact" class="inline-block bg-atlas-blue text-white px-8 py-3 rounded-xl text-lg font-bold hover:bg-atlas-light btn-primary shadow-xl">
                    Request Service Today
                </a>
            </div>
        </div>
    </section>

    <section class="py-16 sm:py-24 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="order-2 md:order-1">
                    <h2 class="text-4xl font-extrabold text-gray-900">Why Choose Atlas Maintenance?</h2>
                    <p class="mt-4 text-gray-600 text-lg">
                        We believe quality maintenance shouldn't be a headache. We provide **transparent pricing**, show up **on time**, and offer a **100% satisfaction guarantee** on every job, big or small. Our team is fully insured and trained to handle a vast array of general maintenance needs, giving you peace of mind.
                    </p>
                    <ul class="mt-6 space-y-3 text-gray-700">
                        <li class="flex items-center text-lg"><span class="text-atlas-blue font-bold mr-2 text-2xl">&check;</span> Reliable & Vetted Professionals</li>
                        <li class="flex items-center text-lg"><span class="text-atlas-blue font-bold mr-2 text-2xl">&check;</span> Fully Insured & Licensed</li>
                        <li class="flex items-center text-lg"><span class="text-atlas-blue font-bold mr-2 text-2xl">&check;</span> Upfront, Honest Quotes</li>
                    </ul>
                </div>
                <div class="order-1 md:order-2">
                    <img src="https://placehold.co/600x400/1e3a8a/ffffff?text=Professional+Team+Serving+You" 
                         alt="Atlas Maintenance Professional Team" 
                         class="rounded-xl shadow-2xl w-full h-auto object-cover"
                         onerror="this.src='https://placehold.co/600x400/1e3a8a/ffffff?text=Professional+Team+Serving+You';">
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 sm:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-atlas-blue p-8 sm:p-12 rounded-xl shadow-2xl text-white">
                <h2 class="text-4xl font-extrabold text-white text-center">Ready for Reliable Service?</h2>
                <p class="mt-4 text-xl text-indigo-200 text-center">
                    Tell us about your project (inside or out) and we'll get back to you with a free, non-binding estimate.
                </p>

                <form id="quoteForm" class="mt-8 max-w-lg mx-auto space-y-4">
                    <input type="text" placeholder="Your Name" required
                           class="w-full p-4 rounded-lg text-gray-900 border-2 border-indigo-500 focus:outline-none focus:border-indigo-400">
                    <input type="email" placeholder="Email Address" required
                           class="w-full p-4 rounded-lg text-gray-900 border-2 border-indigo-500 focus:outline-none focus:border-indigo-400">
                    <textarea rows="4" placeholder="Describe the maintenance/repair needed (e.g., Lawn Mowing, Pressure Wash, Drywall Patching...)" required
                              class="w-full p-4 rounded-lg text-gray-900 border-2 border-indigo-500 focus:outline-none focus:border-indigo-400"></textarea>
                    
                    <button type="submit"
                            class="w-full bg-atlas-light text-white p-4 rounded-xl text-lg font-bold hover:bg-white hover:text-atlas-blue btn-primary shadow-xl">
                        Send My Quote Request
                    </button>
                    <p id="formMessage" class="text-center text-sm mt-3 hidden"></p>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-white py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="mb-4">
                <span class="text-2xl font-extrabold text-atlas-light">ATLAS</span>
                <span class="text-2xl font-light text-gray-400">Maintenance</span>
            </div>
            <p class="text-gray-400">&copy; 2025 Atlas Maintenance. All rights reserved. | Total Property Upkeep</p>
            <p class="mt-2 text-sm text-gray-500">Contact: (555) 555-ATLAS | service@atlasmaintenance.com</p>
        </div>
    </footer>

    <script>
        document.getElementById('quoteForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const messageEl = document.getElementById('formMessage');
            messageEl.classList.remove('hidden', 'text-red-400');
            messageEl.classList.add('text-green-400');
            messageEl.textContent = '✅ Quote request sent! We will contact you within 24 hours. Thanks for choosing Atlas!';
            
            // In a real application, you would send this data to a backend server here.
            this.reset();
        });
    </script>
</body>
</html>
```eof

The site now clearly highlights your full range of services, using a touch of green to visually connect the **Lawn & Yard Care** and **Exterior Cleaning** (including **pressure washing** and **window cleaning**) to the classic blue of your **General Interior Repairs**