
# 🐍 Python Basic Part 4 – OOP, Inheritance, Scope, dan Modules

![Python](https://img.shields.io/badge/Python-Basic-blue?logo=python)
![Level](https://img.shields.io/badge/Level-Beginner-green)
![Topic](https://img.shields.io/badge/Topic-OOP%20%7C%20Inheritance%20%7C%20Scope%20%7C%20Modules-orange)
![Status](https://img.shields.io/badge/Project-Academic-lightgrey)

Repository ini berisi **materi pembelajaran Python Basic Part 4** yang membahas konsep **Object Oriented Programming (OOP)** dalam Python, termasuk **Class, Object, Inheritance, Scope, dan Modules**.

Materi ini dijelaskan melalui **notebook Python** yang berisi lebih dari **110 cell pembelajaran** lengkap dengan contoh kode dan penjelasan.

---

# 📚 Materi yang Dipelajari

## 1️⃣ Python Classes and Objects

Class adalah blueprint untuk membuat object.

Contoh class sederhana:

class MyClass:
    x = 5

Membuat object dari class:

myObj = MyClass()
print(myObj.x)

Konsep yang dipelajari:

-Class
- Object
- Properties
- Methods
- Constructor __init__()
- self parameter
- Modify dan delete object properties

2️⃣ Python Inheritance

Inheritance memungkinkan sebuah class mewarisi properties dan method dari class lain.

Contoh:

class Person:
    def __init__(self, fname, lname):
        self.firstname = fname
        self.lastname = lname

class Student(Person):
    pass

Topik yang dibahas:

- Parent Class
- Child Class
- Method Inheritance
- super() function
- Multiple Inheritance

3️⃣ Python Scope

Scope menentukan dimana variabel dapat diakses.

Jenis scope:

- Local Scope
- Global Scope
- Nested Function Scope

Contoh:

x = 300

def myfunc():
    print(x)

myfunc()



4️⃣ Python Modules

- Module adalah file .py yang berisi fungsi, class, atau variabel yang bisa digunakan kembali.

Contoh import module:

import my_module

my_module.greeting("Budi")

Contoh built-in module:

import os

os.listdir()
os.getcwd()

---

📂 Struktur Repository

Tugas-Individu-4-ML/
│
├── Python_Individu5.ipynb
└── README.md

---

🎥 Video Penjelasan

Video presentasi materi dapat ditonton di YouTube:

Tambahkan link video YouTube di sini

---

👩‍💻 Author

Tasri Zulfitriyati (231001074)

---

📌 Tujuan Project

Project ini dibuat untuk:

Tugas pembelajaran Python
Memahami konsep OOP di Python
Dokumentasi pembelajaran programming

---

📜 License

Project ini dibuat untuk tujuan pembelajaran dan akademik.
---














