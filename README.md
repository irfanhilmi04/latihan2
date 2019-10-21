# latihan2

## Mengenal apa itu operator 
. operator merupakan simbol-simbol yang digunakan untuk melakukan operasi tertentu
. operator adalah simbol atau tanda yang jika diletakkan pada dua buah operand (data) dapat menghasilkan sebuah hasil, operator berupa simbol yang digunakan untuk menyusun suatu ekspresi dengan melibatkan satu atau beberapa operand

### Langkah langkah
pada lab 2 kita mencoba untuk mengoprasikan operator, contoh :

langkah 1 dan 2 ambil input untuk mengisi nilai
1. a=input("inputkan nilai a: ")
2. b=input("inputkan nilai b: ") 
langkah 3 dan 4 menulis ulang nilai yang telah kita masukkan 
3. print("Variable a=",a)
4. print("Variable b=",b)
langkah 5 akan menggunakan variable a dan b, kita harus menggunakan '%s' agar sistem membacanya sebagai string bukan integer
5. print("Hasil penggabungan{1}&{0}=%s".format(a,b)%(a+b))
langkah 6 dan 7 akan mengkonversikan tipe data variable a dan b 
6. a=int(a)
7. b=int(b)
langkah 8 akan menjumlahkan nilai variable a dan b 
8. print("Hasil penjumlahan {1}+{0}=%d.format(a,b)%(a,b))
langkah 9 akan melakukan pembagian nilai variable a dengan b 
9. print("Hasil pembagian {1}/{0}=%d".format(a,b)%(a,b)) 
