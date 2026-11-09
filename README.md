<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Minh Toàn Fruits - Trái Cây Nhập Khẩu & Giỏ Quà Tặng Đà Nẵng | minhtoanfruits.com</title>
    <meta name="description" content="Minh Toàn Fruits (minhtoanfruits.com) - Chuyên cung cấp Trái Cây Nhập Khẩu cao cấp, Giỏ Quà Tặng Trái Cây, Khay Hộp Biếu Tặng, Mâm Quả Đi Lễ tại 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng. Hotline: 0898.174.555">
    
    <!-- Open Graph / Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://minhtoanfruits.com/">
    <meta property="og:site_name" content="minhtoanfruits.com">
    <meta property="og:title" content="Minh Toàn Fruits - Hệ Thống Trái Cây Nhập Khẩu & Giỏ Quà Tặng Cao Cấp">
    <meta property="og:description" content="Trái cây nhập khẩu tươi ngon chuẩn vị, Giỏ quà trái cây sang trọng. Địa chỉ: 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng. Hotline/Zalo: 0898.174.555">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w1200">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Minh Toàn Fruits - minhtoanfruits.com">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w200">

    <!-- Tailwind CSS & Font Awesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f1f8f3',
                            100: '#ddeee2',
                            500: '#2e7d32',
                            600: '#1b5e20',
                            700: '#144718',
                            800: '#0d3310',
                            accent: '#e65100',
                            gold: '#f59e0b'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8faf8;
            color: #222222;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng không rớt dòng trong từng mục */
        .nav-cat-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
        }
        .nav-cat-link:hover, .nav-cat-link.active {
            background-color: #ffffff;
            color: #1b5e20;
        }

        /* Dropdown danh mục con trên máy tính chuẩn F5 Fruit Shop */
        .nav-cat-item {
            position: relative;
        }
        .nav-cat-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            color: #1f2937;
            border-radius: 8px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.14);
            border: 1px solid #e5e7eb;
            padding: 6px 0;
            z-index: 60;
        }
        .nav-cat-item:hover .nav-cat-dropdown {
            display: block;
        }

        /* Nút danh mục trang chủ nhỏ gọn */
        .home-cat-pill {
            white-space: nowrap;
            font-size: 11.5px;
            line-height: 1.3;
            padding: 5px 11px;
            border-radius: 9999px;
            transition: all 0.2s ease;
        }

        /* Tên sản phẩm: hiển thị đầy đủ, tự xuống dòng tự nhiên, không bị cắt mất chữ */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
            min-height: 2.75em;
            display: block;
        }

        /* Nhãn giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: linear-gradient(135deg, #d32f2f 0%, #e65100 100%);
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 9999px;
            box-shadow: 0 2px 6px rgba(211, 47, 47, 0.35);
            letter-spacing: -0.2px;
        }

        /* Hiệu ứng mượt cho khung sản phẩm Flatsome */
        .flatsome-product-box {
            transition: transform 0.22s ease, box-shadow 0.22s ease;
        }
        .flatsome-product-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 24px -6px rgba(27, 94, 32, 0.16);
        }

        /* Ẩn thanh cuộn ngang cho danh mục điện thoại */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng rung nhẹ cho nút nổi Hotline/Zalo */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(46, 125, 50, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(46, 125, 50, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(46, 125, 50, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-[#f7faf7] text-gray-800 antialiased selection:bg-brand-600 selection:text-white">

    <!-- ==================== HEADER (CHUẨN FLATSOME - KHÔNG ĐỂ NÚT GỌI NGAY TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40 w-full">
        <!-- Top Bar mỏng gọn -->
        <div class="bg-brand-700 text-white text-[11px] sm:text-xs py-1.5 border-b border-brand-800">
            <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-amber-300 shrink-0"></i>
                    <span class="truncate">25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng</span>
                </div>
                <div class="hidden sm:flex items-center gap-4 text-[11.5px] shrink-0">
                    <span><i class="fa-solid fa-globe text-amber-300 mr-1"></i>minhtoanfruits.com</span>
                    <span><i class="fa-solid fa-clock text-amber-300 mr-1"></i>Mở cửa: 07:00 - 21:30</span>
                    <span><i class="fa-solid fa-phone-volume text-amber-300 mr-1"></i>Hotline: <strong>0898.174.555</strong></span>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo nhỏ gọn + Tìm kiếm + Giỏ hàng (Không để nút gọi ngay) -->
        <div class="container-1500 py-2.5 md:py-3">
            <div class="flex items-center justify-between gap-2.5 md:gap-6">
                <!-- Nút mở menu trên điện thoại -->
                <button onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg text-brand-700 hover:bg-brand-50 border border-brand-100 shrink-0" aria-label="Menu danh mục">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-full overflow-hidden border border-brand-100 bg-white flex items-center justify-center p-0.5 shadow-sm shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5"
                             onerror="if(!this.dataset.fb1){this.dataset.fb1=1;this.src='https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w400';}else{this.src='https://placehold.co/120x120/1b5e20/ffffff?text=MT+Fruits';}"
                             alt="Minh Toàn Fruits Logo"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base md:text-lg font-extrabold text-brand-700 tracking-tight">MINH TOÀN FRUITS</span>
                        <span class="block text-[10px] sm:text-[11px] text-gray-500 font-medium">Trái Cây Nhập Khẩu Cao Cấp</span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm -->
                <div class="hidden md:flex flex-1 max-w-xl mx-auto">
                    <div class="relative w-full">
                        <input id="desktopSearchInput" type="text" oninput="handleSearch(this.value)"
                               placeholder="Tìm táo Envy, nho mẫu đơn, cherry Mỹ, giỏ quà trái cây..."
                               class="w-full pl-4 pr-10 py-2 text-xs md:text-sm bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand-600 focus:bg-white transition">
                        <button onclick="handleSearch(document.getElementById('desktopSearchInput').value)" class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full bg-brand-600 text-white flex items-center justify-center hover:bg-brand-700">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Khu vực liên hệ chữ nhẹ nhàng & Giỏ hàng (Không dùng nút gọi ngay tránh tràn viền) -->
                <div class="flex items-center gap-2 sm:gap-3 shrink-0">
                    <a href="#form-bao-gia" class="hidden xl:flex items-center gap-1.5 text-xs font-semibold text-brand-700 hover:text-brand-800 px-2.5 py-1.5 rounded-lg bg-brand-50 border border-brand-100">
                        <i class="fa-solid fa-file-signature text-brand-600"></i>
                        <span>Nhận Báo Giá Sỉ/Lẻ</span>
                    </a>
                    <button onclick="openCartModal()" class="relative inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 text-xs font-semibold transition">
                        <i class="fa-solid fa-basket-shopping text-brand-600 text-sm"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="bg-brand-accent text-white text-[10px] font-bold px-1.5 py-0.5 rounded-full">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="mt-2 md:hidden">
                <div class="relative w-full">
                    <input id="mobileSearchInput" type="text" oninput="handleSearch(this.value)"
                           placeholder="Tìm kiếm trái cây nhập khẩu, giỏ quà tặng..."
                           class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-gray-50 border border-gray-200 rounded-full focus:outline-none focus:border-brand-600">
                    <i class="fa-solid fa-magnifying-glass text-gray-400 text-xs absolute right-3 top-1/2 -translate-y-1/2"></i>
                </div>
            </div>
        </div>

        <!-- Thanh Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, tuyệt đối không xuống dòng tên danh mục, kèm danh mục con từ f5fruitshop.vn -->
        <nav class="hidden lg:block bg-brand-600 text-white border-t border-brand-700">
            <div class="container-1500 py-1">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 gap-y-1">
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('all', this)" class="nav-cat-link active">
                            <i class="fa-solid fa-house text-[11px]"></i>
                            <span>Trang chủ</span>
                        </a>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây nhập khẩu', this)" class="nav-cat-link">
                            <i class="fa-solid fa-apple-whole text-[11px] text-amber-300"></i>
                            <span>Trái cây nhập khẩu</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterSubCategory('Trái cây nhập khẩu', 'Táo')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Táo nhập khẩu (Envy, Dazzle, Rockit)</a>
                            <a href="#san-pham-trang-chu" onclick="filterSubCategory('Trái cây nhập khẩu', 'Nho')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Nho nhập khẩu (Autumn Crisp, Úc, Mỹ)</a>
                            <a href="#san-pham-trang-chu" onclick="filterSubCategory('Trái cây nhập khẩu', 'Cherry')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Cherry Mỹ - Úc</a>
                            <a href="#san-pham-trang-chu" onclick="filterSubCategory('Trái cây nhập khẩu', 'Kiwi')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Kiwi vàng & đỏ New Zealand</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây nhập khẩu')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Lê • Cam - Quýt • Dưa lưới • Việt Quất</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây', this)" class="nav-cat-link">
                            <i class="fa-solid fa-gift text-[11px] text-amber-300"></i>
                            <span>Giỏ quà tặng trái cây</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Giỏ từ 400k - 500k</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Giỏ từ 500k - 800k</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Giỏ từ 800k - 1 triệu</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Giỏ từ 1 triệu - 1.5 triệu</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Giỏ từ 1.5 triệu - 2 triệu</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng', this)" class="nav-cat-link">
                            <i class="fa-solid fa-box-open text-[11px] text-amber-300"></i>
                            <span>Khay - Hộp trái cây biếu tặng</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Khay hộp từ 200k - 300k</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Khay hộp giá từ 300k - 500k</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Khay hộp từ 500k - 700k</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Khay hộp từ 700k - 1 triệu</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Mâm trái cây đi lễ - thắp hương', this)" class="nav-cat-link">
                            <i class="fa-solid fa-spa text-[11px] text-amber-300"></i>
                            <span>Mâm trái cây đi lễ - thắp hương</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Mâm quả đi lễ</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Combo đĩa quả thắp hương</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây Việt Nam', this)" class="nav-cat-link">
                            <i class="fa-solid fa-leaf text-[11px] text-amber-300"></i>
                            <span>Trái cây Việt Nam</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây Việt Nam')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Dưa hấu</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây Việt Nam')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Xoài Cát Chu & Đặc sản mùa vụ</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Thực phẩm đồ khô', this)" class="nav-cat-link">
                            <i class="fa-solid fa-seedling text-[11px] text-amber-300"></i>
                            <span>Thực phẩm đồ khô</span>
                            <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-cat-dropdown">
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Thực phẩm đồ khô')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Hạt dinh dưỡng & Thực phẩm sức khỏe</a>
                            <a href="#san-pham-trang-chu" onclick="filterCategory('Thực phẩm đồ khô')" class="block px-3.5 py-1.5 text-xs hover:bg-brand-50 hover:text-brand-700 font-medium">Bánh kẹo & Sữa nhập khẩu</a>
                        </div>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#form-bao-gia" class="nav-cat-link">
                            <i class="fa-solid fa-file-invoice-dollar text-[11px] text-amber-300"></i>
                            <span>Yêu cầu & Báo giá</span>
                        </a>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#bai-viet-trang-chu" class="nav-cat-link">
                            <i class="fa-solid fa-newspaper text-[11px] text-amber-300"></i>
                            <span>Blog</span>
                        </a>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#doi-tac" class="nav-cat-link">
                            <i class="fa-solid fa-handshake text-[11px] text-amber-300"></i>
                            <span>Đối tác</span>
                        </a>
                    </li>
                    <li class="nav-cat-item">
                        <a href="#lien-he-bando" class="nav-cat-link">
                            <i class="fa-solid fa-map-location-dot text-[11px] text-amber-300"></i>
                            <span>Liên hệ</span>
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh Danh Mục Nhỏ Gọn Trên Điện Thoại (Cuộn ngang mượt, chữ nhỏ gọn đẹp mắt) -->
        <div class="lg:hidden bg-brand-600 text-white border-t border-brand-700">
            <div class="container-1500 py-1.5 flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <button onclick="filterCategory('all')" class="shrink-0 whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-white text-brand-700">
                    Tất cả
                </button>
                <button onclick="filterCategory('Trái cây nhập khẩu')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Trái cây nhập khẩu
                </button>
                <button onclick="filterCategory('Giỏ quà tặng trái cây')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Giỏ quà tặng trái cây
                </button>
                <button onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Khay - Hộp trái cây biếu tặng
                </button>
                <button onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Mâm trái cây đi lễ - thắp hương
                </button>
                <button onclick="filterCategory('Trái cây Việt Nam')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Trái cây Việt Nam
                </button>
                <button onclick="filterCategory('Thực phẩm đồ khô')" class="shrink-0 whitespace-nowrap text-[11px] font-medium px-2.5 py-1 rounded bg-brand-700/80 hover:bg-white hover:text-brand-700">
                    Thực phẩm đồ khô
                </button>
            </div>
        </div>
    </header>

    <!-- Drawer Menu Danh Mục cho Điện Thoại -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/50 backdrop-blur-xs"></div>
        <div class="relative w-[280px] max-w-[82vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
            <div>
                <div class="p-3.5 bg-brand-700 text-white flex items-center justify-between">
                    <div class="flex items-center gap-2">
                        <img src="https://lh3.googleusercontent.com/d/1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w200'"
                             alt="Logo Minh Toàn Fruits"
                             class="w-8 h-8 rounded-full bg-white p-0.5 object-contain shrink-0">
                        <span class="font-bold text-xs tracking-wide uppercase">Danh Mục Sản Phẩm</span>
                    </div>
                    <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-white/15 flex items-center justify-center text-white">
                        <i class="fa-solid fa-xmark text-sm"></i>
                    </button>
                </div>

                <ul class="divide-y divide-gray-100 text-xs font-semibold text-gray-700">
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('all'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-house text-brand-600 w-5"></i>Trang chủ</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây nhập khẩu'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-apple-whole text-brand-600 w-5"></i>Trái cây nhập khẩu</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-gift text-brand-600 w-5"></i>Giỏ quà tặng trái cây</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-box-open text-brand-600 w-5"></i>Khay - Hộp trái cây biếu tặng</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Mâm trái cây đi lễ - thắp hương'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-spa text-brand-600 w-5"></i>Mâm trái cây đi lễ - thắp hương</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây Việt Nam'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-leaf text-brand-600 w-5"></i>Trái cây Việt Nam</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-trang-chu" onclick="filterCategory('Thực phẩm đồ khô'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-seedling text-brand-600 w-5"></i>Thực phẩm đồ khô</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-file-invoice-dollar text-brand-600 w-5"></i>Yêu cầu & Báo giá</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#bai-viet-trang-chu" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-newspaper text-brand-600 w-5"></i>Tin tức & Blog</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he-bando" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 hover:text-brand-700">
                            <span><i class="fa-solid fa-map-location-dot text-brand-600 w-5"></i>Bản đồ & Fanpage</span>
                            <i class="fa-solid fa-angle-right text-[10px] text-gray-400"></i>
                        </a>
                    </li>
                </ul>
            </div>

            <div class="p-4 bg-brand-50 border-t border-brand-100 text-xs space-y-1.5">
                <p class="font-bold text-brand-700">MINH TOÀN FRUITS ĐÀ NẴNG</p>
                <p class="text-gray-600 text-[11px]"><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>25 Cẩm Bắc 3, P. Cẩm Lệ, TP Đà Nẵng</p>
                <p class="text-gray-600 text-[11px]"><i class="fa-solid fa-phone text-brand-600 mr-1"></i>Hotline/Zalo: <strong>0898.174.555</strong></p>
            </div>
        </div>
    </div>

    <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU (THIẾT KẾ RIÊNG CHO ĐIỆN THOẠI & MÁY TÍNH) ==================== -->
    <section class="pt-3 pb-1">
        <div class="container-1500">
            <div class="relative w-full rounded-xl overflow-hidden shadow-sm border border-brand-100 bg-brand-800">

                <!-- SLIDE 1 -->
                <div class="banner-slide block transition-opacity duration-500" data-slide="0">
                    <!-- Thiết kế Banner MÁY TÍNH Slide 1 (Kích thước cố định 340px bằng Slide 2, chữ nhỏ gọn nằm hết trong ảnh banner) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[340px] bg-gradient-to-r from-[#0f3814] via-[#1b5e20] to-[#2e7d32] px-10 lg:px-14 overflow-hidden">
                        <div class="col-span-7 text-white pr-6 space-y-2.5">
                            <p class="text-xs font-bold text-amber-300 uppercase tracking-wider">
                                MINH TOÀN FRUITS • MINHTOANFRUITS.COM
                            </p>
                            <h2 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white">
                                HỆ THỐNG TRÁI CÂY NHẬP KHẨU CAO CẤP<br>
                                <span class="text-amber-300">TƯƠI NGON CHUẨN VỊ MỖI NGÀY TẠI ĐÀ NẴNG</span>
                            </h2>
                            <p class="text-xs lg:text-[13px] text-emerald-100 max-w-xl leading-relaxed">
                                Chuyên Táo Envy, Nho Xanh Autumn Crisp, Kiwi Vàng New Zealand, Cherry Mỹ - Úc chính ngạch. Kiểm hàng trước khi thanh toán, đổi trả miễn phí trong 24h.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#san-pham-trang-chu" class="bg-amber-400 hover:bg-amber-300 text-gray-900 font-bold px-4 py-2 rounded-lg shadow transition">
                                    Xem Sản Phẩm Ngay
                                </a>
                                <span class="text-emerald-100 font-medium">
                                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>25 Cẩm Bắc 3, P. Cẩm Lệ, TP Đà Nẵng • <strong>0898.174.555</strong>
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center h-full py-4">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[380px]">
                                <div class="bg-white/10 p-1.5 rounded-xl border border-white/20">
                                    <img src="https://lh3.googleusercontent.com/d/16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf&sz=w600'"
                                         alt="Trái cây nhập khẩu Minh Toàn Fruits"
                                         class="w-full h-36 object-cover rounded-lg">
                                </div>
                                <div class="bg-white/10 p-1.5 rounded-xl border border-white/20">
                                    <img src="https://lh3.googleusercontent.com/d/1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h&sz=w600'"
                                         alt="Nho nhập khẩu tươi ngon"
                                         class="w-full h-36 object-cover rounded-lg">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Thiết kế Banner ĐIỆN THOẠI Slide 1 (Thiết kế riêng khác với máy tính, cao cố định 185px bằng Slide 2, chữ nhỏ gọn nằm hết trong ảnh không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[185px] bg-gradient-to-br from-[#0f3814] via-[#1b5e20] to-[#2e7d32] px-3 py-2.5 overflow-hidden">
                        <div class="flex items-center justify-between text-[9.5px] text-amber-300 font-bold border-b border-white/15 pb-1">
                            <span>MINHTOANFRUITS.COM</span>
                            <span><i class="fa-solid fa-phone mr-1"></i>0898.174.555</span>
                        </div>
                        <div class="grid grid-cols-12 items-center gap-2 my-auto">
                            <div class="col-span-7 text-white space-y-1 pr-1">
                                <h2 class="text-[11.5px] font-extrabold leading-tight text-white">
                                    TRÁI CÂY NHẬP KHẨU TƯƠI NGON CHUẨN VỊ
                                </h2>
                                <p class="text-[9.5px] text-emerald-100 leading-snug">
                                    Táo Envy, Nho Autumn Crisp, Kiwi Zespri, Cherry Mỹ - Úc chính ngạch.
                                </p>
                                <p class="text-[9px] text-amber-200 font-semibold leading-tight">
                                    ĐC: 25 Cẩm Bắc 3, Cẩm Lệ, Đà Nẵng
                                </p>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-1">
                                <div class="h-[74px] rounded-lg overflow-hidden border border-amber-300/70 bg-white p-0.5">
                                    <img src="https://lh3.googleusercontent.com/d/16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf&sz=w400'"
                                         alt="Trái cây nhập khẩu"
                                         class="w-full h-full object-cover rounded">
                                </div>
                                <div class="h-[74px] rounded-lg overflow-hidden border border-amber-300/70 bg-white p-0.5">
                                    <img src="https://lh3.googleusercontent.com/d/1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h&sz=w400'"
                                         alt="Nho nhập khẩu"
                                         class="w-full h-full object-cover rounded">
                                </div>
                            </div>
                        </div>
                        <div class="text-[9px] text-emerald-100 flex items-center justify-between border-t border-white/15 pt-1">
                            <span>✓ Kiểm hàng trước thanh toán</span>
                            <span>✓ Đổi trả trong 24h</span>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 -->
                <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
                    <!-- Thiết kế Banner MÁY TÍNH Slide 2 (Kích thước cố định 340px bằng Slide 1, chữ nhỏ gọn nằm trọn bên trong) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[340px] bg-gradient-to-r from-[#1b4d20] via-[#256629] to-[#143d18] px-10 lg:px-14 overflow-hidden">
                        <div class="col-span-7 text-white pr-6 space-y-2.5">
                            <p class="text-xs font-bold text-amber-300 uppercase tracking-wider">
                                GIỎ QUÀ TRÁI CÂY • KHAY QUÀ BIẾU • MÂM QUẢ DÂNG LỄ
                            </p>
                            <h2 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white">
                                THIẾT KẾ GIỎ QUÀ TRÁI CÂY & HOA TƯƠI<br>
                                <span class="text-amber-300">SANG TRỌNG - TINH TẾ - ĐẲNG CẤP</span>
                            </h2>
                            <p class="text-xs lg:text-[13px] text-emerald-100 max-w-xl leading-relaxed">
                                Nhận đóng giỏ quà tặng doanh nghiệp, khay quà biếu đối tác, mâm ngũ quả đi lễ - thắp hương theo ngân sách từ 200k - 2 triệu. Miễn phí thiệp chúc & biển tên.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#form-bao-gia" class="bg-amber-400 hover:bg-amber-300 text-gray-900 font-bold px-4 py-2 rounded-lg shadow transition">
                                    Đặt Giỏ Quà Theo Yêu Cầu
                                </a>
                                <span class="text-emerald-100 font-medium">
                                    <i class="fa-solid fa-truck-fast text-amber-300 mr-1"></i>Giao nhanh tại Đà Nẵng • <strong>0898.174.555</strong>
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center h-full py-4">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[380px]">
                                <div class="bg-white/10 p-1.5 rounded-xl border border-white/20">
                                    <img src="https://lh3.googleusercontent.com/d/1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY&sz=w600'"
                                         alt="Giỏ quà trái cây cao cấp"
                                         class="w-full h-36 object-cover rounded-lg">
                                </div>
                                <div class="bg-white/10 p-1.5 rounded-xl border border-white/20">
                                    <img src="https://lh3.googleusercontent.com/d/1-ogygf0fWyqHatKILLe94RlkIuNgo9BN"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1-ogygf0fWyqHatKILLe94RlkIuNgo9BN&sz=w600'"
                                         alt="Mâm quả trái cây đi lễ"
                                         class="w-full h-36 object-cover rounded-lg">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Thiết kế Banner ĐIỆN THOẠI Slide 2 (Thiết kế riêng khác với máy tính, cao cố định 185px bằng Slide 1, chữ nhỏ gọn nằm hết trong ảnh không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[185px] bg-gradient-to-br from-[#194a1e] via-[#256629] to-[#113814] px-3 py-2.5 overflow-hidden">
                        <div class="flex items-center justify-between text-[9.5px] text-amber-300 font-bold border-b border-white/15 pb-1">
                            <span>GIỎ QUÀ & MÂM QUẢ ĐI LỄ</span>
                            <span><i class="fa-solid fa-gift mr-1"></i>Tặng kèm thiệp & nơ</span>
                        </div>
                        <div class="grid grid-cols-12 items-center gap-2 my-auto">
                            <div class="col-span-7 text-white space-y-1 pr-1">
                                <h2 class="text-[11.5px] font-extrabold leading-tight text-white">
                                    GIỎ QUÀ TRÁI CÂY & KHAY BIẾU TẶNG SANG TRỌNG
                                </h2>
                                <p class="text-[9.5px] text-emerald-100 leading-snug">
                                    Thiết kế theo ngân sách từ 200k - 2 triệu. Giao tận nơi tại Đà Nẵng.
                                </p>
                                <p class="text-[9px] text-amber-200 font-semibold leading-tight">
                                    Hotline/Zalo: 0898.174.555
                                </p>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-1">
                                <div class="h-[74px] rounded-lg overflow-hidden border border-amber-300/70 bg-white p-0.5">
                                    <img src="https://lh3.googleusercontent.com/d/13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh&sz=w400'"
                                         alt="Giỏ quà trái cây 1"
                                         class="w-full h-full object-cover rounded">
                                </div>
                                <div class="h-[74px] rounded-lg overflow-hidden border border-amber-300/70 bg-white p-0.5">
                                    <img src="https://lh3.googleusercontent.com/d/1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY"
                                         onerror="this.src='https://drive.google.com/thumbnail?id=1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY&sz=w400'"
                                         alt="Giỏ quà trái cây 2"
                                         class="w-full h-full object-cover rounded">
                                </div>
                            </div>
                        </div>
                        <div class="text-[9px] text-emerald-100 flex items-center justify-between border-t border-white/15 pt-1">
                            <span>✓ Mẫu mã sang trọng</span>
                            <span>✓ Xuất hóa đơn VAT</span>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng & chấm tròn 2 Banner -->
                <button onclick="changeBanner(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition z-10" aria-label="Banner trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeBanner(1)" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition z-10" aria-label="Banner tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                    <button onclick="goToBanner(0)" class="banner-dot w-6 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToBanner(1)" class="banner-dot w-2.5 h-1.5 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
    <section class="py-3">
        <div class="container-1500">
            <div class="bg-white rounded-xl p-3 md:p-4 shadow-xs border border-gray-100">
                <div class="flex items-center justify-between mb-3">
                    <h2 class="text-xs sm:text-sm md:text-base font-bold text-brand-700 uppercase tracking-tight flex items-center gap-2">
                        <span class="w-1.5 h-4 bg-brand-600 rounded-full inline-block"></span>
                        <span>Danh Mục Sản Phẩm</span>
                    </h2>
                    <span class="text-[11px] text-gray-500">Chọn danh mục để lọc nhanh</span>
                </div>

                <!-- Grid Danh Mục Nhỏ Gọn (2 hàng trên mobile, 6 cột trên máy tính, chữ nhỏ gọn không gãy dòng) -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2 md:gap-3">
                    <button onclick="filterCategory('Trái cây nhập khẩu')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh"
                             onerror="this.src='https://drive.google.com/thumbnail?id=13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh&sz=w200'"
                             alt="Trái cây nhập khẩu" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Trái Cây Nhập Khẩu</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Táo, Nho, Kiwi, Cherry</span>
                        </div>
                    </button>

                    <button onclick="filterCategory('Giỏ quà tặng trái cây')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/1i0Kg-oIfcMK_GJw4wfBWDbI_emrBG4-P"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1i0Kg-oIfcMK_GJw4wfBWDbI_emrBG4-P&sz=w200'"
                             alt="Giỏ quà tặng trái cây" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Giỏ Quà Trái Cây</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Giỏ 400k - 2 triệu</span>
                        </div>
                    </button>

                    <button onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY&sz=w200'"
                             alt="Khay - Hộp trái cây biếu tặng" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Khay - Hộp Biếu Tặng</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Hộp quà 200k - 1 triệu</span>
                        </div>
                    </button>

                    <button onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/1-ogygf0fWyqHatKILLe94RlkIuNgo9BN"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1-ogygf0fWyqHatKILLe94RlkIuNgo9BN&sz=w200'"
                             alt="Mâm trái cây đi lễ" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Mâm Quả Đi Lễ</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Mâm lễ & thắp hương</span>
                        </div>
                    </button>

                    <button onclick="filterCategory('Trái cây Việt Nam')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf"
                             onerror="this.src='https://drive.google.com/thumbnail?id=16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf&sz=w200'"
                             alt="Trái cây Việt Nam" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Trái Cây Việt Nam</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Đặc sản tuyển chọn</span>
                        </div>
                    </button>

                    <button onclick="filterCategory('Thực phẩm đồ khô')" class="group flex items-center gap-2.5 p-2 rounded-lg border border-gray-100 bg-brand-50/50 hover:bg-brand-600 hover:text-white transition text-left">
                        <img src="https://lh3.googleusercontent.com/d/1-f55hcJwL8BmdG7SVS3Z-91qqG3e1vjA"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1-f55hcJwL8BmdG7SVS3Z-91qqG3e1vjA&sz=w200'"
                             alt="Thực phẩm đồ khô" class="w-10 h-10 rounded-lg object-cover shrink-0 border border-white shadow-2xs">
                        <div class="min-w-0">
                            <p class="text-[11.5px] md:text-xs font-bold leading-snug group-hover:text-white text-gray-800">Thực Phẩm Đồ Khô</p>
                            <span class="text-[10px] text-gray-500 group-hover:text-emerald-100">Hạt & quà sức khỏe</span>
                        </div>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== KHU VỰC SẢN PHẨM TRANG CHỦ (12 ẢNH THỰC TẾ GOOGLE DRIVE - CHIA 2 CỘT TRÊN ĐIỆN THOẠI - % GIẢM GIÁ GÓC TRÁI FLATSOME) ==================== -->
    <section id="san-pham-trang-chu" class="py-4">
        <div class="container-1500 space-y-6">

            <!-- Thanh tiêu đề + Bộ lọc danh mục nhỏ gọn -->
            <div class="bg-white rounded-xl p-3.5 md:p-5 shadow-xs border border-gray-100">
                <div class="flex flex-col md:flex-row md:items-center justify-between gap-3 pb-3.5 border-b border-gray-100">
                    <div>
                        <h2 id="currentCategoryTitle" class="text-base md:text-lg font-extrabold text-brand-700 uppercase tracking-tight">
                            SẢN PHẨM NỔI BẬT & KHUYẾN MÃI
                        </h2>
                        <p class="text-xs text-gray-500 mt-0.5">Hình ảnh sản phẩm thực tế tại Minh Toàn Fruits - 25 Cẩm Bắc 3, Cẩm Lệ, Đà Nẵng</p>
                    </div>

                    <!-- Các nút lọc danh mục nhỏ gọn -->
                    <div class="flex flex-wrap items-center gap-1.5">
                        <button onclick="filterCategory('all')" data-cat-btn="all" class="cat-filter-btn home-cat-pill bg-brand-600 text-white font-semibold">
                            Tất cả (12)
                        </button>
                        <button onclick="filterCategory('Trái cây nhập khẩu')" data-cat-btn="Trái cây nhập khẩu" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Trái cây nhập khẩu
                        </button>
                        <button onclick="filterCategory('Giỏ quà tặng trái cây')" data-cat-btn="Giỏ quà tặng trái cây" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Giỏ quà tặng trái cây
                        </button>
                        <button onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" data-cat-btn="Khay - Hộp trái cây biếu tặng" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Khay - Hộp biếu tặng
                        </button>
                        <button onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" data-cat-btn="Mâm trái cây đi lễ - thắp hương" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Mâm trái cây đi lễ
                        </button>
                        <button onclick="filterCategory('Trái cây Việt Nam')" data-cat-btn="Trái cây Việt Nam" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Trái cây Việt Nam
                        </button>
                        <button onclick="filterCategory('Thực phẩm đồ khô')" data-cat-btn="Thực phẩm đồ khô" class="cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium">
                            Thực phẩm đồ khô
                        </button>
                    </div>
                </div>

                <!-- LƯỚI SẢN PHẨM: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) chuẩn UX Builder Flatsome -->
                <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4 mt-4">
                    <!-- Được render tự động bằng JS từ danh sách 12 ảnh thực tế Google Drive -->
                </div>
            </div>

            <!-- Khối Chuyên Mục 2: Giỏ Quà Tặng Trái Cây & Khay Hộp Biếu Tặng (Giống cấu trúc F5 Fruit Shop) -->
            <div class="bg-white rounded-xl p-3.5 md:p-5 shadow-xs border border-gray-100">
                <div class="flex flex-wrap items-center justify-between gap-2 pb-3 border-b border-gray-100">
                    <div>
                        <h2 class="text-base md:text-lg font-extrabold text-brand-700 uppercase tracking-tight">
                            GIỎ QUÀ TẶNG TRÁI CÂY & MÂM QUẢ DÂNG LỄ
                        </h2>
                        <p class="text-xs text-gray-500">Mẫu giỏ quà từ 400k - 2 triệu • Thiết kế sang trọng theo yêu cầu</p>
                    </div>
                    <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:text-brand-700 flex items-center gap-1">
                        <span>Đặt mẫu theo ngân sách riêng</span>
                        <i class="fa-solid fa-arrow-right text-[11px]"></i>
                    </a>
                </div>
                <div id="giftBasketGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4 mt-4">
                    <!-- Render 4 mẫu tiêu biểu -->
                </div>
            </div>

        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="form-bao-gia" class="py-4">
        <div class="container-1500">
            <div class="bg-gradient-to-br from-brand-700 via-brand-600 to-[#144718] rounded-xl p-4 sm:p-6 md:p-8 text-white shadow-md">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    
                    <!-- Thông tin cam kết & hướng dẫn đặt hàng giống F5 Fruit Shop -->
                    <div class="lg:col-span-5 space-y-3">
                        <span class="inline-block bg-amber-400 text-gray-900 text-xs font-bold px-3 py-1 rounded-full">
                            DỊCH VỤ KHÁCH HÀNG & DOANH NGHIỆP
                        </span>
                        <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold leading-snug">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ NHANH
                        </h2>
                        <p class="text-xs sm:text-sm text-emerald-100 leading-relaxed">
                            Minh Toàn Fruits nhận thiết kế <strong>Giỏ quà tặng trái cây, Khay quà biếu đối tác, Mâm quả đi lễ</strong> và cung cấp sỉ/lẻ trái cây nhập khẩu có xuất hóa đơn VAT đầy đủ tại Đà Nẵng.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs">
                            <div class="bg-white/10 p-3 rounded-lg border border-white/15">
                                <p class="font-bold text-amber-300"><i class="fa-solid fa-check-circle mr-1.5"></i>Kiểm hàng trước thanh toán</p>
                                <p class="text-emerald-100 text-[11px] mt-0.5">Đổi trả miễn phí trong 24h nếu không đúng cam kết.</p>
                            </div>
                            <div class="bg-white/10 p-3 rounded-lg border border-white/15">
                                <p class="font-bold text-amber-300"><i class="fa-solid fa-truck-fast mr-1.5"></i>Giao nhanh tại Đà Nẵng</p>
                                <p class="text-emerald-100 text-[11px] mt-0.5">Tặng kèm thiệp chúc mừng & biển tên doanh nghiệp.</p>
                            </div>
                        </div>
                        <div class="pt-1 text-xs space-y-1 text-emerald-100">
                            <p><i class="fa-solid fa-location-dot text-amber-300 w-5"></i><strong>Địa chỉ:</strong> 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng</p>
                            <p><i class="fa-solid fa-phone-volume text-amber-300 w-5"></i><strong>Hotline / Zalo báo giá:</strong> 0898.174.555</p>
                        </div>
                    </div>

                    <!-- Form nhập thông tin báo giá -->
                    <div class="lg:col-span-7">
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-gray-800 rounded-xl p-4 sm:p-6 shadow-lg space-y-3.5">
                            <h3 class="text-sm sm:text-base font-bold text-brand-700 border-b border-gray-100 pb-2">
                                <i class="fa-solid fa-file-pen text-brand-600 mr-1.5"></i>Gửi Yêu Cầu Tư Vấn & Báo Giá
                            </h3>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên quý khách *</label>
                                    <input id="quoteName" type="text" required placeholder="Nhập họ và tên..."
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brand-600">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx"
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brand-600">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Danh mục quan tâm</label>
                                    <select id="quoteCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brand-600 bg-white">
                                        <option value="Giỏ quà tặng trái cây (400k - 2 triệu)">Giỏ quà tặng trái cây (400k - 2 triệu)</option>
                                        <option value="Khay - Hộp trái cây biếu tặng (200k - 1 triệu)">Khay - Hộp trái cây biếu tặng (200k - 1 triệu)</option>
                                        <option value="Mâm trái cây đi lễ - thắp hương">Mâm trái cây đi lễ - thắp hương</option>
                                        <option value="Trái cây nhập khẩu nguyên thùng / sỉ lẻ">Trái cây nhập khẩu nguyên thùng / sỉ lẻ</option>
                                        <option value="Quà tặng doanh nghiệp số lượng lớn">Quà tặng doanh nghiệp số lượng lớn</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Ngân sách dự kiến / Số lượng</label>
                                    <input id="quoteBudget" type="text" placeholder="VD: 5 giỏ quà mức 800k/giỏ"
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brand-600">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-gray-700 mb-1">Nội dung yêu cầu chi tiết (Loại quả yêu thích, nội dung thiệp, giờ giao...)</label>
                                <textarea id="quoteNote" rows="2" placeholder="Nhập yêu cầu của bạn để Minh Toàn Fruits chuẩn bị chu đáo nhất..."
                                          class="w-full px-3 py-2 text-xs sm:text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brand-600"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                                <span class="text-[11px] text-gray-500">
                                    <i class="fa-solid fa-shield-halved text-brand-600 mr-1"></i>Phản hồi báo giá trong 5 phút
                                </span>
                                <button type="submit" class="w-full sm:w-auto bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded-lg shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU BÁO GIÁ</span>
                                </button>
                            </div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG TRÁI CÂY) ==================== -->
    <section id="bai-viet-trang-chu" class="py-4">
        <div class="container-1500">
            <div class="bg-white rounded-xl p-3.5 md:p-5 shadow-xs border border-gray-100">
                <div class="flex items-center justify-between pb-3 border-b border-gray-100">
                    <div>
                        <h2 class="text-base md:text-lg font-extrabold text-brand-700 uppercase tracking-tight">
                            TIN TỨC & CẨM NANG TRÁI CÂY NHẬP KHẨU
                        </h2>
                        <p class="text-xs text-gray-500">Kinh nghiệm chọn trái cây tươi ngon, bảo quản đúng chuẩn & xu hướng giỏ quà tặng</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mt-4">
                    <!-- Bài viết 1 -->
                    <article class="rounded-xl border border-gray-100 overflow-hidden bg-gray-50/50 hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="h-40 overflow-hidden bg-gray-100">
                                <img src="https://lh3.googleusercontent.com/d/1mstlDrVN9zzvcqI0tDa3gSOjnEoanSKu"
                                     onerror="this.src='https://drive.google.com/thumbnail?id=1mstlDrVN9zzvcqI0tDa3gSOjnEoanSKu&sz=w600'"
                                     alt="Top mẫu giỏ quà trái cây nhập khẩu" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            </div>
                            <div class="p-3.5">
                                <span class="text-[10.5px] text-brand-600 font-semibold"><i class="fa-regular fa-calendar mr-1"></i>Cẩm nang quà tặng</span>
                                <h3 class="text-xs sm:text-sm font-bold text-gray-800 mt-1 leading-snug">
                                    Gợi Ý Những Mẫu Giỏ Quà Trái Cây Nhập Khẩu Kèm Hoa Tươi Sang Trọng Tại Đà Nẵng
                                </h3>
                                <p class="text-[11.5px] text-gray-600 mt-1.5 leading-relaxed">
                                    Tổng hợp các mẫu giỏ quà trái cây biếu tặng đối tác, khai trương, sinh nhật và lễ Tết tinh tế, đầy đặn với mức giá hợp lý từ 400k - 2 triệu đồng.
                                </p>
                            </div>
                        </div>
                        <div class="px-3.5 pb-3">
                            <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline">Xem chi tiết & đặt mẫu »</a>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article class="rounded-xl border border-gray-100 overflow-hidden bg-gray-50/50 hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="h-40 overflow-hidden bg-gray-100">
                                <img src="https://lh3.googleusercontent.com/d/1B3n518NBXCpAo4wBcktIs3cpQTaIlltO"
                                     onerror="this.src='https://drive.google.com/thumbnail?id=1B3n518NBXCpAo4wBcktIs3cpQTaIlltO&sz=w600'"
                                     alt="Kiwi Vàng New Zealand Zespri" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            </div>
                            <div class="p-3.5">
                                <span class="text-[10.5px] text-brand-600 font-semibold"><i class="fa-regular fa-calendar mr-1"></i>Dinh dưỡng sức khỏe</span>
                                <h3 class="text-xs sm:text-sm font-bold text-gray-800 mt-1 leading-snug">
                                    Kiwi Vàng New Zealand & Táo Envy Mỹ: Bộ Đôi Giàu Vitamin C Cho Cả Gia Đình
                                </h3>
                                <p class="text-[11.5px] text-gray-600 mt-1.5 leading-relaxed">
                                    Trái cây nhập khẩu chính ngạch với hàm lượng dinh dưỡng cao, vị ngọt đậm tự nhiên, giòn thơm, rất tốt cho sức đề kháng của trẻ nhỏ và người lớn tuổi.
                                </p>
                            </div>
                        </div>
                        <div class="px-3.5 pb-3">
                            <a href="#san-pham-trang-chu" class="text-xs font-semibold text-brand-600 hover:underline">Khám phá sản phẩm »</a>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article class="rounded-xl border border-gray-100 overflow-hidden bg-gray-50/50 hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="h-40 overflow-hidden bg-gray-100">
                                <img src="https://lh3.googleusercontent.com/d/17aCQw3a97nWS5GcHbVY60vJ4sP7LbW-X"
                                     onerror="this.src='https://drive.google.com/thumbnail?id=17aCQw3a97nWS5GcHbVY60vJ4sP7LbW-X&sz=w600'"
                                     alt="Cách bảo quản nho xanh và cherry" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            </div>
                            <div class="p-3.5">
                                <span class="text-[10.5px] text-brand-600 font-semibold"><i class="fa-regular fa-calendar mr-1"></i>Mẹo bảo quản</span>
                                <h3 class="text-xs sm:text-sm font-bold text-gray-800 mt-1 leading-snug">
                                    3 Cách Bảo Quản Nho Xanh Autumn Crisp, Cherry Và Việt Quất Tươi Lâu Trong Tủ Lạnh
                                </h3>
                                <p class="text-[11.5px] text-gray-600 mt-1.5 leading-relaxed">
                                    Bí quyết giữ cuống nho luôn xanh tươi, quả giòn mọng nước suốt 7-10 ngày bằng cách bảo quản khô trong hộp thoáng khí trước khi rửa ăn.
                                </p>
                            </div>
                        </div>
                        <div class="px-3.5 pb-3">
                            <a href="#san-pham-trang-chu" class="text-xs font-semibold text-brand-600 hover:underline">Xem thêm mẹo hay »</a>
                        </div>
                    </article>

                    <!-- Bài viết 4 -->
                    <article class="rounded-xl border border-gray-100 overflow-hidden bg-gray-50/50 hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="h-40 overflow-hidden bg-gray-100">
                                <img src="https://lh3.googleusercontent.com/d/1iYmrrsucZ7n806cc6VbdhMCsgeiF_0Qe"
                                     onerror="this.src='https://drive.google.com/thumbnail?id=1iYmrrsucZ7n806cc6VbdhMCsgeiF_0Qe&sz=w600'"
                                     alt="Mâm trái cây đi lễ thắp hương" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            </div>
                            <div class="p-3.5">
                                <span class="text-[10.5px] text-brand-600 font-semibold"><i class="fa-regular fa-calendar mr-1"></i>Văn hóa tâm linh</span>
                                <h3 class="text-xs sm:text-sm font-bold text-gray-800 mt-1 leading-snug">
                                    Nghệ Thuật Sắp Xếp Mâm Quả Trái Cây Nhập Khẩu Dâng Lễ & Thắp Hương Trang Trọng
                                </h3>
                                <p class="text-[11.5px] text-gray-600 mt-1.5 leading-relaxed">
                                    Cách phối hợp ngũ quả hài hòa màu sắc, tươi mới và trang nghiêm cho ngày Rằm, mồng Một, lễ khai trương và tân gia tại Minh Toàn Fruits.
                                </p>
                            </div>
                        </div>
                        <div class="px-3.5 pb-3">
                            <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline">Đặt mâm lễ ngay »</a>
                        </div>
                    </article>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC ==================== -->
    <section id="doi-tac" class="py-4">
        <div class="container-1500">
            <div class="bg-white rounded-xl p-3.5 md:p-5 shadow-xs border border-gray-100">
                <div class="text-center max-w-2xl mx-auto mb-4">
                    <h2 class="text-base md:text-lg font-extrabold text-brand-700 uppercase tracking-tight">
                        ĐỐI TÁC & THƯƠNG HIỆU NHẬP KHẨU CHÍNH NGẠCH
                    </h2>
                    <p class="text-xs text-gray-500 mt-0.5">Hợp tác cùng các thương hiệu nông sản & trái cây danh tiếng hàng đầu thế giới</p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3.5">
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-brand-700 tracking-wide">ZESPRI™</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Kiwi New Zealand</span>
                    </div>
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-red-700 tracking-wide">ENVY™ APPLES</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Táo Cao Cấp Mỹ & NZ</span>
                    </div>
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-emerald-700 tracking-wide">AUTUMN CRISP®</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Nho Xanh Không Hạt</span>
                    </div>
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-rose-700 tracking-wide">ROCKIT™</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Táo Ống New Zealand</span>
                    </div>
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-amber-700 tracking-wide">K-BERRY & PEAR</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Lê & Dưa Lưới Hàn Quốc</span>
                    </div>
                    <div class="p-3 rounded-xl border border-gray-100 bg-gray-50/70 flex flex-col items-center justify-center text-center hover:border-brand-500 transition">
                        <span class="text-sm font-extrabold text-purple-700 tracking-wide">ORCHARD VIEW</span>
                        <span class="text-[11px] text-gray-500 mt-0.5">Cherry Đỏ Mỹ & Úc</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ ==================== -->
    <section id="lien-he-bando" class="py-4">
        <div class="container-1500">
            <div class="bg-white rounded-xl p-3.5 md:p-5 shadow-xs border border-gray-100">
                <div class="flex flex-wrap items-center justify-between gap-2 pb-3 border-b border-gray-100 mb-4">
                    <div>
                        <h2 class="text-base md:text-lg font-extrabold text-brand-700 uppercase tracking-tight">
                            KẾT NỐI FANPAGE & BẢN ĐỒ CỬA HÀNG MINH TOÀN FRUITS
                        </h2>
                        <p class="text-xs text-gray-500">Địa chỉ: 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng • Hotline/Zalo: 0898.174.555</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                    
                    <!-- Cột 1: Bản đồ Google Map trực tiếp ngoài trang chủ (7 cột) -->
                    <div class="lg:col-span-7 flex flex-col justify-between rounded-xl overflow-hidden border border-gray-200 bg-gray-50">
                        <div class="p-3 bg-brand-50 border-b border-brand-100 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-700">
                                <i class="fa-solid fa-map-location-dot text-brand-600"></i>
                                <span>Bản Đồ Google Maps: 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng</span>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=25+C%E1%BA%A9m+B%E1%BA%AFc+3,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold bg-brand-600 text-white px-3 py-1 rounded-lg hover:bg-brand-700 transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường Google Maps
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[340px]">
                            <iframe
                                title="Google Map Minh Toàn Fruits 25 Cẩm Bắc 3 Đà Nẵng"
                                src="https://maps.google.com/maps?q=25%20C%E1%BA%A9m%20B%E1%BA%AFc%203,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột 2: Fanpage Facebook trực tiếp ngoài trang chủ (5 cột) -->
                    <div class="lg:col-span-5 flex flex-col justify-between rounded-xl overflow-hidden border border-gray-200 bg-white">
                        <div class="p-3 bg-blue-50 border-b border-blue-100 flex items-center justify-between">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-blue-800">
                                <i class="fa-brands fa-facebook text-blue-600 text-base"></i>
                                <span>Fanpage Chính Thức Minh Toàn Fruits</span>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold bg-blue-600 text-white px-2.5 py-1 rounded-lg hover:bg-blue-700 transition">
                                Theo dõi trang
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage + Nhúng Facebook Plugin -->
                        <div class="p-4 flex-1 flex flex-col justify-between space-y-3 bg-gradient-to-b from-blue-50/40 to-white">
                            <div class="flex items-center gap-3 p-3 rounded-xl bg-white border border-gray-200 shadow-2xs">
                                <img src="https://lh3.googleusercontent.com/d/1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5"
                                     onerror="this.src='https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w300'"
                                     alt="Logo Fanpage Minh Toàn Fruits"
                                     class="w-14 h-14 rounded-full object-contain border border-brand-200 p-1 bg-white shrink-0">
                                <div class="min-w-0">
                                    <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer"
                                       class="text-sm font-extrabold text-blue-800 hover:underline block truncate">
                                        Minh Toàn Fruits - Trái Cây Nhập Khẩu
                                    </a>
                                    <p class="text-xs text-gray-600">Cửa hàng trái cây nhập khẩu & Giỏ quà tặng Đà Nẵng</p>
                                    <div class="flex items-center gap-2 mt-1">
                                        <span class="text-[11px] bg-green-100 text-green-800 font-semibold px-2 py-0.5 rounded">Đang mở cửa</span>
                                        <span class="text-[11px] text-gray-500">ID: 61593844808825</span>
                                    </div>
                                </div>
                            </div>

                            <!-- Bộ ảnh thực tế mới cập nhật trên Fanpage -->
                            <div>
                                <p class="text-xs font-semibold text-gray-700 mb-2">Hình ảnh giỏ quà & trái cây cập nhật mỗi ngày trên Fanpage:</p>
                                <div class="grid grid-cols-4 gap-2">
                                    <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer" class="block rounded-lg overflow-hidden border border-gray-200 h-16">
                                        <img src="https://lh3.googleusercontent.com/d/13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh" onerror="this.src='https://drive.google.com/thumbnail?id=13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh&sz=w300'" alt="Ảnh thực tế 1" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer" class="block rounded-lg overflow-hidden border border-gray-200 h-16">
                                        <img src="https://lh3.googleusercontent.com/d/1i0Kg-oIfcMK_GJw4wfBWDbI_emrBG4-P" onerror="this.src='https://drive.google.com/thumbnail?id=1i0Kg-oIfcMK_GJw4wfBWDbI_emrBG4-P&sz=w300'" alt="Ảnh thực tế 2" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer" class="block rounded-lg overflow-hidden border border-gray-200 h-16">
                                        <img src="https://lh3.googleusercontent.com/d/1-nCGSHeUzEmsXmWPhL08NJMdPsj_QdyN" onerror="this.src='https://drive.google.com/thumbnail?id=1-nCGSHeUzEmsXmWPhL08NJMdPsj_QdyN&sz=w300'" alt="Ảnh thực tế 3" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer" class="block rounded-lg overflow-hidden border border-gray-200 h-16">
                                        <img src="https://lh3.googleusercontent.com/d/1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h" onerror="this.src='https://drive.google.com/thumbnail?id=1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h&sz=w300'" alt="Ảnh thực tế 4" class="w-full h-full object-cover">
                                    </a>
                                </div>
                            </div>

                            <div class="grid grid-cols-2 gap-2.5 pt-1">
                                <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer"
                                   class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold transition">
                                    <i class="fa-brands fa-facebook-f"></i>
                                    <span>Truy Cập Fanpage</span>
                                </a>
                                <a href="https://zalo.me/0898174555" target="_blank" rel="noopener noreferrer"
                                   class="flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold transition">
                                    <i class="fa-solid fa-comment-dots"></i>
                                    <span>Nhắn Zalo: 0898.174.555</span>
                                </a>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="bg-brand-800 text-white mt-6 border-t-4 border-brand-500">
        <div class="container-1500 py-8 md:py-10">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 text-xs sm:text-sm">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5"
                             onerror="this.src='https://drive.google.com/thumbnail?id=1HUb6hZaAXaya3UGQqJ3pzdpZgullR6n5&sz=w200'"
                             alt="Logo Minh Toàn Fruits"
                             class="w-10 h-10 rounded-full bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <h3 class="font-extrabold text-sm sm:text-base text-white">MINH TOÀN FRUITS</h3>
                            <p class="text-[11px] text-amber-300">Website: minhtoanfruits.com</p>
                        </div>
                    </div>
                    <p class="text-emerald-100 text-xs leading-relaxed">
                        CÔNG TY TNHH HOA QUẢ NHẬP KHẨU MINH TOÀN FRUITS chuyên nhập khẩu và phân phối sỉ lẻ trái cây tươi cao cấp, giỏ quà tặng trái cây, khay quà biếu và mâm quả dâng lễ uy tín tại Đà Nẵng.
                    </p>
                    <div class="space-y-1 text-xs text-emerald-100 pt-1">
                        <p><i class="fa-solid fa-location-dot text-amber-300 w-5"></i>25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone text-amber-300 w-5"></i>Hotline/Zalo: <strong>0898.174.555</strong></p>
                        <p><i class="fa-solid fa-globe text-amber-300 w-5"></i>Website: minhtoanfruits.com</p>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm uppercase text-amber-300 tracking-wide">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây nhập khẩu')" class="hover:text-white">› Trái cây nhập khẩu (Táo, Nho, Kiwi, Cherry)</a></li>
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Giỏ quà tặng trái cây')" class="hover:text-white">› Giỏ quà tặng trái cây (400k - 2 triệu)</a></li>
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Khay - Hộp trái cây biếu tặng')" class="hover:text-white">› Khay - Hộp trái cây biếu tặng</a></li>
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Mâm trái cây đi lễ - thắp hương')" class="hover:text-white">› Mâm trái cây đi lễ - thắp hương</a></li>
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Trái cây Việt Nam')" class="hover:text-white">› Trái cây Việt Nam tuyển chọn</a></li>
                        <li><a href="#san-pham-trang-chu" onclick="filterCategory('Thực phẩm đồ khô')" class="hover:text-white">› Thực phẩm đồ khô & Hạt dinh dưỡng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách cam kết (Giống F5 Fruit Shop) -->
                <div class="space-y-2">
                    <h4 class="font-bold text-sm uppercase text-amber-300 tracking-wide">Cam Kết Chất Lượng</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li>✓ Được kiểm hàng trước khi thanh toán</li>
                        <li>✓ Đổi trả nhanh chóng trong vòng 24h</li>
                        <li>✓ Nguồn gốc xuất xứ rõ ràng, chính ngạch</li>
                        <li>✓ Đảm bảo vệ sinh an toàn thực phẩm</li>
                        <li>✓ Miễn phí thiệp & băng rôn cho giỏ quà tặng</li>
                        <li>✓ Hỗ trợ xuất hóa đơn cho doanh nghiệp</li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div class="space-y-2.5">
                    <h4 class="font-bold text-sm uppercase text-amber-300 tracking-wide">Liên Hệ Đặt Hàng Nhanh</h4>
                    <p class="text-xs text-emerald-100 leading-relaxed">
                        Nhắn tin trực tiếp qua Fanpage hoặc Zalo để nhân viên gửi ảnh mẫu giỏ quà và các loại quả tươi mới về trong ngày:
                    </p>
                    <div class="flex flex-col gap-2 pt-1">
                        <a href="tel:0898174555" class="flex items-center gap-2 bg-amber-400 text-gray-900 font-bold text-xs px-3.5 py-2 rounded-lg hover:bg-amber-300 transition">
                            <i class="fa-solid fa-phone-volume"></i>
                            <span>Hotline: 0898.174.555</span>
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer"
                           class="flex items-center gap-2 bg-blue-600 text-white font-bold text-xs px-3.5 py-2 rounded-lg hover:bg-blue-500 transition">
                            <i class="fa-brands fa-facebook"></i>
                            <span>Fanpage Minh Toàn Fruits</span>
                        </a>
                    </div>
                </div>

            </div>
        </div>
        <div class="bg-[#08220a] text-emerald-200/80 text-[11px] py-3 text-center border-t border-white/10">
            <div class="container-1500">
                © Bản quyền thuộc về <strong>Minh Toàn Fruits (minhtoanfruits.com)</strong> • Địa chỉ: 25 Cẩm Bắc 3, Phường Cẩm Lệ, TP Đà Nẵng • SĐT: 0898.174.555
            </div>
        </div>
    </footer>

    <!-- ==================== NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61593844808825" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition"
           title="Fanpage Minh Toàn Fruits">
            <i class="fa-brands fa-facebook-f text-base md:text-sm w-5 text-center"></i>
            <span class="hidden md:inline text-xs font-bold whitespace-nowrap">Fanpage</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0898174555" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition"
           title="Chat Zalo 0898.174.555">
            <span class="font-extrabold text-[11px] bg-white text-[#0068FF] rounded-full w-5 h-5 flex items-center justify-center shrink-0">Z</span>
            <span class="hidden md:inline text-xs font-bold whitespace-nowrap">Zalo: 0898.174.555</span>
        </a>

        <!-- Nút Gọi Hotline Nổi Bật -->
        <a href="tel:0898174555"
           class="pulse-btn flex items-center gap-2 bg-gradient-to-r from-red-600 to-brand-accent text-white rounded-full p-3 md:px-4 md:py-2.5 shadow-xl transition"
           title="Gọi Hotline 0898.174.555">
            <i class="fa-solid fa-phone-volume text-base md:text-sm"></i>
            <span class="text-xs font-extrabold whitespace-nowrap pr-0.5">0898.174.555</span>
        </a>
    </div>

    <!-- ==================== MODAL GIỎ HÀNG & ĐẶT HÀNG NHANH ==================== -->
    <div id="cartModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3 bg-black/50 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-lg w-full p-4 sm:p-6 shadow-2xl border border-gray-100 max-h-[90vh] flex flex-col justify-between">
            <div class="flex items-center justify-between pb-3 border-b border-gray-100">
                <h3 class="text-sm sm:text-base font-extrabold text-brand-700 flex items-center gap-2">
                    <i class="fa-solid fa-basket-shopping text-brand-600"></i>
                    <span>GIỎ HÀNG CỦA BẠN</span>
                </h3>
                <button onclick="closeCartModal()" class="w-7 h-7 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center text-gray-600">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>

            <div id="cartItemsContainer" class="py-3 overflow-y-auto space-y-2.5 max-h-[45vh] text-xs">
                <!-- Danh sách sản phẩm trong giỏ -->
            </div>

            <div class="pt-3 border-t border-gray-100 space-y-3">
                <div class="flex items-center justify-between text-sm font-bold">
                    <span>Tổng cộng tạm tính:</span>
                    <span id="cartTotalAmount" class="text-red-600 text-base">0₫</span>
                </div>
                <div class="grid grid-cols-2 gap-2">
                    <a href="https://zalo.me/0898174555" target="_blank" rel="noopener noreferrer"
                       class="bg-brand-600 hover:bg-brand-700 text-white text-center font-bold text-xs py-2.5 px-3 rounded-lg transition">
                        <i class="fa-solid fa-check mr-1"></i>Chốt Đơn Qua Zalo
                    </a>
                    <a href="tel:0898174555"
                       class="bg-brand-accent hover:bg-orange-700 text-white text-center font-bold text-xs py-2.5 px-3 rounded-lg transition">
                        <i class="fa-solid fa-phone mr-1"></i>Gọi: 0898.174.555
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Hộp thông báo đẹp thay cho alert() -->
    <div id="toastMessage" class="fixed top-4 right-4 z-50 hidden bg-brand-700 text-white text-xs sm:text-sm font-semibold px-4 py-3 rounded-xl shadow-xl border border-white/20 flex items-center gap-2.5 max-w-xs">
        <i class="fa-solid fa-circle-check text-amber-300 text-base"></i>
        <span id="toastText">Đã thêm vào giỏ hàng!</span>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ SẢN PHẨM, BANNER TỰ TRƯỢT, BỘ LỌC & BÁO GIÁ ==================== -->
    <script>
        // Danh sách 12 sản phẩm sử dụng toàn bộ 12 ảnh thực tế trong Google Drive của khách hàng,
        // phân bổ đúng danh mục và tên sản phẩm chuẩn theo mẫu F5 Fruit Shop & Minh Toàn Fruits:
        const productsData = [
            {
                id: 1,
                name: "Giỏ Quà Trái Cây Nhập Khẩu Kèm Hoa Tươi Cao Cấp MT01",
                category: "Giỏ quà tặng trái cây",
                subCategory: "Giỏ từ 800k - 1 triệu",
                driveId: "13ylXJDG3Lj7_GXA-kQkgt0xwfS4MDvrh",
                oldPrice: 950000,
                price: 790000,
                discount: 17,
                unit: "Giỏ thiết kế"
            },
            {
                id: 2,
                name: "Giỏ Quà Trái Cây Nhập Khẩu Biếu Tặng Sang Trọng MT02",
                category: "Giỏ quà tặng trái cây",
                subCategory: "Giỏ từ 500k - 800k",
                driveId: "1i0Kg-oIfcMK_GJw4wfBWDbI_emrBG4-P",
                oldPrice: 780000,
                price: 650000,
                discount: 17,
                unit: "Giỏ thiết kế"
            },
            {
                id: 3,
                name: "Giỏ Quà Trái Cây Nhập Khẩu Kết Hợp Hoa Tươi Tinh Tế MT03",
                category: "Giỏ quà tặng trái cây",
                subCategory: "Giỏ từ 1 triệu - 1.5 triệu",
                driveId: "1HS2o74J4kt-N0Q4RAXHQ6N9kIMDXd9jY",
                oldPrice: 1250000,
                price: 1050000,
                discount: 16,
                unit: "Giỏ cao cấp"
            },
            {
                id: 4,
                name: "Mâm Trái Cây Nhập Khẩu Dâng Lễ - Thắp Hương Trang Trọng MT04",
                category: "Mâm trái cây đi lễ - thắp hương",
                subCategory: "Mâm quả đi lễ",
                driveId: "1-ogygf0fWyqHatKILLe94RlkIuNgo9BN",
                oldPrice: 850000,
                price: 690000,
                discount: 19,
                unit: "Mâm lễ đầy đặn"
            },
            {
                id: 5,
                name: "Khay - Hộp Trái Cây Nhập Khẩu Biếu Tặng Tuyển Chọn MT05",
                category: "Khay - Hộp trái cây biếu tặng",
                subCategory: "Khay hộp từ 500k - 700k",
                driveId: "1-nCGSHeUzEmsXmWPhL08NJMdPsj_QdyN",
                oldPrice: 650000,
                price: 550000,
                discount: 15,
                unit: "Khay/Hộp quà"
            },
            {
                id: 6,
                name: "Táo Envy New Zealand Size Lớn Giòn Ngọt Chuẩn Vị (1kg)",
                category: "Trái cây nhập khẩu",
                subCategory: "Táo nhập khẩu",
                driveId: "16P4rEt1vWRGymUAootgPVCXsBp9Z5Hpf",
                oldPrice: 260000,
                price: 225000,
                discount: 13,
                unit: "Kg / Hộp quà"
            },
            {
                id: 7,
                name: "Nho Xanh Không Hạt Autumn Crisp Mỹ / Úc Tươi Giòn",
                category: "Trái cây nhập khẩu",
                subCategory: "Nho nhập khẩu",
                driveId: "1sHHHynvsNNv0I76lbbVV2KGTViEBwU3h",
                oldPrice: 295000,
                price: 245000,
                discount: 17,
                unit: "Kg / Hộp tươi"
            },
            {
                id: 8,
                name: "Kiwi Vàng Zespri New Zealand Hộp Tuyển Chọn Ngọt Mọng",
                category: "Trái cây nhập khẩu",
                subCategory: "Kiwi nhập khẩu",
                driveId: "1mstlDrVN9zzvcqI0tDa3gSOjnEoanSKu",
                oldPrice: 310000,
                price: 265000,
                discount: 15,
                unit: "Hộp / Kg"
            },
            {
                id: 9,
                name: "Quả Anh Đào (Cherry) Đỏ Mỹ / Úc Size VIP Quả Căng Mọng",
                category: "Trái cây nhập khẩu",
                subCategory: "Cherry nhập khẩu",
                driveId: "1B3n518NBXCpAo4wBcktIs3cpQTaIlltO",
                oldPrice: 550000,
                price: 465000,
                discount: 15,
                unit: "Kg / Hộp 500g"
            },
            {
                id: 10,
                name: "Khay Quà Trái Cây Tươi Mix Đa Dạng Các Loại Quả Theo Mùa MT10",
                category: "Khay - Hộp trái cây biếu tặng",
                subCategory: "Khay hộp từ 300k - 500k",
                driveId: "17aCQw3a97nWS5GcHbVY60vJ4sP7LbW-X",
                oldPrice: 520000,
                price: 430000,
                discount: 17,
                unit: "Khay đóng sẵn"
            },
            {
                id: 11,
                name: "Combo Đĩa Quả Thắp Hương & Trái Cây Đặc Sản Tuyển Chọn MT11",
                category: "Trái cây Việt Nam",
                subCategory: "Trái cây đặc sản",
                driveId: "1iYmrrsucZ7n806cc6VbdhMCsgeiF_0Qe",
                oldPrice: 420000,
                price: 350000,
                discount: 17,
                unit: "Combo / Khay"
            },
            {
                id: 12,
                name: "Set Hộp Quà Trái Cây Nhập Khẩu & Thực Phẩm Dinh Dưỡng Sức Khỏe MT12",
                category: "Thực phẩm đồ khô",
                subCategory: "Quà sức khỏe",
                driveId: "1-f55hcJwL8BmdG7SVS3Z-91qqG3e1vjA",
                oldPrice: 680000,
                price: 560000,
                discount: 18,
                unit: "Set hộp quà"
            }
        ];

        let cart = [];

        function formatCurrency(val) {
            return val.toLocaleString('vi-VN') + '₫';
        }

        // Tạo thẻ sản phẩm chuẩn Flatsome:
        // - Có % giảm giá góc trên bên trái (.flatsome-sale-badge)
        // - Không có các nhãn dán rối mắt khác ở trang chủ
        // - Chia 2 cột trên điện thoại, tên sản phẩm đầy đủ không bị cắt hay tràn chữ
        function createProductCardHTML(product) {
            const primaryImg = `https://lh3.googleusercontent.com/d/${product.driveId}`;
            const backupImg1 = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800`;
            const backupImg2 = `https://drive.google.com/uc?export=view&id=${product.driveId}`;

            return `
                <div class="flatsome-product-box bg-white rounded-xl border border-gray-200/80 overflow-hidden flex flex-col justify-between relative">
                    <!-- Góc trên bên trái: % giảm giá chuẩn Flatsome -->
                    <div class="flatsome-sale-badge">-${product.discount}%</div>

                    <div>
                        <!-- Khung ảnh tỉ lệ vuông đồng đều -->
                        <div class="relative w-full aspect-square bg-gray-50 overflow-hidden border-b border-gray-100">
                            <img src="${primaryImg}"
                                 onerror="if(!this.dataset.retry1){this.dataset.retry1=1;this.src='${backupImg1}';}else if(!this.dataset.retry2){this.dataset.retry2=1;this.src='${backupImg2}';}"
                                 alt="${product.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>

                        <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ không tràn ra ngoài hoặc thiếu chữ, không để các nhãn dán rối mắt -->
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full text-[12.5px] sm:text-[13.5px] font-bold text-gray-800 hover:text-brand-600 transition">
                                ${product.name}
                            </h3>

                            <!-- Giá gốc gạch ngang và Giá giảm nổi bật giống Flatsome -->
                            <div class="mt-2 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-red-600 font-extrabold text-xs sm:text-sm md:text-base">
                                    ${formatCurrency(product.price)}
                                </span>
                                <del class="text-gray-400 text-[10.5px] sm:text-xs font-medium">
                                    ${formatCurrency(product.oldPrice)}
                                </del>
                            </div>
                        </div>
                    </div>

                    <!-- Nút đặt mua gọn đẹp -->
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 grid grid-cols-2 gap-1.5">
                        <button onclick="addToCart(${product.id})"
                                class="w-full py-1.5 px-2 rounded-lg bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white border border-brand-200 font-semibold text-[11px] sm:text-xs transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-cart-plus text-[10px]"></i>
                            <span>Thêm giỏ</span>
                        </button>
                        <a href="#form-bao-gia" onclick="prefillProductQuote('${product.name.replace(/'/g, "\\'")}')"
                           class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white font-semibold text-[11px] sm:text-xs transition flex items-center justify-center gap-1 text-center">
                            <span>Đặt ngay</span>
                        </a>
                    </div>
                </div>
            `;
        }

        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list || list.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full py-8 text-center text-gray-500 text-xs sm:text-sm">
                        Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng liên hệ Hotline/Zalo <strong>0898.174.555</strong> để được tư vấn mẫu mới nhất!
                    </div>
                `;
                return;
            }
            grid.innerHTML = list.map(item => createProductCardHTML(item)).join('');
        }

        function renderGiftBasketsSection() {
            const giftGrid = document.getElementById('giftBasketGrid');
            const giftItems = productsData.slice(0, 4);
            giftGrid.innerHTML = giftItems.map(item => createProductCardHTML(item)).join('');
        }

        function filterCategory(categoryName) {
            const titleEl = document.getElementById('currentCategoryTitle');
            const buttons = document.querySelectorAll('.cat-filter-btn');

            buttons.forEach(btn => {
                if (btn.dataset.catBtn === categoryName) {
                    btn.className = 'cat-filter-btn home-cat-pill bg-brand-600 text-white font-semibold';
                } else {
                    btn.className = 'cat-filter-btn home-cat-pill bg-gray-100 hover:bg-brand-50 text-gray-700 font-medium';
                }
            });

            if (categoryName === 'all') {
                titleEl.textContent = 'SẢN PHẨM NỔI BẬT & KHUYẾN MÃI';
                renderProducts(productsData);
            } else {
                titleEl.textContent = 'DANH MỤC: ' + categoryName.toUpperCase();
                const filtered = productsData.filter(p => p.category === categoryName);
                renderProducts(filtered);
            }
        }

        function filterSubCategory(categoryName, keyword) {
            const titleEl = document.getElementById('currentCategoryTitle');
            titleEl.textContent = `DANH MỤC: ${categoryName.toUpperCase()} - ${keyword.toUpperCase()}`;
            const filtered = productsData.filter(p =>
                p.category === categoryName &&
                (p.name.toLowerCase().includes(keyword.toLowerCase()) || p.subCategory.toLowerCase().includes(keyword.toLowerCase()))
            );
            renderProducts(filtered.length ? filtered : productsData.filter(p => p.category === categoryName));
        }

        function handleSearch(keyword) {
            const cleanKey = (keyword || '').trim().toLowerCase();
            if (!cleanKey) {
                renderProducts(productsData);
                return;
            }
            const results = productsData.filter(p =>
                p.name.toLowerCase().includes(cleanKey) ||
                p.category.toLowerCase().includes(cleanKey) ||
                p.subCategory.toLowerCase().includes(cleanKey)
            );
            document.getElementById('currentCategoryTitle').textContent = `KẾT QUẢ TÌM KIẾM: "${keyword}"`;
            renderProducts(results);
        }

        // ==================== BANNER SLIDER TỰ TRƯỢT ====================
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let bannerInterval = null;

        function updateBannerDisplay() {
            const slides = document.querySelectorAll('.banner-slide');
            const dots = document.querySelectorAll('.banner-dot');

            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });

            dots.forEach((dot, idx) => {
                if (idx === currentSlideIndex) {
                    dot.className = 'banner-dot w-6 h-1.5 rounded-full bg-amber-400 transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-1.5 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeBanner(step) {
            currentSlideIndex = (currentSlideIndex + step + totalSlides) % totalSlides;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function goToBanner(index) {
            currentSlideIndex = index;
            updateBannerDisplay();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentSlideIndex = (currentSlideIndex + 1) % totalSlides;
                updateBannerDisplay();
            }, 4500);
        }

        // ==================== GIỎ HÀNG & FORM BÁO GIÁ ====================
        function showToast(msg) {
            const toast = document.getElementById('toastMessage');
            document.getElementById('toastText').textContent = msg;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 2800);
        }

        function addToCart(productId) {
            const prod = productsData.find(p => p.id === productId);
            if (!prod) return;
            const existing = cart.find(item => item.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...prod, qty: 1 });
            }
            updateCartUI();
            showToast(`Đã thêm "${prod.name}" vào giỏ hàng!`);
        }

        function updateCartUI() {
            const count = cart.reduce((sum, item) => sum + item.qty, 0);
            document.getElementById('cartCountBadge').textContent = count;

            const container = document.getElementById('cartItemsContainer');
            const totalEl = document.getElementById('cartTotalAmount');

            if (cart.length === 0) {
                container.innerHTML = `<p class="text-center text-gray-500 py-6">Giỏ hàng của bạn đang trống.</p>`;
                totalEl.textContent = '0₫';
                return;
            }

            let total = 0;
            container.innerHTML = cart.map(item => {
                const sub = item.price * item.qty;
                total += sub;
                return `
                    <div class="flex items-center justify-between gap-2 p-2 rounded-lg bg-gray-50 border border-gray-100">
                        <div class="min-w-0 flex-1">
                            <p class="font-bold text-gray-800 leading-snug">${item.name}</p>
                            <p class="text-red-600 font-semibold mt-0.5">${formatCurrency(item.price)} x ${item.qty}</p>
                        </div>
                        <button onclick="removeFromCart(${item.id})" class="text-gray-400 hover:text-red-600 px-2 py-1">
                            <i class="fa-solid fa-trash-can"></i>
                        </button>
                    </div>
                `;
            }).join('');

            totalEl.textContent = formatCurrency(total);
        }

        function removeFromCart(productId) {
            cart = cart.filter(item => item.id !== productId);
            updateCartUI();
        }

        function openCartModal() {
            updateCartUI();
            document.getElementById('cartModal').classList.remove('hidden');
        }

        function closeCartModal() {
            document.getElementById('cartModal').classList.add('hidden');
        }

        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        function prefillProductQuote(productName) {
            const noteEl = document.getElementById('quoteNote');
            noteEl.value = `Tôi muốn đặt / nhận tư vấn mẫu: ${productName}`;
            showToast('Đã chọn sản phẩm vào Form Yêu Cầu & Báo Giá bên dưới!');
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const cat = document.getElementById('quoteCategory').value;
            const budget = document.getElementById('quoteBudget').value.trim();

            showToast(`Cảm ơn ${name}! Minh Toàn Fruits sẽ liên hệ SĐT ${phone} ngay.`);
            document.getElementById('quoteRequestForm').reset();
        }

        // Khởi tạo giao diện khi tải trang
        window.onload = function () {
            renderProducts(productsData);
            renderGiftBasketsSection();
            updateCartUI();
            resetBannerTimer();
        };
    </script>
</body>
</html>
