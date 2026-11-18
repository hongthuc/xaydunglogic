<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - xaydunglogic.com</title>
    <meta name="description" content="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - Chuyên Thiết kế Kiến trúc, Thi công phần thô, Thi công hoàn thiện, Xây nhà trọn gói Biệt thự, Nhà phố, Khách sạn, Căn hộ tại Đà Nẵng. Hotline: 0986.642.634">
    <link rel="canonical" href="https://xaydunglogic.com/">

    <!-- Open Graph / Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://xaydunglogic.com/">
    <meta property="og:site_name" content="xaydunglogic.com">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - Thiết Kế & Thi Công Trọn Gói Đà Nẵng">
    <meta property="og:description" content="Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên Thiết kế Kiến trúc – Nội thất, Thi công phần thô, Thi công hoàn thiện Nhà phố, Biệt thự, Căn hộ, Văn phòng. Địa chỉ: Lô 24 B1.22 KĐT Sinh thái Hòa Xuân, TP Đà Nẵng. ĐT: 0986.642.634">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="600">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - xaydunglogic.com">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800">

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        logic: {
                            navy: '#0c264e',
                            blue: '#163d7a',
                            light: '#eef4fb',
                            gold: '#d97706',
                            amber: '#f59e0b',
                            dark: '#071733'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1e293b;
            background-color: #f8fafc;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn Flatsome: Rộng 95% màn hình trên máy tính */
        .flatsome-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (max-width: 767px) {
            .flatsome-container {
                width: 96%;
                max-width: 96%;
                padding-left: 6px;
                padding-right: 6px;
            }
        }

        /* Menu danh mục trên máy tính: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng */
        .nav-single-line {
            display: flex;
            align-items: center;
            justify-content: flex-end;
            flex-wrap: nowrap;
            gap: 2px;
            overflow: visible;
        }
        .nav-item-link {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 0.01em;
            padding: 8px 9px;
            color: #0c264e;
            border-radius: 6px;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .nav-item-link {
                font-size: 12.5px;
                padding: 8px 11px;
            }
        }
        .nav-item-link:hover, .nav-item-link.active {
            color: #d97706;
            background-color: #f1f5f9;
        }

        /* Dropdown Submenu chuẩn Flatsome */
        .has-dropdown {
            position: relative;
        }
        .nav-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            border-top: 3px solid #d97706;
            box-shadow: 0 10px 25px rgba(12, 38, 78, 0.14);
            border-radius: 0 0 8px 8px;
            padding: 6px 0;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }
        .has-dropdown:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .nav-dropdown a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 600;
            color: #1e293b;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .nav-dropdown a:last-child {
            border-bottom: none;
        }
        .nav-dropdown a:hover {
            background-color: #eef4fb;
            color: #d97706;
            padding-left: 18px;
        }

        /* Nút danh mục nhỏ gọn ở trang chủ (Filter Tabs) - không xuống dòng chữ danh mục */
        .cat-tab-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 6px;
        }
        .cat-tab-btn {
            white-space: nowrap !important;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background-color: #ffffff;
            color: #0c264e;
            transition: all 0.2s ease;
            cursor: pointer;
            line-height: 1.3;
        }
        .cat-tab-btn:hover, .cat-tab-btn.active {
            background-color: #0c264e;
            color: #ffffff;
            border-color: #0c264e;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 14px;
            text-align: center;
        }
        .flatsome-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #cbd5e1;
            max-width: 120px;
        }
        .flatsome-section-title span {
            padding: 0 16px;
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
            color: #0c264e;
            letter-spacing: 0.02em;
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối */
        .banner-slider-wrapper {
            position: relative;
            width: 100%;
            height: 360px;
            overflow: hidden;
            border-radius: 10px;
            background-color: #071733;
        }
        @media (min-width: 640px) {
            .banner-slider-wrapper {
                height: 400px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slider-wrapper {
                height: 460px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Box Sản phẩm / Công trình chuẩn UX Builder Flatsome */
        .ux-box-card {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
        }
        .ux-box-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(12, 38, 78, 0.1);
            border-color: #cbd5e1;
        }
        .ux-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #e2e8f0;
        }
        .ux-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
        }
        .ux-box-card:hover .ux-box-image img {
            transform: scale(1.05);
        }
        .ux-box-text {
            padding: 10px 10px 12px 10px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            flex-grow: 1;
        }
        /* Tên sản phẩm không bị tràn hoặc thiếu chữ trên điện thoại và máy tính */
        .ux-product-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 700;
            color: #0c264e;
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .ux-box-text {
                padding: 12px 14px 14px 14px;
            }
            .ux-product-title {
                font-size: 14px;
            }
        }

        /* Nút liên hệ nổi bật cố định góc trái/phải */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- =====================================================================
         FLATSOME HEADER WRAPPER (#header)
         - Không có thanh công cụ UX Builder ở trên cùng
         - Không để nút "Gọi ngay" trên Header tránh tràn viền
         - Logo chỉnh gọn nhỏ lại
         - Danh mục trên máy tính nằm gọn trên 1 hàng, không xuống dòng
    ====================================================================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-50 border-b border-slate-200">
        
        <!-- Top Bar (#top-bar) -->
        <div id="top-bar" class="bg-logic-navy text-white py-1.5 text-[11px] sm:text-xs">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 truncate">
                    <span class="font-semibold text-amber-400">
                        <i class="fa-solid fa-building mr-1"></i>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC
                    </span>
                    <span class="hidden lg:inline-block text-slate-300">|</span>
                    <span class="hidden lg:inline-block text-slate-200 truncate">
                        <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Lô 24 B1.22 KĐT Sinh thái Hòa Xuân, Phường Hòa Xuân, TP Đà Nẵng
                    </span>
                </div>
                <div class="flex items-center gap-3 shrink-0 ml-auto">
                    <a href="https://xaydunglogic.com" class="hover:text-amber-400 transition hidden sm:inline-block">
                        <i class="fa-solid fa-globe text-amber-400 mr-1"></i>xaydunglogic.com
                    </a>
                    <span class="hidden sm:inline-block text-slate-400">|</span>
                    <a href="tel:0986642634" class="font-bold text-amber-400 hover:text-amber-300 transition">
                        <i class="fa-solid fa-phone-volume mr-1"></i>0986.642.634
                    </a>
                </div>
            </div>
        </div>

        <!-- Main Header (#masthead) - Không có nút Gọi Ngay để tránh tràn viền -->
        <div id="masthead" class="py-2 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-2">
                
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group py-0.5" title="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-logic-navy flex flex-col items-center justify-center border-2 border-logic-gold shadow-sm shrink-0">
                        <svg class="w-5 h-5 text-amber-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M3 21h18M5 21V7l7-4 7 4v14M9 21v-6h6v6" />
                        </svg>
                        <span class="text-[7px] font-extrabold tracking-widest text-white leading-none mt-0.5">LOGIC</span>
                    </div>
                    <div class="leading-tight">
                        <div class="font-heading font-extrabold text-logic-navy text-xs sm:text-sm tracking-tight">
                            XÂY DỰNG <span class="text-logic-gold">LOGIC</span>
                        </div>
                        <div class="text-[9.5px] sm:text-[10px] text-slate-500 font-medium">
                            xaydunglogic.com
                        </div>
                    </div>
                </a>

                <!-- Menu Danh Mục Máy Tính: 1 Hàng Duy Nhất, Chữ Nhỏ Gọn, Không Xuống Dòng -->
                <nav class="hidden lg:flex items-center flex-1 justify-end" aria-label="Menu chính">
                    <ul class="nav-single-line m-0 p-0 list-none">
                        <li>
                            <a href="#trang-chu" class="nav-item-link active">TRANG CHỦ</a>
                        </li>
                        <li>
                            <a href="#gioi-thieu" class="nav-item-link">GIỚI THIỆU</a>
                        </li>
                        <li class="has-dropdown">
                            <a href="#cong-trinh-thuc-te" class="nav-item-link">
                                CÔNG TRÌNH THỰC TẾ <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')">Văn phòng</a>
                            </div>
                        </li>
                        <li class="has-dropdown">
                            <a href="#linh-vuc-hoat-dong" class="nav-item-link">
                                LĨNH VỰC HOẠT ĐỘNG <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                            </div>
                        </li>
                        <li>
                            <a href="#du-an-da-nang" class="nav-item-link">DỰ ÁN ĐÀ NẴNG</a>
                        </li>
                        <li class="has-dropdown">
                            <a href="#mau-thiet-ke" class="nav-item-link">
                                MẪU THIẾT KẾ <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#mau-thiet-ke">Mẫu thiết kế nhà phố</a>
                                <a href="#mau-thiet-ke">Mẫu thiết kế biệt thự</a>
                                <a href="#mau-thiet-ke">Mẫu thiết kế nội thất</a>
                            </div>
                        </li>
                        <li class="has-dropdown">
                            <a href="#bao-gia" class="nav-item-link">
                                BÁO GIÁ <i class="fa-solid fa-chevron-down text-[9px] opacity-75"></i>
                            </a>
                            <div class="nav-dropdown">
                                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia">Báo giá thi công phần thô</a>
                                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia">Báo giá thi công trọn gói</a>
                            </div>
                        </li>
                        <li>
                            <a href="#doi-tac" class="nav-item-link">ĐỐI TÁC</a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="nav-item-link">TIN TỨC</a>
                        </li>
                        <li>
                            <a href="#lien-he" class="nav-item-link">LIÊN HỆ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại / Máy Tính Bảng -->
                <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center p-2 rounded-md text-logic-navy hover:bg-slate-100 border border-slate-200 focus:outline-none" aria-label="Mở danh mục">
                    <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                    <span class="ml-1.5 text-xs font-bold">DANH MỤC</span>
                </button>
            </div>

            <!-- Thanh Danh Mục Nhanh Trên Điện Thoại (Vuốt ngang gọn đẹp, chữ nằm trên 1 hàng) -->
            <div class="lg:hidden border-t border-slate-100 mt-2 pt-1.5">
                <div class="flatsome-container flex items-center gap-1.5 overflow-x-auto pb-1 no-scrollbar">
                    <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Công trình thực tế</a>
                    <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Lĩnh vực hoạt động</a>
                    <a href="#du-an-da-nang" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Dự án Đà Nẵng</a>
                    <a href="#bao-gia" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Báo giá xây dựng</a>
                    <a href="#doi-tac" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Đối tác</a>
                    <a href="#tin-tuc" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Tin tức</a>
                    <a href="#lien-he" class="whitespace-nowrap text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-logic-navy hover:bg-logic-navy hover:text-white transition">Bản đồ & Liên hệ</a>
                </div>
            </div>
        </div>

        <!-- Drawer Menu Điện Thoại (Hiển thị đầy đủ danh mục con giống web mẫu) -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 divide-y divide-slate-100 text-xs font-semibold text-logic-navy">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">TRANG CHỦ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">GIỚI THIỆU CÔNG TY LOGIC</a>
                <div class="py-2.5">
                    <div class="font-bold text-logic-gold mb-1.5">CÔNG TRÌNH THỰC TẾ</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-slate-700">
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san'); toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu'); toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Biệt thự cao cấp</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho'); toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Nhà phố hiện đại</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong'); toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Văn phòng công ty</a>
                    </div>
                </div>
                <div class="py-2.5">
                    <div class="font-bold text-logic-gold mb-1.5">LĨNH VỰC HOẠT ĐỘNG</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-slate-700">
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Thiết kế Kiến trúc</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Thi công phần thô</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Thi công hoàn thiện</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-logic-gold">• Thi công nội thất</a>
                    </div>
                </div>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</a>
                <a href="#bao-gia" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">BÁO GIÁ THIẾT KẾ & THI CÔNG</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">ĐỐI TÁC CHIẾN LƯỢC</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">TIN TỨC & KINH NGHIỆM</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="block py-2.5 hover:text-logic-gold">LIÊN HỆ & BẢN ĐỒ</a>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         MAIN CONTENT (#main) - Cấu trúc UX Builder Flatsome (section > row > col)
    ====================================================================== -->
    <main id="main">

        <!-- SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             - Hình ảnh và chữ nằm gọn bên trong banner
             - Chữ cách xa viền ảnh banner (padding rộng rãi)
             - Không bị thiếu chữ hay cắt chữ trên cả điện thoại và máy tính -->
        <section id="trang-chu" class="py-3 sm:py-4">
            <div class="flatsome-container">
                <div class="banner-slider-wrapper shadow-md">
                    
                    <!-- SLIDE 1 -->
                    <div class="banner-slide active" data-slide="0">
                        <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                             onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=1600&q=80';"
                             alt="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - Banner 1"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-r from-logic-dark/90 via-logic-navy/80 to-logic-navy/55"></div>
                        
                        <!-- Nội dung chữ cách xa viền banner (px-8 sm:px-16 md:px-24 py-8 sm:py-12) -->
                        <div class="absolute inset-0 flex items-center justify-between px-8 sm:px-16 md:px-24 py-8 sm:py-12">
                            <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3">
                                <p class="text-amber-400 font-bold text-[11px] sm:text-xs md:text-sm uppercase tracking-wider">
                                    CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC
                                </p>
                                <h1 class="font-heading font-extrabold text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug text-white">
                                    THIẾT KẾ & THI CÔNG XÂY DỰNG TRỌN GÓI UY TÍN TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed max-w-xl">
                                    Chuyên Thiết kế Kiến trúc – Thi công Phần thô – Hoàn thiện Nội thất Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng với cam kết: An toàn – Chất lượng – Đúng tiến độ.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5 text-[11px] sm:text-xs text-amber-300 font-medium">
                                    <span><i class="fa-solid fa-phone mr-1"></i>Hotline: 0986.642.634</span>
                                    <span>•</span>
                                    <span><i class="fa-solid fa-globe mr-1"></i>xaydunglogic.com</span>
                                </div>
                                <div class="pt-1 flex flex-wrap gap-2.5">
                                    <a href="#bao-gia" class="bg-logic-gold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded-md transition shadow">
                                        NHẬN BÁO GIÁ MIỄN PHÍ
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded-md transition">
                                        XEM CÔNG TRÌNH THỰC TẾ
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh thực tế nằm gọn bên trong banner trên màn hình lớn -->
                            <div class="hidden lg:block lg:w-4/12">
                                <div class="bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-lg">
                                    <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                                         onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80';"
                                         alt="Thi công thực tế Xây Dựng Logic"
                                         class="w-full h-52 object-cover rounded-lg">
                                    <div class="text-center text-white text-xs font-semibold pt-2">
                                        Công trình thực tế tại KĐT Sinh thái Hòa Xuân, Đà Nẵng
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
                    <div class="banner-slide" data-slide="1">
                        <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1600"
                             onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1600&q=80';"
                             alt="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - Banner 2"
                             class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-r from-logic-dark/90 via-logic-navy/80 to-logic-navy/55"></div>

                        <!-- Nội dung chữ cách xa viền banner (px-8 sm:px-16 md:px-24 py-8 sm:py-12) -->
                        <div class="absolute inset-0 flex items-center justify-between px-8 sm:px-16 md:px-24 py-8 sm:py-12">
                            <div class="w-full lg:w-7/12 text-white space-y-2 sm:space-y-3">
                                <p class="text-amber-400 font-bold text-[11px] sm:text-xs md:text-sm uppercase tracking-wider">
                                    GIẢI PHÁP KIẾN TRÚC & KẾT CẤU BỀN VỮNG
                                </p>
                                <h2 class="font-heading font-extrabold text-base sm:text-2xl md:text-3xl lg:text-4xl leading-snug text-white">
                                    CHUẨN MỰC KỸ THUẬT – TỐI ƯU CHI PHÍ – BẢO HÀNH DÀI HẠN
                                </h2>
                                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed max-w-xl">
                                    Đội ngũ Kiến trúc sư, Kỹ sư xây dựng giàu kinh nghiệm trực tiếp giám sát thi công tại Đà Nẵng & miền Trung. Vật tư chính hãng, minh bạch từng hạng mục.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5 text-[11px] sm:text-xs text-amber-300 font-medium">
                                    <span><i class="fa-solid fa-location-dot mr-1"></i>Lô 24 B1.22 KĐT Sinh thái Hòa Xuân, TP Đà Nẵng</span>
                                </div>
                                <div class="pt-1 flex flex-wrap gap-2.5">
                                    <a href="#du-an-da-nang" class="bg-logic-gold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded-md transition shadow">
                                        DỰ ÁN TẠI ĐÀ NẴNG
                                    </a>
                                    <a href="#lien-he" class="bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 py-2 sm:px-5 sm:py-2.5 rounded-md transition">
                                        LIÊN HỆ TƯ VẤN NGAY
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh thực tế nằm gọn bên trong banner trên màn hình lớn -->
                            <div class="hidden lg:block lg:w-4/12">
                                <div class="bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-lg">
                                    <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
                                         onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80';"
                                         alt="Giám sát thi công Xây Dựng Logic"
                                         class="w-full h-52 object-cover rounded-lg">
                                    <div class="text-center text-white text-xs font-semibold pt-2">
                                        Thi công kết cấu vững chắc – Giám sát 24/7
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng Trước / Sau -->
                    <button type="button" onclick="prevBanner()" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-logic-gold text-white flex items-center justify-center transition" aria-label="Slide trước">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button type="button" onclick="nextBanner()" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-logic-gold text-white flex items-center justify-center transition" aria-label="Slide tiếp theo">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo Slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToBanner(0)" class="banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Banner 1"></button>
                        <button type="button" onclick="goToBanner(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (Giống bố cục web mẫu tintruongthinh.com) -->
        <section id="linh-vuc-hoat-dong" class="py-6 sm:py-8 bg-white border-y border-slate-200">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">LĨNH VỰC HOẠT ĐỘNG TIÊU BIỂU</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
                    Cung cấp giải pháp khép kín từ Tư vấn Thiết kế Kiến trúc, Thi công phần thô, Thi công hoàn thiện đến Nội thất trọn gói theo tiêu chuẩn chất lượng cao.
                </p>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Dịch vụ 1 -->
                    <div class="ux-box-card">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80';"
                                 alt="Thiết kế Kiến trúc – Nội thất">
                        </div>
                        <div class="ux-box-text text-center">
                            <div>
                                <h3 class="ux-product-title">Thiết Kế Kiến Trúc – Nội Thất</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Hồ sơ bản vẽ kiến trúc, kết cấu, phối cảnh 3D tối ưu công năng và phong thủy cho Nhà phố, Biệt thự, Khách sạn.
                                </p>
                            </div>
                            <a href="#bao-gia" class="mt-2.5 inline-block text-xs font-bold text-logic-gold hover:underline">
                                Xem chi tiết & Báo giá →
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 2 -->
                    <div class="ux-box-card">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80';"
                                 alt="Thi công phần thô">
                        </div>
                        <div class="ux-box-text text-center">
                            <div>
                                <h3 class="ux-product-title">Thi Công Phần Thô & Nhân Công Hoàn Thiện</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Thi công nền móng, khung bê tông cốt thép, xây tô và hệ thống điện nước âm tường chuẩn quy phạm kỹ thuật.
                                </p>
                            </div>
                            <a href="#bao-gia" class="mt-2.5 inline-block text-xs font-bold text-logic-gold hover:underline">
                                Xem chi tiết & Báo giá →
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 3 -->
                    <div class="ux-box-card">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80';"
                                 alt="Thi công hoàn thiện">
                        </div>
                        <div class="ux-box-text text-center">
                            <div>
                                <h3 class="ux-product-title">Thi Công Xây Nhà Trọn Gói – Hoàn Thiện</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Giải pháp chìa khóa trao tay từ xin phép xây dựng, thi công thô đến hoàn thiện ốp lát, sơn bả, cửa và thiết bị.
                                </p>
                            </div>
                            <a href="#bao-gia" class="mt-2.5 inline-block text-xs font-bold text-logic-gold hover:underline">
                                Xem chi tiết & Báo giá →
                            </a>
                        </div>
                    </div>

                    <!-- Dịch vụ 4 -->
                    <div class="ux-box-card">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80';"
                                 alt="Thi công nội thất">
                        </div>
                        <div class="ux-box-text text-center">
                            <div>
                                <h3 class="ux-product-title">Sản Xuất & Thi Công Nội Thất Trọn Gói</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Thi công nội thất gỗ công nghiệp An Cường, gỗ tự nhiên cao cấp cho Phòng khách, Bếp, Phòng ngủ, Văn phòng.
                                </p>
                            </div>
                            <a href="#bao-gia" class="mt-2.5 inline-block text-xs font-bold text-logic-gold hover:underline">
                                Xem chi tiết & Báo giá →
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỐT LÕI (Theo cấu trúc Tín Trường Thịnh) -->
        <section id="gioi-thieu" class="py-7 sm:py-9 bg-slate-50">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-6 rounded-xl border border-slate-200 shadow-sm">
                    <div class="lg:col-span-7 space-y-3">
                        <div class="text-xs font-bold text-logic-gold uppercase tracking-wider">
                            VỀ CHÚNG TÔI • XAYDUNGLOGIC.COM
                        </div>
                        <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-logic-navy leading-snug">
                            CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                            <strong>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC</strong> (Mã số thuế: <strong>0401798273</strong>) có trụ sở tại <strong>Lô 24 B1.22 Khu đô thị Sinh thái Hòa Xuân, Phường Hòa Xuân, TP Đà Nẵng</strong>, là đơn vị chuyên nghiệp trong lĩnh vực Tư vấn Thiết kế Kiến trúc – Thi công Xây dựng – Hoàn thiện Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng và Nhà phố tại Đà Nẵng và khu vực miền Trung.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                            Với phương châm <strong>“Tư Duy Logic – Kết Cấu Vững Bền – Kiến Tạo Tổ Ấm Hoàn Hảo”</strong>, chúng tôi luôn đặt chữ “TÂM” và chữ “TÍN” lên hàng đầu để mỗi công trình bàn giao đều đạt chuẩn: <strong>An Toàn – Chất Lượng – Đúng Tiến Độ – Tối Ưu Chi Phí</strong>.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-2">
                            <div class="bg-logic-light p-3 rounded-lg border border-slate-200">
                                <div class="font-heading font-extrabold text-lg sm:text-xl text-logic-navy">10+ Năm</div>
                                <div class="text-[11px] sm:text-xs text-slate-600">Kinh nghiệm thực chiến</div>
                            </div>
                            <div class="bg-logic-light p-3 rounded-lg border border-slate-200">
                                <div class="font-heading font-extrabold text-lg sm:text-xl text-logic-navy">250+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600">Công trình tại Đà Nẵng</div>
                            </div>
                            <div class="bg-logic-light p-3 rounded-lg border border-slate-200 col-span-2 sm:col-span-1">
                                <div class="font-heading font-extrabold text-lg sm:text-xl text-logic-gold">Bảo Hành 5 Năm</div>
                                <div class="text-[11px] sm:text-xs text-slate-600">Kết cấu công trình</div>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5">
                        <div class="grid grid-cols-2 gap-2.5">
                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=600&q=80';"
                                 alt="Thi công thực tế Xây Dựng Logic 1"
                                 class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w600"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=600&q=80';"
                                 alt="Thi công thực tế Xây Dựng Logic 2"
                                 class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi (Giống mẫu Tín Trường Thịnh) -->
                <div class="mt-6">
                    <div class="flatsome-section-title">
                        <b></b>
                        <span class="text-base sm:text-xl">THẾ MẠNH CỦA XÂY DỰNG LOGIC</span>
                        <b></b>
                    </div>
                    <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4 mt-4">
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-user-gear"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Đội ngũ Kiến trúc sư, Kỹ sư chuyên nghiệp</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư chỉ huy công trường giàu kinh nghiệm và thợ lành nghề.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-compass-drafting"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Cập nhật xu hướng kiến trúc hiện đại</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp không gian mở, thông gió chiếu sáng tự nhiên và vật liệu xây dựng thế hệ mới.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-clipboard-check"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Giám sát tiến độ chuẩn xác</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Báo cáo nhật ký thi công kèm hình ảnh thực tế hàng ngày giúp Chủ đầu tư theo dõi mọi lúc mọi nơi.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-shield-halved"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Bảo hành công trình lâu dài</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Bảo hành kết cấu lên đến 5 năm, bảo trì kỹ thuật tận tâm, hỗ trợ nhanh chóng khi khách hàng cần.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-Scale-balanced fa-scale-balanced"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Dự toán minh bạch – Không phát sinh</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Bóc tách khối lượng chi tiết từng hạng mục vật tư, cam kết chi phí hợp lý và không phát sinh.</p>
                            </div>
                        </div>
                        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex flex-col sm:flex-row items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-headset"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-xs sm:text-sm text-logic-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">Khảo sát thực tế tận nơi tại Đà Nẵng, tư vấn phương án mặt bằng và thủ tục cấp phép miễn phí.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: CÔNG TRÌNH THỰC TẾ & HÌNH ẢNH THI CÔNG XÂY DỰNG (9 FILE DRIVE NHÓM 1)
             - Lấy đúng 9 ảnh thực tế thi công xây dựng trong file Google Drive đã cung cấp
             - Danh mục giống web mẫu: Tất cả | Khách sạn - Căn hộ - Phòng trọ | Biệt thự | Nhà phố | Văn phòng
             - Chia 2 cột trên điện thoại, không để nhãn dán trên ảnh, tên sản phẩm hiển thị đầy đủ không thiếu chữ -->
        <section id="cong-trinh-thuc-te" class="py-7 sm:py-9 bg-white">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">CÔNG TRÌNH THỰC TẾ THI CÔNG XÂY DỰNG</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-4">
                    Hình ảnh thực tế hoạt động thi công phần thô, kết cấu và hoàn thiện các công trình Nhà phố, Biệt thự, Căn hộ, Văn phòng do Xây Dựng LOGIC trực tiếp triển khai.
                </p>

                <!-- Thanh chọn danh mục nhỏ gọn, chữ danh mục không bị rớt dòng -->
                <div class="cat-tab-list mb-5" id="construction-tabs">
                    <button type="button" onclick="filterConstruction('all')" data-cat="all" class="cat-tab-btn active">Tất cả công trình</button>
                    <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="cat-tab-btn">Nhà phố</button>
                    <button type="button" onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="cat-tab-btn">Biệt thự</button>
                    <button type="button" onclick="filterConstruction('khach-san')" data-cat="khach-san" class="cat-tab-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button type="button" onclick="filterConstruction('van-phong')" data-cat="van-phong" class="cat-tab-btn">Văn phòng</button>
                </div>

                <!-- Grid Sản Phẩm / Công Trình Thực Tế: 2 cột trên Điện Thoại (grid-cols-2), 3 cột trên Máy Tính -->
                <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    
                    <!-- Ảnh thực tế 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                    <article class="ux-box-card construction-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w800';"
                                 alt="Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng Khu Đô Thị Hòa Xuân">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Nhà phố</div>
                                <h3 class="ux-product-title">Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng Khu Đô Thị Hòa Xuân</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">Hòa Xuân, Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                    <article class="ux-box-card construction-item" data-category="biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800';"
                                 alt="Thi Công Phần Thô & Kết Cấu Khung Bê Tông Biệt Thự Phố Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Biệt thự</div>
                                <h3 class="ux-product-title">Thi Công Phần Thô & Kết Cấu Khung Bê Tông Biệt Thự Phố Đà Nẵng</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                    <article class="ux-box-card construction-item" data-category="khach-san">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800';"
                                 alt="Thi Công Xây Dựng Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn Mini">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Khách sạn – Căn hộ</div>
                                <h3 class="ux-product-title">Thi Công Xây Dựng Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn Mini</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                    <article class="ux-box-card construction-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800';"
                                 alt="Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Lệch Tầng Hiện Đại">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Nhà phố</div>
                                <h3 class="ux-product-title">Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Lệch Tầng Hiện Đại</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                    <article class="ux-box-card construction-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800';"
                                 alt="Nghiệm Thu Cốt Thép Dầm Sàn & Đổ Bê Tông Tươi Thương Phẩm">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Thi công phần thô</div>
                                <h3 class="ux-product-title">Nghiệm Thu Cốt Thép Dầm Sàn & Đổ Bê Tông Tươi Thương Phẩm</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                    <article class="ux-box-card construction-item" data-category="biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800';"
                                 alt="Thiết Kế & Thi Công Biệt Thự Hiện Đại 2 Mặt Tiền Khu Đô Thị">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Biệt thự</div>
                                <h3 class="ux-product-title">Thiết Kế & Thi Công Biệt Thự Hiện Đại 2 Mặt Tiền Khu Đô Thị</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                    <article class="ux-box-card construction-item" data-category="khach-san">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w800';"
                                 alt="Thi Công Xây Tường Gạch Tuynel & Lắp Đặt Hệ Thống Cơ Điện M&E">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Khách sạn – Căn hộ</div>
                                <h3 class="ux-product-title">Thi Công Xây Tường Gạch Tuynel & Lắp Đặt Hệ Thống Cơ Điện M&E</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                    <article class="ux-box-card construction-item" data-category="van-phong">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w800';"
                                 alt="Thiết Kế & Thi Công Tòa Nhà Văn Phòng Kết Hợp Nhà Ở Gia Đình">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Văn phòng</div>
                                <h3 class="ux-product-title">Thiết Kế & Thi Công Tòa Nhà Văn Phòng Kết Hợp Nhà Ở Gia Đình</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                    <!-- Ảnh thực tế 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                    <article class="ux-box-card construction-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w800';"
                                 alt="Thi Công Hoàn Thiện Nội Ngoại Thất Nhà Phố Cao Cấp Chìa Khóa Trao Tay">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-slate-500 mb-1">Danh mục: Nhà phố</div>
                                <h3 class="ux-product-title">Thi Công Hoàn Thiện Nội Ngoại Thất Nhà Phố Cao Cấp Chìa Khóa Trao Tay</h3>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                                <span class="text-slate-600">TP Đà Nẵng</span>
                                <a href="#bao-gia" class="font-bold text-logic-gold hover:underline">Báo giá</a>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- SECTION 5: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 FILE DRIVE NHÓM 2)
             - Hiển thị trọn vẹn 10 ảnh dự án ở Đà Nẵng từ 10 link Google Drive đã cung cấp
             - Chia 2 cột trên điện thoại, 5 cột trên màn hình lớn để cân đối vừa khít 10 dự án
             - Không gắn nhãn dán đè lên ảnh, tên dự án hiển thị đầy đủ -->
        <section id="du-an-da-nang" class="py-7 sm:py-9 bg-slate-50 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-4">
                    Tổng hợp các dự án Thiết kế & Thi công trọn gói tiêu biểu tại Khu đô thị Sinh thái Hòa Xuân, Nam Hòa Xuân, Hải Châu, Sơn Trà và Ngũ Hành Sơn – TP Đà Nẵng.
                </p>

                <!-- Thanh lọc Danh mục Dự án Đà Nẵng -->
                <div class="cat-tab-list mb-5" id="danang-tabs">
                    <button type="button" onclick="filterDaNang('all')" data-dncat="all" class="cat-tab-btn active">Tất cả dự án Đà Nẵng</button>
                    <button type="button" onclick="filterDaNang('hoa-xuan')" data-dncat="hoa-xuan" class="cat-tab-btn">KĐT Hòa Xuân & Cẩm Lệ</button>
                    <button type="button" onclick="filterDaNang('hai-chau')" data-dncat="hai-chau" class="cat-tab-btn">Hải Châu & Thanh Khê</button>
                    <button type="button" onclick="filterDaNang('son-tra')" data-dncat="son-tra" class="cat-tab-btn">Sơn Trà & Ngũ Hành Sơn</button>
                </div>

                <!-- Grid 10 Dự Án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên desktop -->
                <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">

                    <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                    <article class="ux-box-card danang-item" data-dncategory="hoa-xuan">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800';"
                                 alt="Dự Án Nhà Phố Hiện Đại Khu Đô Thị Sinh Thái Hòa Xuân – Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">P. Hòa Xuân, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Nhà Phố Hiện Đại Khu Đô Thị Sinh Thái Hòa Xuân – Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                    <article class="ux-box-card danang-item" data-dncategory="son-tra">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800';"
                                 alt="Dự Án Biệt Thự Nghỉ Dưỡng Cao Cấp Ven Sông Hàn – Sơn Trà, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Q. Sơn Trà, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Biệt Thự Nghỉ Dưỡng Cao Cấp Ven Sông Hàn – Sơn Trà, Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                    <article class="ux-box-card danang-item" data-dncategory="son-tra">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz=w800';"
                                 alt="Dự Án Căn Hộ Cho Thuê & Khách Sạn Phố Biển Mỹ Khê – Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Biển Mỹ Khê, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Căn Hộ Cho Thuê & Khách Sạn Phố Biển Mỹ Khê – Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                    <article class="ux-box-card danang-item" data-dncategory="hoa-xuan">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800';"
                                 alt="Dự Án Biệt Thự 2 Mặt Tiền Khu Đảo VIP Hòa Xuân – TP Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Đảo VIP Hòa Xuân, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Biệt Thự 2 Mặt Tiền Khu Đảo VIP Hòa Xuân – TP Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                    <article class="ux-box-card danang-item" data-dncategory="hai-chau">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N=w800';"
                                 alt="Dự Án Tòa Nhà Văn Phòng & Showroom Thương Mại Hải Châu – Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Q. Hải Châu, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Tòa Nhà Văn Phòng & Showroom Thương Mại Hải Châu – Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                    <article class="ux-box-card danang-item" data-dncategory="son-tra">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML=w800';"
                                 alt="Dự Án Nhà Phố 4 Tầng Khu Đô Thị Nam Việt Á – Ngũ Hành Sơn, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Nam Việt Á, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Nhà Phố 4 Tầng Khu Đô Thị Nam Việt Á – Ngũ Hành Sơn, Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                    <article class="ux-box-card danang-item" data-dncategory="son-tra">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF=w800';"
                                 alt="Dự Án Tổ Hợp Căn Hộ Dịch Vụ Khu Phố Tây An Thượng – Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">An Thượng, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Tổ Hợp Căn Hộ Dịch Vụ Khu Phố Tây An Thượng – Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                    <article class="ux-box-card danang-item" data-dncategory="hoa-xuan">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A=w800';"
                                 alt="Dự Án Biệt Thự Sân Vườn Khu Đô Thị Nam Hòa Xuân – TP Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Nam Hòa Xuân, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Biệt Thự Sân Vườn Khu Đô Thị Nam Hòa Xuân – TP Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                    <article class="ux-box-card danang-item" data-dncategory="hai-chau">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80=w800';"
                                 alt="Dự Án Nhà Phố Kết Hợp Kinh Doanh Đường Nguyễn Hữu Thọ – Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Q. Hải Châu, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Nhà Phố Kết Hợp Kinh Doanh Đường Nguyễn Hữu Thọ – Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                    <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                    <article class="ux-box-card danang-item" data-dncategory="hai-chau">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4=w800';"
                                 alt="Dự Án Thi Công Hoàn Thiện Biệt Thự Phố Hòa Cường – TP Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Hòa Cường, Đà Nẵng</div>
                                <h3 class="ux-product-title">Dự Án Thi Công Hoàn Thiện Biệt Thự Phố Hòa Cường – TP Đà Nẵng</h3>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- SECTION 6: MẪU THIẾT KẾ & BẢNG BÁO GIÁ THAM KHẢO (Lấy danh mục từ web mẫu tintruongthinh.com) -->
        <section id="mau-thiet-ke" class="py-7 sm:py-9 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">BẢNG BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
                    Đơn giá minh bạch theo từng gói dịch vụ tại Đà Nẵng. Liên hệ trực tiếp Hotline <strong>0986.642.634</strong> để nhận bảng bóc tách dự toán chi tiết theo diện tích thực tế.
                </p>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="text-xs font-bold text-logic-gold uppercase mb-1">Gói Thiết Kế</div>
                            <h3 class="ux-product-title text-sm sm:text-base">Báo Giá Thiết Kế Kiến Trúc & Nội Thất</h3>
                            <div class="my-2.5 font-heading font-extrabold text-base sm:text-xl text-logic-navy">
                                120.000đ - 180.000đ/m²
                            </div>
                            <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                                <li>• Bản vẽ kiến trúc & phối cảnh 3D</li>
                                <li>• Hồ sơ kết cấu & điện nước M&E</li>
                                <li>• Hồ sơ xin cấp phép xây dựng</li>
                                <li>• Giảm 50% - 100% khi ký HĐ thi công</li>
                            </ul>
                        </div>
                        <a href="#bao-gia" class="w-full text-center py-2 rounded bg-logic-navy hover:bg-logic-gold text-white font-bold text-xs transition">
                            Đăng ký nhận báo giá
                        </a>
                    </div>

                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="text-xs font-bold text-logic-gold uppercase mb-1">Gói Phần Thô</div>
                            <h3 class="ux-product-title text-sm sm:text-base">Báo Giá Thi Công Phần Thô & Nhân Công</h3>
                            <div class="my-2.5 font-heading font-extrabold text-base sm:text-xl text-logic-navy">
                                3.500.000đ - 3.900.000đ/m²
                            </div>
                            <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                                <li>• Sắt thép Hòa Phát, Xi măng Hà Tiên</li>
                                <li>• Gạch Tuynel, Cát đá đúng tiêu chuẩn</li>
                                <li>• Hệ thống ống nước Bình Minh, điện Cadivi</li>
                                <li>• Nhân công hoàn thiện xây tô, ốp lát</li>
                            </ul>
                        </div>
                        <a href="#bao-gia" class="w-full text-center py-2 rounded bg-logic-navy hover:bg-logic-gold text-white font-bold text-xs transition">
                            Đăng ký nhận báo giá
                        </a>
                    </div>

                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="text-xs font-bold text-logic-gold uppercase mb-1">Gói Hoàn Thiện</div>
                            <h3 class="ux-product-title text-sm sm:text-base">Báo Giá Thi Công Hoàn Thiện Công Trình</h3>
                            <div class="my-2.5 font-heading font-extrabold text-base sm:text-xl text-logic-navy">
                                2.200.000đ - 3.200.000đ/m²
                            </div>
                            <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                                <li>• Gạch ốp lát, đá Granite cầu thang</li>
                                <li>• Sơn nước Dulux / Jotun chính hãng</li>
                                <li>• Cửa nhôm Xingfa, lan can kính cường lực</li>
                                <li>• Thiết bị vệ sinh Inax / Toto đồng bộ</li>
                            </ul>
                        </div>
                        <a href="#bao-gia" class="w-full text-center py-2 rounded bg-logic-navy hover:bg-logic-gold text-white font-bold text-xs transition">
                            Đăng ký nhận báo giá
                        </a>
                    </div>

                    <div class="bg-slate-50 rounded-xl p-4 border border-slate-200 flex flex-col justify-between">
                        <div>
                            <div class="text-xs font-bold text-logic-gold uppercase mb-1">Chìa Khóa Trao Tay</div>
                            <h3 class="ux-product-title text-sm sm:text-base">Báo Giá Xây Nhà Trọn Gói Tại Đà Nẵng</h3>
                            <div class="my-2.5 font-heading font-extrabold text-base sm:text-xl text-logic-navy">
                                5.600.000đ - 6.800.000đ/m²
                            </div>
                            <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-3">
                                <li>• Miễn phí 100% hồ sơ thiết kế & GPXD</li>
                                <li>• Quản lý vật tư & giám sát kỹ thuật 24/7</li>
                                <li>• Cam kết không phát sinh chi phí</li>
                                <li>• Bảo hành kết cấu 5 năm, chống thấm 2 năm</li>
                            </ul>
                        </div>
                        <a href="#bao-gia" class="w-full text-center py-2 rounded bg-logic-navy hover:bg-logic-gold text-white font-bold text-xs transition">
                            Đăng ký nhận báo giá
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 7: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (Giống mẫu MIỄN PHÍ TƯ VẤN tintruongthinh.com) -->
        <section id="bao-gia" class="py-8 sm:py-10 bg-logic-navy text-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    
                    <!-- Cột thông tin cam kết báo giá -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="text-amber-400 font-bold text-xs uppercase tracking-wider">
                            ĐĂNG KÝ NHẬN TƯ VẤN & DỰ TOÁN MIỄN PHÍ
                        </div>
                        <h2 class="font-heading font-extrabold text-lg sm:text-2xl leading-snug text-white">
                            YÊU CẦU TƯ VẤN & BÁO GIÁ XÂY DỰNG TRỌN GÓI
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Quý khách hàng đang có kế hoạch xây dựng Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn hoặc Văn phòng tại Đà Nẵng? Hãy để lại thông tin, Kỹ sư trưởng của <strong>Xây Dựng LOGIC</strong> sẽ liên hệ tư vấn mặt bằng và gửi bảng báo giá chi tiết trong vòng 30 phút.
                        </p>
                        <div class="space-y-2 pt-2 text-xs sm:text-sm text-slate-100">
                            <div><i class="fa-solid fa-check text-amber-400 mr-2"></i>Khảo sát hiện trạng & tư vấn thiết kế miễn phí 100%</div>
                            <div><i class="fa-solid fa-check text-amber-400 mr-2"></i>Báo giá chi tiết từng chủng loại vật tư thô & hoàn thiện</div>
                            <div><i class="fa-solid fa-check text-amber-400 mr-2"></i>Hỗ trợ thủ tục xin phép xây dựng & hoàn công tại Đà Nẵng</div>
                        </div>
                        <div class="pt-3 border-t border-white/15 flex flex-wrap items-center gap-4 text-xs sm:text-sm">
                            <div>
                                <span class="text-slate-300 block text-[11px]">Hotline Tư Vấn Trực Tiếp:</span>
                                <a href="tel:0986642634" class="font-heading font-extrabold text-amber-400 text-base sm:text-lg">0986.642.634</a>
                            </div>
                            <div>
                                <span class="text-slate-300 block text-[11px]">Trụ sở tại Đà Nẵng:</span>
                                <span class="font-semibold text-white text-xs">Lô 24 B1.22 KĐT Sinh thái Hòa Xuân</span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá -->
                    <div class="lg:col-span-7">
                        <div class="bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-lg">
                            <h3 class="font-heading font-extrabold text-sm sm:text-lg text-logic-navy mb-3 uppercase text-center">
                                FORM YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                            </h3>
                            <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên *</label>
                                        <input type="text" id="q-name" required placeholder="Nhập họ tên của Quý khách" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-logic-navy">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại *</label>
                                        <input type="tel" id="q-phone" required placeholder="Ví dụ: 0986642634" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-logic-navy">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Loại công trình (Giống mẫu Tín Trường Thịnh)</label>
                                        <select id="q-type" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md bg-white focus:outline-none focus:border-logic-navy">
                                            <option value="Nhà phố">Nhà phố hiện đại</option>
                                            <option value="Biệt thự">Biệt thự phố / Biệt thự nghỉ dưỡng</option>
                                            <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                            <option value="Văn phòng">Văn phòng công ty / Showroom</option>
                                            <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa – Hoàn thiện</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                        <select id="q-budget" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md bg-white focus:outline-none focus:border-logic-navy">
                                            <option value="1 - 2 tỷ">Từ 1 – 2 tỷ</option>
                                            <option value="2 - 3 tỷ">Từ 2 – 3 tỷ</option>
                                            <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                            <option value="500 triệu - 1 tỷ">Từ 500 triệu – 1 tỷ</option>
                                            <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        </select>
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục yêu cầu</label>
                                        <select id="q-service" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md bg-white focus:outline-none focus:border-logic-navy">
                                            <option value="Xây nhà trọn gói - Chìa khóa trao tay">Xây nhà trọn gói (Chìa khóa trao tay)</option>
                                            <option value="Thi công phần thô & nhân công hoàn thiện">Thi công phần thô & nhân công hoàn thiện</option>
                                            <option value="Thiết kế Kiến trúc - Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                                            <option value="Thi công hoàn thiện & nội thất">Thi công hoàn thiện & nội thất</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Khu vực / Diện tích đất (m²)</label>
                                        <input type="text" id="q-area" placeholder="VD: Hòa Xuân, Đà Nẵng - 5x20m (3 tầng)" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-logic-navy">
                                    </div>
                                </div>

                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung ghi chú thêm</label>
                                    <textarea id="q-note" rows="2" placeholder="Nhập yêu cầu cụ thể về số tầng, công năng hoặc thời gian dự kiến khởi công..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-logic-navy"></textarea>
                                </div>

                                <button type="submit" class="w-full py-2.5 px-4 rounded-md bg-logic-gold hover:bg-amber-600 text-white font-heading font-bold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                                </button>
                            </form>

                            <!-- Hộp thông báo xác nhận ngay trên trang (Không dùng alert) -->
                            <div id="quote-success-box" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs sm:text-sm"></div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG) -->
        <section id="tin-tuc" class="py-7 sm:py-9 bg-white">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">TIN TỨC & CẨM NANG XÂY DỰNG</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-4">
                    Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm lựa chọn vật tư, bảo dưỡng bê tông và giải pháp tối ưu không gian sống từ đội ngũ Kỹ sư Xây Dựng LOGIC.
                </p>

                <!-- Danh mục bài viết trang chủ (Chữ nhỏ gọn, không xuống dòng) -->
                <div class="cat-tab-list mb-5" id="blog-tabs">
                    <button type="button" onclick="filterBlog('all')" data-bcat="all" class="cat-tab-btn active">Tất cả bài viết</button>
                    <button type="button" onclick="filterBlog('ky-thuat')" data-bcat="ky-thuat" class="cat-tab-btn">Kỹ thuật thi công</button>
                    <button type="button" onclick="filterBlog('kinh-nghiem')" data-bcat="kinh-nghiem" class="cat-tab-btn">Kinh nghiệm xây nhà</button>
                    <button type="button" onclick="filterBlog('kien-truc')" data-bcat="kien-truc" class="cat-tab-btn">Kiến trúc & Nội thất</button>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="blog-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    
                    <!-- Bài viết 1 -->
                    <article class="ux-box-card blog-item" data-bcategory="ky-thuat">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80';"
                                 alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng quy chuẩn kỹ thuật">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Kỹ thuật thi công</div>
                                <h3 class="ux-product-title">Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Quy Chuẩn Kỹ Thuật</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Trong quá trình thi công phần thô, việc giữ ẩm và bảo dưỡng bê tông móng, dầm sàn đúng cách quyết định trực tiếp đến cường độ chịu lực lâu dài.
                                </p>
                            </div>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article class="ux-box-card blog-item" data-bcategory="kinh-nghiem">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80';"
                                 alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần lưu ý">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Kinh nghiệm xây nhà</div>
                                <h3 class="ux-product-title">03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Nào Cũng Cần Biết</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Kiểm soát chi phí phát sinh, lựa chọn vật tư chính hãng và giám sát tiến độ thi công thực tế để ngôi nhà hoàn thiện đúng bản vẽ thiết kế.
                                </p>
                            </div>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article class="ux-box-card blog-item" data-bcategory="kien-truc">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80';"
                                 alt="Tâm lý học không gian: Thiết kế kiến trúc và nội thất tối ưu ánh sáng">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Kiến trúc & Nội thất</div>
                                <h3 class="ux-product-title">Giải Pháp Bố Trí Giếng Trời Và Thông Gió Cho Nhà Phố Tại Đà Nẵng</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Cách tổ chức không gian thông tầng, giếng trời và vật liệu cách nhiệt giúp nhà phố hướng Tây tại Đà Nẵng luôn thông thoáng, mát mẻ.
                                </p>
                            </div>
                        </div>
                    </article>

                    <!-- Bài viết 4 -->
                    <article class="ux-box-card blog-item" data-bcategory="kinh-nghiem">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
                                 onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80';"
                                 alt="Chứng chỉ năng lực hoạt động xây dựng và quy trình nghiệm thu">
                        </div>
                        <div class="ux-box-text">
                            <div>
                                <div class="text-[11px] font-semibold text-logic-gold mb-1">Kinh nghiệm xây nhà</div>
                                <h3 class="ux-product-title">Chứng Chỉ Năng Lực Hoạt Động Xây Dựng Và Quy Trình Nghiệm Thu</h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed">
                                    Tìm hiểu các tiêu chuẩn pháp lý, hồ sơ xin cấp phép xây dựng và các bước nghiệm thu từng giai đoạn từ móng đến mái tại Đà Nẵng.
                                </p>
                            </div>
                        </div>
                    </article>

                </div>
            </div>
        </section>

        <!-- SECTION 9: DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC & VẬT TƯ CHÍNH HÃNG) -->
        <section id="doi-tac" class="py-6 sm:py-8 bg-slate-50 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">ĐỐI TÁC & NHÀ CUNG CẤP VẬT TƯ</span>
                    <b></b>
                </div>
                <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
                    CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC hợp tác cùng các thương hiệu vật liệu xây dựng và trang thiết bị uy tín hàng đầu Việt Nam.
                </p>

                <!-- Chia 2 cột trên điện thoại, 6 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">THÉP HÒA PHÁT</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng tiêu chuẩn</div>
                    </div>
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">XI MĂNG HÀ TIÊN</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Bê tông & kết cấu bền vững</div>
                    </div>
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">SƠN DULUX / JOTUN</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Sơn chống thấm ngoại thất</div>
                    </div>
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">NHÔM XINGFA</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cao cấp</div>
                    </div>
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">TOTO / INAX</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh chính hãng</div>
                    </div>
                    <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
                        <div class="font-heading font-extrabold text-sm text-logic-navy">PANASONIC / CADIVI</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện & cáp chống cháy</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 10: ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="lien-he" class="py-7 sm:py-9 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="flatsome-section-title">
                    <b></b>
                    <span class="text-base sm:text-xl">THÔNG TIN LIÊN HỆ, FANPAGE & BẢN ĐỒ TRỤ SỞ</span>
                    <b></b>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 mt-4">
                    
                    <!-- Cột 1: Thông tin trụ sở chính thức -->
                    <div class="lg:col-span-4 bg-slate-50 p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                        <div class="space-y-3">
                            <div class="flex items-center gap-2.5">
                                <div class="w-9 h-9 rounded-lg bg-logic-navy text-amber-400 flex items-center justify-center font-heading font-extrabold text-xs">
                                    LOGIC
                                </div>
                                <div>
                                    <h3 class="font-heading font-extrabold text-xs sm:text-sm text-logic-navy">
                                        CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC
                                    </h3>
                                    <p class="text-[11px] text-slate-500">MST: 0401798273 • Website: xaydunglogic.com</p>
                                </div>
                            </div>

                            <div class="space-y-2.5 text-xs sm:text-sm text-slate-700 pt-2 border-t border-slate-200">
                                <p class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-logic-gold mt-1 shrink-0"></i>
                                    <span><strong>Địa chỉ trụ sở:</strong> Lô 24 B1.22 Khu đô thị Sinh thái Hòa Xuân, Phường Hòa Xuân, TP Đà Nẵng</span>
                                </p>
                                <p class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-logic-gold shrink-0"></i>
                                    <span><strong>Điện thoại / Hotline:</strong> <a href="tel:0986642634" class="font-bold text-logic-navy hover:text-logic-gold">0986.642.634</a></span>
                                </p>
                                <p class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-globe text-logic-gold shrink-0"></i>
                                    <span><strong>Website:</strong> <a href="https://xaydunglogic.com" class="font-semibold text-logic-navy hover:text-logic-gold">https://xaydunglogic.com</a></span>
                                </p>
                                <p class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-envelope text-logic-gold shrink-0"></i>
                                    <span><strong>Email:</strong> info@xaydunglogic.com</span>
                                </p>
                                <p class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-clock text-logic-gold shrink-0"></i>
                                    <span><strong>Giờ làm việc:</strong> Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
                                </p>
                            </div>
                        </div>

                        <div class="pt-4 mt-4 border-t border-slate-200 flex flex-wrap gap-2">
                            <a href="tel:0986642634" class="flex-1 text-center py-2 px-3 rounded bg-logic-navy text-white font-bold text-xs hover:bg-logic-blue transition">
                                <i class="fa-solid fa-phone mr-1"></i>0986.642.634
                            </a>
                            <a href="https://zalo.me/0986642634" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-sky-600 text-white font-bold text-xs hover:bg-sky-700 transition">
                                <i class="fa-solid fa-comment-dots mr-1"></i>Chat Zalo
                            </a>
                        </div>
                    </div>

                    <!-- Cột 2: Fanpage đưa ra ngoài trang chủ -->
                    <div class="lg:col-span-4 bg-slate-50 p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-logic-navy uppercase mb-3 flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-base"></i>FANPAGE CHÍNH THỨC TRÊN TRANG CHỦ
                            </h3>
                            <!-- Khung Fanpage trực quan + Plugin kết nối trực tiếp -->
                            <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                                <div class="relative h-32 bg-logic-navy">
                                    <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                                         onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80';"
                                         alt="Fanpage Xây Dựng Logic"
                                         class="w-full h-full object-cover opacity-55">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-2.5 text-white">
                                        <div class="w-11 h-11 rounded-lg bg-logic-navy border-2 border-white flex items-center justify-center font-heading font-extrabold text-xs text-amber-400 shrink-0">
                                            LOGIC
                                        </div>
                                        <div class="min-w-0">
                                            <div class="font-bold text-xs sm:text-sm truncate">Công Ty CP Đầu Tư Và Xây Dựng LOGIC</div>
                                            <div class="text-[11px] text-slate-200">Thiết kế & Thi công trọn gói Đà Nẵng • 5.8K theo dõi</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3 space-y-2.5 text-xs">
                                    <p class="text-slate-600 leading-relaxed">
                                        Cập nhật hình ảnh nhật ký công trình thực tế hàng ngày tại Khu đô thị Sinh thái Hòa Xuân và toàn TP Đà Nẵng.
                                    </p>
                                    <div class="grid grid-cols-3 gap-1.5">
                                        <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w300" alt="Ảnh Fanpage 1" class="w-full h-14 object-cover rounded">
                                        <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w300" alt="Ảnh Fanpage 2" class="w-full h-14 object-cover rounded">
                                        <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w300" alt="Ảnh Fanpage 3" class="w-full h-14 object-cover rounded">
                                    </div>
                                    <div class="flex items-center gap-2 pt-1">
                                        <a href="https://facebook.com" target="_blank" rel="noopener" class="flex-1 text-center py-2 rounded bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs transition">
                                            <i class="fa-brands fa-facebook-f mr-1"></i>Theo dõi Fanpage
                                        </a>
                                        <a href="https://m.me/" target="_blank" rel="noopener" class="flex-1 text-center py-2 rounded bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold text-xs transition">
                                            <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i>Gửi tin nhắn
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột 3: Bản đồ Google Maps đưa ra ngoài trang chủ -->
                    <div class="lg:col-span-4 bg-slate-50 p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-logic-navy uppercase mb-3 flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-logic-gold text-base"></i>BẢN ĐỒ GOOGLE MAPS TRỤ SỞ HÒA XUÂN
                            </h3>
                            <div class="w-full h-56 sm:h-60 rounded-lg overflow-hidden border border-slate-300 bg-slate-200">
                                <iframe
                                    title="Bản đồ CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC - Lô 24 B1.22 KĐT Sinh thái Hòa Xuân, Đà Nẵng"
                                    src="https://maps.google.com/maps?q=Khu%20%C4%91%C3%B4%20th%E1%BB%8B%20Sinh%20th%C3%A1i%20H%C3%B2a%20Xu%C3%A2n,%20Ph%C6%B0%E1%BB%9Dng%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                    width="100%"
                                    height="100%"
                                    style="border:0;"
                                    allowfullscreen=""
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>
                        <div class="pt-3 flex items-center justify-between text-xs text-slate-600">
                            <span class="truncate"><i class="fa-solid fa-location-crosshairs text-logic-gold mr-1"></i>Lô 24 B1.22 KĐT Sinh thái Hòa Xuân, Đà Nẵng</span>
                            <a href="https://www.google.com/maps/search/?api=1&query=L%C3%B4+24+B1.22+Khu+%C4%91%C3%B4+th%E1%BB%8B+Sinh+th%C3%A1i+H%C3%B2a+Xu%C3%A2n+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="font-bold text-logic-navy hover:text-logic-gold shrink-0 ml-2">
                                Chỉ đường →
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- =====================================================================
         FOOTER (#footer) - Chuẩn Flatsome Footer giống bố cục tintruongthinh.com
    ====================================================================== -->
    <footer id="footer" class="bg-logic-dark text-slate-300 pt-8 pb-6 border-t-4 border-logic-gold text-xs sm:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <h4 class="font-heading font-extrabold text-white text-sm uppercase">
                        CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC
                    </h4>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Đơn vị chuyên Thiết kế – Thi công phần thô – Thi công hoàn thiện – Nội thất trọn gói các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><strong>Trụ sở:</strong> Lô 24 B1.22 Khu đô thị Sinh thái Hòa Xuân, Phường Hòa Xuân, TP Đà Nẵng</li>
                        <li><strong>Hotline:</strong> <a href="tel:0986642634" class="text-amber-400 font-bold">0986.642.634</a></li>
                        <li><strong>Website:</strong> <a href="https://xaydunglogic.com" class="text-amber-400">xaydunglogic.com</a></li>
                        <li><strong>Mã số thuế:</strong> 0401798273</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="space-y-2">
                    <h4 class="font-heading font-extrabold text-white text-sm uppercase">
                        LĨNH VỰC HOẠT ĐỘNG
                    </h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thi công phần thô</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thi công hoàn thiện</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">• Thi công nội thất trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-400 transition">• Dự án tiêu biểu tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Công trình thực tế & Báo giá -->
                <div class="space-y-2">
                    <h4 class="font-heading font-extrabold text-white text-sm uppercase">
                        CÔNG TRÌNH & BÁO GIÁ
                    </h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="hover:text-amber-400 transition">• Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-amber-400 transition">• Thi công Biệt thự Đà Nẵng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-amber-400 transition">• Thi công Nhà phố trọn gói</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-amber-400 transition">• Thiết kế & Thi công Văn phòng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition">• Báo giá thi công trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Cam kết chất lượng -->
                <div class="space-y-2">
                    <h4 class="font-heading font-extrabold text-white text-sm uppercase">
                        CAM KẾT VỚI KHÁCH HÀNG
                    </h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Vật tư chính hãng đúng hợp đồng</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Không bán thầu, trực tiếp thi công</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Đảm bảo an toàn lao động & tiến độ</li>
                        <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Bảo hành kết cấu 5 năm tận tâm</li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>
                    Copyright 2026 © <strong>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC</strong> (xaydunglogic.com)
                </div>
                <div class="flex items-center gap-4">
                    <a href="#trang-chu" class="hover:text-white">Trang chủ</a>
                    <a href="#cong-trinh-thuc-te" class="hover:text-white">Công trình thực tế</a>
                    <a href="#du-an-da-nang" class="hover:text-white">Dự án Đà Nẵng</a>
                    <a href="#lien-he" class="hover:text-white">Liên hệ</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích hoàn hảo trên cả máy tính và điện thoại
         - Không gây tràn viền màn hình
    ====================================================================== -->
    <div class="fixed bottom-4 left-3 sm:left-4 z-50 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://facebook.com" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Facebook Fanpage Xây Dựng LOGIC">
            <span class="w-6 h-6 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0986642634" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Chat Zalo 0986.642.634">
            <span class="w-6 h-6 rounded-full bg-white text-sky-600 flex items-center justify-center font-extrabold text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0986642634"
           class="floating-pulse flex items-center gap-2 bg-logic-gold hover:bg-amber-600 text-white px-3.5 py-2 rounded-full shadow-lg transition"
           title="Gọi Hotline 0986.642.634">
            <span class="w-6 h-6 rounded-full bg-white text-logic-gold flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold tracking-wide pr-1">0986.642.634</span>
        </a>
    </div>

    <!-- Nút Lên Đầu Trang -->
    <a href="#trang-chu" aria-label="Lên đầu trang"
       class="fixed bottom-4 right-3 sm:right-4 z-40 w-9 h-9 rounded-full bg-logic-navy hover:bg-logic-gold text-white flex items-center justify-center shadow-md transition">
        <i class="fa-solid fa-arrow-up text-xs"></i>
    </a>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER 2 BANNER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
    ====================================================================== -->
    <script>
        // 1. Điều khiển 2 Banner tự trượt chuyên nghiệp
        let currentBanner = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.banner-dot');
        let bannerTimer = null;

        function showBanner(index) {
            currentBanner = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentBanner) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            dots.forEach((dot, i) => {
                if (i === currentBanner) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function nextBanner() {
            showBanner(currentBanner + 1);
            resetBannerTimer();
        }

        function prevBanner() {
            showBanner(currentBanner - 1);
            resetBannerTimer();
        }

        function goToBanner(index) {
            showBanner(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerTimer) clearInterval(bannerTimer);
            bannerTimer = setInterval(() => {
                showBanner(currentBanner + 1);
            }, 5000);
        }

        // 2. Đóng/mở menu danh mục trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-menu-drawer');
            const icon = document.getElementById('mobile-menu-icon');
            if (drawer.classList.contains('hidden')) {
                drawer.classList.remove('hidden');
                icon.className = 'fa-solid fa-xmark text-lg';
            } else {
                drawer.classList.add('hidden');
                icon.className = 'fa-solid fa-bars text-lg';
            }
        }

        // 3. Lọc danh mục Công trình thực tế (9 ảnh Drive nhóm 1)
        function filterConstruction(category) {
            const items = document.querySelectorAll('.construction-item');
            const buttons = document.querySelectorAll('#construction-tabs .cat-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 4. Lọc danh mục Dự án tại Đà Nẵng (10 ảnh Drive nhóm 2)
        function filterDaNang(category) {
            const items = document.querySelectorAll('.danang-item');
            const buttons = document.querySelectorAll('#danang-tabs .cat-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-dncat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-dncategory');
                if (category === 'all' || itemCat === category) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 5. Lọc danh mục Bài viết trang chủ
        function filterBlog(category) {
            const items = document.querySelectorAll('.blog-item');
            const buttons = document.querySelectorAll('#blog-tabs .cat-tab-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-bcat') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-bcategory');
                if (category === 'all' || itemCat === category) {
                    item.style.display = 'flex';
                } else {
                    item.style.display = 'none';
                }
            });
        }

        // 6. Xử lý gửi Form Yêu Cầu & Báo Giá trên trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const budget = document.getElementById('q-budget').value;
            const service = document.getElementById('q-service').value;
            const box = document.getElementById('quote-success-box');

            box.innerHTML = `
                <div class="font-bold text-emerald-800 mb-1">
                    <i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá của Quý khách ${name}!
                </div>
                <div>
                    Hệ thống <strong>xaydunglogic.com</strong> đã ghi nhận thông tin: <strong>${type}</strong> (${service} - Mức đầu tư: ${budget}). Kỹ sư của <strong>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG LOGIC</strong> sẽ liên hệ số <strong>${phone}</strong> trong ít phút tới. Hotline hỗ trợ trực tiếp: <strong>0986.642.634</strong>.
                </div>
            `;
            box.classList.remove('hidden');
            document.getElementById('quote-form').reset();
        }

        window.onload = function () {
            resetBannerTimer();
        };
    </script>
</body>
</html>
