<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migi Setyo - F&B Hybrid Professional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #f8fafc; font-family: 'Inter', sans-serif; }
        .banner-container {
            width: 100%;
            background-image: url('banner.png');
            background-size: cover;
            background-position: center;
            aspect-ratio: 16 / 6;
        }
        .gallery-img { 
            width: 100%; 
            height: 250px; 
            object-cover: cover; 
            border-radius: 1rem;
            transition: transform 0.3s ease;
        }
        .gallery-img:hover { transform: scale(1.03); }
    </style>
</head>
<body class="p-4 md:p-8">

    <div class="max-w-5xl mx-auto bg-white shadow-2xl rounded-2xl overflow-hidden">
        
        <div class="banner-container border-b-4 border-yellow-600"></div>

        <div class="p-6 md:p-10">
            
            <div class="grid md:grid-cols-2 gap-8 mb-12">
                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100 shadow-sm">
                    <h2 class="text-xs font-black uppercase tracking-widest text-slate-400 mb-3 text-center md:text-left">Executive Summary</h2>
                    <p class="text-slate-700 text-sm leading-relaxed">
                        Lulusan Tata Boga dengan **5+ tahun pengalaman progresif** di industri F&B[cite: 3, 27]. Memiliki kombinasi unik antara keahlian teknis Barista dan kemampuan strategis sebagai Store Manager serta Admin Purchasing. Terbukti mampu **menekan waste hingga 15%** melalui manajemen stok berbasis data[cite: 4, 9].
                    </p>
                </div>
                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100 shadow-sm">
                    <h2 class="text-xs font-black uppercase tracking-widest text-slate-400 mb-3 text-center md:text-left">Professional Objective</h2>
                    <p class="text-slate-700 text-sm leading-relaxed">
                        Mencari posisi di bidang **F&B Operations, Store Management, atau Purchasing** untuk berkontribusi dalam meningkatkan efisiensi operasional dan pertumbuhan bisnis melalui pengalaman manajerial dan teknis yang saya miliki[cite: 7].
                    </p>
                </div>
            </div>

            <div class="mb-12">
                <h2 class="text-center text-gray-800 font-bold text-2xl mb-8 uppercase tracking-tight">Expertise Showcase</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="relative group">
                        <img src="meeting.jpg" alt="Management Meeting" class="gallery-img shadow-lg">
                        <div class="mt-3 text-center">
                            <h3 class="font-bold text-slate-800">Strategic Leadership</h3>
                            <p class="text-xs text-slate-500">Mengarahkan operasional & koordinasi tim </p>
                        </div>
                    </div>
                    <div class="relative group">
                        <img src="product1.jpg" alt="Latte Art Product" class="gallery-img shadow-lg">
                        <div class="mt-3 text-center">
                            <h3 class="font-bold text-slate-800">Quality Craftsmanship</h3>
                            <p class="text-xs text-slate-500">Standar produk tinggi & estetika [cite: 11, 21]</p>
                        </div>
                    </div>
                    <div class="relative group">
                        <img src="product2.jpg" alt="Barista Action" class="gallery-img shadow-lg">
                        <div class="mt-3 text-center">
                            <h3 class="font-bold text-slate-800">Technical Expertise</h3>
                            <p class="text-xs text-slate-500">Penguasaan alur kerja Barista </p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex flex-col items-center gap-8 border-t border-slate-100 pt-10">
                <div class="flex gap-8">
                    <a href="https://www.linkedin.com/in/migisetyo" target="_blank" class="text-slate-400 hover:text-[#0a66c2] text-4xl transition-colors">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="mailto:migisetyosa@gmail.com" class="text-slate-400 hover:text-[#ea4335] text-4xl transition-colors">
                        <i class="fas fa-envelope"></i>
                    </a>
                    <a href="https://wa.me/628112683668" target="_blank" class="text-slate-400 hover:text-[#22c55e] text-4xl transition-colors">
                        <i class="fab fa-whatsapp"></i>
                    </a>
                </div>

                <div class="flex flex-col md:flex-row gap-4 w-full justify-center">
                    <a href="Migi Setyo Sugiarto Adi (10).pdf" download="Migi_Setyo_Adi_CV" class="flex items-center justify-center gap-3 bg-slate-900 text-white px-10 py-4 rounded-xl font-bold hover:bg-slate-800 transition-all w-full md:w-auto">
                        <i class="fas fa-file-download"></i> DOWNLOAD CV (PDF)
                    </a>
                    <a href="https://wa.me/628112683668" target="_blank" class="flex items-center justify-center gap-3 bg-green-500 text-white px-10 py-4 rounded-xl font-bold hover:bg-green-600 transition-all w-full md:w-auto">
                        <i class="fab fa-whatsapp text-lg"></i> HUBUNGI SAYA
                    </a>
                </div>
            </div>

        </div>

        <footer class="bg-slate-50 p-6 text-center border-t border-slate-100">
            <p class="text-slate-400 text-[10px] font-bold uppercase tracking-[0.3em]">Migi Setyo Sugiarto Adi &copy; 2024</p>
        </footer>
    </div>

</body>
</html>
