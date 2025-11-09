# Streamlit Launcher

<img src="https://github.com/DwiDevelopes/gambar/raw/main/launcher.jpg" width="100%" height="100%">

[![PyPI version](https://badge.fury.io/py/streamlit-launcher.svg)](https://badge.fury.io/py/streamlit-launcher)
[![Downloads](https://pepy.tech/badge/streamlit-launcher/week)](https://pepy.tech/project/streamlit-launcher)
[![Total Downloads](https://pepy.tech/badge/streamlit-launcher)](https://pepy.tech/project/streamlit-launcher)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-FF4B4B)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code Style: Black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## 🔗 Links Penting

- **PyPI Package**: [https://pypi.org/project/streamlit-launcher/](https://pypi.org/project/streamlit-launcher/)
- **Demo Online**: [https://stremlit-launcher.streamlit.app/](https://stremlit-launcher.streamlit.app/)
- **GitHub Repository**: [https://github.com/DwiDevelopes/Launcher](https://github.com/DwiDevelopes/Launcher)
- **Documentation**: [https://streamlit-launcher-docs.readthedocs.io/](https://streamlit-launcher-docs.readthedocs.io/)

## 📊 Statistik Penggunaan

| Metric | Value |
|--------|-------|
| Total Downloads | 10,000+ |
| Monthly Downloads | 2,500+ |
| Weekly Downloads | 600+ |
| Python Version Support | 3.7+ |
| Streamlit Version | 1.28+ |
| Test Coverage | 92%+ |
| Last Update | September 2024 |

## 📖 Overview

**Streamlit Launcher** adalah alat GUI yang sederhana, powerful, dan intuitif untuk menjalankan aplikasi Streamlit secara lokal. Tool ini dirancang khusus untuk Data Scientist, Analis Data, Machine Learning Engineers, dan Developer yang bekerja dengan Streamlit untuk membuat dashboard dan aplikasi data interaktif.

### 🎯 Target Pengguna

- **Data Scientist** - Membuat prototype model ML dengan cepat
- **Data Analyst** - Membuat dashboard analitik interaktif
- **ML Engineer** - Deployment model machine learning
- **Business Intelligence** - Laporan dan visualisasi bisnis
- **Researchers** - Eksperimen dan presentasi hasil penelitian
- **Educators** - Materi pembelajaran interaktif

# Streamlit Launcher V4 Update

<img src="https://github.com/DwiDevelopes/gambar/raw/main/launcher.jpg" width="100%" height="100%">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/1.png" width="100%" />
<p align="center">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/2.png" width="48%" />
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/3.png" width="48%" />
</p>
<p align="center">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/4.png" width="48%" />
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/5.png" width="48%" />
</p>
<p align="center">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/6.png" width="48%" />
<img src="https://github.com/DwiDevelopes/gambar/raw/main/tas/7.png" width="48%" />
</p>

## Update V4 Grafik Saham

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-11-09%20001502.png" width="100%" height="100%">


1. Menambahkan grafik saham
2. Menambahkan fitur pencarian
3. Menambahkan fitur pengaturan
4. Menambahkan fitur pengaturan pengguna
5. Vitur Saham Grafik
6. Chart Saham Lengkap
7. OLDC

# Update V4 Install Streamlit Launcher Make Termux ☕

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Desain%20tanpa%20judul%20(10).jpg" width="100%" height="100%">


# 🌱 Pantun untuk Anak Programming
Baik, saatnya puisi kecil untuk pejuang logika digital.
Pantun bukan algoritma, tapi ritmenya juga perlu rapi supaya compiler kehidupan tidak error karna logika.

### 🌱 Pantun untuk Anak Programming Indonesia

#### 🐞 Debugging Pantun
1. Naik sepeda ke tempat angringan,
2. Bawa laptop sambil tersenyum sopan.
3. Kalau kode sering berantakan,
4. Sabar… bug itu cuma ujian keimanan

#### 🥮 Pantun Mie Instan

1. Makan mie instan dua porsi bareng-bareng,
2. Sambil commit patch di repository terang-terang.
3. Jika hasil kerja belum dipuji orang,
4. Santai… kode bagus lama-lama sendiri yang gemilang.

---

### ✅ **Step-by-step install Streamlit dan jalankan launcher di Termux**

#### **1. Update & install paket penting**

```bash
pkg update && pkg upgrade -y
pkg install python git clang cmake libffi libffi-dev openssl openssl-dev -y
pkg install python
```

#### **2. Upgrade pip**

```bash
pip install --upgrade pip wheel setuptools
```

#### **3. Install Streamlit (dan fix dependencies)**

> Streamlit butuh beberapa paket scientific + wheel builder

```bash
pip install streamlit==1.49.1
pip install pandas==2.3.2
pip install numpy==2.2.2
pip install plotly==5.24.1
pip install matplotlib==3.9.2
pip install seaborn==0.13.2
pip install wordcloud==1.9.4
pip install streamlit-folium==0.23.1
pip install graphviz==0.20.3
pip install pillow==10.4.0
pip install pydeck==0.9.1  
pip install scipy==1.14.1
pip install scikit-learn==1.5.2   
pip install xgboost==2.1.1
pip install statsmodels==0.14.3   
pip install tensorflow-cpu==2.20.0
pip install keras==3.11.3
pip install networkx==3.4.2
pip install rich==14.2.0
pip install requests==2.32.3
pip install openpyxl==3.1.5
pip install xlrd==2.0.1
pip install numpy-stl==3.2.0
pip install trimesh==4.3.2
pip install streamlit-modal==0.1.2
pip install opencv-python-headless
pip install mlxtend==0.23.4
```

Kalau masih error, alternatif lebih aman:

```bash
pip install streamlit --no-cache-dir
```

#### **4. Clone repo**

```bash
git clone https://github.com/DwiDevelopes/Launcher.git
cd Launcher/build/lib/streamlit_launcher
```

#### **5. Install requirements project**

```bash
pip install -r requirements.txt --no-cache-dir
```

#### **6. Jalankan Streamlit**

```bash
streamlit run dashboard.py --server.address=0.0.0.0 --server.port=8501
```

---

### ⚠️ **Kalau muncul error “No module named xyz”**

Install modul manual, contoh:

```bash
pip install streamlit
pip install pandas
pip install numpy
pip install plotly
pip install matplotlib
pip install seaborn
pip install wordcloud
pip install streamlit-folium
pip install graphviz
pip install pillow
pip install pydeck 
pip install scipy
pip install scikit-learn
pip install xgboost
pip install statsmodels  
pip install tensorflow-cpu
pip install keras
pip install networkx
pip install rich
pip install requests
pip install openpyxl
pip install xlrd
pip install numpy-stl
pip install trimesh
pip install streamlit-modal
pip install opencv-python-headless
pip install mlxtend
```

---

### 🎯 **Tips penting**

| Masalah                  | Solusi                                                          |
| ------------------------ | --------------------------------------------------------------- |
| Streamlit gagal build    | Pastikan `clang`, `cmake`, `openssl`, `libffi` sudah terinstall |
| Termux tidak buka web UI | Buka dari browser HP ke `http://localhost:8501`                 |
| Masih error              | Coba `termux-chroot` (kalau pakai proot distro)                 |

---

# ☕ Simple Install Streamlit Launcher Termux.sh

Berikut resep terminal layaknya koki DevOps yang sedang menyiapkan dapur Termux agar Streamlit mau nurut. Ini adalah file **`install_streamlit_termux.sh`** yang tinggal kamu simpan dan eksekusi.

> Script ini memastikan dependency, pip builder, dan repo Launcher terpasang rapi tanpa drama.

---

### ✅ **`install_streamlit_termux.sh`**

---

### 📦 **Cara pakai**

```bash
chmod +x install_streamlit_termux.sh
./install_streamlit_termux.sh
```

---

### 🎯 Hasil akhir

Jika sukses, buka browser Android lalu masuk ke:

```
http://localhost:8501
```

---

### 🍵 Catatan teknis kecil

1. Script ini tidak menghapus environment lama; aman untuk update
2. coffie panas opsional, tapi bikin suasana ngoding lebih damai

---

Menjalankan `install_streamlit_termux.sh` itu seperti membangunkan naga kecil di Termux: perlu sedikit ritual, tapi setelah hidup, dia akan menghembuskan Streamlit dari pori-pori ponselmu.

# ✅ **Langkah menjalankan skrip di Termux**

1. **Masuk ke folder tempat file disimpan**
   Misal file ada di `~/` (home):

   ```bash
   cd ~
   ```

2. **Pastikan file punya izin eksekusi**

   ```bash
   chmod +x install_streamlit_termux.sh
   ```

3. **Jalankan script**

   ```bash
   ./install_streamlit_termux.sh
   ```

Kalau kamu ingin menjalankan langsung via `bash`, boleh juga:

```bash
bash install_streamlit_termux.sh
```

---

### 🧠 **Kalau file belum ada di Termux**

Kamu bisa buat file manual:

```bash
nano install_streamlit_termux.sh
```

Paste script ke dalamnya, lalu:

`CTRL + O` untuk save
`ENTER`
`CTRL + X` untuk keluar

Lanjut ke langkah **chmod** dan **run** di atas.

---

### 🛠️ **Troubleshooting singkat**

| Masalah               | Solusi                                                                    |
| --------------------- | ------------------------------------------------------------------------- |
| Permission denied     | Pastikan sudah `chmod +x`                                                 |
| Command not found     | Pastikan berada di folder yang benar                                      |
| Gagal install package | Coba jalankan ulang script, atau install `termux-chroot` jika pakai PRoot |

---


Bayangkan ini sebagai menu spell:

| Nomor | Mantra                               | Hasil                                                                  |
| ----- | ------------------------------------ | ---------------------------------------------------------------------- |
| 1     | **Auto-installer 1 baris**           | Tinggal copy-paste, semua terinstal otomatis                           |
| 2     | **Installer + Virtual Env**          | Termux jadi rapi, paket terisolasi seperti laboratorium kimia          |
| 3     | **Termux Widget Shortcut**           | Tinggal tap ikon di Android, Streamlit langsung menyala                |
| 4     | **Systemd-like auto-restart script** | Kalau Streamlit error, bangkit sendiri seperti zombie ramah            |
| 5     | **Full Linux magic (proot Ubuntu)**  | Streamlit jalan layaknya di PC, lebih stabil                           |
| 6     | **Gabungan level Hokage**            | Semua opsi di atas, sistem jalan sendiri, kamu tinggal menyeruput kopi |


### 📊 Fitur

- 📊 Analisis DNA
- 📈 Statistik
- 📈 Visualisasi
- 📈 Editor File
- 📈 Grafik Saham
- 📈 SQL Style
- 📈 Konversi Cepat
- 📈 Database
- 📈 Machine Learning
- 📈 Laporan
- 📈 Dashboard
- 📈 Simulasi
- 📈 Deeplearning
- 📈 Pencarian
- 📈 Remove Background
- 📈 dll


# Update V4 Anlisis And Doctor Analisis and Install Streamlit Launcher Make Termux ☕

## vitur Update Api Key And Api Server

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-11-05%20092327.png" width="100%" height="100%">


1. Api key
2. Api server
3. Api server code
4. Test api server
5. Simple
6. Generated

## Source Code Server Api key Is Running

```python
# api_server.py
from flask import Flask, request, jsonify
import pandas as pd
import sqlite3
from datetime import datetime
import os
import logging
from typing import Optional, Tuple, Any

# Setup logging
logging.basicConfig(level=logging.INFO)
logger = logging.getLogger(__name__)

app = Flask(__name__)
app.config['JSON_SORT_KEYS'] = False

class DatabaseManager:
    """Class untuk mengelola koneksi database"""
    
    @staticmethod
    def get_connection(db_path: str) -> sqlite3.Connection:
        """Membuat koneksi database dengan error handling"""
        try:
            conn = sqlite3.connect(db_path)
            conn.row_factory = sqlite3.Row  # Mengembalikan hasil sebagai dictionary
            return conn
        except sqlite3.Error as e:
            logger.error(f"Database connection error: {e}")
            raise

def validate_api_key(api_key: str) -> bool:
    """
    Validasi API key dari database
    
    Args:
        api_key: String API key untuk divalidasi
        
    Returns:
        Boolean indicating validity of API key
    """
    if not api_key:
        return False
        
    try:
        conn = DatabaseManager.get_connection('api_keys.db')
        c = conn.cursor()
        
        c.execute("""
            SELECT * FROM api_keys 
            WHERE api_key = ? AND is_active = 1
        """, (api_key,))
        
        result = c.fetchone()
        conn.close()
        
        return result is not None
        
    except sqlite3.Error as e:
        logger.error(f"Database error during API key validation: {e}")
        return False
    except Exception as e:
        logger.error(f"Unexpected error during API key validation: {e}")
        return False

def get_api_key() -> Optional[str]:
    """
    Mendapatkan API key dari header atau query parameters
    
    Returns:
        API key string atau None jika tidak ditemukan
    """
    # Cek di header terlebih dahulu
    api_key = request.headers.get('X-API-Key')
    
    # Jika tidak ada di header, cek di query parameters
    if not api_key:
        api_key = request.args.get('api_key')
    
    return api_key

@app.before_request
def log_request_info():
    """Middleware untuk logging setiap request"""
    logger.info(f"Request: {request.method} {request.path} - IP: {request.remote_addr}")

@app.after_request
def after_request(response):
    """Middleware untuk menambahkan header security"""
    response.headers.add('X-Content-Type-Options', 'nosniff')
    response.headers.add('X-Frame-Options', 'DENY')
    response.headers.add('X-XSS-Protection', '1; mode=block')
    return response

@app.route('/api/v1/health', methods=['GET'])
def health_check():
    """Endpoint untuk health check API"""
    try:
        # Test database connection
        conn = DatabaseManager.get_connection('api_keys.db')
        conn.close()
        
        return jsonify({
            'status': 'healthy',
            'timestamp': datetime.now().isoformat(),
            'version': '1.0.0'
        })
    except Exception as e:
        logger.error(f"Health check failed: {e}")
        return jsonify({
            'status': 'unhealthy',
            'error': str(e),
            'timestamp': datetime.now().isoformat()
        }), 503

@app.route('/api/v1/statistics', methods=['GET'])
def get_statistics():
    """Endpoint untuk mendapatkan statistics"""
    api_key = get_api_key()
    
    if not api_key or not validate_api_key(api_key):
        logger.warning(f"Invalid API key attempt from IP: {request.remote_addr}")
        return jsonify({
            'error': 'Invalid or inactive API key',
            'code': 'UNAUTHORIZED'
        }), 401
    
    try:
        # Your statistics logic here
        # Contoh: membaca data dari database atau file
        statistics_data = {
            'total_users': 1000,
            'active_users': 750,
            'requests_today': 15000,
            'average_response_time': '45ms'
        }
        
        logger.info(f"Statistics request successful for API key: {api_key[:8]}...")
        
        return jsonify({
            'status': 'success',
            'timestamp': datetime.now().isoformat(),
            'data': statistics_data
        })
        
    except Exception as e:
        logger.error(f"Error in statistics endpoint: {e}")
        return jsonify({
            'error': 'Internal server error',
            'code': 'INTERNAL_ERROR'
        }), 500

@app.errorhandler(404)
def not_found(error):
    """Handler untuk 404 Not Found"""
    return jsonify({
        'error': 'Endpoint not found',
        'code': 'NOT_FOUND'
    }), 404

@app.errorhandler(405)
def method_not_allowed(error):
    """Handler untuk 405 Method Not Allowed"""
    return jsonify({
        'error': 'Method not allowed',
        'code': 'METHOD_NOT_ALLOWED'
    }), 405

@app.errorhandler(500)
def internal_server_error(error):
    """Handler untuk 500 Internal Server Error"""
    logger.error(f"Internal server error: {error}")
    return jsonify({
        'error': 'Internal server error',
        'code': 'INTERNAL_ERROR'
    }), 500

if __name__ == '__main__':
    # Cek apakah database exists
    if not os.path.exists('api_keys.db'):
        logger.warning("Database file 'api_keys.db' not found. Please create it first.")
    
    # Run aplikasi
    debug_mode = os.getenv('FLASK_DEBUG', 'False').lower() == 'true'
    
    app.run(
        host=os.getenv('FLASK_HOST', '0.0.0.0'),
        port=int(os.getenv('FLASK_PORT', 5000)),
        debug=debug_mode
    )
```

## vitur Update Scatterplot Visualisasi Interval

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-11-04%20225922.png" width="100%" height="100%">

1. Korelasi Pearson (r)
2. Kekuatan Korelasi
3. Arah & Signifikansi
4. Effect Size
5. Minimum
6. Maximum
7. Variance X
8. Variance Y
9. Variance Total
10. Variance Population
11. Variance Sample
12. Variance
13. Standard Deviation X
14. Standard Deviation Y
15. Standard Deviation Total
16. Standard Deviation Population
17. Standard Deviation Sample
18. Standard Deviation
19. Mean X
20. Mean Y
21. Mean Total
22. Mean Population
23. Mean Sample
24. Mean
25. Median X
26. Median Y
27. Median Total
28. Median Population
29. Median Sample
30. Median
31. Mode X
32. Mode Y
33. Mode Total
34. Mode Population
35. Mode Sample
36. Mode
37. Interquartile Range X
38. Interquartile Range Y
39. Interquartile Range Total
40. Interquartile Range Population
41. Interquartile Range Sample
42. Interquartile Range
43. Range X
44. Range Y
45. Confidence Interval
46. Implikasi Praktis

## Vitur Update Chart Visualisasi
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k1.png" width="100%" height="100%">

1. 📊 Chart Utama
2. 📈 Analisis Chart Csv/xlsx
3. 📈 Statistik
4. 📈 Visualisasi
5. 📈 Pengaturan Konfigurasi
6. 📈 Menggunakan Plugin
7. 📈 Menggunakan Data Mentah

## Welcome Vitur Update Doctor Analisis Healty Human
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k4.png" width="100%" />
<p align="center">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k2.png" width="48%" />
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k3.png" width="48%" />
</p>
<p align="center">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k6.png" width="48%" />
<img src="https://github.com/DwiDevelopes/gambar/raw/main/kesehatan/k5.png" width="48%" />
</p>


1. Low Blood Pressure
2. High Blood Pressure
3. Blood Health
4. Blood Pressure
5. Weight
6. Diet
7. Health Pattern
8. Regularity
9. Age
10. Target Weight
11. etc.

## Vitur Analisis Face 
=======
## Welcome Vitur Analisis Face 
>>>>>>> 0ad9b6b0c54f59479b51e0f175573068b40c2f8e

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-10-30%20200557.png" width="100%" height="100%">

1. Analisis Face
2. Statistik
3. Visualisasi
4. Mark Face
5. Face Detection
6. Face Recognition
7. Face Verification
8. Face Quality
9. Face Clustering
10. Face Similarity

## 📊 Analisis DNA

Fitur analisis DNA yang tersedia:

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-10-26%20021559.png" width="100%" height="100%">

1. 📊 Komposisi Basa
2. 🔍 Motif & Pattern
3. 🧮 Biophysical Properties
4. 📈 Sequence Features
5. 🧪 Aplikasi Penelitian

## 📚 Vitur Keamanan CSV Data

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-10-26%20211631.png" width="100%" height="100%">

1. Encrypsi Data
2. Denkripsi Data
3. Sistem Keamanan Data
4. Keamanan Data
5. Data Terenkripsi
6. Python dan Data Encryption
7. Text dan Encryption

## 📚 Vitur Profile And Analytics Source Code

<img src="https://github.com/DwiDevelopes/gambar/raw/main/Screenshot%202025-10-27%20213625.png" width="100%" height="100%">

1. Source Code
2. Member Premium
3. AI Unlimited Free
4. Realtime Data
5. Data Visualization
6. Data Analysis
7. Data Export
8. Data Import
9. Data Encryption
10. Data Security
11. Data Privacy
12. Data Anonymization
13. Data Anomaly Detection
14. Data Clustering
15. Data Dimensionality Reduction
16. Data Feature Selection
17. Data Feature Engineering
18. Data Feature Extraction
19. Data Feature Selection
20. Data Feature Selection

## Vitur Map Data

<img src="https://github.com/DwiDevelopes/gambar/raw/main/mapchart4.png" width="100%" height="100%">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/mapchar3.png" width="100%" height="100%">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/mapchart2.png" width="100%" height="100%">
<img src="https://github.com/DwiDevelopes/gambar/raw/main/mapchart.png" width="100%" height="100%">

1. Peta Interaktif
2. Data Points pada Peta
3. Tampilkan semua kolom
4. Tampilkan kolom lat, lon
5. Tampilkan kolom lat, lon, nama
6. Peta Internasional
7. Peta Global
8. Peta Glob
9. Information Map
10. Analisis Map
11. Statistik Map
12. Visualisasi Map
13. Visualisasi Map dengan Marker
14. Visualisasi Map dengan Marker dengan Cluster
15. Visualisasi Map dengan Marker dengan Cluster dengan Tooltip
16. Peta Satelit
17. Peta Typograpy
18. Peta Dark


## 🚀 Installation

### Prerequisites System:

- **Python 3.7** atau lebih tinggi
- **pip** (Python package manager) versi terbaru
- **Virtual environment** (direkomendasikan)
- **Git** (untuk version control)

### Metode Installasi:

#### 1. Installasi Basic (Recommended)

```bash
# Install menggunakan pip
pip install streamlit-launcher

# Verifikasi installasi
streamlit-launcher --version
```

#### 2. Installasi dengan Virtual Environment (Best Practice)

```bash
# Buat virtual environment
python -m venv streamlit_env

# Aktifkan virtual environment
# Windows:
streamlit_env\Scripts\activate
# macOS/Linux:
source streamlit_env/bin/activate

# Install package
pip install streamlit-launcher
```

#### 3. Installasi untuk Development

```bash
# Install dengan dependencies development
pip install streamlit-launcher[dev]

# Atau install manual
pip install streamlit-launcher pytest black flake8 mypy
```

#### 4. Installasi dari Source

```bash
# Clone repository
git clone https://github.com/royhtml/streamlit-launcher.git
cd streamlit-launcher

# Install dalam development mode
pip install -e .

# Atau install dengan requirements
pip install -r requirements.txt
```

#### 5. Installasi dengan Options Tambahan

```bash
# Install dengan extra features
pip install streamlit-launcher[all]

# Install specific version
pip install streamlit-launcher==1.0.0

# Upgrade ke versi terbaru
pip install --upgrade streamlit-launcher
```

### Verifikasi Installasi:

```bash
# Cek versi
streamlit-launcher --version

# Cek help
streamlit-launcher --help

# Test import
python -c "import streamlit_launcher; print('Installation successful!')"
```

### Troubleshooting Installasi:

```bash
# Jika ada permission error
pip install --user streamlit-launcher

# Jika ada conflict dependencies
pip install --upgrade --force-reinstall streamlit-launcher

# Clear pip cache
pip cache purge

# Install dengan no-cache
pip install --no-cache-dir streamlit-launcher
```

## 💻 Usage

### Cara Menjalankan Dasar:

```bash
# Jalankan launcher (mode default)
streamlit_launcher

# Atau dengan python module
python -m streamlit_launcher

# Dengan specific port
streamlit_launcher --port 8501

# Dengan host tertentu
streamlit_launcher --host 0.0.0.0
```

### Advanced Usage:

```bash
# Jalankan dengan debug mode
streamlit_launcher --debug true

# Specify browser automatically open
streamlit_launcher --browser true

# Dengan konfigurasi custom
streamlit_launcher --config .streamlit/config.toml

# Menjalankan specific app
streamlit_launcher --app my_app.py
```

### Command Line Options Lengkap:

```bash
streamlit_launcher --help

# Output:
Usage: streamlit_launcher [OPTIONS]

Options:
  --port INTEGER           Port number to run the app (default: 8501)
  --host TEXT              Host address to bind to (default: localhost)
  --browser BOOLEAN        Auto-open browser (default: true)
  --debug BOOLEAN          Enable debug mode (default: false)
  --log-level TEXT         Log level (debug, info, warning, error)
  --config FILE            Path to config file
  --app FILE               Specific app file to launch
  --theme TEXT             Color theme (light, dark)
  --version                Show version information
  --help                   Show this message and exit
```

## 🖼️ Screenshot & Demo

<img src="https://github.com/DwiDevelopes/Streamlit-Launcher/raw/main/Screenshot%202025-10-25%20122002.png" width="100%" height="100%">

*Tampilan GUI Streamlit Launcher yang user-friendly dengan dark mode*

### Fitur GUI:
- ✅ **File Browser** - Navigasi file yang intuitif
- ✅ **Project Management** - Kelola multiple Streamlit apps
- ✅ **Real-time Logs** - Melihat logs secara real-time
- ✅ **Port Management** - Manage multiple ports dengan mudah
- ✅ **Theme Selection** - Light/Dark mode
- ✅ **Quick Actions** - Shortcut untuk common tasks

## 🔧 Advanced Configuration

### Environment Variables:

```bash
# Set di shell atau .env file
export STREAMLIT_SERVER_PORT=8501
export STREAMLIT_SERVER_ADDRESS=0.0.0.0
export STREAMLIT_BROWSER_GATHER_USAGE_STATS=false
export STREAMLIT_THEME_BASE="dark"
export STREAMLIT_LOG_LEVEL="info"
```

### File Konfigurasi (.streamlit/config.toml):

```toml
[server]
port = 8501
address = "0.0.0.0"
enableCORS = false
enableXsrfProtection = true
maxUploadSize = 200

[browser]
serverAddress = "localhost"
gatherUsageStats = false
serverPort = 8501

[theme]
base = "dark"
primaryColor = "#ff4b4b"
backgroundColor = "#0e1117"
secondaryBackgroundColor = "#262730"
textColor = "#fafafa"
font = "sans serif"

[logger]
level = "info"

[client]
showErrorDetails = true
```

### Konfigurasi untuk Production:

```toml
[server]
headless = true
enableCORS = false
maxUploadSize = 500

[runner]
magicEnabled = false
```

## 📊 Contoh Aplikasi Data Science Lengkap

### Contoh 1: Comprehensive EDA Dashboard

```python
# app_eda.py
import streamlit as st
import pandas as pd
import numpy as np
import plotly.express as px
import plotly.graph_objects as go
from scipy import stats
import seaborn as sns
import matplotlib.pyplot as plt

# Page configuration
st.set_page_config(
    page_title="EDA Dashboard",
    page_icon="📊",
    layout="wide",
    initial_sidebar_state="expanded"
)

# Custom CSS
st.markdown("""
<style>
    .main-header {
        font-size: 2.5rem;
        color: #1f77b4;
        text-align: center;
        margin-bottom: 2rem;
    }
    .metric-card {
        background-color: #f0f2f6;
        padding: 1rem;
        border-radius: 10px;
        margin: 0.5rem 0;
    }
</style>
""", unsafe_allow_html=True)

@st.cache_data
def load_data(uploaded_file):
    """Load data dengan caching untuk performance"""
    try:
        if uploaded_file.name.endswith('.csv'):
            return pd.read_csv(uploaded_file)
        elif uploaded_file.name.endswith('.xlsx'):
            return pd.read_excel(uploaded_file)
        else:
            st.error("Format file tidak didukung")
            return None
    except Exception as e:
        st.error(f"Error loading file: {e}")
        return None

def show_data_overview(df):
    """Menampilkan overview data"""
    st.header("📈 Data Overview")
    
    col1, col2, col3, col4 = st.columns(4)
    
    with col1:
        st.metric("Total Rows", df.shape[0])
    with col2:
        st.metric("Total Columns", df.shape[1])
    with col3:
        st.metric("Missing Values", df.isnull().sum().sum())
    with col4:
        st.metric("Memory Usage", f"{df.memory_usage(deep=True).sum() / 1024**2:.2f} MB")
    
    # Data preview
    st.subheader("Data Preview")
    st.dataframe(df, use_container_width=True)
    
    # Data types
    st.subheader("Data Types")
    dtype_df = pd.DataFrame(df.dtypes, columns=['Data Type'])
    st.dataframe(dtype_df)

def show_missing_analysis(df):
    """Analisis missing values"""
    st.header("🔍 Missing Values Analysis")
    
    missing_data = df.isnull().sum()
    missing_percent = (missing_data / len(df)) * 100
    
    missing_df = pd.DataFrame({
        'Column': missing_data.index,
        'Missing Count': missing_data.values,
        'Missing Percentage': missing_percent.values
    }).sort_values('Missing Count', ascending=False)
    
    # Filter hanya yang ada missing values
    missing_df = missing_df[missing_df['Missing Count'] > 0]
    
    if len(missing_df) > 0:
        st.dataframe(missing_df, use_container_width=True)
        
        # Visualisasi missing values
        fig = px.bar(missing_df, x='Column', y='Missing Percentage', 
                     title='Missing Values Percentage by Column')
        st.plotly_chart(fig, use_container_width=True)
    else:
        st.success("🎉 Tidak ada missing values dalam dataset!")

def show_statistical_analysis(df):
    """Analisis statistik"""
    st.header("📊 Statistical Analysis")
    
    # Pilih kolom numerik
    numeric_cols = df.select_dtypes(include=[np.number]).columns.tolist()
    
    if numeric_cols:
        selected_col = st.selectbox("Pilih kolom untuk analisis:", numeric_cols)
        
        if selected_col:
            col_data = df[selected_col].dropna()
            
            col1, col2 = st.columns(2)
            
            with col1:
                st.subheader("Descriptive Statistics")
                stats_df = pd.DataFrame({
                    'Statistic': ['Count', 'Mean', 'Std Dev', 'Min', '25%', '50%', '75%', 'Max', 'Skewness', 'Kurtosis'],
                    'Value': [
                        len(col_data),
                        col_data.mean(),
                        col_data.std(),
                        col_data.min(),
                        col_data.quantile(0.25),
                        col_data.median(),
                        col_data.quantile(0.75),
                        col_data.max(),
                        col_data.skew(),
                        col_data.kurtosis()
                    ]
                })
                st.dataframe(stats_df, use_container_width=True)
            
            with col2:
                st.subheader("Distribution")
                fig = px.histogram(col_data, x=selected_col, 
                                 title=f'Distribution of {selected_col}',
                                 marginal="box")
                st.plotly_chart(fig, use_container_width=True)

def show_correlation_analysis(df):
    """Analisis korelasi"""
    st.header("🔗 Correlation Analysis")
    
    numeric_df = df.select_dtypes(include=[np.number])
    
    if len(numeric_df.columns) > 1:
        # Heatmap korelasi
        corr_matrix = numeric_df.corr()
        
        fig = px.imshow(corr_matrix,
                       title="Correlation Heatmap",
                       color_continuous_scale="RdBu",
                       aspect="auto")
        st.plotly_chart(fig, use_container_width=True)
        
        # Nilai korelasi detail
        st.subheader("Detailed Correlation Values")
        st.dataframe(corr_matrix.style.background_gradient(cmap='RdBu'), 
                    use_container_width=True)

def main():
    st.markdown('<div class="main-header">📊 Exploratory Data Analysis Dashboard</div>', 
                unsafe_allow_html=True)
    
    # File upload
    uploaded_file = st.sidebar.file_uploader(
        "Upload dataset Anda", 
        type=['csv', 'xlsx'],
        help="Support CSV dan Excel files"
    )
    
    if uploaded_file is not None:
        df = load_data(uploaded_file)
        
        if df is not None:
            # Sidebar controls
            st.sidebar.header("Analysis Options")
            show_overview = st.sidebar.checkbox("Data Overview", True)
            show_missing = st.sidebar.checkbox("Missing Analysis", True)
            show_stats = st.sidebar.checkbox("Statistical Analysis", True)
            show_corr = st.sidebar.checkbox("Correlation Analysis", True)
            
            # Main analysis sections
            if show_overview:
                show_data_overview(df)
            
            if show_missing:
                show_missing_analysis(df)
            
            if show_stats:
                show_statistical_analysis(df)
            
            if show_corr:
                show_correlation_analysis(df)
            
            # Download processed data
            st.sidebar.header("Export Data")
            if st.sidebar.button("Download Processed Data as CSV"):
                csv = df.to_csv(index=False)
                st.sidebar.download_button(
                    label="Download CSV",
                    data=csv,
                    file_name="processed_data.csv",
                    mime="text/csv"
                )
    else:
        st.info("👆 Please upload your dataset to begin analysis")
        st.markdown("""
        ### Supported Features:
        - **Data Overview**: Basic statistics and data preview
        - **Missing Analysis**: Identify and visualize missing values
        - **Statistical Analysis**: Detailed descriptive statistics
        - **Correlation Analysis**: Heatmaps and correlation values
        - **Data Export**: Download processed data
        """)

if __name__ == "__main__":
    main()
```

### Contoh 2: Advanced Machine Learning Dashboard

```python
# app_ml.py
import streamlit as st
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.ensemble import RandomForestClassifier, RandomForestRegressor
from sklearn.linear_model import LogisticRegression, LinearRegression
from sklearn.svm import SVC, SVR
from sklearn.metrics import (accuracy_score, classification_report, 
                           confusion_matrix, mean_squared_error, r2_score)
import plotly.express as px
import plotly.figure_factory as ff
import joblib
import io

# Page config
st.set_page_config(
    page_title="ML Model Trainer",
    page_icon="🤖",
    layout="wide"
)

@st.cache_data
def load_data(uploaded_file):
    """Load dataset dengan caching"""
    if uploaded_file.name.endswith('.csv'):
        return pd.read_csv(uploaded_file)
    elif uploaded_file.name.endswith('.xlsx'):
        return pd.read_excel(uploaded_file)
    return None

def evaluate_model(model, X_test, y_test, problem_type):
    """Evaluate model performance"""
    y_pred = model.predict(X_test)
    
    if problem_type == "classification":
        accuracy = accuracy_score(y_test, y_pred)
        report = classification_report(y_test, y_pred, output_dict=True)
        cm = confusion_matrix(y_test, y_pred)
        return accuracy, report, cm, y_pred
    else:
        mse = mean_squared_error(y_test, y_pred)
        r2 = r2_score(y_test, y_pred)
        return mse, r2, y_pred

def main():
    st.title("🤖 Machine Learning Model Trainer")
    st.markdown("Train and evaluate multiple ML models with ease")
    
    # File upload
    uploaded_file = st.sidebar.file_uploader(
        "Upload Dataset", 
        type=['csv', 'xlsx'],
        help="Dataset harus mengandung features dan target variable"
    )
    
    if uploaded_file is not None:
        df = load_data(uploaded_file)
        
        if df is not None:
            st.success(f"✅ Dataset loaded successfully: {df.shape[0]} rows, {df.shape[1]} columns")
            
            # Problem type selection
            problem_type = st.sidebar.radio(
                "Select Problem Type:",
                ["Classification", "Regression"]
            )
            
            # Feature and target selection
            st.sidebar.header("Model Configuration")
            target_col = st.sidebar.selectbox(
                "Select Target Variable:",
                df.columns
            )
            
            feature_cols = st.sidebar.multiselect(
                "Select Features:",
                [col for col in df.columns if col != target_col],
                default=[col for col in df.columns if col != target_col]
            )
            
            # Model selection based on problem type
            if problem_type == "Classification":
                models = {
                    "Random Forest": RandomForestClassifier(),
                    "Logistic Regression": LogisticRegression(),
                    "Support Vector Machine": SVC()
                }
            else:
                models = {
                    "Random Forest": RandomForestRegressor(),
                    "Linear Regression": LinearRegression(),
                    "Support Vector Regression": SVR()
                }
            
            selected_models = st.sidebar.multiselect(
                "Select Models to Train:",
                list(models.keys()),
                default=list(models.keys())[0]
            )
            
            # Training parameters
            st.sidebar.header("Training Parameters")
            test_size = st.sidebar.slider("Test Size Ratio:", 0.1, 0.5, 0.2, 0.05)
            random_state = st.sidebar.number_input("Random State:", 42)
            cv_folds = st.sidebar.slider("Cross-Validation Folds:", 3, 10, 5)
            
            if st.sidebar.button("🚀 Train Models"):
                if not feature_cols:
                    st.error("Please select at least one feature!")
                    return
                
                # Prepare data
                X = df[feature_cols]
                y = df[target_col]
                
                # Handle categorical variables
                X = pd.get_dummies(X)
                
                # Split data
                X_train, X_test, y_train, y_test = train_test_split(
                    X, y, test_size=test_size, random_state=random_state
                )
                
                # Train and evaluate models
                results = {}
                
                for model_name in selected_models:
                    with st.spinner(f"Training {model_name}..."):
                        model = models[model_name]
                        
                        # Train model
                        model.fit(X_train, y_train)
                        
                        # Evaluate model
                        if problem_type == "Classification":
                            accuracy, report, cm, y_pred = evaluate_model(
                                model, X_test, y_test, "classification"
                            )
                            
                            # Cross-validation
                            cv_scores = cross_val_score(model, X, y, cv=cv_folds)
                            
                            results[model_name] = {
                                'type': 'classification',
                                'accuracy': accuracy,
                                'report': report,
                                'cm': cm,
                                'cv_scores': cv_scores,
                                'model': model
                            }
                        else:
                            mse, r2, y_pred = evaluate_model(
                                model, X_test, y_test, "regression"
                            )
                            
                            cv_scores = cross_val_score(model, X, y, cv=cv_folds, 
                                                      scoring='r2')
                            
                            results[model_name] = {
                                'type': 'regression',
                                'mse': mse,
                                'r2': r2,
                                'cv_scores': cv_scores,
                                'model': model,
                                'predictions': y_pred
                            }
                
                # Display results
                st.header("📊 Model Results")
                
                # Metrics comparison
                if problem_type == "Classification":
                    metrics_df = pd.DataFrame({
                        'Model': list(results.keys()),
                        'Accuracy': [results[model]['accuracy'] for model in results],
                        'CV Mean Score': [results[model]['cv_scores'].mean() for model in results],
                        'CV Std': [results[model]['cv_scores'].std() for model in results]
                    })
                else:
                    metrics_df = pd.DataFrame({
                        'Model': list(results.keys()),
                        'R² Score': [results[model]['r2'] for model in results],
                        'MSE': [results[model]['mse'] for model in results],
                        'CV Mean Score': [results[model]['cv_scores'].mean() for model in results],
                        'CV Std': [results[model]['cv_scores'].std() for model in results]
                    })
                
                st.subheader("Model Comparison")
                st.dataframe(metrics_df.style.highlight_max(axis=0), 
                           use_container_width=True)
                
                # Detailed results for each model
                for model_name, result in results.items():
                    with st.expander(f"Detailed Results - {model_name}"):
                        col1, col2 = st.columns(2)
                        
                        with col1:
                            st.metric("Accuracy" if problem_type == "classification" else "R² Score", 
                                    f"{result['accuracy' if problem_type == 'classification' else 'r2']:.3f}")
                            st.metric("CV Mean Score", f"{result['cv_scores'].mean():.3f}")
                        
                        with col2:
                            st.metric("CV Std", f"{result['cv_scores'].std():.3f}")
                            if problem_type == "regression":
                                st.metric("MSE", f"{result['mse']:.3f}")
                        
                        # Visualizations
                        if problem_type == "classification":
                            # Confusion matrix
                            fig_cm = px.imshow(result['cm'], 
                                             title=f"Confusion Matrix - {model_name}",
                                             labels=dict(x="Predicted", y="Actual"),
                                             color_continuous_scale="Blues")
                            st.plotly_chart(fig_cm, use_container_width=True)
                        else:
                            # Regression plot
                            fig_reg = px.scatter(x=y_test, y=result['predictions'],
                                              title=f"Actual vs Predicted - {model_name}",
                                              labels={'x': 'Actual', 'y': 'Predicted'})
                            fig_reg.add_shape(type='line', line=dict(dash='dash'),
                                            x0=y_test.min(), y0=y_test.min(),
                                            x1=y_test.max(), y1=y_test.max())
                            st.plotly_chart(fig_reg, use_container_width=True)
                
                # Model saving
                st.header("💾 Model Export")
                best_model_name = metrics_df.iloc[metrics_df['Accuracy' if problem_type == 'classification' else 'R² Score'].idxmax()]['Model']
                best_model = results[best_model_name]['model']
                
                # Save model
                model_buffer = io.BytesIO()
                joblib.dump(best_model, model_buffer)
                model_buffer.seek(0)
                
                st.download_button(
                    label=f"Download Best Model ({best_model_name})",
                    data=model_buffer,
                    file_name=f"best_model_{best_model_name}.pkl",
                    mime="application/octet-stream"
                )
    
    else:
        st.info("👆 Please upload your dataset to begin model training")
        st.markdown("""
        ### Supported Features:
        - **Classification & Regression**: Multiple algorithm support
        - **Model Comparison**: Side-by-side performance comparison
        - **Cross-Validation**: Robust model evaluation
        - **Visual Analytics**: Confusion matrices, regression plots
        - **Model Export**: Download trained models
        - **Hyperparameter Tuning**: Basic parameter configuration
        """)

if __name__ == "__main__":
    main()
```

## 🏗️ Project Structure Best Practices

```
my_streamlit_project/
├── apps/                          # Streamlit applications
│   ├── app_eda.py                # EDA dashboard
│   ├── app_ml.py                 # ML model trainer
│   ├── app_dashboard.py          # Main dashboard
│   └── app_monitoring.py         # Real-time monitoring
├── data/                         # Data directory
│   ├── raw/                      # Raw data files
│   ├── processed/                # Processed data
│   └── external/                 # External datasets
├── models/                       # Trained models
│   ├── production/               # Production models
│   └── experimental/             # Experimental models
├── utils/                        # Utility functions
│   ├── data_loader.py           # Data loading utilities
│   ├── visualization.py         # Plotting functions
│   └── helpers.py               # Helper functions
├── tests/                        # Test files
│   ├── test_data_loader.py
│   └── test_visualization.py
├── .streamlit/                   # Streamlit configuration
│   ├── config.toml
│   └── credentials.toml
├── requirements.txt              # Python dependencies
├── environment.yml              # Conda environment
├── Dockerfile                   # Container configuration
├── .env.example                 # Environment variables template
├── .gitignore                   # Git ignore rules
└── README.md                    # Project documentation
```

## 📋 Dependencies & Requirements

### Core Dependencies:

```txt
streamlit>=1.28.0
pandas>=1.5.0
numpy>=1.21.0
plotly>=5.13.0
scikit-learn>=1.2.0
scipy>=1.9.0
matplotlib>=3.5.0
seaborn>=0.12.0
joblib>=1.2.0
click>=8.0.0
```

### Optional Dependencies:

```txt
# Data processing
openpyxl>=3.0.0        # Excel support
pyarrow>=10.0.0        # Parquet support
sqlalchemy>=2.0.0      # Database support

# Advanced visualizations
altair>=5.0.0
bokeh>=3.0.0
folium>=0.14.0

# Machine learning
xgboost>=1.7.0
lightgbm>=3.3.0
catboost>=1.0.0

# Utilities
python-dotenv>=1.0.0   # Environment variables
tqdm>=4.65.0          # Progress bars
```

### Development Dependencies:

```txt
pytest>=7.0.0
black>=23.0.0
flake8>=6.0.0
mypy>=1.0.0
pre-commit>=3.0.0
pytest-cov>=4.0.0
```

## 🐛 Troubleshooting & Debugging

### Common Issues dan Solutions:

1. **Port Already in Use:**
```bash
# Cari process yang menggunakan port
lsof -i :8501

# Kill process
kill -9 $(lsof -t -i:8501)

# Atau gunakan port lain
streamlit_launcher --port 8502
```

2. **Module Import Errors:**
```bash
# Check Python path
python -c "import sys; print(sys.path)"

# Reinstall package
pip uninstall streamlit-launcher
pip install --no-cache-dir streamlit-launcher
```

3. **Permission Issues:**
```bash
# Gunakan virtual environment
python -m venv myenv
source myenv/bin/activate

# Atau install untuk user
pip install --user streamlit-launcher
```

4. **Performance Issues:**
```bash
# Enable caching
@st.cache_data
def load_data():
    return pd.read_csv('large_file.csv')

# Use lighter data types
df = df.astype({col: 'category' for col in categorical_columns})
```

### Debug Mode:

```bash
# Enable detailed logging
streamlit-launcher --log-level debug

# Atau set environment variable
export STREAMLIT_LOG_LEVEL=debug
export STREAMLIT_DEBUG=true

# Debug specific component
import streamlit as st
st.write(st.session_state)  # Print session state
```

## 🚀 Deployment & Production

### Local Deployment:

```bash
# Run with production settings
streamlit-launcher --port 8501 --host 0.0.0.0 --log-level error
```

### Docker Deployment:

```dockerfile
FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 8501

CMD ["streamlit-launcher", "--server.port=8501", "--server.address=0.0.0.0"]
```

### Cloud Deployment:

```yaml
# streamlit.yaml untuk Kubernetes
apiVersion: apps/v1
kind: Deployment
metadata:
  name: streamlit-app
spec:
  replicas: 3
  selector:
    matchLabels:
      app: streamlit
  template:
    metadata:
      labels:
        app: streamlit
    spec:
      containers:
      - name: streamlit
        image: your-registry/streamlit-app:latest
        ports:
        - containerPort: 8501
        env:
        - name: STREAMLIT_SERVER_PORT
          value: "8501"
```

## 🤝 Contributing

Kami menyambut kontribusi dari komunitas! Berikut cara berkontribusi:

### Setup Development Environment:

```bash
# Fork dan clone repository
git clone https://github.com/DwiDevelopes/streamlit-launcher.git
cd streamlit-launcher

# Setup development environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install development dependencies
pip install -e ".[dev]"

# Setup pre-commit hooks
pre-commit install
```

### Development Workflow:

1. **Buat branch baru:**
```bash
git checkout -b feature/amazing-feature
```

2. **Lakukan perubahan dan test:**
```bash
# Run tests
pytest

# Check code style
black .
flake8
mypy .

# Test the package
python -m streamlit_launcher --help
```

3. **Commit changes:**
```bash
git add .
git commit -m "feat: add amazing feature"
git push origin feature/amazing-feature
```

4. **Buat Pull Request**

### Testing:

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=streamlit_launcher tests/

# Run specific test file
pytest tests/test_launcher.py -v

# Run with different Python versions
tox
```

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🔗 Links & Resources

- **Official Documentation**: [https://streamlit-launcher-docs.readthedocs.io/](https://streamlit-launcher-docs.readthedocs.io/)
- **PyPI Package**: [https://pypi.org/project/streamlit-launcher/](https://pypi.org/project/streamlit-launcher/)
- **GitHub Repository**: [https://github.com/royhtml/streamlit-launcher](https://github.com/royhtml/streamlit-launcher)
- **Issue Tracker**: [https://github.com/royhtml/streamlit-launcher/issues](https://github.com/royhtml/streamlit-launcher/issues)
- **Streamlit Documentation**: [https://docs.streamlit.io/](https://docs.streamlit.io/)
- **Community Forum**: [https://discuss.streamlit.io/](https://discuss.streamlit.io/)

## 📞 Support & Community

### Getting Help:

1. **Documentation**: Check the comprehensive docs first
2. **GitHub Issues**: Search existing issues or create new one
3. **Community Forum**: Ask questions on Streamlit forum
4. **Stack Overflow**: Use tag `[streamlit]`

### Reporting Bugs:

```bash
# Include system information
python -c "import streamlit_launcher; print(streamlit_launcher.__version__)"
python --version

# Describe the issue clearly
# Include error messages and screenshots
# Provide steps to reproduce
```

### Feature Requests:

Kami welcome feature requests! Silakan:
1. Check existing issues terlebih dahulu
2. Jelaskan use case secara detail
3. Sertakan contoh kode jika memungkinkan
4. Vote pada features yang sudah ada

---

**⭐ Jangan lupa memberikan bintang di GitHub jika tool ini membantu!**

---

*Streamlit Launcher dikembangkan dengan ❤️ oleh [Dwi Bakti N Dev](https://github.com/DwiDevelopes)*
