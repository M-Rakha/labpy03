# Latihan Program Python

## Programs

## Random Number Generator (latiha1.py) 
Sebuah program yang akan menggenerate angka random kurang dari 0,5 berdasrkan input user.

![gambar](https://github.com/M-Rakha/labpy03/blob/1696cf8fc99b2e4f84fadb712940dfd7703a7951/Cuplikan%20layar%202024-11-03%20204135.png)

## Algorithm

```python
1. Import random library
2. Minta input N dari user
3. Loop N times:
   - Generate random number between 0 and 1
   - Bagi dengan 2 untuk memastikan angka < 0.5
   - Tampilkan output
4. Print "Selesai" saat selesai
```

## Example Output

```python
Masukkan nilai N: 5
data ke: 1 => 0.17294922043570056
data ke: 2 => 0.08717360127477924
data ke: 3 => 0.050516076545020832
data ke: 4 => 0.27535124215716744
data ke: 5 => 0.39262323600723776
Selesai
```

## Investment Profit Calculator (latihan2.py)
Program yang menghitung laba bulanan untuk investasi selama 8 bulan dengan tingkat laba yang bervariasi.

![gambar](https://github.com/M-Rakha/labpy03/blob/154efa8f9c34baa5ee984652ea95f37d18a4d14e/Cuplikan%20layar%202024-11-03%20211202.png)

## Algorithm

```python
1. Tetapkan modal awal = 100.000.000
2. Buat list kosong untuk menyimpan laba bulanan
3. Lakukan perulangan selama 8 bulan:
   - Bulan 1-2: laba 0%
   - Bulan 3-4: laba 1%
   - Bulan 5-7: laba 5%
   - Bulan 8: laba 2%
4. Untuk setiap bulan:
   - Hitung laba berdasarkan persentase
   - Tampilkan laba bulanan
   - Simpan laba dalam list
5. Hitung dan tampilkan total laba
```

## Example Output

```python
laba bulan ke- 1 sebesar: 0
laba bulan ke- 2 sebesar: 0
laba bulan ke- 3 sebesar: 10000000.0
laba bulan ke- 4 sebesar: 10000000.0
laba bulan ke- 5 sebesar: 50000000.0
laba bulan ke- 6 sebesar: 50000000.0
laba bulan ke- 7 sebesar: 50000000.0
laba bulan ke- 8 sebesar: 20000000.0
Total laba adalah: 190000000.0
```

## ATM Sederhana (latihan3.py)
Program ini akan mensimulasikan mesin ATM sederhana dengan fitur penarikan uang dan pengecekan saldo.











