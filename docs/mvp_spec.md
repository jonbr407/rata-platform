# MVP Specification

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

- [ ]  Feature list is lean but complete enough to test the concept
- [ ]  Highlights what’s out-of-scope until Phase 2
- [ ]  Makes it easy for a dev team to understand
- [ ]  Syncs with long-term strategy
- [ ]  Ready to sync with GitHub → `mvp_spec.md`

---

### ✍️ Current Draft:

## **Rātā MVP Specification**

**Purpose:**

Define what the Minimum Viable Product (MVP) includes at launch, and what is deferred to in later phases.

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
- A view of the map with restricted access but views of trap and toxin placement

---

### 🛑 **Out of Scope (Until Phase 2+) (Adding 3+ too)**

These features are deferred to maintain MVP simplicity, control initial complexity, and ensure the platform is robust before adding advanced integrations:

- AI-driven pest ID or hotspot prediction
- Barcode scanning / OSPRI integration
- Smart trap or remote sensor syncing
- Drone or thermal camera feed integration
- Chat/messaging system
- Researcher / landowner / marketplace logins
- Multi-species filters or detailed tagging
- Ai powered tailgates and feedback system
- Automated text on text off

---

### 🚧 **Future-Proofing (AI-Ready Design)**

The MVP architecture is explicitly designed to support future integration of artificial intelligence tools. In later phases, we plan to incorporate large language models (LLMs) for advanced data summarisation, reporting automation, . Additionally, computer vision models for automated pest identification, work verification, and hotspot prediction will become central to the platform’s long-term capability. This foundational design ensures smooth integration and scalability as Rātā evolves.

---

### 👟 **User Journey (Field Operator)**

1. Open app → Map view, centered on operator
2. Swipe screen → Camera app appears seamlessly, no delay
3. Take photo of trap → Tag it (trap type, status, result)
4. Save → Data is stored locally (offline)
5. Reconnect to signal → Data auto-syncs to central dashboard
6. Base and team sees live map updates of trap checks, locations, hazards added

---

### 📱 **Target Devices**

- Mobile App: Android (priority), iOS (later)
- Dashboard: Tablets, Laptops (Windows/Mac)

---

### 🎯 **How This Proves the Concept**

- Confirms that live mapping and field visibility save time
- Validates reduction in coordination delays
- Demonstrates clear improvement in data accuracy over manual logging methods
- Proves offline-first logging works in remote NZ terrain
- Tests operator ease-of-use vs existing methods
- Delivers immediate value for teams managing contracts

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