# Operasi Tiga Bilangan
### Format Masukan
Tiga nilai bilangan bulat.

### Format Keluaran
Sebuah bilangan bulat sesuai dengan ketentuan soal.

### Contoh Masukan
```
1.
2.
7.
```

### Contoh Keluaran
```
10.
```

### Code
```
program :- read(A), read(B), read(C), operasi(A,B,C,D), write(D), nl.
operasi(A,B,0,D):- D is A * B. 
operasi(A,B,C,D):- D is A + B + C.
:- program.
```
