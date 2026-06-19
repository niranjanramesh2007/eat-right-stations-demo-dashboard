# 🍽️ Eat Right Stations – India | FSSAI Dashboard

An interactive web dashboard showcasing **FSSAI-certified Eat Right Stations** across Indian Railways.

Built as part of a student research project on food safety and hygiene standards at railway stations across India.

---

## 📊 Features

- **Interactive Map** – India choropleth showing Eat Right Stations by state
- **Zone & State Bar Charts** – Distribution of certified stations across railway zones and states, with percentage breakdowns
- **Category Doughnut Chart** – Certification categories (Gold, Silver, Bronze)
- **Live Filters** – Filter by Zone, State, Category, and search by station name
- **Station Data Table** – Detailed sortable list of all certified stations
- **Current Date Badge** – Shows when the dashboard was last updated

---

## 🗂️ Project Structure

```
├── index.html              # Main dashboard (single-file app)
├── assets/
│   ├── eatright_logo.png
│   ├── fssai_logo.jpg
│   ├── fssai_emblem_logo.png
│   ├── fssai_script_logo.png
│   ├── eatright_horizontal_logo.jpg
│   ├── indian-railway-logo-png_seeklogo-390907.png
│   └── india-composite.geojson   # GeoJSON map data
├── excel_verified.json     # Verified stations dataset
├── excel_names.txt         # Raw station names reference
├── stations_list.txt       # Station listing
├── read_xlsx_rows.py       # Data preparation utility script
└── FINAL EAT_RIGHT_STATIONS DATA DRAFT - Copy.xlsx
```

---

## ⚠️ Disclaimer

> The information is based on specific datasets and is subject to periodic updates and data renewal.  
> This is a **student project** created for academic purposes. Data accuracy is not guaranteed and may not reflect the most current certification status.

---

## 🛠️ Tech Stack

- **HTML5 / Vanilla CSS / JavaScript** – No frameworks
- **Chart.js** – Bar, Doughnut charts
- **Leaflet.js** – Interactive India map
- **GeoJSON** – State boundary data

---

## 🚀 Running Locally

Simply open `index.html` in any modern browser, or serve with:

```bash
python -m http.server 8000
```

Then navigate to `http://localhost:8000`

---

*Developed by Niranjan R | FSSAI Eat Right Railways Initiative*
