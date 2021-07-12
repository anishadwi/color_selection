# AnalisisColor
Ini merupakan tugas kuis 2 Image Processing dengan menggunakan Bahasa Pemrograman Python

Dalam mengenali sebuah warna disini menggunakan computer vision yaitu teknologi opencv python jadi yang harus dilakukan adalah menginstal opencv.

Install Open Cv (pip install numpy pandas opencv-python) 
   
Program colorRecognition.py untuk mengenali warna RGB berdasarkan gambar yang dipilih dan menampilkan nama dari warna tersebut dimana sudah ada dataset warna pada color.csv

![image](https://user-images.githubusercontent.com/58914195/125000567-e22a7f80-e07a-11eb-8123-59080124c2ec.png)

Jalankan Program (python colorRecognition.py) ,setelah itu klik kanan dua kali maka akan menampilkan RGB dan jenis warna
![image](https://user-images.githubusercontent.com/58914195/125000852-844a6780-e07b-11eb-886a-c75d7e912f72.png)

Program selectImage.py untuk mengenali warna yang akan dicrop/dipisah/dipotong menjadi mask lain berdasarkan warna yang dipilih disini menggunakan warna HSV yang nantinya akan menampilkan nilai dari warna HSV

Jalankan Program (python SelectImage.py --image warnatokobenang.png) , setelah itu select gambar warna yang dipilih ,lalu tekan c untuk menampilkan mask atau memisahkan warna gambar
![image](https://user-images.githubusercontent.com/58914195/125001114-1c485100-e07c-11eb-821d-80749e55b173.png)

maka program akan mengenali warna yang dipilih dengan menampilkan warna yang ditampilkan kemudian membuat mask baru
![image](https://user-images.githubusercontent.com/58914195/125001251-67fafa80-e07c-11eb-8e52-3ef82bf35cfc.png)

jika kita liat pada command land maka akan menampilkan detail warna HSV yang kita pilih
![image](https://user-images.githubusercontent.com/58914195/125001400-bad4b200-e07c-11eb-8af6-d01342f5b6c4.png)



SUMBER
https://youtu.be/bWVEXya08bw
https://towardsdatascience.com/building-a-color-recognizer-in-python-4783dfc72456
https://youtu.be/861Nt2iPy1I

