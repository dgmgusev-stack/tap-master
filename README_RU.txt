TAP MASTER — Android-проект для сборки APK

Что внутри:
- Android-приложение на Kotlin с WebView.
- Игра хранится локально в app/src/main/assets/index.html.
- Монеты, скины, улучшения и рекорд сохраняются через localStorage WebView.
- GitHub Actions workflow автоматически собирает debug APK.

Как получить APK с телефона:
1. Создай репозиторий на GitHub и загрузи туда всё содержимое этого ZIP.
2. Открой вкладку Actions в репозитории.
3. Выбери workflow "Build TAP MASTER APK" и нажми Run workflow.
4. Когда сборка закончится, открой её и скачай Artifact "TAP-MASTER-APK".
5. Распакуй artifact ZIP — внутри будет app-debug.apk.
6. Открой APK на Android и разреши установку из этого источника, если Android спросит.

Примечание:
Это debug APK для личной установки и тестирования, не подписанный релиз для Google Play.
В этой среде нет Android SDK/Gradle, поэтому APK здесь не компилируется.
