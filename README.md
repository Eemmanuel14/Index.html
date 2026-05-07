<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heavens Company Limited | Reliable Logistics in Ghana</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: '#0f172a',
                        gold: '#D4AF37',
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white text-slate-800 font-sans text-sm md:text-base">

    <nav class="bg-white/90 backdrop-blur-md sticky top-0 z-50 shadow-sm border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
            <span class="text-xl font-bold text-navy uppercase tracking-tighter">Heavens <span class="text-gold text-[10px] italic">Co. Ltd</span></span>
            <div class="hidden md:flex space-x-6 font-bold uppercase text-xs tracking-widest text-navy">
                <a href="#home" class="hover:text-gold transition">Home</a>
                <a href="#services" class="hover:text-gold transition">Services</a>
                <a href="#contact" class="hover:text-gold transition">Contact</a>
            </div>
            <a href="https://wa.me/233542310189" class="bg-green-500 text-white px-4 py-2 rounded text-xs font-bold uppercase">WhatsApp</a>
        </div>
    </nav>

    <section id="home" class="relative min-h-[70vh] flex items-center bg-navy text-white overflow-hidden">
        <div class="absolute inset-0 opacity-40">
            <img src="https://images.unsplash.com/photo-1519003722824-194d4455a60c?auto=format&fit=crop&w=1200&q=80" class="w-full h-full object-cover" alt="Truck">
        </div>
        <div class="relative z-10 p-6 max-w-4xl mx-auto text-center">
            <div class="text-gold mb-2 font-bold flex justify-center gap-1"><i class="fa-solid fa-star"></i> 5.0 Google Rating</div>
            <h1 class="text-4xl md:text-6xl font-black uppercase leading-tight mb-4">Reliable Transportation <span class="text-gold">You Can Trust</span></h1>
            <p class="text-gray-300 mb-8 max-w-xl mx-auto">Moving your cargo across Ghana with speed, safety, and professionalism. Based in Adenta, Accra.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#contact" class="bg-gold text-white px-10 py-4 rounded font-bold uppercase">Get a Quote</a>
                <a href="tel:0542310189" class="border border-white/30 bg-white/10 text-white px-10 py-4 rounded font-bold uppercase">Call Now</a>
            </div>
        </div>
    </section>

    <section id="services" class="py-16 px-6 max-w-7xl mx-auto">
        <h2 class="text-center text-3xl font-black text-navy uppercase mb-12 italic">Our Services</h2>
        <div class="grid md:grid-cols-3 gap-6">
            <div class="bg-gray-50 p-8 rounded-xl border-l-4 border-gold">
                <i class="fa-solid fa-truck text-gold text-3xl mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Cargo Transport</h3>
                <p class="text-gray-500">Heavy duty hauling and nationwide logistics support.</p>
            </div>
            <div class="bg-gray-50 p-8 rounded-xl border-l-4 border-navy">
                <i class="fa-solid fa-box text-navy text-3xl mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Delivery Services</h3>
                <p class="text-gray-500">Safe and fast last-mile delivery across Greater Accra.</p>
            </div>
            <div class="bg-gray-50 p-8 rounded-xl border-l-4 border-gold">
                <i class="fa-solid fa-business-time text-gold text-3xl mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Commercial</h3>
                <p class="text-gray-500">Tailored transport solutions for corporate clients.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="bg-navy text-white py-16 px-6">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12">
            <div>
                <h2 class="text-3xl font-black uppercase mb-6">Heavens Company Limited</h2>
                <p class="text-gray-400 mb-8 italic">Trust, Reliability, Speed.</p>
                <div class="space-y-4">
                    <p><i class="fa-solid fa-location-dot text-gold mr-3"></i> Adenta – Accra, Ghana</p>
                    <p><i class="fa-solid fa-phone text-gold mr-3"></i> 0542310189 / 0533851847</p>
                    <p><i class="fa-solid fa-envelope text-gold mr-3"></i> heavenscompanylimited@gmail.com</p>
                </div>
            </div>
            <div class="bg-white p-8 rounded-lg text-navy">
                <h3 class="font-bold mb-4 uppercase">Inquiry Form</h3>
                <input type="text" placeholder="Your Name" class="w-full mb-4 p-3 bg-gray-100 rounded text-sm">
                <textarea placeholder="Service Required" class="w-full mb-4 p-3 bg-gray-100 rounded text-sm h-24"></textarea>
                <button class="w-full bg-navy text-white py-3 rounded font-bold uppercase transition hover:bg-gold">Send Inquiry</button>
            </div>
        </div>
    </section>

    <a href="https://wa.me/233542310189?text=Hello%20Heavens%20Company%20Limited,%20I%20would%20like%20to%20inquire%20about%20your%20transportation%20services." 
       class="fixed bottom-6 right-6 bg-[#25D366] w-14 h-14 rounded-full flex items-center justify-center text-white text-3xl shadow-xl z-50">
        <i class="fa-brands fa-whatsapp"></i>
    </a>

    <footer class="py-8 text-center text-gray-500 text-[10px] uppercase tracking-widest">
        © 2026 Heavens Company Limited. All Rights Reserved.
    </footer>

</body>
</html>
