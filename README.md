![image](images/image1.png)
![image](images/image2.png)
![image](images/image3.png)
![image](images/image4.png)


Pengujian menunjukkan bahwa server WebSocket di port 2000 dapat mengelola hingga tiga klien secara simultan dengan koneksi yang stabil. Setiap klien berhasil tersambung tanpa hambatan dan melakukan pertukaran data dengan lancar. Sistem broadcast beroperasi secara real-time, mendistribusikan pesan dari satu klien ke klien lainnya tanpa penundaan berarti. Tidak terdapat blocking selama proses komunikasi berlangsung, memastikan pengalaman chat yang responsif. Keandalan ini dicapai berkat arsitektur asynchronous yang mendasari seluruh sistem. Perpaduan tokio_websockets dengan broadcast channel dari Tokio terbukti sangat efektif untuk kebutuhan aplikasi chat sederhana.