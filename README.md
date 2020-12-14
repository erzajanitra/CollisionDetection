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
      
        <img src="https://github.com/erzajanitra/CollisionDetection/blob/master/gambar2%20buat%20PBO%20-%20COLLISON/sprite%20bounding.jpg"/>
      
         

# Alien 
Class Alien ini merupakan extends dari class Sprite yang dimana class Alien ini termasuk inheritance dari superclass Sprite. Berikut Method - method yang terdapat dalam class Alien: 
  1.  Constructor untuk menginisialisasi koordinat dan gambar Alien. Untuk mendapatkan gambar         alien nya itu sudah terdapat pada bagian superclass Sprite.
  2.  Methode untuk bergeraknya sebuah objek Alien: 
  
      <img src="https://github.com/erzajanitra/CollisionDetection/blob/master/gambar2%20buat%20PBO%20-%20COLLISON/alien%20move.jpg"/>
      
      Alien bergerak ke kiri, jika sebuah objek Alien itu keluar dari window sebelah kiri (x<0) maka objek Alien tersebut akal muncul kembali ke posisi awal (intial_x)
      
# Class Diagram 
<img src="https://github.com/erzajanitra/CollisionDetection/blob/master/gambar2%20buat%20PBO%20-%20COLLISON/class%20diagramcollision%20detection.jpg"/>

