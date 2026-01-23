`Cyber Security adalah praktik perlindungan terhadap penggunaan data elektronik secara kriminal atau pengaksesan ilegal/tidak sah, maupun tindakan lainnya yang digunakan untuk mencapainya.` - CompTIA

`Cyber Security adalah praktik penerapan sumber daya manusia, kebijakan, proses, dan teknologi untuk melindungi organisasi, sistem penting, dan informasi sensitif dari serangan digital.` - Gartner

`Cyber Security adalah pencegahan kerusakan, perlindungan, dan pemulihan komunikasi komputer, sistem elektronik, layanan komunikasi elektronik, komunikasi kabel, dan komunikasi elektronik, termasuk informasi yang terkandung di dalamnya, untuk memastikan ketersediaan, integritas, autentikasi, kerahasiaan, dan tanpa penyangkalan.` - National Institute of Standard & Technology (NIST)

## Team on Cyber Security
1. Offensive Team [Red Team] = Menemukan celah dan kelemahan keamanan
    - Offensive Team identik dengan Pentest [Penetration Testing]
    - Pentesting adalah pekerjaan yang dilakukan oleh pentester
    - Pentester adalah orang yang melakukan pentesting
2. Defensive Team [Blue Team] = Mengatasi dan memperkuat kerentanan keamanan
    - Defensive Team identik dengan DFIR [Digital Forensic an Insident Response]
    _ DFIR adalah kegiatan yang dilakukan oleh DFIR Specialist/DFIR Analyst

3. Purple Team = Mengerjakan tugas Offensive dan Defensive
    - Dipergunakan dalam lingkungan yang kompleks dan berubah dengan cepat 

## Phase Pentesting
1. Planning and Scoping [Perencanaan dan Ruang Lingkup]
    - Planning: Menetapkan tujuan utama dari pengujian, menentukan metode yang akan digunakan (black-box, gray-box, atau white-box), dan merencanakan tahapan pengujian secara keseluruhan. Tahap ini juga mencakup persiapan teknis dan penyusunan alat yang akan digunakan.
    - Scoping: Menentukan lingkup (scope) dari pengujian, yaitu aset atau area yang akan diuji, batasan, dan aturan khusus. Ini termasuk berkoordinasi dengan pemilik sistem untuk memahami batasan yang diperbolehkan dan menetapkan ekspektasi yang jelas.
2. Reconnaissance/Information Gathering [Pengumpulan Informasi]
    - Passive Reconnaissance: Pengumpulan informasi tanpa interaksi langsung dengan target, misalnya mencari data melalui internet, sumber publik, dan basis data.
    - Active Reconnaissance: Melibatkan interaksi langsung dengan sistem target, seperti pinging, port scanning, dan lainnya yang bertujuan untuk mengidentifikasi layanan dan sistem operasi yang digunakan oleh target.
3. Scanning [Mengumpulkan Informasi Dasar]
    - Port Scanning: Untuk mengidentifikasi port terbuka dan layanan yang berjalan di sistem target.
    - Vulnerability Scanning: Untuk menemukan kerentanan pada layanan atau aplikasi yang teridentifikasi, misalnya dengan menggunakan alat seperti Nessus atau OpenVAS.
    - Enumeration: Pengumpulan informasi yang lebih mendalam, seperti akun pengguna, grup, dan struktur direktori.
4. Gain Access/Exploitation [Mengeksploitasi]
    - Eksploitasi kerentanan yang ditemukan pada tahap sebelumnya untuk mendapatkan akses ke sistem atau jaringan target. Pendekatan eksploitasi dapat bervariasi, mulai dari serangan brute-force, SQL injection, XSS (cross-site scripting), hingga buffer overflow. Fase ini memungkinkan pentester memahami dampak potensial dari kerentanan yang ada.
5. Maintain Access [Mempertahankan Akses]
    - Backdoors: Menempatkan pintu belakang yang memungkinkan mereka kembali ke sistem di masa depan.
    - Privileged Account: Membuat atau mendapatkan akun dengan hak akses tinggi yang memungkinkan eksploitasi lebih lanjut.
6. Cover Tracks [Penghapusan Jejak]
    - Menyembunyikan aktivitas mereka untuk menghindari deteksi, memastikan bahwa jejak akses dan eksploitasi tidak terdeteksi oleh sistem atau tim keamanan.
    - Menghapus atau memodifikasi log yang menunjukkan akses ilegal atau eksploitasi.
    - Menghapus file atau backdoor yang mungkin mengindikasikan adanya pelanggaran.
7. Analysis
    - Analisis menyeluruh terhadap hasil pengujian. Mereka mengevaluasi temuan berdasarkan tingkat keparahan, serta potensi dampaknya terhadap organisasi. Analisis ini membantu merumuskan rekomendasi perbaikan yang jelas dan efektif.
8. Reporting
    - Detail Kerentanan: Temuan spesifik yang menjelaskan kerentanan, cara eksploitasi, dan dampak potensial.
    - Tingkat Keparahan: Penilaian tingkat risiko atau dampak dari kerentanan yang ditemukan.
    - Rekomendasi Perbaikan: Saran untuk memperbaiki atau memitigasi setiap kerentanan yang ditemukan.
    - Langkah Teknis: Langkah-langkah teknis yang diambil dalam pengujian untuk referensi bagi tim keamanan.

## Capture The Flag
> Merupakan salah satu kompetisi/latihan Ethical Hacking yang dimana sebuah tim/personal harus mengambil sebuah string yang disembunyikan [flag] menggunakan berbagai teknik.
- Metode kompetisi
    - Jeopardy = Kompetisi/latihan berupa soal-soal dengan berbagai kategori yang dimana setiap soal memili poin dan tingkat kesulitannya serta dapat berupa blackbox maupun whitebox.
    - Attack and Defense [A&D] = Kompetisi/latihan yang memiliki sebuah flag server/infrastuktur/sistem/jaringan masing-masing yang tergolong rentan dan tujuan dari metode ini untuk melindungi flag server/infrastuktur/sistem/jaringan tersebut tidak diretas/tidak terganggu disertai mengeksploitasi flag server/infrastuktur/sistem/jaringan lawan.
    - Speed CTF = Kompetisi/latihan yang dimana tiap personal akan beradu kecepatan dalam menyelesaikan sebuah soal.
- Kategori CTF 
    - Binary Exploitation/PWN
    - Blockchain
    - Boot2Root/Privilege Escalation
    - Cryptography
    - Forensics
    - Game Exploitation
    - Miscellaneous [MISC]
    - Mobile Exploitation
    - Open-Source Intelligence [OSINT]
    - Programming
    - Reverse Engineering
    - Web Exploitation
- Sistem penilaian Jeopardy
    - Dynamic = Sistem penilaian semakin menurun berdasarkan total personal yang meyelesaikannya.
    - Static = Sistem penilaian tetap sama walaupun total personal yang menyelesaikan banyak.
- Sumber belajar Cyber Security
    - https://cryptohack.org/
    - https://picoctf.org/
    - https://ctflearn.com/
    - https://pwn.college/
    - https://asmtutor.com/
    - https://tryhackme.com/
    - https://ctf.rajawalisecteam.eu.org/
    - https://portswigger.net/
    - https://playground.tcp1p.team/
    - https://overthewire.org/wargames/
    - https://pwnable.tw/
    - https://www.hackthebox.com/
    - https://cyberdefenders.org/
    - https://ctf.hackthebox.com/
    - https://www.vulnhub.com/
    - https://capturetheflag.withgoogle.com/
    - https://www.hackthissite.org/
    - https://www.hacktrace-ranges.id/ranges
    - https://ethernaut.openzeppelin.com/
    - https://cryptozombies.io/
    - https://ctf.hackucf.org/
    - https://www.damnvulnerabledefi.xyz/
    - https://cryptopals.com/   
    - https://mrstealyocrypto.xyz/
    - https://prompt.ml/

