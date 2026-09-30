# company-profile-themecd C:\xampp\htdocs\companyweb\wp-content\themes\company-profile# Inisialisasi Git di dalam folder tema
git init

# Tambahkan seluruh file tema ke staging
git add .

# Buat commit pertama
git commit -m "First commit: Tema Custom Company Profile WordPress"

# Ubah nama branch utama menjadi main
git branch -M main

# Sambungkan ke repository GitHub Anda (Ganti URL berikut dengan URL repo Anda)
git remote add origin https://github.com/USERNAME_ANDA/company-profile-theme.git

# Unggah kode ke GitHub
git push -u origin main
