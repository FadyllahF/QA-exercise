1. - Regression: untuk memastikan bahwa perubahan baru tidak memunculkan bug atau masalah baru di bagian lain yang sebelumnya telah berfungsi dengan baik. Regression testing dilakukan secara berkala setelah ada perubahan dalam kode, termasuk perubahan fitur, perbaikan bug, atau pembaruan, perangkat lunak.

   - Retest: pengujian yang dilakukan untuk memverifikasi bahwa bug atau masalah tertentu yang sebelumnya dilaporkan dan telah diperbaiki benar-benar telah diperbaiki dengan baik.

2. - Exploratory Testing: pengujian di mana para pengujian secara dinamis mengeksplorasi perangkat lunak tanpa rencana pengujian yang terperinci sebelumnya. Tujuanya menemukan bug atau masalah yang mungkin tidak tercakup dalam rencana pengujian formal.

   - Ad-hoc Testing: pengujian yang dilakukan tanpa rencana pengujian formal atau skenario yang telah ditentukan sebelumnya. Pengujian ad-hoc cenderung kurang terstruktur dan lebih acak.

3. - White Box Testing: White box testing, juga dikenal sebagai "structural testing" atau "glass box testing," adalah pendekatan pengujian di mana pengujian dilakukan dengan memahami struktur internal perangkat lunak.

   - Black Box Testting: Black box testing adalah pendekatan pengujian di mana pengujian dilakukan dari sudut pandang user tanpa memperhatikan struktur source code.

4. - Smoke Testing: pengujian yang dilakukan setelah selesai pengembangan atau pembaruan tertentu. Tujuannya adalah untuk memeriksa dapat dijalankan dengan baik atau tidak dalam pengujian.

   - Sanity Testing: pengujian yang lebih fokus untuk memverifikasi bahwa perbaikan atau perubahan tertentu pada kode telah diperbaiki dengan baik setelah masalah ditemukan dalam iterasi sebelumnya.

5. Test Planning, Requirement Analysis, Test Design, Test Construction, Test Reporting, Evaluation Test.

6. Planning, Analysis, Design, Development, Testing, Integration, Deployment, Maintenance.

7. - 400 Bad Request: request yang dikirimkan ke server tidak valid. Request mungkin format yang salah, parameter yang hilang, atau data yang tidak sesuai dengan yang diharapkan oleh server.

   - 401 Unauthorized: request memerlukan autentikasi yang tidak valid atau tidak ada. kita tidak memiliki izin untuk mengakses sumber daya yang diminta.

   - 403 Forbidden: klien tidak memiliki izin untuk mengakses data tertentu.

   - 404 Not Found: server tidak dapat menemukan data yang diminta oleh klien bisa juga URL yang diberikan tidak sesuai dengan URL yang ada di server.

   - 500 Internal Server Error: Terjadi kesalahan di pihak server saat mencoba memenuhi request.

   - 503 Service Unavailable: Server tidak dapat mengatasi request saat ini karena alasan sementara, seperti pemeliharaan atau overload.

8. Bug Priority, Communication, Isolation Critical Area, Regression Testing di Stable Area, Solusi Temporary, Defect Management, Feedback, Escalation, Redefine Strategy, Regular Testing

9. Test case analisis dan pengkategorian, Test fungsional, Test Integrasi, Bug Report, Dokumentasi.

10. –

11. –

12. Tahapan yang menggambarkan bagaimana suatu masalah atau bug di dalam applikasi ditemukan, dilaporkan, dianalisis, dan diperbaiki

EXERCISE:

1. Test Scenario
   A. Tidak terdapat warning saat mengisi form email dengan salah
   B. Tidak terdapat warning saat mengisi form password dengan salah
   C. Mengisi form email dengan password random masih bisa login
   D. Mengisi form login dengan benar, tetapi tidak sesuai Role saat sudah masuk home

2. Test Scenario
   A. Periksa link pada saat menekan login with sesuai(tombol Facebook ke halaman Facebook)
   B. Periksa persetujuan untuk facebook dapat mengakses aplikasi(seperti perijinan)

3. –

4. Test Scenario
   A. Add Product to cart:
   • Buka halaman rincian produk.
   • Pilih opsi "Tambah ke Keranjang" atau "Beli Sekarang".
   • Pastikan produk yang dipilih ditampilkan dengan benar pada halaman keranjang.
   • Verifikasi bahwa jumlah dan harga produk sesuai dengan yang diharapkan.

B. Update cart :
• Tambahkan beberapa produk ke dalam keranjang.
• Buka halaman keranjang.
• Ubah kuantitas produk untuk salah satu item.
• Pastikan perubahan kuantitas tercermin dengan benar dalam ringkasan pesanan.

C. Delete Product from cart:
• Tambahkan beberapa produk ke dalam keranjang.
• Buka halaman keranjang.
• Hapus satu atau lebih produk dari keranjang.
• Pastikan produk dihapus secara akurat dan total harga diperbarui sesuai.

D. Navigate between Screen:
• Buka halaman rincian produk.
• Tambahkan produk ke keranjang.
• Klik tombol "Lanjutkan Belanja" atau "Lihat Keranjang".
• Pastikan navigasi antara halaman rincian produk dan halaman keranjang berjalan lancar.

E. Manage cart:
• Pastikan stok produk yang terbatas ditampilkan dengan benar di halaman rincian produk.
• Tambahkan produk ke keranjang hingga stok hampir habis.
• Verifikasi apakah produk tidak bisa ditambahkan lagi jika stok habis di halaman keranjang.

F. Verify total cost:
• Tambahkan beberapa produk ke keranjang dengan harga yang berbeda.
• Buka halaman keranjang dan periksa total harga yang ditampilkan.
• Pastikan total harga dihitung dengan benar berdasarkan harga produk dan kuantitas.

5. Test Scenario

   A. Periksa halaman/popup Payment gateway dapat muncul atau tidak
   B. Check system behavior when valid virtual account is entered
   C. Check system behavior when invalid virtual account is entered.
   D. Periksa jumlah uang di aplikasi dengan payment gateway
   E. Periksa status saat ada perubahan (belum terbayar, sudah dibayar) pada aplikasi dan jasa payment gateway nya
   F. Periksa halaman/popup Payment gateway dapat tertutup atau tidak dan kembali ke aplikasi
