<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plaza Homes | Luxury Real Estate</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: { DEFAULT: '#D4AF37', light: '#F4E4BC', dark: '#AA8C2C' },
                        dark: { DEFAULT: '#0a0a0a', lighter: '#111111', card: '#1a1a1a', border: '#2a2a2a' }
                    },
                    fontFamily: {
                        cairo: ['Cairo', 'sans-serif'],
                        poppins: ['Poppins', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Cairo', sans-serif; background-color: #0a0a0a; color: #e5e5e5; overflow-x: hidden; }
        .gold-text { color: #D4AF37; }
        .gold-bg { background-color: #D4AF37; }
        .gold-border { border-color: #D4AF37; }
        .glass { background: rgba(26, 26, 26, 0.85); backdrop-filter: blur(12px); border: 1px solid rgba(212, 175, 55, 0.15); }
        .gold-gradient { background: linear-gradient(135deg, #D4AF37 0%, #F4E4BC 50%, #AA8C2C 100%); }
        .card-hover { transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); }
        .card-hover:hover { transform: translateY(-8px); box-shadow: 0 20px 40px rgba(212, 175, 55, 0.15); border-color: rgba(212, 175, 55, 0.4); }
        .fade-in { animation: fadeIn 0.6s ease-out forwards; opacity: 0; }
        @keyframes fadeIn { to { opacity: 1; } }
        .slide-up { animation: slideUp 0.6s ease-out forwards; opacity: 0; transform: translateY(30px); }
        @keyframes slideUp { to { opacity: 1; transform: translateY(0); } }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        .loader { border: 3px solid #1a1a1a; border-top: 3px solid #D4AF37; border-radius: 50%; width: 40px; height: 40px; animation: spin 1s linear infinite; }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
        .property-image { transition: transform 0.6s ease; }
        .property-card:hover .property-image { transform: scale(1.1); }
        .nav-link { position: relative; }
        .nav-link::after { content: ''; position: absolute; bottom: -4px; right: 0; width: 0; height: 2px; background: #D4AF37; transition: width 0.3s ease; }
        .nav-link:hover::after { width: 100%; }
        .btn-gold { background: linear-gradient(135deg, #D4AF37, #AA8C2C); color: #0a0a0a; font-weight: 700; transition: all 0.3s; }
        .btn-gold:hover { box-shadow: 0 0 25px rgba(212, 175, 55, 0.4); transform: translateY(-2px); }
        input, select, textarea { background: #111111 !important; border: 1px solid #2a2a2a !important; color: #e5e5e5 !important; transition: all 0.3s; }
        input:focus, select:focus, textarea:focus { border-color: #D4AF37 !important; box-shadow: 0 0 0 3px rgba(212, 175, 55, 0.1) !important; outline: none !important; }

        /* CRITICAL FIX: Sections hidden completely */
        .app-section {
            display: none !important;
            visibility: hidden;
            opacity: 0;
            height: 0;
            overflow: hidden;
        }
        .app-section.active-section {
            display: block !important;
            visibility: visible;
            opacity: 1;
            height: auto;
            overflow: visible;
            animation: fadeIn 0.4s ease-out;
        }

        .toast { position: fixed; top: 20px; left: 50%; transform: translateX(-50%) translateY(-100px); background: #1a1a1a; border: 1px solid #D4AF37; color: #D4AF37; padding: 12px 24px; border-radius: 8px; z-index: 1000; transition: transform 0.4s cubic-bezier(0.68, -0.55, 0.265, 1.55); font-weight: 600; }
        .toast.show { transform: translateX(-50%) translateY(0); }

        /* Hidden Admin Lock Button */
        .admin-lock-btn {
            position: fixed;
            bottom: 1px;
            left: 1px;
            z-index: 50;
            width: 12px;
            height: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0.06;
            transition: opacity 0.3s;
            background: none;
            border: none;
            padding: 0;
            outline: none;
        }
        .admin-lock-btn:hover { opacity: 0.4; }
        .admin-lock-btn i { font-size: 9px; color: #444; }

        /* Live Preview Card */
        .live-preview {
            position: sticky;
            top: 100px;
            transition: all 0.3s ease;
        }
        .preview-label {
            position: absolute;
            top: -10px;
            right: 20px;
            background: #D4AF37;
            color: #0a0a0a;
            padding: 2px 12px;
            border-radius: 20px;
            font-size: 10px;
            font-weight: 700;
            z-index: 10;
        }
    </style>
<base target="_blank">
</head>
<body class="font-cairo">

    <!-- Toast Notification -->
    <div id="toast" class="toast">تمت العملية بنجاح</div>

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center gap-3 cursor-pointer" onclick="showPage('home')">
                    <div class="w-10 h-10 gold-gradient rounded-lg flex items-center justify-center">
                        <i class="fas fa-building text-dark text-lg"></i>
                    </div>
                    <div>
                        <h1 class="text-xl font-bold gold-text tracking-wider font-poppins">PLAZA HOMES</h1>
                        <p class="text-[10px] text-gray-400 -mt-1 tracking-widest">LUXURY REAL ESTATE</p>
                    </div>
                </div>
                <div class="hidden md:flex items-center gap-8">
                    <button onclick="showPage('home')" class="nav-link text-sm hover:text-gold transition-colors">الرئيسية</button>
                    <button onclick="showPage('properties')" class="nav-link text-sm hover:text-gold transition-colors">العقارات</button>
                    <button onclick="showPage('about')" class="nav-link text-sm hover:text-gold transition-colors">من نحن</button>
                    <button onclick="showPage('contact')" class="nav-link text-sm hover:text-gold transition-colors">تواصل معنا</button>
                </div>
                <button onclick="showPage('properties')" class="btn-gold px-6 py-2 rounded-full text-sm">استكشف العقارات</button>
                <button class="md:hidden text-gold text-xl" onclick="toggleMobileMenu()">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="hidden md:hidden glass border-t border-dark-border">
            <div class="px-4 py-4 space-y-3">
                <button onclick="showPage('home'); toggleMobileMenu()" class="block w-full text-right py-2 hover:text-gold">الرئيسية</button>
                <button onclick="showPage('properties'); toggleMobileMenu()" class="block w-full text-right py-2 hover:text-gold">العقارات</button>
                <button onclick="showPage('about'); toggleMobileMenu()" class="block w-full text-right py-2 hover:text-gold">من نحن</button>
                <button onclick="showPage('contact'); toggleMobileMenu()" class="block w-full text-right py-2 hover:text-gold">تواصل معنا</button>
            </div>
        </div>
    </nav>

    <div id="app">

        <!-- HOME SECTION -->
        <div id="home" class="app-section active-section">
            <div class="relative h-screen flex items-center justify-center overflow-hidden">
                <div class="absolute inset-0 bg-gradient-to-b from-dark/60 via-dark/40 to-dark z-10"></div>
                <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=1920&q=80')] bg-cover bg-center"></div>
                <div class="relative z-20 text-center px-4 max-w-5xl mx-auto">
                    <div class="slide-up" style="animation-delay: 0.1s">
                        <span class="inline-block px-4 py-1 rounded-full border border-gold/30 text-gold text-xs tracking-widest mb-6 bg-dark/50 backdrop-blur-sm">PLAZA HOMES - ZAHRAA NASR CITY</span>
                    </div>
                    <h1 class="text-5xl md:text-7xl font-bold mb-6 slide-up leading-tight" style="animation-delay: 0.2s">
                        اكتشف <span class="gold-text">الفخامة</span><br>في كل زاوية
                    </h1>
                    <p class="text-gray-300 text-lg md:text-xl mb-10 max-w-2xl mx-auto slide-up" style="animation-delay: 0.3s">
                        نقدم لك مجموعة مختارة من أرقى العقارات في مصر الجديدة، مدينة نصر، المعادي، والتجمع الخامس. تجربة عقارية لا مثيل لها.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center slide-up" style="animation-delay: 0.4s">
                        <button onclick="showPage('properties')" class="btn-gold px-8 py-4 rounded-full text-base">تصفح العقارات</button>
                        <button onclick="showPage('contact')" class="px-8 py-4 rounded-full border border-gold/30 text-gold hover:bg-gold/10 transition-all">تواصل معنا</button>
                    </div>
                </div>
                <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 z-20 animate-bounce">
                    <i class="fas fa-chevron-down text-gold text-2xl"></i>
                </div>
            </div>

            <div class="py-20 bg-dark-lighter">
                <div class="max-w-7xl mx-auto px-4 grid grid-cols-2 md:grid-cols-4 gap-8">
                    <div class="text-center fade-in" style="animation-delay: 0.1s">
                        <div class="text-4xl font-bold gold-text mb-2">+500</div>
                        <div class="text-gray-400 text-sm">عقار مباع</div>
                    </div>
                    <div class="text-center fade-in" style="animation-delay: 0.2s">
                        <div class="text-4xl font-bold gold-text mb-2">+1200</div>
                        <div class="text-gray-400 text-sm">عميل سعيد</div>
                    </div>
                    <div class="text-center fade-in" style="animation-delay: 0.3s">
                        <div class="text-4xl font-bold gold-text mb-2">6</div>
                        <div class="text-gray-400 text-sm">سنوات خبرة</div>
                    </div>
                    <div class="text-center fade-in" style="animation-delay: 0.4s">
                        <div class="text-4xl font-bold gold-text mb-2">4</div>
                        <div class="text-gray-400 text-sm">مناطق رئيسية</div>
                    </div>
                </div>
            </div>

            <div class="py-24 bg-dark">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="text-center mb-16">
                        <span class="text-gold text-sm tracking-widest">المميز لدينا</span>
                        <h2 class="text-4xl font-bold mt-2">أحدث العقارات</h2>
                        <div class="w-24 h-1 gold-gradient mx-auto mt-4 rounded-full"></div>
                    </div>
                    <div id="featured-properties" class="grid md:grid-cols-3 gap-8">
                        <div class="col-span-full flex justify-center py-12">
                            <div class="loader"></div>
                        </div>
                    </div>
                    <div class="text-center mt-12">
                        <button onclick="showPage('properties')" class="px-8 py-3 border border-gold/30 text-gold rounded-full hover:bg-gold/10 transition-all">عرض جميع العقارات</button>
                    </div>
                </div>
            </div>

            <div class="py-24 bg-dark-lighter">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="text-center mb-16">
                        <span class="text-gold text-sm tracking-widest">نغطي أفضل المناطق</span>
                        <h2 class="text-4xl font-bold mt-2">المناطق الرئيسية</h2>
                        <div class="w-24 h-1 gold-gradient mx-auto mt-4 rounded-full"></div>
                    </div>
                    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                        <div class="relative group overflow-hidden rounded-2xl h-80 cursor-pointer" onclick="filterByLocation('مصر الجديدة')">
                            <img src="https://images.unsplash.com/photo-1564013799919-ab600027ffc6?w=600&q=80" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="مصر الجديدة">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark via-dark/50 to-transparent"></div>
                            <div class="absolute bottom-0 right-0 p-6">
                                <h3 class="text-2xl font-bold mb-1">مصر الجديدة</h3>
                                <p class="text-gray-300 text-sm">Heliopolis</p>
                            </div>
                        </div>
                        <div class="relative group overflow-hidden rounded-2xl h-80 cursor-pointer" onclick="filterByLocation('مدينة نصر')">
                            <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?w=600&q=80" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="مدينة نصر">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark via-dark/50 to-transparent"></div>
                            <div class="absolute bottom-0 right-0 p-6">
                                <h3 class="text-2xl font-bold mb-1">مدينة نصر</h3>
                                <p class="text-gray-300 text-sm">Nasr City</p>
                            </div>
                        </div>
                        <div class="relative group overflow-hidden rounded-2xl h-80 cursor-pointer" onclick="filterByLocation('المعادي')">
                            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=600&q=80" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="المعادي">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark via-dark/50 to-transparent"></div>
                            <div class="absolute bottom-0 right-0 p-6">
                                <h3 class="text-2xl font-bold mb-1">المعادي</h3>
                                <p class="text-gray-300 text-sm">Maadi</p>
                            </div>
                        </div>
                        <div class="relative group overflow-hidden rounded-2xl h-80 cursor-pointer" onclick="filterByLocation('التجمع الخامس')">
                            <img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?w=600&q=80" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-110" alt="التجمع">
                            <div class="absolute inset-0 bg-gradient-to-t from-dark via-dark/50 to-transparent"></div>
                            <div class="absolute bottom-0 right-0 p-6">
                                <h3 class="text-2xl font-bold mb-1">التجمع الخامس</h3>
                                <p class="text-gray-300 text-sm">New Cairo</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- PROPERTIES SECTION -->
        <div id="properties" class="app-section">
            <div class="pt-24 pb-12 min-h-screen">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="text-center mb-12">
                        <span class="text-gold text-sm tracking-widest">استكشف</span>
                        <h2 class="text-4xl font-bold mt-2">قائمة العقارات</h2>
                        <div class="w-24 h-1 gold-gradient mx-auto mt-4 rounded-full"></div>
                    </div>

                    <div class="glass rounded-2xl p-6 mb-10">
                        <div class="mb-4">
                            <div class="relative">
                                <i class="fas fa-search absolute right-4 top-1/2 transform -translate-y-1/2 text-gold"></i>
                                <input type="text" id="search-input" class="w-full px-4 py-3 pr-12 rounded-xl text-sm" placeholder="ابحث باسم المنطقة أو العنوان أو الكود..." oninput="applyFilters()">
                            </div>
                        </div>
                        <div class="grid md:grid-cols-4 gap-4">
                            <select id="filter-location" class="w-full px-4 py-3 rounded-xl text-sm" onchange="applyFilters()">
                                <option value="">كل المناطق</option>
                                <optgroup label="مصر الجديدة">
                                    <option value="مصر الجديدة - الميرغني">الميرغني</option>
                                    <option value="مصر الجديدة - ثروت">ثروت</option>
                                    <option value="مصر الجديدة - عمر بن الخطاب">عمر بن الخطاب</option>
                                    <option value="مصر الجديدة - الحجاز">الحجاز</option>
                                    <option value="مصر الجديدة - إبراهيم اللقاني">إبراهيم اللقاني</option>
                                    <option value="مصر الجديدة - الخليفة المأمون">الخليفة المأمون</option>
                                    <option value="مصر الجديدة - النزهة">النزهة</option>
                                    <option value="مصر الجديدة - العروبة">العروبة</option>
                                </optgroup>
                                <optgroup label="مدينة نصر">
                                    <option value="مدينة نصر - حي السفارات">حي السفارات</option>
                                    <option value="مدينة نصر - السبع أبنية">السبع أبنية</option>
                                    <option value="مدينة نصر - حي أول">حي أول</option>
                                    <option value="مدينة نصر - حي ثانٍ">حي ثانٍ</option>
                                    <option value="مدينة نصر - حي ثالث">حي ثالث</option>
                                    <option value="مدينة نصر - حي رابع">حي رابع</option>
                                    <option value="مدينة نصر - حي خامس">حي خامس</option>
                                    <option value="مدينة نصر - حي سادس">حي سادس</option>
                                    <option value="مدينة نصر - المنطقة الثامنة">المنطقة الثامنة</option>
                                    <option value="مدينة نصر - المنطقة العاشرة">المنطقة العاشرة</option>
                                    <option value="مدينة نصر - المنطقة الحادية عشر">المنطقة الحادية عشر</option>
                                    <option value="مدينة نصر - زهراء مدينة نصر">زهراء مدينة نصر</option>
                                    <option value="مدينة نصر - المنطقة الصناعية">المنطقة الصناعية</option>
                                </optgroup>
                                <optgroup label="المعادي">
                                    <option value="المعادي - المعادي الجديدة">المعادي الجديدة</option>
                                    <option value="المعادي - المعادي القديمة">المعادي القديمة</option>
                                    <option value="المعادي - دجلة">دجلة</option>
                                    <option value="المعادي - كورنيش المعادي">كورنيش المعادي</option>
                                    <option value="المعادي - سرايات المعادي">سرايات المعادي</option>
                                    <option value="المعادي - ثكنات المعادي">ثكنات المعادي</option>
                                    <option value="المعادي - المنطقة الأولى">المنطقة الأولى</option>
                                    <option value="المعادي - المنطقة الثالثة">المنطقة الثالثة</option>
                                    <option value="المعادي - المنطقة الخامسة">المنطقة الخامسة</option>
                                </optgroup>
                                <optgroup label="التجمع الخامس">
                                    <option value="التجمع الخامس - البنفسج">البنفسج</option>
                                    <option value="التجمع الخامس - الياسمين">الياسمين</option>
                                    <option value="التجمع الخامس - اللوتس">اللوتس</option>
                                    <option value="التجمع الخامس - الجنينة">الجنينة</option>
                                    <option value="التجمع الخامس - القطامية">القطامية</option>
                                    <option value="التجمع الخامس - القاهرة الجديدة">القاهرة الجديدة</option>
                                    <option value="التجمع الخامس - مدينتي">مدينتي</option>
                                    <option value="التجمع الخامس - الرحاب">الرحاب</option>
                                    <option value="التجمع الخامس - الشروق">الشروق</option>
                                    <option value="التجمع الخامس - التجمع الأول">التجمع الأول</option>
                                    <option value="التجمع الخامس - التجمع الثالث">التجمع الثالث</option>
                                </optgroup>
                            </select>
                            <select id="filter-type" class="w-full px-4 py-3 rounded-xl text-sm" onchange="applyFilters()">
                                <option value="">كل الأنواع</option>
                                <option value="شقة">شقة</option>
                                <option value="فيلا">فيلا</option>
                                <option value="دوبلكس">دوبلكس</option>
                                <option value="بنتهاوس">بنتهاوس</option>
                                <option value="محل تجاري">محل تجاري</option>
                                <option value="مكتب إداري">مكتب إداري</option>
                            </select>
                            <select id="filter-rooms" class="w-full px-4 py-3 rounded-xl text-sm" onchange="applyFilters()">
                                <option value="">عدد الغرف</option>
                                <option value="1">1 غرفة</option>
                                <option value="2">2 غرفة</option>
                                <option value="3">3 غرف</option>
                                <option value="4">4 غرف</option>
                                <option value="5">5+ غرف</option>
                            </select>
                            <select id="filter-price" class="w-full px-4 py-3 rounded-xl text-sm" onchange="applyFilters()">
                                <option value="">السعر</option>
                                <option value="0-1000000">حتى 1 مليون</option>
                                <option value="1000000-3000000">1 - 3 مليون</option>
                                <option value="3000000-5000000">3 - 5 مليون</option>
                                <option value="5000000-10000000">5 - 10 مليون</option>
                                <option value="10000000-999999999">10+ مليون</option>
                            </select>
                        </div>
                    </div>

                    <div id="properties-grid" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                        <div class="col-span-full flex justify-center py-12">
                            <div class="loader"></div>
                        </div>
                    </div>
                    <div id="no-results" class="hidden text-center py-20">
                        <i class="fas fa-search text-6xl text-gray-700 mb-4"></i>
                        <p class="text-xl text-gray-400">لا توجد عقارات مطابقة للبحث</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- PROPERTY DETAIL SECTION -->
        <div id="property-detail" class="app-section">
            <div class="pt-24 pb-12 min-h-screen">
                <div class="max-w-7xl mx-auto px-4">
                    <button onclick="showPage('properties')" class="mb-6 flex items-center gap-2 text-gold hover:text-gold-light transition-colors">
                        <i class="fas fa-arrow-right"></i>
                        <span>العودة للعقارات</span>
                    </button>
                    <div id="property-detail-content"></div>
                </div>
            </div>
        </div>

        <!-- ABOUT SECTION -->
        <div id="about" class="app-section">
            <div class="pt-24 pb-12 min-h-screen">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="grid md:grid-cols-2 gap-16 items-center">
                        <div>
                            <span class="text-gold text-sm tracking-widest">من نحن</span>
                            <h2 class="text-4xl font-bold mt-2 mb-6">Plaza Homes<br>للعقارات الفاخرة</h2>
                            <div class="w-20 h-1 gold-gradient mb-8 rounded-full"></div>
                            <p class="text-gray-300 leading-relaxed mb-6">
                                نحن شركة Plaza Homes للعقارات، مقرنا زهراء مدينة نصر. نتخصص في تقديم خدمات عقارية متميزة تشمل البيع والشراء والإيجار للعقارات الفاخرة في أرقى مناطق القاهرة.
                            </p>
                            <p class="text-gray-300 leading-relaxed mb-8">
                                نغطي مناطق مصر الجديدة، مدينة نصر بأحيائها المختلفة، المعادي بجميع أقسامها، والتجمع الخامس بأحيائه الراقية. هدفنا هو تقديم تجربة عقارية سلسة وآمنة لعملائنا الكرام.
                            </p>
                            <div class="grid grid-cols-2 gap-6">
                                <div class="glass p-4 rounded-xl">
                                    <i class="fas fa-shield-alt text-gold text-2xl mb-2"></i>
                                    <h4 class="font-bold mb-1">أمان تام</h4>
                                    <p class="text-gray-400 text-sm">صفقات موثقة وقانونية 100%</p>
                                </div>
                                <div class="glass p-4 rounded-xl">
                                    <i class="fas fa-clock text-gold text-2xl mb-2"></i>
                                    <h4 class="font-bold mb-1">سرعة التنفيذ</h4>
                                    <p class="text-gray-400 text-sm">إنهاء الإجراءات في أسرع وقت</p>
                                </div>
                            </div>
                        </div>
                        <div class="relative">
                            <div class="absolute -inset-4 gold-gradient rounded-2xl opacity-20 blur-2xl"></div>
                            <img src="https://images.unsplash.com/photo-1600585154526-990dced4db0d?w=800&q=80" class="relative rounded-2xl w-full h-[500px] object-cover" alt="About">
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- CONTACT SECTION -->
        <div id="contact" class="app-section">
            <div class="pt-24 pb-12 min-h-screen">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="text-center mb-16">
                        <span class="text-gold text-sm tracking-widest">تواصل معنا</span>
                        <h2 class="text-4xl font-bold mt-2">نحن هنا لمساعدتك</h2>
                        <div class="w-24 h-1 gold-gradient mx-auto mt-4 rounded-full"></div>
                    </div>
                    <div class="grid md:grid-cols-2 gap-12">
                        <div class="glass rounded-2xl p-8">
                            <h3 class="text-2xl font-bold mb-6">معلومات التواصل</h3>
                            <div class="space-y-6">
                                <div class="flex items-start gap-4">
                                    <div class="w-12 h-12 gold-gradient rounded-xl flex items-center justify-center flex-shrink-0">
                                        <i class="fas fa-map-marker-alt text-dark"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-bold mb-1">العنوان</h4>
                                        <p class="text-gray-400">زهراء مدينة نصر، القاهرة، مصر</p>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="w-12 h-12 gold-gradient rounded-xl flex items-center justify-center flex-shrink-0">
                                        <i class="fas fa-phone text-dark"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-bold mb-1">الهاتف</h4>
                                        <p class="text-gray-400" dir="ltr">+20 112 559 5673</p>
                                    </div>
                                </div>
                                <div class="flex items-start gap-4">
                                    <div class="w-12 h-12 gold-gradient rounded-xl flex items-center justify-center flex-shrink-0">
                                        <i class="fab fa-whatsapp text-dark"></i>
                                    </div>
                                    <div>
                                        <h4 class="font-bold mb-1">واتساب</h4>
                                        <p class="text-gray-400" dir="ltr">+20 112 559 5673</p>
                                    </div>
                                </div>
                            </div>
                            <div class="mt-8 pt-8 border-t border-dark-border">
                                <h4 class="font-bold mb-4">تابعنا</h4>
                                <div class="flex gap-4">
                                    <a href="https://www.facebook.com/profile.php?id=61577387500877&locale=ar_AR" target="_blank" class="w-10 h-10 rounded-full glass flex items-center justify-center hover:bg-gold hover:text-dark transition-all"><i class="fab fa-facebook-f"></i></a>
                                    <a href="#" class="w-10 h-10 rounded-full glass flex items-center justify-center hover:bg-gold hover:text-dark transition-all"><i class="fab fa-instagram"></i></a>
                                    <a href="#" class="w-10 h-10 rounded-full glass flex items-center justify-center hover:bg-gold hover:text-dark transition-all"><i class="fab fa-tiktok"></i></a>
                                </div>
                            </div>
                        </div>
                        <div class="glass rounded-2xl p-8">
                            <h3 class="text-2xl font-bold mb-6">أرسل لنا رسالة</h3>
                            <form onsubmit="event.preventDefault(); showToast('تم إرسال رسالتك بنجاح'); this.reset();">
                                <div class="space-y-4">
                                    <div>
                                        <label class="block text-sm mb-2 text-gray-400">الاسم</label>
                                        <input type="text" class="w-full px-4 py-3 rounded-xl" required>
                                    </div>
                                    <div>
                                        <label class="block text-sm mb-2 text-gray-400">رقم الهاتف</label>
                                        <input type="tel" class="w-full px-4 py-3 rounded-xl" required>
                                    </div>
                                    <div>
                                        <label class="block text-sm mb-2 text-gray-400">الرسالة</label>
                                        <textarea rows="4" class="w-full px-4 py-3 rounded-xl resize-none" required></textarea>
                                    </div>
                                    <button type="submit" class="btn-gold w-full py-4 rounded-xl text-base">إرسال الرسالة</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- ADMIN LOGIN - COMPLETELY HIDDEN -->
        <div id="admin-login" class="app-section">
            <div class="min-h-screen flex items-center justify-center pt-24 pb-12">
                <div class="max-w-md w-full mx-4">
                    <div class="glass rounded-2xl p-8">
                        <div class="text-center mb-8">
                            <div class="w-16 h-16 gold-gradient rounded-2xl flex items-center justify-center mx-auto mb-4">
                                <i class="fas fa-lock text-dark text-2xl"></i>
                            </div>
                            <h2 class="text-2xl font-bold">لوحة الإدارة</h2>
                            <p class="text-gray-400 text-sm mt-2">تسجيل دخول مسؤول النظام</p>
                        </div>
                        <form onsubmit="event.preventDefault(); handleAdminLogin();">
                            <div class="space-y-4">
                                <div>
                                    <label class="block text-sm mb-2 text-gray-400">اسم المستخدم</label>
                                    <input type="text" id="admin-user" class="w-full px-4 py-3 rounded-xl" value="admin">
                                </div>
                                <div>
                                    <label class="block text-sm mb-2 text-gray-400">كلمة المرور</label>
                                    <input type="password" id="admin-pass" class="w-full px-4 py-3 rounded-xl">
                                </div>
                                <button type="submit" class="btn-gold w-full py-4 rounded-xl text-base">دخول</button>
                                <button type="button" onclick="showPage('home')" class="w-full py-3 text-gray-400 hover:text-white transition-colors text-sm">العودة للموقع</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>

        <!-- ADMIN PANEL - COMPLETELY HIDDEN -->
        <div id="admin-panel" class="app-section">
            <div class="pt-24 pb-12 min-h-screen">
                <div class="max-w-7xl mx-auto px-4">
                    <div class="flex justify-between items-center mb-8">
                        <div>
                            <h2 class="text-3xl font-bold">لوحة الإدارة</h2>
                            <p class="text-gray-400 text-sm">إدارة العقارات والمحتوى</p>
                        </div>
                        <button onclick="adminLogout()" class="px-6 py-2 border border-red-500/30 text-red-400 rounded-full hover:bg-red-500/10 transition-all text-sm">
                            <i class="fas fa-sign-out-alt ml-2"></i>خروج
                        </button>
                    </div>

                    <div class="grid lg:grid-cols-5 gap-8">
                        <!-- Add Property Form -->
                        <div class="lg:col-span-2">
                            <div class="glass rounded-2xl p-6 sticky top-24">
                                <h3 class="text-xl font-bold mb-6 flex items-center gap-2">
                                    <i class="fas fa-plus-circle text-gold"></i>
                                    إضافة عقار جديد
                                </h3>
                                <form id="add-property-form" onsubmit="event.preventDefault(); handleAddProperty();">
                                    <div class="space-y-4 max-h-[65vh] overflow-y-auto hide-scrollbar pr-1">
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">كود العقار *</label>
                                            <input type="text" id="prop-code" class="w-full px-3 py-2 rounded-lg text-sm" placeholder="مثال: PH-001" required oninput="updatePreview()">
                                        </div>
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">العنوان *</label>
                                            <input type="text" id="prop-title" class="w-full px-3 py-2 rounded-lg text-sm" placeholder="عنوان العقار" required oninput="updatePreview()">
                                        </div>
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">المنطقة *</label>
                                            <select id="prop-location" class="w-full px-3 py-2 rounded-lg text-sm" required onchange="updatePreview()">
                                                <option value="">اختر المنطقة</option>
                                                <optgroup label="مصر الجديدة">
                                                    <option value="مصر الجديدة - الميرغني">الميرغني</option>
                                                    <option value="مصر الجديدة - ثروت">ثروت</option>
                                                    <option value="مصر الجديدة - عمر بن الخطاب">عمر بن الخطاب</option>
                                                    <option value="مصر الجديدة - الحجاز">الحجاز</option>
                                                    <option value="مصر الجديدة - إبراهيم اللقاني">إبراهيم اللقاني</option>
                                                    <option value="مصر الجديدة - الخليفة المأمون">الخليفة المأمون</option>
                                                    <option value="مصر الجديدة - النزهة">النزهة</option>
                                                    <option value="مصر الجديدة - العروبة">العروبة</option>
                                                </optgroup>
                                                <optgroup label="مدينة نصر">
                                                    <option value="مدينة نصر - حي السفارات">حي السفارات</option>
                                                    <option value="مدينة نصر - السبع أبنية">السبع أبنية</option>
                                                    <option value="مدينة نصر - حي أول">حي أول</option>
                                                    <option value="مدينة نصر - حي ثانٍ">حي ثانٍ</option>
                                                    <option value="مدينة نصر - حي ثالث">حي ثالث</option>
                                                    <option value="مدينة نصر - حي رابع">حي رابع</option>
                                                    <option value="مدينة نصر - حي خامس">حي خامس</option>
                                                    <option value="مدينة نصر - حي سادس">حي سادس</option>
                                                    <option value="مدينة نصر - المنطقة الثامنة">المنطقة الثامنة</option>
                                                    <option value="مدينة نصر - المنطقة العاشرة">المنطقة العاشرة</option>
                                                    <option value="مدينة نصر - المنطقة الحادية عشر">المنطقة الحادية عشر</option>
                                                    <option value="مدينة نصر - زهراء مدينة نصر">زهراء مدينة نصر</option>
                                                </optgroup>
                                                <optgroup label="المعادي">
                                                    <option value="المعادي - المعادي الجديدة">المعادي الجديدة</option>
                                                    <option value="المعادي - المعادي القديمة">المعادي القديمة</option>
                                                    <option value="المعادي - دجلة">دجلة</option>
                                                    <option value="المعادي - كورنيش المعادي">كورنيش المعادي</option>
                                                    <option value="المعادي - سرايات المعادي">سرايات المعادي</option>
                                                    <option value="المعادي - ثكنات المعادي">ثكنات المعادي</option>
                                                    <option value="المعادي - المنطقة الأولى">المنطقة الأولى</option>
                                                    <option value="المعادي - المنطقة الثالثة">المنطقة الثالثة</option>
                                                    <option value="المعادي - المنطقة الخامسة">المنطقة الخامسة</option>
                                                </optgroup>
                                                <optgroup label="التجمع الخامس">
                                                    <option value="التجمع الخامس - البنفسج">البنفسج</option>
                                                    <option value="التجمع الخامس - الياسمين">الياسمين</option>
                                                    <option value="التجمع الخامس - اللوتس">اللوتس</option>
                                                    <option value="التجمع الخامس - الجنينة">الجنينة</option>
                                                    <option value="التجمع الخامس - القطامية">القطامية</option>
                                                    <option value="التجمع الخامس - القاهرة الجديدة">القاهرة الجديدة</option>
                                                    <option value="التجمع الخامس - مدينتي">مدينتي</option>
                                                    <option value="التجمع الخامس - الرحاب">الرحاب</option>
                                                    <option value="التجمع الخامس - الشروق">الشروق</option>
                                                    <option value="التجمع الخامس - التجمع الأول">التجمع الأول</option>
                                                    <option value="التجمع الخامس - التجمع الثالث">التجمع الثالث</option>
                                                </optgroup>
                                            </select>
                                        </div>
                                        <div class="grid grid-cols-2 gap-3">
                                            <div>
                                                <label class="block text-xs mb-1 text-gray-400">السعر (جنيه) *</label>
                                                <input type="number" id="prop-price" class="w-full px-3 py-2 rounded-lg text-sm" placeholder="0" required oninput="updatePreview()">
                                            </div>
                                            <div>
                                                <label class="block text-xs mb-1 text-gray-400">المساحة (م²)</label>
                                                <input type="number" id="prop-area" class="w-full px-3 py-2 rounded-lg text-sm" placeholder="0" oninput="updatePreview()">
                                            </div>
                                        </div>
                                        <div class="grid grid-cols-2 gap-3">
                                            <div>
                                                <label class="block text-xs mb-1 text-gray-400">الغرف *</label>
                                                <input type="number" id="prop-rooms" class="w-full px-3 py-2 rounded-lg text-sm" required oninput="updatePreview()">
                                            </div>
                                            <div>
                                                <label class="block text-xs mb-1 text-gray-400">الحمامات *</label>
                                                <input type="number" id="prop-bathrooms" class="w-full px-3 py-2 rounded-lg text-sm" required oninput="updatePreview()">
                                            </div>
                                        </div>
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">النوع</label>
                                            <select id="prop-type" class="w-full px-3 py-2 rounded-lg text-sm" onchange="updatePreview()">
                                                <option value="شقة للبيع">شقة للبيع</option>
                                                <option value="شقة للإيجار">شقة للإيجار</option>
                                                <option value="فيلا للبيع">فيلا للبيع</option>
                                                <option value="فيلا للإيجار">فيلا للإيجار</option>
                                                <option value="دوبلكس للبيع">دوبلكس للبيع</option>
                                                <option value="دوبلكس للإيجار">دوبلكس للإيجار</option>
                                                <option value="بنتهاوس للبيع">بنتهاوس للبيع</option>
                                                <option value="بنتهاوس للإيجار">بنتهاوس للإيجار</option>
                                                <option value="محل تجاري للبيع">محل تجاري للبيع</option>
                                                <option value="محل تجاري للإيجار">محل تجاري للإيجار</option>
                                                <option value="مكتب إداري للبيع">مكتب إداري للبيع</option>
                                                <option value="مكتب إداري للإيجار">مكتب إداري للإيجار</option>
                                            </select>
                                        </div>
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">رابط الصورة <span class="text-gold">*</span></label>
                                            <input type="url" id="prop-image-url" class="w-full px-3 py-2 rounded-lg text-sm" placeholder="https://example.com/image.jpg" required oninput="updatePreview()">
                                            <p class="text-[10px] text-gray-500 mt-1">انسخ رابط الصورة من أي موقع (Imgur, Unsplash, إلخ)</p>
                                        </div>
                                        <div>
                                            <label class="block text-xs mb-1 text-gray-400">الوصف</label>
                                            <textarea id="prop-desc" rows="3" class="w-full px-3 py-2 rounded-lg text-sm resize-none" placeholder="وصف تفصيلي للعقار..." oninput="updatePreview()"></textarea>
                                        </div>
                                        <button type="submit" id="submit-btn" class="btn-gold w-full py-3 rounded-lg text-sm">
                                            <i class="fas fa-plus ml-2"></i>إضافة العقار
                                        </button>
                                    </div>
                                </form>
                            </div>
                        </div>

                        <!-- Live Preview -->
                        <div class="lg:col-span-2">
                            <div class="live-preview glass rounded-2xl overflow-hidden">
                                <div class="preview-label">معاينة حية</div>
                                <div class="relative h-56 overflow-hidden bg-dark-lighter">
                                    <img id="preview-image" src="https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=600&q=80" class="w-full h-full object-cover transition-all duration-500" alt="Preview">
                                    <div class="absolute top-3 right-3 gold-gradient text-dark px-3 py-1 rounded-full text-xs font-bold" id="preview-type">شقة</div>
                                </div>
                                <div class="p-5">
                                    <div class="flex justify-between items-start mb-2">
                                        <h3 class="font-bold text-lg line-clamp-1" id="preview-title">عنوان العقار</h3>
                                        <span class="text-gold font-bold text-sm" dir="ltr" id="preview-price">0 ج.م</span>
                                    </div>
                                    <p class="text-gray-400 text-sm mb-4"><i class="fas fa-map-marker-alt ml-1 text-gold"></i><span id="preview-location">المنطقة</span></p>
                                    <div class="flex items-center gap-4 text-sm text-gray-400 border-t border-dark-border pt-4">
                                        <span><i class="fas fa-bed ml-1 text-gold"></i><span id="preview-rooms">0</span> غرف</span>
                                        <span><i class="fas fa-bath ml-1 text-gold"></i><span id="preview-bathrooms">0</span> حمام</span>
                                        <span><i class="fas fa-ruler-combined ml-1 text-gold"></i><span id="preview-area">-</span> م²</span>
                                    </div>
                                    <div class="mt-4 pt-3 border-t border-dark-border">
                                        <span class="text-xs text-gray-500">كود: <span id="preview-code">---</span></span>
                                    </div>
                                    <div class="mt-3 p-3 bg-dark-lighter rounded-lg">
                                        <p class="text-xs text-gray-400 line-clamp-3" id="preview-desc">الوصف يظهر هنا...</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Properties List -->
                        <div class="lg:col-span-1">
                            <div class="glass rounded-2xl p-6 h-full">
                                <h3 class="text-xl font-bold mb-6">العقارات الحالية</h3>
                                <div id="admin-properties-list" class="space-y-4 max-h-[65vh] overflow-y-auto hide-scrollbar pr-2">
                                    <div class="flex justify-center py-8">
                                        <div class="loader"></div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark-lighter border-t border-dark-border py-12 mt-12">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-8 h-8 gold-gradient rounded flex items-center justify-center">
                            <i class="fas fa-building text-dark text-sm"></i>
                        </div>
                        <span class="font-bold text-lg">PLAZA HOMES</span>
                    </div>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        وجهتك الأولى للعقارات الفاخرة في القاهرة. نقدم لك تجربة بحث سهلة وآمنة عن منزلك المثالي.
                    </p>
                </div>
                <div>
                    <h4 class="font-bold mb-4">روابط سريعة</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li><button onclick="showPage('home')" class="hover:text-gold transition-colors">الرئيسية</button></li>
                        <li><button onclick="showPage('properties')" class="hover:text-gold transition-colors">العقارات</button></li>
                        <li><button onclick="showPage('about')" class="hover:text-gold transition-colors">من نحن</button></li>
                        <li><button onclick="showPage('contact')" class="hover:text-gold transition-colors">تواصل معنا</button></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">المناطق</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li><button onclick="filterByLocation('مصر الجديدة')" class="hover:text-gold transition-colors">مصر الجديدة</button></li>
                        <li><button onclick="filterByLocation('مدينة نصر')" class="hover:text-gold transition-colors">مدينة نصر</button></li>
                        <li><button onclick="filterByLocation('المعادي')" class="hover:text-gold transition-colors">المعادي</button></li>
                        <li><button onclick="filterByLocation('التجمع الخامس')" class="hover:text-gold transition-colors">التجمع الخامس</button></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">تواصل معنا</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li><i class="fas fa-phone ml-2 text-gold"></i>+20 112 559 5673</li>
                        <li><i class="fab fa-whatsapp ml-2 text-gold"></i>+20 112 559 5673</li>
                        <li><i class="fas fa-map-marker-alt ml-2 text-gold"></i>زهراء مدينة نصر</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-dark-border pt-8 text-center text-sm text-gray-500">
                <p>© 2026 Plaza Homes Real Estate. جميع الحقوق محفوظة.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/201125595673" target="_blank" id="whatsapp-btn" class="fixed bottom-6 right-6 z-50 w-14 h-14 bg-green-500 rounded-full flex items-center justify-center shadow-lg hover:scale-110 transition-transform">
        <i class="fab fa-whatsapp text-white text-2xl"></i>
    </a>

    <!-- Hidden Admin Lock Button - INVISIBLE TO VISITORS -->
    <button onclick="showPage('admin-login')" class="admin-lock-btn" title="">
        <i class="fas fa-lock"></i>
    </button>

    <!-- FIREBASE CONFIGURATION - REPLACE WITH YOUR CREDENTIALS -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
        import { getFirestore, collection, addDoc, deleteDoc, doc, onSnapshot, query, orderBy, serverTimestamp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

        const firebaseConfig = {
            apiKey: "AIzaSyA7Ezer5AKWg9eKl4rP5xifKdJRBJ2j4OM",
            authDomain: "plaza-homes-38735.firebaseapp.com",
            projectId: "plaza-homes-38735",
            storageBucket: "plaza-homes-38735.firebasestorage.app",
            messagingSenderId: "945013713967",
            appId: "1:945013713967:web:6cfd67653541f17d2eeada",
            measurementId: "G-H0QNXWWF4S"
        };

        const app = initializeApp(firebaseConfig);
        const db = getFirestore(app);
        const propertiesCollection = collection(db, "properties");

        window.db = db;
        window.propertiesCollection = propertiesCollection;
        window.firebaseAddDoc = addDoc;
        window.firebaseDeleteDoc = deleteDoc;
        window.firebaseDoc = doc;
        window.firebaseOnSnapshot = onSnapshot;
        window.firebaseQuery = query;
        window.firebaseOrderBy = orderBy;
        window.firebaseServerTimestamp = serverTimestamp;
        

        window.unsubscribeProperties = null;

        function initRealtimeUpdates() {
            const q = query(propertiesCollection, orderBy("createdAt", "desc"));
            window.unsubscribeProperties = onSnapshot(q, (snapshot) => {
                const properties = [];
                snapshot.forEach((doc) => {
                    properties.push({ id: doc.id, ...doc.data() });
                });
                window.allProperties = properties;
                renderProperties(properties);
                renderFeaturedProperties(properties.slice(0, 3));
                renderAdminProperties(properties);
            }, (error) => {
                console.error("Firebase error:", error);
                showToast("خطأ في الاتصال بقاعدة البيانات");
            });
        }

        document.addEventListener('DOMContentLoaded', () => {
            initRealtimeUpdates();
            checkAdminSession();
        });
    </script>

    <script>
        window.allProperties = [];
        let currentFilter = {};
        

        function showPage(pageId) {
            const allSections = ['home', 'properties', 'property-detail', 'about', 'contact', 'admin-login', 'admin-panel'];
            allSections.forEach(id => {
                const el = document.getElementById(id);
                if (el) {
                    el.classList.remove('active-section');
                    el.classList.add('app-section');
                }
            });
            const target = document.getElementById(pageId);
            if (target) {
                target.classList.add('active-section');
                target.classList.remove('app-section');
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
            if (pageId === 'properties') applyFilters();
        }

        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function showToast(message) {
            const toast = document.getElementById('toast');
            toast.textContent = message;
            toast.classList.add('show');
            setTimeout(() => toast.classList.remove('show'), 3000);
        }

        function formatPrice(price) {
            if (!price) return '0 ج.م';
            return new Intl.NumberFormat('ar-EG').format(price) + ' ج.م';
        }

        function renderProperties(properties) {
            const grid = document.getElementById('properties-grid');
            const noResults = document.getElementById('no-results');

            if (properties.length === 0) {
                grid.innerHTML = '';
                noResults.classList.remove('hidden');
                return;
            }
            noResults.classList.add('hidden');

            grid.innerHTML = properties.map((prop, index) => `
                <div class="property-card glass rounded-2xl overflow-hidden card-hover cursor-pointer fade-in" style="animation-delay: ${index * 0.05}s" onclick="showPropertyDetail('${prop.id}')">
                    <div class="relative h-64 overflow-hidden">
                        <img src="${prop.imageUrl || 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=600&q=80'}" 
                             class="property-image w-full h-full object-cover" alt="${prop.title}" loading="lazy">
                        <div class="absolute top-4 right-4 gold-gradient text-dark px-3 py-1 rounded-full text-xs font-bold">${prop.type || 'شقة'}</div>
                        <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-dark to-transparent h-20"></div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg line-clamp-1">${prop.title}</h3>
                            <span class="text-gold font-bold text-sm" dir="ltr">${formatPrice(prop.price)}</span>
                        </div>
                        <p class="text-gray-400 text-sm mb-4"><i class="fas fa-map-marker-alt ml-1 text-gold"></i>${prop.location}</p>
                        <div class="flex items-center gap-4 text-sm text-gray-400 border-t border-dark-border pt-4">
                            <span><i class="fas fa-bed ml-1 text-gold"></i>${prop.rooms} غرف</span>
                            <span><i class="fas fa-bath ml-1 text-gold"></i>${prop.bathrooms} حمام</span>
                            <span><i class="fas fa-ruler-combined ml-1 text-gold"></i>${prop.area || '-'} م²</span>
                        </div>
                        <div class="mt-4 pt-3 border-t border-dark-border flex justify-between items-center">
                            <span class="text-xs text-gray-500">كود: ${prop.code}</span>
                            <button class="text-gold text-sm hover:underline">التفاصيل <i class="fas fa-arrow-left mr-1"></i></button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function renderFeaturedProperties(properties) {
            const container = document.getElementById('featured-properties');
            if (!properties || properties.length === 0) {
                container.innerHTML = '<div class="col-span-full text-center text-gray-500 py-8">لا توجد عقارات مميزة حالياً</div>';
                return;
            }
            container.innerHTML = properties.map((prop, index) => `
                <div class="property-card glass rounded-2xl overflow-hidden card-hover cursor-pointer fade-in" style="animation-delay: ${index * 0.1}s" onclick="showPropertyDetail('${prop.id}')">
                    <div class="relative h-72 overflow-hidden">
                        <img src="${prop.imageUrl || 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=600&q=80'}" 
                             class="property-image w-full h-full object-cover" alt="${prop.title}" loading="lazy">
                        <div class="absolute top-4 right-4 bg-red-500 text-white px-3 py-1 rounded-full text-xs font-bold">مميز</div>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-xl mb-2">${prop.title}</h3>
                        <p class="text-gray-400 text-sm mb-3"><i class="fas fa-map-marker-alt ml-1 text-gold"></i>${prop.location}</p>
                        <div class="flex justify-between items-center">
                            <span class="text-gold font-bold text-lg" dir="ltr">${formatPrice(prop.price)}</span>
                            <span class="text-sm text-gray-400">${prop.rooms} غرف | ${prop.area || '-'} م²</span>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function renderAdminProperties(properties) {
            const list = document.getElementById('admin-properties-list');
            if (!properties || properties.length === 0) {
                list.innerHTML = '<div class="text-center text-gray-500 py-8">لا توجد عقارات مسجلة</div>';
                return;
            }
            list.innerHTML = properties.map(prop => `
                <div class="glass rounded-xl p-4 flex gap-4 items-center">
                    <img src="${prop.imageUrl || 'https://via.placeholder.com/80'}" class="w-20 h-20 rounded-lg object-cover flex-shrink-0">
                    <div class="flex-1 min-w-0">
                        <h4 class="font-bold truncate">${prop.title}</h4>
                        <p class="text-xs text-gray-400">${prop.location} | كود: ${prop.code}</p>
                        <p class="text-gold text-sm font-bold mt-1" dir="ltr">${formatPrice(prop.price)}</p>
                    </div>
                    <button onclick="deleteProperty('${prop.id}')" class="w-10 h-10 rounded-full bg-red-500/10 text-red-400 hover:bg-red-500 hover:text-white transition-all flex items-center justify-center flex-shrink-0">
                        <i class="fas fa-trash-alt"></i>
                    </button>
                </div>
            `).join('');
        }

        function applyFilters() {
            const location = document.getElementById('filter-location').value;
            const type = document.getElementById('filter-type').value;
            const rooms = document.getElementById('filter-rooms').value;
            const priceRange = document.getElementById('filter-price').value;
            const searchQuery = document.getElementById('search-input') ? document.getElementById('search-input').value.toLowerCase() : '';

            let filtered = [...window.allProperties];

            if (searchQuery) {
                filtered = filtered.filter(p => 
                    (p.title && p.title.toLowerCase().includes(searchQuery)) ||
                    (p.location && p.location.toLowerCase().includes(searchQuery)) ||
                    (p.code && p.code.toLowerCase().includes(searchQuery)) ||
                    (p.type && p.type.toLowerCase().includes(searchQuery))
                );
            }
            if (location) {
                filtered = filtered.filter(p => p.location && p.location.includes(location.split(' - ')[1] || location));
            }
            if (type) filtered = filtered.filter(p => p.type === type);
            if (rooms) filtered = filtered.filter(p => p.rooms == rooms);
            if (priceRange) {
                const [min, max] = priceRange.split('-').map(Number);
                filtered = filtered.filter(p => p.price >= min && p.price <= max);
            }

            renderProperties(filtered);
        }

        function filterByLocation(loc) {
            showPage('properties');
            document.getElementById('filter-location').value = loc;
            applyFilters();
        }

        function showPropertyDetail(id) {
            const prop = window.allProperties.find(p => p.id === id);
            if (!prop) return;

            const content = document.getElementById('property-detail-content');
            const whatsappMsg = encodeURIComponent(`مرحباً Plaza Homes، أنا مهتم بالعقار: ${prop.title} (كود: ${prop.code})`);

            content.innerHTML = `
                <div class="grid lg:grid-cols-2 gap-8">
                    <div class="relative rounded-2xl overflow-hidden h-[400px] lg:h-[600px]">
                        <img src="${prop.imageUrl || 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=1200&q=80'}" 
                             class="w-full h-full object-cover" alt="${prop.title}">
                        <div class="absolute top-4 right-4 gold-gradient text-dark px-4 py-2 rounded-full font-bold">${prop.type || 'شقة'}</div>
                    </div>
                    <div>
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h1 class="text-3xl font-bold mb-2">${prop.title}</h1>
                                <p class="text-gray-400"><i class="fas fa-map-marker-alt ml-2 text-gold"></i>${prop.location}</p>
                            </div>
                            <div class="text-left">
                                <div class="text-3xl font-bold gold-text" dir="ltr">${formatPrice(prop.price)}</div>
                                <div class="text-xs text-gray-500 mt-1">كود العقار: ${prop.code}</div>
                            </div>
                        </div>
                        <div class="w-full h-px bg-dark-border my-6"></div>
                        <div class="grid grid-cols-3 gap-4 mb-8">
                            <div class="glass rounded-xl p-4 text-center">
                                <i class="fas fa-bed text-gold text-2xl mb-2"></i>
                                <div class="font-bold text-xl">${prop.rooms}</div>
                                <div class="text-xs text-gray-400">غرف النوم</div>
                            </div>
                            <div class="glass rounded-xl p-4 text-center">
                                <i class="fas fa-bath text-gold text-2xl mb-2"></i>
                                <div class="font-bold text-xl">${prop.bathrooms}</div>
                                <div class="text-xs text-gray-400">الحمامات</div>
                            </div>
                            <div class="glass rounded-xl p-4 text-center">
                                <i class="fas fa-ruler-combined text-gold text-2xl mb-2"></i>
                                <div class="font-bold text-xl">${prop.area || '-'}</div>
                                <div class="text-xs text-gray-400">المساحة (م²)</div>
                            </div>
                        </div>
                        <div class="glass rounded-xl p-6 mb-8">
                            <h3 class="font-bold text-xl mb-4">وصف العقار</h3>
                            <p class="text-gray-300 leading-relaxed">${prop.description || 'لا يوجد وصف مفصل لهذا العقار.'}</p>
                        </div>
                        <div class="flex gap-4">
                            <a href="https://wa.me/201125595673?text=${whatsappMsg}" target="_blank" class="btn-gold flex-1 py-4 rounded-xl text-center text-base">
                                <i class="fab fa-whatsapp ml-2"></i>تواصل عبر واتساب
                            </a>
                            <button onclick="showPage('properties')" class="px-6 py-4 border border-dark-border rounded-xl hover:border-gold transition-colors">
                                <i class="fas fa-arrow-right"></i>
                            </button>
                        </div>
                    </div>
                </div>
            `;
            showPage('property-detail');
        }

        // Admin Functions
        function handleAdminLogin() {
            const user = document.getElementById('admin-user').value;
            const pass = document.getElementById('admin-pass').value;
            if (user === 'admin' && pass === 'R3A-2026') {
                localStorage.setItem('plaza_admin', 'true');
                showPage('admin-panel');
                showToast('تم تسجيل الدخول بنجاح');
            } else {
                showToast('بيانات الدخول غير صحيحة');
            }
        }

        function adminLogout() {
            localStorage.removeItem('plaza_admin');
            showPage('home');
            showToast('تم تسجيل الخروج');
        }

        function checkAdminSession() {
            if (localStorage.getItem('plaza_admin') === 'true') {
                // Session valid
            }
        }

        // Live Preview Functions
        function updatePreview() {
            const code = document.getElementById('prop-code').value || '---';
            const title = document.getElementById('prop-title').value || 'عنوان العقار';
            const location = document.getElementById('prop-location').value || 'المنطقة';
            const price = document.getElementById('prop-price').value || '0';
            const area = document.getElementById('prop-area').value || '-';
            const rooms = document.getElementById('prop-rooms').value || '0';
            const bathrooms = document.getElementById('prop-bathrooms').value || '0';
            const type = document.getElementById('prop-type').value || 'شقة';
            const desc = document.getElementById('prop-desc').value || 'الوصف يظهر هنا...';
            const imageUrl = document.getElementById('prop-image-url').value;

            document.getElementById('preview-code').textContent = code;
            document.getElementById('preview-title').textContent = title;
            document.getElementById('preview-location').textContent = location;
            document.getElementById('preview-price').textContent = formatPrice(price);
            document.getElementById('preview-area').textContent = area;
            document.getElementById('preview-rooms').textContent = rooms;
            document.getElementById('preview-bathrooms').textContent = bathrooms;
            document.getElementById('preview-type').textContent = type;
            document.getElementById('preview-desc').textContent = desc;

            if (imageUrl) {
                document.getElementById('preview-image').src = imageUrl;
            } else {
                document.getElementById('preview-image').src = 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=600&q=80';
            }
        }

        

        async function handleAddProperty() {
            const submitBtn = document.getElementById('submit-btn');
            submitBtn.disabled = true;
            submitBtn.innerHTML = '<i class="fas fa-spinner fa-spin ml-2"></i>جاري الإضافة...';

            try {
                if (!window.db || !window.propertiesCollection) {
                    throw new Error('Firebase not initialized. Please check your configuration.');
                }

                const imageUrl = document.getElementById('prop-image-url').value.trim();

                if (!imageUrl) {
                    throw new Error('يرجى إدخال رابط الصورة');
                }

                const propertyData = {
                    code: document.getElementById('prop-code').value.trim(),
                    title: document.getElementById('prop-title').value.trim(),
                    location: document.getElementById('prop-location').value,
                    price: Number(document.getElementById('prop-price').value) || 0,
                    area: Number(document.getElementById('prop-area').value) || 0,
                    rooms: Number(document.getElementById('prop-rooms').value) || 0,
                    bathrooms: Number(document.getElementById('prop-bathrooms').value) || 0,
                    type: document.getElementById('prop-type').value,
                    imageUrl: imageUrl,
                    description: document.getElementById('prop-desc').value.trim(),
                    createdAt: window.firebaseServerTimestamp()
                };

                console.log('Adding property:', propertyData);
                await window.firebaseAddDoc(window.propertiesCollection, propertyData);

                document.getElementById('add-property-form').reset();
                updatePreview();
                showToast('✅ تم إضافة العقار بنجاح');
            } catch (error) {
                console.error('Add property error:', error);
                showToast('❌ خطأ: ' + error.message);
            } finally {
                submitBtn.disabled = false;
                submitBtn.innerHTML = '<i class="fas fa-plus ml-2"></i>إضافة العقار';
            }
        }

        async function deleteProperty(id) {
            if (!confirm('هل أنت متأكد من حذف هذا العقار؟')) return;
            try {
                await window.firebaseDeleteDoc(window.firebaseDoc(window.db, 'properties', id));
                showToast('تم حذف العقار');
            } catch (error) {
                showToast('خطأ في الحذف');
            }
        }

        window.addEventListener('scroll', () => {
            const nav = document.getElementById('navbar');
            if (window.scrollY > 50) {
                nav.classList.add('shadow-lg');
                nav.style.background = 'rgba(10,10,10,0.95)';
            } else {
                nav.classList.remove('shadow-lg');
                nav.style.background = 'rgba(26,26,26,0.85)';
            }
        });
    </script>
</body>
</html>
