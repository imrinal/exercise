# PRO-TRACK AUTO ⚡

PRO-TRACK AUTO is a high-performance, single-page application (SPA) fitness engine engineered specifically for rapid execution on mobile devices. It completely eliminates traditional multi-tab layouts in favor of an optimized, state-driven workout execution interface that features dynamic landscape adaptation and automated exercise progression.

🌐 **Live Deployment:** [pro-track-auto.vercel.app](https://pro-track-auto.vercel.app)

---

## ✨ Core Features

* **Adaptive Grid Engine:** Seamlessly transitions between a single-column vertical smartphone layout and a dual-column wide-screen landscape interface (optimized for mobile notches and media-rich displays).
* **Linear Auto-Advance State Machine:** Eliminates manual tracking fatigue. Once you mark an exercise complete, the architecture automatically saves its dataset and buffers the next progressive exercise in the split array.
* **Precision Metabolic Analytics:** Utilizes real-time Metabolic Equivalent of Task (MET) coefficient tracking to calculate precise mechanical work energy expenditure ($6.0\text{ METs}$ active, $1.5\text{ METs}$ rest) computed live against user-supplied body mass metrics.
* **Zero-Overhead Local Assets:** Configured specifically to look for local hardware storage directory paths, resolving third-party cross-origin (CORS) content blockages.
* **OLED Pure Black Interface:** Fully styled using true `#000000` color fields to maximize display power savings and visual focus during exhaustive exercise environments.

---

## 📁 Required Local Storage Directory Setup

To utilize the native media visualization engine, maintain an asset folder containing compressed `.jpeg`/`.jpg` files exactly adjacent to your deployment script:

```text
/Your-Repository-Root
  ├── index.html
  └── /assets
      ├── push-ups.jpeg
      ├── db-floor-press.jpeg
      ├── db-fly.jpeg
      ├── db-shoulder-press.jpeg
      ├── db-lateral-raise.jpeg
      ├── pike-push-ups.jpg
      ├── overhead-triceps.jpeg
      ├── db-kickback.jpeg
      ├── crunches.jpeg
      ├── Reverse-Crunch.jpeg
      ├── db-Rear-Delt-Fly.jpeg
      ├── plnk-Shoulder-tap.jpeg
      ├── goblet-squat.jpeg
      ├── split-squat.jpeg
      ├── db-rdl.jpeg
      ├── db-sumo-squat.jpeg
      ├── glute-bridge.jpeg
      ├── Single-Leg-Glute.jpeg
      ├── calf-raise.jpeg
      ├── bw-squat.jpeg
      ├── dead-bug.jpeg
      ├── walking-lunges.jpeg
      ├── mountain-climbers.jpeg
      ├── high-knees.jpeg
      ├── burpees.jpeg
      └── bicycle-crunches.jpeg
