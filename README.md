# Tugas Kelompok PBO - Collision Detection

Contributor : 
  1. Kirana Zea Sachdania Mays - 081
  2. Erza Janitradevi - 153
  3. Rayhan Daffa Alhafish - 227 
  
# APPLIKASI COLLISION DETECTION 
Banyak aplikasi games yang menggunakan atau yang meng-handle collision, terutama permainan arkade. Permainan arkade sendiri adalah sebuah mesin permainan hiburan yang dioperasikan dengan koin yang terpasang di tempat-tempat bisnis, dan pusat permainan hiburan. Bentuk kebayakan permainan arkade adalah permainan video, mesin pinbol, dan lainnya. 

Karakteristik dari games yang berdimensi 2D yaitu terdapatnya program yang berisi objek - objek yang bergerak. Objek - objek tersebut dapat bertumbukan (collision) satu sama lain. Oleh karena itu, untuk dapat menangani collision yang berlebihan maka diperlukannya sebuah cara dengan menggunakan Collision Detection. 

# Cara Kerja Program 
Berdasarkan karakteristik dari games berdimensi 2D, terdapat sebuah class yang bertugas mengenkapsulasi objek - objek yang dapat bergerak di suatu game. Objek - objek yang bergerak tersebut adalah Alien, Spaceship, dan Missile. Kemudian, objek - objek tersebut akan di inisialisasi pada saat objek Board dibuat dan akan objek - objek tersebut dipakai saat game dijalankan. 

# Sprite 
Class Sprite merupakan sebuah class yang bertugas untuk mengenkapsulasi objek - objek yang dapat bergerak di suatu game. Pada class ini, terdapat bebrpa methode yang akan digunakan pada class lainya. Method - method teresebut antara lain : 
  1.  Constructor yang akan menginisialisasi koordinat x, y dan variable visible
  2.  Method - method yang digunakan untuk mendapatkan gambar, dan dimensi. Dimensi disini yaitu       height and width pada gambar tersebut
  3.  Getter dan setter untuk variabel dalam class
  4.  Methode yang bertugas untuk mengatur visibiltas
  5.  Methode Bounding: 
      Methode ini akan membuat Rectangle baru menggunakan koordinat dan ukuran yang telah             didapatkan dengan kata lain semua objek dianggap Rectangle
      
# Alien 
  
  
  
  
  
  
# Class Diagram Collision Detection 

