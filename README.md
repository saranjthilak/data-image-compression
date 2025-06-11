# Data Image Compression

A lightweight image compression tool/framework to optimize images (JPEG, PNG, SVG, GIF) with configurable compression engines and settings.

---

## 🧩 Features

- **Multi-format support**: JPEG, PNG, SVG, and GIF.
- **Flexible engines**: Use popular tools like mozjpeg, pngquant, svgo, gifsicle, etc.
- **Combine compressions**: Apply multiple algorithms in sequence (e.g. mozjpeg + jpegoptim).
- **Detailed stats**: Compression ratio, size change, and more.
- **Error logging**: Save detailed error logs for troubleshooting.

---




## Image Compression with KMeans

We'll apply KMeans to reduce the number of colors in an image:
- Start with `warmup_k_means.ipynb` if you want to warm up
- Then, move on to `image_compression.ipynb` for the main course

<img src="https://miro.medium.com/max/840/1*y0nV4cWk3KbzXSe9dIWL5g.jpeg" width=500>

## 🔧 Installation

```bash
git clone https://github.com/saranjthilak/data-image-compression.git
cd data-image-compression
npm install
