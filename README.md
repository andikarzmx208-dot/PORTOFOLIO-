
</head><meta name="google-site-verification" content="m2yxpAGDiBCKi4Xjd577S_BMBUM3eJ-nlApK9VdHQd0" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Data Diri | Andika Ramadani</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f7fb;
            color: #222;
            line-height: 1.6;
        }

        /* NAVBAR */
        nav {
            width: 100%;
            background: #111827;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 3px 15px rgba(0,0,0,0.2);
        }

        .navbar {
            max-width: 1100px;
            margin: auto;
            padding: 15px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: white;
            font-size: 22px;
            font-weight: bold;
        }

        .logo span {
            color: #38bdf8;
        }

        .menu {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        .menu a {
            color: white;
            text-decoration: none;
            font-size: 15px;
            transition: 0.3s;
        }

        .menu a:hover {
            color: #38bdf8;
        }

        /* HERO */
        .hero {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 100px 20px 50px;
            background: linear-gradient(135deg, #0f172a, #1e3a8a);
            color: white;
        }

        .hero-content {
            max-width: 800px;
        }

        .foto-profil {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            margin-bottom: 20px;
            background: #ddd;
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }

        .hero h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        .hero h1 span {
            color: #38bdf8;
        }

        .hero p {
            font-size: 20px;
            color: #dbeafe;
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            background: #38bdf8;
            color: #0f172a;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
            transform: translateY(-3px);
        }

        /* SECTION */
        section {
            max-width: 1100px;
            margin: auto;
            padding: 80px 25px;
        }

        .judul {
            text-align: center;
            margin-bottom: 40px;
        }

        .judul h2 {
            font-size: 32px;
            color: #111827;
            margin-bottom: 10px;
        }

        .judul p {
            color: #64748b;
        }

        /* TENTANG */
        .tentang-box {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .tentang-box p {
            margin-bottom: 15px;
            color: #475569;
        }

        /* BIODATA */
        .biodata {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .data-box {
            background: white;
            padding: 22px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.07);
            border-left: 5px solid #38bdf8;
        }

        .data-box h3 {
            color: #64748b;
            font-size: 15px;
            margin-bottom: 5px;
        }

        .data-box p {
            font-size: 17px;
            font-weight: bold;
            color: #111827;
        }

        /* KEAHLIAN */
        .skill-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .skill {
            background: white;
            padding: 25px;
            text-align: center;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        .skill:hover {
            transform: translateY(-7px);
        }

        .skill .icon {
            font-size: 40px;
            margin-bottom: 10px;
        }

        .skill h3 {
            margin-bottom: 8px;
        }

        .skill p {
            color: #64748b;
        }

        /* PENDIDIKAN */
        .pendidikan {
            background: white;
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }

        .pendidikan h3 {
            color: #1e3a8a;
            margin-bottom: 5px;
        }

        .pendidikan p {
            color: #64748b;
        }

        /* HOBI */
        .hobi-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .hobi {
            background: #111827;
            color: white;
            padding: 15px 25px;
            border-radius: 30px;
            font-weight: bold;
        }

        /* KONTAK */
        .kontak {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .kontak-item {
            padding: 15px 0;
            border-bottom: 1px solid #e5e7eb;
        }

        .kontak-item:last-child {
            border-bottom: none;
        }

        .kontak-item strong {
            display: inline-block;
            width: 100px;
        }

        .kontak a {
            color: #2563eb;
            text-decoration: none;
        }

        .kontak a:hover {
            text-decoration: underline;
        }

        /* FOOTER */
        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 25px;
        }

        footer span {
            color: #38bdf8;
            font-weight: bold;
        }

        /* RESPONSIVE HP */
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 12px;
            }

            .menu {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .menu a {
                font-size: 13px;
            }

            .hero h1 {
                font-size: 32px;
            }

            .hero p {
                font-size: 17px;
            }

            .foto-profil {
                width: 140px;
                height: 140px;
            }

            .biodata {
                grid-template-columns: 1fr;
            }

            .skill-container {
                grid-template-columns: 1fr;
            }

            section {
                padding: 60px 18px;
            }

            .judul h2 {
                font-size: 27px;
            }
        }
    </style>
</head>

<body>

    <!-- NAVBAR -->
    <nav>
        <div class="navbar">

            <div class="logo">
                ANDIKA<span>.</span>
            </div>

            <ul class="menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#tentang">Tentang</a></li>
                <li><a href="#biodata">Biodata</a></li>
                <li><a href="#keahlian">Keahlian</a></li>
                <li><a href="#pendidikan">Pendidikan</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>

        </div>
    </nav>


    <!-- HOME -->
    <section class="hero" id="home">

        <div class="hero-content">

            <!-- GANTI FOTO DI SINI -->
            <img
                src="IMG_20260929_155254.jpg"
                alt="Foto Andika Ramadani"
                class="foto-profil"
            >

            <h1>Halo, Saya <span>Andika Ramadani</span></h1>

            <p>
                Siswa Kelas XI RPL | Web Developer Pemula
            </p>

            <a href="#biodata" class="btn">
                Lihat Data Diri
            </a>

        </div>

    </section>


    <!-- TENTANG SAYA -->
    <section id="tentang">

        <div class="judul">
            <h2>Tentang Saya</h2>
            <p>Kenali saya lebih dekat</p>
        </div>

        <div class="tentang-box">

            <p>
                Halo, nama saya <strong>Andika Ramadani</strong>.
                Saya adalah seorang siswa jurusan Rekayasa Perangkat Lunak
                (RPL).
            </p>

            <p>
                Saya sedang belajar mengenai dunia pemrograman,
                pembuatan website, database, dan berbagai teknologi
                komputer.
            </p>

            <p>
                Saya ingin terus mengembangkan kemampuan saya dalam
                bidang teknologi dan pemrograman serta membuat berbagai
                proyek yang bermanfaat.
            </p>

        </div>

    </section>


    <!-- BIODATA -->
    <section id="biodata">

        <div class="judul">
            <h2>Biodata Diri</h2>
            <p>Informasi tentang diri saya</p>
        </div>

        <div class="biodata">

            <div class="data-box">
                <h3>Nama Lengkap</h3>
                <p>Andika Ramadani</p>
            </div>

            <div class="data-box">
                <h3>Kelas</h3>
                <p>XI RPL</p>
            </div>

            <div class="data-box">
                <h3>Jurusan</h3>
                <p>Rekayasa Perangkat Lunak</p>
            </div>

            <div class="data-box">
                <h3>Sekolah</h3>
                <p>SMK</p>
            </div>

            <div class="data-box">
                <h3>Tempat, Tanggal Lahir</h3>
                <p>19 September 2008</p>
            </div>

            <div class="data-box">
                <h3>Alamat</h3>
                <p>Merak Belantung</p>
            </div>

            <div class="data-box">
                <h3>Jenis Kelamin</h3>
                <p>Laki Laki</p>
            </div>

            <div class="data-box">
                <h3>Agama</h3>
                <p>Islam</p>
            </div>

        </div>

    </section>


    <!-- KEAHLIAN -->
    <section id="keahlian">

        <div class="judul">
            <h2>Keahlian</h2>
            <p>Kemampuan yang sedang saya pelajari</p>
        </div>

        <div class="skill-container">

            <div class="skill">
                <div class="icon">💻</div>
                <h3>HTML</h3>
                <p>Membuat struktur halaman website.</p>
            </div>

            <div class="skill">
                <div class="icon">🎨</div>
                <h3>CSS</h3>
                <p>Membuat tampilan website menjadi lebih menarik.</p>
            </div>

            <div class="skill">
                <div class="icon">⚙️</div>
                <h3>JavaScript</h3>
                <p>Membuat website menjadi lebih interaktif.</p>
            </div>

            <div class="skill">
                <div class="icon">🐘</div>
                <h3>PHP</h3>
                <p>Mempelajari pemrograman web dari sisi server.</p>
            </div>

            <div class="skill">
                <div class="icon">🗄️</div>
                <h3>Database</h3>
                <p>Mempelajari penyimpanan dan pengolahan data.</p>
            </div>

            <div class="skill">
                <div class="icon">🖥️</div>
                <h3>VS Code</h3>
                <p>Menggunakan editor untuk membuat program.</p>
            </div>

        </div>

    </section>


    <!-- PENDIDIKAN -->
    <section id="pendidikan">

        <div class="judul">
            <h2>Pendidikan</h2>
            <p>Riwayat pendidikan</p>
        </div>

        <div class="pendidikan">

            <h3>SMKN 1 KALIANDA</h3>

            <p>
                Jurusan: Rekayasa Perangkat Lunak (RPL)
            </p>

            <p>
                Kelas: XI RPL
            </p>

        </div>

        <div class="pendidikan">

            <h3>SMP</h3>

            <p>
                SMPN 2 KALIANDA.
            </p>

        </div>

        <div class="pendidikan">

            <h3>SD</h3>

            <p>
                SDN 1 MERAK BELANTUNG.
            </p>

        </div>

    </section>


    <!-- HOBI -->
    <section>

        <div class="judul">
            <h2>Hobi</h2>
            <p>Beberapa kegiatan yang saya sukai</p>
        </div>

        <div class="hobi-container">

            <div class="hobi">🎮 Gaming</div>

            <div class="hobi">💻 Coding</div>

            <div class="hobi">🎧 Musik</div>

            <div class="hobi">🎬 Menonton</div>

            <div class="hobi">📱 Teknologi</div>

        </div>

    </section>


    <!-- KONTAK -->
    <section id="kontak">

        <div class="judul">
            <h2>Kontak</h2>
            <p>Hubungi saya melalui</p>
        </div>

        <div class="kontak">

            <div class="kontak-item">
                <strong>📧 Email</strong>
                <a href="mailto: andikaramadani889@gmail.com">
                    andikaramadani889@gmail.com
                </a>
            </div>

            <div class="kontak-item">
                <strong>📱 WhatsApp</strong>
                <a href="https://wa.me/6280000000000">
                    08xxxxxxxxxx
                </a>
            </div>

            <div class="kontak-item">
                <strong>📸 Instagram</strong>
                <a href="https://instagram.com/" target="_blank">
                    @ramaa_208
                </a>
            </div>

            <div class="kontak-item">
                <strong>📍 Alamat</strong>
                <span>Merak Belantung</span>
            </div>

        </div>

    </section>


    <!-- FOOTER -->
    <footer>

        <p>
            © 2026 <span>Andika Ramadani</span>.
            Semua Hak Dilindungi.
        </p>

        <p>
            XI RPL | Personal Website
        </p>

    </footer>

</body>
</html>
