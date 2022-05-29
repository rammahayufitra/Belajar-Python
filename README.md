# Belajar-Python

**Chapter-Cython**
depedensi yang diperlukan dalam chapter ini adalah:</br>
(1). opencv (pip3 install opencv-python)</br>
(2). cython (pip3 install cython)</br> 

Cara Konversi **Python** ke **Cython** </br> 
(1). clone repo https://github.com/rammahayufitra/Belajar-Python/tree/main/Cython/cython-opencv-streamingwebcam </br>
(2). cd Belajar-Python/Cython/cython-opencv-streamingwebcam </br> 
(3). didalam folder cython-opencv-streamingwebcame terdapat beberapa file streaming_webcam_.py, streaming_webcame.pyx, setup.py, test.py. selain, keemapt file ini silahkan dihapus saja.</br> 
(4). sebenarnya proses python ke cython hanya membutuhkan file streaming_webcam.pyx, setup.py. sedangkan file streaming_webcam_.py hnaya digunakan untuk membuat program python-nya saja. setalah program di streaming_webcam_.py berhasil dijalankan maka copy semua program dan paste ke file streaming_webcam.pyx.</br>
(5). kemudian running file setup.py dengan cara: python3 setup.py build_ext --inplace. nanti akan muncul beberapa file-file baru dengan extensi c dan so seperti yang diperlihatkan di repo ini.</br> 
(6). untuk menjalankan cython-nya, running file test.py dengan cara: python3 test.py 

