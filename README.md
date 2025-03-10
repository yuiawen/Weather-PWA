# weather-pwa
Welcome to the documentation for modifying the program for the Progressive Web App from https://glitch.com/~responsive-forecast

## Live Website
https://yuiawen.github.io/weather-pwa/

### What Has Been Modified ? 
### 1. Media Queries Based on Screen Size  
``` bash
Saya menggunakan beberapa breakpoint dalam CSS:  
- Mobile (below 600px) → Tata letak lebih sederhana dan ditampilkan secara vertikal.  
- **Tablet (601px - 900px) → Tata letak lebih luas dengan elemen lebih sejajar.  
- **Desktop (above 901px) → Tampilan lebih lebar dengan lebih banyak elemen dalam satu baris.  
```

### 2. Responsive Images 
``` bash
Ukuran gambar menyesuaikan layar agar tetap proporsional dan tidak pecah, termasuk ikon cuaca.  
```


### 3. Responsive Layout  
Saya menggunakan flexbox agar tampilan menyesuaikan ukuran layar:  
- Mobile → Bagian cuaca saat ini ditampilkan berurutan ke bawah.  
- Tablet → Kartu prakiraan cuaca ditampilkan **3 per baris**.  
- Desktop → Kartu prakiraan cuaca ditampilkan **7 per baris**.  

## 4. Content Visibility  
Semua konten tetap terlihat di semua ukuran layar, hanya tata letaknya yang diubah agar lebih nyaman dibaca.  

## 5. Mobile-First Approach 
Desain dimulai dari versi mobile, lalu ditingkatkan untuk layar yang lebih besar.  

## 6, Text Optimization  
Ukuran font disesuaikan agar tetap mudah dibaca di semua layar.
