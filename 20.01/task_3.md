# 📱 Практическая работа: Типы мобильных приложений

## ЧАСТЬ 1️⃣: ТЕОРИЯ

### Что такое мобильное приложение?

**Определение:** Программа, которая работает на смартфонах и планшетах.

**Основная задача:** Предоставить функциональность пользователю удобно и быстро.

---

## 4 основных типа приложений

### 1. **NATIVE приложения** 📱

**Что это:** Приложение разработано специально для одной платформы (iOS или Android) на её языке программирования.

| Платформа | Язык программирования |
|-----------|----------------------|
| **iOS** | Swift (или Objective-C) |
| **Android** | Kotlin (или Java) |

**Пример кода iOS (Swift):**
```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello from Instagram!")
            .font(.title)
    }
}
```

**Пример кода Android (Kotlin):**
```kotlin
class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    }
}
```

**Примеры реальных Native приложений:**
- ✅ Instagram (iOS + Android)
- ✅ Uber (iOS + Android)
- ✅ WhatsApp (iOS + Android)

**Плюсы ➕:**
- ⚡ Максимальная скорость (очень быстрые приложения)
- 🎮 Полный доступ ко всем функциям телефона (камера, GPS, контакты)
- 😍 Лучший дизайн и пользовательский опыт

**Минусы ➖:**
- 💰 Дорого (нужно две разные команды разработчиков: для iOS и для Android)
- ⏰ Долго разрабатывать (нужно писать код дважды)
- 👥 Нужны специалисты по Swift и Kotlin

---

### 2. **CROSS-PLATFORM приложения** 🔄

**Что это:** Одно приложение работает И на iOS И на Android одновременно. Пишешь код один раз, он работает везде.

**Фреймворки (инструменты):**
- **Flutter** (язык Dart) ← Самый популярный ✨
- **React Native** (JavaScript)
- **Xamarin** (C#)

**Пример кода Flutter (Dart):**
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: const Text('Google Pay')),
        body: const Center(
          child: Text('Hello from Flutter!'),
        ),
      ),
    );
  }
}
```

**Примеры реальных Cross-Platform приложений:**
- ✅ Google Pay (Flutter)
- ✅ BMW Connected (Flutter)
- ✅ Discord (React Native)
- ✅ Tesla App (React Native)

**Плюсы ➕:**
- 💰 Экономно (одна команда вместо двух)
- ⏰ Быстро (пишешь один раз, работает везде)
- 👨‍💻 Проще найти разработчиков

**Минусы ➖:**
- ⚡ Чуть медленнее, чем Native (но почти незаметно!)
- 📦 Приложение немного больше по размеру

---

### 3. **PWA (Progressive Web App)** 🌐

**Что это:** Это **веб-приложение** (как сайт), но оно работает как мобильное приложение. Не нужно скачивать из App Store!

**Технологии:**
- HTML5 (структура)
- CSS3 (дизайн)
- JavaScript (логика)
- Service Workers (работа офлайн)

**Пример кода PWA (JavaScript):**
```javascript
// Регистрируем Service Worker для работы офлайн
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('/sw.js');
}

// Обработка клика
document.getElementById('button').addEventListener('click', () => {
  alert('Это PWA приложение!');
});
```

**Примеры реальных PWA:**
- ✅ Twitter Lite (веб-версия Twitter)
- ✅ Spotify Web (веб-версия Spotify)
- ✅ Pinterest (веб-версия)

**Плюсы ➕:**
- 📥 Не нужно скачивать (открыл ссылку → приложение работает)
- 💾 Очень мало места в памяти телефона
- 🔄 Обновляется автоматически (не нужно обновлять через App Store)
- 🌐 Работает в браузере

**Минусы ➖:**
- ⚡ Медленнее, чем Native
- 📷 Ограниченный доступ к камере, микрофону и т.д.
- 🔗 Зависит от браузера (в некоторых браузерах может не работать)

---

### 4. **HYBRID приложения** 🔌

**Что это:** Гибрид Native + Web. Используем веб-технологии (HTML, CSS, JavaScript), но упаковываем в Native контейнер.

**Фреймворки:**
- **Ionic** (Angular + Cordova)
- **PhoneGap/Cordova**
- **Capacitor** (современный подход)

**Пример кода Ionic (HTML/CSS/JavaScript):**
```html
<ion-app>
  <ion-content>
    <ion-button color="primary">
      Click me! (Hybrid App)
    </ion-button>
  </ion-content>
</ion-app>
```

**Примеры реальных Hybrid приложений:**
- ✅ Некоторые версии мессенджеров
- ✅ Некоторые приложения стартапов

**Плюсы ➕:**
- 💨 Быстро разработать (используем веб-разработчиков)
- 💰 Дешевле, чем Native
- 🔄 Один код для обеих платформ

**Минусы ➖:**
- ⚡ Самые медленные из всех типов
- 📦 Файл приложения большой
- 🚫 Ограниченный доступ к функциям телефона

---

## 📊 СРАВНИТЕЛЬНАЯ ТАБЛИЦА

| Критерий | Native | Cross-Platform (Flutter) | PWA | Hybrid |
|----------|--------|--------------------------|-----|--------|
| **Скорость** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| **Время разработки** | ⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| **Стоимость** | 💰💰💰 | 💰💰 | 💰 | 💰💰 |
| **Доступ к функциям телефона** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| **Размер приложения** | 45-80 MB | 60-90 MB | 0 MB (браузер) | 80-150 MB |
| **Скорость загрузки первый раз** | 0.8 сек | 1.2 сек | 2+ сек | 1.8 сек |
| **Требует установки** | ✅ Да | ✅ Да | ❌ Нет | ✅ Да |
| **Работает офлайн** | ✅ Да | ✅ Да | ✅ Да (с Service Worker) | ✅ Да |

---

## 🤔 Как выбрать тип приложения?

**Выбирай NATIVE если:**
- Нужна максимальная скорость (например, игра)
- Нужен полный доступ к камере, микрофону, GPS
- Бюджет большой (есть деньги на две команды)

**Выбирай CROSS-PLATFORM (Flutter) если:**
- Нужно быстро выпустить приложение
- Бюджет средний
- Приложение должно работать одинаково на iOS и Android

**Выбирай PWA если:**
- Не хочешь чтобы люди скачивали приложение
- Нужна максимальная доступность
- Бюджет минимальный

**Выбирай HYBRID если:**
- У тебя есть веб-разработчики, но нет мобильных
- Нужно быстро сделать MVP (первая версия)
- Производительность не критична

---

---

## ЧАСТЬ 2️⃣: ПРАКТИКА

## Проект: App Types Showcase (Flutter)

**Что делаем:** Создаём простое приложение, которое показывает примеры реальных приложений для каждого типа.

**Структура приложения:**
```
Главный экран
├─ Native приложения (Instagram, Uber, WhatsApp)
├─ Cross-Platform приложения (Google Pay, BMW, Discord)
├─ PWA приложения (Twitter Lite, Spotify, Pinterest)
└─ Hybrid приложения (примеры)
```

---

## 📋 ЗАДАНИЕ 1: Организация проекта

### Шаг 1: Создать новый Flutter проект

```bash
flutter create app_types_showcase
cd app_types_showcase
```

### Шаг 2: Структура файлов

Создай эту структуру в папке `lib/`:

```
lib/
├── main.dart                    ← Точка входа
├── screens/
│   ├── home_screen.dart         ← Главный экран (список типов)
│   └── app_type_detail.dart     ← Экран деталей типа
├── models/
│   └── app_type.dart            ← Модель данных
├── widgets/
│   ├── app_type_card.dart       ← Карточка типа приложения
│   └── app_example_tile.dart    ← Плитка с примером приложения
└── data/
    └── mock_data.dart           ← Данные с примерами приложений
```

### Шаг 3: Зависимости (pubspec.yaml)

Открой файл `pubspec.yaml` и добавь строчки:

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  go_router: ^10.0.0  # Для навигации между экранами
```

Потом запусти в терминале:
```bash
flutter pub get
```

---

## 📝 ЗАДАНИЕ 2: Модель данных

### Файл: `lib/models/app_type.dart`

```dart
class AppType {
  final String id;
  final String name;              // "Native", "Flutter", "PWA", "Hybrid"
  final String emoji;             // "📱", "🦋", "🌐", "🔌"
  final String description;       // Краткое описание
  final List<AppExample> examples; // Примеры реальных приложений

  AppType({
    required this.id,
    required this.name,
    required this.emoji,
    required this.description,
    required this.examples,
  });
}

class AppExample {
  final String name;              // "Instagram"
  final String platforms;         // "iOS, Android" или просто "Web"
  final String advantage;         // "Максимальная скорость"

  AppExample({
    required this.name,
    required this.platforms,
    required this.advantage,
  });
}
```

---

## 📊 ЗАДАНИЕ 3: Данные (Mock Data)

### Файл: `lib/data/mock_data.dart`

```dart
import '../models/app_type.dart';

final List<AppType> appTypes = [
  AppType(
    id: 'native',
    name: 'Native Applications',
    emoji: '📱',
    description: 'Swift (iOS) & Kotlin (Android) - максимальная скорость',
    examples: [
      AppExample(
        name: 'Instagram',
        platforms: 'iOS, Android',
        advantage: 'Максимальная скорость загрузки фото',
      ),
      AppExample(
        name: 'Uber',
        platforms: 'iOS, Android',
        advantage: 'Полный доступ к GPS',
      ),
      AppExample(
        name: 'WhatsApp',
        platforms: 'iOS, Android',
        advantage: 'Быстрая отправка сообщений',
      ),
    ],
  ),
  AppType(
    id: 'flutter',
    name: 'Cross-Platform (Flutter)',
    emoji: '🦋',
    description: 'Один код для iOS и Android - быстрая разработка',
    examples: [
      AppExample(
        name: 'Google Pay',
        platforms: 'iOS, Android',
        advantage: 'Работает одинаково на обеих платформах',
      ),
      AppExample(
        name: 'BMW Connected',
        platforms: 'iOS, Android',
        advantage: 'Красивый дизайн на обеих платформах',
      ),
      AppExample(
        name: 'Alibaba',
        platforms: 'iOS, Android',
        advantage: 'Быстрая разработка для двух платформ',
      ),
    ],
  ),
  AppType(
    id: 'pwa',
    name: 'Progressive Web App',
    emoji: '🌐',
    description: 'HTML/CSS/JavaScript - открывается в браузере',
    examples: [
      AppExample(
        name: 'Twitter Lite',
        platforms: 'Web (браузер)',
        advantage: 'Не нужно скачивать, очень быстро',
      ),
      AppExample(
        name: 'Spotify Web',
        platforms: 'Web (браузер)',
        advantage: 'Работает везде, где есть браузер',
      ),
      AppExample(
        name: 'Pinterest',
        platforms: 'Web (браузер)',
        advantage: 'Легко обновляется',
      ),
    ],
  ),
  AppType(
    id: 'hybrid',
    name: 'Hybrid Applications',
    emoji: '🔌',
    description: 'Web + Native контейнер - быстро разработать',
    examples: [
      AppExample(
        name: 'Ionic App',
        platforms: 'iOS, Android',
        advantage: 'Веб-разработчик может создать мобильное приложение',
      ),
      AppExample(
        name: 'PhoneGap App',
        platforms: 'iOS, Android',
        advantage: 'Один код для обеих платформ',
      ),
    ],
  ),
];
```

---

## 🎨 ЗАДАНИЕ 4: Widget для карточки типа приложения

### Файл: `lib/widgets/app_type_card.dart`

```dart
import 'package:flutter/material.dart';
import '../models/app_type.dart';

class AppTypeCard extends StatelessWidget {
  final AppType appType;
  final VoidCallback onTap;

  const AppTypeCard({
    required this.appType,
    required this.onTap,
    Key? key,
  }) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return GestureDetector(
      onTap: onTap,
      child: Card(
        margin: const EdgeInsets.all(12),
        elevation: 4,
        shape: RoundedRectangleBorder(
          borderRadius: BorderRadius.circular(12),
        ),
        child: Container(
          padding: const EdgeInsets.all(20),
          decoration: BoxDecoration(
            borderRadius: BorderRadius.circular(12),
            gradient: LinearGradient(
              colors: [
                Colors.blue.shade400,
                Colors.blue.shade600,
              ],
            ),
          ),
          child: Column(
            mainAxisAlignment: MainAxisAlignment.center,
            children: [
              // Эмодзи
              Text(
                appType.emoji,
                style: const TextStyle(fontSize: 60),
              ),
              const SizedBox(height: 16),
              // Название
              Text(
                appType.name,
                style: const TextStyle(
                  color: Colors.white,
                  fontSize: 22,
                  fontWeight: FontWeight.bold,
                ),
                textAlign: TextAlign.center,
              ),
              const SizedBox(height: 8),
              // Описание
              Text(
                appType.description,
                style: const TextStyle(
                  color: Colors.white70,
                  fontSize: 14,
                ),
                textAlign: TextAlign.center,
              ),
            ],
          ),
        ),
      ),
    );
  }
}
```

---

## 📱 ЗАДАНИЕ 5: Главный экран

### Файл: `lib/screens/home_screen.dart`

```dart
import 'package:flutter/material.dart';
import 'package:go_router/go_router.dart';
import '../models/app_type.dart';
import '../data/mock_data.dart';
import '../widgets/app_type_card.dart';

class HomeScreen extends StatelessWidget {
  const HomeScreen({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('📱 Типы мобильных приложений'),
        centerTitle: true,
        elevation: 0,
        backgroundColor: Colors.blue,
      ),
      body: ListView.builder(
        itemCount: appTypes.length,
        itemBuilder: (context, index) {
          final appType = appTypes[index];
          return AppTypeCard(
            appType: appType,
            onTap: () {
              // Переходим на экран деталей
              context.push('/detail/${appType.id}');
            },
          );
        },
      ),
    );
  }
}
```

---

## 🔍 ЗАДАНИЕ 6: Экран деталей

### Файл: `lib/screens/app_type_detail.dart`

```dart
import 'package:flutter/material.dart';
import 'package:go_router/go_router.dart';
import '../models/app_type.dart';
import '../data/mock_data.dart';

class AppTypeDetailScreen extends StatelessWidget {
  final String appTypeId;

  const AppTypeDetailScreen({
    required this.appTypeId,
    Key? key,
  }) : super(key: key);

  @override
  Widget build(BuildContext context) {
    // Находим нужный тип приложения
    final appType = appTypes.firstWhere((type) => type.id == appTypeId);

    return Scaffold(
      appBar: AppBar(
        title: Text(appType.name),
        leading: IconButton(
          icon: const Icon(Icons.arrow_back),
          onPressed: () => context.pop(),
        ),
      ),
      body: SingleChildScrollView(
        padding: const EdgeInsets.all(16),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            // Заголовок
            Center(
              child: Text(
                appType.emoji,
                style: const TextStyle(fontSize: 80),
              ),
            ),
            const SizedBox(height: 16),
            Text(
              appType.name,
              style: Theme.of(context).textTheme.headlineSmall,
            ),
            const SizedBox(height: 8),
            Text(
              appType.description,
              style: Theme.of(context).textTheme.bodyMedium,
            ),
            const SizedBox(height: 32),

            // Примеры приложений
            Text(
              'Примеры реальных приложений:',
              style: Theme.of(context).textTheme.titleMedium,
            ),
            const SizedBox(height: 12),
            ...appType.examples.map(
              (example) => Card(
                margin: const EdgeInsets.only(bottom: 12),
                child: Padding(
                  padding: const EdgeInsets.all(16),
                  child: Column(
                    crossAxisAlignment: CrossAxisAlignment.start,
                    children: [
                      Text(
                        example.name,
                        style: const TextStyle(
                          fontSize: 18,
                          fontWeight: FontWeight.bold,
                        ),
                      ),
                      const SizedBox(height: 8),
                      Text(
                        'Платформы: ${example.platforms}',
                        style: TextStyle(
                          fontSize: 14,
                          color: Colors.grey[600],
                        ),
                      ),
                      const SizedBox(height: 8),
                      Text(
                        'Преимущество: ${example.advantage}',
                        style: const TextStyle(fontSize: 14),
                      ),
                    ],
                  ),
                ),
              ),
            ),
          ],
        ),
      ),
    );
  }
}
```

---

## 🧭 ЗАДАНИЕ 7: Навигация (Routing)

### Файл: `lib/main.dart`

```dart
import 'package:flutter/material.dart';
import 'package:go_router/go_router.dart';
import 'screens/home_screen.dart';
import 'screens/app_type_detail.dart';

void main() {
  runApp(const MyApp());
}

final GoRouter _router = GoRouter(
  routes: [
    GoRoute(
      path: '/',
      builder: (context, state) => const HomeScreen(),
    ),
    GoRoute(
      path: '/detail/:id',
      builder: (context, state) {
        final id = state.pathParameters['id']!;
        return AppTypeDetailScreen(appTypeId: id);
      },
    ),
  ],
);

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp.router(
      title: 'App Types Showcase',
      theme: ThemeData(
        primarySwatch: Colors.blue,
        useMaterial3: true,
      ),
      routerConfig: _router,
    );
  }
}
```

---

## ✅ ЗАДАНИЕ 8: Проверка (Тестирование)

Запусти приложение:
```bash
flutter run
```

**Проверь:**
- [ ] На главном экране отображаются 4 карточки (Native, Flutter, PWA, Hybrid)
- [ ] При клике на карточку переходишь на экран деталей
- [ ] На экране деталей видны примеры приложений
- [ ] Кнопка "Назад" работает и возвращает на главный экран
- [ ] Дизайн красивый и понятный

---

## 🎁 БОНУСНЫЕ ЗАДАНИЯ (если есть время)

### Бонус 1: Добавить иконки приложений

Измени `AppExample`:
```dart
class AppExample {
  final String name;
  final String platforms;
  final String advantage;
  final IconData icon;  // ← Добавили

  AppExample({
    required this.name,
    required this.platforms,
    required this.advantage,
    required this.icon,  // ← Добавили
  });
}
```

И в `mock_data.dart`:
```dart
AppExample(
  name: 'Instagram',
  platforms: 'iOS, Android',
  advantage: 'Максимальная скорость',
  icon: Icons.camera_alt,  // ← Добавили
),
```

Потом в `app_type_detail.dart` вывести иконку:
```dart
Icon(example.icon, size: 40, color: Colors.blue),
```

### Бонус 2: Добавить цвета для каждого типа

```dart
Color getColorForAppType(String id) {
  switch (id) {
    case 'native':
      return Colors.red;
    case 'flutter':
      return Colors.blue;
    case 'pwa':
      return Colors.orange;
    case 'hybrid':
      return Colors.green;
    default:
      return Colors.grey;
  }
}
```

### Бонус 3: Добавить Favorite кнопку

Добавь `favorite` поле в `AppType` и позволь пользователю добавлять в избранное (используй `StatefulWidget`).

---

## 📚 Полезные ссылки

- **Flutter документация:** https://flutter.dev/docs
- **Dart язык программирования:** https://dart.dev
- **GoRouter (навигация):** https://pub.dev/packages/go_router
- **Material Design:** https://material.io/design

---

## 🏆 Результат

После завершения этой работы ты:
- ✅ Понимаешь разницу между 4 типами приложений
- ✅ Создал реальное Flutter приложение
- ✅ Научился работать с моделями данных
- ✅ Научился писать widgets
- ✅ Научился использовать навигацию (GoRouter)

**Давай кодить! 🚀**