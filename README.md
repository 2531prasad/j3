# Jhanvi Enterprises — B2B Industrial Perimeter Security & Structural Steel Portal

A high-performance, zero-dependency B2B web portal built for **Jhanvi Enterprises** (Hyderabad, India). Designed with an industrial slate engineering aesthetic (inspired by global benchmarks like *Betafence*), the platform showcases physical perimeter security systems, crash-rated vehicle barriers, active electrification, automated access gates, precast concrete Jersey barriers, and structural steel fabrication.

---

## 🏗️ Architectural Overview & Technical Stack

- **Zero-Dependency Static Architecture**: Pure HTML5, Vanilla JavaScript (ES6+), and Tailwind CSS (via CDN) — no Node.js build steps, Webpack, or npm dependencies required.
- **Single Source of Truth**: Dynamic catalog filtering and product specification hydration powered by `js/products-data.js` and `data/products.json`.
- **B2B Lead & RFQ Engine**: Omnichannel lead generation supporting pre-filled direct WhatsApp payloads (`+91 8328014122`) and official RFC/quotation emails (`info@jhanvienterprises.co.in`).
- **Responsive & Mobile-Optimized**: Custom hardware-accelerated touch swipe handling, momentum-aware carousel auto-scroll, mobile drawer navigation, and input zoom prevention.
- **Enterprise Design System**:
  - Industrial Dark Slate (`#0B0F17`, `#111726`, `#182235`, `#233149`)
  - Accent Colorways: Brand Emerald (`#22C55E`), Security Red (`#EF4444`), Technical Blue (`#3B82F6`)
  - Technical Typography: `Inter` for UI & `JetBrains Mono` for engineering specifications and badges.

---

## 📁 Project Directory Structure

```text
website/
├── assets/
│   ├── docs/
│   │   └── Where Quality Meets Security, We Fence. Jhanvi Enterprises (Profile)-1.pdf  # 19-Page Company Profile TDS
│   └── images/
│       ├── Anti-Climb High Security Mesh.webp            # Hero Pillar 2 (Square focus)
│       ├── K-4 Crash Rated Anti-Ram Fence .webp          # Hero Pillar 1 (Square focus)
│       ├── Structural Steel Fabrication & Erection.webp  # Hero Pillar 3 (Square focus)
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
│       ├── logo2.png                                     # Jhanvi Enterprises official brand logo
│       ├── ppgi_sheet_fencing_installed.webp             # PPGI corrugated sheet boundary
│       ├── precast_jersey_barrier_single.webp            # Modular precast concrete block
│       ├── precast_jersey_barriers_stack.webp            # Factory-cast Jersey barriers stack
│       ├── sliding_automated_gate.webp                   # Heavy automated industrial sliding gate
│       ├── structural_steel_erection_2.webp              # Crane site assembly & erection
│       ├── structural_steel_fabrication_1.webp           # PEB columns & heavy fabrication yard
│       └── swing_security_gate.webp                      # Heavy dual-leaf automated swing gate
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
| **Home** | [`index.html`](index.html) | • Full-width expansive sticky header with direct PDF brochure download.<br>• 3-Pillar Flagship Hero (K-4 Red, 358 Blue centered, Steel Green).<br>• 12-Client dual-track infinite marquee (*Amazon, Tata Projects, etc.*).<br>• Momentum-aware auto-scrolling solutions carousel.<br>• Sector application matrix & technical spec comparison table.<br>• Instant WhatsApp / Email RFQ lead submission form. |
| **Catalog** | [`products.html`](products.html) | • Live client-side category filtering (Welded Mesh, Crash Rated, Active Electronics, Gates, Structural Steel).<br>• Dynamic spec preview cards linked to deep specification pages. |
| **Product Detail** | [`product-detail.html?id=...`](product-detail.html) | • Parametric data hydration based on `?id=<product_id>`.<br>• Interactive thumbnail gallery switcher.<br>• Tabular engineering specifications matrix (mesh pitch, wire gauge, coatings, ratings).<br>• Context-aware prefilled quotation engine. |
| **Contact** | [`contact.html`](contact.html) | • Hyderabad HQ coordinates (*Plot No 942, Asbestos Colony, Kukatpally, Hyderabad - 500072*).<br>• Interactive inquiry form with direct WhatsApp business routing (`+91 8328014122`). |

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

## 🌐 Deployment Instructions

Because this project is built with **pure static HTML, JS, and CSS**, it can be hosted instantly on any static web server or CDN with zero build steps:

### Option 1: Cloudflare Pages / Vercel / Netlify
1. Connect this repository to **Cloudflare Pages**, **Vercel**, or **Netlify**.
2. Set the **Root Directory** to `website/` (or repository root).
3. Leave **Build Command** blank (or `echo "Ready"`).
4. Set **Output Directory** to `.`.
5. Deploy.

### Option 2: GitHub Pages
1. Push to your GitHub repository.
2. Navigate to **Settings > Pages**.
3. Under **Branch**, select `main` (or your default branch) and folder `/` (or `/website`).
4. Click **Save**.

### Option 3: Local Development / Testing
You can serve the directory using any local HTTP server:
```bash
# Using Python 3:
cd website
python3 -m http.server 8080

# Using Node.js (npx):
npx serve .
```
Then open `http://localhost:8080` in your web browser.

---

## 📞 Corporate Contact

- **Company**: Jhanvi Enterprises
- **Head Office**: Plot No 942, Asbestos Colony, Kukatpally, Ranga Reddy, Hyderabad, Telangana - 500072, India
- **Phone / WhatsApp**: [+91 8328014122](https://wa.me/918328014122)
- **Official Email**: [info@jhanvienterprises.co.in](mailto:info@jhanvienterprises.co.in)
- **Official Tagline**: *"Where Quality Meets Security, We Fence."*
