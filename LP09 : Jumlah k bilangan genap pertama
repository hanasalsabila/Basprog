# Jumlah K Bilangan Genap Pertama
Diketahui sebuah list berisi bilangan bulat. Buatlah sebuah program prolog yang dapat menghitung jumlah k bilangan genap pertama yang terdapat pada list tersebut.

### Format Masukan
Masukan terdiri dari sebuah list berisi bilangan bulat dan sebuah bilangan bulat k.

### Format Keluaran
Jumlah k bilangan genap pertama

### Contoh Masukan
```
[2,4,1,6,7,8,3].
3.
```

### Contoh Keluaran
```
12
```

### Code
```
program:- read(List), read(K), sumgen(List,K,X), write(X),nl.
sumgen(_,0,0).
sumgen([H|T],K,X):- K>0, 0 is mod(H,2), K1 is K-1, sumgen(T,K1,X1), X is X1+H.
sumgen([_|T],K,X):- sumgen(T,K,X).
:- program.
```
