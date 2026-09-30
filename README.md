# 🌍 GreenScape AI — GIS-Based Green-Space Optimization System for Urban Heat & Analysis



---

### 🔍 Overview

**GreenScape AI (GEO-Greenspace)** is an advanced GIS-based web platform engineered to analyze urban environmental microclimates, model Urban Heat Island (UHI) effects, and optimize urban green-space distribution for sustainable city planning. 

Rapid urbanization and expanding impervious surfaces create significant temperature differentials in metropolitan areas. This platform combines geospatial data visualization, multi-layer GIS mapping, real-time environmental metrics, and intelligent green-space placement strategies to empower city planners, environmental researchers, and local governments to mitigate urban heat risks, enhance canopy coverage, and build climate-resilient cities.

---

### 🌐 Live Server Status

> 🚀 **The project is running on:**  
> 👉 **Server Link:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
> 📊 **Analytics Dashboard:** [http://127.0.0.1:8000/dashboard.html](http://127.0.0.1:8000/dashboard.html)

---

### ✨ Key Features

- **🗺️ Interactive Multi-Layer GIS Maps**: High-performance geospatial mapping powered by Leaflet.js with dynamic switching between satellite imagery, street topography, and vegetation layers.
- **🔥 Urban Heat Island (UHI) Heatmaps**: Real-time spatial heat density visualization leveraging `leaflet-heat` to pinpoint critical thermal hotspots across urban sectors.
- **🌿 Green-Space & Canopy Optimization**: Interactive simulation tools demonstrating the cooling impact of strategic tree planting, urban parks, and green corridors.
- **📊 Comprehensive Environmental Analytics**: Interactive dashboards with Chart.js visualizing temperature trends, air quality index (AQI), vegetation index (NDVI), and cooling efficiency metrics.
- **📄 Professional PDF Export**: One-click generation of comprehensive environmental planning and heat audit reports using `jsPDF` and `html2canvas`.
- **🎬 Modern Immersive UI**: Fluid GSAP scroll-triggered animations, dynamic video backgrounds, and responsive dark/light themes styled with Tailwind CSS.

---

### ⚙️ Technologies Used

| Category | Technologies |
| :--- | :--- |
| **Frontend Core** | HTML5, CSS3, JavaScript (ES6+) |
| **Styling & Design** | Tailwind CSS, Custom Modern CSS, Inter & Manrope Fonts |
| **GIS & Geospatial** | Leaflet.js, Leaflet Heat Plugin, OpenStreetMap & Satellite Layers |
| **Data Visualization** | Chart.js |
| **Motion & Animation** | GSAP (GreenSock), ScrollTrigger |
| **Document Export** | jsPDF, html2canvas |

---

### 📁 Project Structure

```text
GEO-Greenspace/
│
├── GIS (3)/
│   └── GIS/
│       └── dist/
│           ├── index.html              # Main GIS optimization platform
│           ├── dashboard.html          # Environmental analytics dashboard
│           └── assets/
│               ├── css/
│               │   ├── background.css  # Dynamic ambient background styles
│               │   └── style.css       # Core UI & map styling
│               ├── js/
│               │   ├── animations.js   # GSAP scroll animations & transitions
│               │   ├── background.js   # Ambient particle canvas & lighting
│               │   ├── charts.js       # Chart.js environmental configurations
│               │   ├── main.js         # Core application logic & UI controllers
│               │   └── map.js          # Leaflet GIS mapping & heatmap engine
│               ├── images/
│               │   └── logo.svg        # Platform brand logo
│               └── video/
│                   └── earth.mp4       # Hero background animation
│
├── .gitignore                          # Git ignore configuration
└── README.md                           # Comprehensive project documentation
```

---

### 🚀 How to Run Locally

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/zoyashaikh3/GIS-based-greenspace-optimization-system-for-urban-heat-and-analysis.git
cd GIS-based-greenspace-optimization-system-for-urban-heat-and-analysis
```

#### 2️⃣ Start Local Web Server
You can run the application with Python's built-in HTTP server:

```bash
# Using Python
python -m http.server 8000 --directory "GIS (3)/GIS/dist"
```

Or using Node.js `http-server` / `live-server`:
```bash
# Using npx
npx serve "GIS (3)/GIS/dist" -l 8000
```

#### 3️⃣ Open in Browser
Open your browser and navigate to:
👉 **http://127.0.0.1:8000/**

- Main Platform: `http://127.0.0.1:8000/`
- Analytics Dashboard: `http://127.0.0.1:8000/dashboard.html`

---

### 🧩 How It Works

1. **Geospatial Data Ingestion**: The system loads spatial boundary coordinates and surface temperature datasets across urban districts.
2. **Thermal Analysis & Heat Mapping**: Temperature variances are calculated and rendered as high-resolution heat intensity layers.
3. **Greenery Coverage Assessment**: Canopy coverage metrics are evaluated against recommended urban forestry guidelines.
4. **Optimization Modeling**: Identifies high-priority zones where green-space interventions (pocket parks, street canopies, green roofs) achieve the greatest temperature reduction.
5. **Reporting**: Urban planners can analyze live graphs and export decision-ready PDF dossiers.

---

### 📜 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute.
