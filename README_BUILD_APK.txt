تم تجهيز هذا الأرشيف بحيث تكون جميع الملفات الرئيسية في الجذر مباشرة (بدون مجلد إضافي):
- gradlew / gradlew.bat
- gradle/wrapper/gradle-wrapper.jar و gradle-wrapper.properties
- gradle.properties و settings.gradle.kts و build.gradle.kts
- .github/workflows/build-apk.yml (لبناء APK تلقائياً عند الرفع إلى GitHub)
- app/ (الكود المصدري الكامل بلغة Kotlin و Jetpack Compose و Room)

طريقة البناء:
1) عبر GitHub Actions: ارفع محتويات الملف المضغوط مباشرة إلى مستودع GitHub ليتم بناء app-debug.apk تلقائياً.
2) عبر Android Studio: افتح المجلد بعد فك الضغط واختر Build > Build APK(s).
تم تضمين ملفات خط IBM Plex Sans Arabic (app/src/main/res/font/) وأيقونة التطبيق تلقائياً لتعمل على جميع إصدارات أندرويد.
