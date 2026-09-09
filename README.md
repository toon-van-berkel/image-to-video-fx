# ImageToVideoFX

**ImageToVideoFX** is a lightweight Python project that converts a static image into a smooth zoom-in video with optional background music.

## 🚀 Features

- 🔍 Smooth zoom-in effect using frame-by-frame cropping
- 🎵 Optional background music support (MP3)
- 🎬 Outputs high-quality MP4 video with audio sync
- ⚙️ Fully compatible with most video players (uses `libx264` and `yuv420p`)

## 📦 Requirements

- Python 3.7+
- `moviepy`
- `Pillow`
- `numpy`

Install them with:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

```bash
python image_to_video.py
```

## 📄 License

ImageToVideoFX is licensed under the **PolyForm Noncommercial License 1.0.0**.

You may use, study, modify and redistribute the software for **noncommercial purposes**.

Commercial use requires separate permission from the copyright holder.

See [`LICENSE`](LICENSE) for the full terms.
