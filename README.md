# praktikum5
praktikum5

# 1. Menginput data mahasiswa
    my sql> INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)    VALUES ('1812345', 'Ari Santoso', 'Laki-laki', '1999-10-11', 'NULL', 'Bekasi', 'NULL', 'NULL', 'DS001');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1823456', 'Dina Marlina', 'perempuan ', '1998-1120', 'NULL', 'Jakarta', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1834567', 'Rahmat Hidayat', 'Laki-laki', '1999-05-10', 'NULL', 'Bekasi', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1845678', 'Jaka Sampurna', 'Laki-laki', '2000-10-19', 'NULL', 'Cikarang', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1856789', 'Tia Lestari', 'Perempuan', '1999-02-15', 'NULL', 'Karawang', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1867890', 'Anton Sinaga', 'Laki-laki', '1998-08-22', 'NULL', 'Bekasi', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1912345', 'Listia Nastiti', 'perempuan', '2001-10-23', 'NULL', 'Jakarta', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1923456', 'Amira Jarisa', 'Perempuan', '2001-01-24', 'NULL', 'Karawang', 'NULL', 'NULL','DS004');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1934567', 'Laksana Mardito', 'Laki-laki', '1999-04-14', 'NULL', 'Cikarang', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1945678', 'Jura Marsina', 'Perempuan', '2000-05-10', 'NULL', 'Cikarang', 'NULL', 'NULL','NULL');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1956789', 'Dadi Martani', 'Laki-laki', '2001-08-29', 'NULL', 'Bekasi', 'NULL', 'NULL','DS005');
    INSERT INTO `praktikum5`.`mahasiswa` (`nim`, `nama`, `jenis_kelamin`, `tgl_lahir`, `jalan`, `kota`,`kodepos`, `no_hp`, `kd_ds`)VALUES ('1967890', 'bayu Laksono', 'Laki-laki', '1999-07-22', 'NULL', 'Cikarang', 'NULL', 'NULL','DS004');
![gambar 1](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss1.png)

# 2. Menginput data dosen
    my sql> INSERT INTO `praktikum5`.`dosen` (`kd_ds`, `nama`) VALUES ('DS001', 'Nofal arianto'); 
            INSERT INTO `praktikum5`.`dosen` (`kd_ds`, `nama`) VALUES ('DS002', 'Ario Talib'); 
            INSERT INTO `praktikum5`.`dosen` (`kd_ds`, `nama`) VALUES ('DS003', 'Ayu Rahmadina'); 
            INSERT INTO `praktikum5`.`dosen` (`kd_ds`, `nama`) VALUES ('DS004', 'Ratna Kumala'); 
            INSERT INTO `praktikum5`.`dosen` (`kd_ds`, `nama`) VALUES ('DS005', 'Vika Prasetyo');
![gambar 2](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss2.png)

# 3. Menginput data mata kuliah
    my sql> INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK001', 'Algoritma dan Pemrograman', '3');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK002', 'Praktikum Algoritma dan Pemrograman', '1');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK003', 'Teknologi Basis Data', '3');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK004', 'Praktikum Teknologi Basis Data', '1');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK005', 'Pemrograman Dasar', '3');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK006', 'Pemrograman Berorientasi Objek', '3');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK007', 'Struktur Data', '3');
            INSERT INTO `praktikum5`.`matakuliah` (`kd_mk`, `nama`, `sks`)
            VALUES ('MK008', 'Arsitektur Komputer', '2');
![gambar 3](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss3.png)

# 4. Menginput data jadwal mengajar
    my sql> INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS001', 'MK001', 'Senin', '10.00.00', '102');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS002', 'MK002', 'Senin', '13.00.00', 'Lab. 01');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS003', 'MK003', 'Selasa', '08.00.00', '201');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS004', 'MK004', 'Rabu', '10.00.00', 'Lab. 02');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS005', 'MK005', 'Selasa', '10.00.00', 'Lab. 01');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS006', 'MK006', 'Kamis', '09.00.00', 'Lab. 03');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS007', 'MK007', 'Rabu', '08.00.00', '102');
            INSERT INTO `praktikum5`.`jadwalmengajar` (`kd_ds`, `kd_mk`, `hari`, `jam`, `ruangan`)
            VALUES ('DS008', 'MK008', 'Kamis', '13.00.00', '201');
![gambar 4](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss4.png)

# 5. Menginput data KRS mahasiswa
    my sql> INSERT INTO krsmahasiswa
            VALUES ('1823456', 'MK001', 'DS001', '3', 'NULL'),
            ('1823456', 'MK002', 'DS002', '1', 'NULL'),
            ('1823456', 'MK003', 'DS003', '3', 'NULL'),
            ('1823456', 'MK004', 'DS004', '3', 'NULL'),
            ('1823456', 'MK007', 'DS007', '3', 'NULL'),
            ('1823456', 'MK008', 'DS008', '3', 'NULL');
![gambar 5](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss5.png)

# 6. Melakukan join table Mahasiswa dan Dosen
    my sql> SELECT * FROM mahasiswa JOIN dosen ON dosen.kd_ds=mahasiswa.kd_ds;
![gambar 6](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss6.png)

# 7. Melakukan join table Matakuliah dan Dosen
    my sql> SELECT * FROM matakuliah JOIN dosen ON dosen.kd_ds=matakuliah.kd_mk;

# 8. Lakukan join table JadwalMengajar, Dosen, dan Matakuliah
    my sql> SELECT jadwalmengajar.*,
            dosen.nama AS nama_dosen, matakuliah.nama AS nama_matakuliah
            FROM jadwalmengajar
            JOIN dosen ON jadwalmengajar.kd_ds=dosen.kd_ds
            JOIN matakuliah ON jadwalmengajar.kd_mk=matakuliah.kd_mk;
![gambar 7](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss7.png)

# 8. Lakukan join table KrsMahasiswa, mahasiswa, Matakuliah, dan Dosen
    my sql> SELECT krsmahasiswa.*,
            mahasiswa.nama AS nama_mahasiswa, matakuliah.nama AS nama_matakuliah, dosen.nama
            AS nama_dosen
            FROM krsmahasiswa
            JOIN mahasiswa ON krsmahasiswa.kd_ds=mahasiswa.kd_ds
            JOIN matakuliah ON krsmahasiswa.kd_mk=matakuliah.kd_mk
            JOIN dosen ON krsmahasiswa.kd_ds=dosen.kd_ds;
![gambar 8](https://github.com/alfaza-putra/Praktikum5/blob/main/screnshotPraktikum_5/ss8.png)
