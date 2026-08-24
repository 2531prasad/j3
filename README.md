# Industrial Physical Perimeter Security & Structural Steel B2B Portal

A high-performance, production-ready B2B web portal engineered for enterprise physical perimeter protection, crash-rated hostile vehicle mitigation (HVM), active electrification, automated access gates, precast concrete Jersey barriers, and heavy structural steel fabrication.

Designed with an industrial dark slate engineering aesthetic inspired by global benchmarks (*Betafence*), the platform provides specifiers, EPC contractors, defence procurers, and infrastructure architects with parametric technical data sheets, elevation details, and streamlined RFQ quotation pathways.

---

## 🏗️ Architectural Overview & Technical Stack

- **Production-Optimized Static Architecture**: Pure HTML5, Vanilla JavaScript (ES6+), compiled minified Tailwind CSS (`css/style.min.css` @ 27 KB), and pruned Google Web Fonts — zero runtime compiler overhead.
- **Single Source of Truth**: Dynamic catalog filtering and product specification hydration powered by `js/products-data.js` and `data/products.json`.
- **Parametric Data Hydration**: Product detail pages dynamically render technical specifications, material coatings, testing certifications, and interactive photo galleries from query parameters (`?id=<product_id>`).
- **Hardware-Accelerated Touch & Mobile UX**: Custom touch swipe physics, momentum-aware carousel scrolling, IntersectionObserver CPU optimization, and input zoom prevention on iOS/Android.
- **Enterprise Design System**:
  - Industrial Dark Slate Palette (`#0B0F17`, `#111726`, `#182235`, `#233149`)
  - Semantic Color Coding: Brand Emerald (`#22C55E`), Security Red (`#EF4444`), Technical Blue (`#3B82F6`)
  - Typography: `Inter` for interface readability & `JetBrains Mono` for engineering metrics, tolerances, and badges.

---

## 📁 Project Directory Structure

```text
website/
├── assets/
│   ├── docs/
│   │   └── jhanvi-enterprises-technical-spec-2026.pdf  # 19-Page Company Profile TDS
│   └── images/
│       ├── anti-climb-high-security-mesh.webp            # Hero Pillar 2 (Square focus)
│       ├── k4-crash-rated-anti-ram-fence.webp          # Hero Pillar 1 (Square focus)
│       ├── structural-steel-fabrication-erection-hero.webp  # Hero Pillar 3 (Square focus)
│       ├── anti_climb_358_installed.webp                 # 358 Anti-Climb site installation
│       ├── anti_climb_panel_detail_1.webp                # 358 Finger/toe proof aperture macro
│       ├── anti_climb_panel_detail_2.webp                # 358 Bolt-cutter delay test
│       ├── anti_climb_panel_green.webp                   # 358 RAL green coated panel
│       ├── brc_bell_post_fence_installed.webp            # BRC Roll-top boundary installation
│       ├── brc_unico_prima_installation.webp             # UNICO Prima slot-in post fitment
│       ├── brc_unico_prima_mesh_zoom.webp                # 200x50mm mesh pattern close-up
│       ├── brc_unico_prima_post_detail.webp              # Fixtureless Bell Post lock channel
│       ├── cantilever_heavy_duty_gate.webp               # Industrial trackless cantilever gate
│       ├── client_logo_01.webp to client_logo_12.webp   # Enterprise client trust logos
│       ├── company_mission_about_fence.webp              # Mission craftsmanship backdrop
│       ├── contact_us_fencing_backdrop.webp              # Contact facility hero image
│       ├── d5_evo_gate_motor_banner.webp                 # Centurion D5-Evo motor banner
│       ├── d5_evo_gate_motor_product.webp                # D5-Evo motor unit & LCD controller
│       ├── electric_perimeter_fence.webp                 # Multi-strand active electric fence
│       ├── gate_safety_flash_light.webp                  # Industrial strobe safety beacon
│       ├── gate_safety_photocells.webp                   # Anti-crush infrared optical beams
│       ├── h_post_detail_1.webp                          # H-channel steel profile detail
│       ├── h_post_detail_2.webp                          # Smart U-clamp corner execution
│       ├── h_post_fence_installed.webp                   # H-Post modular fence installation
│       ├── h_post_spec_diagram.webp                      # H-Post technical elevation drawing
│       ├── k4_rated_high_security_fence.webp             # ASTM F2656 anti-ram barrier
│       ├── logo2.png                                     # Official brand logo
│       ├── ppgi_sheet_fencing_installed.webp             # PPGI corrugated sheet boundary
│       ├── precast_jersey_barrier_single.webp            # Modular precast concrete block
│       ├── precast_jersey_barriers_stack.webp            # Factory-cast Jersey barriers stack
│       ├── sliding_automated_gate.webp                   # Heavy automated industrial sliding gate
│       ├── structural_steel_erection_2.webp              # Crane site assembly & erection
│       ├── structural_steel_fabrication_1.webp           # PEB columns & heavy fabrication yard
│       └── swing_security_gate.webp                      # Heavy dual-leaf automated swing gate
├── css/
│   └── style.min.css                                     # Production compiled minified Tailwind CSS (27 KB)
├── data/
│   └── products.json                                     # Master JSON product catalog data
├── js/
│   └── products-data.js                                  # Client-side catalog model & specs
├── index.html                                            # Flagship Homepage with 3-pillar hero & RFQ
├── products.html                                         # Filterable Technical Products Catalog
├── product-detail.html                                   # Deep Parametric Spec Sheet & CAD Viewer
├── contact.html                                          # Technical Consultation & RFQ Engine
└── README.md                                             # Project documentation
```

---

## 🚀 Page Guide & Functional Features

| Page | URL Route | Core Modules & Interactions |
| :--- | :--- | :--- |
| **Home** | [`index.html`](index.html) | • Expansive full-width sticky navigation with one-click TDS brochure download.<br>• 3-Pillar Flagship Hero (K-4 Crash Barrier, 358 Anti-Climb Mesh centered, Structural Steel).<br>• 12-Client dual-track infinite marquee showcasing enterprise credentials.<br>• Momentum-aware auto-scrolling solutions carousel with IntersectionObserver.<br>• Sector application matrix & technical spec comparison table.<br>• Instant omnichannel RFQ quotation engine. |
| **Catalog** | [`products.html`](products.html) | • Live client-side category filtering (Welded Mesh, Crash Rated, Active Electronics, Gates, Structural Steel).<br>• Dynamic spec preview cards linked to deep specification pages. |
| **Product Detail** | [`product-detail.html?id=...`](product-detail.html) | • Parametric data hydration based on `?id=<product_id>`.<br>• Interactive thumbnail gallery switcher.<br>• Tabular engineering specifications matrix (mesh pitch, wire gauge, coatings, ratings).<br>• Context-aware prefilled quotation engine. |
| **Contact** | [`contact.html`](contact.html) | • Technical consultation form.<br>• Multi-channel quote dispatch with pre-formatted technical project details. |

---

## 🛡️ Product Portfolio & Specifications

1. **358 Anti-Climb High Security Mesh**: 76.2 × 12.7 mm aperture, 4.0mm high-tensile core wire, finger/toe-proof, bolt-cutter resistant, CCTV optical clarity.
2. **BRC / Bell Post Weldmesh (UNICO Prima)**: 200 × 50 mm roll-top geometry with fixtureless slot-and-lock posts (zero loose bolts, zero onsite welding).
3. **H-Post Universal Modular System**: Heavy H-channel steel profile with Smart U-clamps for seamless 90° corner runs and razor concertina toppings.
4. **K-4 Crash Rated Anti-Ram Fence**: ASTM F2656 / DOS K-4 certified impact barrier stopping 15,000 lbs (6,800 kg) vehicles at 30 mph (48 km/h).
5. **Active Power Electric Fence**: IEC 60335 compliant non-lethal pulsed shock deterrent with multi-zone CMS/SCADA telemetry.
6. **Industrial Automated Gates & Centurion Motors**: Trackless cantilever and sliding gates powered by Centurion D5-Evo drives (500kg capacity, battery backup, infrared safety beams).
7. **Structural Steel Fabrication & Erection**: End-to-end industrial PEB columns, beams, platforms, and turnkey crane site erection.
8. **Precast Concrete Jersey Barriers & PPGI Barricading**: Factory-cast high-strength modular crash barriers with integrated fence topping sockets.

---

## ⚡ Performance & Core Web Vitals Optimization

The portal is optimized for Google Core Web Vitals (CWV) compliance and sub-second paint times on mobile 4G networks:

| Optimization Area | Implementation Detail | Performance Benefit |
| :--- | :--- | :--- |
| **CSS Delivery** | Replaced 350 KB runtime Tailwind CDN with a static 27 KB minified stylesheet (`css/style.min.css`). | **FCP**: Instant render without DOM parsing lag. |
| **Image Compression** | Downsampled and compressed all 44 visuals using WebP format; reduced hero visuals from 5.6 MB to ~655 KB. | **LCP**: 88%+ reduction in above-the-fold transfer payload. |
| **Media Deferral** | Added native `loading="lazy"` and `decoding="async"` to all below-the-fold carousel, marquee, and backdrop images. | **Network Saturation**: Eliminated initial connection contention. |
| **IntersectionObserver** | Bound the continuous carousel auto-scroll animation loop to viewport visibility. | **INP / CPU**: Zero main-thread overhead when carousel is off-screen. |
| **Font Payload** | Pruned Google Fonts from 11 weights down to essential weights (`Inter: 400,500,600,700,800` & `Mono: 400,600`). | **FOIT / FOUT**: Faster font swap and fewer roundtrips. |
| **CLS Stability** | Explicit `width` and `height` dimensions declared on image containers. | **CLS**: Zero layout shifts during asset streaming. |

---

## ⚙️ Development & Maintenance Workflow

### 1. Adding or Modifying Products
All product definitions are stored in [`js/products-data.js`](js/products-data.js) and mirrored in [`data/products.json`](data/products.json).
To add a new product or modify technical specifications:
1. Open `js/products-data.js`.
2. Add or update the product entry under the appropriate category object with `id`, `name`, `badge`, `tagline`, `image`, `secondary_images`, `overview`, `specifications`, `key_features`, and `applications`.
3. The catalog (`products.html`) and specification sheet (`product-detail.html?id=your-id`) will update automatically.

### 2. Recompiling Tailwind CSS (When Adding New Utility Classes)
If you add new Tailwind utility classes to HTML markup:
```bash
# From within the website/ directory:
npx tailwindcss -i ./css/input.css -o ./css/style.min.css --minify
```

### 3. Image Optimization Guidelines
- Use modern **WebP** format for all photographic assets.
- Keep hero visuals $\le 1200px$ width at quality 75–80.
- Keep catalog card thumbnails $\le 600px$ width at quality 75–80.
- Always include `loading="lazy"` and `decoding="async"` for below-the-fold images.

---

## 🌐 Deployment Instructions

Because this project is built with **pure static HTML, JS, and CSS**, it can be hosted on any static web server or CDN with zero build steps:

### Option 1: Cloudflare Pages / Vercel / Netlify
1. Connect this repository to **Cloudflare Pages**, **Vercel**, or **Netlify**.
2. Set the **Root Directory** to `website/` (or repository root).
3. Leave **Build Command** blank (or `echo "Ready"`).
4. Set **Output Directory** to `.`.
5. Deploy.

### Option 2: GitHub Pages
1. Push to your GitHub repository.
2. Navigate to **Settings > Pages**.
3. Under **Branch**, select `main` (or default branch) and folder `/` (or `/website`).
4. Click **Save**.

### Option 3: Local Development Server
```bash
# Using Python 3:
cd website
python3 -m http.server 8080

# Using Node.js (npx):
npx serve .
```
Open `http://localhost:8080` in your web browser.

---

## 🔒 Security & Browser Compatibility

- **Content Security Policy (CSP) Ready**: No inline scripts requiring `eval()`; safe for strict CSP headers.
- **Cross-Browser Tested**: Full support for Chrome, Safari (macOS & iOS), Edge, Firefox, and Chromium mobile browsers.
- **Zero Third-Party Tracking**: Fully self-contained static assets without telemetry or third-party trackers.
