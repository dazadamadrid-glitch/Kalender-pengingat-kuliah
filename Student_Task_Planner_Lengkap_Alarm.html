<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Student Task Planner</title>

    <style>
        /* ================================
           RESET & DASAR
        ================================= */

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            padding: 20px;
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            background: #f4f6f9;
            color: #333;
        }

        /* ================================
           CONTAINER
        ================================= */

        .container {
            width: 100%;
            max-width: 700px;
            margin: 0 auto;
            background: #ffffff;
            padding: 25px;
            border-radius: 14px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
        }

        /* ================================
           HEADER
        ================================= */

        .header {
            text-align: center;
            margin-bottom: 25px;
        }

        .header h1 {
            margin: 0 0 8px;
            color: #2c3e50;
            font-size: 28px;
        }

        .header p {
            margin: 0;
            color: #7f8c8d;
            font-size: 14px;
        }

        /* ================================
           WAKTU DEVICE
        ================================= */

        .device-time {
            margin-bottom: 25px;
            padding: 15px;
            background: linear-gradient(135deg, #3498db, #2980b9);
            color: white;
            border-radius: 10px;
            text-align: center;
        }

        .device-time .label {
            font-size: 13px;
            opacity: 0.9;
        }

        .device-time .date {
            margin-top: 5px;
            font-size: 18px;
            font-weight: bold;
        }

        .device-time .clock {
            margin-top: 3px;
            font-size: 25px;
            font-weight: bold;
        }

        /* ================================
           FORM
        ================================= */

        .form-group {
            margin-bottom: 16px;
        }

        label {
            display: block;
            margin-bottom: 7px;
            font-weight: 600;
            font-size: 14px;
            color: #34495e;
        }

        input[type="text"],
        input[type="date"] {
            width: 100%;
            padding: 11px 12px;
            border: 1px solid #d5d9de;
            border-radius: 7px;
            outline: none;
            font-size: 14px;
            transition: 0.2s;
        }

        input[type="text"]:focus,
        input[type="date"]:focus {
            border-color: #3498db;
            box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.12);
        }

        .date-wrapper {
            display: flex;
            gap: 8px;
        }

        .date-wrapper input {
            flex: 1;
        }

        .btn-today {
            border: none;
            padding: 0 14px;
            border-radius: 7px;
            background: #ecf0f1;
            color: #34495e;
            cursor: pointer;
            font-weight: 600;
        }

        .btn-today:hover {
            background: #dfe6e9;
        }

        /* ================================
           BUTTON TAMBAH
        ================================= */

        .btn-submit {
            width: 100%;
            border: none;
            padding: 13px;
            border-radius: 7px;
            background: #3498db;
            color: white;
            font-size: 15px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s;
        }

        .btn-submit:hover {
            background: #2980b9;
        }

        /* ================================
           HEADER DAFTAR
        ================================= */

        .task-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 30px;
            margin-bottom: 12px;
        }

        .task-header h2 {
            margin: 0;
            color: #2c3e50;
            font-size: 19px;
        }

        .task-count {
            padding: 5px 10px;
            border-radius: 20px;
            background: #ecf0f1;
            color: #34495e;
            font-size: 12px;
            font-weight: bold;
        }

        /* ================================
           TASK LIST
        ================================= */

        .task-list {
            margin: 0;
            padding: 0;
            list-style: none;
        }

        .empty-message {
            padding: 25px;
            text-align: center;
            color: #95a5a6;
            border: 2px dashed #dfe6e9;
            border-radius: 8px;
            font-size: 14px;
        }

        .task-item {
            display: flex;
            justify-content: space-between;
            gap: 15px;
            align-items: center;

            margin-bottom: 10px;
            padding: 15px;

            background: #f8f9fa;
            border-left: 5px solid #3498db;
            border-radius: 7px;

            transition: 0.2s;
        }

        .task-item:hover {
            transform: translateY(-1px);
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
        }

        .task-item.completed {
            border-left-color: #2ecc71;
            background: #eafaf1;
            opacity: 0.75;
        }

        .task-info {
            flex: 1;
            min-width: 0;
        }

        .task-title {
            margin: 0 0 7px;
            color: #2c3e50;
            font-size: 15px;
            word-break: break-word;
        }

        .completed .task-title {
            text-decoration: line-through;
            color: #7f8c8d;
        }

        .task-detail {
            margin: 0 0 5px;
            font-size: 13px;
            color: #555;
        }

        .deadline {
            margin: 0;
            font-size: 12px;
            color: #7f8c8d;
        }

        /* ================================
           STATUS DEADLINE
        ================================= */

        .deadline-status {
            display: inline-block;
            margin-top: 7px;
            padding: 4px 8px;
            border-radius: 5px;
            font-size: 11px;
            font-weight: bold;
        }

        .status-today {
            background: #fff3cd;
            color: #856404;
        }

        .status-tomorrow {
            background: #d1ecf1;
            color: #0c5460;
        }

        .status-late {
            background: #f8d7da;
            color: #721c24;
        }

        .status-safe {
            background: #d4edda;
            color: #155724;
        }

        /* ================================
           ACTION BUTTON
        ================================= */

        .action-buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            justify-content: flex-end;
        }

        .action-buttons button,
        .calendar-link {
            border: none;
            padding: 7px 9px;
            border-radius: 5px;
            font-size: 11px;
            cursor: pointer;
            text-decoration: none;
            color: white;
            font-weight: 600;
            white-space: nowrap;
        }

        .btn-done {
            background: #2ecc71;
        }

        .btn-undone {
            background: #f39c12;
        }

        .btn-delete {
            background: #e74c3c;
        }

        .calendar-link {
            background: #4285f4;
            display: inline-block;
        }

        .action-buttons button:hover,
        .calendar-link:hover {
            opacity: 0.85;
        }

        /* ================================
           FOOTER
        ================================= */

        .footer {
            margin-top: 25px;
            text-align: center;
            color: #95a5a6;
            font-size: 12px;
        }

        /* ================================
           RESPONSIVE
        ================================= */

        @media (max-width: 600px) {

            body {
                padding: 10px;
            }

            .container {
                padding: 18px;
            }

            .task-item {
                flex-direction: column;
                align-items: stretch;
            }

            .action-buttons {
                justify-content: flex-start;
            }

            .header h1 {
                font-size: 23px;
            }

            .device-time .clock {
                font-size: 22px;
            }
        }

        /* ================================
           ANIMASI JUDUL HEADER
        ================================= */

        .animated-title {
            display: inline-block;
            position: relative;
            cursor: default;
            animation: titleFloat 2.8s ease-in-out infinite;
        }

        .animated-title .title-icon {
            display: inline-block;
            animation: iconBounce 1.8s ease-in-out infinite;
        }

        .animated-title .title-text {
            display: inline-block;
            background: linear-gradient(
                90deg,
                #2c3e50,
                #3498db,
                #2c3e50,
                #3498db,
                #2c3e50
            );
            background-size: 300% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textShine 4s linear infinite;
        }

        .animated-title::after {
            content: "";
            position: absolute;
            left: 8%;
            right: 8%;
            bottom: -6px;
            height: 3px;
            border-radius: 10px;
            background: #3498db;
            transform: scaleX(0.25);
            opacity: 0.35;
            animation: titleLine 2.2s ease-in-out infinite;
        }

        @keyframes titleFloat {
            0%, 100% {
                transform: translateY(0) rotate(0deg);
            }
            25% {
                transform: translateY(-4px) rotate(-0.5deg);
            }
            50% {
                transform: translateY(0) rotate(0.5deg);
            }
            75% {
                transform: translateY(-3px) rotate(0deg);
            }
        }

        @keyframes iconBounce {
            0%, 100% {
                transform: translateY(0) rotate(0deg) scale(1);
            }
            25% {
                transform: translateY(-5px) rotate(-8deg) scale(1.05);
            }
            50% {
                transform: translateY(0) rotate(8deg) scale(1);
            }
            75% {
                transform: translateY(-3px) rotate(-4deg) scale(1.04);
            }
        }

        @keyframes textShine {
            0% {
                background-position: 0% center;
            }
            100% {
                background-position: 300% center;
            }
        }

        @keyframes titleLine {
            0%, 100% {
                transform: scaleX(0.25);
                opacity: 0.25;
            }
            50% {
                transform: scaleX(1);
                opacity: 0.75;
            }
        }

        @media (prefers-reduced-motion: reduce) {
            .animated-title,
            .animated-title .title-icon,
            .animated-title .title-text,
            .animated-title::after {
                animation: none;
            }
        }


        /* ================================
           PENANDA JENIS PERANGKAT
        ================================= */
        .device-indicator {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 7px;
            margin: 0 auto 9px;
            padding: 6px 13px;
            border-radius: 20px;
            background: rgba(255,255,255,0.18);
            border: 1px solid rgba(255,255,255,0.35);
            color: #fff;
            font-size: 12px;
            font-weight: 700;
            box-shadow: 0 3px 10px rgba(0,0,0,.08);
            animation: devicePulse 2s ease-in-out infinite;
        }
        .device-indicator .device-icon {
            display: inline-block;
            font-size: 15px;
            animation: deviceIconMove 1.8s ease-in-out infinite;
        }
        @keyframes devicePulse {
            0%,100% { transform: scale(1); }
            50% { transform: scale(1.04); }
        }
        @keyframes deviceIconMove {
            0%,100% { transform: translateY(0) rotate(0); }
            50% { transform: translateY(-3px) rotate(5deg); }
        }
        @media (max-width:600px) {
            .device-indicator { font-size:11px; padding:5px 11px; }
        }
        @media (prefers-reduced-motion:reduce) {
            .device-indicator, .device-indicator .device-icon { animation:none; }
        }


        /* ================================
           ALARM TUGAS
        ================================= */

        .alarm-box {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 10px;
            margin-top: 12px;
            padding: 10px 12px;
            border-radius: 8px;
            background: #f8f9fa;
            border: 1px solid #e1e5e8;
            font-size: 12px;
            color: #34495e;
        }

        .alarm-status {
            font-weight: 700;
        }

        .alarm-status.active {
            color: #27ae60;
        }

        .alarm-status.warning {
            color: #e67e22;
        }

        .btn-alarm {
            border: none;
            padding: 7px 10px;
            border-radius: 6px;
            background: #f39c12;
            color: white;
            font-size: 11px;
            font-weight: 700;
            cursor: pointer;
            white-space: nowrap;
        }

        .btn-alarm:hover {
            opacity: 0.88;
        }

        .deadline-alarm {
            animation: alarmFlash 1s ease-in-out infinite;
        }

        @keyframes alarmFlash {
            0%, 100% {
                box-shadow: 0 0 0 rgba(231, 76, 60, 0);
            }
            50% {
                box-shadow: 0 0 18px rgba(231, 76, 60, 0.45);
            }
        }

        @media (max-width: 600px) {
            .alarm-box {
                flex-direction: column;
                align-items: stretch;
            }

            .btn-alarm {
                width: 100%;
            }
        }

        @media (prefers-reduced-motion: reduce) {
            .deadline-alarm {
                animation: none;
            }
        }

    </style>
</head>

<body>

    <main class="container">

        <!-- ================================
             HEADER
        ================================= -->

        <header class="header">
            <h1 class="animated-title" aria-label="Student Task Planner">
                <span class="title-icon">📅</span>
                <span class="title-text">Student Task Planner</span>
            </h1>
            <p>
                Aplikasi pengingat jadwal kuliah dan tugas mahasiswa
            </p>
        </header>


        <!-- ================================
             WAKTU DEVICE
        ================================= -->

        <section class="device-time">

            <div class="device-indicator" id="device-indicator">
                <span class="device-icon" id="device-icon">💻</span>
                <span class="device-name" id="device-name">Laptop / Desktop</span>
            </div>

            <div class="label">
                🕒 Waktu Perangkat Anda
            </div>

            <div class="date" id="device-date">
                Memuat tanggal...
            </div>

            <div class="clock" id="device-clock">
                00:00:00
            </div>

        </section>


        <!-- ================================
             FORM INPUT
        ================================= -->

        <section>

            <div class="form-group">
                <label for="matkul-input">
                    Mata Kuliah
                </label>

                <input
                    type="text"
                    id="matkul-input"
                    placeholder="Contoh: Pemrograman Web"
                    autocomplete="off"
                >
            </div>


            <div class="form-group">
                <label for="tugas-input">
                    Detail Tugas / Kegiatan
                </label>

                <input
                    type="text"
                    id="tugas-input"
                    placeholder="Contoh: Membuat CRUD Web"
                    autocomplete="off"
                >
            </div>


            <div class="form-group">

                <label for="deadline-input">
                    Tenggat Waktu
                </label>

                <div class="date-wrapper">

                    <input
                        type="date"
                        id="deadline-input"
                    >

                    <button
                        type="button"
                        class="btn-today"
                        onclick="gunakanHariIni()"
                    >
                        Hari Ini
                    </button>

                </div>

            </div>


            <button
                type="button"
                class="btn-submit"
                onclick="tambahTugas()"
            >
                ➕ Tambahkan ke Jadwal
            </button>

            <div class="alarm-box">
                <span>
                    🔔 <span id="alarm-status" class="alarm-status warning">
                        Alarm deadline belum diaktifkan
                    </span>
                </span>
                <button
                    type="button"
                    class="btn-alarm"
                    onclick="aktifkanAlarm()"
                >
                    🔔 Aktifkan Alarm
                </button>
            </div>

        </section>


        <!-- ================================
             DAFTAR TUGAS
        ================================= -->

        <section>

            <div class="task-header">

                <h2>📚 Daftar Tugas</h2>

                <span
                    class="task-count"
                    id="task-count"
                >
                    0 tugas
                </span>

            </div>


            <ul
                class="task-list"
                id="task-container"
            >
            </ul>

        </section>


        <footer class="footer">
            Data tugas tersimpan otomatis di browser perangkat ini.
        </footer>

    </main>


    <script>

        /* ==========================================
           ELEMENT HTML
        ========================================== */

        const taskContainer =
            document.getElementById("task-container");

        const taskCount =
            document.getElementById("task-count");

        const matkulInput =
            document.getElementById("matkul-input");

        const tugasInput =
            document.getElementById("tugas-input");

        const deadlineInput =
            document.getElementById("deadline-input");

        const deviceDate =
            document.getElementById("device-date");

        const deviceClock =
            document.getElementById("device-clock");

        const deviceIcon =
            document.getElementById("device-icon");

        const deviceName =
            document.getElementById("device-name");

        const alarmStatus =
            document.getElementById("alarm-status");

        let alarmAktif = false;
        let alarmAudioContext = null;
        const alarmSudahBerbunyi = {};


        /* ==========================================
           DATA TUGAS
        ========================================== */

        let daftarTugas =
            JSON.parse(
                localStorage.getItem("studentTasks")
            ) || [];


        /* ==========================================
           FORMAT TANGGAL
        ========================================== */

        function formatTanggal(tanggalString) {

            const tanggal =
                new Date(
                    tanggalString + "T00:00:00"
                );

            return tanggal.toLocaleDateString(
                "id-ID",
                {
                    weekday: "long",
                    year: "numeric",
                    month: "long",
                    day: "numeric"
                }
            );
        }


        /* ==========================================
           TANGGAL HARI INI
        ========================================== */

        function tanggalHariIni() {

            const sekarang = new Date();

            const tahun =
                sekarang.getFullYear();

            const bulan =
                String(
                    sekarang.getMonth() + 1
                ).padStart(2, "0");

            const hari =
                String(
                    sekarang.getDate()
                ).padStart(2, "0");

            return `${tahun}-${bulan}-${hari}`;
        }


        /* ==========================================
           SET TANGGAL HARI INI
        ========================================== */

        function gunakanHariIni() {

            deadlineInput.value =
                tanggalHariIni();

        }


        /* ==========================================
           PENANDA JENIS DEVICE
        ========================================== */

        function updatePenandaDevice() {
            const lebarLayar = window.innerWidth;

            if (lebarLayar <= 600) {
                deviceIcon.textContent = "📱";
                deviceName.textContent = "HP / Smartphone";
            } else if (lebarLayar <= 1024) {
                deviceIcon.textContent = "📱";
                deviceName.textContent = "Tablet";
            } else {
                deviceIcon.textContent = "💻";
                deviceName.textContent = "Laptop / Desktop";
            }
        }


        /* ==========================================
           UPDATE JAM DEVICE
        ========================================== */

        function updateWaktuDevice() {

            const sekarang = new Date();

            deviceDate.textContent =
                sekarang.toLocaleDateString(
                    "id-ID",
                    {
                        weekday: "long",
                        day: "numeric",
                        month: "long",
                        year: "numeric"
                    }
                );

            deviceClock.textContent =
                sekarang.toLocaleTimeString(
                    "id-ID",
                    {
                        hour: "2-digit",
                        minute: "2-digit",
                        second: "2-digit"
                    }
                );
        }



        /* ==========================================
           ALARM DEADLINE
        ========================================== */

        function aktifkanAlarm() {
            alarmAktif = true;

            // Membuka izin audio melalui klik pengguna.
            try {
                alarmAudioContext =
                    new (window.AudioContext || window.webkitAudioContext)();

                if (alarmAudioContext.state === "suspended") {
                    alarmAudioContext.resume();
                }
            } catch (error) {
                console.log("Audio tidak tersedia pada browser ini.");
            }

            if ("Notification" in window &&
                Notification.permission === "default") {
                Notification.requestPermission();
            }

            alarmStatus.textContent =
                "Alarm aktif — akan berbunyi saat deadline tiba";
            alarmStatus.className =
                "alarm-status active";

            cekAlarmDeadline();
        }

        function bunyikanAlarm() {
            if (!alarmAudioContext) return;

            const sekarang = alarmAudioContext.currentTime;

            // Tiga bunyi pendek agar lebih mudah terdengar.
            [0, 0.35, 0.7].forEach((delay, index) => {
                const oscillator =
                    alarmAudioContext.createOscillator();

                const gain =
                    alarmAudioContext.createGain();

                oscillator.type = "sine";
                oscillator.frequency.value =
                    index === 1 ? 880 : 660;

                gain.gain.setValueAtTime(
                    0.0001,
                    sekarang + delay
                );

                gain.gain.exponentialRampToValueAtTime(
                    0.35,
                    sekarang + delay + 0.03
                );

                gain.gain.exponentialRampToValueAtTime(
                    0.0001,
                    sekarang + delay + 0.25
                );

                oscillator.connect(gain);
                gain.connect(alarmAudioContext.destination);

                oscillator.start(sekarang + delay);
                oscillator.stop(sekarang + delay + 0.28);
            });
        }

        function kirimNotifikasiAlarm(tugas) {
            if ("Notification" in window &&
                Notification.permission === "granted") {

                new Notification("🔔 Deadline Tugas!", {
                    body:
                        `${tugas.matkul}: ${tugas.tugas} — deadline hari ini.`,
                    icon: "data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='128' height='128'%3E%3Ctext y='90' font-size='90'%3E🔔%3C/text%3E%3C/svg%3E"
                });
            }
        }

        function cekAlarmDeadline() {
            if (!alarmAktif) return;

            const hariIni = tanggalHariIni();

            daftarTugas.forEach(tugas => {

                if (
                    tugas.deadline === hariIni &&
                    !tugas.selesai
                ) {

                    const kunciAlarm =
                        `${tugas.id}-${hariIni}`;

                    if (!alarmSudahBerbunyi[kunciAlarm]) {

                        alarmSudahBerbunyi[kunciAlarm] = true;

                        bunyikanAlarm();
                        kirimNotifikasiAlarm(tugas);

                        alarmStatus.textContent =
                            `🔔 Deadline hari ini: ${tugas.matkul}`;

                        alarmStatus.className =
                            "alarm-status warning";

                        // Tampilkan efek pada tugas yang jatuh tempo.
                        const semuaTugas =
                            document.querySelectorAll(".task-item");

                        semuaTugas.forEach(item => {
                            if (item.textContent.includes(tugas.matkul)) {
                                item.classList.add("deadline-alarm");
                            }
                        });

                        setTimeout(() => {
                            tampilkanTugas();
                        }, 6000);
                    }
                }
            });
        }


        /* ==========================================
           STATUS DEADLINE
        ========================================== */

        function cekStatusDeadline(
            deadline,
            selesai
        ) {

            if (selesai) {

                return {
                    text: "✔ Selesai",
                    className: "status-safe"
                };

            }


            const sekarang =
                new Date();

            sekarang.setHours(
                0, 0, 0, 0
            );


            const tanggalDeadline =
                new Date(
                    deadline + "T00:00:00"
                );


            const selisih =
                Math.ceil(
                    (
                        tanggalDeadline -
                        sekarang
                    ) /
                    (1000 * 60 * 60 * 24)
                );


            if (selisih < 0) {

                return {
                    text: "⚠ Terlambat",
                    className: "status-late"
                };

            }


            if (selisih === 0) {

                return {
                    text: "🔥 Hari ini",
                    className: "status-today"
                };

            }


            if (selisih === 1) {

                return {
                    text: "📌 Besok",
                    className: "status-tomorrow"
                };

            }


            return {
                text: `⏳ ${selisih} hari lagi`,
                className: "status-safe"
            };
        }


        /* ==========================================
           SIMPAN DATA
        ========================================== */

        function simpanData() {

            localStorage.setItem(
                "studentTasks",
                JSON.stringify(daftarTugas)
            );

        }


        /* ==========================================
           ESCAPE HTML
           Mencegah input pengguna menjadi HTML
        ========================================== */

        function escapeHTML(teks) {

            const div =
                document.createElement("div");

            div.textContent = teks;

            return div.innerHTML;
        }


        /* ==========================================
           TAMBAH TUGAS
        ========================================== */

        function tambahTugas() {

            const matkul =
                matkulInput.value.trim();

            const tugas =
                tugasInput.value.trim();

            const deadline =
                deadlineInput.value;


            /* Validasi */

            if (
                matkul === "" ||
                tugas === "" ||
                deadline === ""
            ) {

                alert(
                    "Mohon isi semua kolom terlebih dahulu."
                );

                return;
            }


            /* Buat object tugas */

            const tugasBaru = {

                id:
                    Date.now(),

                matkul:
                    matkul,

                tugas:
                    tugas,

                deadline:
                    deadline,

                selesai:
                    false

            };


            /* Masukkan ke array */

            daftarTugas.push(
                tugasBaru
            );


            /* Simpan */

            simpanData();


            /* Render */

            tampilkanTugas();


            /* Reset */

            matkulInput.value = "";
            tugasInput.value = "";
            deadlineInput.value = "";

            matkulInput.focus();
        }


        /* ==========================================
           TAMPILKAN SEMUA TUGAS
        ========================================== */

        function tampilkanTugas() {

            taskContainer.innerHTML = "";


            /* Jika belum ada tugas */

            if (
                daftarTugas.length === 0
            ) {

                taskContainer.innerHTML = `
                    <li class="empty-message">
                        📝 Belum ada tugas.
                        Silakan tambahkan tugas baru.
                    </li>
                `;

                updateJumlahTugas();

                return;
            }


            /* Urutkan berdasarkan deadline */

            const tugasTerurut =
                [...daftarTugas].sort(
                    (a, b) =>
                        a.deadline.localeCompare(
                            b.deadline
                        )
                );


            tugasTerurut.forEach(
                tugas => {

                    const li =
                        document.createElement("li");

                    li.className =
                        "task-item";


                    if (tugas.selesai) {

                        li.classList.add(
                            "completed"
                        );

                    }


                    const status =
                        cekStatusDeadline(
                            tugas.deadline,
                            tugas.selesai
                        );


                    li.innerHTML = `

                        <div class="task-info">

                            <h4 class="task-title">
                                📘 ${escapeHTML(tugas.matkul)}
                            </h4>

                            <p class="task-detail">
                                ${escapeHTML(tugas.tugas)}
                            </p>

                            <p class="deadline">
                                📅 ${formatTanggal(tugas.deadline)}
                            </p>

                            <span
                                class="deadline-status ${status.className}"
                            >
                                ${status.text}
                            </span>

                        </div>


                        <div class="action-buttons">

                            <button
                                class="${
                                    tugas.selesai
                                    ? "btn-undone"
                                    : "btn-done"
                                }"
                                onclick="ubahStatus(${tugas.id})"
                            >
                                ${
                                    tugas.selesai
                                    ? "↩ Batal"
                                    : "✔ Selesai"
                                }
                            </button>


                            <a
                                class="calendar-link"
                                href="${buatLinkGoogleCalendar(tugas)}"
                                target="_blank"
                                rel="noopener noreferrer"
                            >
                                📅 Google
                            </a>


                            <button
                                class="btn-delete"
                                onclick="hapusTugas(${tugas.id})"
                            >
                                ❌ Hapus
                            </button>

                        </div>

                    `;


                    taskContainer.appendChild(
                        li
                    );

                }
            );


            updateJumlahTugas();
        }


        /* ==========================================
           UBAH STATUS SELESAI
        ========================================== */

        function ubahStatus(id) {

            const tugas =
                daftarTugas.find(
                    item =>
                        item.id === id
                );


            if (!tugas) {
                return;
            }


            tugas.selesai =
                !tugas.selesai;


            simpanData();

            tampilkanTugas();
        }


        /* ==========================================
           HAPUS TUGAS
        ========================================== */

        function hapusTugas(id) {

            const konfirmasi =
                confirm(
                    "Apakah Anda yakin ingin menghapus tugas ini?"
                );


            if (!konfirmasi) {
                return;
            }


            daftarTugas =
                daftarTugas.filter(
                    tugas =>
                        tugas.id !== id
                );


            simpanData();

            tampilkanTugas();
        }


        /* ==========================================
           JUMLAH TUGAS
        ========================================== */

        function updateJumlahTugas() {

            const jumlah =
                daftarTugas.length;


            taskCount.textContent =
                `${jumlah} tugas`;
        }


        /* ==========================================
           GOOGLE CALENDAR
        ========================================== */

        function buatLinkGoogleCalendar(tugas) {

            /*
                Google Calendar membutuhkan:

                action=TEMPLATE
                text=Judul event
                details=Deskripsi
                dates=Tanggal mulai/Tanggal selesai
            */


            const judul =
                encodeURIComponent(
                    `[${tugas.matkul}] ${tugas.tugas}`
                );


            const detail =
                encodeURIComponent(
                    `Tugas mata kuliah ${tugas.matkul}.\n\n` +
                    `Detail: ${tugas.tugas}\n\n` +
                    `Dibuat melalui Student Task Planner.`
                );


            /*
                Untuk deadline seharian.

                Misalnya:
                20261008

                sampai:
                20261009

                Google Calendar menggunakan
                tanggal akhir exclusive.
            */

            const tanggalMulai =
                tugas.deadline.replace(
                    /-/g,
                    ""
                );


            const tanggalObj =
                new Date(
                    tugas.deadline + "T00:00:00"
                );


            tanggalObj.setDate(
                tanggalObj.getDate() + 1
            );


            const tahun =
                tanggalObj.getFullYear();

            const bulan =
                String(
                    tanggalObj.getMonth() + 1
                ).padStart(2, "0");

            const hari =
                String(
                    tanggalObj.getDate()
                ).padStart(2, "0");


            const tanggalSelesai =
                `${tahun}${bulan}${hari}`;


            return (
                "https://calendar.google.com/calendar/render" +
                "?action=TEMPLATE" +
                `&text=${judul}` +
                `&details=${detail}` +
                `&dates=${tanggalMulai}/${tanggalSelesai}`
            );
        }


        /* ==========================================
           ENTER UNTUK MENAMBAH TUGAS
        ========================================== */

        document.addEventListener(
            "keydown",
            function(event) {

                if (
                    event.key === "Enter" &&
                    (
                        document.activeElement ===
                        matkulInput ||

                        document.activeElement ===
                        tugasInput
                    )
                ) {

                    tambahTugas();

                }

            }
        );


        /* ==========================================
           INISIALISASI
        ========================================== */

        function init() {

            /*
                Default deadline =
                tanggal device hari ini
            */

            deadlineInput.value =
                tanggalHariIni();


            /*
                Update waktu pertama kali
            */

            updateWaktuDevice();


                        updatePenandaDevice();

            window.addEventListener(
                "resize",
                updatePenandaDevice
            );

/*
                Update jam setiap detik
            */

            setInterval(
                updateWaktuDevice,
                1000
            );

            // Periksa deadline secara berkala.
            setInterval(
                cekAlarmDeadline,
                1000
            );


            /*
                Tampilkan data tersimpan
            */

            tampilkanTugas();

        }


        /* Jalankan aplikasi */

        init();

    </script>

</body>
</html>
