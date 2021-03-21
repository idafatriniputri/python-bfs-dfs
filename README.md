# BFS dan DFS menggunakan Python

Nama  : Ida Fatrini Putri
NPM   : 1184113
Kelas : D4 TI 3A

Penerapan BFS sendiri merupakan algoritma yang menjalankan penelitian secara berkembang yang mendatangi simpul secara preorder. Algoritma ini membutuhkan suatu antrian untuk menyimpan simpul yang dikunjungi.
Cara kerjanya sendiri di dalam algoritma adalah simpul yang telah dikunjungi disimpan dalam sebuah antrian. Sedangkan

Penerapan DFS adalah salah satu algoritma penel pencarian strruktur graf atau pohon berdasarkan kedalaman. Selanjutnya simpul ditelusuri dari root, setelah itu ke salah satu simpul lainnya.
Contohnya adalah pohon biner.

Pada sistem ini langkah awalnya adalah melakukan inputan awal dan tujuan peta yang sudah ditentukan.
Setelah itu memasukkan antrian paling depan ke variable jalur. Variable state akang menyimpan simpul
yang ditentukan. Contohnya jalur D,E maka akan disimpan di jalur E.
Periksa state yang dipilih sama atau tidak dengan tujuan yang ditentukan, jika iya maka akan menentukan
jalur kembali. 
Jika state yang dipilih tidak sama dengan tujuan, periksa pengunjung dari state tersebut. 
Misalkan state tidak ada pengunjung lakukan pemeriksaan cabang. Terakhir adalah tandai state yang telah dikunjungi.
