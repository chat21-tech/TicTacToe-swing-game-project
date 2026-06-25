# Aplikasi Game Tic-Tac-Toe dengan Java Swing, Login, dan Statistik

## Informasi Mahasiswa
- Nama: Chatrine Dwi Ratulina Siregar
- NRP: 5026251025
- KELAS: E
- MATA KULIAH: PEMROGRAMAN DASAR

## Deskripsi Project
Project ini adalah aplikasi game Tic-Tac-Toe berbasis GUI menggunakan Java Swing. Aplikasi ini dilengkapi dengan sistem login menggunakan database, pencatatan statistik permainan, dan papan peringkat Top 5 pemain terbaik. Pemain bermain sebagai X melawan komputer sebagai O.

## Fitur Aplikasi
- Login menggunakan database MariaDB
- Bermain Tic-Tac-Toe melawan komputer menggunakan Java Swing GUI
- Mencatat jumlah menang, kalah, seri, dan skor setelah setiap permainan
- Menampilkan statistik pribadi pemain
- Menampilkan Top 5 pemain terbaik menggunakan JTable

## Database
- Database yang digunakan: MariaDB melalui HeidiSQL
- Nama tabel: players
- Kolom: id, username, password, wins, losses, draws, score

## Cara Menjalankan Program
1. Install MariaDB dan buat database
2. Import file `database/schema.sql` ke HeidiSQL
3. Buka project di IntelliJ IDEA
4. Tambahkan MariaDB JDBC driver (`mariadb-java-client-3.3.3.jar`) ke project libraries
5. Buka `DatabaseManager.java` dan sesuaikan setting database:
6. Jalankan `Main.java`

## Penjelasan Class
| Class             | Tanggung Jawab                                                                              |
|                   |                                                                                             |
| `Main`            | Titik awal program, membuka Login Window                                                    |
| `DatabaseManager` | Mengurus koneksi JDBC ke MariaDB                                                            |
| `Player`          | Class model yang menyimpan data pemain                                                      |
| `PlayerService`   | Mengurus login, update statistik, dan Top 5 pemain                                          |
| `GameLogic`       | Mengurus validasi gerakan, pengecekan pemenang, pengecekan seri, dan gerakan komputer       |
| `LoginFrame`      | Tampilan GUI untuk login                                                                    |
| `MainMenuFrame`   | Tampilan GUI untuk navigasi menu utama                                                      |
| `GameFrame`       | Tampilan GUI untuk bermain game                                                             |
| `StatisticsFrame` | Tampilan GUI untuk menampilkan statistik pribadi                                            |
| `TopScorersFrame` | Tampilan GUI untuk menampilkan Top 5 pemain menggunakan JTable                              |

## Perhitungan Skor
| Hasil | Skor |
|       |      |
| Menang| +10  |
| Seri  | +3   |
| Kalah | +0   |

## Screenshots
Bukti Screenshots ada di folder screenshots

## Link GitHub


## Link Video YouTube
[Video Demonstrasi](https://youtube.com/[LINK VIDEO KAMU])
