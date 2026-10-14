<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Sabariah, S.A.B - Certified Caregiver & Data Specialist</title>
  
  <!-- Font Google Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  
  <style>
    /* ==========================================================================
       THEME: PROFESSIONAL SOFT WHITE & SOFT BLUE (MEDICAL & CORPORATE)
       Palette: Soft White (#ffffff, #f8fafc), Soft Blue (#2563eb, #3b82f6, #eff6ff)
       ========================================================================== */
    :root {
      --bg-body: #f8fafc;
      --bg-surface: #ffffff;
      --bg-card: #ffffff;
      --border-subtle: #e2e8f0;
      --border-accent: #dbeafe;
      --blue-primary: #2563eb;
      --blue-dark: #1d4ed8;
      --blue-soft: #eff6ff;
      --blue-glow: rgba(37, 99, 235, 0.12);
      --text-main: #0f172a;
      --text-muted: #475569;
      --text-light: #94a3b8;
      --shadow-sm: 0 1px 3px rgba(15, 23, 42, 0.05);
      --shadow-md: 0 4px 16px -2px rgba(37, 99, 235, 0.06);
      --shadow-lg: 0 10px 28px -4px rgba(15, 23, 42, 0.08);
      --transition-smooth: all 0.22s cubic-bezier(0.4, 0, 0.2, 1);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      -webkit-tap-highlight-color: transparent;
    }

    body {
      font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: var(--bg-body);
      color: var(--text-main);
      min-height: 100vh;
      line-height: 1.6;
      overflow-x: hidden;
      display: flex;
      flex-direction: column;
    }

    /* Scrollbar */
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: #f1f5f9;
    }
    ::-webkit-scrollbar-thumb {
      background: #cbd5e1;
      border-radius: 4px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: var(--blue-primary);
    }

    .container {
      width: 100%;
      max-width: 1140px;
      margin: 0 auto;
      padding: 0 20px;
    }

    .navbar {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(255, 255, 255, 0.96);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border-subtle);
      box-shadow: 0 1px 10px rgba(15, 23, 42, 0.03);
    }
    .nav-wrapper {
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 64px;
      gap: 12px;
    }
    .brand-logo {
      display: flex;
      flex-direction: column;
      cursor: pointer;
      text-decoration: none;
      user-select: none;
      min-width: 0;
      flex-shrink: 1;
    }
    .brand-title {
      font-size: 1.05rem;
      font-weight: 800;
      color: var(--text-main);
      letter-spacing: -0.3px;
      line-height: 1.18;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }
    .brand-sub {
      font-size: 0.68rem;
      color: var(--blue-primary);
      font-weight: 600;
      letter-spacing: 0.1px;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }

    .nav-actions-group {
      display: flex;
      align-items: center;
      gap: 8px;
      flex-shrink: 0;
    }
    .lang-switcher {
      display: inline-flex;
      align-items: center;
      background: #f1f5f9;
      border: 1px solid var(--border-subtle);
      border-radius: 20px;
      padding: 2px;
      cursor: pointer;
      font-size: 0.72rem;
      font-weight: 700;
      user-select: none;
      transition: var(--transition-smooth);
    }
    .lang-btn {
      padding: 3px 9px;
      border-radius: 16px;
      color: var(--text-muted);
      transition: var(--transition-smooth);
    }
    .lang-btn.active {
      background: var(--blue-primary);
      color: #ffffff;
      box-shadow: 0 2px 6px var(--blue-glow);
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 4px;
      list-style: none;
    }
    .nav-item {
      padding: 7px 11px;
      font-size: 0.81rem;
      font-weight: 600;
      color: var(--text-muted);
      border-radius: 8px;
      cursor: pointer;
      transition: var(--transition-smooth);
      display: flex;
      align-items: center;
      gap: 6px;
      white-space: nowrap;
    }
    .nav-item:hover {
      color: var(--blue-primary);
      background: var(--blue-soft);
    }
    .nav-item.active {
      color: #ffffff;
      background: var(--blue-primary);
      box-shadow: 0 2px 8px var(--blue-glow);
    }
    .nav-item svg {
      width: 14px;
      height: 14px;
      fill: currentColor;
    }

    .mobile-menu-btn {
      display: none;
      background: #f1f5f9;
      border: 1px solid var(--border-subtle);
      border-radius: 8px;
      cursor: pointer;
      color: var(--text-main);
      padding: 6px;
    }
    .mobile-menu-btn svg {
      width: 20px;
      height: 20px;
      fill: currentColor;
    }

    .mobile-drawer {
      display: none;
      position: fixed;
      top: 64px;
      left: 0;
      width: 100%;
      background: #ffffff;
      border-bottom: 2px solid var(--blue-primary);
      padding: 14px 16px 20px;
      z-index: 999;
      box-shadow: var(--shadow-lg);
    }
    .mobile-drawer.open {
      display: block;
    }
    .mobile-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 8px;
    }
    .mobile-nav-item {
      padding: 9px 11px;
      border-radius: 8px;
      background: #f8fafc;
      border: 1px solid var(--border-subtle);
      font-size: 0.8rem;
      font-weight: 600;
      color: var(--text-main);
      display: flex;
      align-items: center;
      gap: 8px;
      cursor: pointer;
    }
    .mobile-nav-item.active {
      background: var(--blue-soft);
      color: var(--blue-primary);
      border-color: var(--blue-primary);
      font-weight: 700;
    }

    .view-content {
      display: none;
      opacity: 0;
      transform: translateY(6px);
      transition: opacity 0.25s ease, transform 0.25s ease;
      padding: 24px 0 50px;
    }
    .view-content.active {
      display: block;
      opacity: 1;
      transform: translateY(0);
    }

    .section-header {
      margin-bottom: 24px;
      text-align: center;
    }
    .section-tag {
      display: inline-block;
      padding: 4px 12px;
      border-radius: 30px;
      font-size: 0.72rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.6px;
      background: var(--blue-soft);
      color: var(--blue-dark);
      border: 1px solid var(--border-accent);
      margin-bottom: 8px;
    }
    .section-title {
      font-size: 1.7rem;
      font-weight: 800;
      color: var(--text-main);
      letter-spacing: -0.5px;
    }
    .section-desc {
      font-size: 0.88rem;
      color: var(--text-muted);
      max-width: 640px;
      margin: 6px auto 0;
    }

    .pro-card {
      background: var(--bg-card);
      border: 1px solid var(--border-subtle);
      border-radius: 14px;
      padding: 20px;
      box-shadow: var(--shadow-sm);
      transition: var(--transition-smooth);
      position: relative;
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }
    .pro-card:hover {
      border-color: #bfdbfe;
      box-shadow: var(--shadow-md);
      transform: translateY(-2px);
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      padding: 10px 18px;
      border-radius: 10px;
      font-size: 0.85rem;
      font-weight: 700;
      cursor: pointer;
      border: none;
      text-decoration: none;
      transition: var(--transition-smooth);
      white-space: nowrap;
    }
    .btn-primary {
      background: var(--blue-primary);
      color: #ffffff;
      box-shadow: 0 3px 10px var(--blue-glow);
    }
    .btn-primary:hover {
      background: var(--blue-dark);
      box-shadow: 0 4px 14px rgba(37, 99, 235, 0.25);
    }
    .btn-outline {
      background: #ffffff;
      color: var(--blue-dark);
      border: 1px solid var(--border-subtle);
    }
    .btn-outline:hover {
      background: var(--blue-soft);
      border-color: var(--blue-primary);
    }
    .btn svg {
      width: 15px;
      height: 15px;
      fill: currentColor;
    }

    .hero-box {
      background: #ffffff;
      border: 1px solid var(--border-subtle);
      border-radius: 18px;
      padding: 36px 32px;
      box-shadow: var(--shadow-sm);
      display: flex;
      flex-direction: column;
      gap: 18px;
      position: relative;
      overflow: hidden;
    }
    .hero-watermark-bg {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 380px;
      height: 380px;
      max-width: 92%;
      max-height: 92%;
      background-image: url('https://lh3.googleusercontent.com/d/1yUfPjYU82pMYb3fwOpmss9NuEsCvAwpG');
      background-size: contain;
      background-position: center;
      background-repeat: no-repeat;
      opacity: 0.28;
      filter: contrast(1.22) saturate(1.12) drop-shadow(0 4px 16px rgba(37, 99, 235, 0.10));
      pointer-events: none;
      z-index: 1;
      mask-image: radial-gradient(circle at center, black 65%, transparent 98%);
      -webkit-mask-image: radial-gradient(circle at center, black 65%, transparent 98%);
    }
    .hero-content-inner {
      position: relative;
      z-index: 2;
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .hero-badge-pill {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      padding: 4px 12px;
      border-radius: 20px;
      background: var(--blue-soft);
      border: 1px solid var(--border-accent);
      width: fit-content;
      font-size: 0.75rem;
      font-weight: 700;
      color: var(--blue-dark);
    }
    .pulse-dot {
      width: 7px;
      height: 7px;
      background: var(--blue-primary);
      border-radius: 50%;
      animation: pulse 1.6s infinite;
    }
    @keyframes pulse {
      0% { opacity: 0.4; transform: scale(0.9); }
      50% { opacity: 1; transform: scale(1.3); }
      100% { opacity: 0.4; transform: scale(0.9); }
    }
    .hero-title {
      font-size: 2.15rem;
      font-weight: 800;
      line-height: 1.25;
      color: var(--text-main);
      letter-spacing: -0.7px;
    }
    .hero-title span {
      color: var(--blue-primary);
    }
    .hero-bio {
      font-size: 0.93rem;
      color: #334155;
      line-height: 1.7;
      max-width: 860px;
    }

    .badge-slider {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding-bottom: 4px;
      scrollbar-width: none;
      -webkit-overflow-scrolling: touch;
      flex-wrap: wrap;
    }
    .badge-slider::-webkit-scrollbar {
      display: none;
    }
    .skill-pill {
      flex-shrink: 0;
      font-size: 0.77rem;
      font-weight: 600;
      padding: 6px 12px;
      border-radius: 8px;
      background: #f8fafc;
      border: 1px solid var(--border-subtle);
      color: #1e293b;
      display: inline-flex;
      align-items: center;
      gap: 6px;
      white-space: nowrap;
    }
    .skill-pill svg {
      width: 14px;
      height: 14px;
      fill: var(--blue-primary);
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 12px;
      margin-top: 4px;
    }

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 18px;
    }
    .card-badge {
      display: inline-flex;
      align-items: center;
      font-size: 0.7rem;
      font-weight: 700;
      color: var(--blue-dark);
      background: var(--blue-soft);
      border: 1px solid var(--border-accent);
      padding: 3px 8px;
      border-radius: 6px;
      margin-bottom: 10px;
      width: fit-content;
    }
    .card-title {
      font-size: 1.02rem;
      font-weight: 700;
      color: var(--text-main);
      line-height: 1.35;
      margin-bottom: 4px;
    }
    .card-issuer {
      font-size: 0.8rem;
      color: var(--blue-dark);
      font-weight: 600;
      margin-bottom: 8px;
    }
    .card-desc {
      font-size: 0.84rem;
      color: var(--text-muted);
      line-height: 1.55;
      margin-bottom: 14px;
    }
    .card-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-top: auto;
      padding-top: 12px;
      border-top: 1px solid var(--border-subtle);
    }

    .timeline-container {
      position: relative;
      max-width: 820px;
      margin: 0 auto;
      padding: 6px 0 16px;
    }
    .timeline-container::after {
      content: '';
      position: absolute;
      width: 2px;
      background: #cbd5e1;
      top: 18px;
      bottom: 18px;
      left: 18px;
    }
    .timeline-item {
      position: relative;
      margin-left: 50px;
      margin-bottom: 22px;
    }
    .timeline-dot {
      position: absolute;
      left: -39px;
      top: 8px;
      width: 14px;
      height: 14px;
      border-radius: 50%;
      background: #ffffff;
      border: 3px solid var(--blue-primary);
      box-shadow: 0 0 0 3px var(--blue-soft);
      z-index: 10;
    }
    .timeline-header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      gap: 6px;
      margin-bottom: 4px;
    }
    .timeline-period {
      font-size: 0.72rem;
      font-weight: 700;
      padding: 3px 8px;
      border-radius: 5px;
      background: var(--blue-soft);
      color: var(--blue-dark);
      border: 1px solid var(--border-accent);
    }

    .contact-layout {
      display: grid;
      grid-template-columns: 1fr 1.3fr;
      gap: 24px;
      align-items: start;
    }
    .info-box {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 12px;
      border-radius: 10px;
      background: #ffffff;
      border: 1px solid var(--border-subtle);
      text-decoration: none;
      color: var(--text-main);
      transition: var(--transition-smooth);
    }
    .info-box:hover {
      border-color: var(--blue-primary);
      transform: translateX(3px);
      box-shadow: var(--shadow-sm);
    }
    .info-box-icon {
      width: 38px;
      height: 38px;
      border-radius: 8px;
      background: var(--blue-soft);
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }
    .info-box-icon svg {
      width: 18px;
      height: 18px;
      fill: var(--blue-primary);
    }
    .form-group {
      margin-bottom: 14px;
    }
    .form-label {
      display: block;
      font-size: 0.78rem;
      font-weight: 700;
      color: var(--text-main);
      margin-bottom: 5px;
    }
    .form-control {
      width: 100%;
      padding: 10px 12px;
      border-radius: 8px;
      background: #f8fafc;
      border: 1px solid var(--border-subtle);
      color: var(--text-main);
      font-size: 0.86rem;
      font-family: inherit;
      transition: var(--transition-smooth);
    }
    .form-control:focus {
      outline: none;
      background: #ffffff;
      border-color: var(--blue-primary);
      box-shadow: 0 0 0 3px var(--blue-soft);
    }
    textarea.form-control {
      resize: vertical;
      min-height: 95px;
    }

    .modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(15, 23, 42, 0.5);
      backdrop-filter: blur(4px);
      z-index: 2000;
      display: none;
      align-items: center;
      justify-content: center;
      padding: 16px;
    }
    .modal-overlay.open {
      display: flex;
    }
    .modal-card {
      width: 100%;
      max-width: 400px;
      background: #ffffff;
      border-radius: 16px;
      padding: 24px;
      box-shadow: var(--shadow-lg);
      position: relative;
      text-align: center;
    }
    .modal-close-btn {
      position: absolute;
      top: 14px;
      right: 14px;
      background: #f1f5f9;
      border: none;
      border-radius: 50%;
      width: 30px;
      height: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: var(--text-muted);
      cursor: pointer;
    }
    .modal-close-btn svg {
      width: 16px;
      height: 16px;
      fill: currentColor;
    }

    .toast-container {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 3000;
      display: flex;
      flex-direction: column;
      gap: 8px;
      pointer-events: none;
    }
    .toast {
      min-width: 270px;
      padding: 12px 16px;
      border-radius: 10px;
      background: #ffffff;
      border: 1px solid var(--border-subtle);
      border-left: 4px solid var(--blue-primary);
      color: var(--text-main);
      font-size: 0.84rem;
      font-weight: 600;
      box-shadow: var(--shadow-lg);
      display: flex;
      align-items: center;
      gap: 10px;
      transform: translateY(16px);
      opacity: 0;
      transition: all 0.25s ease;
      pointer-events: auto;
    }
    .toast.show {
      transform: translateY(0);
      opacity: 1;
    }

    .mobile-bottom-bar {
      display: none;
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 58px;
      background: #ffffff;
      border-top: 1px solid var(--border-subtle);
      z-index: 1000;
      padding: 0 4px;
      align-items: center;
      justify-content: space-around;
      box-shadow: 0 -2px 8px rgba(0, 0, 0, 0.02);
    }
    .bottom-tab {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 2px;
      font-size: 0.67rem;
      color: var(--text-muted);
      cursor: pointer;
      text-decoration: none;
      padding: 4px 6px;
      border-radius: 6px;
    }
    .bottom-tab.active {
      color: var(--blue-primary);
      font-weight: 700;
    }
    .bottom-tab svg {
      width: 17px;
      height: 17px;
      fill: currentColor;
    }

    @media (max-width: 992px) {
      .nav-links {
        display: none;
      }
      .mobile-menu-btn {
        display: block;
      }
      .contact-layout {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 768px) {
      .brand-title {
        font-size: 0.94rem;
      }
      .brand-sub {
        font-size: 0.63rem;
      }
      .hero-box {
        padding: 24px 18px;
      }
      .hero-watermark-bg {
        width: 290px;
        height: 290px;
        opacity: 0.26;
      }
      .hero-title {
        font-size: 1.78rem;
      }
      .section-title {
        font-size: 1.45rem;
      }
      .mobile-bottom-bar {
        display: flex;
      }
      body {
        padding-bottom: 60px;
      }
      .badge-slider {
        flex-wrap: nowrap;
        padding-bottom: 6px;
      }
      .timeline-container::after {
        left: 12px;
      }
      .timeline-dot {
        left: -32px;
      }
      .timeline-item {
        margin-left: 38px;
      }
    }
  </style>
</head>
<body>

  <header class="navbar">
    <div class="container nav-wrapper">
      <div class="brand-logo" onclick="switchView('home')">
        <h1 class="brand-title">Sabariah, S.A.B</h1>
        <span class="brand-sub" data-i18n="brand_sub">Certified Caregiver & Data Specialist</span>
      </div>

      <!-- Desktop Navigation Tabs -->
      <ul class="nav-links">
        <li class="nav-item active" data-view="home" onclick="switchView('home')">
          <svg viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
          <span data-i18n="nav_home">Home</span>
        </li>
        <li class="nav-item" data-view="certifications" onclick="switchView('certifications')">
          <svg viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/></svg>
          <span data-i18n="nav_cert">Certifications</span>
        </li>
        <li class="nav-item" data-view="experience" onclick="switchView('experience')">
          <svg viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8zm.5-13H11v6l5.25 3.15.75-1.23-4.5-2.67z"/></svg>
          <span data-i18n="nav_exp">Experience</span>
        </li>
        <li class="nav-item" data-view="trainer" onclick="switchView('trainer')">
          <svg viewBox="0 0 24 24"><path d="M20 18c1.1 0 1.99-.9 1.99-2L22 6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2H0v2h24v-2h-4zM4 6h16v10H4V6z"/></svg>
          <span data-i18n="nav_trainer">Trainer & IT</span>
        </li>
        <li class="nav-item" data-view="leadership" onclick="switchView('leadership')">
          <svg viewBox="0 0 24 24"><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 3s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z"/></svg>
          <span data-i18n="nav_lead">Leadership</span>
        </li>
        <li class="nav-item" data-view="education" onclick="switchView('education')">
          <svg viewBox="0 0 24 24"><path d="M5 13.18v4L12 21l7-3.82v-4L12 17l-7-3.82zM12 3L1 9l11 6 9-4.91V17h2V9L12 3z"/></svg>
          <span data-i18n="nav_edu">Education</span>
        </li>
        <li class="nav-item" data-view="projects" onclick="switchView('projects')">
          <svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-5 14H7v-2h7v2zm3-4H7v-2h10v2zm0-4H7V7h10v2z"/></svg>
          <span data-i18n="nav_proj">Projects</span>
        </li>
        <li class="nav-item" data-view="contact" onclick="switchView('contact')">
          <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
          <span data-i18n="nav_contact">Contact</span>
        </li>
      </ul>

      <!-- Language Switcher & Mobile Menu Button -->
      <div class="nav-actions-group">
        <div class="lang-switcher" onclick="toggleLanguage()" title="Switch Language">
          <span class="lang-btn" id="langBtnId">ID</span>
          <span class="lang-btn" id="langBtnEn">EN</span>
        </div>

        <button class="mobile-menu-btn" onclick="toggleMobileDrawer()" aria-label="Menu">
          <svg viewBox="0 0 24 24"><path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"/></svg>
        </button>
      </div>
    </div>

    <div class="mobile-drawer" id="mobileDrawer">
      <div class="mobile-grid">
        <div class="mobile-nav-item active" onclick="switchView('home'); toggleMobileDrawer();" data-i18n="nav_home">Home</div>
        <div class="mobile-nav-item" onclick="switchView('certifications'); toggleMobileDrawer();" data-i18n="nav_cert">Certifications</div>
        <div class="mobile-nav-item" onclick="switchView('experience'); toggleMobileDrawer();" data-i18n="nav_exp">Experience</div>
        <div class="mobile-nav-item" onclick="switchView('trainer'); toggleMobileDrawer();" data-i18n="nav_trainer">Trainer & IT</div>
        <div class="mobile-nav-item" onclick="switchView('leadership'); toggleMobileDrawer();" data-i18n="nav_lead">Leadership</div>
        <div class="mobile-nav-item" onclick="switchView('education'); toggleMobileDrawer();" data-i18n="nav_edu">Education</div>
        <div class="mobile-nav-item" onclick="switchView('projects'); toggleMobileDrawer();" data-i18n="nav_proj">Projects</div>
        <div class="mobile-nav-item" onclick="switchView('contact'); toggleMobileDrawer();" data-i18n="nav_contact">Contact</div>
      </div>
    </div>
  </header>

  <main class="container">
    
    <!-- 1. HOME VIEW -->
    <section id="view-home" class="view-content active">
      <div class="hero-box">
        <!-- Transparent Centered Watermark Image Layer -->
        <div class="hero-watermark-bg"></div>

        <div class="hero-content-inner">
          <div class="hero-badge-pill">
            <span class="pulse-dot"></span>
            <span data-i18n="hero_status">Live-in Caregiver & Remote Virtual Health Support</span>
          </div>
          
          <h2 class="hero-title">
            <span data-i18n="hero_title_1">Human Touch Caregiver & </span>
            <span data-i18n="hero_title_2">Data-Driven Precision</span>
          </h2>
          
          <p class="hero-bio" data-i18n="hero_bio">
            Saya <strong>Sabariah, S.A.B</strong>, Certified Caregiver dengan pengalaman profesional tinggal bersama pasien di Dubai dan Hong Kong. Dilengkapi sertifikasi resmi <strong>BNSP Data Analyst</strong> & <strong>BNSP Microsoft Office</strong>, saya mengintegrasikan empati pendampingan lansia holistik dengan keahlian operasional data medis, alur telehealth jarak jauh, dan dokumentasi vital sign terstruktur.
          </p>

          <!-- Horizontal Swipeable Badge Slider -->
          <div class="badge-slider">
            <span class="skill-pill">
              <svg viewBox="0 0 24 24"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>
              <span data-i18n="pill_health">Elderly Care & CPR/AED</span>
            </span>
            <span class="skill-pill">
              <svg viewBox="0 0 24 24"><path d="M20 18c1.1 0 1.99-.9 1.99-2L22 6c0-1.1-.9-2-2-2H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2H0v2h24v-2h-4zM4 6h16v10H4V6z"/></svg>
              <span>BNSP Data Analyst & Office</span>
            </span>
            <span class="skill-pill">
              <svg viewBox="0 0 24 24"><path d="M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3z"/></svg>
              <span data-i18n="pill_lead">Pengurus IKAUT HK (2026-2031)</span>
            </span>
            <span class="skill-pill">
              <svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2z"/></svg>
              <span data-i18n="pill_research">Sinta 4 Scientific Research</span>
            </span>
          </div>

          <!-- Hero Actions -->
          <div class="hero-actions">
            <a href="https://drive.google.com/file/d/1jAV55lWwrJQa-xDAti3A_-q4BQLv0qyw/view?usp=drive_link" target="_blank" rel="noopener noreferrer" class="btn btn-primary" id="btnDownloadCv">
              <svg viewBox="0 0 24 24"><path d="M19.35 10.04C18.67 6.59 15.64 4 12 4 9.11 4 6.6 5.64 5.35 8.04 2.34 8.36 0 10.91 0 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96zM17 13l-5 5-5-5h3V9h4v4h3z"/></svg>
              <span data-i18n="btn_cv">Download Official CV & Portfolio</span>
            </a>
            <button class="btn btn-outline" onclick="switchView('contact')">
              <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
              <span data-i18n="btn_contact_me">Hubungi Saya</span>
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- 2. CERTIFICATIONS VIEW -->
    <section id="view-certifications" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_cert">Akreditasi Internasional</span>
        <h2 class="section-title" data-i18n="title_cert">Sertifikasi Caregiving & Medis</h2>
        <p class="section-desc" data-i18n="desc_cert">Kualifikasi profesional terakreditasi Hong Kong, Britania Raya (UK), dan Amerika Serikat (US) dalam penanganan lansia dan gawat darurat medis.</p>
      </div>
      <div class="cards-grid" id="cert-grid-container"></div>
    </section>

    <!-- 3. EXPERIENCE VIEW -->
    <section id="view-experience" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_exp">Rekam Jejak Lapangan</span>
        <h2 class="section-title" data-i18n="title_exp">Timeline Pengalaman Sejak 2016</h2>
        <p class="section-desc" data-i18n="desc_exp">Kombinasi pengalaman tinggal bersama pasien (Live-in Caregiver) dan dukungan virtual koordinasi medis lintas negara.</p>
      </div>
      <div class="timeline-container" id="timeline-container"></div>
    </section>

    <!-- 4. TRAINER & IT DOCUMENTATION VIEW -->
    <section id="view-trainer" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_trainer">Kompetensi Digital & K3</span>
        <h2 class="section-title" data-i18n="title_trainer">Dokumentasi Trainer, IT & BNSP</h2>
        <p class="section-desc" data-i18n="desc_trainer">Sertifikasi Badan Nasional Sertifikasi Profesi (BNSP), keahlian Microsoft Office, analisis data, ISO 9001, serta keselamatan K3.</p>
      </div>
      <div class="cards-grid" id="trainer-grid-container"></div>
    </section>

    <!-- 5. LEADERSHIP VIEW -->
    <section id="view-leadership" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_lead">Organisasi & Pengabdian</span>
        <h2 class="section-title" data-i18n="title_lead">Kepemimpinan & Komunitas Alumni</h2>
        <p class="section-desc" data-i18n="desc_lead">Peran aktif kepengurusan di IKAUT Hong Kong, inisiator pelatihan vokasi teknologi, dan pemberdayaan pekerja migran.</p>
      </div>
      <div class="cards-grid" id="leadership-grid-container"></div>
    </section>

    <!-- 6. EDUCATION VIEW -->
    <section id="view-education" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_edu">Pendidikan Formal</span>
        <h2 class="section-title" data-i18n="title_edu">Pendidikan Formal & Legalitas Apostille</h2>
        <p class="section-desc" data-i18n="desc_edu">Sarjana Administrasi Bisnis (S.A.B) dari Universitas Terbuka dengan validasi Ijazah Apostille Kemenkumham RI untuk legalitas global.</p>
      </div>
      <div class="cards-grid" id="education-grid-container"></div>
    </section>

    <!-- 7. PROJECTS & PUBLICATIONS VIEW -->
    <section id="view-projects" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_proj">Karya Nyata & Riset</span>
        <h2 class="section-title" data-i18n="title_proj">Proyek Teknologi Kesehatan & Publikasi</h2>
        <p class="section-desc" data-i18n="desc_proj">Template pelaporan medis digital, dashboard visualisasi data analitik kesehatan, dan artikel riset terakreditasi Jurnal Sinta 4.</p>
      </div>
      <div class="cards-grid" id="projects-grid-container"></div>
    </section>

    <!-- 8. CONTACT VIEW -->
    <section id="view-contact" class="view-content">
      <div class="section-header">
        <span class="section-tag" data-i18n="tag_contact">Komunikasi & Konsultasi</span>
        <h2 class="section-title" data-i18n="title_contact">Hubungi Sabariah, S.A.B</h2>
        <p class="section-desc" data-i18n="desc_contact">Tersedia untuk wawancara caregiver keluarga, asisten virtual medis, training komputer/data, dan kolaborasi riset.</p>
      </div>

      <div class="contact-layout">
        <!-- Direct Contacts -->
        <div class="pro-card">
          <h3 style="font-size: 1.15rem; font-weight: 700; color: var(--text-main); margin-bottom: 10px;" data-i18n="contact_direct">Kontak Langsung</h3>
          <p style="font-size: 0.84rem; color: var(--text-muted); margin-bottom: 14px;" data-i18n="contact_direct_sub">
            Silakan hubungi secara langsung atau pindai kode QR untuk membuka chat WhatsApp seketika.
          </p>

          <div style="display:flex; flex-direction:column; gap:10px;">
            <a href="mailto:riahsaba123@gamil.com" class="info-box">
              <div class="info-box-icon">
                <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
              </div>
              <div>
                <span style="font-size: 0.7rem; color: var(--blue-primary); display: block; font-weight: 700;">Email Resmi</span>
                <span style="font-size: 0.85rem; font-weight: 600;">riahsaba123@gamil.com</span>
              </div>
            </a>

            <a href="https://wa.me/6285202088185" target="_blank" class="info-box">
              <div class="info-box-icon">
                <svg viewBox="0 0 24 24"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91C2.13 13.66 2.59 15.36 3.45 16.86L2.05 22L7.3 20.63C8.75 21.41 10.38 21.82 12.04 21.82C17.5 21.82 21.95 17.37 21.95 11.91C21.95 6.45 17.5 2 12.04 2M12.05 3.67C16.58 3.67 20.28 7.37 20.28 11.91C20.28 16.45 16.58 20.15 12.05 20.15C10.59 20.15 9.17 19.76 7.93 19.03L7.63 18.85L4.53 19.66L5.36 16.64L5.16 16.32C4.38 15.06 3.96 13.5 3.96 11.91C3.96 7.37 7.66 3.67 12.05 3.67Z"/></svg>
              </div>
              <div>
                <span style="font-size: 0.7rem; color: var(--blue-primary); display: block; font-weight: 700;">WhatsApp Direct</span>
                <span style="font-size: 0.85rem; font-weight: 600;">+62 852-0208-8185</span>
              </div>
            </a>

            <a href="https://linkedin.com/in/saba-riah" target="_blank" class="info-box">
              <div class="info-box-icon">
                <svg viewBox="0 0 24 24"><path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14m-.5 15.5v-5.3a3.26 3.26 0 0 0-3.26-3.26c-.85 0-1.84.52-2.28 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 0 1 1.4 1.4v4.93h2.75M6.46 10.9v8.37H9.2V10.9H6.46M7.83 6.45a1.64 1.64 0 1 0 0 3.28 1.64 1.64 0 0 0 0-3.28z"/></svg>
              </div>
              <div>
                <span style="font-size: 0.7rem; color: var(--blue-primary); display: block; font-weight: 700;">LinkedIn Profile</span>
                <span style="font-size: 0.85rem; font-weight: 600;">linkedin.com/in/saba-riah</span>
              </div>
            </a>
          </div>

          <div style="margin-top: 14px;">
            <button class="btn btn-outline" style="width: 100%;" onclick="openQrModal('wa')">
              <svg viewBox="0 0 24 24"><path d="M4 4h6v6H4V4zm2 2v2h2V6H6zm8-2h6v6h-6V4zm2 2v2h2V6h-2zM4 14h6v6H4v-6zm2 2v2h2v-2H6zm10-2h2v2h-2v-2zm-2 2h2v2h-2v-2zm4 2h2v2h-2v-2zm0-4h2v2h-2v-2zm-2 4h2v2h-2v-2z"/></svg>
              <span data-i18n="btn_qr">Tampilkan QR Code WhatsApp</span>
            </button>
          </div>
        </div>

        <!-- Contact Form -->
        <div class="pro-card">
          <h3 style="font-size: 1.15rem; font-weight: 700; color: var(--text-main); margin-bottom: 4px;" data-i18n="form_title">Kirim Pesan Resmi</h3>
          <p style="font-size: 0.82rem; color: var(--text-muted); margin-bottom: 16px;" data-i18n="form_desc">Pesan Anda langsung tersimpan secara aman di database Google Sheet.</p>

          <form id="contactForm" onsubmit="event.preventDefault(); submitContactForm();">
            <div class="form-group">
              <label class="form-label" data-i18n="label_name">Nama Lengkap *</label>
              <input type="text" id="formNama" class="form-control" placeholder="Contoh: Dr. Michael / Keluarga Cheung" required>
            </div>

            <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px;">
              <div class="form-group">
                <label class="form-label">Email</label>
                <input type="email" id="formEmail" class="form-control" placeholder="nama@email.com">
              </div>
              <div class="form-group">
                <label class="form-label">WhatsApp</label>
                <input type="tel" id="formWhatsapp" class="form-control" placeholder="+852 / +62">
              </div>
            </div>

            <div class="form-group">
              <label class="form-label" data-i18n="label_cat">Kategori Keperluan</label>
              <select id="formKategori" class="form-control">
                <option value="Healthcare Caregiver">Healthcare & Live-in Caregiver</option>
                <option value="Virtual Healthcare Support">Virtual Healthcare Support</option>
                <option value="Pelatihan IT & Data">Pelatihan IT / Komputer & Data</option>
                <option value="Riset & Kolaborasi Ilmiah">Riset & Kolaborasi Ilmiah</option>
                <option value="Lainnya">Lainnya</option>
              </select>
            </div>

            <div class="form-group">
              <label class="form-label" data-i18n="label_msg">Pesan / Rincian Kebutuhan *</label>
              <textarea id="formPesan" class="form-control" placeholder="Tuliskan deskripsi kebutuhan perawatan atau kolaborasi Anda..." required></textarea>
            </div>

            <button type="submit" id="btnSubmitContact" class="btn btn-primary" style="width: 100%;">
              <svg viewBox="0 0 24 24"><path d="M2.01 21L23 12 2.01 3 2 10l15 2-15 2z"/></svg>
              <span data-i18n="btn_submit">Kirim Pesan Sekarang</span>
            </button>
          </form>
        </div>
      </div>
    </section>

  </main>

  <!-- Mobile Bottom Tab Bar -->
  <nav class="mobile-bottom-bar">
    <div class="bottom-tab active" data-view="home" onclick="switchView('home')">
      <svg viewBox="0 0 24 24"><path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z"/></svg>
      <span>Home</span>
    </div>
    <div class="bottom-tab" data-view="certifications" onclick="switchView('certifications')">
      <svg viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4z"/></svg>
      <span data-i18n="nav_cert">Sertifikat</span>
    </div>
    <div class="bottom-tab" data-view="experience" onclick="switchView('experience')">
      <svg viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2z"/></svg>
      <span data-i18n="nav_exp">Karier</span>
    </div>
    <div class="bottom-tab" data-view="projects" onclick="switchView('projects')">
      <svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2z"/></svg>
      <span data-i18n="nav_proj">Proyek</span>
    </div>
    <div class="bottom-tab" data-view="contact" onclick="switchView('contact')">
      <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2z"/></svg>
      <span data-i18n="nav_contact">Kontak</span>
    </div>
  </nav>

  <!-- Modal Dialog QR Code -->
  <div class="modal-overlay" id="qrModal" onclick="closeQrModal(event)">
    <div class="modal-card" onclick="event.stopPropagation();">
      <button class="modal-close-btn" onclick="closeQrModal()">
        <svg viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12z"/></svg>
      </button>
      <div id="modalContentInner"></div>
    </div>
  </div>

  <!-- Toast Notification -->
  <div class="toast-container" id="toastContainer"></div>

  <script>
    // Bilingual Dictionaries (ID & EN)
    var I18N = {
      id: {
        brand_sub: "Certified Caregiver & Data Specialist",
        nav_home: "Home",
        nav_cert: "Certifications",
        nav_exp: "Experience",
        nav_trainer: "Trainer & IT",
        nav_lead: "Leadership",
        nav_edu: "Education",
        nav_proj: "Projects",
        nav_contact: "Contact",
        hero_status: "Live-in Caregiver & Remote Virtual Health Support",
        hero_title_1: "Human Touch Caregiver & ",
        hero_title_2: "Data-Driven Precision",
        hero_bio: "Saya <strong>Sabariah, S.A.B</strong>, Certified Caregiver dengan pengalaman profesional tinggal bersama pasien di Dubai dan Hong Kong. Dilengkapi sertifikasi resmi <strong>BNSP Data Analyst</strong> & <strong>BNSP Microsoft Office</strong>, saya mengintegrasikan empati pendampingan lansia holistik dengan keahlian operasional data medis, alur telehealth jarak jauh, dan dokumentasi vital sign terstruktur.",
        pill_health: "Elderly Care & CPR/AED",
        pill_lead: "Pengurus IKAUT HK (2026-2031)",
        pill_research: "Riset Ilmiah Sinta 4",
        btn_cv: "Download Official CV & Portfolio",
        btn_contact_me: "Hubungi Saya",
        tag_cert: "Akreditasi Internasional",
        title_cert: "Sertifikasi Caregiving & Medis",
        desc_cert: "Kualifikasi profesional terakreditasi Hong Kong, Britania Raya (UK), dan Amerika Serikat (US) dalam penanganan lansia dan gawat darurat medis.",
        tag_exp: "Rekam Jejak Lapangan",
        title_exp: "Timeline Pengalaman Sejak 2016",
        desc_exp: "Kombinasi pengalaman tinggal bersama pasien (Live-in Caregiver) dan dukungan virtual koordinasi medis lintas negara.",
        tag_trainer: "Kompetensi Digital & K3",
        title_trainer: "Dokumentasi Trainer, IT & BNSP",
        desc_trainer: "Sertifikasi Badan Nasional Sertifikasi Profesi (BNSP), keahlian Microsoft Office, analisis data, ISO 9001, serta keselamatan K3.",
        tag_lead: "Organisasi & Pengabdian",
        title_lead: "Kepemimpinan & Komunitas Alumni",
        desc_lead: "Peran aktif kepengurusan di IKAUT Hong Kong, inisiator pelatihan vokasi teknologi, dan pemberdayaan pekerja migran.",
        tag_edu: "Pendidikan Formal",
        title_edu: "Pendidikan Formal & Legalitas Apostille",
        desc_edu: "Sarjana Administrasi Bisnis (S.A.B) dari Universitas Terbuka dengan validasi Ijazah Apostille Kemenkumham RI untuk legalitas global.",
        tag_proj: "Karya Nyata & Riset",
        title_proj: "Proyek Teknologi Kesehatan & Publikasi",
        desc_proj: "Template pelaporan medis digital, dashboard visualisasi data analitik kesehatan, dan artikel riset terakreditasi Jurnal Sinta 4.",
        tag_contact: "Komunikasi & Konsultasi",
        title_contact: "Hubungi Sabariah, S.A.B",
        desc_contact: "Tersedia untuk wawancara caregiver keluarga, asisten virtual medis, training komputer/data, dan kolaborasi riset.",
        contact_direct: "Kontak Langsung",
        contact_direct_sub: "Silakan hubungi secara langsung atau pindai kode QR untuk membuka chat WhatsApp seketika.",
        btn_qr: "Tampilkan QR Code WhatsApp",
        form_title: "Kirim Pesan Resmi",
        form_desc: "Pesan Anda langsung tersimpan secara aman di database Google Sheet.",
        label_name: "Nama Lengkap *",
        label_cat: "Kategori Keperluan",
        label_msg: "Pesan / Rincian Kebutuhan *",
        btn_submit: "Kirim Pesan Sekarang",
        btn_verify: "Lihat Berkas Resmi",
        toast_success: "Pesan Anda telah berhasil dikirim! Terima kasih.",
        toast_required: "Mohon lengkapi Nama, Kontak (Email/WhatsApp), dan Pesan Anda."
      },
      en: {
        brand_sub: "Certified Caregiver & Data Specialist",
        nav_home: "Home",
        nav_cert: "Certifications",
        nav_exp: "Experience",
        nav_trainer: "Trainer & IT",
        nav_lead: "Leadership",
        nav_edu: "Education",
        nav_proj: "Projects",
        nav_contact: "Contact",
        hero_status: "Live-in Caregiver & Remote Virtual Health Support",
        hero_title_1: "Human Touch Caregiver & ",
        hero_title_2: "Data-Driven Precision",
        hero_bio: "I am <strong>Sabariah, S.A.B</strong>, a Certified Caregiver with extensive live-in clinical elderly care experience in Dubai and Hong Kong. Certified as a <strong>BNSP Data Analyst</strong> and <strong>BNSP Microsoft Office Specialist</strong>, I bridge compassionate bedside healthcare with systematic data operations, telehealth workflows, and precise vital signs documentation.",
        pill_health: "Elderly Care & CPR/AED",
        pill_lead: "Officer of IKAUT HK (2026-2031)",
        pill_research: "Sinta 4 Scientific Research",
        btn_cv: "Download Official CV & Portfolio",
        btn_contact_me: "Get In Touch",
        tag_cert: "International Accreditations",
        title_cert: "Caregiving & Medical Certifications",
        desc_cert: "Professional credentials accredited across Hong Kong, United Kingdom, and the United States in elderly assistance and medical emergency response.",
        tag_exp: "Career Track Record",
        title_exp: "Experience Timeline Since 2016",
        desc_exp: "Combination of high-standard live-in patient care and virtual cross-border telehealth healthcare support coordination.",
        tag_trainer: "Digital Competence & Safety",
        title_trainer: "Trainer, IT & BNSP Credentials",
        desc_trainer: "National Professional Certification Board (BNSP) credentials, Microsoft Office proficiency, data analytics, ISO 9001, and workplace fire safety.",
        tag_lead: "Service & Organizations",
        title_lead: "Leadership & Community Outreach",
        desc_lead: "Active leadership at IKAUT Hong Kong, pioneering digital vocational training, and migrant worker empowerment programs.",
        tag_edu: "Higher Education",
        title_edu: "Formal Education & Apostille Validation",
        desc_edu: "Bachelor of Business Administration (S.A.B) from Universitas Terbuka verified with official Apostille legal certification by the Ministry of Law & Human Rights.",
        tag_proj: "Applied Tools & Papers",
        title_proj: "Healthcare Tech Projects & Publications",
        desc_proj: "Digital medical reporting templates, health analytics dashboards, and published peer-reviewed research in Sinta 4 accredited journal.",
        tag_contact: "Direct Communication",
        title_contact: "Contact Sabariah, S.A.B",
        desc_contact: "Available for private family caregiver engagements, virtual medical assistant roles, computer/data training, and academic research.",
        contact_direct: "Direct Contacts",
        contact_direct_sub: "Feel free to reach out directly or scan the QR code to connect on WhatsApp immediately.",
        btn_qr: "Show WhatsApp QR Code",
        form_title: "Send Official Message",
        form_desc: "Your inquiry will be logged directly into our secure Google Sheets database.",
        label_name: "Full Name *",
        label_cat: "Inquiry Category",
        label_msg: "Message / Requirements *",
        btn_submit: "Send Message Now",
        btn_verify: "View Official Record",
        toast_success: "Your message has been sent successfully! Thank you.",
        toast_required: "Please complete Full Name, Contact info, and Message."
      }
    };

    // Full Portfolio Dataset synchronized with CV and user updates
    var MOCK_PORTFOLIO_DATA = [
      // 1. Certifications
      {
        kategori: "Certifications", subkategori: "Healthcare (HK)",
        judul: "Certificate in First Aid & CPR with AED", penerbit: "CNA (Hong Kong)", periode: "2024",
        deskripsi: "Pertolongan pertama gawat darurat, RJP/CPR, dan pemakaian AED bersertifikasi Hong Kong.",
        deskripsi_en: "Emergency first aid, CPR resuscitation, and AED operation certified by Hong Kong CNA.",
        urlTautan: "https://drive.google.com/file/d/1EiZkyv7M0ZPH2_Iw6HGG5G2o_-0N9tS1/view?usp=sharing"
      },
      {
        kategori: "Certifications", subkategori: "Healthcare (UK)",
        judul: "Assured Professional Certificate in Caregiving", penerbit: "City & Guilds (UK)", periode: "2024",
        deskripsi: "Pendampingan profesional terakreditasi Britania Raya dengan standar holistik keperawatan.",
        deskripsi_en: "Assured professional healthcare and elderly assistance accredited by City & Guilds UK.",
        urlTautan: "https://drive.google.com/file/d/1Nvz60A5ee8YZ1tTEJ-UK9E5-IVpbNMiI/view?usp=sharing"
      },
      {
        kategori: "Certifications", subkategori: "Healthcare (US)",
        judul: "National Caregiver Certificate", penerbit: "American Caregiver Association (ACA)", periode: "2024",
        deskripsi: "Standar perawatan lansia nasional AS, etika medis rumah tangga, dan keamanan fisik pasien.",
        deskripsi_en: "US national standard elderly care, domestic medical ethics, and resident patient safety.",
        urlTautan: "https://drive.google.com/drive/folders/1160N50H0FluMb3WtCechbms4oaWEh9QJ?usp=drive_link"
      },
      {
        kategori: "Certifications", subkategori: "Healthcare (US)",
        judul: "Adult First Aid, CPR & AED Certification Card", penerbit: "ASHI (US)", periode: "2024",
        deskripsi: "Sertifikasi resmi ASHI Amerika Serikat untuk penanganan henti jantung dan cedera akut.",
        deskripsi_en: "Official ASHI United States certification for adult sudden cardiac arrest and trauma response.",
        urlTautan: "https://drive.google.com/file/d/13i9nMlJk-WshDOJ4moQhoFqnYx9WGCyM/view?usp=drive_link"
      },
      {
        kategori: "Certifications", subkategori: "Healthcare (UK)",
        judul: "Certificate in Caregiving Level 2", penerbit: "TQUK (UK)", periode: "2024",
        deskripsi: "Perawatan medis harian, kepatuhan obat, pemindahan ranjang, dan pencegahan dekubitus.",
        deskripsi_en: "Regulated UK Level 2 care qualification covering daily medication, transfers, and ulcer prevention.",
        urlTautan: "https://drive.google.com/file/d/1oyCAakZ2VLD-tG0DZeowXxQU9JDTl4C3/view?usp=drive_link"
      },

      // 2. Experience
      {
        kategori: "Experience", subkategori: "Caregiver Dubai",
        judul: "Live-in Caregiver (Dubai, UAE)", penerbit: "Private Residence", periode: "2016 - 2018",
        deskripsi: "Pendampingan lansia penuh, kontrol jadwal obat harian, pengaturan nutrisi seimbang, dan koordinasi staf helpers.",
        deskripsi_en: "Full live-in elderly bedside care, strict daily medication schedules, tailored nutritional meals, and helpers management.",
        urlTautan: ""
      },
      {
        kategori: "Experience", subkategori: "Caregiver & Telehealth",
        judul: "Live-in Caregiver & Virtual Care Support (Hong Kong)", penerbit: "Family & Remote Healthcare", periode: "2025 - Present",
        deskripsi: "Perawatan lansia, pemeriksaan tensi harian, rawat luka diabetes, bantuan kursi roda, serta koordinasi konsultasi dokter telehealth.",
        deskripsi_en: "Comprehensive senior care: daily vital signs monitoring, diabetic wound dressing, wheelchair assistance, and telehealth coordination.",
        urlTautan: ""
      },
      {
        kategori: "Experience", subkategori: "Volunteering IT",
        judul: "Volunteer Assistant Teacher Computer", penerbit: "YMCA Hong Kong", periode: "2025 - Present",
        deskripsi: "Asisten pengajar pelatihan komputer praktis dan aplikasi perkantoran bagi komunitas pekerja migran.",
        deskripsi_en: "Assistant trainer for practical computer literacy and office software for community workers.",
        urlTautan: "https://drive.google.com/file/d/1u643FCDd0in2ZbN-6twvYcpRXewROH0G/view?usp=drive_link"
      },
      {
        kategori: "Experience", subkategori: "Pengajar UT",
        judul: "Trainer Komputer & Administrasi", penerbit: "Universitas Terbuka (UTLLN Hong Kong)", periode: "2024 - Present",
        deskripsi: "Instruktur pelatihan Microsoft Office dan pemrosesan basis data spreadsheet untuk mahasiswa luar negeri.",
        deskripsi_en: "Instructor for Microsoft Office and spreadsheet database workflows for overseas university students.",
        urlTautan: "https://drive.google.com/file/d/1OsrXfLN9PjqgeVBA-C1bGsF5eAvArmvA/view?usp=drive_link"
      },

      // 3. Trainer & IT
      {
        kategori: "Trainer", subkategori: "BNSP Indonesia",
        judul: "Sertifikasi BNSP Data Analyst", penerbit: "BNSP Indonesia", periode: "2024",
        deskripsi: "Standar resmi nasional pengolahan data terstruktur, visualisasi data bisnis, dan analitik analitis.",
        deskripsi_en: "National certification for data cleaning, business intelligence reporting, and analytics.",
        urlTautan: "https://drive.google.com/file/d/1ZbEUqKULJR-AaR39N9IZoBm2DVrmZhXJ/view?usp=sharing"
      },
      {
        kategori: "Trainer", subkategori: "BNSP Indonesia",
        judul: "Sertifikasi BNSP Microsoft Office", penerbit: "BNSP Indonesia", periode: "2024",
        deskripsi: "Penguasaan profesional Word, Excel, dan PowerPoint standar kompetensi nasional kerja.",
        deskripsi_en: "Nationally certified advanced competence in Microsoft Word, Excel, and PowerPoint.",
        urlTautan: "https://drive.google.com/file/d/1HTuzbpKkjTbwbM973j2Ui6aekKHsCTXa/view?usp=sharing"
      },
      {
        kategori: "Trainer", subkategori: "BNSP Indonesia",
        judul: "BNSP Data Entry Certificate", penerbit: "BNSP Indonesia", periode: "2024",
        deskripsi: "Sertifikasi pengetikan akurasi tinggi, verifikasi data berkas, dan validasi rekaman sistem.",
        deskripsi_en: "High-accuracy data encoding, records verification, and database auditing certification.",
        urlTautan: "https://drive.google.com/file/d/1ZbEUqKULJR-AaR39N9IZoBm2DVrmZhXJ/view?usp=drive_link"
      },
      {
        kategori: "Trainer", subkategori: "Sertifikasi",
        judul: "Excel Data Entry Certificate", penerbit: "LSP Indonesia", periode: "2024",
        deskripsi: "Keahlian pembuatan database spreadsheet, formula otomasi, dan tata kelola lembar kerja.",
        deskripsi_en: "Spreadsheet database structuring, lookup formulas, and tabular data automation.",
        urlTautan: "https://drive.google.com/file/d/1NbdvqbVvCmsQ4fQP4fQkY1hYQGDvZ710/view?usp=drive_link"
      },
      {
        kategori: "Trainer", subkategori: "Sertifikasi",
        judul: "Data Entry Specialist Certificate", penerbit: "LSP Mandiri", periode: "2024",
        deskripsi: "Spesialisasi manajemen arsip digital kecepatan tinggi dan verifikasi dokumen terstruktur.",
        deskripsi_en: "Fast-speed digital record management, transaction verification, and filing compliance.",
        urlTautan: "https://drive.google.com/file/d/1H00PWw93cdfNojYdurA8KJ6Bcrdawqzl/view?usp=drive_link"
      },
      {
        kategori: "Trainer", subkategori: "Quality Standard",
        judul: "ISO 9001 Quality Management Systems", penerbit: "Global Standard", periode: "2024",
        deskripsi: "Pemahaman penerapan manajemen mutu dan prosedur kerja standar operasional (SOP).",
        deskripsi_en: "Knowledge of quality management standards, audit controls, and workflow procedures.",
        urlTautan: "https://drive.google.com/file/d/1GmB7exv4iFeaZG3YdsaE3qj0QIfj-ORP/view?usp=drive_link"
      },
      {
        kategori: "Trainer", subkategori: "Safety HK",
        judul: "Fire Safety Certification – Hong Kong", penerbit: "HK Safety Authority", periode: "2024",
        deskripsi: "Prosedur keselamatan darurat kebakaran, tanggap bencana, dan penanganan sarana evakuasi.",
        deskripsi_en: "Emergency fire response, high-rise building evacuation, and fire safety compliance in HK.",
        urlTautan: "https://drive.google.com/file/d/1yjLqU_tsfvQKNDLnlDyYnk0sqJz-1Nq0/view?usp=drive_link"
      },
      {
        kategori: "Trainer", subkategori: "Komunitas",
        judul: "Certified Computer Group – YMCA", penerbit: "YMCA Hong Kong", periode: "2024",
        deskripsi: "Instruktur bersertifikat dalam bimbingan komputer bagi komunitas sosial luar negeri.",
        deskripsi_en: "Certified computer instruction facilitator for overseas community programs.",
        urlTautan: "https://drive.google.com/file/d/1CCVL6eKoJsKMoB-Wei8dcNWu0HI3bvbq/view?usp=drive_link"
      },

      // 4. Leadership (Updated per user instruction)
      {
        kategori: "Leadership", subkategori: "Organisasi Alumni",
        judul: "Pengurus Bidang IKAUT HK", penerbit: "Ikatan Alumni UT Hong Kong", periode: "2026 - 2031",
        deskripsi: "Mengkoordinasikan pelatihan komputer vokasi, kegiatan sosial PMI, dan publikasi karya alumni dalam masa kepengurusan 2026 - 2031.",
        deskripsi_en: "Coordinating alumni vocational IT workshops, community social outreach, and research publications for the 2026 - 2031 period.",
        urlTautan: "https://drive.google.com/drive/folders/1zHJEi-SPmR5aiyy5ORpugAngWXUkdfpo?usp=drive_link"
      },
      {
        kategori: "Leadership", subkategori: "Volunteering YMCA",
        judul: "Volunteer Assistant Teacher di YMCA Hong Kong", penerbit: "YMCA Hong Kong", periode: "2025 - Present",
        deskripsi: "Asisten pengajar sukarela dalam pembinaan literasi teknologi komputer, aplikasi bisnis, dan pendampingan pekerja migran.",
        deskripsi_en: "Volunteer assistant teacher mentoring community workers in applied computer literacy and digital tools.",
        urlTautan: "https://drive.google.com/drive/folders/194GLEHT8K5H4SOqa_Ov7OpGtgasaxaHG?usp=drive_link"
      },

      // 5. Education
      {
        kategori: "Education", subkategori: "Strata 1 (S1)",
        judul: "S1 Administrasi Bisnis (S.A.B)", penerbit: "Universitas Terbuka (UTLLN HK)", periode: "Lulus Resmi",
        deskripsi: "Tata kelola bisnis, sistem informasi, dan legalitas resmi Ijazah Apostille Kemenkumham RI.",
        deskripsi_en: "Business administration degree officially validated with Apostille legal certification by Kemenkumham RI.",
        urlTautan: "https://drive.google.com/drive/folders/160pS-gFkXw-DB6O9idJPxzotZp1ypKH2?usp=drive_link"
      },

      // 6. Projects & Publications
      {
        kategori: "Projects", subkategori: "Volunteer Analytics",
        judul: "Volunteer Experience Dashboard", penerbit: "Sabariah Analytics", periode: "2025",
        deskripsi: "Dashboard visual interaktif untuk pelacakan performa kegiatan relawan dan rekapitulasi pelatihan literasi digital masyarakat.",
        deskripsi_en: "Interactive visual analytics dashboard tracking community volunteer initiatives and computer training progress.",
        urlTautan: "https://drive.google.com/file/d/1sl_8PftUCCABUiPEYMF453Vbz4JAiD9O/view?usp=sharing"
      },
      {
        kategori: "Projects", subkategori: "Healthcare System",
        judul: "Dashboard Elderly Care", penerbit: "Sabariah Healthcare Analytics", periode: "2025",
        deskripsi: "Sistem dashboard cerdas untuk pemantauan parameter tanda vital lansia, jadwal obat harian, dan evaluasi kondisi pasien.",
        deskripsi_en: "Smart healthcare dashboard monitoring senior patient vitals, medication adherence, and daily clinical metrics.",
        urlTautan: "https://drive.google.com/file/d/1NhgC-8sxfwBl4Za6cJ9ZYcFJw3CPeAlN/view?usp=sharing"
      },
      {
        kategori: "Projects", subkategori: "Healthcare Tool",
        judul: "Caregiving Report Templates", penerbit: "Sabariah Project", periode: "2024",
        deskripsi: "Standar pelaporan tanda vital harian, jadwal obat pasien, dan status luka diabetes.",
        deskripsi_en: "Standard digital reporting for daily vitals, patient medication logs, and diabetic wound progression.",
        urlTautan: "https://drive.google.com/file/d/1jxfGAUKXnccdu8ePX0Q5l2hVZmZ3iut_/view?usp=sharing"
      },
      {
        kategori: "Projects", subkategori: "Visual Analytics",
        judul: "Health Data Dashboard (Excel & Power BI)", penerbit: "Sabariah Analytics", periode: "2024",
        deskripsi: "Visualisasi analitik tekanan darah harian, kadar glukosa, dan rekam medis digital pasien.",
        deskripsi_en: "Interactive visual dashboards tracking daily blood pressure trends, glucose, and patient vitals.",
        urlTautan: "https://drive.google.com/file/d/1T7BL4JIPKBieea1tOhkgMN1KPEkcF8yH/view?usp=drive_link"
      },
      {
        kategori: "Projects", subkategori: "Web Platform",
        judul: "Website Resmi IKA – UTLLN Hong Kong", penerbit: "IKAUT HK", periode: "2024",
        deskripsi: "Portal komunikasi terpadu dan informasi mahasiswa & alumni Universitas Terbuka Hong Kong.",
        deskripsi_en: "Integrated communication portal and community hub for university alumni in Hong Kong.",
        urlTautan: "https://ikauthk.srh.ai.id/"
      },
      {
        kategori: "Publications", subkategori: "Jurnal Sinta 4",
        judul: "Strategi Perkembangan Pemasaran Produk Digital Online Courses Pada PT. Esas Edukasi Indonesia (2023/2024)", penerbit: "Jurnal Ekonomi dan Riset", periode: "2025",
        deskripsi: "Riset ilmiah terakreditasi nasional Sinta 4 mengenai penetrasi pasar digital dan edukasi online.",
        deskripsi_en: "Sinta 4 national peer-reviewed paper analyzing market penetration strategies for online education.",
        urlTautan: "https://penerbitadm.pubmedia.id/index.php/JER/article/view/2630"
      }
    ];

    var appState = {
      lang: 'id',
      currentView: 'home',
      portfolioCache: MOCK_PORTFOLIO_DATA
    };

    // Auto-detect Language
    function initLanguage() {
      var navLang = (navigator.language || navigator.userLanguage || 'id').toLowerCase();
      if (navLang.indexOf('en') === 0) {
        appState.lang = 'en';
      } else {
        appState.lang = 'id';
      }
      applyLanguage(appState.lang);
    }

    function toggleLanguage() {
      appState.lang = (appState.lang === 'id' ? 'en' : 'id');
      applyLanguage(appState.lang);
    }

    function applyLanguage(lang) {
      var btnId = document.getElementById('langBtnId');
      var btnEn = document.getElementById('langBtnEn');
      if (lang === 'id') {
        btnId.classList.add('active');
        btnEn.classList.remove('active');
      } else {
        btnEn.classList.add('active');
        btnId.classList.remove('active');
      }

      // Update static text elements
      var elements = document.querySelectorAll('[data-i18n]');
      for (var i = 0; i < elements.length; i++) {
        var el = elements[i];
        var key = el.getAttribute('data-i18n');
        if (I18N[lang] && I18N[lang][key]) {
          el.innerHTML = I18N[lang][key];
        }
      }

      // Re-populate Dynamic Cards
      populateModules(appState.portfolioCache);
    }

    // View Switching
    function switchView(viewName) {
      appState.currentView = viewName;
      
      var navItems = document.querySelectorAll('.nav-item');
      for (var i = 0; i < navItems.length; i++) {
        var item = navItems[i];
        if (item.getAttribute('data-view') === viewName) {
          item.classList.add('active');
        } else {
          item.classList.remove('active');
        }
      }

      var bottomTabs = document.querySelectorAll('.bottom-tab');
      for (var b = 0; b < bottomTabs.length; b++) {
        var bTab = bottomTabs[b];
        if (bTab.getAttribute('data-view') === viewName) {
          bTab.classList.add('active');
        } else {
          bTab.classList.remove('active');
        }
      }

      var viewContents = document.querySelectorAll('.view-content');
      for (var v = 0; v < viewContents.length; v++) {
        viewContents[v].classList.remove('active');
      }
      
      var targetView = document.getElementById('view-' + viewName);
      if (targetView) {
        targetView.classList.add('active');
      }

      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function toggleMobileDrawer() {
      var drawer = document.getElementById('mobileDrawer');
      if (drawer.classList.contains('open')) {
        drawer.classList.remove('open');
      } else {
        drawer.classList.add('open');
      }
    }

    // Render Card Item (Pure string concatenation)
    function renderCardItem(item) {
      var isEn = (appState.lang === 'en');
      var desc = (isEn && item.deskripsi_en) ? item.deskripsi_en : item.deskripsi;
      var verifyText = I18N[appState.lang].btn_verify;

      var html = '';
      html += '<div class="pro-card">';
      html += '  <div class="card-badge">' + (item.subkategori || item.kategori) + '</div>';
      html += '  <h3 class="card-title">' + item.judul + '</h3>';
      html += '  <p class="card-issuer">' + item.penerbit + ' &bull; ' + item.periode + '</p>';
      html += '  <p class="card-desc">' + desc + '</p>';
      
      html += '  <div class="card-footer">';
      if (item.urlTautan && item.urlTautan.trim() !== '') {
        html += '    <a href="' + item.urlTautan + '" target="_blank" rel="noopener noreferrer" class="btn btn-outline" style="padding: 6px 12px; font-size: 0.76rem;">';
        html += '      ' + verifyText;
        html += '      <svg viewBox="0 0 24 24"><path d="M19 19H5V5h7V3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z"/></svg>';
        html += '    </a>';
      } else {
        html += '    <span style="font-size:0.75rem; color:var(--text-muted); font-weight:600;">Verified Accreditation</span>';
      }
      html += '  </div>';
      html += '</div>';
      return html;
    }

    // Render Timeline
    function renderTimeline(items) {
      var container = document.getElementById('timeline-container');
      if (!container) return;
      var isEn = (appState.lang === 'en');
      var html = '';

      for (var i = 0; i < items.length; i++) {
        var itm = items[i];
        var desc = (isEn && itm.deskripsi_en) ? itm.deskripsi_en : itm.deskripsi;
        
        html += '<div class="timeline-item">';
        html += '  <div class="timeline-dot"></div>';
        html += '  <div class="pro-card" style="padding: 16px 18px;">';
        html += '    <div class="timeline-header">';
        html += '      <h3 style="font-size:1.02rem; color:var(--text-main); font-weight:700;">' + itm.judul + '</h3>';
        html += '      <span class="timeline-period">' + itm.periode + '</span>';
        html += '    </div>';
        html += '    <p style="font-size:0.8rem; color:var(--blue-primary); font-weight:700; margin-bottom:6px;">' + itm.penerbit + '</p>';
        html += '    <p style="font-size:0.84rem; color:#475569; line-height:1.55;">' + desc + '</p>';
        
        if (itm.urlTautan && itm.urlTautan !== '') {
          html += '    <div style="margin-top:10px;">';
          html += '      <a href="' + itm.urlTautan + '" target="_blank" class="btn btn-outline" style="padding:5px 10px; font-size:0.74rem;">';
          html += '        Dokumentasi / Record';
          html += '      </a>';
          html += '    </div>';
        }
        html += '  </div>';
        html += '</div>';
      }
      container.innerHTML = html;
    }

    // Populate SPA Modules
    function populateModules(dataList) {
      var certHtml = '';
      var trainerHtml = '';
      var leaderHtml = '';
      var eduHtml = '';
      var projHtml = '';
      var timelineItems = [];

      for (var i = 0; i < dataList.length; i++) {
        var row = dataList[i];
        var cat = (row.kategori || '').toLowerCase();

        if (cat === 'certifications') {
          certHtml += renderCardItem(row);
        } else if (cat === 'experience') {
          timelineItems.push(row);
        } else if (cat === 'trainer') {
          trainerHtml += renderCardItem(row);
        } else if (cat === 'leadership') {
          leaderHtml += renderCardItem(row);
        } else if (cat === 'education') {
          eduHtml += renderCardItem(row);
        } else if (cat === 'projects' || cat === 'publications') {
          projHtml += renderCardItem(row);
        }
      }

      var elCert = document.getElementById('cert-grid-container');
      if (elCert) elCert.innerHTML = certHtml;

      var elTrainer = document.getElementById('trainer-grid-container');
      if (elTrainer) elTrainer.innerHTML = trainerHtml;

      var elLeader = document.getElementById('leadership-grid-container');
      if (elLeader) elLeader.innerHTML = leaderHtml;

      var elEdu = document.getElementById('education-grid-container');
      if (elEdu) elEdu.innerHTML = eduHtml;

      var elProj = document.getElementById('projects-grid-container');
      if (elProj) elProj.innerHTML = projHtml;

      renderTimeline(timelineItems);
    }

    // Toast Alert
    function showToast(message, isError) {
      var container = document.getElementById('toastContainer');
      var toast = document.createElement('div');
      toast.className = 'toast';
      if (isError) {
        toast.style.borderLeftColor = '#ef4444';
      }
      
      var iconHtml = isError
        ? '<svg style="width:18px;height:18px;fill:#ef4444;" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-2h2v2zm0-4h-2V7h2v6z"/></svg>'
        : '<svg style="width:18px;height:18px;fill:#2563eb;" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/></svg>';
      
      toast.innerHTML = iconHtml + '<span>' + message + '</span>';
      container.appendChild(toast);

      setTimeout(function() { toast.classList.add('show'); }, 50);
      setTimeout(function() {
        toast.classList.remove('show');
        setTimeout(function() {
          if (toast.parentNode) toast.parentNode.removeChild(toast);
        }, 300);
      }, 4000);
    }

    // Submit Form
    function submitContactForm() {
      var namaVal = document.getElementById('formNama').value;
      var emailVal = document.getElementById('formEmail').value;
      var waVal = document.getElementById('formWhatsapp').value;
      var katVal = document.getElementById('formKategori').value;
      var pesanVal = document.getElementById('formPesan').value;

      var payload = {
        nama: String(namaVal || '').trim(),
        email: String(emailVal || '').trim(),
        whatsapp: String(waVal || '').trim(),
        kategori: String(katVal || '').trim(),
        pesan: String(pesanVal || '').trim()
      };

      if (!payload.nama || (!payload.email && !payload.whatsapp) || !payload.pesan) {
        showToast(I18N[appState.lang].toast_required, true);
        return;
      }

      showToast(I18N[appState.lang].toast_success, false);
      document.getElementById('contactForm').reset();

      if (typeof google !== 'undefined' && google.script && google.script.run) {
        google.script.run
          .withSuccessHandler(function(res) {
            if (res && !res.success) showToast(res.message, true);
          })
          .withFailureHandler(function(err) {
            showToast('Sync delay: ' + err.toString(), true);
          })
          .submitContactMessage(payload);
      }
    }

    // Modal QR Code
    function openQrModal(type) {
      var modal = document.getElementById('qrModal');
      var container = document.getElementById('modalContentInner');
      var html = '';

      html += '<h3 style="color:var(--text-main); font-size:1.15rem; font-weight:800; margin-bottom:6px;">WhatsApp Sabariah</h3>';
      html += '<p style="font-size:0.8rem; color:var(--text-muted); margin-bottom:14px;">+62 852-0208-8185 &bull; Direct Consultation</p>';
      html += '<div style="background:#f8fafc; padding:14px; border-radius:10px; display:inline-block; border:1px solid var(--border-subtle); margin-bottom:16px;">';
      html += '  <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=https://wa.me/6285202088185" alt="QR WhatsApp" style="display:block;">';
      html += '</div>';
      html += '<div>';
      html += '  <a href="https://wa.me/6285202088185" target="_blank" class="btn btn-primary" style="width:100%;">Buka WhatsApp / Open Chat</a>';
      html += '</div>';

      container.innerHTML = html;
      modal.classList.add('open');
    }

    function closeQrModal(e) {
      var modal = document.getElementById('qrModal');
      modal.classList.remove('open');
    }

    document.addEventListener('DOMContentLoaded', function() {
      initLanguage();

      // Load data from Apps Script backend if available
      if (typeof google !== 'undefined' && google.script && google.script.run) {
        google.script.run
          .withSuccessHandler(function(res) {
            if (res && res.items && res.items.length > 0) {
              appState.portfolioCache = res.items;
              populateModules(res.items);
            }
          })
          .getPortfolioDataPaginated('ALL', 1, 50);
      }
    });
  </script>
</body>
</html>
