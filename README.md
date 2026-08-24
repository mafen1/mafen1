<div align="center">

# Frolov Alexey

**Junior Android Developer**

Kotlin/Jetpack Compose, Room, WebSocket, Ktor и Docker. Спроектировал мессенджер со сквозным шифрованием.

[![Telegram](https://img.shields.io/badge/Telegram-@maafeeen-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/maafeeen)
[![Email](https://img.shields.io/badge/Email-frolalex07@yandex.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:frolalex07@yandex.com)
[![GitHub](https://img.shields.io/badge/GitHub-mafen1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mafen1)

</div>

---

## Чем я занимаюсь

- Разрабатываю Android-приложения на Kotlin: Jetpack Compose, Material Design 3, type-safe Navigation, ViewModels.
- Строю архитектуру: MVVM + Clean Architecture (data/domain/ui), Hilt DI, единая обработка ошибок через Result.
- Делаю real-time фичи: WebSocket с авто-reconnect и backoff, offline-first через Room + WorkManager (outbox).
- Реализую безопасность: E2E-шифрование чатов AES-GCM + RSA в Android Keystore, JWT, EncryptedSharedPreferences.
- Пишу backend на Ktor: REST + WebSocket, PostgreSQL (Exposed, HikariCP), bcrypt, rate limiting, Docker Compose.

## Стек

### Android
<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Material_3-757575?style=flat-square&logo=materialdesign&logoColor=white" alt="Material Design 3" />
  <img src="https://img.shields.io/badge/Room-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Room" />
  <img src="https://img.shields.io/badge/DataStore-3DDC84?style=flat-square&logo=android&logoColor=white" alt="DataStore" />
  <img src="https://img.shields.io/badge/WorkManager-3DDC84?style=flat-square&logo=android&logoColor=white" alt="WorkManager" />
  <img src="https://img.shields.io/badge/Hilt-018671?style=flat-square&logo=dagger&logoColor=white" alt="Hilt" />
  <img src="https://img.shields.io/badge/Coil-E682FF?style=flat-square&logo=coil&logoColor=white" alt="Coil" />
</p>

### Сеть и асинхронность
<p>
  <img src="https://img.shields.io/badge/Retrofit-00B0FF?style=flat-square&logo=square&logoColor=white" alt="Retrofit" />
  <img src="https://img.shields.io/badge/OkHttp-3F51B5?style=flat-square&logo=square&logoColor=white" alt="OkHttp" />
  <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSocket" />
  <img src="https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Coroutines" />
  <img src="https://img.shields.io/badge/Flow-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Flow" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Ktor-BF360C?style=flat-square&logo=ktor&logoColor=white" alt="Ktor" />
  <img src="https://img.shields.io/badge/Exposed-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Exposed ORM" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />
</p>

### Инструменты и тестирование
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Gradle_KTS-02303A?style=flat-square&logo=gradle&logoColor=white" alt="Gradle Kotlin DSL" />
  <img src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit" />
  <img src="https://img.shields.io/badge/Mockito-782B90?style=flat-square&logo=mockito&logoColor=white" alt="Mockito" />
  <img src="https://img.shields.io/badge/MockWebServer-3F51B5?style=flat-square&logo=square&logoColor=white" alt="MockWebServer" />
  <img src="https://img.shields.io/badge/LeakCanary-CB2E06?style=flat-square&logo=android&logoColor=white" alt="LeakCanary" />
</p>

## Проекты

| Проект | Что внутри | Стек |
| --- | --- | --- |
| [MessageApp](https://github.com/mafen1/MessageApp) | Мессенджер со сквозным шифрованием (AES-GCM + RSA/Keystore): чаты, друзья и заявки, лента новостей, offline-first очередь отправки, авто-reconnect WebSocket, статусы доставки. Покрыт юнит-тестами. | Kotlin, Jetpack Compose, Room, WorkManager, Hilt, WebSocket, Retrofit |
| [ServerMessage](https://github.com/mafen1/ServerMessage) | Backend мессенджера: WebSocket real-time + REST API, JWT с bcrypt (cost 12), rate limiting, хранилище обёрток ключей E2E с версионированием эпох, интеграционные тесты, Docker Compose. | Kotlin, Ktor, Exposed, PostgreSQL, HikariCP, JWT, Docker |

## GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mafen1&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mafen1&layout=compact&theme=github_dark&hide_border=true" alt="Top languages" />
</p>

## Сейчас в фокусе

- Push-уведомления и foreground service для приёма сообщений в фоне.
- Read-receipts («прочитано») поверх существующих статусов доставки.
- CI/CD на GitHub Actions: тесты, lint, сборка APK.
- UI-тесты на Compose и углубление в безопасность E2E-протоколов.

---

<div align="center">

Открыт к junior/middle Android-позициям, стажировкам и интересным задачам.

</div>
