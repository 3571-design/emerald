<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emerald Image Painting | Professional Residential Painting</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-slate-50 font-sans text-gray-800">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-emerald-700">EMERALD <span class="text-slate-700">IMAGE PAINTING</span></div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#services" class="hover:text-emerald-600 transition">Services</a>
                <a href="#gallery" class="hover:text-emerald-600 transition">Portfolio</a>
                <a href="#contact" class="bg-emerald-600 text-white px-5 py-2 rounded-full hover:bg-emerald-700 transition">Get a Free Quote</a>
            </div>
        </div>
    </nav>

    <header class="relative h-[600px] flex items-center justify-center text-center text-white">
        <div class="absolute inset-0 bg-black opacity-50 z-10"></div>
        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1589939705384-5185137a7f0f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80')] bg-cover bg-center"></div>
        
        <div class="relative z-20 px-4">
            <h1 class="text-5xl md:text-7xl font-bold mb-4">Your Home, <span class="text-emerald-400">Perfectly Painted.</span></h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">Premium interior and exterior painting services with a focus on precision and clean execution.</p>
            <a href="#contact" class="bg-emerald-500 hover:bg-emerald-600 text-white px-8 py-4 rounded-lg text-lg font-bold transition duration-300">Schedule Your Estimate</a>
        </div>
    </header>

    <section id="services" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-16">Our Specialties</h2>
            <div class="grid md:grid-cols-3 gap-12">
                <div class="text-center p-6 border rounded-xl hover:shadow-xl transition">
                    <div class="text-emerald-600 text-4xl mb-4"><i class="fas fa-paint-roller"></i></div>
                    <h3 class="text-2xl font-semibold mb-3">Interior Painting</h3>
                    <p class="text-gray-600">From accent walls to full home transformations. We protect your furniture and floor like it's our own.</p>
                </div>
                <div class="text-center p-6 border rounded-xl hover:shadow-xl transition">
                    <div class="text-emerald-600 text-4xl mb-4"><i class="fas fa-home"></i></div>
                    <h3 class="text-2xl font-semibold mb-3">Exterior Painting</h3>
                    <p class="text-gray-600">Weather-resistant coatings that boost curb appeal and protect your investment for years to come.</p>
                </div>
                <div class="text-center p-6 border rounded-xl hover:shadow-xl transition">
                    <div class="text-emerald-600 text-4xl mb-4"><i class="fas fa-brush"></i></div>
                    <h3 class="text-2xl font-semibold mb-3">Cabinet Refinishing</h3>
                    <p class="text-gray-600">Give your kitchen a factory-finish look without the cost of a full remodel.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-slate-900 text-white">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto bg-white text-gray-800 rounded-2xl overflow-hidden shadow-2xl flex flex-col md:flex-row">
                <div class="md:w-1/2 p-12 bg-emerald-700 text-white">
                    <h2 class="text-3xl font-bold mb-6">Ready for a fresh look?</h2>
                    <p class="mb-8">Fill out the form and we'll contact you within 24 hours to schedule a walk-through.</p>
                    <ul class="space-y-4">
                        <li><i class="fas fa-check-circle mr-2"></i> Licensed & Insured</li>
                        <li><i class="fas fa-check-circle mr-2"></i> 5-Year Warranty</li>
                        <li><i class="fas fa-check-circle mr-2"></i> Free Color Consultation</li>
                    </ul>
                </div>
                <div class="md:w-1/2 p-12">
                    <form action="#" class="space-y-4">
                        <div>
                            <label class="block text-sm font-bold mb-1">Name</label>
                            <input type="text" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-emerald-500 outline-none">
                        </div>
                        <div>
                            <label class="block text-sm font-bold mb-1">Phone</label>
                            <input type="tel" class="w-full p-3 border rounded-lg focus:ring-2 focus:ring-emerald-500 outline-none">
                        </div>
                        <div>
                            <label class="block text-sm font-bold mb-1">Message</label>
                            <textarea class="w-full p-3 border rounded-lg h-32 focus:ring-2 focus:ring-emerald-500 outline-none" placeholder="Tell us about your project..."></textarea>
                        </div>
                        <button class="w-full bg-emerald-600 text-white font-bold py-3 rounded-lg hover:bg-emerald-700 transition">Send Quote Request</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-950 text-gray-400 py-10 text-center">
        <p>&copy; 2026 Emerald Image Painting. All rights reserved.</p>
    </footer>

</body>
</html>
