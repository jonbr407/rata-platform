### ✅ **In Scope – MVP Features**

### 📱 Mobile Field App (Offline-First)

- Photo-based data capture (traps, signs, bait stations)
- GPS geotagging and timestamping
- Quick-entry tags: trap type, bait used, result/status
- Offline-first design; data syncs once back in coverage
- UI inspired by Snapchat: swipe-based, minimal training overhead

### 🗺️ Shared Topographic Map

- Displays trap locations and operator movement in real time
- Smooth map interaction modelled on Google Earth
- High-res terrain tiles preloaded for offline navigation
- Shared map visibility to support situational awareness in the field

### 💻 Game-Engine Central Dashboard

- Visualises operator activity and trap data in 2D/3D map views
- Real-time hotspot flagging using basic logic (non-AI)
- Designed for operations leads, clients and landowners (with restrictions)
- Lightweight engine allows performance on standard laptops

### 🧾 Client Reporting Panel

- Secure login access for clients
- Summary dashboard: job progress, trap coverage, daily or weekly updates
- Downloadable exports (CSV, GPX) for reporting and compliance
- Map-based interface with restricted views to preserve privacy

---

### 🛑 Out of Scope (Deferred to Phase 2+)

To maintain build velocity and validate core functionality, the following are excluded from the MVP:

- AI-powered pest identification or hotspot prediction
- Barcode scanning (e.g. OSPRI integration)
- Smart trap / remote device syncing
- Drone / thermal image data integration
- Internal messaging or team chat
- Researcher, landowner, or marketplace logins
- Multi-species filters or custom tagging taxonomies
- AI-powered safety briefings or feedback systems
- Automated text-in / text-out coordination

---

### 🧠 Future-Proofing: AI-Ready by Design

The MVP is engineered with future AI integration in mind. Core infrastructure supports later adoption of:

- **Large Language Models**: for auto-report generation, QA summaries, and team feedback
- **Computer Vision Models**: for trap verification, pest ID, image scoring, and automated hotspot detection

This ensures that Rātā evolves with the tools that will define the future of field operations—first in pest control, and eventually across other remote field industries.

---

### 👟 Field Operator User Journey

1. Open app → Map opens, centered on current location
2. Swipe into camera mode → Capture image of trap
3. Tag → Enter trap type, bait used, result
4. Save → Stored offline until coverage is restored
5. Sync → Data uploads and updates the central map automatically
6. Command sees → Real-time updates of trap work, locations, and hazards

---

### 📱 Target Devices

- **Mobile App**: Android (priority), iOS (secondary)
- **Dashboard**: Laptop (Windows/Mac)
- **Map Layers**: Designed to run on standard laptops

---

### 🎯 Proof of Concept – What MVP Validates

- That offline-first logging works reliably in remote NZ conditions
- That field visibility via live maps reduces communication delays
- That photo-based data logging is as fast as current data logging
- That operators find the system more intuitive than legacy tools
- That centralised data improves planning and performance monitoring
- That clients gain immediate operational transparency
- That operational admin overhead can be reduced—even as field scale increases