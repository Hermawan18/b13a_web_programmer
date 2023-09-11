Luas lingkaran
flow:
pi dikali jari" pangkat 2

pseudocode:
1. deklarasikan pi assign 3.14
2. deklarasikan jari" assign 5
3. deklarasikan result assign pengkalian dari pi dan jari"

Keliling lingkaran
flow:
1. 2 dikali pi dikali jari" atau
2. pi dikali diameter

pseudocode:
1. deklarasikan pi assign 3.14
2. deklarasikan jari" assign 5
3. deklarasika diameter assign 10 (5 * 2)

coding:
var display = document.getElementById('luas');
var display2 = document.getElementById('keliling');
var r = 5;
var p = 3.14;

// Luas lingkaran
var luas = p * r * r;
 display.innerHTML = "<p>Luas lingkaran : " + luas.toFixed(1) + " cm</p>"

 // Keliling lingkaran
var keliling = 2 * p * r;
display2.innerHTML = "<p>Keliling lingkaran : " + keliling.toFixed(1) + " cm</p>"
