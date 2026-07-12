# UI Test Automation Framework

Framework ini dibuat menggunakan:

- Java
- Gradle
- Selenium WebDriver
- Cucumber
- JUnit

## Struktur Project

```
src
├── main
│   └── java
│       └── org.example.pages
├── test
│   ├── java
│   │   ├── hooks
│   │   ├── runners
│   │   └── stepdefinitions
│   └── resources
│       └── features
```

## Cara Menjalankan

1. Clone repository.
2. Buka project menggunakan IntelliJ IDEA.
3. Jalankan perintah:

```bash
gradlew test
```

Atau jalankan `TestRunner.java` langsung dari IntelliJ.

## Laporan Hasil Test

Setelah pengujian selesai, laporan dapat dilihat pada:

```
reports/cucumber-report.html
```

## Test Case

### Positive Test
- Login dengan username dan password yang benar.

### Negative Test
- Login dengan username yang salah.
- Login dengan password yang salah.

### Boundary Test
- Login dengan username kosong.
- Login dengan username yang sangat panjang.