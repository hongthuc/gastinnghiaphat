<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH GAS TÍN NGHĨA PHÁT - Tổng Đại Lý Gas & Bếp Gas Chính Hãng Đà Nẵng | gastinnghiaphat.com</title>
  <meta name="description" content="CÔNG TY TNHH GAS TÍN NGHĨA PHÁT (gastinnghiaphat.com) - Chuyên cung cấp Bình Gas Petrolimex, Bình Gas Công Nghiệp 45kg, Bếp Gas Âm, Bếp Gas Dương, Linh Kiện Gas chính hãng tại 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng. Hotline: 0914.000.299." />
  
  <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://gastinnghiaphat.com/" />
  <meta property="og:site_name" content="gastinnghiaphat.com" />
  <meta property="og:title" content="CÔNG TY TNHH GAS TÍN NGHĨA PHÁT - gastinnghiaphat.com" />
  <meta property="og:description" content="Đại lý phân phối Bình Gas Dân Dụng, Gas Công Nghiệp, Bếp Gas Chính Hãng uy tín tại Đà Nẵng. Địa chỉ: 245 Trần Quý Khoách, P. Hòa Khánh, TP Đà Nẵng - ĐT: 0914.000.299" />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w1200" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w1200" />
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w200" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome 6 -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            petroBlue: '#004B93',
            petroDark: '#003366',
            petroLight: '#EBF4FF',
            petroOrange: '#F36F21',
            petroRed: '#E31837',
          }
        }
      }
    }
  </script>

  <style>
    /* Reset & chống tràn viền tuyệt đối trên cả máy tính và điện thoại */
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
      background-color: #f5f7fa;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Chuẩn danh mục viết liền trên 1 hàng, không bị xuống dòng lẻ chữ */
    .nav-cat-item {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      line-height: 1.2;
      flex-shrink: 0;
    }

    /* Flatsome Sale Badge góc trên bên trái */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background: linear-gradient(135deg, #F36F21 0%, #E31837 100%);
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 6px 8px;
      border-radius: 9999px;
      box-shadow: 0 2px 6px rgba(227, 24, 55, 0.35);
      pointer-events: none;
    }
    @media (min-width: 640px) {
      .flatsome-sale-badge {
        font-size: 12px;
        padding: 7px 10px;
      }
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
    .product-title-full {
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
      hyphens: none;
      line-height: 1.38;
    }

    /* Tiêu đề Section kiểu Flatsome (Section Title Border) */
    .flatsome-section-header {
      border-bottom: 2px solid #004B93;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      gap: 8px;
      background: #ffffff;
      border-radius: 8px 8px 0 0;
    }
    .flatsome-section-title {
      background: linear-gradient(90deg, #004B93 0%, #0062BD 100%);
      color: #ffffff;
      padding: 10px 18px;
      font-weight: 700;
      font-size: 14px;
      text-transform: uppercase;
      letter-spacing: 0.02em;
      border-radius: 6px 6px 0 0;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      white-space: nowrap;
    }
    @media (min-width: 768px) {
      .flatsome-section-title {
        font-size: 15px;
        padding: 11px 22px;
      }
    }

    /* Hiệu ứng nút liên hệ nổi (Floating Contact) */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(243, 111, 33, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(243, 111, 33, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(243, 111, 33, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-[#f4f6f9] text-slate-800 antialiased">

  <!-- =====================================================================
       FLATSOME TOP BAR (#top-bar)
  ====================================================================== -->
  <div id="top-bar" class="bg-petroDark text-white text-xs py-2 border-b border-blue-900">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 font-medium">
        <i class="fa-solid fa-fire-flame-curved text-petroOrange"></i>
        <span><strong>CÔNG TY TNHH GAS TÍN NGHĨA PHÁT</strong> — Website: <a href="https://gastinnghiaphat.com" class="underline text-amber-300 font-semibold">gastinnghiaphat.com</a></span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-[12px] text-blue-100">
        <span><i class="fa-solid fa-location-dot text-petroOrange mr-1"></i>245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng</span>
        <span>|</span>
        <span><i class="fa-solid fa-clock text-petroOrange mr-1"></i>Giao gas nhanh 24/7 toàn Đà Nẵng</span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       FLATSOME HEADER (#header) - KHÔNG ĐỂ NÚT GỌI NGAY TRÊN HEADER ĐỂ TRÁNH TRÀN VIỀN
  ====================================================================== -->
  <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <!-- Header Main -->
    <div class="flatsome-container py-2.5 md:py-3">
      <div class="flex items-center justify-between gap-2 sm:gap-4">
        
        <!-- Nút mở danh mục trên điện thoại -->
        <button id="mobile-menu-btn" type="button" onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg bg-petroLight text-petroBlue hover:bg-petroBlue hover:text-white transition shrink-0">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
        <a href="#trang-chu" class="flex items-center gap-2.5 sm:gap-3 min-w-0 shrink">
          <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center shrink-0 overflow-hidden shadow-xs">
            <img 
              src="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w400" 
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1AH_S744i4E3BjzoZzhuWrcFEELQHipd7';"
              alt="Logo Công Ty TNHH Gas Tín Nghĩa Phát" 
              class="max-h-full max-w-full object-contain"
            />
          </div>
          <div class="min-w-0">
            <div class="text-[13px] sm:text-base md:text-lg font-extrabold text-petroBlue tracking-tight leading-tight">
              GAS TÍN NGHĨA PHÁT
            </div>
            <div class="text-[10px] sm:text-xs text-petroOrange font-semibold leading-tight">
              gastinnghiaphat.com • MST: 0401969539
            </div>
          </div>
        </a>

        <!-- Thanh tìm kiếm sản phẩm (ẩn trên màn nhỏ, hiện từ md) -->
        <div class="hidden md:flex flex-1 max-w-md mx-2">
          <div class="relative w-full flex">
            <input 
              id="desktop-search-input"
              type="text" 
              oninput="filterProductsBySearch(this.value)"
              placeholder="Tìm bình gas Petrolimex 12kg, gas 45kg, bếp gas âm..." 
              class="w-full rounded-l-lg border border-slate-300 px-3.5 py-2 text-xs lg:text-sm focus:outline-none focus:border-petroBlue"
            />
            <button type="button" onclick="filterProductsBySearch(document.getElementById('desktop-search-input').value)" class="bg-petroBlue hover:bg-petroOrange text-white px-4 rounded-r-lg text-sm font-medium transition">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- Cụm nút chức năng gọn nhẹ (Báo giá & Giỏ hàng - Không để nút Gọi ngay tránh tràn viền) -->
        <div class="flex items-center gap-2 shrink-0">
          <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 hover:bg-petroLight text-petroBlue text-xs font-semibold transition">
            <i class="fa-solid fa-file-invoice-dollar text-petroOrange"></i>
            <span>Nhận Báo Giá</span>
          </a>
          <button type="button" onclick="openCartModal()" class="relative inline-flex items-center gap-1.5 px-3 py-2 rounded-lg border border-petroBlue/20 bg-petroLight/60 hover:bg-petroBlue hover:text-white text-petroBlue text-xs font-semibold transition">
            <i class="fa-solid fa-cart-shopping text-sm"></i>
            <span class="hidden sm:inline">Giỏ hàng</span>
            <span id="cart-count-badge" class="inline-flex items-center justify-center min-w-[18px] h-[18px] px-1 text-[10px] font-bold bg-petroOrange text-white rounded-full">0</span>
          </button>
        </div>

      </div>

      <!-- Thanh tìm kiếm trên điện thoại -->
      <div class="mt-2 md:hidden">
        <div class="relative w-full flex">
          <input 
            id="mobile-search-input"
            type="text" 
            oninput="filterProductsBySearch(this.value)"
            placeholder="Tìm sản phẩm: Bình gas 12kg, công nghiệp, bếp gas..." 
            class="w-full rounded-l-lg border border-slate-300 px-3 py-1.5 text-xs focus:outline-none focus:border-petroBlue"
          />
          <button type="button" onclick="filterProductsBySearch(document.getElementById('mobile-search-input').value)" class="bg-petroBlue text-white px-3.5 rounded-r-lg text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- =====================================================================
         THANH DANH MỤC TRÊN MÁY TÍNH (#wide-nav)
         Chữ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap), tự xuống hàng 2 nguyên cụm nếu màn hình hẹp, tuyệt đối không gãy chữ
    ====================================================================== -->
    <nav id="wide-nav" class="hidden lg:block bg-petroBlue text-white border-t border-blue-800">
      <div class="flatsome-container">
        <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-1 py-1.5 text-[12px] xl:text-[12.5px] font-semibold">
          <li>
            <a href="#trang-chu" onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1.5 rounded bg-petroOrange text-white hover:bg-orange-600 transition">
              <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>TRANG CHỦ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">GIỚI THIỆU</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-petrolimex')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BÌNH GAS PETROLIMEX</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-cong-nghiep')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BÌNH GAS CÔNG NGHIỆP</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BẾP GAS ÂM</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am-kinh')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BẾP GAS ÂM KÍNH</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-duong')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BẾP GAS DƯƠNG</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('bo-binh-bep-gas')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">BỘ BÌNH BẾP GAS</a>
          </li>
          <li>
            <a href="#san-pham-trang-chu" onclick="filterCategory('linh-kien-bep')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">LINH KIỆN BẾP & VAN GAS</a>
          </li>
          <li>
            <a href="#bai-viet-trang-chu" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">GIÁ GAS</a>
          </li>
          <li>
            <a href="#doi-tac" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">ĐỐI TÁC</a>
          </li>
          <li>
            <a href="#bai-viet-trang-chu" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">TIN TỨC</a>
          </li>
          <li>
            <a href="#ban-do-lien-he" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-white/15 transition">LIÊN HỆ</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- =====================================================================
       DRAWER DANH MỤC TRÊN ĐIỆN THOẠI (Tối ưu gọn đẹp)
  ====================================================================== -->
  <div id="mobile-drawer-backdrop" onclick="toggleMobileDrawer()" class="fixed inset-0 bg-slate-900/60 z-50 hidden backdrop-blur-xs"></div>
  <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
    <div class="p-3.5 bg-petroBlue text-white flex items-center justify-between">
      <div class="flex items-center gap-2">
        <img src="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w200" alt="Logo" class="w-8 h-8 rounded bg-white p-0.5 object-contain" />
        <span class="font-bold text-xs tracking-wide">DANH MỤC SẢN PHẨM</span>
      </div>
      <button type="button" onclick="toggleMobileDrawer()" class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-xs font-semibold text-slate-700">
      <a href="#trang-chu" onclick="filterCategory('all'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight text-petroBlue">
        <span><i class="fa-solid fa-house mr-2 text-petroOrange"></i>Trang Chủ</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-petrolimex'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-fire-burner mr-2 text-petroBlue"></i>Bình Gas Petrolimex</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-cong-nghiep'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-industry mr-2 text-petroBlue"></i>Bình Gas Công Nghiệp</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-kitchen-set mr-2 text-petroBlue"></i>Bếp Gas Âm</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am-kinh'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-table-cells-large mr-2 text-petroBlue"></i>Bếp Gas Âm Kính</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-duong'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-fire mr-2 text-petroBlue"></i>Bếp Gas Dương</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('bo-binh-bep-gas'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-boxes-stacked mr-2 text-petroBlue"></i>Bộ Bình Bếp Gas</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#san-pham-trang-chu" onclick="filterCategory('linh-kien-bep'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-screwdriver-wrench mr-2 text-petroBlue"></i>Linh Kiện Bếp & Van Gas</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#form-bao-gia" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-file-signature mr-2 text-petroOrange"></i>Yêu Cầu & Báo Giá</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#bai-viet-trang-chu" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-newspaper mr-2 text-petroBlue"></i>Tin Tức & Giá Gas</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#doi-tac" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-handshake mr-2 text-petroBlue"></i>Đối Tác Chiến Lược</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
      <a href="#ban-do-lien-he" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-petroLight">
        <span><i class="fa-solid fa-map-location-dot mr-2 text-petroBlue"></i>Bản Đồ & Liên Hệ</span>
        <i class="fa-solid fa-angle-right text-slate-400"></i>
      </a>
    </div>
    <div class="p-3.5 bg-slate-50 border-t border-slate-200 text-xs">
      <div class="font-bold text-petroBlue mb-1">CÔNG TY TNHH GAS TÍN NGHĨA PHÁT</div>
      <div class="text-slate-600 mb-1">245 Trần Quý Khoách, P. Hòa Khánh, TP Đà Nẵng</div>
      <div class="font-bold text-petroRed">Hotline: 0914.000.299</div>
    </div>
  </aside>

  <!-- =====================================================================
       MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE)
  ====================================================================== -->
  <main id="trang-chu" class="py-3 md:py-5 space-y-6 md:space-y-8">

    <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         Chữ và hình ảnh nằm trọn bên trong banner, cách xa viền ảnh banner, không bị thiếu chữ trên cả điện thoại và máy tính -->
    <section class="flatsome-container" aria-label="Banner chính">
      <div class="relative w-full rounded-xl overflow-hidden shadow-md bg-petroDark">
        
        <!-- Khung trượt 2 Banner có chiều cao đồng nhất (kích thước bằng nhau) -->
        <div id="hero-slider" class="relative w-full h-[290px] sm:h-[340px] md:h-[390px] lg:h-[420px]">
          
          <!-- SLIDE 1: Bình Gas Dân Dụng & Bộ Bình Bếp Gas Chính Hãng -->
          <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10 flex items-center" style="background: radial-gradient(circle at 80% 50%, #0066cc 0%, #003b75 55%, #002244 100%);">
            <!-- Khoảng đệm an toàn cách xa viền banner (px-7 sm:px-14 md:px-20 py-6) -->
            <div class="w-full h-full px-7 sm:px-14 md:px-20 py-5 sm:py-8 flex flex-row items-center justify-between gap-3 sm:gap-8">
              
              <!-- Phần chữ bên trong banner (cách xa viền, co giãn thông minh không bao giờ mất chữ) -->
              <div class="w-[62%] sm:w-[60%] text-white space-y-1.5 sm:space-y-3">
                <div class="inline-flex items-center gap-1.5 bg-petroOrange text-white text-[10px] sm:text-xs font-bold px-2.5 py-1 rounded-md">
                  <i class="fa-solid fa-shield-halved"></i>
                  <span>TỔNG ĐẠI LÝ GAS UY TÍN ĐÀ NẴNG</span>
                </div>
                <h1 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug tracking-tight text-white">
                  CÔNG TY TNHH GAS TÍN NGHĨA PHÁT
                </h1>
                <p class="text-[11px] sm:text-xs md:text-sm text-blue-100 leading-relaxed">
                  Chuyên phân phối Bình Gas Petrolimex 12kg, Gas Công Nghiệp 45kg, Bếp Gas Âm - Dương & Linh Kiện chính hãng. Giao gas tận nơi chỉ 10 - 15 phút!
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 text-[10px] sm:text-xs md:text-sm">
                  <span class="bg-white/15 border border-white/25 px-2.5 py-1 rounded-lg font-semibold text-amber-300">
                    <i class="fa-solid fa-phone-volume mr-1"></i>ĐT: 0914.000.299
                  </span>
                  <span class="hidden sm:inline-block bg-white/10 px-2.5 py-1 rounded-lg text-white">
                    <i class="fa-solid fa-location-dot text-petroOrange mr-1"></i>245 Trần Quý Khoách, P. Hòa Khánh, Đà Nẵng
                  </span>
                </div>
              </div>

              <!-- Phần hình ảnh thực tế nằm gọn trong khung phải của Banner 1 -->
              <div class="w-[38%] sm:w-[38%] h-full flex items-center justify-center">
                <div class="relative w-full max-w-[135px] sm:max-w-[210px] md:max-w-[260px] h-[190px] sm:h-[250px] md:h-[300px] bg-white/95 rounded-2xl p-2 sm:p-3 shadow-xl border-2 border-amber-400 flex flex-col items-center justify-center">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1HZkIU2ZMwHIl2bA7_Y8iiAcAS5TcPNvE&sz=w800" 
                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1HZkIU2ZMwHIl2bA7_Y8iiAcAS5TcPNvE';"
                    alt="Bình Gas Chính Hãng Tín Nghĩa Phát" 
                    class="max-h-[78%] max-w-full object-contain"
                  />
                  <span class="mt-1.5 text-[10px] sm:text-xs font-extrabold text-petroBlue text-center leading-tight">
                    An Toàn • Đủ Cân • Chính Hãng
                  </span>
                </div>
              </div>

            </div>
          </div>

          <!-- SLIDE 2: Hệ Thống Gas Công Nghiệp & Thiết Bị Bếp Nhà Hàng -->
          <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 flex items-center" style="background: linear-gradient(125deg, #0f172a 0%, #004B93 55%, #b45309 100%);">
            <!-- Khoảng đệm an toàn cách xa viền banner (px-7 sm:px-14 md:px-20 py-6) -->
            <div class="w-full h-full px-7 sm:px-14 md:px-20 py-5 sm:py-8 flex flex-row items-center justify-between gap-3 sm:gap-8">
              
              <!-- Phần chữ bên trong banner 2 -->
              <div class="w-[62%] sm:w-[60%] text-white space-y-1.5 sm:space-y-3">
                <div class="inline-flex items-center gap-1.5 bg-amber-500 text-slate-950 text-[10px] sm:text-xs font-extrabold px-2.5 py-1 rounded-md">
                  <i class="fa-solid fa-Certificate"></i>
                  <span>GIẢI PHÁP GAS CÔNG NGHIỆP & NHÀ BẾP</span>
                </div>
                <h2 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug tracking-tight text-white">
                  LẮP ĐẶT HỆ THỐNG GAS & BẾP GAS GIÁ SỈ
                </h2>
                <p class="text-[11px] sm:text-xs md:text-sm text-slate-100 leading-relaxed">
                  Cung cấp sỉ & lẻ Bình Gas 45kg - 48kg, Bếp Gas Âm Kính, Bếp Gas Công Nghiệp cho nhà hàng, khách sạn, quán ăn tại TP Đà Nẵng. Bảo hành chu đáo!
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 text-[10px] sm:text-xs md:text-sm">
                  <span class="bg-petroOrange text-white px-2.5 py-1 rounded-lg font-bold">
                    <i class="fa-solid fa-globe mr-1"></i>gastinnghiaphat.com
                  </span>
                  <span class="bg-white/15 border border-white/25 px-2.5 py-1 rounded-lg font-semibold text-amber-300">
                    Hotline: 0914.000.299
                  </span>
                </div>
              </div>

              <!-- Phần hình ảnh thực tế nằm gọn trong khung phải của Banner 2 -->
              <div class="w-[38%] sm:w-[38%] h-full flex items-center justify-center">
                <div class="relative w-full max-w-[135px] sm:max-w-[210px] md:max-w-[260px] h-[190px] sm:h-[250px] md:h-[300px] bg-white/95 rounded-2xl p-2 sm:p-3 shadow-xl border-2 border-petroOrange flex flex-col items-center justify-center">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1tHYEOcc4QvgYx1MvOY5y7SdBW0KjVMnx&sz=w800" 
                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tHYEOcc4QvgYx1MvOY5y7SdBW0KjVMnx';"
                    alt="Bếp Gas và Bình Gas Công Nghiệp Tín Nghĩa Phát" 
                    class="max-h-[78%] max-w-full object-contain"
                  />
                  <span class="mt-1.5 text-[10px] sm:text-xs font-extrabold text-petroOrange text-center leading-tight">
                    Bếp Gas & Phụ Kiện Cao Cấp
                  </span>
                </div>
              </div>

            </div>
          </div>

        </div>

        <!-- Nút điều hướng qua lại Banner -->
        <button type="button" onclick="prevBannerSlide()" aria-label="Banner trước" class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-petroOrange text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button type="button" onclick="nextBannerSlide()" aria-label="Banner tiếp" class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-petroOrange text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm tròn chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToBannerSlide(0)" id="slider-dot-0" class="w-6 h-2 rounded-full bg-petroOrange transition-all" aria-label="Slide 1"></button>
          <button type="button" onclick="goToBannerSlide(1)" id="slider-dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
        </div>

      </div>
    </section>

    <!-- =====================================================================
         SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu nhỏ gọn, viết liền 1 hàng)
    ====================================================================== -->
    <section class="flatsome-container" aria-label="Danh mục sản phẩm trang chủ">
      <div class="bg-white rounded-xl p-3 sm:p-4 shadow-xs border border-slate-200">
        <div class="flex items-center justify-between mb-2.5 border-b border-slate-100 pb-2">
          <h2 class="text-xs sm:text-sm font-extrabold text-petroBlue uppercase flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-petroOrange"></i>
            <span>DANH MỤC SẢN PHẨM</span>
          </h2>
          <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>

        <!-- Danh mục hiển thị dạng thanh nút nhỏ gọn, tên mỗi danh mục luôn nằm trên 1 dòng -->
        <div class="flex flex-wrap items-center gap-1.5 sm:gap-2">
          <button type="button" onclick="filterCategory('all')" data-cat-btn="all" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-bold bg-petroBlue text-white border border-petroBlue transition">
            <i class="fa-solid fa-border-all mr-1.5"></i>Tất Cả Sản Phẩm
          </button>
          <button type="button" onclick="filterCategory('binh-gas-petrolimex')" data-cat-btn="binh-gas-petrolimex" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-fire-flame-simple text-petroOrange mr-1.5"></i>Bình Gas Petrolimex
          </button>
          <button type="button" onclick="filterCategory('binh-gas-cong-nghiep')" data-cat-btn="binh-gas-cong-nghiep" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-industry text-petroBlue mr-1.5"></i>Bình Gas Công Nghiệp
          </button>
          <button type="button" onclick="filterCategory('bep-gas-am')" data-cat-btn="bep-gas-am" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-kitchen-set text-petroOrange mr-1.5"></i>Bếp Gas Âm
          </button>
          <button type="button" onclick="filterCategory('bep-gas-am-kinh')" data-cat-btn="bep-gas-am-kinh" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-table-cells-large text-petroBlue mr-1.5"></i>Bếp Gas Âm Kính
          </button>
          <button type="button" onclick="filterCategory('bep-gas-duong')" data-cat-btn="bep-gas-duong" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-fire text-petroOrange mr-1.5"></i>Bếp Gas Dương
          </button>
          <button type="button" onclick="filterCategory('bo-binh-bep-gas')" data-cat-btn="bo-binh-bep-gas" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-boxes-stacked text-petroBlue mr-1.5"></i>Bộ Bình Bếp Gas
          </button>
          <button type="button" onclick="filterCategory('linh-kien-bep')" data-cat-btn="linh-kien-bep" class="cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition">
            <i class="fa-solid fa-screwdriver-wrench text-petroOrange mr-1.5"></i>Linh Kiện Bếp & Van Gas
          </button>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         SECTION 3: DANH SÁCH SẢN PHẨM TRANG CHỦ CHUẨN FLATSOME (gaspetrolimex.com)
         - Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 4 cột (lg:grid-cols-4)
         - Góc trên bên trái chỉ có duy nhất badge % giảm giá chuẩn Flatsome
         - Tên sản phẩm hiển thị đầy đủ, không cắt chữ, không tràn viền
    ====================================================================== -->
    <section id="san-pham-trang-chu" class="flatsome-container space-y-6">

      <!-- KHỐI 3.1: BÌNH GAS PETROLIMEX & BÌNH GAS CÔNG NGHIỆP -->
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 overflow-hidden">
        <div class="flatsome-section-header px-3 pt-2.5">
          <h2 class="flatsome-section-title">
            <i class="fa-solid fa-fire-flame-curved text-petroOrange"></i>
            <span>BÌNH GAS PETROLIMEX & GAS CÔNG NGHIỆP</span>
          </h2>
          <div class="flex flex-wrap items-center gap-1.5 pb-2 pr-1 text-[11px] sm:text-xs font-semibold text-petroBlue">
            <button type="button" onclick="filterCategory('binh-gas-petrolimex')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-slate-100">Bình Gas Petrolimex</button>
            <button type="button" onclick="filterCategory('binh-gas-cong-nghiep')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-slate-100">Bình Gas Công Nghiệp</button>
            <button type="button" onclick="filterCategory('all')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-petroLight text-petroBlue">Xem tất cả</button>
          </div>
        </div>

        <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div id="product-grid-gas" class="p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
          <!-- Được render tự động từ mảng dữ liệu 8 ảnh thực tế Google Drive bên dưới -->
        </div>
      </div>

      <!-- KHỐI 3.2: BẾP GAS ÂM - BẾP GAS DƯƠNG - BỘ BÌNH BẾP GAS -->
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 overflow-hidden">
        <div class="flatsome-section-header px-3 pt-2.5">
          <h2 class="flatsome-section-title">
            <i class="fa-solid fa-kitchen-set text-petroOrange"></i>
            <span>BẾP GAS - BỘ BÌNH BẾP GAS - LINH KIỆN</span>
          </h2>
          <div class="flex flex-wrap items-center gap-1.5 pb-2 pr-1 text-[11px] sm:text-xs font-semibold text-petroBlue">
            <button type="button" onclick="filterCategory('bep-gas-am')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-slate-100">Bếp Gas Âm</button>
            <button type="button" onclick="filterCategory('bep-gas-duong')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-slate-100">Bếp Gas Dương</button>
            <button type="button" onclick="filterCategory('bo-binh-bep-gas')" class="nav-cat-item hover:text-petroOrange px-2 py-1 rounded bg-slate-100">Bộ Bình Bếp Gas</button>
          </div>
        </div>

        <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div id="product-grid-stoves" class="p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
          <!-- Được render tự động từ mảng dữ liệu 8 ảnh thực tế Google Drive bên dưới -->
        </div>
      </div>

    </section>

    <!-- =====================================================================
         SECTION 4: GIỚI THIỆU NGẮN & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ
    ====================================================================== -->
    <section id="form-bao-gia" class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 md:gap-6">
        
        <!-- Cột thông tin Công Ty TNHH Gas Tín Nghĩa Phát (5/12) -->
        <div id="gioi-thieu" class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-xs flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-3 pb-3 mb-4 border-b border-slate-200">
              <img 
                src="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w300" 
                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1AH_S744i4E3BjzoZzhuWrcFEELQHipd7';"
                alt="Logo Gas Tín Nghĩa Phát" 
                class="w-12 h-12 rounded-lg border border-slate-200 p-1 object-contain shrink-0"
              />
              <div>
                <h2 class="text-sm sm:text-base font-extrabold text-petroBlue uppercase">
                  CÔNG TY TNHH GAS TÍN NGHĨA PHÁT
                </h2>
                <p class="text-xs text-petroOrange font-semibold">Đại diện pháp luật: Ông Hồ Viết Pháp</p>
              </div>
            </div>

            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-4">
              <strong>Công Ty TNHH Gas Tín Nghĩa Phát</strong> (Mã số thuế: <strong>0401969539</strong>) là đơn vị chuyên phân phối sỉ và lẻ khí dầu mỏ hóa lỏng (LPG) chai dân dụng 12kg, bình gas công nghiệp 45kg - 48kg, thi công hệ thống gas nhà hàng và cung cấp thiết bị bếp gas chính hãng tại TP Đà Nẵng.
            </p>

            <ul class="space-y-2.5 text-xs sm:text-sm text-slate-700">
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-petroOrange mt-1"></i>
                <span>Cam kết bình gas chính hãng 100%, có màng co chống giả, bảo hiểm an toàn đầy đủ.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-petroOrange mt-1"></i>
                <span>Cân kiểm tra trọng lượng gas trực tiếp tại nhà khách hàng, miễn phí kiểm tra rò rỉ van dây.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-petroOrange mt-1"></i>
                <span>Chiết khấu giá sỉ đặc biệt cho quán ăn, nhà hàng, căn tin trường học, khu công nghiệp Hòa Khánh.</span>
              </li>
            </ul>
          </div>

          <div class="mt-5 pt-4 border-t border-slate-100 bg-petroLight/60 rounded-lg p-3.5 text-xs sm:text-sm space-y-1.5">
            <div class="font-bold text-petroBlue"><i class="fa-solid fa-location-dot text-petroOrange mr-1.5"></i>Địa chỉ: 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng</div>
            <div class="font-bold text-petroRed"><i class="fa-solid fa-phone-volume mr-1.5"></i>Hotline / Zalo đặt gas: 0914.000.299</div>
            <div class="text-slate-600"><i class="fa-solid fa-globe text-petroBlue mr-1.5"></i>Website: <strong>gastinnghiaphat.com</strong></div>
          </div>
        </div>

        <!-- Cột Form Yêu Cầu & Báo Giá Trang Chủ (7/12) -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-xs">
          <div class="border-b-2 border-petroBlue pb-2.5 mb-4 flex items-center justify-between">
            <h2 class="text-sm sm:text-base font-extrabold text-petroBlue uppercase flex items-center gap-2">
              <i class="fa-solid fa-file-pen text-petroOrange"></i>
              <span>ĐĂNG KÝ ĐẶT GAS & NHẬN BÁO GIÁ NHANH</span>
            </h2>
            <span class="text-[11px] font-semibold text-petroOrange">Phản hồi trong 3 phút</span>
          </div>

          <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng / Đơn vị *</label>
                <input 
                  type="text" 
                  id="quote-name" 
                  required 
                  placeholder="Nhập họ tên hoặc tên nhà hàng, công ty..." 
                  class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-petroBlue"
                />
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo liên hệ *</label>
                <input 
                  type="tel" 
                  id="quote-phone" 
                  required 
                  placeholder="Ví dụ: 0914000299" 
                  class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-petroBlue"
                />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục cần báo giá / đặt hàng *</label>
                <select id="quote-category" class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm bg-white focus:outline-none focus:border-petroBlue">
                  <option value="Đổi bình Gas Petrolimex 12kg dân dụng">Đổi bình Gas Petrolimex 12kg dân dụng</option>
                  <option value="Báo giá sỉ Bình Gas Công Nghiệp 45kg - 48kg">Báo giá sỉ Bình Gas Công Nghiệp 45kg - 48kg</option>
                  <option value="Trọn bộ Bình Gas + Bếp Gas mới">Trọn bộ Bình Gas + Bếp Gas mới</option>
                  <option value="Bếp Gas Âm / Bếp Gas Dương chính hãng">Bếp Gas Âm / Bếp Gas Dương chính hãng</option>
                  <option value="Lắp đặt hệ thống giàn gas nhà hàng, quán ăn">Lắp đặt hệ thống giàn gas nhà hàng, quán ăn</option>
                  <option value="Thay van gas, dây dẫn gas, sửa bếp gas">Thay van gas, dây dẫn gas, sửa bếp gas</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ giao gas / khảo sát tại Đà Nẵng</label>
                <input 
                  type="text" 
                  id="quote-address" 
                  placeholder="Số nhà, tên đường, phường, TP Đà Nẵng..." 
                  class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-petroBlue"
                />
              </div>
            </div>

            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú yêu cầu chi tiết</label>
              <textarea 
                id="quote-note" 
                rows="3" 
                placeholder="Nhập số lượng bình, loại van chụp hay van ngang, hoặc yêu cầu báo giá..." 
                class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-petroBlue"
              ></textarea>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
              <button type="submit" class="bg-petroOrange hover:bg-orange-600 text-white font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg shadow-sm transition inline-flex items-center gap-2">
                <i class="fa-solid fa-paper-plane"></i>
                <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
              </button>
              <span class="text-xs text-slate-500">
                Hoặc gọi trực tiếp: <a href="tel:0914000299" class="font-bold text-petroBlue underline">0914.000.299</a>
              </span>
            </div>

            <!-- Hộp thông báo kết quả gửi form (thay thế hoàn toàn alert) -->
            <div id="quote-feedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200"></div>
          </form>
        </div>

      </div>
    </section>

    <!-- =====================================================================
         SECTION 5: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & GIÁ GAS)
    ====================================================================== -->
    <section id="bai-viet-trang-chu" class="flatsome-container">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 overflow-hidden">
        <div class="flatsome-section-header px-3 pt-2.5">
          <h2 class="flatsome-section-title">
            <i class="fa-solid fa-newspaper text-petroOrange"></i>
            <span>DANH MỤC BÀI VIẾT & CẬP NHẬT GIÁ GAS MỚI NHẤT</span>
          </h2>
          <span class="text-xs text-slate-500 pr-2 pb-1 hidden sm:inline">Cẩm nang an toàn gas & Bảng giá gas Đà Nẵng</span>
        </div>

        <div class="p-3 sm:p-5 grid grid-cols-1 md:grid-cols-3 gap-4">
          <!-- Bài viết 1 -->
          <article class="rounded-xl border border-slate-200 overflow-hidden flex flex-col bg-slate-50/50 hover:shadow-md transition">
            <div class="h-44 bg-white p-3 flex items-center justify-center border-b border-slate-100">
              <img 
                src="https://drive.google.com/thumbnail?id=16aQp0HPdk_vgsvnubIDcEdBIGD-bkzrf&sz=w600" 
                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/16aQp0HPdk_vgsvnubIDcEdBIGD-bkzrf';"
                alt="Giá gas Petrolimex Đà Nẵng hôm nay" 
                class="max-h-full max-w-full object-contain"
              />
            </div>
            <div class="p-3.5 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] font-semibold text-petroOrange mb-1">GIÁ GAS HÔM NAY • ĐÀ NẴNG</div>
                <h3 class="text-sm font-bold text-slate-800 hover:text-petroBlue leading-snug mb-2">
                  Cập nhật bảng giá bình Gas Petrolimex 12kg và 45kg chính hãng tại Đà Nẵng
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Công Ty TNHH Gas Tín Nghĩa Phát thông báo bảng giá đổi bình gas dân dụng 12kg van ngang, van chụp và bình gas công nghiệp 45kg ưu đãi mới nhất kèm quà tặng hấp dẫn.
                </p>
              </div>
              <div class="mt-3 pt-2.5 border-t border-slate-200/70 flex items-center justify-between text-xs">
                <span class="text-slate-500"><i class="fa-regular fa-calendar mr-1"></i>Cập nhật hàng tháng</span>
                <a href="#form-bao-gia" class="font-bold text-petroBlue hover:text-petroOrange">Nhận báo giá →</a>
              </div>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="rounded-xl border border-slate-200 overflow-hidden flex flex-col bg-slate-50/50 hover:shadow-md transition">
            <div class="h-44 bg-white p-3 flex items-center justify-center border-b border-slate-100">
              <img 
                src="https://drive.google.com/thumbnail?id=1wQxFDhHDz3wYCizA6eG07K0_6x_uTo5F&sz=w600" 
                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wQxFDhHDz3wYCizA6eG07K0_6x_uTo5F';"
                alt="Cách sử dụng bếp gas tiết kiệm và an toàn" 
                class="max-h-full max-w-full object-contain"
              />
            </div>
            <div class="p-3.5 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] font-semibold text-petroOrange mb-1">KỸ THUẬT & AN TOÀN GAS</div>
                <h3 class="text-sm font-bold text-slate-800 hover:text-petroBlue leading-snug mb-2">
                  Hướng dẫn cách sử dụng bếp gas an toàn, tiết kiệm gas cho mọi gia đình
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Bí quyết chỉnh ngọn lửa xanh đều, quy trình khóa van bình gas an toàn sau khi đun nấu và thời điểm cần bảo dưỡng, thay thế dây dẫn gas định kỳ để phòng ngừa rò rỉ.
                </p>
              </div>
              <div class="mt-3 pt-2.5 border-t border-slate-200/70 flex items-center justify-between text-xs">
                <span class="text-slate-500"><i class="fa-solid fa-user-shield mr-1"></i>Kỹ thuật Tín Nghĩa Phát</span>
                <a href="tel:0914000299" class="font-bold text-petroBlue hover:text-petroOrange">Tư vấn miễn phí →</a>
              </div>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="rounded-xl border border-slate-200 overflow-hidden flex flex-col bg-slate-50/50 hover:shadow-md transition">
            <div class="h-44 bg-white p-3 flex items-center justify-center border-b border-slate-100">
              <img 
                src="https://drive.google.com/thumbnail?id=1SZABqp4E5Gvqz-PYIUt3fLh8p2nKNHrR&sz=w600" 
                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1SZABqp4E5Gvqz-PYIUt3fLh8p2nKNHrR';"
                alt="Lắp đặt hệ thống gas công nghiệp Đà Nẵng" 
                class="max-h-full max-w-full object-contain"
              />
            </div>
            <div class="p-3.5 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] font-semibold text-petroOrange mb-1">DỰ ÁN GAS CÔNG NGHIỆP</div>
                <h3 class="text-sm font-bold text-slate-800 hover:text-petroBlue leading-snug mb-2">
                  Tư vấn thiết kế, thi công hệ thống giàn gas công nghiệp nhà hàng tại Đà Nẵng
                </h3>
                <p class="text-xs text-slate-600 leading-relaxed">
                  Giải pháp lắp đặt hệ thống gas trung tâm, van điều áp tự động, còi báo rò rỉ gas đạt tiêu chuẩn PCCC cho bếp ăn công nghiệp, nhà hàng và khách sạn tại Đà Nẵng.
                </p>
              </div>
              <div class="mt-3 pt-2.5 border-t border-slate-200/70 flex items-center justify-between text-xs">
                <span class="text-slate-500"><i class="fa-solid fa-Phone mr-1"></i>0914.000.299</span>
                <a href="#form-bao-gia" class="font-bold text-petroBlue hover:text-petroOrange">Khảo sát tận nơi →</a>
              </div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         SECTION 6: DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC CHIẾN LƯỢC)
    ====================================================================== -->
    <section id="doi-tac" class="flatsome-container">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 overflow-hidden">
        <div class="flatsome-section-header px-3 pt-2.5">
          <h2 class="flatsome-section-title">
            <i class="fa-solid fa-handshake text-petroOrange"></i>
            <span>DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU CHÍNH HÃNG</span>
          </h2>
          <span class="text-xs text-slate-500 pr-2 pb-1 hidden sm:inline">Hợp tác phân phối chính thức tại Đà Nẵng</span>
        </div>

        <div class="p-3.5 sm:p-5 grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-petroBlue text-white font-extrabold flex items-center justify-center text-sm mb-1.5">P</div>
            <div class="text-xs font-extrabold text-petroBlue">PETROLIMEX GAS</div>
            <div class="text-[10px] text-slate-500">Tổng Công Ty Gas Petrolimex</div>
          </div>
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-petroRed text-white font-extrabold flex items-center justify-center text-sm mb-1.5">PV</div>
            <div class="text-xs font-extrabold text-slate-800">PETROVIETNAM GAS</div>
            <div class="text-[10px] text-slate-500">Khí Hóa Lỏng Dầu Khí</div>
          </div>
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-petroOrange text-white font-extrabold flex items-center justify-center text-sm mb-1.5">RN</div>
            <div class="text-xs font-extrabold text-slate-800">BẾP GAS RINNAI</div>
            <div class="text-[10px] text-slate-500">Thương Hiệu Nhật Bản</div>
          </div>
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-emerald-600 text-white font-extrabold flex items-center justify-center text-sm mb-1.5">SH</div>
            <div class="text-xs font-extrabold text-slate-800">SUNHOUSE</div>
            <div class="text-[10px] text-slate-500">Thiết Bị Nhà Bếp Cao Cấp</div>
          </div>
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-blue-700 text-white font-extrabold flex items-center justify-center text-sm mb-1.5">NM</div>
            <div class="text-xs font-extrabold text-slate-800">NAMILUX</div>
            <div class="text-[10px] text-slate-500">Bếp Gas & Van An Toàn</div>
          </div>
          <div class="rounded-lg border border-slate-200 p-3 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-petroBlue transition">
            <div class="w-10 h-10 rounded-full bg-amber-600 text-white font-extrabold flex items-center justify-center text-sm mb-1.5">PL</div>
            <div class="text-xs font-extrabold text-slate-800">PALOMA & CANZY</div>
            <div class="text-[10px] text-slate-500">Bếp Âm & Bếp Dương</div>
          </div>
        </div>
      </div>
    </section>

    <!-- =====================================================================
         SECTION 7: ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ
         Địa chỉ: 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng
    ====================================================================== -->
    <section id="ban-do-lien-he" class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 md:gap-6">
        
        <!-- Cột Fanpage Facebook Ngoài Trang Chủ (5/12) -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col">
          <div class="flatsome-section-header px-3 pt-2.5">
            <h2 class="flatsome-section-title">
              <i class="fa-brands fa-facebook text-white"></i>
              <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
            </h2>
          </div>

          <div class="p-4 flex-1 flex flex-col justify-between space-y-4">
            <!-- Card mô phỏng Fanpage trực quan + Plugin kết nối trực tiếp https://www.facebook.com/vietphap.ho.3 -->
            <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50">
              <div class="h-28 bg-gradient-to-r from-petroDark via-petroBlue to-petroOrange p-4 flex items-end relative">
                <div class="flex items-center gap-3">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w300" 
                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1AH_S744i4E3BjzoZzhuWrcFEELQHipd7';"
                    alt="Avatar Fanpage Gas Tín Nghĩa Phát" 
                    class="w-16 h-16 rounded-xl bg-white p-1 border-2 border-white shadow-md object-contain shrink-0"
                  />
                  <div class="text-white">
                    <h3 class="font-extrabold text-sm sm:text-base leading-tight">
                      Công Ty TNHH Gas Tín Nghĩa Phát
                    </h3>
                    <p class="text-xs text-amber-200 font-medium">Hồ Viết Pháp • Đại lý Gas & Bếp Gas Đà Nẵng</p>
                  </div>
                </div>
              </div>

              <div class="p-3.5 space-y-3 text-xs sm:text-sm">
                <p class="text-slate-700 leading-relaxed">
                  Kết nối trực tiếp qua trang Facebook chính thức để xem hình ảnh lắp đặt thực tế, chương trình khuyến mãi đổi gas và nhắn tin đặt gas nhanh 24/7.
                </p>

                <div class="grid grid-cols-2 gap-2 pt-1">
                  <a 
                    href="https://www.facebook.com/vietphap.ho.3" 
                    target="_blank" 
                    rel="noopener noreferrer" 
                    class="inline-flex items-center justify-center gap-2 px-3 py-2.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition"
                  >
                    <i class="fa-brands fa-facebook-f"></i>
                    <span>Xem Trang Facebook</span>
                  </a>
                  <a 
                    href="https://zalo.me/0914000299" 
                    target="_blank" 
                    rel="noopener noreferrer" 
                    class="inline-flex items-center justify-center gap-2 px-3 py-2.5 rounded-lg bg-[#0068FF] hover:bg-blue-600 text-white font-bold text-xs transition"
                  >
                    <i class="fa-solid fa-comment-dots"></i>
                    <span>Nhắn Zalo Ngay</span>
                  </a>
                </div>
              </div>
            </div>

            <!-- Hình ảnh hoạt động thực tế từ Google Drive trên Fanpage -->
            <div>
              <div class="text-xs font-bold text-slate-600 mb-2">Hình ảnh sản phẩm thực tế tại cửa hàng:</div>
              <div class="grid grid-cols-4 gap-2">
                <img src="https://drive.google.com/thumbnail?id=1HZkIU2ZMwHIl2bA7_Y8iiAcAS5TcPNvE&sz=w300" alt="Ảnh thực tế 1" class="w-full h-16 object-contain bg-white border border-slate-200 rounded-lg p-1" />
                <img src="https://drive.google.com/thumbnail?id=1Y-ltDQxsFIlnztAL1Zvanarp5oZQzefY&sz=w300" alt="Ảnh thực tế 2" class="w-full h-16 object-contain bg-white border border-slate-200 rounded-lg p-1" />
                <img src="https://drive.google.com/thumbnail?id=1VtvnQ71spdutLECNJcmPdKLDJZ40AQtK&sz=w300" alt="Ảnh thực tế 3" class="w-full h-16 object-contain bg-white border border-slate-200 rounded-lg p-1" />
                <img src="https://drive.google.com/thumbnail?id=1bPzvJTEqEieTdLz-BGXvntDSvtkutf16&sz=w300" alt="Ảnh thực tế 4" class="w-full h-16 object-contain bg-white border border-slate-200 rounded-lg p-1" />
              </div>
            </div>
          </div>
        </div>

        <!-- Cột Bản Đồ Google Maps Ngoài Trang Chủ (7/12) -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col">
          <div class="flatsome-section-header px-3 pt-2.5">
            <h2 class="flatsome-section-title">
              <i class="fa-solid fa-map-location-dot text-petroOrange"></i>
              <span>BẢN ĐỒ GOOGLE MAPS TRỤ SỞ CÔNG TY</span>
            </h2>
            <a 
              href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJ6eGv69oYQjERZkg5mmtuzBE" 
              target="_blank" 
              rel="noopener noreferrer" 
              class="text-xs font-bold text-petroBlue hover:text-petroOrange pr-2 pb-1"
            >
              <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường Google Maps
            </a>
          </div>

          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between space-y-3">
            <div class="flex flex-wrap items-center justify-between gap-2 bg-petroLight/70 px-3.5 py-2.5 rounded-lg border border-blue-200 text-xs sm:text-sm">
              <div>
                <strong class="text-petroBlue">Địa chỉ:</strong> 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng
              </div>
              <div class="font-bold text-petroRed">
                <i class="fa-solid fa-phone mr-1"></i>SĐT: 0914.000.299
              </div>
            </div>

            <!-- Google Maps Embed trực tiếp خارج trang chủ -->
            <div class="w-full h-[270px] sm:h-[310px] rounded-xl overflow-hidden border border-slate-200 shadow-inner">
              <iframe 
                title="Bản đồ Công Ty TNHH Gas Tín Nghĩa Phát - 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng"
                src="https://maps.google.com/maps?q=245%20Tr%E1%BA%A7n%20Qu%C3%BD%20Kho%C3%A1ch,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                class="w-full h-full border-0" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>
        </div>

      </div>
    </section>

  </main>

  <!-- =====================================================================
       FLATSOME FOOTER (#footer)
  ====================================================================== -->
  <footer id="footer" class="bg-petroDark text-white mt-8 border-t-4 border-petroOrange">
    <div class="flatsome-container py-8 md:py-10">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6">
        
        <!-- Thông tin công ty (5 cột) -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <img 
              src="https://drive.google.com/thumbnail?id=1AH_S744i4E3BjzoZzhuWrcFEELQHipd7&sz=w300" 
              onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1AH_S744i4E3BjzoZzhuWrcFEELQHipd7';"
              alt="Logo Công Ty TNHH Gas Tín Nghĩa Phát" 
              class="w-11 h-11 rounded-lg bg-white p-1 object-contain shrink-0"
            />
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-white uppercase">
                CÔNG TY TNHH GAS TÍN NGHĨA PHÁT
              </h3>
              <p class="text-xs text-amber-300 font-semibold">Website: gastinnghiaphat.com</p>
            </div>
          </div>
          <ul class="space-y-2 text-xs sm:text-sm text-blue-100">
            <li><i class="fa-solid fa-id-card text-petroOrange mr-2 w-4"></i>Mã số thuế: <strong>0401969539</strong> — Đại diện: <strong>Hồ Viết Pháp</strong></li>
            <li><i class="fa-solid fa-location-dot text-petroOrange mr-2 w-4"></i>Địa chỉ: <strong>245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng</strong></li>
            <li><i class="fa-solid fa-phone-volume text-petroOrange mr-2 w-4"></i>Điện thoại / Hotline / Zalo: <a href="tel:0914000299" class="font-bold text-amber-300 underline">0914.000.299</a></li>
            <li><i class="fa-brands fa-facebook text-petroOrange mr-2 w-4"></i>Fanpage: <a href="https://www.facebook.com/vietphap.ho.3" target="_blank" rel="noopener noreferrer" class="underline hover:text-amber-300">facebook.com/vietphap.ho.3</a></li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm (4 cột) -->
        <div class="lg:col-span-4 space-y-2.5">
          <h4 class="text-sm font-extrabold uppercase text-amber-300 border-b border-blue-800 pb-2">
            DANH MỤC SẢN PHẨM CHÍNH
          </h4>
          <ul class="grid grid-cols-2 gap-2 text-xs text-blue-100">
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-petrolimex')" class="hover:text-amber-300">• Bình Gas Petrolimex</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('binh-gas-cong-nghiep')" class="hover:text-amber-300">• Bình Gas Công Nghiệp</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am')" class="hover:text-amber-300">• Bếp Gas Âm</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-am-kinh')" class="hover:text-amber-300">• Bếp Gas Âm Kính</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('bep-gas-duong')" class="hover:text-amber-300">• Bếp Gas Dương</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('bo-binh-bep-gas')" class="hover:text-amber-300">• Bộ Bình Bếp Gas</a></li>
            <li><a href="#san-pham-trang-chu" onclick="filterCategory('linh-kien-bep')" class="hover:text-amber-300">• Linh Kiện Bếp & Van</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">• Báo Giá Gas Sỉ & Lẻ</a></li>
          </ul>
        </div>

        <!-- Cam kết dịch vụ (3 cột) -->
        <div class="lg:col-span-3 space-y-2.5">
          <h4 class="text-sm font-extrabold uppercase text-amber-300 border-b border-blue-800 pb-2">
            CAM KẾT CHẤT LƯỢNG
          </h4>
          <ul class="space-y-2 text-xs text-blue-100">
            <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Giao gas siêu tốc 10 - 15 phút</li>
            <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Bình gas đủ ký, niêm phong chuẩn</li>
            <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Bảo trì, kiểm tra rò rỉ gas miễn phí</li>
            <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Hóa đơn VAT đầy đủ cho doanh nghiệp</li>
          </ul>
        </div>

      </div>
    </div>

    <!-- Bản quyền chân trang -->
    <div class="bg-[#002244] py-3 text-center text-xs text-blue-200 border-t border-blue-900 px-3">
      Copyright © <strong>CÔNG TY TNHH GAS TÍN NGHĨA PHÁT</strong> (<strong>gastinnghiaphat.com</strong>) — 245 Trần Quý Khoách, Phường Hòa Khánh, TP Đà Nẵng. ĐT: <strong>0914.000.299</strong>.
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       Tương thích hoàn hảo trên máy tính và điện thoại, không gây tràn viền
  ====================================================================== -->
  <div class="fixed bottom-4 right-3 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/vietphap.ho.3" 
      target="_blank" 
      rel="noopener noreferrer"
      aria-label="Facebook Gas Tín Nghĩa Phát"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm shrink-0">
        <i class="fa-brands fa-facebook-f"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Facebook</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a 
      href="https://zalo.me/0914000299" 
      target="_blank" 
      rel="noopener noreferrer"
      aria-label="Zalo 0914.000.299"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px] shrink-0">
        Zalo
      </span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Zalo: 0914.000.299</span>
    </a>

    <!-- Nút Gọi Hotline Nổi Bật -->
    <a 
      href="tel:0914000299" 
      aria-label="Gọi ngay 0914.000.299"
      class="pulse-btn flex items-center gap-2 bg-gradient-to-r from-petroRed to-petroOrange text-white rounded-full px-3.5 py-2.5 shadow-xl font-extrabold text-xs sm:text-sm"
    >
      <span class="w-6 h-6 rounded-full bg-white text-petroRed flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span>0914.000.299</span>
    </a>

  </div>

  <!-- =====================================================================
       MODAL GIỎ HÀNG & ĐẶT HÀNG NHANH (Không dùng alert)
  ====================================================================== -->
  <div id="cart-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-3 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="bg-petroBlue text-white px-4 py-3 flex items-center justify-between">
        <h3 class="font-bold text-sm sm:text-base flex items-center gap-2">
          <i class="fa-solid fa-cart-shopping text-petroOrange"></i>
          <span>ĐƠN ĐẶT GAS & SẢN PHẨM ĐÃ CHỌN</span>
        </h3>
        <button type="button" onclick="closeCartModal()" class="w-8 h-8 rounded-lg bg-white/10 hover:bg-white/20 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 max-h-[65vh] overflow-y-auto space-y-3">
        <div id="cart-items-list" class="space-y-2 text-xs sm:text-sm"></div>
        <div class="pt-3 border-t border-slate-200 flex items-center justify-between font-extrabold text-sm text-petroBlue">
          <span>Tổng cộng tạm tính:</span>
          <span id="cart-total-price" class="text-petroRed text-base">0₫</span>
        </div>
        <div class="bg-petroLight/70 p-3 rounded-lg text-xs text-slate-700 space-y-1">
          <div class="font-bold text-petroBlue">Giao hàng tận nơi tại Đà Nẵng:</div>
          <div>Gọi xác nhận nhanh qua Hotline/Zalo: <strong class="text-petroRed">0914.000.299</strong> hoặc nhấn nút Đặt Hàng bên dưới để chuyển vào Form Báo Giá.</div>
        </div>
      </div>
      <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 flex items-center justify-end gap-2">
        <button type="button" onclick="closeCartModal()" class="px-3.5 py-2 rounded-lg border border-slate-300 text-xs font-semibold text-slate-600 hover:bg-slate-100">
          Đóng
        </button>
        <button type="button" onclick="transferCartToQuote()" class="px-4 py-2 rounded-lg bg-petroOrange hover:bg-orange-600 text-white text-xs font-bold">
          Tiến hành Đặt Hàng Ngay
        </button>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT: DỮ LIỆU 8 ẢNH SẢN PHẨM THỰC TẾ GOOGLE DRIVE & CHỨC NĂNG
  ====================================================================== -->
  <script>
    // Danh sách 8 sản phẩm sử dụng đúng 8 file ảnh thực tế từ Google Drive
    // kết hợp đúng danh mục và tên sản phẩm chuẩn web mẫu gaspetrolimex.com
    const productsData = [
      {
        id: 'sp-1',
        name: 'Bình Gas Petrolimex 12kg Van Chụp Chính Hãng',
        category: 'binh-gas-petrolimex',
        categoryLabel: 'Bình Gas Petrolimex',
        section: 'gas',
        oldPrice: 480000,
        price: 420000,
        discountPercent: 13,
        driveId: '1HZkIU2ZMwHIl2bA7_Y8iiAcAS5TcPNvE'
      },
      {
        id: 'sp-2',
        name: 'Bình Gas Petrolimex 12kg Van Ngang An Toàn',
        category: 'binh-gas-petrolimex',
        categoryLabel: 'Bình Gas Petrolimex',
        section: 'gas',
        oldPrice: 480000,
        price: 420000,
        discountPercent: 13,
        driveId: '16aQp0HPdk_vgsvnubIDcEdBIGD-bkzrf'
      },
      {
        id: 'sp-3',
        name: 'Bình Gas Công Nghiệp 45kg Petrolimex Chính Hãng',
        category: 'binh-gas-cong-nghiep',
        categoryLabel: 'Bình Gas Công Nghiệp',
        section: 'gas',
        oldPrice: 1950000,
        price: 1690000,
        discountPercent: 13,
        driveId: '1Y-ltDQxsFIlnztAL1Zvanarp5oZQzefY'
      },
      {
        id: 'sp-4',
        name: 'Bộ Bình Gas Petrolimex 12kg Kèm Van Dây An Toàn',
        category: 'bo-binh-bep-gas',
        categoryLabel: 'Bộ Bình Bếp Gas',
        section: 'gas',
        oldPrice: 1150000,
        price: 950000,
        discountPercent: 17,
        driveId: '1tHYEOcc4QvgYx1MvOY5y7SdBW0KjVMnx'
      },
      {
        id: 'sp-5',
        name: 'Bộ Bếp Gas Đôi Kính & Bình Gas Petrolimex 12kg',
        category: 'bo-binh-bep-gas',
        categoryLabel: 'Bộ Bình Bếp Gas',
        section: 'stoves',
        oldPrice: 1380000,
        price: 1150000,
        discountPercent: 17,
        driveId: '1wQxFDhHDz3wYCizA6eG07K0_6x_uTo5F'
      },
      {
        id: 'sp-6',
        name: 'Bếp Gas Âm Kính Cường Lực Cao Cấp Chính Hãng',
        category: 'bep-gas-am-kinh',
        categoryLabel: 'Bếp Gas Âm Kính',
        section: 'stoves',
        oldPrice: 2250000,
        price: 1850000,
        discountPercent: 18,
        driveId: '1SZABqp4E5Gvqz-PYIUt3fLh8p2nKNHrR'
      },
      {
        id: 'sp-7',
        name: 'Bếp Gas Dương Đôi Rinnai Mặt Men Chính Hãng',
        category: 'bep-gas-duong',
        categoryLabel: 'Bếp Gas Dương',
        section: 'stoves',
        oldPrice: 1200000,
        price: 980000,
        discountPercent: 18,
        driveId: '1VtvnQ71spdutLECNJcmPdKLDJZ40AQtK'
      },
      {
        id: 'sp-8',
        name: 'Bếp Gas Âm Đôi & Bộ Van Dây Gas Chống Cháy Nổ',
        category: 'bep-gas-am',
        categoryLabel: 'Bếp Gas Âm & Linh Kiện',
        section: 'stoves',
        oldPrice: 1890000,
        price: 1550000,
        discountPercent: 18,
        driveId: '1bPzvJTEqEieTdLz-BGXvntDSvtkutf16'
      }
    ];

    let currentCategory = 'all';
    let currentSearchQuery = '';
    let cart = [];

    function formatCurrencyVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ',') + '₫';
    }

    // Tạo thẻ HTML cho từng sản phẩm theo đúng chuẩn Flatsome Product Box
    // Không có nhãn dán phụ, chỉ có đúng duy nhất % giảm giá góc trên bên trái
    function createProductCardHTML(product) {
      const primaryImgUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800`;
      const fallbackImgUrl = `https://lh3.googleusercontent.com/d/${product.driveId}`;

      return `
        <div class="ux-product-box group bg-white rounded-xl border border-slate-200 hover:border-petroBlue hover:shadow-md transition flex flex-col justify-between overflow-hidden">
          <div>
            <!-- Box Image với Flatsome % giảm giá góc trên bên trái -->
            <div class="box-image relative w-full h-40 sm:h-48 md:h-52 bg-white p-2.5 flex items-center justify-center border-b border-slate-100 overflow-hidden">
              <div class="flatsome-sale-badge">-${product.discountPercent}%</div>
              <img 
                src="${primaryImgUrl}" 
                onerror="this.onerror=null;this.src='${fallbackImgUrl}';"
                alt="${product.name}" 
                loading="lazy"
                class="max-h-full max-w-full object-contain group-hover:scale-105 transition-transform duration-300"
              />
            </div>

            <!-- Box Text: Tên sản phẩm đầy đủ không bị cắt hay tràn chữ -->
            <div class="box-text p-2.5 sm:p-3.5">
              <div class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase mb-1">
                ${product.categoryLabel}
              </div>
              <h3 class="product-title-full text-[12.5px] sm:text-sm md:text-[15px] font-bold text-slate-800 group-hover:text-petroBlue mb-2">
                ${product.name}
              </h3>
            </div>
          </div>

          <!-- Giá gốc, Giá giảm & Nút đặt mua -->
          <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1">
            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2.5">
              <del class="text-[11px] sm:text-xs text-slate-400 font-medium">${formatCurrencyVND(product.oldPrice)}</del>
              <ins class="no-underline text-xs sm:text-sm md:text-base font-extrabold text-petroRed">${formatCurrencyVND(product.price)}</ins>
            </div>
            <div class="grid grid-cols-2 gap-1.5">
              <button 
                type="button" 
                onclick="addToCart('${product.id}')" 
                class="w-full py-1.5 px-2 rounded-lg bg-petroBlue hover:bg-petroDark text-white font-bold text-[11px] sm:text-xs transition flex items-center justify-center gap-1"
              >
                <i class="fa-solid fa-cart-plus"></i>
                <span>Đặt Mua</span>
              </button>
              <a 
                href="tel:0914000299" 
                class="w-full py-1.5 px-2 rounded-lg bg-petroLight hover:bg-petroOrange hover:text-white text-petroBlue font-bold text-[11px] sm:text-xs transition flex items-center justify-center gap-1 text-center"
              >
                <i class="fa-solid fa-phone"></i>
                <span>Gọi Đổi</span>
              </a>
            </div>
          </div>
        </div>
      `;
    }

    function renderProducts() {
      const gasGrid = document.getElementById('product-grid-gas');
      const stovesGrid = document.getElementById('product-grid-stoves');

      const filtered = productsData.filter(item => {
        const matchCat =
          currentCategory === 'all' ||
          item.category === currentCategory ||
          (currentCategory === 'linh-kien-bep' && (item.id === 'sp-4' || item.id === 'sp-8'));
        const matchSearch =
          !currentSearchQuery ||
          item.name.toLowerCase().includes(currentSearchQuery.toLowerCase()) ||
          item.categoryLabel.toLowerCase().includes(currentSearchQuery.toLowerCase());
        return matchCat && matchSearch;
      });

      const gasItems = filtered.filter(i => i.section === 'gas');
      const stoveItems = filtered.filter(i => i.section === 'stoves');

      // Nếu lọc theo 1 danh mục cụ thể, hiển thị linh hoạt để khách dễ nhìn
      if (currentCategory !== 'all' || currentSearchQuery !== '') {
        gasGrid.innerHTML = filtered.length
          ? filtered.map(createProductCardHTML).join('')
          : `<div class="col-span-full py-8 text-center text-xs sm:text-sm text-slate-500">Không tìm thấy sản phẩm phù hợp. Vui lòng gọi <strong>0914.000.299</strong> để được tư vấn trực tiếp.</div>`;
        stovesGrid.parentElement.classList.add('hidden');
      } else {
        stovesGrid.parentElement.classList.remove('hidden');
        gasGrid.innerHTML = gasItems.map(createProductCardHTML).join('');
        stovesGrid.innerHTML = stoveItems.map(createProductCardHTML).join('');
      }
    }

    function filterCategory(categorySlug) {
      currentCategory = categorySlug;
      document.querySelectorAll('.cat-filter-btn').forEach(btn => {
        const isSelected = btn.getAttribute('data-cat-btn') === categorySlug;
        if (isSelected) {
          btn.className = 'cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-bold bg-petroBlue text-white border border-petroBlue transition';
        } else {
          btn.className = 'cat-filter-btn nav-cat-item px-3 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold bg-slate-50 hover:bg-petroLight text-slate-700 border border-slate-200 transition';
        }
      });
      renderProducts();
    }

    function filterProductsBySearch(query) {
      currentSearchQuery = (query || '').trim();
      renderProducts();
    }

    // Chức năng Giỏ hàng & Đặt hàng nhanh
    function addToCart(productId) {
      const product = productsData.find(p => p.id === productId);
      if (!product) return;
      const existing = cart.find(item => item.id === productId);
      if (existing) {
        existing.qty += 1;
      } else {
        cart.push({ ...product, qty: 1 });
      }
      updateCartUI();
      openCartModal();
    }

    function changeCartQty(productId, delta) {
      const idx = cart.findIndex(i => i.id === productId);
      if (idx === -1) return;
      cart[idx].qty += delta;
      if (cart[idx].qty <= 0) {
        cart.splice(idx, 1);
      }
      updateCartUI();
    }

    function updateCartUI() {
      const countBadge = document.getElementById('cart-count-badge');
      const listEl = document.getElementById('cart-items-list');
      const totalEl = document.getElementById('cart-total-price');

      const totalCount = cart.reduce((sum, i) => sum + i.qty, 0);
      const totalPrice = cart.reduce((sum, i) => sum + i.price * i.qty, 0);

      countBadge.textContent = totalCount;
      totalEl.textContent = formatCurrencyVND(totalPrice);

      if (cart.length === 0) {
        listEl.innerHTML = `<div class="py-6 text-center text-slate-500">Chưa có sản phẩm nào trong giỏ hàng.</div>`;
        return;
      }

      listEl.innerHTML = cart.map(item => `
        <div class="flex items-center justify-between gap-2 p-2.5 rounded-lg border border-slate-200 bg-slate-50">
          <div class="min-w-0 flex-1">
            <div class="font-bold text-slate-800 text-xs sm:text-sm">${item.name}</div>
            <div class="text-petroRed font-semibold text-xs">${formatCurrencyVND(item.price)} x ${item.qty}</div>
          </div>
          <div class="flex items-center gap-1.5 shrink-0">
            <button type="button" onclick="changeCartQty('${item.id}', -1)" class="w-6 h-6 rounded bg-white border border-slate-300 font-bold text-xs">-</button>
            <span class="w-6 text-center font-bold text-xs">${item.qty}</span>
            <button type="button" onclick="changeCartQty('${item.id}', 1)" class="w-6 h-6 rounded bg-white border border-slate-300 font-bold text-xs">+</button>
          </div>
        </div>
      `).join('');
    }

    function openCartModal() {
      updateCartUI();
      const modal = document.getElementById('cart-modal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeCartModal() {
      const modal = document.getElementById('cart-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function transferCartToQuote() {
      const summary = cart.map(i => `${i.name} (SL: ${i.qty} - ${formatCurrencyVND(i.price * i.qty)})`).join('; ');
      const noteEl = document.getElementById('quote-note');
      if (summary && noteEl) {
        noteEl.value = `Đặt hàng từ giỏ hàng: ${summary}`;
      }
      closeCartModal();
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      document.getElementById('quote-name').focus();
    }

    // Xử lý gửi Form Báo Giá ở trang chủ
    function submitQuoteForm(event) {
      event.preventDefault();
      const name = document.getElementById('quote-name').value.trim();
      const phone = document.getElementById('quote-phone').value.trim();
      const category = document.getElementById('quote-category').value;
      const address = document.getElementById('quote-address').value.trim();
      const feedback = document.getElementById('quote-feedback');

      feedback.classList.remove('hidden');
      feedback.innerHTML = `
        <div class="flex items-start gap-2">
          <i class="fa-solid fa-circle-check text-emerald-600 mt-0.5 text-base"></i>
          <div>
            <strong>Đã tiếp nhận yêu cầu của ${name} (${phone})!</strong><br/>
            Nội dung: <em>${category}</em> ${address ? 'tại ' + address : ''}. Bộ phận điều phối <strong>CÔNG TY TNHH GAS TÍN NGHĨA PHÁT (0914.000.299)</strong> sẽ liên hệ lại ngay!
          </div>
        </div>
      `;
      event.target.reset();
    }

    // Drawer Menu trên điện thoại
    function toggleMobileDrawer() {
      const drawer = document.getElementById('mobile-drawer');
      const backdrop = document.getElementById('mobile-drawer-backdrop');
      const isClosed = drawer.classList.contains('-translate-x-full');
      if (isClosed) {
        drawer.classList.remove('-translate-x-full');
        backdrop.classList.remove('hidden');
      } else {
        drawer.classList.add('-translate-x-full');
        backdrop.classList.add('hidden');
      }
    }

    // Điều khiển 2 Banner tự trượt chuyên nghiệp
    let activeBannerIndex = 0;
    let bannerTimer = null;

    function updateBannerSlides() {
      const slides = document.querySelectorAll('.hero-slide');
      const dot0 = document.getElementById('slider-dot-0');
      const dot1 = document.getElementById('slider-dot-1');

      slides.forEach((slide, index) => {
        if (index === activeBannerIndex) {
          slide.classList.remove('opacity-0', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0');
        }
      });

      if (activeBannerIndex === 0) {
        dot0.className = 'w-6 h-2 rounded-full bg-petroOrange transition-all';
        dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
      } else {
        dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
        dot1.className = 'w-6 h-2 rounded-full bg-petroOrange transition-all';
      }
    }

    function nextBannerSlide() {
      activeBannerIndex = (activeBannerIndex + 1) % 2;
      updateBannerSlides();
      resetBannerTimer();
    }

    function prevBannerSlide() {
      activeBannerIndex = (activeBannerIndex - 1 + 2) % 2;
      updateBannerSlides();
      resetBannerTimer();
    }

    function goToBannerSlide(index) {
      activeBannerIndex = index;
      updateBannerSlides();
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        activeBannerIndex = (activeBannerIndex + 1) % 2;
        updateBannerSlides();
      }, 5000);
    }

    window.onload = function () {
      renderProducts();
      resetBannerTimer();
    };
  </script>
</body>
</html>
