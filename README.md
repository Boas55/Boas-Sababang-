# Boas-Sababang-
welcome to my channel 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulir Pendaftaran Siswa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: ##8080ab97;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffbe955e;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h2 {
            text-align: center;
            color: #333;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        label {
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }
        input, select, textarea {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ffbd40b6;
            border-radius: 5px;
            font-size: 16px;
        }
        input[type="submit"] {
            background-color: #1c15ff;
            color: white;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        .form-group {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Formulir Pendaftaran</h2>

        <form action="#" method="post">
            <!-- Biodata Siswa -->
            <div class="form-group">
                <label for="nama">Nama Lengkap:</label>
                <input type="text" id="nama" name="nama" placeholder="Masukkan Nama Lengkap Anda" required>
            </div>
            

            <div class="form-group">
                <label for="email">Email:<br>
                </label>
                <input type="email" id="email" name="email" placeholder="Masukkan Email Anda" required>
            </div>

            <div class="form-group">
                <label for="phone">Nomor Telepon:</label>
                <input type="tel" id="phone" name="phone" placeholder="Masukkan Nomor Telepon" required>
            </div>

            <div class="form-group">
                <label for="alamat">Alamat Lengkap:</label>
                <textarea id="alamat" name="alamat" rows="4" placeholder="Masukkan Alamat Lengkap Anda" required></textarea>
            </div>

            <div class="form-group">
                <label for="tanggal_lahir">Tanggal Lahir:<br></label>
                <input type="date" id="tanggal_lahir" name="tanggal_lahir" required>
            </div>

            <!-- Pemilihan Jurusan -->
            <div class="form-group">
                <label for="jurusan">Pilih Jurusan:</label>
                <select id="jurusan" name="jurusan" required>
                    <option value="">-- Pilih Jurusan --</option>
                    <option value="Teknik Informatika">Teknik Informatika</option>
                    <option value="Sistem Informasi">Sistem Informasi</option>
                    <option value="Manajemen Bisnis">Manajemen Bisnis</option>
                    <option value="Akuntansi">Akuntansi</option>
                    <option value="Desain Komunikasi Visual">Desain Komunikasi Visual</option>
                </select>
            </div>

            <!-- Tombol Submit -->
            <div class="form-group">
                <input type="submit" value="DAFTAR SEKARANG">
            </div>
        </form>
    </div>
    <ul>
    
   
    </ul>

</body>
</html>