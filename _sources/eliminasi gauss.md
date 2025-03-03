---
title: eliminasi gauss

---

## Eliminasi gauss
**Metode Eliminasi Gauss**
Metode penyelesaian gauss adalah cara untuk menyelesaikan sistem persamaan liniear dengan mengubahnya menjadi bentuk yang lebih sederhana, sehingga lebih mudah dihitung. Caranya adalah dengan mengubah persamaan satu persatu, menghilangkan variabel secara bertahap, sampai akhirnya bisa menemukan nilai dari setiap variabel.

Berikut adalah langkah langkah menyelesaikan sistem persamaan linear menggunakan metode eliminasi gauss, serta menampilkan solusinya secara grafis menggunakan GeoGebra


---

**Sistem Persamaan Linear yang digunakan**
x + y + z = 6
2x - y + 3z = 11
3x + 4y + z = 19

*Matriksnya, yaitu:*
1         1       1        |6
2         3       1        |11
3         5       2        |19

**Eliminasi Gauss(Operasi baris)**
Membuat elemen (2,1) dan (3,1) menjadi nol

**a. Elemen pertama (2,1)**
- $B_2= B_2 - 2B_1$
- $B_3 = B_3 - 3B_1$
Hasilnya:
1    1    1    |6
0    1    -1   |-1
0    2    -1    |1

**b. Elemen kedua (3,2)**
$B_3 = B_3 - 2B_2$
Hasilnya:
1    1    1    |6
0    1    -1    |-1
0    0    1    |3

**Subsitusi Mundur**
Dari baris ketiga 
z = 3
Subsitusikan z=3 ke baris kedua:
y-3= -1
y=2
Subsitusikan y=2 dan z=3 ke baris pertama:
x + 2 + 3 = 6
x= 1

**Solusi**
Solusi sistem persamaan ini adalah:
(x,y,z)=(1,2,3)
 

---

**Contoh dengan GeoGebra**
![GeoGebra KAL](https://hackmd.io/_uploads/SyWuGXmoyl.png)
[https://www.geogebra.org/classic/psn4sb4g](https://)

