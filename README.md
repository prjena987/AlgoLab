# ⬡ AlgoLab — Algorithm & Data Structure Visualizer

> An interactive, step-by-step algorithm visualization platform built with vanilla JavaScript and HTML5 Canvas.

🔗 **Live Demo:** [prjena987.github.io/AlgoLab](https://prjena987.github.io/AlgoLab)

---

## ✨ Features

AlgoLab has 4 interactive tabs, each focused on a different area of algorithms and data structures.

### ⬡ Tab 1 — Heap Lab

- Build **Max Heap** and **Min Heap** from scratch
- Animate **Insert**, **Extract Root**, **Peek**, and **Change Key** operations
- Real-time **binary tree visualization** on HTML5 Canvas
- Step-by-step log explaining every swap and comparison
- O(n) **Build Heap** from a custom array

### ↕ Tab 2 — Sorting Lab

- **Heap Sort** — animated heapify phases with pivot highlighting
- **Selection Sort** — shows minimum scanning pass by pass
- **Merge Sort** — divide and conquer with merge animation
- Live **comparison** and **swap** counters
- Adjustable animation speed (1x → 5x)

### 🔍 Tab 3 — Kth Element & Priority Queue

- Find **Kth Smallest / Largest** element with animated array highlighting
- Two approaches: **Heap O(n log k)** and **Sort O(n log n)**
- Full **Max Priority Queue** simulation with insert, extract max and peek
- Priority-ranked display with live operation log

### ◎ Tab 4 — Complexity Dashboard

- Interactive **Big O Growth Curves** — toggle O(1), O(log n), O(n), O(n log n), O(n²), O(2ⁿ)
- **Live Benchmark** — measures real comparisons, swaps and execution time in ms
- **Comparison Count Meters** — visualize theoretical operation counts for any N
- Complete **algorithm comparison table** with best/avg/worst case and space complexity

---

## 🛠️ Tech Stack

| Technology         | Usage                                            |
| ------------------ | ------------------------------------------------ |
| HTML5              | Structure and layout                             |
| CSS3               | Neon dark theme, animations, responsive grid     |
| Vanilla JavaScript | All algorithm logic and animations               |
| HTML5 Canvas API   | Binary tree visualization and growth curve chart |
| Google Fonts       | JetBrains Mono + Outfit                          |

> No frameworks. No libraries. No build tools. Pure HTML/CSS/JS.

---

## 🚀 Run Locally

No installation needed.

```bash
git clone https://github.com/prjena987/AlgoLab.git
cd AlgoLab
# Open index.html in your browser
```

Or just double-click `index.html` to open it directly.

---

## 📸 Preview

| Heap Lab                            | Sorting Lab                                 |
| ----------------------------------- | ------------------------------------------- |
| Animated binary tree with neon glow | Real-time bar chart with color coded states |

| Kth Element                                     | Complexity Dashboard                   |
| ----------------------------------------------- | -------------------------------------- |
| Animated array highlighting with result display | Live Big O growth curves and benchmark |

---

## 📚 Algorithms Covered

| Algorithm          | Time Complexity      | Space | Stable |
| ------------------ | -------------------- | ----- | ------ |
| Heap Sort          | O(n log n) all cases | O(1)  | ✗      |
| Selection Sort     | O(n²) all cases      | O(1)  | ✗      |
| Merge Sort         | O(n log n) all cases | O(n)  | ✓      |
| Kth Element (Heap) | O(n log k)           | O(k)  | —      |
| Heap Insert        | O(log n)             | O(1)  | —      |
| Build Heap         | O(n)                 | O(1)  | —      |
| Extract Max        | O(log n)             | O(1)  | —      |

---

## 🎨 Design

- **Dark navy** background (`#080b18`) with animated grid overlay
- **Neon accents** — Cyan, Pink, Purple, Green, Yellow per tab
- Glowing orb backgrounds with CSS animations
- HTML5 Canvas for tree rendering and growth curves
- Fully **responsive** — works on mobile and desktop

---

## 👨‍💻 Author

**Prjena987**

- GitHub: [@prjena987](https://github.com/prjena987)

---

## 📄 License

MIT License — free to use and modify.
