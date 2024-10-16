# Employee Attrition Rate Prediction

## Cakupan Proyek

1. Mencari tahu faktor apa saja yang memengaruhi tingginya attrition rate (keluar) karyawan di perusahaan Jaya Jaya Maju
2. Memprediksi karyawan yang berpotensi tinggi untuk keluar dari perusahaan berdasarkan data yang tersedia?

## Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

## Conclusion

1. Berdasarkan hasil analisis, faktor utama yang memengaruhi tingginya attrition rate di perusahaan Jaya Jaya Maju diantaranya:
- Pendapatan Bulanan (Monthly Income): Karyawan dengan pendapatan bulanan lebih rendah cenderung memiliki tingkat attrition yang lebih tinggi.
- Usia (Age): Usia karyawan juga menunjukkan pengaruh signifikan, di mana karyawan yang lebih muda cenderung memiliki tingkat keluar yang lebih tinggi.
- Total Tahun Bekerja (Total Working Years): Pengalaman kerja yang lebih banyak cenderung berhubungan dengan tingkat attrition yang lebih rendah.
- Jarak dari Rumah ke Tempat Kerja (Distance From Home): Karyawan yang tinggal lebih jauh dari tempat kerja cenderung memiliki tingkat keluar yang lebih tinggi.
- Tingkat Gaji Harian (Daily Rate) dan Tingkat Gaji Bulanan (Monthly Rate): Kedua faktor ini juga menunjukkan korelasi dengan attrition, meskipun pengaruhnya tidak sebesar faktor lain seperti pendapatan bulanan.
- Jumlah Perusahaan yang Pernah Dikerjakan (NumCompaniesWorked): Karyawan yang telah bekerja di banyak perusahaan sebelumnya cenderung lebih mungkin untuk keluar.
- Tingkat Kenaikan Gaji (PercentSalaryHike): Karyawan yang menerima kenaikan gaji lebih rendah cenderung lebih mungkin keluar.

2. Untuk memprediksi karyawan yang berpotensi tinggi untuk keluar, kita dapat menggunakan model prediktif seperti Random Forest yang telah dibangun. Model ini menggunakan kombinasi dari beberapa fitur utama yang diidentifikasi, seperti pendapatan bulanan, usia, total tahun bekerja, jarak dari rumah ke tempat kerja, dan lain-lain. Dengan model ini, HR dapat memasukkan data karyawan dan mendapatkan prediksi mengenai kemungkinan karyawan tersebut akan keluar, sehingga langkah-langkah pencegahan dapat diambil untuk mengurangi tingkat attrition.

### Rekomendasi Action Items

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

1.  Tinjau dan Tingkatkan Struktur Gaji
    Pertimbangkan peningkatan gaji atau insentif untuk karyawan dengan pendapatan bulanan lebih rendah, terutama bagi mereka yang menunjukkan kinerja baik, untuk meningkatkan retensi.

2.  Perbaiki Program Pengembangan Karir
    Buat jalur pengembangan karir dan program peningkatan keterampilan bagi karyawan muda agar mereka lebih termotivasi untuk bertahan dan berkembang di perusahaan.

3.  Tawarkan Fleksibilitas Kerja
    Pertimbangkan kebijakan bekerja dari rumah atau jadwal fleksibel bagi karyawan yang tinggal jauh dari kantor untuk meningkatkan kenyamanan mereka.

4.  Optimalisasi Kebijakan Kenaikan Gaji
    Pastikan proses kenaikan gaji transparan dan berorientasi pada kinerja, sehingga karyawan merasa dihargai dan termotivasi untuk tetap di perusahaan.

5.  Fokus pada Program Kesejahteraan Karyawan
    Kembangkan program kesejahteraan karyawan yang mencakup kesehatan fisik, mental, dan keseimbangan kerja-hidup untuk menciptakan lingkungan kerja yang suportif dan mencegah burnout.

6.  Membuat Program Kepercayaan dan Penghargaan
    Berikan penghargaan kepada karyawan yang telah bekerja lama atau yang memiliki kontribusi besar, sehingga meningkatkan loyalitas mereka terhadap perusahaan.
