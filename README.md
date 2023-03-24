Kodu Derleme ve Çalıştırma

Not: Bilgisayarınızda opencv'nin kurulu olması gerekmektedir.

1- g++ -std=c++17 -o foto fotografCekme.cpp `pkg-config --cflags --libs opencv4`

Not: "pkg-config --cflags --libs opencv4" 

komutunun başında ve sonunda " ` " tırnağı vardır ancak buraya eklerken gözükmemektedir.

2- ./foto
