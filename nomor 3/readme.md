output dari program tersebut adalah 
"Programmer writes code"
"Employee attends meeting"

ada method yang menggunakan subclass version, dan ada juga yang menggunakan superclass version. hal ini dikarenakan adanya perbedaan status method di dalam class Programmer: method work() adalah method yang telah dioverride, sedangkan attendMeeting() adalah method inherited. oleh karena itu, Java menjalankan versi terbaru milik subclass , sementara method attendMeeting() tidak diubah sama sekali oleh Programmer, sehingga Java tetap menjalankan versi asli milik superclass Employee