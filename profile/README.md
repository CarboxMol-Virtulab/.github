# CarboxMol VirtuLab

### Virtual Laboratory & 3D Interactive Anatomy Education Center
### Qərbi Kaspi Universiteti Təbiət Elmləri Kafedrası

---

## 1. Akademik Mənsubiyyət (Academic Affiliation)

* **Müəssisə:** Qərbi Kaspi Universiteti (Western Caspian University - WCU)
* **Kafedra:** Təbiət Elmləri Kafedrası (Department of Natural Sciences)
* **Müəllif və Layihə Rəhbəri:** Suleiman M. Hajizadeh
* **İxtisas İstiqaməti:** Bioinformatika, Tətbiqi Biologiya və Kompüter Elmləri
* **Rəsmi Əlaqə:** suleyman.hacizade1@gmail.com
* **Məkan:** Bakı, Azərbaycan (Baku, Azerbaijan)
* **Rəsmi Portal:** https://carboxmol-virtulab.github.io

---

## 2. Məlumat Bazası və Mənbə Kodu Giriş Qaydaları (Data & Source Access Policy)

### Məxfilik Bildirişi (Private Repository Notice)
CarboxMol VirtuLab platformasının əsas mənbə kodu, 3D anatomik modelləşdirmə faylları, laboratoriya alqoritmləri və tədqiqat məlumat bazası daxili tədris və tədqiqat məqsədləri üçün qapalı (Private) rejimdə qorunur.

Layihə ilə tanışlıq, elmi-tədqiqat əməkdaşlığı və ya məlumat bazasına giriş icazəsi (Access) əldə etmək üçün müəllifə rəsmi elektron poçt vasitəsilə müraciət edilməlidir:
* **E-poçt:** suleyman.hacizade1@gmail.com
* **Mövzu:** CarboxMol VirtuLab - Tədqiqat və Giriş İcazəsi Müraciəti

### Private Data & Source Code Policy (English)
The core source code, high-resolution 3D anatomical datasets, and clinical laboratory algorithms within this organization are maintained in private repositories for academic integrity and institutional governance. To request authorized access or propose research collaboration, please contact the project lead directly at suleyman.hacizade1@gmail.com.

---

## 3. Layihənin Təyinatı və Missiyası (Mission and Scope)

CarboxMol VirtuLab Qərbi Kaspi Universitetinin biologiya, təbiət elmləri, biotexnologiya və tibbə hazırlıq ixtisasları üzrə təhsil alan tələbələri üçün hazırlanmış rəqəmsal tədris və simulyasiya ekosistemidir. 

Platformanın əsas məqsədi dərsliklərdə verilən nəzəri bilikləri real vaxt rejimində çalışan interaktiv simulyasiyalarla birləşdirmək, tələbələrin klinik təfəkkürünü və laboratoriya vərdişlərini inkişaf etdirməkdir.

---

## 4. Təşkilatın Rəsmi Repozitoriyaları (Official Repositories)

| Repozitoriya | Status | Təyinatı |
| :--- | :--- | :--- |
| Carboxmol-virtulab | Qapalı (Private) | Əsas mənbə kodu (Next.js, TypeScript, Three.js, WebGL, Service Worker) |
| CarboxMol-Virtulab.github.io | Açıq (Public) | Rəsmi statik veb yayımlanması və PWA istehsalat mühiti |
| .github | Açıq (Public) | Təşkilat səviyyəli profil sənədləşməsi və standartlar |

---

## 5. Əsas İnteraktiv Modullar (Core Modules)

### 1. 3D İnsan Anatomiyası Atlası
* Üçölçülü fəza koordinatları əsasında 360 dərəcə orqan müşahidəsi, kəsik aparılması və rentgen vizuallaşdırması.
* Beynəlxalq standartlara uyğun ardıcıl üçdilli nomenklatura:
  1. Latın dili (Terminologia Anatomica - TA2)
  2. İngilis dili
  3. Azərbaycan dili
* 201 fərdi orqan və 11 anatomik sistem üzrə funksional, topoqrafik və klinik patologiya qeydləri.
* Latınca terminlərin fonetik nitq sintezi tələffüzü.

### 2. Virtual İşıq Mikroskopu Simulyatoru
* Optik mexanika simulyasiyası: 4x, 10x, 40x və 100x (yağ immersion) obyektivlər.
* Makrometrik və mikrometrik vint fokuslaması ilə fiziki optik dərinlik və bulanıqlıq effekti.
* 17 fərdi histoloji və mikrobioloji preparat kolleksiyası (qan yaxması, hərəki neyron, eninəzolaqlı əzələ, miokard, bitki toxumaları, Qram boyanması).
* Hüceyrələrin həndəsi ölçülərini təyin etmək üçün kalibrlənmiş mikrometrik şəbəkə.

### 3. Klinik və Kimyəvi Laboratoriya Sınaqları
* Seroloji qan qrupunun təyini (ABO və Rh sistemləri) və aqqlütinasiya sınaqları.
* Katalaza ferment kinetikası: temperatur və pH dərəcəsinin reaksiyanın ilkin sürətinə və fermentin denaturasiyasına təsiri.
* Eritrosit membranının osmotik rezistentliyi (hipotonik hemoliz, izotonik tarazlıq, hipertonik plazmoliz).
* Molekulyar biologiya: PZR (polimeraza zəncir reaksiyası) termik dövriyyəsi və aqaroza gelində DNT elektroforezi.
* Termokimya: qələvi metalların su ilə reaksiyasında entalpiya dəyişmələri və alov emissiyası.

### 4. Laboratoriya Cihazları və Biotəhlükəsizlik Qaydaları (SOP)
* 16 analitik laboratoriya cihazının (avtomat mikropipetlər, sentrifuqa, spektrofotometr, avtoklav və s.) standart əməliyyat prosedurları.
* BSL-1 səviyyəsindən BSL-4 səviyyəsinə qədər beynəlxalq biotəhlükəsizlik protokolları.

### 5. Qiymətləndirmə, Flashcard Sistemi və Akademik Protokol
* Tibbi və bioloji imtahan bazası üzrə interaktiv testlər.
* İkitərəfli 3D termin kartları (Spaced Repetition metodu).
* Tələbənin nəticələrini təsdiq edən çap edilə bilən rəsmi laboratoriya protokolu.

---

## 6. Proqram Arxitekturası və Oflayn PWA Standartı

* **Frontend Arxitekturası:** Next.js (App Router), React, TypeScript, Tailwind CSS.
* **3D Qrafika Mühərriki:** Three.js (WebGL Hardware Accelerated Rendering).
* **Oflayn İnteqrasiya:** W3C Service Worker standartı, Cache Storage API və Web App Manifest.
* **Platformalararası Uyğunluq:** Masaüstü (macOS, Windows, Linux) və mobil (iOS, Android) əməliyyat sistemlərində veb brauzer və ya quraşdırılmış tətbiq (Standalone App) kimi 100% oflayn rejimdə işləmə imkanı.

---

## 7. Müəlliflik Hüququ və Əlaqə

CarboxMol VirtuLab platformasının bütün konseptual strukturu, proqram təminatı arxitekturası və tədris materialları Qərbi Kaspi Universiteti Təbiət Elmləri Kafedrasının müəllif hüquqları çərçivəsində tənzimlənir.

* **Layihə Rəhbəri:** Suleiman M. Hajizadeh
* **Əlaqə E-poçtu:** suleyman.hacizade1@gmail.com
* **Təşkilat:** Western Caspian University | Department of Natural Sciences
* **Ünvan:** Bakı, Azərbaycan
