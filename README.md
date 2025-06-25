# 🎵 Real-Time Audio Visualizer Toolkit

This repository showcases two audio visualizer tools developed by **Worachat W., Ph.D. (2025) :

1. 🎧 **Web-Based Audio Visualizer** (HTML5 + React + Tailwind CSS)
2. 🧪 **Real-Time Spectrogram & Waveform Analyzer** in **Python (Google Colab)


## 📁 Contents

### 1. 🔊 Web-Based Audio Visualizer (HTML5 + React)

A drag-and-drop audio visualizer using the Web Audio API, HTML5 Canvas, and a modern React front end styled with Tailwind CSS.

#### 🔧 Features
- Drag & drop or select audio files
- Real-time animated spectrum bars
- Responsive UI with Tailwind CSS
- Compatible with modern browsers
- Visual updates using `requestAnimationFrame`
- No back-end needed — runs entirely client-side

#### 🔗 Live Demo
Coming soon (host it on GitHub Pages or Vercel)

#### 📄 Usage
Open the `index.html` in your browser or deploy the HTML file online.

```bash
git clone https://github.com/your-username/audio-visualizer.git
cd audio-visualizer
open index.html  # or deploy it on your web server
````

---

### 2. 📊 Real-Time Audio Spectrogram & Waveform (Python + Matplotlib)

This Colab-compatible script visualizes both the **waveform** and **spectrogram** of an uploaded WAV file in real-time.

#### 🧪 Dependencies

* `numpy`
* `matplotlib`
* `IPython`
* `pydub` (optional for more formats)

#### ▶️ How It Works

* Upload a `.wav` file
* The script performs STFT on chunks of the waveform
* It animates the waveform and FFT spectrum live using `matplotlib.animation`

#### 📄 Usage in Google Colab

```python
# Open in Google Colab and run cell-by-cell
https://colab.research.google.com/...
```

#### 🖼️ Visualization Output

* Top plot: Audio waveform over time
* Bottom plot: Rolling FFT-based spectrogram using `imshow`

---

## 📌 Credits

Developed by:

**Worachat Wannawong, Ph.D.**
NutriCious Co., Ltd., Bangkok, Thailand
`Audio API Showcase 2025`

---

## 📜 License

MIT License – feel free to use, modify, and share!

