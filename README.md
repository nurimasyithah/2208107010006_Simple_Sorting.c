Nuri Masyithah

2208107010006_Simple_Sorting.c


**Cara Menjalankan Program:**

1. Pastikan Anda memiliki compiler C yang terinstal di sistem Anda, seperti GCC.
2. Unduh file sumber `sorting.c`.
3. Buka terminal atau command prompt.
4. Arahkan terminal ke direktori tempat Anda menyimpan file `sorting.c`.
5. Kompilasi program dengan menjalankan perintah berikut di terminal:

   ```
   gcc sorting.c -o sorting
   ```

   Pastikan tidak ada kesalahan saat kompilasi.
   
6. Setelah berhasil dikompilasi, jalankan program dengan mengetikkan:

   ```
   ./sorting
   ```

Program akan mulai menguji dan mengurutkan array dengan berbagai ukuran menggunakan tiga algoritma pengurutan yang berbeda.

7. Setelah program selesai berjalan, Anda dapat melihat hasil pengurutan dan waktu eksekusi yang dicatat dalam file `sortingResults.txt`.


**Fungsi-fungsi yang Digunakan dalam Kode Program:**

1. `generateRandomNumbers(int *array, int size)`: Fungsi ini digunakan untuk mengisi array dengan bilangan acak.

2. `bubbleSort(int *array, int size)`: Implementasi algoritma Bubble Sort untuk mengurutkan array.

3. `selectionSort(int *array, int size)`: Implementasi algoritma Selection Sort untuk mengurutkan array.

4. `insertionSort(int *array, int size)`: Implementasi algoritma Insertion Sort untuk mengurutkan array.

5. `copyArray(int *source, int *destination, int size)`: Fungsi ini digunakan untuk menyalin isi array sumber ke array tujuan.

6. `performSort(const char *sortName, void (*sortFunction)(int*, int), int *data, int size, FILE *file)`: Fungsi ini digunakan untuk melakukan pengurutan array menggunakan algoritma yang ditentukan, mencatat waktu eksekusi ke file, dan menulis hasil pengurutan ke file.

Dengan mengikuti langkah-langkah di atas, Anda dapat menjalankan program dan menguji berbagai algoritma pengurutan pada array dengan ukuran yang berbeda.
