# SoundGen / 声音发生器

[English](#english) | [中文](#chinese)

---

## English

### Overview
**SoundGen** is a lightweight web-based audio signal generator built with the Web Audio API. It allows you to generate various waveforms, adjust frequency, volume, and stereo panning, and visualize the real‑time waveform. The interface is responsive and works on both desktop and mobile devices.

### Features
- **Waveform selection**: Sine, square, sawtooth, triangle, and white noise.
- **Frequency control**: 0 – 20,000 Hz, adjustable via slider or numeric input.
- **Volume control**: 0% – 100%.
- **Stereo panning**: Balance between left and right channels with preset buttons (Left / Center / Right).
- **Real‑time waveform display**: Shows the actual output when playing; when paused, a preview of the selected waveform (scaled by volume and pan) is drawn.
- **Play / Stop** button to start or suspend audio.
- **Responsive design**: Optimized for mobile screens (touch‑friendly sliders, stacked layout).

### Technology
- HTML5, CSS3, JavaScript (ES6)
- Web Audio API (`AudioContext`, `OscillatorNode`, `GainNode`, `StereoPannerNode`, `AnalyserNode`)
- Canvas for waveform visualization

### How to Use
1. Open [website](majiangla.github.io/SoundGen) in any modern browser (Chrome, Firefox, Edge, Safari).
2. Click the **Start** button to begin audio playback.
3. Choose a waveform, adjust frequency, volume, and panning.
4. The waveform display updates in real time.
5. Click **Stop** to pause (the context is suspended, not destroyed).

### Links
- [Bilibili](https://space.bilibili.com/1431497051)
- [GitHub Repository](https://github.com/majiangla/SoundGen)


---

## Chinese

### 项目简介
**声音发生器** 是一个基于 Web Audio API 的轻量级音频信号发生器。它可以生成多种波形，调节频率、音量、立体声平衡，并实时显示波形。界面采用响应式设计，支持桌面端和移动端。

### 功能特点
- **波形选择**：正弦波、方波、锯齿波、三角波、白噪声。
- **频率控制**：0 – 20000 Hz，可通过滑块或数字输入调节。
- **音量控制**：0% – 100%。
- **立体声平衡**：左右声道平衡调节，并提供左/中/右预设按钮。
- **实时波形显示**：播放时显示实际输出波形；暂停时根据当前波形、音量和平衡绘制预览波形。
- **开始/停止**按钮：控制音频的播放与暂停。
- **响应式设计**：针对移动端优化（增大滑块触点、单列布局等）。

### 技术栈
- HTML5、CSS3、JavaScript (ES6)
- Web Audio API（`AudioContext`、振荡器、增益节点、立体声控制节点、分析节点）
- Canvas 用于波形绘制

### 使用方法
1. 在现代浏览器中打开 [网站](majiangla.github.io/SoundGen)（推荐 Chrome、Firefox、Edge、Safari）。
2. 点击 **开始** 按钮播放音频。
3. 选择波形，调节频率、音量和平衡。
4. 波形显示区域会实时更新。
5. 点击 **停止** 暂停音频（上下文被挂起，不会销毁）。

### 相关链接
- [Bilibili 空间](https://space.bilibili.com/1431497051)
- [GitHub 仓库](https://github.com/majiangla/SoundGen)


---

*Feel free to contribute or report issues on GitHub.*  
*欢迎在 GitHub 上贡献或报告问题。*
