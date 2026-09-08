# SocioSolve — Societal Challenges & Innovation Platform
### **Grassroots Problem Resolution & University-Industry Innovation Exchange**

> **Vision:** A collaborative platform where citizens report local community problems (rural & urban), engineering universities adopt them for accredited R&D and capstone projects, and industry sponsors prototype development through CSR funding.

---

## 🌟 Pitch to Evaluators & Judges (Why SocioSolve Wins)

1. **Solves the Grassroots Disconnect**:
   - Millions of local civic challenges (e.g. uncollected village waste, water fluorosis, post-harvest crop rot) currently lack engineering interventions.
   - Millions of engineering students build theoretical, repetitive final-year projects without real-world community impact.
   - **SocioSolve bridges this gap directly**, turning validated citizen complaints into accredited academic capstones and corporate CSR investments.
2. **End-to-End Tri-Party Lifecycle**:
   - 👨‍🌾 **Citizens**: Fast geo-tagged reporting with photo evidence, public tracking ticket (`SS-2026-101`), and transparent status updates.
   - 🎓 **Universities & Students**: Verified problem statements, branch categorization (Environmental, Mechanical, Civil, IoT), faculty mentorship, and transparent milestone tracking.
   - 🏢 **Industry / CSR Wings**: Section 135 compliant CSR deployment with verified milestone-linked fund disbursement.
   - 🏛️ **Government & Municipal Administration**: Real-time hotspot heatmaps, bottleneck alerts, and resolution audit trails.

---

## 🚀 Live Demo Walkthrough (The "XYZ Village Garbage" Showcase)

1. **Citizen Perspective (Village Reporting)**:
   - Open **Citizen Hub**.
   - Review the priority case: **"Garbage not collected for 5 days near Village Square & School" in XYZ Village, Pune**.
   - Click **"Submit Your Village Challenge"** & click **"⚡ Autofill XYZ Village Garbage"** to show instant geotagging, photo preview, and ticket generation (`SS-2026-101`).
   - Use the **Track Ticket** search bar with `SS-2026-101` or `XYZ Village` to demonstrate real-time public transparency.

2. **University R&D Perspective (Academic Capstone Adoption)**:
   - Click the **"University R&D"** tab in the top navigation.
   - Show how engineering students from **COEP Technological University** adopted the XYZ Village challenge.
   - View their proposed solution: *“Solar-Assisted Micro Bio-Composter (100 kg/day) & Low-Cost Waste Segregator”*.
   - Click on the milestones to toggle progress (e.g., *Site Inspection Done*, *CAD Design Done*, *Prototype Fabrication*). Watch the progress bar dynamically advance to 65%!

3. **Industry CSR Perspective (Funding & Mentorship)**:
   - Switch to **"Industry CSR"** tab.
   - Demonstrate how **Tata Motors CSR Wing** pledged ₹1,50,000 for fabrication grants and assigned a senior mechanical mentor.
   - Test pledging additional CSR funds using the **"Sponsor / Grant"** button.

4. **Executive Impact Map & Analytics**:
   - Switch to **"Impact Map & KPIs"**.
   - View the interactive India GIS Map with status pins (Red for Reported, Purple for University Adopted, Green for CSR Sponsored, Teal for Resolved).
   - Show the dynamic KPI counters (Total Reported, Active University Projects, ₹9.5 Lakhs CSR Pledged, 4,800+ Citizens Impacted).

---

## 💻 Tech Stack & Architecture

- **Backend**: Python 3.13, Flask RESTful API
- **Database**: SQLite3 (`samadhan.db`) with relational integrity and cascade updates
- **Frontend**: Responsive Single Page App (SPA) using HTML5, Tailwind CSS, FontAwesome 6
- **GIS Mapping**: Leaflet.js with OpenStreetMap layers & custom pin markers
- **Data Visualization**: Chart.js (Doughnut & Bar charts)
- **Zero Heavy Setup**: Standalone, no Node.js/npm or external server dependencies needed!

---

## 🏃 Running the Application

### Option 1: One-Click Batch File (Windows)
Double-click `run.bat` in this folder.

### Option 2: Terminal Command
```bash
python database.py
python app.py
```
Open **http://localhost:5000** in your web browser.
