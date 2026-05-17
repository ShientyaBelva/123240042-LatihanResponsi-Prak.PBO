# 123240042-LatihanResponsi-Prak.PBO - Todo List App

## Deskripsi
Aplikasi Todo List berbasis Java Swing dengan implementasi database MySQL dan pola arsitektur MVC.

## Perubahan yang Dilakukan

### 1. Implementasi Database MySQL
Data tugas yang sebelumnya disimpan menggunakan Fake Repository diubah menjadi penyimpanan database MySQL.

### 2. Implementasi MVC
- Model:
  - TodoTask
  - TodoRepository
  - InsertTodoDTO
  - MySQLTodoRepository

- View:
  - TodoView

- Controller:
  - TodoController

### 3. Database Connection
Menambahkan class DatabaseConnection untuk mengatur koneksi database.

## Database
Nama database: todo_app;
