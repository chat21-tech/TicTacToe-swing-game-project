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
1. Main = Titik awal program, membuka Login Window                                               
2. DatabaseManager = Mengurus koneksi JDBC ke MariaDB                                                           
3. Player = Class model yang menyimpan data pemain                                                  
4. PlayerService = Mengurus login, update statistik, dan Top 5 pemain                                          
5. GameLogic = Mengurus validasi gerakan, pengecekan pemenang, pengecekan seri, dan gerakan komputer       
6. LoginFrame = Tampilan GUI untuk login                                                                    
7. MainMenuFrame = Tampilan GUI untuk navigasi menu utama                                                      
8. GameFrame = Tampilan GUI untuk bermain game                                                             
9. StatisticsFrame = Tampilan GUI untuk menampilkan statistik pribadi                                            
10. TopScorersFrame = Tampilan GUI untuk menampilkan Top 5 pemain menggunakan JTable                             

## Perhitungan Skor
1. Menang +10  
2. Seri +3   
3. Kalah +0   

## Screenshots
Bukti Screenshots ada di folder screenshots

## Link GitHub
https://github.com/chat21-tech/TicTacToe-swing-game-project

## Link Video YouTube
https://youtu.be/HK_8Ubm5NeY
