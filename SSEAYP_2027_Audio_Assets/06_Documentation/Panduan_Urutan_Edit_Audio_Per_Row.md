# Panduan Urutan Pemasangan Audio Sesuai Footage Row (CapCut / Premiere / DaVinci)

Dokumen ini disusun mengikuti **24 baris timeline** (`00:00–01:48`) pada [IMG_3894.MOV](file:///d:/Haerul/AI-Agents/IMG_3894.MOV). Seluruh aset Mandar (`02_Mandar_Traditional_Music/`) kini sudah diekstrak lengkap dan siap pakai.

---

## 1. Susunan Track Audio di Timeline Editor (4 Track)

1. **Track A1 – Original Audio & Vokal/Rebana Utama** (`04_Original_Footage_Audio/` + Rebana utama `00:47–00:53`)
2. **Track A2 – Musik Utama / BGM & Pengiring Mandar** (`01_Cinematic_Music/` + `02_Mandar_Traditional_Music/`)
3. **Track A3 – Ambience (Ombak & Angin)** (`03_Sound_Effects/Ocean_and_Wind/`)
4. **Track A4 – Aksen Transisi & Impact (SFX)** (`03_Sound_Effects/Cinematic_Impacts/`, `Risers_and_Whooshes/`, `Transitions/`)

> **Catatan Gain Staging Penting:**
> File Mixkit & WAV Mandar sudah di-mastering mendekati `0 dBFS`. Di editor, **turunkan volume BGM sekitar `-14 dB` s/d `-18 dB`** saat tanpa dialog, dan **`-22 dB` s/d `-26 dB`** saat ada dialog/vokal.

---

## 2. Urutan Pemasangan Audio Per Footage Row (`00:00 – 01:48`)

| Row | Timecode | Visual Footage | Track A1 (Original / Fokus Budaya) | Track A2 (Musik Utama / Pengiring) | Track A3 (Ambience) & Track A4 (SFX) | Pengaturan Volume & Transisi |
| :-: | :--- | :--- | :--- | :--- | :--- | :--- |
| **1** | `00:00–00:04` | Garuda 50 intro | `ORIGINAL_Garuda50_Intro.wav` | Masuk **`MUSIC_Opening_Atmospheric_Discover_Mixkit.mp3`** (ambil mulai **`00:02`** lagu) di **`00:02.5`** | **A4:** `SFX_Opening_Cinematic_Impact_Mixkit.mp3` tepat di **`00:00.0`** | A1: `0 dB`<br>A4 Impact: `-22 dB`<br>A2 `Discover`: **Fade In `1.5s`** ke `-16 dB` |
| **2** | `00:04–00:07` | Delegate making welcoming gesture | *(Bisu)* | Lanjutkan **`Discover`** | *(Kosong)* | A2 `Discover`: `-16 dB` |
| **3** | `00:07–00:09` | Drone Patung Selamat Datang Polman | *(Bisu)* | Lanjutkan **`Discover`** | **A4:** `SFX_Transition_Fast_Whoosh_Mixkit.wav` (`00:07.0`)<br>**A3:** `SFX_Ambience_Wind_Blowing_Mixkit.wav` | Whoosh: `-24 dB`<br>Angin: **Fade In `0.5s`** ke `-28 dB` |
| **4** | `00:09–00:12` | Drone Polewali Mandar urban area | *(Bisu)* | Lanjutkan **`Discover`** | **A3:** Lanjutkan `Wind_Blowing` | A2 `-16 dB`; Angin `-28 dB` |
| **5** | `00:12–00:14` | Drone view of Mandar waters | *(Bisu)* | Lanjutkan **`Discover`** | **A3:** Ganti ke **`SFX_Ambience_Close_Sea_Waves_Mixkit.wav`** di `00:12.0` | Ombak: **Fade In `0.8s`** ke `-24 dB` |
| **6** | `00:14–00:17` | Delegate looking at Sayyang Pattu'du statue | *(Bisu)* | **`Discover`** **Fade Out** (`00:15.5–00:17.2`) | **A3:** Ombak **Fade Out** `00:15.0`<br>**A4:** **`SFX_Transition_Trailer_Riser_Mixkit.wav`** (`00:14.5–00:17.0`) | Riser: `-18 dB` memuncak di `00:17` |
| **7** | `00:17–00:20` | Two women walking down stairs toward horse | **`MUSIC_Cultural_Mandar_Rebana_Parrawana_Dokumenter.wav`** mulai **`00:17.0`** | **`MUSIC_Cultural_Mandar_Kacapi_Sayyang_Pattudu_Dokumenter.wav`** mulai `00:17.0` *(opsional lapis tipis `Classical_Vibes_4` di `-26 dB`)* | *(Matikan ambience laut)* | A1 Rebana: **Fade In `0.8s`**, level **`-14 dB`**<br>A2 Kacapi: **Fade In `1.0s`**, level **`-20 dB`** |
| **8** | `00:20–00:26` | Participants mounting Sayyang Pattu'du horse | Lanjutkan **Rebana Mandar** (`MAN-01`) | Lanjutkan **Kacapi Mandar** (`MAN-02`) | *(Kosong)* | Rebana tetap memimpin ritme budaya |
| **9** | `00:26–00:29` | Delegate walking toward statue | Lanjutkan **Rebana Mandar** | Lanjutkan **Kacapi Mandar** | *(Kosong)* | Stabil `-14 dB` (rebana) & `-20 dB` (kacapi) |
| **10** | `00:29–00:33` | Sayyang Pattu'du horse with two participants | Lanjutkan **Rebana Mandar** *(ulang/loop klip `14.6s` dengan crossfade `0.2s`)* | Lanjutkan **Kacapi Mandar** | **A3 (opsional):** `MUSIC_Cultural_Mandar_Sayyang_Pattudu_Procession_Dokumenter.wav` (`-24 dB`) | Menambah suasana sorak arak-arakan Sayyang Pattu'du asli |
| **11** | `00:33–00:37` | Second Sayyang Pattu'du horse shot | Lanjutkan **Rebana Mandar** | Lanjutkan **Kacapi Mandar** | **A3 (opsional):** Lanjut suasana prosesi | Pertahankan energi budaya |
| **12** | `00:37–00:41` | Delegate walking around the statue | **Rebana Mandar** **Fade Out** (`00:38.5–00:40.8`) | **Kacapi Mandar** **Fade Out** (`00:38.5–00:40.8`) | *(Kosong)* | Pastikan sebelum `00:41.0` musik latar bersih/hilang |
| **13** | `00:41–00:47` | **Pakkalinda'daq performer** | **WAJIB ASLI:** **`ORIGINAL_Pakkalindadaq_Live_Performance.wav`** (`00:41.0–00:47.6`) | **MUTE BGM sepenuhnya** | *(JANGAN tambah instrumen/vokal lain)* | Naikkan gain **`+3 s/d +5 dB`** (target `-10 s/d -8 dBFS`) |
| **14** | `00:47–00:53` | **Person playing Mandar rebana** | **`MUSIC_Cultural_Mandar_Rebana_Parrawana_Dokumenter.wav`** (`00:47.0–00:53.0`) | **MUTE BGM** | *(JANGAN timpa perkusi lain)* | Turunkan gain ke **`-10 s/d -8 dB`** (agar puncak di `-12 s/d -8 dBFS`) |
| **15** | `00:53–00:57` | Closing shot of Sayyang Pattu'du | Ekor Rebana **Fade Out** (`00:53–00:55.5`) | Masuk **Kacapi Mandar** (`MAN-02`) + **`MUSIC_Cultural_Support_Classical_Vibes_4_Mixkit.mp3`** (`00:25–00:30` lagu) di `00:53.0` | *(Kosong)* | **Fade In `1.0s`** ke `-18 dB` |
| **16** | `00:57–01:02` | Zoom-in motif Sandeq di batik -> Sandeq | *(Bisu)* | Kacapi & `Classical vibes 4` **Fade Out** (`00:57–01:00`) | **A4:** **`SFX_Transition_Wind_Swoosh_Mixkit.wav`** (`00:57.0`) + **`SFX_Transition_Epic_Orchestra_Swell_Mixkit.wav`** (`00:57.0–01:02.0`) | `Wind Swoosh` (`-16 dB`) pas zoom batik; `Orchestra Swell` (`-14 dB`) memuncak di `01:02` |
| **17** | `01:02–01:05` | Drone multiple Sandeq preparing to sail | *(Bisu)* | Mulai **`MUSIC_Maritime_Cinematic_Driving_Ambition_Mixkit.mp3`** dari **`00:00`** lagu di `01:02.0` | **A4:** `SFX_Maritime_Trailer_Epic_Impact_Mixkit.wav` (`01:02.0`)<br>**A3:** **`SFX_Ambience_Sea_Waves_Loop_Mixkit.wav`** | A2 `-16 dB`, A4 Impact `-18 dB`, A3 Ombak `-26 dB` |
| **18** | `01:05–01:09` | Multiple Sandeq sailing | *(Bisu)* | Lanjutkan **`Driving Ambition`** (`00:03–00:07` lagu) | **A3:** Lanjut `Sea_Waves_Loop` (`-25 dB`) | Energi mulai naik |
| **19** | `01:09–01:12` | Delegate walking along the beach | *(Bisu)* | Lanjutkan **`Driving Ambition`** (`00:07–00:10` lagu) | **A3:** Crossfade ke `Close_Sea_Waves` (`-24 dB`) | Hubungkan delegasi dengan pantai |
| **20** | `01:12–01:18` | Drone footage of Sandeq maneuvering | *(Bisu)* | **Potong/Crossfade `0.3s`** di `Driving Ambition` ke **`00:25–00:31`** lagu | **A4:** `Maritime_Trailer_Epic_Impact` (`01:12.0`, `-18 dB`)<br>**A3:** **`SFX_Ambience_Windy_Sea_Loop_Mixkit.wav`** (`-25 dB`) | A2 naik ke `-14 dB`; jangan beri impact di setiap cut |
| **21** | `01:18–01:22` | Drone zoom-in on a sailing Sandeq | *(Bisu)* | Lanjutkan **`Driving Ambition`** (`00:31–00:35` lagu) | **A3:** Lanjut `Windy_Sea_Loop` (`-25 dB`) | Momentum maritim |
| **22** | `01:22–01:27` | **Delegate facing the sea** *(Jeda emosional)* | *(Bisu)* | Turunkan **`Driving Ambition`** `-8 dB` (`-22 dB`) + aktifkan **Low-Pass Filter ~1.2 kHz** | **A3:** Ganti ke `Close_Sea_Waves` (`-21 dB`) + `Wind_Blowing` (`-30 dB`) | Perkusi meredup, sisakan string + ombak lembut |
| **23a** | `01:27–01:29` | Zoom-in on sailing Sandeq *(Build akhir)* | *(Bisu)* | Lepas LPF & crossfade `Driving Ambition` ke **`00:40`** lagu | **A4:** `Trailer_Riser` (`01:27–01:29`, `-16 dB`) | Bangun ketegangan |
| **23b** | `01:29–01:32` | **Wide drone dozens of Sandeq sailing** *(KLIMAKS)* | *(Bisu)* | **`Driving Ambition`** klimaks penuh (**`00:42–00:45`** lagu) | **A4:** **`SFX_Climax_Whoosh_Deep_Impact_Mixkit.mp3`** tepat di **`01:29.0`** (`-12 dB`)<br>**A3:** `Windy_Sea_Loop` (`-24 dB`) | Aksen terkuat video di `01:29.0`; BGM `-14 s/d -13 dB` |
| **23c** | `01:32–01:34` | Island in the sea *(Ruang napas)* | *(Bisu)* | Turunkan `Driving Ambition` **`-3 dB`** selama 2 detik | **A3:** Ombak lembut (`-26 dB`) | Ruang napas visual |
| **23d** | `01:34–01:37` | Another Sandeq sailing shot *(Final lift)* | *(Bisu)* | Naikkan `Driving Ambition` (`00:47–00:50` lagu), lalu **Fade Out `1.2s`** di `01:36.8` | **A3:** `Sea_Waves_Loop` (`-25 dB`) | Angkatan terakhir |
| **24a** | `01:37–01:38` | Transition gap preparing closing | *(Bisu)* | Crossfade ke **`MUSIC_Closing_Emotional_Rebecca_On_The_Shore_Mixkit.mp3`** | **A4:** `Fast_Whoosh` tipis (`-28 dB`) jika perlu | Persiapan dialog |
| **24b** | `01:38–01:48` | **Delegate delivering closing line** | **WAJIB JELAS:** **`ORIGINAL_Closing_Dialogue_Haerul.wav`** | **`Rebecca on the Shore`** *(ambil bagian **`01:00–01:11`** lagu)* | **A3:** `Close_Sea_Waves` tipis (`-30 dB`) | **A1 Dialog:** HPF `80 Hz` + denoise ringan + gain `+3..+5 dB` (`-10..-6 dBFS`)<br>**A2 BGM:** `-24 dB` saat bicara (`01:38–01:46.2`), lalu naikkan `+4 dB` di `01:46.2–01:48.4` & fade out |
