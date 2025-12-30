#  SecureAuth: Praktikum #7 - Menerapkan Desain UI Modern

Aplikasi **SecureAuth** merupakan hasil praktikum ke-7 yang berfokus pada implementasi desain antarmuka modern menggunakan **Jetpack Compose** dan **Material Design 3**. Proyek ini menekankan pada pengalaman pengguna (UX) yang intuitif, keamanan biometrik terintegrasi, dan fleksibilitas tema dinamis.

##  Tech Stack & Tools

Proyek ini dibangun menggunakan standar pengembangan Android modern untuk memastikan performa dan skalabilitas:

| Tools & Libraries | Badge | Deskripsi |
| :--- | :--- | :--- |
| **Kotlin** | ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) | Bahasa utama pengembangan Android modern. |
| **Jetpack Compose** | ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4.svg?style=for-the-badge&logo=jetpack-compose&logoColor=white) | Toolkit UI deklaratif untuk membangun antarmuka. |
| **Android Studio** | ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white) | IDE resmi untuk pengembangan aplikasi Android. |
| **Material 3** | ![Material Design](https://img.shields.io/badge/Material%203-757575.svg?style=for-the-badge&logo=material-design&logoColor=white) | Standar desain terbaru untuk komponen UI Google. |

## 📁 Struktur Proyek (Project Structure)

Berdasarkan arsitektur yang diterapkan, proyek ini diorganisir secara sistematis untuk mendukung skalabilitas dan kemudahan pemeliharaan kode:

```text
id.antasari.p7_modern_ui_230104040205
├── ui/
│   ├── auth/                # Logika dan State Autentikasi
│   │   ├── AuthViewModel.kt
│   │   └── SecureAuthApp.kt
│   ├── components/          # Reusable UI Elements (Atomic Design)
│   │   ├── AppButton.kt
│   │   ├── AppCard.kt
│   │   ├── AppTextField.kt
│   │   ├── SectionHeader.kt
│   │   └── TopBar.kt
│   ├── navigation/          # Pengaturan Alur Navigasi Aplikasi
│   │   └── AppNavHost.kt
│   └── theme/               # Material 3 Styling & Design System
│       ├── Color.kt
│       ├── Shape.kt
│       ├── Theme.kt
│       └── Type.kt
├── AccountStorage.kt        # Manajemen Penyimpanan Akun Lokal
├── BiometricUtils.kt        # Utilitas Keamanan Biometrik
├── CreateAccountScreen.kt   # UI Pendaftaran Akun
├── HomeScreen.kt            # UI Dashboard Utama
├── LoginScreen.kt           # UI Masuk Aplikasi
├── MainActivity.kt          # Entry Point & Lifecycle Management
├── SecurityDetailsScreen.kt # UI Analitik Keamanan
└── SettingsScreen.kt        # UI Pengaturan Aplikasi

```

## 🌟 Fitur Utama

* **Modern Design System**: Implementasi tipografi **Poppins** dan komponen Material 3 yang disesuaikan untuk estetika modern.
* **Security Score Analytics**: Visualisasi skor keamanan (92/100) yang interaktif bagi pengguna.
* **Biometric Authentication**: Keamanan tingkat lanjut menggunakan sensor sidik jari atau pengenalan wajah perangkat.
* **Dynamic Theme Switching**: Dukungan penuh dan adaptasi otomatis antara *Dark Mode* dan *Light Mode*.
* **App Lock Logic**: Sistem keamanan otomatis yang mengunci aplikasi saat berada di background.

## 📸 Dokumentasi Visual (App Flow)

Berikut adalah 10 layar utama yang mengimplementasikan Desain UI Modern:

### 1. Autentikasi (Login & Register)

| Layar | Dark Mode | Light Mode |
| --- | --- | --- |
| **Login** | <img src="P7-Menerapkan-Desain-UI-Modern/P7_UI_Modern_Login_Screen_Dark_Mode.png" width="200"> | <img src="P7-Menerapkan-Desain-UI-Modern/P7_UI_Modern_Login_Screen_Light_Mode.png" width="200"> |
| **Register** | <img src="P7-Menerapkan-Desain-UI-Modern/UI_Register_Dark_Mode.png" width="200"> | <img src="P7-Menerapkan-Desain-UI-Modern/UI_Register_Light_Mode.png" width="200"> |

### 2. Dashboard & Keamanan

| Layar | Dark Mode | Light Mode |
| --- | --- | --- |
| **Dashboard** | <img src="P7-Menerapkan-Desain-UI-Modern/Tampilan_Dashboard_Utama_dan_Ringkasan_Keamanan_Pengguna_(Dark_Mode).png" width="200"> | <img src="P7-Menerapkan-Desain-UI-Modern/Tampilan_Dashboard_Utama_dan_Ringkasan_Keamanan_Pengguna_(Light_Mode).png" width="200"> |
| **Security Details** | <img src="P7-Menerapkan-Desain-UI-Modern/Security_Analytics_Details_Dark_Mode.png" width="200"> | <img src="P7-Menerapkan-Desain-UI-Modern/Security_Analytics_Details_Light_Mode.png" width="200"> |

### 3. Pengaturan (Settings)

| Layar | Dark Mode | Light Mode |
| --- | --- | --- |
| **Settings** | <img src="P7-Menerapkan-Desain-UI-Modern/app_settings_Dark_Mode.png" width="200"> | <img src="P7-Menerapkan-Desain-UI-Modern/app_settings_Light_Mode.png" width="200"> |

---

**Informasi Mahasiswa:**

* **Nama**: Ivan Dwika Bagaskara (Rain/Hujan)
* **NIM**: 230104040205
* **Mata Kuliah**: Mobile Programming
* **Praktikum**: #7 Menerapkan Desain UI Modern

```