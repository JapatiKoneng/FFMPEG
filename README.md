# FFMPEG

**Cara Convert Gambar menjadi Video:**
ffmpeg -framerate 30 -i frame_%04d.jpg -c:v libx264 -pix_fmt yuv420p output.mp4

**Cara Convert Video menjadi Gambar**
ffmpeg -i contoh.mp4 -vf fps=1 frame_%04d.png
ffmpeg -i contoh.mp4 -qscale:v 2 frame_%04d.jpg
