# Fundamental Python

Panduan ini berisi konsep dasar dan fundamental dalam pemrograman menggunakan bahasa Python. Python adalah bahasa pemrograman yang mudah dipelajari, memiliki sintaks sederhana, dan sangat populer untuk pengembangan web, data science, AI, dan banyak lagi.

## Instalasi Python

1. Unduh Python dari [situs resmi Python](https://www.python.org/downloads/).
2. Ikuti langkah instalasi sesuai sistem operasi Anda.
3. Verifikasi instalasi dengan menjalankan perintah berikut di terminal atau command prompt:
   ```bash
   python --version
   ```
   atau (tergantung konfigurasi)
   ```bash
   python3 --version
   ```
   Anda akan melihat versi Python yang terinstal.

## Struktur Dasar Program Python

Setiap program Python dapat ditulis langsung dalam file `.py`. Berikut adalah contoh program dasar:

```python
# Program Python pertama
print("Hello, World!")
```

### Menjalankan Program Python

1. Simpan file Python (misalnya, `main.py`).
2. Jalankan program menggunakan perintah berikut:
   ```bash
   python main.py
   ```

## Konsep Dasar Python

### 1. Variabel dan Tipe Data

Python adalah bahasa dengan tipe data dinamis:

```python
# Deklarasi variabel
name = "Alice"  # String
gender = 'F'      # Karakter
age = 25         # Integer
height = 5.7     # Float
is_student = True # Boolean

print(name, age, height, is_student)
```

### 2. Struktur Kontrol

#### a. Pernyataan If-Else

```python
age = 20
if age >= 18:
    print("Dewasa")
else:
    print("Belum Dewasa")
```

#### b. Perulangan

- **For Loop**:

```python
for i in range(5):
    print(i)
```

- **While Loop**:

```python
count = 0
while count < 5:
    print(count)
    count += 1
```

### 3. Fungsi

Definisi dan pemanggilan fungsi:

```python
def greet(name):
    return f"Hello, {name}!"

message = greet("Alice")
print(message)
```

### 4. List dan Dictionary

- **List**:

```python
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print(fruits)
```

- **Dictionary**:

```python
person = {"name": "Alice", "age": 25, "gender": "F"}
print(person["name"])
```

## Tools Pendukung

- **IDLE**: Editor bawaan Python.
- **Jupyter Notebook**: Ideal untuk analisis data dan pembelajaran.
- **VS Code**: Editor teks dengan banyak plugin untuk Python.

## Tips dan Praktik Terbaik

1. Gunakan nama variabel yang deskriptif.
2. Ikuti panduan PEP8 untuk gaya penulisan kode.
3. Selalu tangani error menggunakan blok `try-except`.

## Sumber Belajar Tambahan

- [Dokumentasi Resmi Python](https://docs.python.org/3/)
- [W3Schools Python Tutorial](https://www.w3schools.com/python/)
- [Real Python](https://realpython.com/)

