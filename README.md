# FPV Техшкола

Отдельное Android-приложение для технического обучения FPV, не связанное с приложениями Изи.

## Разделение проектов

- Приложение: `FPV Техшкола`
- Android package ID: `com.artist.fpvschool`
- Каталог репозитория: `fpv-tech-school`
- Workflow сборки: `Build FPV Tech School APK`
- APK artifact: `FPV-Tech-School-APK-<номер запуска>`

## Первая версия

Есть каталог из десяти тем и первый интерактивный урок «Что такое FPV?»: короткое объяснение, презентационные карточки, схема прохождения сигнала и тест. Прогресс сохраняется на устройстве. Видеоролики подключаются как отдельные материалы после подготовки.

Сборка рассчитана на GitHub Actions: GitHub-hosted runner, Temurin JDK 17, Gradle 9.6.0, Android Gradle Plugin 9.5.0 и Android API 37.
