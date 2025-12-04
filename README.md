
# face-detection-and-emotiion-detection


Face Recognition & Emotion Detection using OpenCV + LBPH + DeepFace

Project ini adalah sistem pengenalan wajah (face recognition) menggunakan algoritma LBPH dan deteksi emosi real-time menggunakan DeepFace.
Webcam digunakan sebagai input utama untuk membaca wajah, mengenali identitas, serta menampilkan ekspresi dominan.


## Acknowledgements

- Fitur Utama

- Membuat dataset wajah dari webcam

- Training model pengenalan wajah menggunakan algoritma LBPH

- Pengenalan wajah real-time dengan OpenCV

- Deteksi emosi otomatis menggunakan DeepFace

- Log sistem untuk memantau error webcam dan peringatan TensorFlow


## Teknologi yang Digunakan

- Python 3.x

- OpenCV (cv2)

- DeepFace

- TensorFlow / Keras

- LBPH Face Recognizer

- Haar Cascade Classifier## 📁 Fitur Utama

- Membuat dataset wajah dari webcam

- Training model pengenalan wajah menggunakan algoritma LBPH

- Pengenalan wajah real-time dengan OpenCV

- Deteksi emosi otomatis menggunakan DeepFace

- Log sistem untuk memantau error webcam dan peringatan TensorFlow


## 📦 Teknologi yang Digunakan

- Python 3.x

- OpenCV (cv2)

- DeepFace

- TensorFlow / Keras

- LBPH Face Recognizer

- Haar Cascade Classifier



## Run Locally

Clone the project

```bash
git clone https://github.com/akukamu9021/face-detection-and-emotiion-detection.git
```

⚙️ Instalasi

```bash
pip install opencv-python opencv-contrib-python deepface numpy
```

📸 1. Membuat Dataset Wajah

```bash
python make_dataset.py

Instruksi:

Arahkan wajah ke webcam
Tekan s untuk menyimpan gambar
Tekan q untuk keluar
Dataset akan tersimpan di folder dataset/.
```
🧠 2. Training Model Wajah
```bash
python model.py

Mengambil seluruh gambar pada folder dataset/
Melatih model LBPH
Menyimpan file trainer.yml
Membuat file name_mapping.txt

```
👁️ 3. Menjalankan Face Recognition
```bash
python scan.py

Fitur:

Menampilkan wajah dalam kotak
Menampilkan nama sesuai prediksi model
Menandai wajah yang tidak dikenal (Unknown)
```
😊 4. Face Recognition + Emotion Detection
```bash
python deepface_start.py


fitur

Mendeteksi wajah
Menampilkan Nama + Emosi Dominan (happy, sad, neutral, angry, dll.)
Real-time melalui webcam
```
🧾 Log File

```bash
output.log

output2.log

fitur:

Mencatat peringatan TensorFlow / DeepFace
Mendeteksi error webcam seperti:
can't grab frame
Tidak dapat membaca frame dari webcam
Membantu debugging ketika analisis wajah/emosi gagal
Menyimpan pesan error tanpa perlu membuka terminal
```
## License

[MIT](https://choosealicense.com/licenses/mit/)

📄 Lisensi

Menggunakan classifier Haar Cascade milik OpenCV (Intel).