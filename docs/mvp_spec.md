## 🔖 Assignment Note – MVP Specification

**🧭 Purpose:**

Define what the Minimum Viable Product (MVP) includes at launch, and what it does *not* include.

---

### 💡 Focus Points:

- What are the **essential features** for MVP?
- What’s the user journey like (especially field operators)?
- What gets deferred to future phases?
- What devices is it for (phone, tablet, web)?
- How does this MVP prove the concept?

---

### ✅ Writing Checklist:

- [x]  Feature list is lean but complete enough to test the concept
- [x]  Highlights what’s out-of-scope until Phase 2
- [x]  Makes it easy for a dev team to understand
- [x]  Syncs with long-term strategy
- [x]  Ready to sync with GitHub → `mvp_spec.md`

---

### ✍️ Final Draft:

## 🔖 **Rātā MVP Specification**

**🧭 Purpose:**

Define what the Minimum Viable Product (MVP) includes at launch, and what is deferred to later phases.

---

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

### 💻 Game-Engine Command Dashboard

- Visualises operator activity and trap data in 2D/3D map views
- Real-time hotspot flagging using basic logic (non-AI)
- Designed for operations leads and team coordination
- Lightweight engine allows performance on standard laptops

### 🧾 Client Reporting Panel

- Secure login access for clients and managers
- Summary dashboard: job progress, trap coverage, daily photos
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

This ensures that Rātā evolves with the tools that will define the future of field operations.

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
- **Dashboard**: Tablet or Laptop (Windows/Mac)
- **Map Layers**: Designed to run on standard GPU-equipped field laptops

---

### 🎯 Proof of Concept – What MVP Validates

- That offline-first logging works reliably in remote NZ conditions
- That field visibility via live maps reduces communication delays
- That photo-based logging is faster, more accurate than manual methods
- That operators find the system faster to learn than legacy tools
- That centralised data improves planning and performance monitoring
- That clients gain immediate operational transparency

### ✍️ First Draft:

## 🔖 **Rātā MVP Specification**

**Purpose:**

Define what the Minimum Viable Product (MVP) includes at launch, and what is deferred to later phases.

---

### ✅ **In Scope – MVP Features**

### 📱 **Mobile Field App (Offline-First)**

- Photo-based data capture (traps, signs, bait stations)
- GPS geotagging + timestamping of each photo
- Quick entry tags: trap type, bait used, status
- Works fully offline; syncs data when back in range
- UI modelled on Snapchat for speed and familiarity

### 🗺️ **Shared Topographic Map**

- Displays trap icons + operator locations
- Smooth interaction modeled after Google Earth
- High-res base layers, optimized for rural terrain
- Works offline using preloaded zones

### 💻 **Game-Engine Command Dashboard**

- Visualises operator movements + trap data
- Map view (2D or lightweight 3D)
- Highlights potential pest “hotspots” based on basic logic
- Supports real-time field coordination

### 🧾 **Client Reporting Panel**

- Secure login access
- Downloadable summaries (CSV, GPX)
- High-level job stats: trap effectiveness, daily progress, coverage

---

### 🛑 **Out of Scope (Until Phase 2+)**

- AI-driven pest ID or hotspot prediction
- Barcode scanning / OSPRI integration
- Smart trap or remote sensor syncing
- Drone or thermal camera feed integration
- Chat/messaging system
- Researcher / landowner / marketplace logins
- Multi-species filters or detailed tagging
- AI-driven assistance tools

---

### 👟 **User Journey (Field Operator)**

1. Open app → Start “New Check”
2. Take photo of trap → Tag it (bait, type, result)
3. Save → Data is stored locally (offline)
4. Reconnect to signal → Data auto-syncs to central dashboard
5. Base team sees live map updates + photos

---

### 📱 **Target Devices**

- Mobile App: Android (priority), iOS (optional)
- Dashboard: Tablets, Laptops (Windows/Mac)

---

### 🎯 **How This Proves the Concept**

- Confirms that live mapping and field visibility save time
- Proves offline-first logging works in remote NZ terrain
- Tests operator ease-of-use vs existing methods
- Delivers immediate value for teams managing contracts

---