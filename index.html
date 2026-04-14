
// ============================================================
// NEXUS STORE — Full E-Commerce Catalog
// Firebase + WhatsApp + Multi-Language + RBAC Admin Dashboard
// ============================================================

import { useState, useEffect, useRef, useCallback, createContext, useContext } from "react";

// ─────────────────────────────────────────────
// FIREBASE CONFIG — Replace with your own
// ─────────────────────────────────────────────
const FIREBASE_CONFIG = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
};

// ─────────────────────────────────────────────
// TRANSLATIONS
// ─────────────────────────────────────────────
const TRANSLATIONS = {
  en: {
    dir: "ltr",
    storeName: "NEXUS STORE",
    tagline: "Premium Products, Delivered Instantly",
    allProducts: "All Products",
    inStock: "In Stock",
    lowStock: "Low Stock",
    outOfStock: "Out of Stock",
    orderWhatsApp: "Order via WhatsApp",
    discount: "OFF",
    noProducts: "No products found.",
    adminPanel: "Admin Panel",
    dashboard: "Dashboard",
    products: "Products",
    stock: "Stock",
    addProduct: "Add Product",
    categories: "Categories",
    settings: "Settings",
    logout: "Logout",
    login: "Login",
    email: "Email",
    password: "Password",
    loginBtn: "Sign In",
    name: "Name",
    description: "Description",
    price: "Price",
    category: "Category",
    productCode: "Product Code",
    images: "Images",
    visibility: "Visibility",
    discountActive: "Discount Active",
    discountPct: "Discount %",
    save: "Save",
    cancel: "Cancel",
    delete: "Delete",
    addNew: "Add New",
    stockStatus: "Stock Status",
    available: "Available",
    unavailable: "Unavailable",
    whatsappNumber: "WhatsApp Number",
    whatsappTemplate: "WhatsApp Message Template",
    bannerText: "Banner Text",
    uploading: "Uploading...",
    uploadImage: "Upload Image",
    confirmDelete: "Are you sure you want to delete this?",
    accessDenied: "Access Denied",
    roleLabel: "Role",
    visible: "Visible",
    hidden: "Hidden",
    oldPrice: "Old Price",
    newPrice: "New Price",
    search: "Search products...",
    filterCategory: "Filter by Category",
    closePanel: "Close",
    gallery: "Gallery",
    stockPage: "Stock Overview",
    productPage: "Products Manager",
    addPage: "Add / Delete Products",
    catPage: "Category Manager",
    settingsPage: "Store Settings",
    addCategory: "Add Category",
    categoryName: "Category Name",
    noCategories: "No categories yet",
    storeLogo: "Store Logo URL",
    heroBanner: "Hero Banner URL",
    saveSettings: "Save Settings",
    whatsappMsg: "Hi, I want to order:\nProduct: {name}\nCode: {code}\nPrice: {price}",
  },
  ar: {
    dir: "rtl",
    storeName: "نيكسوس ستور",
    tagline: "منتجات مميزة، تُسلَّم فورًا",
    allProducts: "جميع المنتجات",
    inStock: "متوفر",
    lowStock: "كمية محدودة",
    outOfStock: "نفذ المخزون",
    orderWhatsApp: "اطلب عبر واتساب",
    discount: "خصم",
    noProducts: "لا توجد منتجات.",
    adminPanel: "لوحة الإدارة",
    dashboard: "الرئيسية",
    products: "المنتجات",
    stock: "المخزون",
    addProduct: "إضافة منتج",
    categories: "الفئات",
    settings: "الإعدادات",
    logout: "تسجيل الخروج",
    login: "تسجيل الدخول",
    email: "البريد الإلكتروني",
    password: "كلمة المرور",
    loginBtn: "دخول",
    name: "الاسم",
    description: "الوصف",
    price: "السعر",
    category: "الفئة",
    productCode: "رمز المنتج",
    images: "الصور",
    visibility: "الظهور",
    discountActive: "تفعيل الخصم",
    discountPct: "نسبة الخصم %",
    save: "حفظ",
    cancel: "إلغاء",
    delete: "حذف",
    addNew: "إضافة جديد",
    stockStatus: "حالة المخزون",
    available: "متوفر",
    unavailable: "غير متوفر",
    whatsappNumber: "رقم واتساب",
    whatsappTemplate: "قالب رسالة واتساب",
    bannerText: "نص البانر",
    uploading: "جارٍ الرفع...",
    uploadImage: "رفع صورة",
    confirmDelete: "هل أنت متأكد من الحذف؟",
    accessDenied: "وصول مرفوض",
    roleLabel: "الدور",
    visible: "ظاهر",
    hidden: "مخفي",
    oldPrice: "السعر الأصلي",
    newPrice: "السعر الجديد",
    search: "ابحث عن منتج...",
    filterCategory: "تصفية حسب الفئة",
    closePanel: "إغلاق",
    gallery: "معرض الصور",
    stockPage: "نظرة عامة على المخزون",
    productPage: "إدارة المنتجات",
    addPage: "إضافة / حذف المنتجات",
    catPage: "إدارة الفئات",
    settingsPage: "إعدادات المتجر",
    addCategory: "إضافة فئة",
    categoryName: "اسم الفئة",
    noCategories: "لا توجد فئات بعد",
    storeLogo: "رابط شعار المتجر",
    heroBanner: "رابط البانر الرئيسي",
    saveSettings: "حفظ الإعدادات",
    whatsappMsg: "مرحباً، أريد الطلب:\nالمنتج: {name}\nالرمز: {code}\nالسعر: {price}",
  },
  fr: {
    dir: "ltr",
    storeName: "NEXUS BOUTIQUE",
    tagline: "Produits Premium, Livrés Instantanément",
    allProducts: "Tous les produits",
    inStock: "En stock",
    lowStock: "Stock limité",
    outOfStock: "Rupture de stock",
    orderWhatsApp: "Commander via WhatsApp",
    discount: "REMISE",
    noProducts: "Aucun produit trouvé.",
    adminPanel: "Panneau Admin",
    dashboard: "Tableau de bord",
    products: "Produits",
    stock: "Stock",
    addProduct: "Ajouter",
    categories: "Catégories",
    settings: "Paramètres",
    logout: "Déconnexion",
    login: "Connexion",
    email: "Email",
    password: "Mot de passe",
    loginBtn: "Se connecter",
    name: "Nom",
    description: "Description",
    price: "Prix",
    category: "Catégorie",
    productCode: "Code produit",
    images: "Images",
    visibility: "Visibilité",
    discountActive: "Remise active",
    discountPct: "% de remise",
    save: "Enregistrer",
    cancel: "Annuler",
    delete: "Supprimer",
    addNew: "Ajouter",
    stockStatus: "État du stock",
    available: "Disponible",
    unavailable: "Indisponible",
    whatsappNumber: "Numéro WhatsApp",
    whatsappTemplate: "Modèle de message WhatsApp",
    bannerText: "Texte de la bannière",
    uploading: "Téléchargement...",
    uploadImage: "Télécharger une image",
    confirmDelete: "Êtes-vous sûr de vouloir supprimer ceci ?",
    accessDenied: "Accès refusé",
    roleLabel: "Rôle",
    visible: "Visible",
    hidden: "Masqué",
    oldPrice: "Ancien prix",
    newPrice: "Nouveau prix",
    search: "Rechercher des produits...",
    filterCategory: "Filtrer par catégorie",
    closePanel: "Fermer",
    gallery: "Galerie",
    stockPage: "Aperçu du stock",
    productPage: "Gestionnaire de produits",
    addPage: "Ajouter / Supprimer des produits",
    catPage: "Gestionnaire de catégories",
    settingsPage: "Paramètres du magasin",
    addCategory: "Ajouter une catégorie",
    categoryName: "Nom de la catégorie",
    noCategories: "Aucune catégorie pour l'instant",
    storeLogo: "URL du logo",
    heroBanner: "URL de la bannière",
    saveSettings: "Enregistrer les paramètres",
    whatsappMsg: "Bonjour, je veux commander:\nProduit: {name}\nCode: {code}\nPrix: {price}",
  },
};

// ─────────────────────────────────────────────
// MOCK DATA (Replaces Firebase when not configured)
// ─────────────────────────────────────────────
const MOCK_PRODUCTS = [
  {
    id: "p1", name: "Wireless Earbuds Pro", description: "Premium sound quality with active noise cancellation. 30-hour battery life.", price: 89.99, old_price: 129.99, discount_active: true, discount_percentage: 30,
    images: ["https://images.unsplash.com/photo-1590658268037-6bf12165a8df?w=600&q=80", "https://images.unsplash.com/photo-1606220945770-b5b6c2c55bf1?w=600&q=80"],
    stock: 45, status: "in_stock", category: "Electronics", product_code: "EAR-PRO-001", visibility: true,
  },
  {
    id: "p2", name: "Mechanical Keyboard", description: "RGB backlit mechanical keyboard with tactile switches. Perfect for gaming and typing.", price: 149.99, old_price: null, discount_active: false, discount_percentage: 0,
    images: ["https://images.unsplash.com/photo-1595044426077-d36d9236d44a?w=600&q=80"],
    stock: 3, status: "low_stock", category: "Electronics", product_code: "KB-MECH-002", visibility: true,
  },
  {
    id: "p3", name: "Minimalist Watch", description: "Slim profile, sapphire crystal glass, 5ATM water resistance.", price: 299.99, old_price: 399.99, discount_active: true, discount_percentage: 25,
    images: ["https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=600&q=80", "https://images.unsplash.com/photo-1508685096489-7aacd43bd3b1?w=600&q=80"],
    stock: 0, status: "out_of_stock", category: "Accessories", product_code: "WCH-MIN-003", visibility: true,
  },
  {
    id: "p4", name: "Leather Wallet", description: "Genuine full-grain leather bifold wallet with RFID blocking.", price: 49.99, old_price: null, discount_active: false, discount_percentage: 0,
    images: ["https://images.unsplash.com/photo-1627123424574-724758594e93?w=600&q=80"],
    stock: 100, status: "in_stock", category: "Accessories", product_code: "WLT-LTH-004", visibility: true,
  },
  {
    id: "p5", name: "Ceramic Pour-Over Set", description: "Handcrafted ceramic pour-over coffee dripper with matching mug.", price: 64.99, old_price: 79.99, discount_active: true, discount_percentage: 18,
    images: ["https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=600&q=80"],
    stock: 28, status: "in_stock", category: "Home", product_code: "COF-CER-005", visibility: true,
  },
  {
    id: "p6", name: "Smart Desk Lamp", description: "Adaptive brightness, circadian rhythm settings, wireless charging base.", price: 79.99, old_price: null, discount_active: false, discount_percentage: 0,
    images: ["https://images.unsplash.com/photo-1507473885765-e6ed057f782c?w=600&q=80"],
    stock: 15, status: "in_stock", category: "Home", product_code: "LMP-SMT-006", visibility: true,
  },
];

const MOCK_SETTINGS = {
  whatsapp_number: "1234567890",
  whatsapp_template: "Hi, I want to order:\nProduct: {name}\nCode: {code}\nPrice: {price}",
  store_name: "NEXUS STORE",
  banner_text: "Premium Products, Delivered Instantly",
  logo_url: "",
  banner_url: "https://images.unsplash.com/photo-1441986300917-64674bd600d8?w=1600&q=80",
};

const MOCK_CATEGORIES = ["Electronics", "Accessories", "Home", "Clothing", "Sports"];

// ─────────────────────────────────────────────
// CONTEXT
// ─────────────────────────────────────────────
const AppContext = createContext(null);
const useApp = () => useContext(AppContext);

// ─────────────────────────────────────────────
// UTILITIES
// ─────────────────────────────────────────────
const calcDiscountedPrice = (price, pct) => +(price * (1 - pct / 100)).toFixed(2);
const stockColor = (status) =>
  status === "in_stock" ? "#22c55e" : status === "low_stock" ? "#f59e0b" : "#ef4444";
const stockLabel = (status, t) =>
  status === "in_stock" ? t.inStock : status === "low_stock" ? t.lowStock : t.outOfStock;
const generateId = () => Math.random().toString(36).substr(2, 9);
const buildWhatsAppUrl = (product, settings, t) => {
  const price = product.discount_active
    ? calcDiscountedPrice(product.price, product.discount_percentage)
    : product.price;
  const msg = (settings.whatsapp_template || t.whatsappMsg)
    .replace("{name}", product.name)
    .replace("{code}", product.product_code)
    .replace("{price}", `$${price}`);
  return `https://wa.me/${settings.whatsapp_number}?text=${encodeURIComponent(msg)}`;
};

// ─────────────────────────────────────────────
// GLOBAL STYLES
// ─────────────────────────────────────────────
const GlobalStyles = () => (
  <style>{`
    @import url('https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap');

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #080c14;
      --bg2: #0d1320;
      --bg3: #111827;
      --surface: rgba(255,255,255,0.04);
      --surface-hover: rgba(255,255,255,0.07);
      --border: rgba(255,255,255,0.08);
      --border-hover: rgba(255,255,255,0.18);
      --accent: #6ee7b7;
      --accent2: #3b82f6;
      --accent-dim: rgba(110,231,183,0.15);
      --text: #f1f5f9;
      --text2: #94a3b8;
      --text3: #475569;
      --red: #ef4444;
      --yellow: #f59e0b;
      --green: #22c55e;
      --radius: 14px;
      --radius-sm: 8px;
      --shadow: 0 8px 32px rgba(0,0,0,0.4);
      --font-display: 'Syne', sans-serif;
      --font-body: 'DM Sans', sans-serif;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--font-body);
      font-size: 15px;
      line-height: 1.6;
      min-height: 100vh;
      overflow-x: hidden;
    }

    #root { min-height: 100vh; }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 5px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: var(--border-hover); border-radius: 99px; }

    /* Animations */
    @keyframes fadeIn { from { opacity: 0; transform: translateY(12px); } to { opacity: 1; transform: translateY(0); } }
    @keyframes slideInRight { from { opacity: 0; transform: translateX(60px); } to { opacity: 1; transform: translateX(0); } }
    @keyframes slideInLeft { from { opacity: 0; transform: translateX(-60px); } to { opacity: 1; transform: translateX(0); } }
    @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.5; } }
    @keyframes shimmer { 0% { background-position: -200% 0; } 100% { background-position: 200% 0; } }
    @keyframes spin { to { transform: rotate(360deg); } }
    @keyframes scaleIn { from { opacity: 0; transform: scale(0.96); } to { opacity: 1; transform: scale(1); } }

    .fade-in { animation: fadeIn 0.4s ease both; }
    .slide-right { animation: slideInRight 0.35s ease both; }
    .scale-in { animation: scaleIn 0.3s ease both; }

    /* Glass card */
    .glass {
      background: var(--surface);
      border: 1px solid var(--border);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
    }

    /* Buttons */
    .btn {
      display: inline-flex; align-items: center; gap: 8px;
      padding: 10px 20px; border-radius: var(--radius-sm);
      border: none; cursor: pointer; font-family: var(--font-body);
      font-size: 14px; font-weight: 500; transition: all 0.2s;
      text-decoration: none; white-space: nowrap;
    }
    .btn-primary {
      background: var(--accent); color: #0a1a12;
      font-weight: 700;
    }
    .btn-primary:hover { background: #a7f3d0; transform: translateY(-1px); }
    .btn-ghost {
      background: var(--surface); color: var(--text);
      border: 1px solid var(--border);
    }
    .btn-ghost:hover { background: var(--surface-hover); border-color: var(--border-hover); }
    .btn-danger {
      background: rgba(239,68,68,0.15); color: var(--red);
      border: 1px solid rgba(239,68,68,0.3);
    }
    .btn-danger:hover { background: rgba(239,68,68,0.25); }
    .btn-whatsapp {
      background: #25d366; color: #fff;
      font-weight: 700; font-size: 15px; padding: 14px 24px;
      border-radius: var(--radius); width: 100%;
      justify-content: center;
    }
    .btn-whatsapp:hover { background: #1fa855; transform: translateY(-2px); box-shadow: 0 8px 24px rgba(37,211,102,0.3); }
    .btn-sm { padding: 7px 14px; font-size: 13px; }
    .btn:disabled { opacity: 0.5; cursor: not-allowed; }

    /* Form inputs */
    .input, .textarea, .select {
      width: 100%; padding: 10px 14px;
      background: rgba(255,255,255,0.05);
      border: 1px solid var(--border);
      border-radius: var(--radius-sm);
      color: var(--text); font-family: var(--font-body);
      font-size: 14px; transition: border 0.2s;
      outline: none;
    }
    .input:focus, .textarea:focus, .select:focus { border-color: var(--accent); }
    .textarea { resize: vertical; min-height: 80px; }
    .select option { background: #1e293b; }

    .field { display: flex; flex-direction: column; gap: 6px; }
    .field label { font-size: 13px; color: var(--text2); font-weight: 500; }

    /* Toggle */
    .toggle {
      position: relative; display: inline-block;
      width: 44px; height: 24px;
    }
    .toggle input { opacity: 0; width: 0; height: 0; }
    .toggle-slider {
      position: absolute; inset: 0;
      background: var(--bg3); border-radius: 99px;
      cursor: pointer; transition: 0.2s;
      border: 1px solid var(--border);
    }
    .toggle-slider::before {
      content: ''; position: absolute;
      width: 18px; height: 18px; left: 2px; top: 2px;
      background: var(--text2); border-radius: 50%;
      transition: 0.2s;
    }
    .toggle input:checked + .toggle-slider { background: var(--accent); border-color: var(--accent); }
    .toggle input:checked + .toggle-slider::before { transform: translateX(20px); background: #0a1a12; }

    /* Tags */
    .tag {
      display: inline-flex; align-items: center; gap: 4px;
      padding: 3px 10px; border-radius: 99px;
      font-size: 12px; font-weight: 600;
    }
    .tag-green { background: rgba(34,197,94,0.15); color: var(--green); border: 1px solid rgba(34,197,94,0.2); }
    .tag-yellow { background: rgba(245,158,11,0.15); color: var(--yellow); border: 1px solid rgba(245,158,11,0.2); }
    .tag-red { background: rgba(239,68,68,0.15); color: var(--red); border: 1px solid rgba(239,68,68,0.2); }
    .tag-blue { background: rgba(59,130,246,0.15); color: var(--accent2); border: 1px solid rgba(59,130,246,0.2); }

    /* Grid */
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 20px;
    }

    /* Product card */
    .product-card {
      border-radius: var(--radius);
      overflow: hidden;
      cursor: pointer;
      transition: transform 0.25s, border-color 0.25s, box-shadow 0.25s;
      border: 1px solid var(--border);
      background: var(--bg2);
      position: relative;
    }
    .product-card:hover {
      transform: translateY(-6px);
      border-color: var(--border-hover);
      box-shadow: 0 20px 60px rgba(0,0,0,0.5);
    }
    .product-card-img {
      width: 100%; aspect-ratio: 4/3;
      object-fit: cover;
      display: block;
      transition: transform 0.4s;
    }
    .product-card:hover .product-card-img { transform: scale(1.04); }
    .product-card-img-wrap { overflow: hidden; position: relative; }
    .discount-badge {
      position: absolute; top: 10px; left: 10px;
      background: var(--red); color: #fff;
      font-size: 11px; font-weight: 800;
      padding: 3px 9px; border-radius: 99px;
      font-family: var(--font-display);
      letter-spacing: 0.5px;
    }
    .product-card-body { padding: 16px; }
    .product-card-name {
      font-family: var(--font-display);
      font-weight: 700; font-size: 15px;
      margin-bottom: 4px;
      white-space: nowrap; overflow: hidden; text-overflow: ellipsis;
    }
    .product-card-price { display: flex; align-items: center; gap: 8px; margin-top: 8px; }
    .price-current { font-family: var(--font-display); font-weight: 700; font-size: 18px; color: var(--accent); }
    .price-old { font-size: 13px; color: var(--text3); text-decoration: line-through; }

    /* Drawer */
    .drawer-overlay {
      position: fixed; inset: 0; z-index: 200;
      background: rgba(0,0,0,0.7);
      backdrop-filter: blur(8px);
    }
    .drawer {
      position: fixed; top: 0; right: 0; bottom: 0;
      width: min(520px, 100vw); z-index: 201;
      background: var(--bg2);
      border-left: 1px solid var(--border);
      overflow-y: auto;
      display: flex; flex-direction: column;
    }
    .drawer-rtl { right: auto; left: 0; border-left: none; border-right: 1px solid var(--border); }

    /* Admin sidebar */
    .admin-layout {
      display: flex; min-height: 100vh;
    }
    .admin-sidebar {
      width: 240px; min-height: 100vh;
      background: var(--bg2);
      border-right: 1px solid var(--border);
      display: flex; flex-direction: column;
      padding: 24px 0; position: sticky; top: 0; height: 100vh;
      overflow-y: auto;
      flex-shrink: 0;
    }
    .admin-sidebar-rtl { border-right: none; border-left: 1px solid var(--border); }
    .admin-main { flex: 1; padding: 32px; overflow-x: hidden; }
    .sidebar-logo {
      font-family: var(--font-display);
      font-weight: 800; font-size: 18px;
      padding: 0 20px 24px;
      border-bottom: 1px solid var(--border);
      margin-bottom: 16px;
      color: var(--accent);
    }
    .sidebar-nav-item {
      display: flex; align-items: center; gap: 10px;
      padding: 10px 20px; color: var(--text2);
      cursor: pointer; transition: all 0.2s;
      font-size: 14px; font-weight: 500;
      border-left: 3px solid transparent;
    }
    .sidebar-nav-item:hover { background: var(--surface); color: var(--text); }
    .sidebar-nav-item.active { color: var(--accent); border-left-color: var(--accent); background: var(--accent-dim); }
    .sidebar-nav-item-rtl { border-left: none; border-right: 3px solid transparent; }
    .sidebar-nav-item-rtl.active { border-right-color: var(--accent); }
    .sidebar-section { padding: 8px 20px 4px; font-size: 11px; font-weight: 700; color: var(--text3); text-transform: uppercase; letter-spacing: 1px; margin-top: 8px; }

    /* Tables */
    .data-table { width: 100%; border-collapse: collapse; }
    .data-table th { padding: 10px 14px; text-align: left; font-size: 12px; font-weight: 600; color: var(--text3); text-transform: uppercase; letter-spacing: 0.5px; border-bottom: 1px solid var(--border); }
    .data-table td { padding: 12px 14px; border-bottom: 1px solid var(--border); font-size: 14px; }
    .data-table tr:last-child td { border-bottom: none; }
    .data-table tr:hover td { background: var(--surface); }
    .data-table-rtl th, .data-table-rtl td { text-align: right; }

    /* Modal */
    .modal-overlay {
      position: fixed; inset: 0; z-index: 300;
      background: rgba(0,0,0,0.8); backdrop-filter: blur(4px);
      display: flex; align-items: center; justify-content: center; padding: 20px;
    }
    .modal {
      background: var(--bg2); border: 1px solid var(--border);
      border-radius: var(--radius); width: 100%; max-width: 560px;
      max-height: 90vh; overflow-y: auto;
      padding: 28px;
    }
    .modal-title { font-family: var(--font-display); font-weight: 700; font-size: 20px; margin-bottom: 20px; }

    /* Header */
    .header {
      position: sticky; top: 0; z-index: 100;
      background: rgba(8,12,20,0.92);
      backdrop-filter: blur(20px);
      border-bottom: 1px solid var(--border);
      padding: 0 24px;
      height: 64px; display: flex; align-items: center; justify-content: space-between;
      gap: 16px;
    }
    .header-logo {
      font-family: var(--font-display);
      font-weight: 800; font-size: 20px; color: var(--text);
      letter-spacing: -0.5px;
    }
    .header-logo span { color: var(--accent); }

    /* Lang switcher */
    .lang-btn {
      padding: 5px 12px; border-radius: var(--radius-sm);
      background: var(--surface); border: 1px solid var(--border);
      color: var(--text2); font-size: 13px; cursor: pointer;
      transition: all 0.2s; font-family: var(--font-body);
    }
    .lang-btn.active { background: var(--accent-dim); border-color: var(--accent); color: var(--accent); }
    .lang-btn:hover:not(.active) { border-color: var(--border-hover); color: var(--text); }

    /* Hero */
    .hero {
      position: relative; overflow: hidden;
      height: 420px; display: flex; align-items: flex-end;
      padding: 48px;
    }
    .hero-bg {
      position: absolute; inset: 0;
      object-fit: cover; width: 100%; height: 100%;
      filter: brightness(0.4);
    }
    .hero-content { position: relative; z-index: 1; }
    .hero-title {
      font-family: var(--font-display); font-weight: 800;
      font-size: clamp(32px, 5vw, 56px);
      line-height: 1.1; color: #fff;
      margin-bottom: 12px;
    }
    .hero-title span { color: var(--accent); }
    .hero-sub { color: rgba(255,255,255,0.7); font-size: 18px; }

    /* Img gallery */
    .gallery-main { width: 100%; aspect-ratio: 4/3; object-fit: cover; border-radius: var(--radius); }
    .gallery-thumbs { display: flex; gap: 8px; margin-top: 10px; flex-wrap: wrap; }
    .gallery-thumb {
      width: 64px; height: 64px; object-fit: cover;
      border-radius: var(--radius-sm); cursor: pointer;
      border: 2px solid transparent; transition: border-color 0.2s;
    }
    .gallery-thumb.active { border-color: var(--accent); }

    /* Search + filter */
    .catalog-controls {
      display: flex; gap: 12px; flex-wrap: wrap;
      margin-bottom: 24px; align-items: center;
    }
    .search-wrap { flex: 1; min-width: 200px; position: relative; }
    .search-icon { position: absolute; left: 12px; top: 50%; transform: translateY(-50%); color: var(--text3); }
    .search-input { padding-left: 36px !important; }

    /* Admin stat cards */
    .stat-card {
      background: var(--bg2); border: 1px solid var(--border);
      border-radius: var(--radius); padding: 20px;
      display: flex; flex-direction: column; gap: 6px;
    }
    .stat-num { font-family: var(--font-display); font-weight: 800; font-size: 32px; }
    .stat-label { font-size: 13px; color: var(--text2); }

    /* Role badge */
    .role-dev { background: rgba(168,85,247,0.15); color: #c084fc; border: 1px solid rgba(168,85,247,0.3); }
    .role-owner { background: rgba(251,191,36,0.15); color: #fbbf24; border: 1px solid rgba(251,191,36,0.3); }
    .role-admin { background: rgba(59,130,246,0.15); color: #60a5fa; border: 1px solid rgba(59,130,246,0.3); }

    /* Admin dropdown */
    .admin-dropdown-wrap { position: relative; }
    .admin-dropdown {
      position: absolute; top: calc(100% + 8px); right: 0;
      background: var(--bg2); border: 1px solid var(--border);
      border-radius: var(--radius); min-width: 180px;
      overflow: hidden; box-shadow: var(--shadow);
      z-index: 150;
    }
    .admin-dropdown-item {
      padding: 10px 16px; display: flex; align-items: center; gap: 10px;
      cursor: pointer; font-size: 14px; color: var(--text2);
      transition: all 0.15s;
    }
    .admin-dropdown-item:hover { background: var(--surface); color: var(--text); }

    /* Misc */
    .divider { height: 1px; background: var(--border); margin: 20px 0; }
    .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
    .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; }
    .flex { display: flex; }
    .flex-between { display: flex; justify-content: space-between; align-items: center; }
    .flex-end { display: flex; justify-content: flex-end; gap: 10px; }
    .gap-2 { gap: 8px; }
    .gap-3 { gap: 12px; }
    .mb-4 { margin-bottom: 16px; }
    .mb-6 { margin-bottom: 24px; }
    .mt-4 { margin-top: 16px; }
    .page-title { font-family: var(--font-display); font-weight: 800; font-size: 26px; margin-bottom: 24px; }
    .text-muted { color: var(--text2); }
    .text-sm { font-size: 13px; }
    .img-preview { width: 60px; height: 60px; object-fit: cover; border-radius: var(--radius-sm); border: 1px solid var(--border); }
    .no-products { text-align: center; padding: 60px 20px; color: var(--text2); }
    .spinner { width: 32px; height: 32px; border: 3px solid var(--border); border-top-color: var(--accent); border-radius: 50%; animation: spin 0.7s linear infinite; }
    .loading-wrap { display: flex; justify-content: center; padding: 60px; }

    @media (max-width: 768px) {
      .admin-layout { flex-direction: column; }
      .admin-sidebar { width: 100%; min-height: auto; height: auto; position: relative; flex-direction: row; flex-wrap: wrap; padding: 12px; gap: 4px; }
      .admin-main { padding: 20px 16px; }
      .hero { height: 280px; padding: 28px 20px; }
      .header { padding: 0 16px; }
      .grid-2 { grid-template-columns: 1fr; }
      .product-grid { grid-template-columns: repeat(auto-fill, minmax(160px, 1fr)); gap: 12px; }
      .sidebar-section { display: none; }
      .sidebar-logo { padding: 0 12px 12px; font-size: 15px; }
    }
  `}</style>
);

// ─────────────────────────────────────────────
// ICONS (inline SVG)
// ─────────────────────────────────────────────
const Icon = ({ name, size = 16, color = "currentColor" }) => {
  const icons = {
    search: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>,
    whatsapp: <svg width={size} height={size} viewBox="0 0 24 24" fill={color}><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>,
    grid: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><rect x="3" y="3" width="7" height="7"/><rect x="14" y="3" width="7" height="7"/><rect x="3" y="14" width="7" height="7"/><rect x="14" y="14" width="7" height="7"/></svg>,
    package: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M12.89 1.45l8 4A2 2 0 0122 7.24v9.53a2 2 0 01-1.11 1.79l-8 4a2 2 0 01-1.78 0l-8-4A2 2 0 012 16.77V7.24a2 2 0 011.11-1.79l8-4a2 2 0 011.78 0z"/><polyline points="2.32 6.16 12 11 21.68 6.16"/><line x1="12" y1="22.76" x2="12" y2="11"/></svg>,
    plus: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>,
    tag: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z"/><line x1="7" y1="7" x2="7.01" y2="7"/></svg>,
    settings: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 00.33 1.82l.06.06a2 2 0 010 2.83 2 2 0 01-2.83 0l-.06-.06a1.65 1.65 0 00-1.82-.33 1.65 1.65 0 00-1 1.51V21a2 2 0 01-4 0v-.09A1.65 1.65 0 009 19.4a1.65 1.65 0 00-1.82.33l-.06.06a2 2 0 01-2.83-2.83l.06-.06A1.65 1.65 0 004.68 15a1.65 1.65 0 00-1.51-1H3a2 2 0 010-4h.09A1.65 1.65 0 004.6 9a1.65 1.65 0 00-.33-1.82l-.06-.06a2 2 0 012.83-2.83l.06.06A1.65 1.65 0 009 4.68a1.65 1.65 0 001-1.51V3a2 2 0 014 0v.09a1.65 1.65 0 001 1.51 1.65 1.65 0 001.82-.33l.06-.06a2 2 0 012.83 2.83l-.06.06A1.65 1.65 0 0019.4 9a1.65 1.65 0 001.51 1H21a2 2 0 010 4h-.09a1.65 1.65 0 00-1.51 1z"/></svg>,
    logout: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M9 21H5a2 2 0 01-2-2V5a2 2 0 012-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/></svg>,
    user: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>,
    x: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>,
    edit: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M11 4H4a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7"/><path d="M18.5 2.5a2.121 2.121 0 013 3L12 15l-4 1 1-4 9.5-9.5z"/></svg>,
    trash: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><polyline points="3 6 5 6 21 6"/><path d="M19 6v14a2 2 0 01-2 2H7a2 2 0 01-2-2V6m3 0V4a1 1 0 011-1h4a1 1 0 011 1v2"/></svg>,
    image: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><polyline points="21 15 16 10 5 21"/></svg>,
    chevronDown: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><polyline points="6 9 12 15 18 9"/></svg>,
    shield: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>,
    barChart: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><line x1="12" y1="20" x2="12" y2="10"/><line x1="18" y1="20" x2="18" y2="4"/><line x1="6" y1="20" x2="6" y2="16"/></svg>,
    store: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>,
    eye: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>,
    eyeOff: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><path d="M17.94 17.94A10.07 10.07 0 0112 20c-7 0-11-8-11-8a18.45 18.45 0 015.06-5.94M9.9 4.24A9.12 9.12 0 0112 4c7 0 11 8 11 8a18.5 18.5 0 01-2.16 3.19m-6.72-1.07a3 3 0 11-4.24-4.24"/><line x1="1" y1="1" x2="23" y2="23"/></svg>,
    globe: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 014 10 15.3 15.3 0 01-4 10 15.3 15.3 0 01-4-10 15.3 15.3 0 014-10z"/></svg>,
    check: <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke={color} strokeWidth="2.5"><polyline points="20 6 9 17 4 12"/></svg>,
  };
  return icons[name] || null;
};

// ─────────────────────────────────────────────
// FIREBASE MOCK SERVICE (swap with real Firebase)
// ─────────────────────────────────────────────
class FirebaseService {
  constructor() {
    this._products = [...MOCK_PRODUCTS];
    this._settings = { ...MOCK_SETTINGS };
    this._categories = [...MOCK_CATEGORIES];
    this._users = {
      "dev@nexus.com": { role: "developer", name: "Dev User" },
      "owner@nexus.com": { role: "owner", name: "Store Owner" },
      "admin@nexus.com": { role: "admin", name: "Store Admin" },
    };
    this._currentUser = null;
    this._listeners = {};
  }

  _emit(channel) {
    if (this._listeners[channel]) this._listeners[channel].forEach(fn => fn());
  }

  _on(channel, fn) {
    if (!this._listeners[channel]) this._listeners[channel] = [];
    this._listeners[channel].push(fn);
    return () => { this._listeners[channel] = this._listeners[channel].filter(l => l !== fn); };
  }

  // Auth
  async signIn(email, password) {
    await new Promise(r => setTimeout(r, 600));
    const user = this._users[email];
    if (!user || password !== "password123") throw new Error("Invalid credentials. Try password123");
    this._currentUser = { email, ...user };
    return this._currentUser;
  }

  signOut() { this._currentUser = null; }
  getCurrentUser() { return this._currentUser; }

  // Products
  onProducts(fn) {
    fn([...this._products]);
    return this._on("products", () => fn([...this._products]));
  }

  async addProduct(data) {
    const p = { id: generateId(), ...data, visibility: true };
    this._products.push(p);
    this._emit("products");
    return p;
  }

  async updateProduct(id, data) {
    const idx = this._products.findIndex(p => p.id === id);
    if (idx !== -1) { this._products[idx] = { ...this._products[idx], ...data }; this._emit("products"); }
  }

  async deleteProduct(id) {
    this._products = this._products.filter(p => p.id !== id);
    this._emit("products");
  }

  // Categories
  onCategories(fn) {
    fn([...this._categories]);
    return this._on("categories", () => fn([...this._categories]));
  }

  async addCategory(name) {
    if (!this._categories.includes(name)) { this._categories.push(name); this._emit("categories"); }
  }

  async deleteCategory(name) {
    this._categories = this._categories.filter(c => c !== name);
    this._emit("categories");
  }

  // Settings
  onSettings(fn) {
    fn({ ...this._settings });
    return this._on("settings", () => fn({ ...this._settings }));
  }

  async updateSettings(data) {
    this._settings = { ...this._settings, ...data };
    this._emit("settings");
  }

  // Image upload mock
  async uploadImage(file) {
    await new Promise(r => setTimeout(r, 1200));
    return URL.createObjectURL(file);
  }
}

const db = new FirebaseService();

// ─────────────────────────────────────────────
// STOCK TAG COMPONENT
// ─────────────────────────────────────────────
const StockTag = ({ status }) => {
  const { t } = useApp();
  const cls = status === "in_stock" ? "tag-green" : status === "low_stock" ? "tag-yellow" : "tag-red";
  return <span className={`tag ${cls}`}><span style={{ width: 6, height: 6, borderRadius: "50%", background: stockColor(status), display: "inline-block" }} />{stockLabel(status, t)}</span>;
};

// ─────────────────────────────────────────────
// PRODUCT DRAWER
// ─────────────────────────────────────────────
const ProductDrawer = ({ product, onClose }) => {
  const { t, settings, lang } = useApp();
  const [activeImg, setActiveImg] = useState(0);
  const isRTL = TRANSLATIONS[lang].dir === "rtl";

  if (!product) return null;
  const discountedPrice = product.discount_active
    ? calcDiscountedPrice(product.price, product.discount_percentage)
    : product.price;

  return (
    <>
      <div className="drawer-overlay fade-in" onClick={onClose} />
      <div className={`drawer slide-right ${isRTL ? "drawer-rtl" : ""}`} dir={TRANSLATIONS[lang].dir}>
        {/* Close */}
        <div style={{ padding: "16px 20px", borderBottom: "1px solid var(--border)", display: "flex", justifyContent: "space-between", alignItems: "center" }}>
          <span style={{ fontFamily: "var(--font-display)", fontWeight: 700, fontSize: 16 }}>{product.name}</span>
          <button className="btn btn-ghost btn-sm" onClick={onClose}><Icon name="x" size={16} /></button>
        </div>

        <div style={{ padding: "20px", flex: 1 }}>
          {/* Gallery */}
          {product.images?.length > 0 && (
            <>
              <img src={product.images[activeImg]} alt="" className="gallery-main" />
              {product.images.length > 1 && (
                <div className="gallery-thumbs">
                  {product.images.map((img, i) => (
                    <img key={i} src={img} alt="" className={`gallery-thumb ${i === activeImg ? "active" : ""}`} onClick={() => setActiveImg(i)} />
                  ))}
                </div>
              )}
            </>
          )}

          <div style={{ marginTop: 20 }}>
            <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-start", marginBottom: 8 }}>
              <h2 style={{ fontFamily: "var(--font-display)", fontWeight: 800, fontSize: 22 }}>{product.name}</h2>
              <StockTag status={product.status} />
            </div>

            <p style={{ color: "var(--text2)", lineHeight: 1.7, marginBottom: 16 }}>{product.description}</p>

            {/* Price */}
            <div style={{ display: "flex", alignItems: "center", gap: 12, marginBottom: 8 }}>
              <span style={{ fontFamily: "var(--font-display)", fontWeight: 800, fontSize: 28, color: "var(--accent)" }}>${discountedPrice}</span>
              {product.discount_active && (
                <>
                  <span style={{ fontSize: 16, color: "var(--text3)", textDecoration: "line-through" }}>${product.price}</span>
                  <span className="tag tag-red">{product.discount_percentage}% {t.discount}</span>
                </>
              )}
            </div>

            <p style={{ color: "var(--text3)", fontSize: 13, marginBottom: 20 }}>Code: <span style={{ color: "var(--text2)" }}>{product.product_code}</span></p>

            {/* WhatsApp button */}
            <a
              href={buildWhatsAppUrl(product, settings, t)}
              target="_blank" rel="noopener noreferrer"
              className={`btn btn-whatsapp ${product.status === "out_of_stock" ? "" : ""}`}
              style={{ pointerEvents: product.status === "out_of_stock" ? "none" : "auto", opacity: product.status === "out_of_stock" ? 0.5 : 1 }}
            >
              <Icon name="whatsapp" size={20} color="#fff" /> {t.orderWhatsApp}
            </a>
          </div>
        </div>
      </div>
    </>
  );
};

// ─────────────────────────────────────────────
// PRODUCT CARD
// ─────────────────────────────────────────────
const ProductCard = ({ product, onClick }) => {
  const discountedPrice = product.discount_active
    ? calcDiscountedPrice(product.price, product.discount_percentage)
    : product.price;

  return (
    <div className="product-card fade-in" onClick={onClick}>
      <div className="product-card-img-wrap">
        <img
          src={product.images?.[0] || "https://images.unsplash.com/photo-1560769629-975ec94e6a86?w=600&q=80"}
          alt={product.name}
          className="product-card-img"
          loading="lazy"
        />
        {product.discount_active && (
          <span className="discount-badge">{product.discount_percentage}% OFF</span>
        )}
        <div style={{ position: "absolute", bottom: 10, right: 10 }}>
          <StockTag status={product.status} />
        </div>
      </div>
      <div className="product-card-body">
        <div className="product-card-name">{product.name}</div>
        <div style={{ fontSize: 12, color: "var(--text3)", marginBottom: 4 }}>{product.category}</div>
        <div className="product-card-price">
          <span className="price-current">${discountedPrice}</span>
          {product.discount_active && <span className="price-old">${product.price}</span>}
        </div>
      </div>
    </div>
  );
};

// ─────────────────────────────────────────────
// LANGUAGE SWITCHER
// ─────────────────────────────────────────────
const LangSwitcher = () => {
  const { lang, setLang } = useApp();
  return (
    <div style={{ display: "flex", gap: 6 }}>
      {[["en", "EN"], ["ar", "ع"], ["fr", "FR"]].map(([code, label]) => (
        <button key={code} className={`lang-btn ${lang === code ? "active" : ""}`} onClick={() => setLang(code)}>{label}</button>
      ))}
    </div>
  );
};

// ─────────────────────────────────────────────
// PUBLIC STORE PAGE
// ─────────────────────────────────────────────
const StorePage = () => {
  const { products, settings, t, lang, user, setPage } = useApp();
  const [selected, setSelected] = useState(null);
  const [search, setSearch] = useState("");
  const [catFilter, setCatFilter] = useState("all");
  const [adminOpen, setAdminOpen] = useState(false);
  const isRTL = TRANSLATIONS[lang].dir === "rtl";
  const categories = [...new Set(products.map(p => p.category).filter(Boolean))];

  const filtered = products.filter(p => {
    if (!p.visibility) return false;
    if (catFilter !== "all" && p.category !== catFilter) return false;
    if (search && !p.name.toLowerCase().includes(search.toLowerCase()) && !p.product_code.toLowerCase().includes(search.toLowerCase())) return false;
    return true;
  });

  const roleClass = user?.role === "developer" ? "role-dev" : user?.role === "owner" ? "role-owner" : "role-admin";

  return (
    <div dir={TRANSLATIONS[lang].dir}>
      {/* HEADER */}
      <header className="header">
        <div className="header-logo">
          {settings.logo_url
            ? <img src={settings.logo_url} alt="logo" style={{ height: 36 }} />
            : <><span style={{ color: "var(--accent)" }}>NX</span>{" "}{settings.store_name || t.storeName}</>
          }
        </div>

        <div style={{ display: "flex", alignItems: "center", gap: 12 }}>
          <LangSwitcher />

          {user ? (
            <div className="admin-dropdown-wrap">
              <button className="btn btn-ghost btn-sm" onClick={() => setAdminOpen(v => !v)}>
                <Icon name="shield" size={15} /> {t.adminPanel} <Icon name="chevronDown" size={13} />
              </button>
              {adminOpen && (
                <div className="admin-dropdown scale-in" style={{ right: isRTL ? "auto" : 0, left: isRTL ? 0 : "auto" }}>
                  <div style={{ padding: "10px 16px 6px", borderBottom: "1px solid var(--border)", marginBottom: 4 }}>
                    <div style={{ fontSize: 12, color: "var(--text3)" }}>{user.email}</div>
                    <span className={`tag ${roleClass}`} style={{ marginTop: 4 }}>{user.role}</span>
                  </div>
                  {[
                    ["stock", t.stockPage, "barChart"],
                    ["products-admin", t.productPage, "package"],
                    ...(["owner", "developer"].includes(user.role) ? [
                      ["add-product", t.addPage, "plus"],
                      ["categories", t.catPage, "tag"],
                      ["store-settings", t.settingsPage, "settings"],
                    ] : []),
                  ].map(([page, label, icon]) => (
                    <div key={page} className="admin-dropdown-item" onClick={() => { setPage(page); setAdminOpen(false); }}>
                      <Icon name={icon} size={15} /> {label}
                    </div>
                  ))}
                  <div className="admin-dropdown-item" style={{ borderTop: "1px solid var(--border)", marginTop: 4, color: "var(--red)" }} onClick={() => { db.signOut(); window.location.reload(); }}>
                    <Icon name="logout" size={15} color="var(--red)" /> {t.logout}
                  </div>
                </div>
              )}
            </div>
          ) : (
            <button className="btn btn-ghost btn-sm" onClick={() => setPage("login")}>
              <Icon name="user" size={15} /> {t.login}
            </button>
          )}
        </div>
      </header>

      {/* HERO */}
      <section className="hero">
        {settings.banner_url && <img src={settings.banner_url} alt="" className="hero-bg" />}
        <div className="hero-content fade-in">
          <div className="hero-title">
            {settings.store_name || t.storeName}<br />
            <span>{settings.banner_text || t.tagline}</span>
          </div>
        </div>
      </section>

      {/* CATALOG */}
      <main style={{ maxWidth: 1280, margin: "0 auto", padding: "40px 24px" }}>
        <div className="catalog-controls">
          <div className="search-wrap">
            <span className="search-icon"><Icon name="search" size={16} /></span>
            <input className="input search-input" placeholder={t.search} value={search} onChange={e => setSearch(e.target.value)} />
          </div>
          <select className="select" style={{ width: "auto", minWidth: 160 }} value={catFilter} onChange={e => setCatFilter(e.target.value)}>
            <option value="all">{t.filterCategory}</option>
            {categories.map(c => <option key={c} value={c}>{c}</option>)}
          </select>
        </div>

        {filtered.length === 0
          ? <div className="no-products"><Icon name="package" size={40} color="var(--text3)" /><p style={{ marginTop: 12 }}>{t.noProducts}</p></div>
          : <div className="product-grid">{filtered.map(p => <ProductCard key={p.id} product={p} onClick={() => setSelected(p)} />)}</div>
        }
      </main>

      {selected && <ProductDrawer product={selected} onClose={() => setSelected(null)} />}
    </div>
  );
};

// ─────────────────────────────────────────────
// LOGIN PAGE
// ─────────────────────────────────────────────
const LoginPage = () => {
  const { t, setUser, setPage, lang } = useApp();
  const [email, setEmail] = useState("dev@nexus.com");
  const [pass, setPass] = useState("password123");
  const [loading, setLoading] = useState(false);
  const [error, setError] = useState("");

  const handleLogin = async () => {
    setLoading(true); setError("");
    try {
      const user = await db.signIn(email, pass);
      setUser(user);
      setPage("store");
    } catch (e) { setError(e.message); }
    setLoading(false);
  };

  return (
    <div dir={TRANSLATIONS[lang].dir} style={{ minHeight: "100vh", display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center", padding: 20 }}>
      <div style={{ width: "100%", maxWidth: 400 }}>
        <div style={{ textAlign: "center", marginBottom: 32 }}>
          <div style={{ fontFamily: "var(--font-display)", fontWeight: 800, fontSize: 28, color: "var(--accent)", marginBottom: 8 }}>NEXUS</div>
          <div style={{ color: "var(--text2)" }}>{t.adminPanel}</div>
        </div>
        <div className="glass" style={{ padding: 28, borderRadius: "var(--radius)" }}>
          {error && <div style={{ background: "rgba(239,68,68,0.1)", border: "1px solid rgba(239,68,68,0.3)", borderRadius: 8, padding: "10px 14px", marginBottom: 16, color: "var(--red)", fontSize: 14 }}>{error}</div>}
          <div className="field mb-4">
            <label>{t.email}</label>
            <input className="input" type="email" value={email} onChange={e => setEmail(e.target.value)} />
          </div>
          <div className="field mb-4">
            <label>{t.password}</label>
            <input className="input" type="password" value={pass} onChange={e => setPass(e.target.value)} onKeyDown={e => e.key === "Enter" && handleLogin()} />
          </div>
          <div style={{ fontSize: 12, color: "var(--text3)", marginBottom: 16, background: "rgba(255,255,255,0.03)", padding: "8px 12px", borderRadius: 6 }}>
            Demo: dev@nexus.com / password123
          </div>
          <button className="btn btn-primary" style={{ width: "100%", justifyContent: "center" }} onClick={handleLogin} disabled={loading}>
            {loading ? <span className="spinner" style={{ width: 18, height: 18, borderWidth: 2 }} /> : t.loginBtn}
          </button>
          <button className="btn btn-ghost" style={{ width: "100%", justifyContent: "center", marginTop: 10 }} onClick={() => setPage("store")}>← Back to Store</button>
        </div>
      </div>
    </div>
  );
};

// ─────────────────────────────────────────────
// ADMIN LAYOUT WRAPPER
// ─────────────────────────────────────────────
const AdminLayout = ({ children, activePage }) => {
  const { t, user, setPage, lang } = useApp();
  const isRTL = TRANSLATIONS[lang].dir === "rtl";

  if (!user) return <div style={{ padding: 40, textAlign: "center" }}><div style={{ color: "var(--red)", fontSize: 20, fontFamily: "var(--font-display)" }}>{t.accessDenied}</div></div>;

  const navItems = [
    { key: "stock", label: t.stockPage, icon: "barChart", roles: ["admin", "owner", "developer"] },
    { key: "products-admin", label: t.productPage, icon: "package", roles: ["admin", "owner", "developer"] },
    { key: "add-product", label: t.addPage, icon: "plus", roles: ["owner", "developer"] },
    { key: "categories", label: t.catPage, icon: "tag", roles: ["owner", "developer"] },
    { key: "store-settings", label: t.settingsPage, icon: "settings", roles: ["owner", "developer"] },
  ].filter(i => i.roles.includes(user.role));

  const roleClass = user.role === "developer" ? "role-dev" : user.role === "owner" ? "role-owner" : "role-admin";

  return (
    <div className="admin-layout" dir={TRANSLATIONS[lang].dir}>
      <aside className={`admin-sidebar ${isRTL ? "admin-sidebar-rtl" : ""}`}>
        <div className="sidebar-logo">⬡ NEXUS ADMIN</div>
        <div className="sidebar-section">Navigation</div>
        {navItems.map(item => (
          <div
            key={item.key}
            className={`sidebar-nav-item ${isRTL ? "sidebar-nav-item-rtl" : ""} ${activePage === item.key ? "active" : ""}`}
            onClick={() => setPage(item.key)}
          >
            <Icon name={item.icon} size={16} /> {item.label}
          </div>
        ))}
        <div style={{ flex: 1 }} />
        <div style={{ borderTop: "1px solid var(--border)", padding: "16px 20px" }}>
          <div style={{ fontSize: 12, color: "var(--text3)", marginBottom: 6 }}>{user.email}</div>
          <span className={`tag ${roleClass}`}>{user.role}</span>
          <div style={{ display: "flex", gap: 8, marginTop: 12 }}>
            <button className="btn btn-ghost btn-sm" onClick={() => setPage("store")}><Icon name="store" size={14} /> Store</button>
            <button className="btn btn-ghost btn-sm" style={{ color: "var(--red)" }} onClick={() => { db.signOut(); setPage("store"); }}>
              <Icon name="logout" size={14} color="var(--red)" />
            </button>
          </div>
        </div>
      </aside>
      <main className="admin-main">{children}</main>
    </div>
  );
};

// ─────────────────────────────────────────────
// ADMIN: STOCK PAGE
// ─────────────────────────────────────────────
const StockPage = () => {
  const { products, t, lang } = useApp();
  const isRTL = TRANSLATIONS[lang].dir === "rtl";
  const total = products.length;
  const inStock = products.filter(p => p.status === "in_stock").length;
  const low = products.filter(p => p.status === "low_stock").length;
  const out = products.filter(p => p.status === "out_of_stock").length;

  return (
    <AdminLayout activePage="stock">
      <div className="page-title">{t.stockPage}</div>
      <div className="grid-3 mb-6" style={{ gap: 16 }}>
        {[
          { label: "Total Products", num: total, color: "var(--accent2)" },
          { label: t.inStock, num: inStock, color: "var(--green)" },
          { label: t.lowStock, num: low, color: "var(--yellow)" },
          { label: t.outOfStock, num: out, color: "var(--red)" },
        ].map((s, i) => (
          <div key={i} className="stat-card">
            <div className="stat-num" style={{ color: s.color }}>{s.num}</div>
            <div className="stat-label">{s.label}</div>
          </div>
        ))}
      </div>
      <div className="glass" style={{ borderRadius: "var(--radius)", overflow: "hidden" }}>
        <table className={`data-table ${isRTL ? "data-table-rtl" : ""}`}>
          <thead>
            <tr>
              <th>Product</th>
              <th>{t.productCode}</th>
              <th>{t.category}</th>
              <th>{t.stockStatus}</th>
              <th>Stock #</th>
            </tr>
          </thead>
          <tbody>
            {products.map(p => (
              <tr key={p.id}>
                <td>
                  <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                    {p.images?.[0] && <img src={p.images[0]} alt="" className="img-preview" />}
                    <span style={{ fontWeight: 500 }}>{p.name}</span>
                  </div>
                </td>
                <td><code style={{ color: "var(--text2)", fontSize: 12 }}>{p.product_code}</code></td>
                <td><span className="tag tag-blue">{p.category}</span></td>
                <td><StockTag status={p.status} /></td>
                <td style={{ color: "var(--text2)" }}>{p.stock}</td>
              </tr>
            ))}
          </tbody>
        </table>
      </div>
    </AdminLayout>
  );
};

// ─────────────────────────────────────────────
// PRODUCT EDIT MODAL
// ─────────────────────────────────────────────
const ProductEditModal = ({ product, categories, onClose, userRole }) => {
  const { t } = useApp();
  const canFullEdit = ["owner", "developer"].includes(userRole);
  const [form, setForm] = useState({
    name: product?.name || "",
    description: product?.description || "",
    price: product?.price || "",
    category: product?.category || categories[0] || "",
    product_code: product?.product_code || "",
    discount_active: product?.discount_active || false,
    discount_percentage: product?.discount_percentage || 0,
    stock: product?.stock || 0,
    status: product?.status || "in_stock",
    visibility: product?.visibility !== false,
    images: product?.images || [],
  });
  const [saving, setSaving] = useState(false);
  const [uploading, setUploading] = useState(false);
  const set = (k, v) => setForm(f => ({ ...f, [k]: v }));

  const discountedPrice = form.discount_active && form.price
    ? calcDiscountedPrice(+form.price, +form.discount_percentage)
    : null;

  const handleSave = async () => {
    setSaving(true);
    const data = { ...form, price: +form.price, discount_percentage: +form.discount_percentage, stock: +form.stock };
    if (product) {
      await db.updateProduct(product.id, data);
    } else {
      await db.addProduct(data);
    }
    setSaving(false);
    onClose();
  };

  const handleImageUpload = async (e) => {
    const file = e.target.files[0];
    if (!file) return;
    setUploading(true);
    const url = await db.uploadImage(file);
    set("images", [...form.images, url]);
    setUploading(false);
  };

  return (
    <div className="modal-overlay">
      <div className="modal scale-in">
        <div className="modal-title">{product ? "Edit Product" : "Add Product"}</div>
        <div style={{ display: "flex", flexDirection: "column", gap: 14 }}>
          {canFullEdit && (
            <>
              <div className="field"><label>{t.name}</label><input className="input" value={form.name} onChange={e => set("name", e.target.value)} /></div>
              <div className="field"><label>{t.description}</label><textarea className="textarea" value={form.description} onChange={e => set("description", e.target.value)} /></div>
              <div className="field"><label>{t.category}</label>
                <select className="select" value={form.category} onChange={e => set("category", e.target.value)}>
                  {categories.map(c => <option key={c} value={c}>{c}</option>)}
                </select>
              </div>
              <div className="field"><label>{t.productCode}</label><input className="input" value={form.product_code} onChange={e => set("product_code", e.target.value)} /></div>
            </>
          )}

          <div className="grid-2">
            <div className="field">
              <label>{t.price} ($)</label>
              <input className="input" type="number" value={form.price} onChange={e => set("price", e.target.value)} />
            </div>
            <div className="field">
              <label>{t.stockStatus}</label>
              <select className="select" value={form.status} onChange={e => set("status", e.target.value)}>
                <option value="in_stock">{t.inStock}</option>
                <option value="low_stock">{t.lowStock}</option>
                <option value="out_of_stock">{t.outOfStock}</option>
              </select>
            </div>
          </div>

          {/* Discount */}
          <div className="glass" style={{ padding: 14, borderRadius: "var(--radius-sm)" }}>
            <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: form.discount_active ? 12 : 0 }}>
              <label style={{ fontSize: 14, fontWeight: 500 }}>{t.discountActive}</label>
              <label className="toggle">
                <input type="checkbox" checked={form.discount_active} onChange={e => set("discount_active", e.target.checked)} />
                <span className="toggle-slider" />
              </label>
            </div>
            {form.discount_active && (
              <div className="grid-2">
                <div className="field">
                  <label>{t.discountPct}</label>
                  <input className="input" type="number" min={1} max={99} value={form.discount_percentage} onChange={e => set("discount_percentage", e.target.value)} />
                </div>
                <div className="field">
                  <label>{t.newPrice}</label>
                  <div className="input" style={{ color: "var(--accent)", fontWeight: 700 }}>${discountedPrice}</div>
                </div>
              </div>
            )}
          </div>

          {canFullEdit && (
            <>
              {/* Visibility */}
              <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center" }}>
                <label style={{ fontSize: 14, fontWeight: 500 }}>{t.visibility}: {form.visibility ? t.visible : t.hidden}</label>
                <label className="toggle">
                  <input type="checkbox" checked={form.visibility} onChange={e => set("visibility", e.target.checked)} />
                  <span className="toggle-slider" />
                </label>
              </div>

              {/* Images */}
              <div className="field">
                <label>{t.images}</label>
                <div style={{ display: "flex", gap: 8, flexWrap: "wrap", marginBottom: 8 }}>
                  {form.images.map((img, i) => (
                    <div key={i} style={{ position: "relative" }}>
                      <img src={img} alt="" className="img-preview" style={{ width: 80, height: 80 }} />
                      <button onClick={() => set("images", form.images.filter((_, j) => j !== i))} style={{ position: "absolute", top: -6, right: -6, background: "var(--red)", border: "none", borderRadius: "50%", width: 20, height: 20, display: "flex", alignItems: "center", justifyContent: "center", cursor: "pointer", color: "#fff" }}>
                        <Icon name="x" size={12} />
                      </button>
                    </div>
                  ))}
                  <label style={{ width: 80, height: 80, border: "2px dashed var(--border)", borderRadius: "var(--radius-sm)", display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center", cursor: "pointer", color: "var(--text3)", fontSize: 12, gap: 4 }}>
                    {uploading ? <span className="spinner" style={{ width: 20, height: 20, borderWidth: 2 }} /> : <><Icon name="plus" size={20} />{t.uploadImage}</>}
                    <input type="file" accept="image/*" style={{ display: "none" }} onChange={handleImageUpload} disabled={uploading} />
                  </label>
                </div>
              </div>
            </>
          )}

          <div className="flex-end mt-4">
            <button className="btn btn-ghost" onClick={onClose}>{t.cancel}</button>
            <button className="btn btn-primary" onClick={handleSave} disabled={saving}>
              {saving ? <span className="spinner" style={{ width: 16, height: 16, borderWidth: 2 }} /> : <><Icon name="check" size={15} />{t.save}</>}
            </button>
          </div>
        </div>
      </div>
    </div>
  );
};

// ─────────────────────────────────────────────
// ADMIN: PRODUCTS PAGE
// ─────────────────────────────────────────────
const ProductsAdminPage = () => {
  const { products, categories, t, user, lang } = useApp();
  const [editing, setEditing] = useState(null);
  const [editOpen, setEditOpen] = useState(false);
  const isRTL = TRANSLATIONS[lang].dir === "rtl";

  return (
    <AdminLayout activePage="products-admin">
      <div className="page-title">{t.productPage}</div>
      <div className="glass" style={{ borderRadius: "var(--radius)", overflow: "hidden" }}>
        <table className={`data-table ${isRTL ? "data-table-rtl" : ""}`}>
          <thead>
            <tr>
              <th>Product</th>
              <th>{t.price}</th>
              <th>Discount</th>
              <th>{t.stockStatus}</th>
              <th>{t.visibility}</th>
              <th>Actions</th>
            </tr>
          </thead>
          <tbody>
            {products.map(p => {
              const discountedPrice = p.discount_active ? calcDiscountedPrice(p.price, p.discount_percentage) : null;
              return (
                <tr key={p.id}>
                  <td>
                    <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
                      {p.images?.[0] && <img src={p.images[0]} alt="" className="img-preview" />}
                      <div>
                        <div style={{ fontWeight: 500 }}>{p.name}</div>
                        <div style={{ fontSize: 12, color: "var(--text3)" }}>{p.product_code}</div>
                      </div>
                    </div>
                  </td>
                  <td>
                    {discountedPrice ? (
                      <><span style={{ color: "var(--accent)", fontWeight: 700 }}>${discountedPrice}</span> <span style={{ fontSize: 12, color: "var(--text3)", textDecoration: "line-through" }}>${p.price}</span></>
                    ) : <span style={{ fontWeight: 600 }}>${p.price}</span>}
                  </td>
                  <td>{p.discount_active ? <span className="tag tag-red">{p.discount_percentage}%</span> : <span style={{ color: "var(--text3)", fontSize: 13 }}>—</span>}</td>
                  <td><StockTag status={p.status} /></td>
                  <td>
                    {p.visibility
                      ? <span style={{ color: "var(--green)" }}><Icon name="eye" size={14} /></span>
                      : <span style={{ color: "var(--text3)" }}><Icon name="eyeOff" size={14} /></span>
                    }
                  </td>
                  <td>
                    <button className="btn btn-ghost btn-sm" onClick={() => { setEditing(p); setEditOpen(true); }}>
                      <Icon name="edit" size={14} /> Edit
                    </button>
                  </td>
                </tr>
              );
            })}
          </tbody>
        </table>
      </div>
      {editOpen && <ProductEditModal product={editing} categories={categories} onClose={() => setEditOpen(false)} userRole={user?.role} />}
    </AdminLayout>
  );
};

// ─────────────────────────────────────────────
// ADMIN: ADD/DELETE PRODUCTS
// ─────────────────────────────────────────────
const AddProductPage = () => {
  const { products, categories, t, user } = useApp();
  const [addOpen, setAddOpen] = useState(false);
  const [delConfirm, setDelConfirm] = useState(null);

  if (!["owner", "developer"].includes(user?.role)) return (
    <AdminLayout activePage="add-product">
      <div style={{ color: "var(--red)", fontFamily: "var(--font-display)", fontSize: 20 }}>{t.accessDenied}</div>
    </AdminLayout>
  );

  return (
    <AdminLayout activePage="add-product">
      <div className="flex-between mb-6">
        <div className="page-title" style={{ marginBottom: 0 }}>{t.addPage}</div>
        <button className="btn btn-primary" onClick={() => setAddOpen(true)}><Icon name="plus" size={16} /> {t.addNew}</button>
      </div>

      <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
        {products.map(p => (
          <div key={p.id} className="glass flex-between" style={{ padding: "12px 16px", borderRadius: "var(--radius-sm)" }}>
            <div style={{ display: "flex", alignItems: "center", gap: 12 }}>
              {p.images?.[0] && <img src={p.images[0]} alt="" className="img-preview" />}
              <div>
                <div style={{ fontWeight: 600 }}>{p.name}</div>
                <div style={{ fontSize: 12, color: "var(--text3)" }}>{p.product_code} · {p.category}</div>
              </div>
            </div>
            <button className="btn btn-danger btn-sm" onClick={() => setDelConfirm(p.id)}>
              <Icon name="trash" size={14} color="var(--red)" /> {t.delete}
            </button>
          </div>
        ))}
      </div>

      {addOpen && <ProductEditModal product={null} categories={categories} onClose={() => setAddOpen(false)} userRole={user?.role} />}

      {delConfirm && (
        <div className="modal-overlay">
          <div className="modal scale-in" style={{ maxWidth: 360 }}>
            <div className="modal-title" style={{ fontSize: 18 }}>Confirm Delete</div>
            <p style={{ color: "var(--text2)", marginBottom: 20 }}>{t.confirmDelete}</p>
            <div className="flex-end">
              <button className="btn btn-ghost" onClick={() => setDelConfirm(null)}>{t.cancel}</button>
              <button className="btn btn-danger" onClick={async () => { await db.deleteProduct(delConfirm); setDelConfirm(null); }}>
                <Icon name="trash" size={14} color="var(--red)" /> {t.delete}
              </button>
            </div>
          </div>
        </div>
      )}
    </AdminLayout>
  );
};

// ─────────────────────────────────────────────
// ADMIN: CATEGORIES
// ─────────────────────────────────────────────
const CategoriesPage = () => {
  const { categories, t, user } = useApp();
  const [newCat, setNewCat] = useState("");
  const [saving, setSaving] = useState(false);

  if (!["owner", "developer"].includes(user?.role)) return (
    <AdminLayout activePage="categories">
      <div style={{ color: "var(--red)", fontFamily: "var(--font-display)", fontSize: 20 }}>{t.accessDenied}</div>
    </AdminLayout>
  );

  const handleAdd = async () => {
    if (!newCat.trim()) return;
    setSaving(true);
    await db.addCategory(newCat.trim());
    setNewCat("");
    setSaving(false);
  };

  return (
    <AdminLayout activePage="categories">
      <div className="page-title">{t.catPage}</div>
      <div className="glass" style={{ borderRadius: "var(--radius)", padding: 24, marginBottom: 24, maxWidth: 480 }}>
        <div style={{ display: "flex", gap: 10, marginBottom: 20 }}>
          <input className="input" placeholder={t.categoryName} value={newCat} onChange={e => setNewCat(e.target.value)} onKeyDown={e => e.key === "Enter" && handleAdd()} style={{ flex: 1 }} />
          <button className="btn btn-primary" onClick={handleAdd} disabled={saving || !newCat.trim()}>
            <Icon name="plus" size={16} /> {t.addCategory}
          </button>
        </div>
        {categories.length === 0
          ? <p style={{ color: "var(--text3)" }}>{t.noCategories}</p>
          : <div style={{ display: "flex", flexDirection: "column", gap: 8 }}>
            {categories.map(cat => (
              <div key={cat} className="flex-between" style={{ background: "var(--surface)", padding: "10px 14px", borderRadius: "var(--radius-sm)", border: "1px solid var(--border)" }}>
                <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
                  <Icon name="tag" size={14} color="var(--accent)" />
                  <span style={{ fontWeight: 500 }}>{cat}</span>
                </div>
                <button className="btn btn-danger btn-sm" onClick={() => db.deleteCategory(cat)}>
                  <Icon name="trash" size={13} color="var(--red)" />
                </button>
              </div>
            ))}
          </div>
        }
      </div>
    </AdminLayout>
  );
};

// ─────────────────────────────────────────────
// ADMIN: STORE SETTINGS
// ─────────────────────────────────────────────
const SettingsPage = () => {
  const { settings, t, user } = useApp();
  const [form, setForm] = useState({ ...settings });
  const [saving, setSaving] = useState(false);
  const [saved, setSaved] = useState(false);
  const set = (k, v) => setForm(f => ({ ...f, [k]: v }));

  useEffect(() => { setForm({ ...settings }); }, [settings]);

  if (!["owner", "developer"].includes(user?.role)) return (
    <AdminLayout activePage="store-settings">
      <div style={{ color: "var(--red)", fontFamily: "var(--font-display)", fontSize: 20 }}>{t.accessDenied}</div>
    </AdminLayout>
  );

  const handleSave = async () => {
    setSaving(true);
    await db.updateSettings(form);
    setSaving(false);
    setSaved(true);
    setTimeout(() => setSaved(false), 2500);
  };

  return (
    <AdminLayout activePage="store-settings">
      <div className="page-title">{t.settingsPage}</div>
      <div style={{ maxWidth: 600, display: "flex", flexDirection: "column", gap: 16 }}>
        <div className="glass" style={{ padding: 24, borderRadius: "var(--radius)" }}>
          <div style={{ fontFamily: "var(--font-display)", fontWeight: 700, marginBottom: 16 }}>Store Identity</div>
          <div style={{ display: "flex", flexDirection: "column", gap: 14 }}>
            <div className="field"><label>Store Name</label><input className="input" value={form.store_name || ""} onChange={e => set("store_name", e.target.value)} /></div>
            <div className="field"><label>{t.bannerText}</label><input className="input" value={form.banner_text || ""} onChange={e => set("banner_text", e.target.value)} /></div>
            <div className="field"><label>{t.storeLogo}</label><input className="input" placeholder="https://..." value={form.logo_url || ""} onChange={e => set("logo_url", e.target.value)} /></div>
            <div className="field"><label>{t.heroBanner}</label><input className="input" placeholder="https://..." value={form.banner_url || ""} onChange={e => set("banner_url", e.target.value)} /></div>
          </div>
        </div>

        <div className="glass" style={{ padding: 24, borderRadius: "var(--radius)" }}>
          <div style={{ fontFamily: "var(--font-display)", fontWeight: 700, marginBottom: 16 }}>WhatsApp Settings</div>
          <div style={{ display: "flex", flexDirection: "column", gap: 14 }}>
            <div className="field"><label>{t.whatsappNumber} (with country code)</label><input className="input" placeholder="1234567890" value={form.whatsapp_number || ""} onChange={e => set("whatsapp_number", e.target.value)} /></div>
            <div className="field">
              <label>{t.whatsappTemplate}</label>
              <textarea className="textarea" style={{ minHeight: 100, fontFamily: "monospace", fontSize: 13 }} value={form.whatsapp_template || ""} onChange={e => set("whatsapp_template", e.target.value)} />
              <div style={{ fontSize: 12, color: "var(--text3)" }}>Variables: {"{name}"} {"{code}"} {"{price}"}</div>
            </div>
          </div>
        </div>

        <button className="btn btn-primary" onClick={handleSave} disabled={saving} style={{ width: "fit-content" }}>
          {saving
            ? <span className="spinner" style={{ width: 16, height: 16, borderWidth: 2 }} />
            : saved ? <><Icon name="check" size={16} /> Saved!</> : <>{t.saveSettings}</>
          }
        </button>
      </div>
    </AdminLayout>
  );
};

// ─────────────────────────────────────────────
// APP ROOT
// ─────────────────────────────────────────────
export default function App() {
  const [lang, setLangRaw] = useState(() => localStorage.getItem("nexus_lang") || "en");
  const [page, setPage] = useState("store");
  const [user, setUser] = useState(() => db.getCurrentUser());
  const [products, setProducts] = useState([]);
  const [categories, setCategories] = useState([]);
  const [settings, setSettings] = useState(MOCK_SETTINGS);
  const t = TRANSLATIONS[lang];

  const setLang = useCallback((l) => {
    setLangRaw(l);
    localStorage.setItem("nexus_lang", l);
  }, []);

  // Real-time subscriptions
  useEffect(() => {
    const unsub1 = db.onProducts(setProducts);
    const unsub2 = db.onCategories(setCategories);
    const unsub3 = db.onSettings(setSettings);
    return () => { unsub1(); unsub2(); unsub3(); };
  }, []);

  // Apply dir to document
  useEffect(() => {
    document.documentElement.dir = t.dir;
    document.documentElement.lang = lang;
  }, [lang, t.dir]);

  const ctx = { lang, setLang, t, page, setPage, user, setUser, products, categories, settings };

  const renderPage = () => {
    switch (page) {
      case "store": return <StorePage />;
      case "login": return <LoginPage />;
      case "stock": return <StockPage />;
      case "products-admin": return <ProductsAdminPage />;
      case "add-product": return <AddProductPage />;
      case "categories": return <CategoriesPage />;
      case "store-settings": return <SettingsPage />;
      default: return <StorePage />;
    }
  };

  return (
    <AppContext.Provider value={ctx}>
      <GlobalStyles />
      {renderPage()}
    </AppContext.Provider>
  );
}
