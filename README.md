<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SALA Architecture | Công Ty TNHH Tư Vấn Thiết Kế Xây Dựng Đà Nẵng - salaarchitecture.com</title>
  <meta name="description" content="Công ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture Đà Nẵng - Chuyên thiết kế kiến trúc xanh, xây nhà trọn gói, thi công phần thô, hoàn thiện biệt thự và nhà phố tại Đà Nẵng. Hotline: 0949.857.007." />

  <!-- Ảnh Thumbnail (Open Graph / Chia sẻ liên kết) sử dụng Logo SALA Architecture -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://salaarchitecture.com/" />
  <meta property="og:site_name" content="SALA Architecture" />
  <meta property="og:title" content="Công Ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture - Đà Nẵng" />
  <meta property="og:description" content="Thiết kế kiến trúc xanh & Thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 04 Phan Thành Tài, Hải Châu, Đà Nẵng. Hotline: 0949.857.007." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w800" />
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w800" />
  <meta property="og:image:alt" content="Logo SALA Architecture" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="SALA Architecture - Thiết Kế & Xây Dựng Đà Nẵng" />
  <meta name="twitter:description" content="Công ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture - 04 Phan Thành Tài, Hải Châu, Đà Nẵng." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w800" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w256" />

  <!-- Font Inter hỗ trợ tiếng Việt sắc nét -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome 6 cho biểu tượng giao diện -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            sala: {
              50: '#f1f8f3',
              100: '#ddeee2',
              200: '#bdddc7',
              300: '#91c4a2',
              400: '#5fa378',
              500: '#398456',
              600: '#276942',
              700: '#1f5335',
              800: '#1a422b',
              900: '#143623',
            },
            gold: {
              400: '#d4b475',
              500: '#b8924a',
              600: '#9c7838',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Thiết lập chuẩn hộp và chống tràn viền / lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1e293b;
      background-color: #ffffff;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      width: 100%;
      max-width: 100%;
      -webkit-font-smoothing: antialiased;
    }

    /* Khung giao diện Flatsome: 95% màn hình trên máy tính, cân đối trên điện thoại */
    .sala-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .sala-container {
        width: 96%;
        max-width: 96%;
        padding-left: 12px;
        padding-right: 12px;
      }
    }

    @media (min-width: 1024px) {
      .sala-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Header menu 1 hàng gọn gàng trên máy tính, không xuống dòng từng mục */
    .desktop-nav-link {
      white-space: nowrap;
      flex-shrink: 0;
      transition: color 0.2s ease, background-color 0.2s ease;
    }

    /* Slider 2 banner tự trượt đồng đều kích thước tuyệt đối */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
    }

    .hero-slides-grid {
      display: grid;
      grid-template-columns: 100%;
      grid-template-rows: 1fr;
    }

    .hero-slide-item {
      grid-area: 1 / 1 / 2 / 2;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
      display: flex;
      align-items: center;
      width: 100%;
    }

    .hero-slide-item.active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 2;
    }

    /* Hiệu ứng phóng nhẹ ảnh giống Flatsome UX Builder */
    .flatsome-card-img {
      transition: transform 0.55s cubic-bezier(0.22, 1, 0.36, 1);
    }

    .flatsome-card:hover .flatsome-card-img {
      transform: scale(1.06);
    }

    /* Đường gạch chân tiêu đề đặc trưng Flatsome */
    .section-divider {
      width: 56px;
      height: 3px;
      background: linear-gradient(90deg, #1f5335 0%, #b8924a 100%);
      border-radius: 999px;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes salaPulse {
      0% {
        box-shadow: 0 0 0 0 rgba(31, 83, 53, 0.45);
      }
      70% {
        box-shadow: 0 0 0 12px rgba(31, 83, 53, 0);
      }
      100% {
        box-shadow: 0 0 0 0 rgba(31, 83, 53, 0);
      }
    }

    .hotline-pulse {
      animation: salaPulse 2.2s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn mượt */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="bg-white text-slate-800">

  <!-- ==================== HEADER (CHUẨN FLATSOME, KHÔNG NÚT GỌI NGAY, MENU 1 HÀNG) ==================== -->
  <header id="site-header" class="sticky top-0 z-40 w-full bg-white/95 backdrop-blur-md border-b border-slate-200/80 shadow-sm">
    <div class="sala-container">
      <div class="flex items-center justify-between gap-3 h-16 lg:h-[74px]">
        <!-- Logo SALA Architecture (chỉnh gọn nhỏ tinh tế) -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 py-1 focus:outline-none">
          <img
            src="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w400"
            data-drive-id="1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype"
            alt="Logo SALA Architecture"
            class="drive-img h-9 sm:h-10 lg:h-11 w-auto max-w-[125px] object-contain rounded-md"
          />
          <div class="flex flex-col leading-tight">
            <span class="text-sm sm:text-[15px] font-extrabold tracking-tight text-sala-800 whitespace-nowrap">SALA ARCHITECTURE</span>
            <span class="text-[10px] sm:text-[11px] font-medium text-slate-500 whitespace-nowrap">Thiết Kế &amp; Xây Dựng Xanh</span>
          </div>
        </a>

        <!-- Menu Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng -->
        <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end gap-0.5 xl:gap-1.5 min-w-0">
          <a href="#trang-chu" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-sala-800 hover:text-gold-600 rounded-md">Trang chủ</a>
          <a href="#gioi-thieu" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Giới thiệu</a>
          <a href="#danh-muc-dich-vu" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Dịch vụ</a>
          <a href="#thiet-ke-xay-dung" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Thiết kế</a>
          <a href="#thi-cong-thuc-te" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Thi công thực tế</a>
          <a href="#du-an-da-nang" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Dự án Đà Nẵng</a>
          <a href="#bao-gia" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Báo giá</a>
          <a href="#tin-tuc" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Bài viết</a>
          <a href="#lien-he" class="desktop-nav-link px-2 xl:px-2.5 py-2 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-sala-700 rounded-md">Liên hệ</a>
        </nav>

        <!-- Nút mở Menu Mobile -->
        <button
          id="mobile-menu-btn"
          type="button"
          aria-label="Mở danh mục"
          class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-sala-800 hover:bg-sala-50 transition"
        >
          <i class="fa-solid fa-bars text-lg"></i>
        </button>
      </div>
    </div>

    <!-- Drawer Menu Mobile -->
    <div id="mobile-menu" class="hidden lg:hidden border-t border-slate-200 bg-white shadow-lg">
      <div class="sala-container py-3 flex flex-col gap-1">
        <a href="#trang-chu" class="mobile-nav-link px-3 py-2.5 text-sm font-semibold text-sala-800 bg-sala-50 rounded-lg">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Giới thiệu</a>
        <a href="#danh-muc-dich-vu" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Danh mục dịch vụ</a>
        <a href="#thiet-ke-xay-dung" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Hình ảnh thiết kế xây dựng</a>
        <a href="#thi-cong-thuc-te" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Công trình thi công thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Các dự án ở Đà Nẵng</a>
        <a href="#bao-gia" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Bảng báo giá</a>
        <a href="#tin-tuc" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Bài viết &amp; Kinh nghiệm</a>
        <a href="#lien-he" class="mobile-nav-link px-3 py-2.5 text-sm font-medium text-slate-700 hover:bg-sala-50 hover:text-sala-800 rounded-lg">Liên hệ &amp; Báo giá</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM GỌN TRONG BANNER, CÁCH XA VIỀN) ==================== -->
    <section aria-label="Banner giới thiệu SALA Architecture" class="w-full pt-3 pb-4 sm:pt-4 sm:pb-6 bg-slate-50">
      <div class="sala-container">
        <div class="hero-slider-wrapper rounded-2xl shadow-md bg-sala-900 overflow-hidden">
          <div id="hero-slides-grid" class="hero-slides-grid">

            <!-- Banner 1 -->
            <div class="hero-slide-item active relative min-h-[340px] sm:min-h-[430px] lg:min-h-[500px] xl:min-h-[540px]">
              <img
                src="https://lh3.googleusercontent.com/d/1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP=w1600"
                data-drive-id="1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP"
                alt="Thiết kế kiến trúc xanh SALA Architecture Đà Nẵng"
                class="drive-img absolute inset-0 w-full h-full object-cover object-center"
              />
              <!-- Lớp phủ tối tinh tế để chữ nổi bật tuyệt đối -->
              <div class="absolute inset-0 bg-gradient-to-r from-sala-900/90 via-sala-900/72 to-sala-900/35"></div>

              <!-- Nội dung chữ cách xa 4 viền banner an toàn trên cả điện thoại & máy tính -->
              <div class="relative z-10 w-full px-10 py-12 sm:px-16 sm:py-16 lg:px-24 lg:py-20">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-[0.16em] text-gold-400 mb-2.5 sm:mb-3">
                    Công Ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture
                  </p>
                  <h1 class="text-xl sm:text-3xl lg:text-4xl xl:text-[42px] font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                    Kiến Tạo Không Gian Sống Xanh &amp; Bền Vững Tại Đà Nẵng
                  </h1>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-100/95 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                    Tiên phong giải pháp thiết kế kiến trúc xanh, tối ưu ánh sáng tự nhiên và thông gió. Cam kết thi công chuẩn kỹ thuật, minh bạch vật tư và bàn giao đúng tiến độ.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#form-bao-gia" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-bold shadow transition">
                      <span>Nhận Tư Vấn &amp; Báo Giá</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-white/15 hover:bg-white/25 backdrop-blur-sm border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                      <span>Xem Dự Án Thực Tế</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- Banner 2 (Kích thước đồng bộ 100% với Banner 1) -->
            <div class="hero-slide-item relative min-h-[340px] sm:min-h-[430px] lg:min-h-[500px] xl:min-h-[540px]">
              <img
                src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                alt="Thi công xây nhà trọn gói SALA Architecture Đà Nẵng"
                class="drive-img absolute inset-0 w-full h-full object-cover object-center"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-sala-900/90 via-sala-900/72 to-sala-900/35"></div>

              <!-- Nội dung chữ cách xa 4 viền banner an toàn trên cả điện thoại & máy tính -->
              <div class="relative z-10 w-full px-10 py-12 sm:px-16 sm:py-16 lg:px-24 lg:py-20">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs lg:text-sm font-semibold uppercase tracking-[0.16em] text-gold-400 mb-2.5 sm:mb-3">
                    Xây Nhà Trọn Gói Chìa Khóa Trao Tay — salaarchitecture.com
                  </p>
                  <h2 class="text-xl sm:text-3xl lg:text-4xl xl:text-[42px] font-extrabold text-white leading-snug sm:leading-tight mb-3 sm:mb-4">
                    Thiết Kế Tận Tâm — Thi Công Chuẩn Mực — Không Phát Sinh
                  </h2>
                  <p class="text-xs sm:text-sm lg:text-base text-slate-100/95 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                    Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm trực tiếp giám sát tại công trình. Đồng hành cùng gia chủ từ bản vẽ 3D đến khi hoàn thiện bàn giao tổ ấm mơ ước.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#bao-gia" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-bold shadow transition">
                      <span>Xem Bảng Báo Giá Mới</span>
                      <i class="fa-solid fa-arrow-right text-xs"></i>
                    </a>
                    <a href="#thi-cong-thuc-te" class="inline-flex items-center justify-center gap-2 px-4 sm:px-6 py-2.5 sm:py-3 rounded-xl bg-white/15 hover:bg-white/25 backdrop-blur-sm border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                      <span>Ảnh Thi Công Thực Tế</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển slide trái/phải đặt sát mép gọn gàng, không che chữ -->
          <button
            id="hero-prev"
            type="button"
            aria-label="Banner trước"
            class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-sala-700 text-white flex items-center justify-center transition"
          >
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button
            id="hero-next"
            type="button"
            aria-label="Banner tiếp theo"
            class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-sala-700 text-white flex items-center justify-center transition"
          >
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chỉ báo chấm chuyển slide -->
          <div class="absolute bottom-3.5 sm:bottom-5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" data-slide="0" aria-label="Xem banner 1" class="hero-dot w-7 h-2 rounded-full bg-gold-400 transition-all"></button>
            <button type="button" data-slide="1" aria-label="Xem banner 2" class="hero-dot w-2.5 h-2 rounded-full bg-white/55 hover:bg-white transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== THANH DANH MỤC NHANH TRANG CHỦ (NHỎ GỌN, CHỮ KHÔNG XUỐNG DÒNG TỪNG MỤC) ==================== -->
    <section aria-label="Danh mục nhanh" class="w-full py-4 sm:py-5 bg-white border-b border-slate-100">
      <div class="sala-container">
        <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 lg:gap-2.5">
          <a href="#danh-muc-dich-vu" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Thiết kế kiến trúc
          </a>
          <a href="#danh-muc-dich-vu" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Xây nhà trọn gói
          </a>
          <a href="#danh-muc-dich-vu" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Thi công phần thô
          </a>
          <a href="#danh-muc-dich-vu" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Thi công hoàn thiện
          </a>
          <a href="#thiet-ke-xay-dung" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Thiết kế biệt thự
          </a>
          <a href="#du-an-da-nang" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Dự án Đà Nẵng
          </a>
          <a href="#thi-cong-thuc-te" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Thi công thực tế
          </a>
          <a href="#bao-gia" class="whitespace-nowrap px-3 sm:px-3.5 py-1.5 sm:py-2 rounded-lg bg-sala-50 hover:bg-sala-700 text-sala-800 hover:text-white border border-sala-200/70 text-[11px] sm:text-xs font-semibold transition">
            Báo giá xây nhà
          </a>
        </div>
      </div>
    </section>

    <!-- ==================== GIỚI THIỆU CÔNG TY SALA ARCHITECTURE (PHONG CÁCH KIẾN TRÚC UY VŨ) ==================== -->
    <section id="gioi-thieu" class="w-full py-10 sm:py-14 bg-white">
      <div class="sala-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center">
          <!-- Cột thông tin giới thiệu -->
          <div class="lg:col-span-6">
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-2">Về SALA Architecture</p>
            <h2 class="text-2xl sm:text-3xl font-extrabold text-sala-900 leading-snug mb-3">
              Công Ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture
            </h2>
            <div class="section-divider mb-5"></div>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-4">
              Khởi nguồn từ triết lý <strong>Thiết Kế Xanh SALA</strong>, chúng tôi kiến tạo những công trình nhà phố, biệt thự và căn hộ hài hòa giữa thẩm mỹ hiện đại, công năng thông minh và thiên nhiên trong lành tại thành phố Đà Nẵng cùng khu vực miền Trung.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-6">
              Với phương châm <strong>Uy tín – Chất lượng – Tận tâm</strong>, đội ngũ kiến trúc sư và kỹ sư SALA Architecture cam kết minh bạch trong từng hạng mục vật tư, kiểm soát kỹ thuật nghiêm ngặt tại công trường và bảo hành dài hạn cho mọi tổ ấm.
            </p>

            <!-- Chỉ số năng lực gọn gàng -->
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
              <div class="p-3.5 rounded-xl bg-sala-50 border border-sala-100 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-sala-800">8+</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Năm kinh nghiệm</div>
              </div>
              <div class="p-3.5 rounded-xl bg-sala-50 border border-sala-100 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-sala-800">150+</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Công trình thực tế</div>
              </div>
              <div class="p-3.5 rounded-xl bg-sala-50 border border-sala-100 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-sala-800">100%</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Không bán thầu</div>
              </div>
              <div class="p-3.5 rounded-xl bg-sala-50 border border-sala-100 text-center">
                <div class="text-xl sm:text-2xl font-extrabold text-sala-800">5 Năm</div>
                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Bảo hành kết cấu</div>
              </div>
            </div>
          </div>

          <!-- Cột ảnh thực tế công trình (lưới 2 ảnh cân đối, không nhãn dán) -->
          <div class="lg:col-span-6">
            <div class="grid grid-cols-2 gap-3 sm:gap-4">
              <div class="rounded-2xl overflow-hidden shadow-sm border border-slate-100 aspect-[4/5]">
                <img
                  src="https://lh3.googleusercontent.com/d/1m1HiNLmr3L4pnyC2-G8gLdQjPHKDExX9=w900"
                  data-drive-id="1m1HiNLmr3L4pnyC2-G8gLdQjPHKDExX9"
                  alt="Thiết kế kiến trúc xanh SALA Architecture"
                  class="drive-img w-full h-full object-cover"
                />
              </div>
              <div class="rounded-2xl overflow-hidden shadow-sm border border-slate-100 aspect-[4/5] mt-5 sm:mt-8">
                <img
                  src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w900"
                  data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                  alt="Thi công xây dựng thực tế SALA Architecture"
                  class="drive-img w-full h-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM & DỊCH VỤ (THEO MẪU KIẾN TRÚC UY VŨ, 2 CỘT TRÊN MOBILE) ==================== -->
    <section id="danh-muc-dich-vu" class="w-full py-10 sm:py-14 bg-slate-50 border-y border-slate-200/70">
      <div class="sala-container">
        <div class="text-center max-w-2xl mx-auto mb-7 sm:mb-10">
          <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1.5">Danh Mục Dịch Vụ Nổi Bật</p>
          <h2 class="text-xl sm:text-3xl font-extrabold text-sala-900 mb-3">Giải Pháp Thiết Kế &amp; Thi Công Trọn Gói</h2>
          <div class="section-divider mx-auto mb-3"></div>
          <p class="text-xs sm:text-sm text-slate-600">
            Đáp ứng trọn vẹn mọi nhu cầu từ tư vấn ý tưởng, thiết kế kiến trúc – nội thất đến xây nhà chìa khóa trao tay tại Đà Nẵng.
          </p>
        </div>

        <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP=w900" data-drive-id="1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP" alt="Thiết kế kiến trúc" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Thiết Kế Kiến Trúc &amp; Nội Thất</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Hồ sơ kiến trúc, kết cấu, điện nước, phối cảnh 3D ngoại thất và nội thất đồng bộ theo phong cách xanh hiện đại.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 2 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900" data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR" alt="Xây nhà trọn gói" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Xây Nhà Trọn Gói Chìa Khóa Trao Tay</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Miễn phí xin phép xây dựng, hỗ trợ giảm phí thiết kế, cam kết vật tư chính hãng và không phát sinh chi phí.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 3 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w900" data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz" alt="Thi công phần thô" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Thi Công Phần Thô &amp; Nhân Công</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Thi công móng, kết cấu bê tông cốt thép, xây tô, chống thấm và hệ thống điện nước âm tường chuẩn kỹ thuật.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 4 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w900" data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO" alt="Thi công hoàn thiện" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Thi Công Hoàn Thiện Nhà Ở</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Ốp lát gạch đá, sơn bả, đóng trần thạch cao, lắp đặt cửa nhôm kính, thiết bị vệ sinh và nội thất gỗ sắc nét.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 5 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w900" data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff" alt="Thiết kế thi công biệt thự" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Thiết Kế &amp; Thi Công Biệt Thự</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Biệt thự hiện đại, biệt thự vườn sinh thái, Indochine đẳng cấp, đề cao dấu ấn cá nhân và không gian thư giãn.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 6 -->
          <div class="flatsome-card bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w900" data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k" alt="Căn hộ khách sạn nhà hàng" class="drive-img flatsome-card-img w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-5 flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[13px] sm:text-base font-bold text-sala-900 mb-1.5 leading-snug break-words">Căn Hộ – Khách Sạn – Nhà Hàng</h3>
                <p class="text-[11.5px] sm:text-sm text-slate-600 leading-relaxed mb-3">Tối ưu diện tích khai thác kinh doanh, giải pháp phòng cháy chữa cháy và thẩm mỹ mặt tiền thu hút khách hàng.</p>
              </div>
              <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-sala-700 hover:text-gold-600 transition">
                <span>Nhận tư vấn</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== DANH MỤC 1: HÌNH ẢNH THIẾT KẾ XÂY DỰNG (5 ẢNH GOOGLE DRIVE) ==================== -->
    <section id="thiet-ke-xay-dung" class="w-full py-10 sm:py-14 bg-white">
      <div class="sala-container">
        <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-3 mb-6 sm:mb-8">
          <div>
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Bộ Sưu Tập Kiến Trúc</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-sala-900">Hình Ảnh Thiết Kế Xây Dựng</h2>
            <div class="section-divider mt-2.5"></div>
          </div>
          <p class="text-xs sm:text-sm text-slate-500 max-w-md">
            Các phương án phối cảnh kiến trúc xanh tiêu biểu do đội ngũ kiến trúc sư SALA Architecture thực hiện.
          </p>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên mobile, không nhãn dán, tên hiển thị trọn vẹn -->
        <div id="design-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4 lg:gap-5"></div>
      </div>
    </section>

    <!-- ==================== DANH MỤC 2: HÌNH ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (9 ẢNH GOOGLE DRIVE) ==================== -->
    <section id="thi-cong-thuc-te" class="w-full py-10 sm:py-14 bg-slate-50 border-y border-slate-200/70">
      <div class="sala-container">
        <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-3 mb-6 sm:mb-8">
          <div>
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Năng Lực Công Trường</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-sala-900">Ảnh Thực Tế Thi Công Xây Dựng</h2>
            <div class="section-divider mt-2.5"></div>
          </div>
          <p class="text-xs sm:text-sm text-slate-500 max-w-md">
            Ghi nhận thực tế quá trình thi công phần thô, hoàn thiện và bàn giao công trình đạt chuẩn kỹ thuật của SALA.
          </p>
        </div>

        <!-- Lưới 2 cột trên mobile, 3 cột trên tablet/desktop -->
        <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5"></div>
      </div>
    </section>

    <!-- ==================== DANH MỤC 3: CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE) ==================== -->
    <section id="du-an-da-nang" class="w-full py-10 sm:py-14 bg-white">
      <div class="sala-container">
        <div class="flex flex-col md:flex-row md:items-end justify-between gap-4 mb-6 sm:mb-8">
          <div>
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Công Trình Tiêu Biểu</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-sala-900">Các Dự Án Ở Đà Nẵng</h2>
            <div class="section-divider mt-2.5"></div>
          </div>

          <!-- Bộ lọc danh mục nhỏ gọn, từng tên danh mục viết liền không xuống dòng -->
          <div id="danang-filter-bar" class="flex flex-wrap items-center gap-1.5 sm:gap-2">
            <button type="button" data-filter="all" class="danang-filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-sala-800 text-white transition">Tất cả dự án</button>
            <button type="button" data-filter="nha-pho" class="danang-filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-sala-50 hover:text-sala-800 transition">Nhà phố Đà Nẵng</button>
            <button type="button" data-filter="biet-thu" class="danang-filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-sala-50 hover:text-sala-800 transition">Biệt thự Đà Nẵng</button>
            <button type="button" data-filter="can-ho" class="danang-filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-sala-50 hover:text-sala-800 transition">Căn hộ &amp; Văn phòng</button>
          </div>
        </div>

        <!-- Lưới 2 cột trên mobile, 4 cột trên desktop -->
        <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4 lg:gap-5"></div>
      </div>
    </section>

    <!-- ==================== QUY TRÌNH THI CÔNG CHUẨN SALA (4 BƯỚC GIỐNG MẪU UY VŨ) ==================== -->
    <section class="w-full py-10 sm:py-14 bg-sala-900 text-white">
      <div class="sala-container">
        <div class="text-center max-w-2xl mx-auto mb-8 sm:mb-10">
          <p class="text-xs font-bold uppercase tracking-widest text-gold-400 mb-1.5">Tiêu Chuẩn Chất Lượng</p>
          <h2 class="text-xl sm:text-3xl font-extrabold text-white mb-3">Quy Trình Thi Công Chuẩn SALA Architecture</h2>
          <div class="w-14 h-0.5 bg-gold-400 mx-auto rounded-full"></div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <div class="p-5 sm:p-6 rounded-2xl bg-white/10 border border-white/15 backdrop-blur-sm">
            <div class="w-10 h-10 rounded-xl bg-gold-500 text-white font-extrabold flex items-center justify-center mb-4">01</div>
            <h3 class="text-base font-bold text-white mb-2">Móng &amp; Bê Tông Cốt Thép</h3>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">Kiểm định thép chuẩn quy cách, định vị cốt thép bằng con kê bê tông, đổ bê tông tươi đúng mác và phủ bạt bảo dưỡng liên tục.</p>
          </div>

          <div class="p-5 sm:p-6 rounded-2xl bg-white/10 border border-white/15 backdrop-blur-sm">
            <div class="w-10 h-10 rounded-xl bg-gold-500 text-white font-extrabold flex items-center justify-center mb-4">02</div>
            <h3 class="text-base font-bold text-white mb-2">Tăng Cường Chống Nứt</h3>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">Đổ giằng khóa đầu tường, bổ trụ bê tông tại mép cửa, đóng lưới thép mắt cáo tại mọi vị trí tiếp giáp dầm – cột và đường cắt điện nước.</p>
          </div>

          <div class="p-5 sm:p-6 rounded-2xl bg-white/10 border border-white/15 backdrop-blur-sm">
            <div class="w-10 h-10 rounded-xl bg-gold-500 text-white font-extrabold flex items-center justify-center mb-4">03</div>
            <h3 class="text-base font-bold text-white mb-2">Xây Tường &amp; Hệ Thống M&amp;E</h3>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">Xây tối thiểu 3 lớp gạch thẻ chân tường chống thấm ngược, mạch hồ no đầy thẳng hàng, thử áp lực đường ống cấp thoát nước trước khi tô trát.</p>
          </div>

          <div class="p-5 sm:p-6 rounded-2xl bg-white/10 border border-white/15 backdrop-blur-sm">
            <div class="w-10 h-10 rounded-xl bg-gold-500 text-white font-extrabold flex items-center justify-center mb-4">04</div>
            <h3 class="text-base font-bold text-white mb-2">Chống Thấm &amp; Hoàn Thiện</h3>
            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">Chống thấm chuyên dụng sàn vệ sinh, ban công, sân thượng ngâm thử nước 48h. Ốp lát dùng ke cân bằng thẩm mỹ và nghiệm thu bàn giao.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== BẢNG BÁO GIÁ THAM KHẢO (PHONG CÁCH UY VŨ, DỄ DỰNG LẠI TRÊN FLATSOME) ==================== -->
    <section id="bao-gia" class="w-full py-10 sm:py-14 bg-white">
      <div class="sala-container">
        <div class="text-center max-w-2xl mx-auto mb-8">
          <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1.5">Minh Bạch Chi Phí</p>
          <h2 class="text-xl sm:text-3xl font-extrabold text-sala-900 mb-3">Bảng Báo Giá Thiết Kế &amp; Xây Dựng Tại Đà Nẵng</h2>
          <div class="section-divider mx-auto mb-3"></div>
          <p class="text-xs sm:text-sm text-slate-600">Đơn giá tham khảo rõ ràng theo từng hạng mục. Liên hệ trực tiếp để nhận dự toán chi tiết theo diện tích thực tế.</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
          <!-- Gói 1 -->
          <div class="rounded-2xl border border-slate-200 bg-slate-50/70 p-5 sm:p-6 flex flex-col justify-between hover:border-sala-500 transition">
            <div>
              <h3 class="text-base font-bold text-sala-900 mb-1">Thiết Kế Nhà Phố</h3>
              <p class="text-xs text-slate-500 mb-4">Kiến trúc hiện đại, không gian xanh</p>
              <div class="text-2xl font-extrabold text-sala-700 mb-4">Từ 165.000 <span class="text-xs font-semibold text-slate-500">VNĐ/m²</span></div>
              <ul class="space-y-2 text-xs sm:text-sm text-slate-600 mb-6">
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Hồ sơ bản vẽ kiến trúc, kết cấu, M&amp;E</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Phối cảnh 3D mặt tiền &amp; công năng</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Hỗ trợ hồ sơ xin phép xây dựng</span></li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="w-full py-2.5 px-4 rounded-xl bg-white border border-sala-700 text-sala-800 hover:bg-sala-800 hover:text-white text-center text-xs sm:text-sm font-bold transition">Đăng Ký Tư Vấn</a>
          </div>

          <!-- Gói 2 -->
          <div class="rounded-2xl border border-slate-200 bg-slate-50/70 p-5 sm:p-6 flex flex-col justify-between hover:border-sala-500 transition">
            <div>
              <h3 class="text-base font-bold text-sala-900 mb-1">Thiết Kế Biệt Thự</h3>
              <p class="text-xs text-slate-500 mb-4">Biệt thự vườn, hiện đại, Indochine</p>
              <div class="text-2xl font-extrabold text-sala-700 mb-4">Từ 220.000 <span class="text-xs font-semibold text-slate-500">VNĐ/m²</span></div>
              <ul class="space-y-2 text-xs sm:text-sm text-slate-600 mb-6">
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Thiết kế kiến trúc &amp; cảnh quan sân vườn</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Phối cảnh 3D nội thất chi tiết từng phòng</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Giám sát quyền tác giả suốt quá trình xây</span></li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="w-full py-2.5 px-4 rounded-xl bg-white border border-sala-700 text-sala-800 hover:bg-sala-800 hover:text-white text-center text-xs sm:text-sm font-bold transition">Đăng Ký Tư Vấn</a>
          </div>

          <!-- Gói 3 -->
          <div class="rounded-2xl border border-slate-200 bg-slate-50/70 p-5 sm:p-6 flex flex-col justify-between hover:border-sala-500 transition">
            <div>
              <h3 class="text-base font-bold text-sala-900 mb-1">Thi Công Phần Thô</h3>
              <p class="text-xs text-slate-500 mb-4">Vật tư phần thô &amp; nhân công hoàn thiện</p>
              <div class="text-2xl font-extrabold text-sala-700 mb-4">Từ 3.650.000 <span class="text-xs font-semibold text-slate-500">VNĐ/m²</span></div>
              <ul class="space-y-2 text-xs sm:text-sm text-slate-600 mb-6">
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Thép Hòa Phát, Xi măng Sông Gianh, Cadivi</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Kỹ sư trực tiếp giám sát hàng ngày</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-600 mt-1"></i><span>Bảo hành kết cấu lên đến 5 năm</span></li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="w-full py-2.5 px-4 rounded-xl bg-white border border-sala-700 text-sala-800 hover:bg-sala-800 hover:text-white text-center text-xs sm:text-sm font-bold transition">Đăng Ký Tư Vấn</a>
          </div>

          <!-- Gói 4 -->
          <div class="rounded-2xl border-2 border-sala-700 bg-sala-50/70 p-5 sm:p-6 flex flex-col justify-between shadow-sm">
            <div>
              <h3 class="text-base font-bold text-sala-900 mb-1">Xây Nhà Trọn Gói</h3>
              <p class="text-xs text-slate-600 mb-4">Chìa khóa trao tay – Tối ưu thời gian</p>
              <div class="text-2xl font-extrabold text-sala-800 mb-4">Từ 5.800.000 <span class="text-xs font-semibold text-slate-600">VNĐ/m²</span></div>
              <ul class="space-y-2 text-xs sm:text-sm text-slate-700 mb-6">
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-700 mt-1"></i><span>Ưu đãi thiết kế kiến trúc &amp; xin phép XD</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-700 mt-1"></i><span>Vật tư hoàn thiện chuẩn hợp đồng cam kết</span></li>
                <li class="flex items-start gap-2"><i class="fa-solid fa-check text-sala-700 mt-1"></i><span>Cam kết tiến độ &amp; không phát sinh chi phí</span></li>
              </ul>
            </div>
            <a href="#form-bao-gia" class="w-full py-2.5 px-4 rounded-xl bg-sala-800 hover:bg-sala-900 text-white text-center text-xs sm:text-sm font-bold transition">Nhận Dự Toán Ngay</a>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (2 CỘT TRÊN MOBILE) ==================== -->
    <section id="tin-tuc" class="w-full py-10 sm:py-14 bg-slate-50 border-y border-slate-200/70">
      <div class="sala-container">
        <div class="flex flex-col sm:flex-row sm:items-end justify-between gap-3 mb-6 sm:mb-8">
          <div>
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Kiến Thức &amp; Cẩm Nang</p>
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-sala-900">Bài Viết &amp; Kinh Nghiệm Xây Nhà</h2>
            <div class="section-divider mt-2.5"></div>
          </div>
          <p class="text-xs sm:text-sm text-slate-500">Chia sẻ thực tế về thiết kế kiến trúc xanh, vật liệu và phong thủy nhà ở.</p>
        </div>

        <!-- 2 cột trên mobile, 4 cột trên desktop -->
        <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5"></div>
      </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC ==================== -->
    <section id="doi-tac" class="w-full py-10 sm:py-12 bg-white">
      <div class="sala-container">
        <div class="text-center max-w-xl mx-auto mb-7">
          <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Vật Tư Chính Hãng</p>
          <h2 class="text-xl sm:text-2xl font-extrabold text-sala-900 mb-2.5">Đối Tác Cung Ứng Của SALA Architecture</h2>
          <div class="section-divider mx-auto"></div>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">HÒA PHÁT</span>
            <span class="text-[10px] text-slate-500">Thép xây dựng</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">SÔNG GIANH</span>
            <span class="text-[10px] text-slate-500">Xi măng PCB40</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">DULUX</span>
            <span class="text-[10px] text-slate-500">Sơn nội ngoại thất</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">JOTUN</span>
            <span class="text-[10px] text-slate-500">Sơn bền màu</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">TOTO</span>
            <span class="text-[10px] text-slate-500">Thiết bị vệ sinh</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">XINGFA</span>
            <span class="text-[10px] text-slate-500">Cửa nhôm kính</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">AN CƯỜNG</span>
            <span class="text-[10px] text-slate-500">Gỗ nội thất</span>
          </div>
          <div class="h-16 sm:h-20 rounded-xl border border-slate-200 bg-slate-50/70 flex flex-col items-center justify-center px-2 text-center hover:border-sala-400 transition">
            <span class="text-xs sm:text-sm font-extrabold tracking-tight text-sala-900">CADIVI</span>
            <span class="text-[10px] text-slate-500">Dây cáp điện</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== FORM YÊU CẦU TƯ VẤN BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAP TRÊN TRANG CHỦ ==================== -->
    <section id="lien-he" class="w-full py-10 sm:py-14 bg-slate-50 border-t border-slate-200/80">
      <div class="sala-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8">

          <!-- Form yêu cầu tư vấn & báo giá -->
          <div id="form-bao-gia" class="lg:col-span-6 bg-white rounded-2xl border border-slate-200 p-5 sm:p-7 shadow-sm">
            <p class="text-xs font-bold uppercase tracking-widest text-gold-600 mb-1">Hỗ Trợ Miễn Phí 24/7</p>
            <h2 class="text-xl sm:text-2xl font-extrabold text-sala-900 mb-2">Gửi Yêu Cầu Tư Vấn &amp; Báo Giá</h2>
            <div class="section-divider mb-4"></div>
            <p class="text-xs sm:text-sm text-slate-600 mb-5">
              Để lại thông tin công trình dự kiến, kiến trúc sư SALA Architecture sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết trong thời gian sớm nhất.
            </p>

            <form id="quote-form" class="space-y-3.5" novalidate>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="customer-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                  <input
                    id="customer-name"
                    type="text"
                    required
                    placeholder="Nhập họ tên của bạn"
                    class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-sala-600 focus:ring-2 focus:ring-sala-100"
                  />
                </div>
                <div>
                  <label for="customer-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input
                    id="customer-phone"
                    type="tel"
                    required
                    placeholder="Ví dụ: 0949.857.007"
                    class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-sala-600 focus:ring-2 focus:ring-sala-100"
                  />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="service-type" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                  <select
                    id="service-type"
                    class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm bg-white focus:outline-none focus:border-sala-600 focus:ring-2 focus:ring-sala-100"
                  >
                    <option value="Xây nhà trọn gói">Xây nhà trọn gói</option>
                    <option value="Thiết kế kiến trúc">Thiết kế kiến trúc</option>
                    <option value="Thi công phần thô">Thi công phần thô</option>
                    <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                    <option value="Thiết kế thi công biệt thự">Thiết kế thi công biệt thự</option>
                    <option value="Căn hộ - Khách sạn - Văn phòng">Căn hộ – Khách sạn – Văn phòng</option>
                  </select>
                </div>
                <div>
                  <label for="budget-range" class="block text-xs font-semibold text-slate-700 mb-1">Ngân sách dự kiến</label>
                  <select
                    id="budget-range"
                    class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm bg-white focus:outline-none focus:border-sala-600 focus:ring-2 focus:ring-sala-100"
                  >
                    <option value="Dưới 1.5 tỷ">Dưới 1.5 tỷ</option>
                    <option value="Từ 1.5 - 2.5 tỷ" selected>Từ 1.5 – 2.5 tỷ</option>
                    <option value="Từ 2.5 - 3.5 tỷ">Từ 2.5 – 3.5 tỷ</option>
                    <option value="Trên 3.5 tỷ">Trên 3.5 tỷ</option>
                  </select>
                </div>
              </div>

              <div>
                <label for="customer-note" class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất &amp; yêu cầu thêm</label>
                <textarea
                  id="customer-note"
                  rows="3"
                  placeholder="Ví dụ: Đất 5x20m tại Hải Châu, Đà Nẵng, dự kiến xây nhà 3 tầng có sân vườn..."
                  class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:outline-none focus:border-sala-600 focus:ring-2 focus:ring-sala-100"
                ></textarea>
              </div>

              <button
                type="submit"
                class="w-full py-3 px-5 rounded-xl bg-sala-800 hover:bg-sala-900 text-white text-sm font-bold shadow-sm transition flex items-center justify-center gap-2"
              >
                <i class="fa-solid fa-paper-plane text-xs"></i>
                <span>Gửi Yêu Cầu Nhận Báo Giá</span>
              </button>

              <!-- Hộp thông báo phản hồi form ngay trên giao diện (không dùng alert) -->
              <div id="quote-feedback" class="hidden rounded-xl p-3.5 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>

          <!-- Cột phải: Fanpage Facebook & Bản đồ Google Map trên trang chủ -->
          <div class="lg:col-span-6 flex flex-col gap-5">
            <!-- Fanpage Facebook chính thức -->
            <div class="bg-white rounded-2xl border border-slate-200 p-4 sm:p-5 shadow-sm">
              <div class="flex items-center justify-between gap-2 mb-3">
                <div class="flex items-center gap-2">
                  <span class="w-8 h-8 rounded-lg bg-[#1877F2]/10 text-[#1877F2] flex items-center justify-center">
                    <i class="fa-brands fa-facebook-f"></i>
                  </span>
                  <div>
                    <h3 class="text-sm sm:text-base font-bold text-sala-900 leading-tight">Fanpage SALA Architecture</h3>
                    <p class="text-[11px] text-slate-500">facebook.com/Thietkexanhsala</p>
                  </div>
                </div>
                <a
                  href="https://www.facebook.com/Thietkexanhsala"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="whitespace-nowrap px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold transition"
                >
                  Theo dõi Page
                </a>
              </div>

              <!-- Nhúng Facebook Page Plugin chuẩn + khung tương tác đẹp -->
              <div class="w-full overflow-hidden rounded-xl border border-slate-100 bg-slate-50">
                <iframe
                  title="Fanpage Thiết Kế Xanh SALA"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FThietkexanhsala&tabs=timeline&width=500&height=210&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[210px] border-0 block"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>

            <!-- Google Map địa chỉ 04 Phan Thành Tài, Hải Châu, Đà Nẵng -->
            <div class="bg-white rounded-2xl border border-slate-200 p-4 sm:p-5 shadow-sm flex-1 flex flex-col">
              <div class="flex items-center justify-between gap-2 mb-3">
                <div class="flex items-center gap-2">
                  <span class="w-8 h-8 rounded-lg bg-sala-50 text-sala-700 flex items-center justify-center">
                    <i class="fa-solid fa-location-dot"></i>
                  </span>
                  <div>
                    <h3 class="text-sm sm:text-base font-bold text-sala-900 leading-tight">Bản Đồ Chỉ Đường Văn Phòng</h3>
                    <p class="text-[11px] sm:text-xs text-slate-500">04 Phan Thành Tài, Hải Châu, Đà Nẵng</p>
                  </div>
                </div>
                <a
                  href="https://www.google.com/maps/search/?api=1&query=04+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="whitespace-nowrap px-3 py-1.5 rounded-lg bg-sala-700 hover:bg-sala-800 text-white text-xs font-semibold transition"
                >
                  Chỉ đường
                </a>
              </div>
              <div class="w-full flex-1 min-h-[220px] rounded-xl overflow-hidden border border-slate-200">
                <iframe
                  title="Bản đồ Công ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture"
                  src="https://maps.google.com/maps?q=04+Phan+Th%C3%A0nh+T%C3%A0i,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                  class="w-full h-full min-h-[220px] border-0 block"
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                ></iframe>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- ==================== FOOTER CHUYÊN NGHIỆP CHUẨN FLATSOME ==================== -->
  <footer class="w-full bg-sala-900 text-slate-200 pt-10 pb-20 sm:pb-10">
    <div class="sala-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/15">
        <!-- Cột 1: Thương hiệu -->
        <div>
          <div class="flex items-center gap-2.5 mb-3">
            <div class="bg-white p-1.5 rounded-lg shrink-0">
              <img
                src="https://lh3.googleusercontent.com/d/1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype=w300"
                data-drive-id="1IMt8fOcR2h8P3Dn-CVUd3cmz15Vjuype"
                alt="Logo SALA Architecture"
                class="drive-img h-8 w-auto max-w-[90px] object-contain"
              />
            </div>
            <div>
              <div class="text-sm font-extrabold text-white">SALA ARCHITECTURE</div>
              <div class="text-[11px] text-gold-400">salaarchitecture.com</div>
            </div>
          </div>
          <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-3">
            Công ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture – Đơn vị chuyên sâu về thiết kế kiến trúc xanh và xây nhà trọn gói uy tín tại Đà Nẵng.
          </p>
          <p class="text-xs text-slate-400">Mã số thuế: 0401850075</p>
        </div>

        <!-- Cột 2: Thông tin liên hệ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3">Thông Tin Liên Hệ</h4>
          <ul class="space-y-2.5 text-xs sm:text-sm text-slate-300">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-gold-400 mt-1"></i>
              <span>Địa chỉ: 04 Phan Thành Tài, Hải Châu, Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-gold-400"></i>
              <a href="tel:0949857007" class="hover:text-white font-semibold">Hotline: 0949.857.007</a>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-gold-400"></i>
              <span>Website: salaarchitecture.com</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-gold-400"></i>
              <a href="https://www.facebook.com/Thietkexanhsala" target="_blank" rel="noopener noreferrer" class="hover:text-white">fb.com/Thietkexanhsala</a>
            </li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục dịch vụ -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3">Danh Mục Dịch Vụ</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#danh-muc-dich-vu" class="hover:text-gold-400 transition">Thiết kế kiến trúc xanh</a></li>
            <li><a href="#danh-muc-dich-vu" class="hover:text-gold-400 transition">Xây nhà trọn gói Đà Nẵng</a></li>
            <li><a href="#danh-muc-dich-vu" class="hover:text-gold-400 transition">Thi công phần thô chuẩn kỹ thuật</a></li>
            <li><a href="#danh-muc-dich-vu" class="hover:text-gold-400 transition">Thi công hoàn thiện nội thất</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-gold-400 transition">Thiết kế thi công biệt thự</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3">Chuyên Mục Nổi Bật</h4>
          <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
            <li><a href="#thiet-ke-xay-dung" class="hover:text-gold-400 transition">Hình ảnh thiết kế xây dựng</a></li>
            <li><a href="#thi-cong-thuc-te" class="hover:text-gold-400 transition">Ảnh thực tế thi công xây dựng</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-gold-400 transition">Các dự án tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-gold-400 transition">Bảng báo giá xây dựng mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-gold-400 transition">Bài viết kinh nghiệm xây nhà</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <p>© 2026 Công ty TNHH Tư Vấn Thiết Kế Xây Dựng SALA Architecture (salaarchitecture.com). Bảo lưu mọi quyền.</p>
        <p>Thiết kế giao diện tương thích Flatsome UX Builder</p>
      </div>
    </div>
  </footer>

  <!-- ==================== BỘ NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH DESKTOP & MOBILE) ==================== -->
  <!-- Thanh nút nổi cho Máy tính (góc phải dưới) -->
  <div class="hidden sm:flex fixed right-4 bottom-5 z-40 flex-col items-end gap-2.5">
    <a
      href="https://www.facebook.com/Thietkexanhsala"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Nhắn tin Facebook SALA Architecture"
      class="group flex items-center gap-2.5 bg-[#1877F2] hover:bg-blue-700 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition"
    >
      <i class="fa-brands fa-facebook-messenger text-base"></i>
      <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <a
      href="https://zalo.me/0949857007"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo 0949.857.007"
      class="group flex items-center gap-2.5 bg-[#0068FF] hover:bg-blue-600 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] text-[10px] font-extrabold flex items-center justify-center">Z</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <a
      href="tel:0949857007"
      aria-label="Gọi Hotline 0949.857.007"
      class="hotline-pulse flex items-center gap-2.5 bg-sala-700 hover:bg-sala-800 text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition"
    >
      <i class="fa-solid fa-phone-volume text-sm"></i>
      <span class="text-xs font-bold whitespace-nowrap">0949.857.007</span>
    </a>
  </div>

  <!-- Thanh liên hệ nổi cố định gọn gàng dưới đáy cho Điện thoại -->
  <div class="sm:hidden fixed bottom-0 left-0 right-0 z-40 bg-white/95 backdrop-blur-md border-t border-slate-200 px-2.5 py-2 shadow-[0_-4px_16px_rgba(0,0,0,0.08)]">
    <div class="grid grid-cols-3 gap-2">
      <a
        href="tel:0949857007"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-sala-700 text-white text-xs font-bold shadow-sm"
      >
        <i class="fa-solid fa-phone text-[11px]"></i>
        <span class="whitespace-nowrap">Hotline</span>
      </a>
      <a
        href="https://zalo.me/0949857007"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#0068FF] text-white text-xs font-bold shadow-sm"
      >
        <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] text-[9px] font-extrabold flex items-center justify-center">Z</span>
        <span class="whitespace-nowrap">Zalo</span>
      </a>
      <a
        href="https://www.facebook.com/Thietkexanhsala"
        target="_blank"
        rel="noopener noreferrer"
        class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-xl bg-[#1877F2] text-white text-xs font-bold shadow-sm"
      >
        <i class="fa-brands fa-facebook-f text-[11px]"></i>
        <span class="whitespace-nowrap">Facebook</span>
      </a>
    </div>
  </div>

  <!-- ==================== MODAL XEM CHI TIẾT DỰ ÁN / BÀI VIẾT ==================== -->
  <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 relative">
      <button
        id="modal-close-btn"
        type="button"
        aria-label="Đóng cửa sổ"
        class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-black/55 hover:bg-sala-800 text-white flex items-center justify-center transition"
      >
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div class="w-full bg-slate-100 aspect-[16/10] overflow-hidden">
        <img id="modal-img" src="" alt="" class="w-full h-full object-cover" />
      </div>
      <div class="p-5 sm:p-6">
        <p id="modal-category" class="text-xs font-bold uppercase tracking-wider text-gold-600 mb-1"></p>
        <h3 id="modal-title" class="text-lg sm:text-xl font-extrabold text-sala-900 mb-3 leading-snug"></h3>
        <div id="modal-desc" class="text-xs sm:text-sm text-slate-600 leading-relaxed space-y-2.5 mb-5"></div>
        <div class="flex flex-wrap items-center gap-2.5 pt-3 border-t border-slate-100">
          <a href="#form-bao-gia" id="modal-quote-btn" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-xl bg-sala-800 hover:bg-sala-900 text-white text-xs sm:text-sm font-bold transition">
            <span>Yêu cầu tư vấn mẫu này</span>
            <i class="fa-solid fa-arrow-right text-xs"></i>
          </a>
          <a href="tel:0949857007" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-xl border border-sala-700 text-sala-800 hover:bg-sala-50 text-xs sm:text-sm font-bold transition">
            <i class="fa-solid fa-phone text-xs"></i>
            <span>0949.857.007</span>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== JAVASCRIPT: DỮ LIỆU DỰ ÁN GOOGLE DRIVE, SLIDER, LỌC DANH MỤC, MODAL & FORM ==================== -->
  <script>
    /**
     * Hàm tạo đường dẫn ảnh Google Drive ưu tiên độ phân giải sắc nét
     * và tự động chuyển nguồn dự phòng nếu đường dẫn chính bị giới hạn
     */
    function getDriveUrl(id, width) {
      var w = width || 900;
      return 'https://lh3.googleusercontent.com/d/' + id + '=w' + w;
    }

    function attachDriveFallback(imgEl) {
      if (!imgEl || imgEl.dataset.fallbackBound) return;
      imgEl.dataset.fallbackBound = '1';
      imgEl.addEventListener('error', function () {
        var id = imgEl.getAttribute('data-drive-id');
        var step = parseInt(imgEl.dataset.fallbackStep || '0', 10);
        if (step === 0 && id) {
          imgEl.dataset.fallbackStep = '1';
          imgEl.src = 'https://drive.google.com/thumbnail?id=' + id + '&sz=w1000';
        } else if (step === 1 && id) {
          imgEl.dataset.fallbackStep = '2';
          imgEl.src = 'https://drive.google.com/uc?export=view&id=' + id;
        } else if (step < 3) {
          imgEl.dataset.fallbackStep = '3';
          imgEl.src = 'https://placehold.co/800x600/1f5335/ffffff?text=SALA+Architecture';
        }
      });
    }

    /* 1. Dữ liệu 5 hình ảnh Thiết Kế Xây Dựng từ Google Drive */
    var designProjects = [
      {
        id: '1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP',
        title: 'Thiết Kế Nhà Phố 3 Tầng Không Gian Xanh Hiện Đại',
        category: 'Thiết kế kiến trúc',
        desc: 'Phương án thiết kế nhà phố 3 tầng tối ưu thông gió tự nhiên, kết hợp mảng xanh ban công và hệ lam chắn nắng tinh tế theo phong cách đặc trưng của SALA Architecture.'
      },
      {
        id: '1m1HiNLmr3L4pnyC2-G8gLdQjPHKDExX9',
        title: 'Thiết Kế Biệt Thự Phố Xanh Tối Ưu Ánh Sáng Tự Nhiên',
        category: 'Thiết kế biệt thự',
        desc: 'Kiến trúc biệt thự phố hiện đại với hình khối giật cấp sang trọng, sử dụng hệ cửa kính lớn và giếng trời giúp mọi không gian luôn ngập tràn ánh sáng.'
      },
      {
        id: '1HBe6xTABNOUgtGwL5RetZqdwAPTyGRYB',
        title: 'Phối Cảnh Kiến Trúc Nhà Ở Kết Hợp Sân Vườn Thông Thoáng',
        category: 'Thiết kế kiến trúc',
        desc: 'Giải pháp tổ chức không gian sống mở gắn kết sân vườn trước sau, vật liệu hoàn thiện thân thiện với khí hậu nắng gió miền Trung.'
      },
      {
        id: '1dzhQ64t24mEQvXeqHsrM-mBWq3LbmUA4',
        title: 'Thiết Kế Mặt Tiền Nhà Phố Hiện Đại Tại Đà Nẵng',
        category: 'Thiết kế nhà phố',
        desc: 'Mặt tiền sử dụng đường nét tối giản kết hợp gam màu trung tính ấm áp, tạo điểm nhấn kiến trúc bền vững và khác biệt trên tuyến phố.'
      },
      {
        id: '1PI4ZkZcWAB4uTwn9m4dNrBOHtYBrcAr4',
        title: 'Thiết Kế Biệt Thự Hiện Đại Phong Cách Kiến Trúc Xanh',
        category: 'Thiết kế biệt thự',
        desc: 'Công trình biệt thự chú trọng công năng cho gia đình đa thế hệ, không gian sinh hoạt chung rộng rãi kết nối trực tiếp với hồ tiểu cảnh và cây xanh.'
      }
    ];

    /* 2. Dữ liệu 9 hình ảnh Thực Tế Thi Công Xây Dựng từ Google Drive */
    var constructionProjects = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Thực Tế Phần Thô & Kết Cấu Bê Tông Cốt Thép',
        category: 'Thi công phần thô',
        desc: 'Kiểm soát chặt chẽ sắt thép, cốp pha và mác bê tông tại công trường do đội ngũ kỹ sư SALA Architecture trực tiếp chỉ huy.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Xây Dựng Nhà Phố Trọn Gói Đạt Chuẩn Kỹ Thuật',
        category: 'Xây nhà trọn gói',
        desc: 'Triển khai thi công đồng bộ từ phần móng đến phần thân, đảm bảo an toàn lao động, vệ sinh công trường và đúng tiến độ cam kết.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Công Trình Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Hiện Đại',
        category: 'Thi công hoàn thiện',
        desc: 'Hoàn thiện mặt tiền sắc nét đúng tỷ lệ bản vẽ thiết kế 3D, xử lý chống thấm và sơn ngoại thất cao cấp bền màu với thời tiết.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Giám Sát & Thi Công Xây Dựng Công Trình Dân Dụng Chuyên Nghiệp',
        category: 'Thi công thực tế',
        desc: 'Nghiệm thu kỹ thuật từng giai đoạn đổ sàn, xây tường, đóng lưới chống nứt trước khi chuyển sang các bước hoàn thiện tiếp theo.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi Công Hoàn Thiện Kiến Trúc & Nội Thất Nhà Ở Trọn Gói',
        category: 'Thi công hoàn thiện',
        desc: 'Độ hoàn thiện tỉ mỉ ở từng đường ron gạch, trần thạch cao, hệ thống chiếu sáng và đồ gỗ nội thất hiện đại.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Hạng Mục Thi Công Xây Tường, Tô Trát & Chống Thấm Tiêu Chuẩn',
        category: 'Thi công phần thô',
        desc: 'Thi công tường xây thẳng đứng bằng máy cân bằng laser, mạch vữa đầy đặn và chống thấm kỹ lưỡng các khu vực ẩm ướt.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi Công Thực Tế Nhà Phố 3 Tầng Chìa Khóa Trao Tay',
        category: 'Xây nhà trọn gói',
        desc: 'Công trình thực hiện trọn gói từ thiết kế đến thi công hoàn thiện, giúp gia chủ tiết kiệm tối đa thời gian và kiểm soát ngân sách.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Nghiệm Thu & Bàn Giao Công Trình Thi Công Xây Dựng Thực Tế',
        category: 'Bàn giao công trình',
        desc: 'Kiểm tra vận hành toàn bộ hệ thống điện nước, thiết bị và vệ sinh công nghiệp sạch sẽ trước khi trao chìa khóa cho chủ đầu tư.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi Công Hoàn Thiện Biệt Thự & Cảnh Quan Xanh Thực Tế',
        category: 'Thi công biệt thự',
        desc: 'Hoàn thiện kiến trúc ngoại thất kết hợp bố trí cảnh quan cây xanh thực tế, mang lại không gian sống trong lành và đẳng cấp.'
      }
    ];

    /* 3. Dữ liệu 10 Dự Án Tại Đà Nẵng từ Google Drive */
    var danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự Án Nhà Phố Xanh 3 Tầng Quận Hải Châu, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        type: 'nha-pho',
        desc: 'Nhà phố hiện đại 3 tầng tại trung tâm quận Hải Châu, bố trí giếng trời trung tâm và cây xanh mặt tiền tạo vi khí hậu mát mẻ.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự Án Biệt Thự Hiện Đại Khu Đô Thị Hòa Xuân, Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        type: 'biet-thu',
        desc: 'Biệt thự hiện đại tại Hòa Xuân với thiết kế không gian mở, kết hợp hồ cá tiểu cảnh và hệ cửa kính đón gió sông thoáng đãng.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự Án Nhà Phố Mặt Tiền Xanh Quận Sơn Trà, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        type: 'nha-pho',
        desc: 'Công trình nhà phố gần biển Sơn Trà được tính toán kỹ vật liệu chống ăn mòn gió biển và tối ưu không gian thư giãn sân thượng.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự Án Căn Hộ Dịch Vụ Cho Thuê Ngũ Hành Sơn, Đà Nẵng',
        category: 'Căn hộ & Văn phòng',
        type: 'can-ho',
        desc: 'Thiết kế và thi công tòa căn hộ dịch vụ hiện đại gần biển Mỹ Khê, tối ưu số lượng phòng khai thác và đảm bảo thông thoáng tự nhiên.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự Án Nhà Phố 2 Mặt Tiền Hiện Đại Quận Thanh Khê, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        type: 'nha-pho',
        desc: 'Nhà phố góc 2 mặt tiền tại Thanh Khê tận dụng tối đa góc nhìn thẩm mỹ và khả năng đón sáng cho toàn bộ các phòng ngủ.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự Án Biệt Thự Sân Vườn Ven Sông Cẩm Lệ, Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        type: 'biet-thu',
        desc: 'Biệt thự sân vườn phong cách nghỉ dưỡng tại Cẩm Lệ, tạo lập không gian sinh hoạt ấm cúng, yên tĩnh cho đại gia đình.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự Án Nhà Ở Kết Hợp Văn Phòng Hải Châu, Đà Nẵng',
        category: 'Căn hộ & Văn phòng',
        type: 'can-ho',
        desc: 'Giải pháp kiến trúc linh hoạt phân tách lối đi và công năng hợp lý giữa khu vực làm việc chuyên nghiệp và không gian ở riêng tư.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự Án Nhà Phố Hiện Đại Tối Ưu Thông Gió Liên Chiểu, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        type: 'nha-pho',
        desc: 'Nhà phố thiết kế theo giải pháp thông gió chéo kết hợp gạch bông gió và cây xanh, giảm nhiệt hiệu quả vào mùa hè Đà Nẵng.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự Án Cải Tạo & Hoàn Thiện Nhà Phố Hòa Cường, Đà Nẵng',
        category: 'Nhà phố Đà Nẵng',
        type: 'nha-pho',
        desc: 'Cải tạo nâng tầm diện mạo mặt tiền và bố trí lại toàn bộ nội thất theo phong cách tối giản hiện đại, tiết kiệm chi phí cho gia chủ.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự Án Biệt Thự Nghỉ Dưỡng Sinh Thái Nam Hòa Xuân, Đà Nẵng',
        category: 'Biệt thự Đà Nẵng',
        type: 'biet-thu',
        desc: 'Biệt thự sinh thái cao cấp tại Nam Hòa Xuân, đề cao vật liệu tự nhiên như gỗ, đá và mảng xanh bao quanh công trình.'
      }
    ];

    /* 4. Dữ liệu 4 Bài Viết Kinh Nghiệm Xây Nhà Trang Chủ */
    var homepageArticles = [
      {
        id: '1S3P2vt0jZS9FFfyy4Ef-42CN_13sk4yP',
        title: 'Báo Giá Xây Nhà Trọn Gói Đà Nẵng Mới Nhất & Cách Tính Diện Tích',
        category: 'Báo giá & Dự toán',
        summary: 'Hướng dẫn chi tiết cách tính m² xây dựng phần móng, thân, mái và các yếu tố ảnh hưởng đến đơn giá xây nhà tại Đà Nẵng.',
        content: 'Khi chuẩn bị xây dựng tổ ấm tại Đà Nẵng, việc nắm rõ cách tính diện tích xây dựng (móng băng, móng cọc, diện tích sàn các tầng, sân thượng, mái bê tông cốt thép) giúp gia chủ chủ động 100% kế hoạch tài chính. Tại SALA Architecture, bảng dự toán luôn được bóc tách chi tiết từng chủng loại vật tư phần thô và hoàn thiện trước khi ký hợp đồng.'
      },
      {
        id: '1m1HiNLmr3L4pnyC2-G8gLdQjPHKDExX9',
        title: 'Xu Hướng Thiết Kế Kiến Trúc Xanh Cho Nhà Phố Khí Hậu Đà Nẵng',
        category: 'Kiến trúc xanh',
        summary: 'Giải pháp giếng trời, thông gió đối lưu, lam chắn nắng và sân vườn ban công giúp nhà phố luôn mát mẻ quanh năm.',
        content: 'Đặc thù khí hậu Đà Nẵng có mùa nắng gắt và mùa mưa bão. Giải pháp kiến trúc xanh của SALA tập trung vào việc định hướng cửa đón gió mát Đông Nam, bố trí khoảng đệm cây xanh mặt tiền hướng Tây và sử dụng giếng trời trung tâm tạo luồng đối lưu không khí tự nhiên, giảm đáng kể điện năng tiêu thụ.'
      },
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: '5 Tiêu Chuẩn Quan Trọng Khi Nghiệm Thu Thi Công Phần Thô',
        category: 'Kinh nghiệm thi công',
        summary: 'Những hạng mục cốt lõi quyết định tuổi thọ công trình: cốt thép móng, bảo dưỡng bê tông, chống nứt tường và chống thấm.',
        content: 'Phần thô là khung xương quyết định độ bền vững hàng chục năm của ngôi nhà. Chủ đầu tư cần lưu ý kiểm tra đúng chủng loại thép, sử dụng con kê bê tông bảo vệ lớp thép, bảo dưỡng ẩm sàn bê tông liên tục 7 ngày, đóng lưới thép chống nứt tại vị trí tiếp giáp cột – tường và ngâm thử nước chống thấm sàn vệ sinh tối thiểu 48 giờ.'
      },
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Kinh Nghiệm Bố Trí Phong Thủy Nhà Phố Hài Hòa & Đầy Đủ Công Năng',
        category: 'Phong thủy nhà ở',
        summary: 'Cách sắp xếp hướng cửa chính, phòng bếp, cầu thang và phòng thờ khoa học, vừa hợp phong thủy vừa thuận tiện sinh hoạt.',
        content: 'Phong thủy kiến trúc hiện đại hướng đến sự thông thoáng, cân bằng ánh sáng và luồng khí lưu thông dễ chịu trong nhà. Khi thiết kế, kiến trúc sư SALA luôn kết hợp yếu tố tuổi mệnh gia chủ với nguyên lý công năng khoa học như tránh đặt bếp đối diện trực tiếp cửa chính hoặc nhà vệ sinh, ưu tiên phòng thờ tại vị trí trang trọng yên tĩnh nhất.'
      }
    ];

    /**
     * Render thẻ sản phẩm/dự án chuẩn Flatsome:
     * - Không nhãn dán (no overlay badge)
     * - 2 cột trên điện thoại
     * - Tên sản phẩm hiển thị đầy đủ, không cắt chữ, không tràn viền
     */
    function createProjectCard(item) {
      var card = document.createElement('article');
      card.className = 'flatsome-card group bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer flex flex-col';

      card.innerHTML =
        '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
          '<img src="' + getDriveUrl(item.id, 800) + '" data-drive-id="' + item.id + '" alt="' + item.title + '" loading="lazy" class="drive-img flatsome-card-img w-full h-full object-cover" />' +
        '</div>' +
        '<div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">' +
          '<h3 class="text-[12.5px] sm:text-[13.5px] lg:text-sm font-bold text-sala-900 group-hover:text-sala-700 leading-snug break-words">' + item.title + '</h3>' +
          '<p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">' + item.category + '</p>' +
        '</div>';

      var img = card.querySelector('img');
      attachDriveFallback(img);

      card.addEventListener('click', function () {
        openDetailModal({
          id: item.id,
          category: item.category,
          title: item.title,
          desc: item.desc
        });
      });

      return card;
    }

    /**
     * Render thẻ bài viết trang chủ (2 cột trên điện thoại, tên đầy đủ)
     */
    function createArticleCard(article) {
      var card = document.createElement('article');
      card.className = 'flatsome-card group bg-white rounded-xl sm:rounded-2xl border border-slate-200/80 overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer flex flex-col';

      card.innerHTML =
        '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
          '<img src="' + getDriveUrl(article.id, 800) + '" data-drive-id="' + article.id + '" alt="' + article.title + '" loading="lazy" class="drive-img flatsome-card-img w-full h-full object-cover" />' +
        '</div>' +
        '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
          '<div>' +
            '<p class="text-[10.5px] sm:text-[11px] font-semibold text-gold-600 mb-1">' + article.category + '</p>' +
            '<h3 class="text-[12.5px] sm:text-sm font-bold text-sala-900 group-hover:text-sala-700 leading-snug break-words mb-2">' + article.title + '</h3>' +
            '<p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3">' + article.summary + '</p>' +
          '</div>' +
          '<span class="inline-flex items-center gap-1 text-[11px] sm:text-xs font-semibold text-sala-700">Đọc chi tiết <i class="fa-solid fa-angle-right text-[10px]"></i></span>' +
        '</div>';

      var img = card.querySelector('img');
      attachDriveFallback(img);

      card.addEventListener('click', function () {
        openDetailModal({
          id: article.id,
          category: article.category,
          title: article.title,
          desc: article.content
        });
      });

      return card;
    }

    /* Render danh mục các dự án Đà Nẵng theo bộ lọc */
    function renderDanangProjects(filterType) {
      var container = document.getElementById('danang-grid');
      if (!container) return;
      container.innerHTML = '';

      var filtered = danangProjects.filter(function (item) {
        return filterType === 'all' || item.type === filterType;
      });

      filtered.forEach(function (item) {
        container.appendChild(createProjectCard(item));
      });
    }

    /* Điều khiển Modal chi tiết */
    var modalEl = document.getElementById('detail-modal');
    var modalImg = document.getElementById('modal-img');
    var modalCat = document.getElementById('modal-category');
    var modalTitle = document.getElementById('modal-title');
    var modalDesc = document.getElementById('modal-desc');

    function openDetailModal(data) {
      if (!modalEl) return;
      modalImg.dataset.fallbackStep = '0';
      modalImg.setAttribute('data-drive-id', data.id);
      modalImg.src = getDriveUrl(data.id, 1200);
      modalImg.alt = data.title;
      attachDriveFallback(modalImg);

      modalCat.textContent = data.category;
      modalTitle.textContent = data.title;
      modalDesc.innerHTML = '<p>' + data.desc + '</p>';

      modalEl.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      if (!modalEl) return;
      modalEl.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /* Khởi tạo toàn bộ giao diện khi tải trang */
    document.addEventListener('DOMContentLoaded', function () {
      try {
        // Gắn fallback cho tất cả ảnh Drive tĩnh trong HTML
        document.querySelectorAll('.drive-img').forEach(attachDriveFallback);

        // Render lưới Thiết kế xây dựng (5 ảnh)
        var designGrid = document.getElementById('design-grid');
        if (designGrid) {
          designProjects.forEach(function (item) {
            designGrid.appendChild(createProjectCard(item));
          });
        }

        // Render lưới Thi công thực tế (9 ảnh)
        var constructionGrid = document.getElementById('construction-grid');
        if (constructionGrid) {
          constructionProjects.forEach(function (item) {
            constructionGrid.appendChild(createProjectCard(item));
          });
        }

        // Render lưới Dự án Đà Nẵng (10 ảnh)
        renderDanangProjects('all');

        // Render lưới Bài viết trang chủ (4 bài)
        var articlesGrid = document.getElementById('articles-grid');
        if (articlesGrid) {
          homepageArticles.forEach(function (article) {
            articlesGrid.appendChild(createArticleCard(article));
          });
        }

        // Bộ lọc Dự án Đà Nẵng
        var filterBtns = document.querySelectorAll('.danang-filter-btn');
        filterBtns.forEach(function (btn) {
          btn.addEventListener('click', function () {
            var filter = btn.getAttribute('data-filter');
            filterBtns.forEach(function (b) {
              b.classList.remove('bg-sala-800', 'text-white');
              b.classList.add('bg-slate-100', 'text-slate-700');
            });
            btn.classList.remove('bg-slate-100', 'text-slate-700');
            btn.classList.add('bg-sala-800', 'text-white');
            renderDanangProjects(filter);
          });
        });

        // Menu Mobile
        var mobileBtn = document.getElementById('mobile-menu-btn');
        var mobileMenu = document.getElementById('mobile-menu');
        if (mobileBtn && mobileMenu) {
          mobileBtn.addEventListener('click', function () {
            mobileMenu.classList.toggle('hidden');
          });
          document.querySelectorAll('.mobile-nav-link').forEach(function (link) {
            link.addEventListener('click', function () {
              mobileMenu.classList.add('hidden');
            });
          });
        }

        // Slider 2 Banner Tự Trượt Chuyên Nghiệp
        var slides = document.querySelectorAll('.hero-slide-item');
        var dots = document.querySelectorAll('.hero-dot');
        var currentSlide = 0;
        var slideInterval = null;

        function showSlide(index) {
          if (!slides.length) return;
          currentSlide = (index + slides.length) % slides.length;
          slides.forEach(function (slide, idx) {
            slide.classList.toggle('active', idx === currentSlide);
          });
          dots.forEach(function (dot, idx) {
            if (idx === currentSlide) {
              dot.classList.remove('w-2.5', 'bg-white/55');
              dot.classList.add('w-7', 'bg-gold-400');
            } else {
              dot.classList.remove('w-7', 'bg-gold-400');
              dot.classList.add('w-2.5', 'bg-white/55');
            }
          });
        }

        function startAutoSlide() {
          if (slideInterval) clearInterval(slideInterval);
          slideInterval = setInterval(function () {
            showSlide(currentSlide + 1);
          }, 5500);
        }

        var prevBtn = document.getElementById('hero-prev');
        var nextBtn = document.getElementById('hero-next');
        if (prevBtn) {
          prevBtn.addEventListener('click', function () {
            showSlide(currentSlide - 1);
            startAutoSlide();
          });
        }
        if (nextBtn) {
          nextBtn.addEventListener('click', function () {
            showSlide(currentSlide + 1);
            startAutoSlide();
          });
        }
        dots.forEach(function (dot) {
          dot.addEventListener('click', function () {
            var idx = parseInt(dot.getAttribute('data-slide'), 10);
            showSlide(idx);
            startAutoSlide();
          });
        });

        // Hỗ trợ vuốt cảm ứng trên điện thoại cho Banner Slider
        var sliderEl = document.getElementById('hero-slides-grid');
        var touchStartX = 0;
        if (sliderEl) {
          sliderEl.addEventListener('touchstart', function (e) {
            touchStartX = e.changedTouches[0].screenX;
          }, { passive: true });
          sliderEl.addEventListener('touchend', function (e) {
            var touchEndX = e.changedTouches[0].screenX;
            if (touchStartX - touchEndX > 45) {
              showSlide(currentSlide + 1);
              startAutoSlide();
            } else if (touchEndX - touchStartX > 45) {
              showSlide(currentSlide - 1);
              startAutoSlide();
            }
          }, { passive: true });
        }

        startAutoSlide();

        // Đóng Modal
        var closeBtn = document.getElementById('modal-close-btn');
        var modalQuoteBtn = document.getElementById('modal-quote-btn');
        if (closeBtn) closeBtn.addEventListener('click', closeDetailModal);
        if (modalQuoteBtn) modalQuoteBtn.addEventListener('click', closeDetailModal);
        if (modalEl) {
          modalEl.addEventListener('click', function (e) {
            if (e.target === modalEl) closeDetailModal();
          });
        }
        document.addEventListener('keydown', function (e) {
          if (e.key === 'Escape') closeDetailModal();
        });

        // Xử lý Form Yêu Cầu Tư Vấn & Báo Giá (hiển thị thông báo ngay trên trang, không dùng alert)
        var quoteForm = document.getElementById('quote-form');
        var quoteFeedback = document.getElementById('quote-feedback');
        if (quoteForm && quoteFeedback) {
          quoteForm.addEventListener('submit', function (e) {
            e.preventDefault();
            var name = document.getElementById('customer-name').value.trim();
            var phone = document.getElementById('customer-phone').value.trim();
            var service = document.getElementById('service-type').value;
            var budget = document.getElementById('budget-range').value;

            if (!name || !phone) {
              quoteFeedback.className = 'rounded-xl p-3.5 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
              quoteFeedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để SALA Architecture liên hệ tư vấn cho bạn.';
              quoteFeedback.classList.remove('hidden');
              return;
            }

            quoteFeedback.className = 'rounded-xl p-3.5 text-xs sm:text-sm font-medium bg-sala-50 text-sala-800 border border-sala-200';
            quoteFeedback.innerHTML =
              'Cảm ơn <strong>' + name + '</strong>! SALA Architecture đã ghi nhận yêu cầu <strong>' + service + '</strong> (ngân sách ' + budget + '). Kiến trúc sư sẽ liên hệ số <strong>' + phone + '</strong> hoặc bạn có thể gọi trực tiếp Hotline <strong>0949.857.007</strong>.';
            quoteFeedback.classList.remove('hidden');
            quoteForm.reset();
          });
        }
      } catch (err) {
        console.error('Lỗi khởi tạo giao diện SALA Architecture:', err);
      }
    });
  </script>
</body>
</html>
