<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registrasi</title>
</head>
<body>
    <h2>Form Registrasi Mahasiswa Baru</h2>
    <fieldset>
        <legend>Data Calon Mahasiswa</legend>
        <form action="">
            <p>Nama Calon Mahasiswa : <input type="text"placeholder="Masukan nama anda"required></p>
            <p>Tempat Lahir : <input type="text"placeholder="Isi Tempat Lahir anda"required></p>
            <p>Jenis Kelamin : <input type="radio"name="jenis_kelamin">Laki-Laki
                <input type="radio"name="jenis_kelamin">Perempuan
                <input type="radio"name="jenis_kelamin">Tidak punya</p>
            <p>Alamat : <input type="text"placeholder="masukan alamat anda"required></p>
            <p>Tanggal Lahir : <input type="date"required></p>
            <P>No NIK : <input type="text"placeholder="No NIK"required></P>
            <P>NISN : <input type="text"placeholder="NISN"required></P>
            <p>AGAMA :
                <select name="" id="">
                    <option value="">Hindu</option>
                    <option value="">buddha</option>
                    <option value="">konghucu</option>
                    <option value="">Kristen katolik</option>
                    <option value="">Kristen Protestan</option>
                    <option value="">Islam</option>
                </select>
            </p>
            </p>
            <p>RT : <input type="text"placeholder="Contoh RT 02"required></p>
            <p>RW : <input type="text"placeholder="Contoh RW 02"required></p>
            <p>Nama Desa : <input type="text"placeholder="Desa Anda"></p>
            <p>Nama Kelurahan : <input type="text"placeholder="Nama Kelurahan Anda"required></p>
            <p>Nama Kecamatan : <input type="text"placeholder="Nama Kecamatan Anda"required></p>
            <p>Masukan Email : <input type="email"placeholder="Contoh@gmail.com"required></p>
            <p>Masukan No.Handphone : <input type="tel"placeholder="8012********"required></p>

        </form>
    </fieldset>
    <br>
    <fieldset>
        <legend>Data Ayah</legend>
        <form action="">
            <p>Nama Ayah : <input type="text"placeholder="Nama Ayah"required></p>
            <p>Tahun Lahir : <input type="text"placeholder="Contoh 1945"required></p>
            <p>Jenjang Pendidikan :
                <select name="" id="">
                    <option value="">SD</option>
                    <option value="">SMP</option>
                    <option value="">SMA</option>
                    <option value="">SMK</option>
                    <option value="">S1</option>
                    <option value="">S2</option>
                </select>
            </p>
            <P>Pekerjaan : <input type="text"placeholder="Pekerjaan Ayah"required></p>
            Penghasilan Per-Bulan : <input type="radio" name="gaji_rata_rata"required>3-5 Juta
            <input type="radio" name="gaji_rata_rata">5-10 Juta
            <input type="radio" name="gaji_rata_rata">10-15 Juta
            <input type="radio" name="gaji_rata_rata">Diatas 15 Juta
            <input type="radio" name="gaji_rata_rata">Dibawah 3 Juta</p>
        </form>
    </fieldset>
    <br>
    <fieldset>
        <legend>Data IBU</legend>
        <form action="">
            <p>Nama IBU : <input type="text"placeholder="Nama IBU"required></p>
            <p>Tahun Lahir : <input type="text"placeholder="Contoh 1945"required></p>
            <p>Jenjang Pendidikan :
                <select name="" id="">
                    <option value="">SD</option>
                    <option value="">SMP</option>
                    <option value="">SMA</option>
                    <option value="">SMK</option>
                    <option value="">S1</option>
                    <option value="">S2</option>
                </select>
            </p>
            <P>Pekerjaan : <input type="text"placeholder="Pekerjaan IBU"required></p>
            Penghasilan Per-Bulan : <input type="radio" name="gaji_rata_rata"required>3-5 Juta
            <input type="radio" name="gaji_rata_rata">5-10 Juta
            <input type="radio" name="gaji_rata_rata">10-15 Juta
            <input type="radio" name="gaji_rata_rata">Diatas 15 Juta
            <input type="radio" name="gaji_rata_rata">Dibawah 3 Juta
            <input type="radio" name="gaji_rata_rata">IRT
        </p>
        </form>
    </fieldset>
    <br>
    <fieldset>
        <legend>Data Wali</legend>
        <form action="">
            <p>Nama Wali : <input type="text"placeholder="Nama Wali"required></p>
            <p>Tahun Lahir : <input type="text"placeholder="Contoh 1945"required></p>
            <p>Jenjang Pendidikan :
                <select name="" id="">
                    <option value="">SD</option>
                    <option value="">SMP</option>
                    <option value="">SMA</option>
                    <option value="">SMK</option>
                    <option value="">S1</option>
                    <option value="">S2</option>
                </select>
            </p>
            <P>Pekerjaan : <input type="text"placeholder="Pekerjaan Wali"required></p>
            Penghasilan Per-Bulan : <input type="radio" name="gaji_rata_rata"required>3-5 Juta
            <input type="radio" name="gaji_rata_rata">5-10 Juta
            <input type="radio" name="gaji_rata_rata">10-15 Juta
            <input type="radio" name="gaji_rata_rata">Diatas 15 Juta
            <input type="radio" name="gaji_rata_rata">Dibawah 3 Juta</p>

    </fieldset>
    <br>
    <fieldset>
         <legend>Pilih Jurusan Anda</legend>
    <p>Pilih Jurusan :
        <select name="" id=""required>
            <option value="">Manajemen</option>
            <option value="">Hukum</option>
            <option value="">Kedokteran</option>
            <option value="">Matematika</option>
            <option value="">Geologi</option>
            <option value="">Geodasi</option>
            <option value="">Sistem informasi</option>
            <option value="">Teknik Komputer</option>
            <option value="">Teknik Informatika</option>
            <option value="">Arsitektur</option>
        </select>
    </fieldset>   
    <br>
    <p>Biaya Pendaftaran : <input type="text"value="Rp.250,000"disabled></p>
        <details> 
            <summary>Detail Ketentuan : </summary>
            <p><input type="checkbox"required> saya menyatakan dengan sesungguhnya bahwa isian data dalam formulir ini adalah benar,apabila data tersebut ternyata tidak benar atau palsu saya bersedia menerima sanksi berupa pembatalan sebagai calon Mahasiswa</p>
        </details>
        <br>
       <p style="text-align: center;"> <button type="submit">Input Data</button></p>
    </form>



</body>
</html>
