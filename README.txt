GUNUN SORUSU - Flutter (Android)

1) Zip'i ac, ICINDEKI TUM dosyalari (gizli olanlar dahi: .github ve .gitignore) GitHub reposunun
   ana dizinine yukle. pubspec.yaml reponun kokunde olmali.
2) GitHub > Actions sekmesinde "APK Olustur" calisir. Bitince "app-release" artifact'ini indir.
   (CodeMagic kullanirsan codemagic.yaml otomatik algilanir.)
3) Yerelde calistirmak icin: klasorde `flutter create . --platforms=android --project-name gunun_sorusu`
   bir kez, sonra `flutter run`.

Soru eklemek icin: uygulamada "Sorular" sekmesi > "Soru Ekle"
veya lib/data/builtin_questions.dart dosyasina elle ekle.
