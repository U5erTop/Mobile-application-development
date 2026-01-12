# 📱 Разработка Мобильных Приложений

---

## 📖 О Курсе

Это **комплексный, практический курс**, разработанный для всех, кто хочет освоить современный стек мобильной разработки. Курс охватывает всё — от установки среды разработки до развертывания приложений в App Store и Google Play.

### 🎯 Что вы получите

✅ **Полное понимание экосистемы Flutter и Dart**  
✅ **Навыки разработки production-ready приложений**  
✅ **Знание всех современных подходов к управлению состоянием**  
✅ **Практический опыт работы с API, базами данных и сторонними сервисами**  
✅ **Умение оптимизировать производительность приложений**  
✅ **Портфолио из 4+ полноценных проектов**  
✅ **Сертификат об окончании курса**

---

## 🎓 Результаты Обучения

После прохождения курса студент сможет:

### Фундаментальные навыки
- ✅ Установить и настроить Flutter SDK на Windows, macOS и Linux
- ✅ Понимать и использовать основные концепции Dart (типы, классы, асинхронность)
- ✅ Создавать пользовательские интерфейсы, используя встроенные и кастомные виджеты
- ✅ Работать с системой компоновки Flutter (Row, Column, Stack, GridView и т.д.)
- ✅ Реализовать навигацию между экранами различными способами

### Управление Состоянием
- ✅ Использовать встроенный setState для простых приложений
- ✅ Реализовать Provider для управления состоянием в средних приложениях
- ✅ Применять Riverpod для более продвинутых сценариев
- ✅ Использовать BLoC паттерн для enterprise-уровня приложений
- ✅ Правильно выбирать подход state management в зависимости от проекта

### Работа с Данными
- ✅ Совершать HTTP запросы и работать с REST API
- ✅ Парсить JSON и преобразовывать данные
- ✅ Использовать SharedPreferences для локального хранения простых данных
- ✅ Работать с SQLite базами данных
- ✅ Интегрировать Hive для быстрого NoSQL хранилища
- ✅ Подключить Firebase (Firestore, Real-time Database)
- ✅ Кэшировать данные и оптимизировать сетевые запросы

### Продвинутый UI/UX
- ✅ Создавать плавные анимации и переходы
- ✅ Обрабатывать жесты и пользовательский ввод
- ✅ Создавать кастомные виджеты и расширять встроенные
- ✅ Разрабатывать адаптивные интерфейсы для разных экранов
- ✅ Реализовать Material Design и Cupertino дизайн системы
- ✅ Оптимизировать производительность рендеринга

### Архитектура и Паттерны
- ✅ Применять Clean Architecture в Flutter проектах
- ✅ Использовать MVVM паттерн для структурирования кода
- ✅ Организовать код в слои (Presentation, Domain, Data)
- ✅ Реализовать Dependency Injection
- ✅ Применять Repository паттерн
- ✅ Использовать Mixins и Extensions для переиспользования кода

### Интеграция с Нативным Кодом
- ✅ Работать с Platform Channels
- ✅ Вызывать нативный код из Dart
- ✅ Запрашивать разрешения (camera, location, contacts)
- ✅ Интегрировать камеру, GPS и другие аппаратные функции
- ✅ Работать с файловой системой

### Тестирование
- ✅ Писать Unit тесты
- ✅ Писать Widget тесты
- ✅ Писать Integration тесты
- ✅ Мокировать зависимости с Mockito
- ✅ Достичь хорошего покрытия тестами (>80%)
- ✅ Использовать Continuous Integration

### Оптимизация и Развертывание
- ✅ Профилировать приложения с DevTools
- ✅ Оптимизировать сборку и размер приложения
- ✅ Подготовить приложение к выпуску
- ✅ Подписать приложение
- ✅ Развернуть на iOS (App Store)
- ✅ Развернуть на Android (Google Play)
- ✅ Использовать Firebase для отслеживания ошибок и аналитики

---

## 📚 Полная Структура Курса

### 📁 **МОДУЛЬ 0: ВВЕДЕНИЕ И ПОДГОТОВКА** (1-2 недели)

**Цель:** Подготовить окружение и понять основные концепции Dart

#### 0.1 Установка и Настройка (08 часов)
```
├── Установка Flutter SDK
├── Настройка IDE (VS Code / Android Studio / IntelliJ)
├── Первое приложение "Hello World"
├── Hot Reload и Hot Restart
├── Работа с Flutter DevTools
├── Устранение проблем при установке
└── Кроссплатформенное тестирование (iOS/Android эмуляторы)
```

**Практика:**
- Успешная установка на вашей ОС
- Запуск эмулятора
- Создание и модификация первого приложения

#### 0.2 Основы Dart (16 часов)
```
├── Переменные и типы данных
│   ├── var, int, double, String, bool
│   ├── dynamic и Object
│   ├── Null safety (!)
│   └── Type inference
│
├── Операторы и выражения
│   ├── Арифметические операторы
│   ├── Условные операторы (if, else, switch)
│   ├── Операторы цикла (for, while, do-while)
│   ├── Ternary и null coalescing (??, ?.)
│   └── Spread operator (...)
│
├── Функции
│   ├── Объявление и вызов функций
│   ├── Параметры (позиционные, именованные, с дефолтами)
│   ├── Arrow функции (=>)
│   ├── Анонимные функции и closures
│   ├── Higher-order функции
│   ├── Рекурсия
│   └── Generic функции
│
├── Коллекции
│   ├── Lists (List<T>)
│   ├── Sets (Set<T>)
│   ├── Maps (Map<K, V>)
│   ├── Операции с коллекциями (map, filter, reduce, fold)
│   ├── Spread operators в коллекциях
│   └── Collection if/for
│
├── ООП в Dart
│   ├── Классы и объекты
│   ├── Конструкторы (обычные, именованные, factory)
│   ├── Наследование (extends)
│   ├── Абстрактные классы и интерфейсы
│   ├── Полиморфизм
│   ├── Инкапсуляция (private переменные)
│   ├── Getters и Setters
│   └── Static члены класса
│
├── Mixins
│   ├── Объявление миксина
│   ├── Использование (with)
│   ├── Множественные миксины
│   ├── Различие между extends, implements и with
│   └── Практические примеры
│
├── Extensions
│   ├── Расширение встроенных типов
│   ├── Расширение кастомных классов
│   ├── Generic extensions
│   └── Практические примеры
│
├── Асинхронное программирование
│   ├── Future и async/await
│   ├── Streams и StreamControllers
│   ├── Обработка ошибок (try, catch, finally)
│   ├── Работа с несколькими Future/Stream
│   └── Isolates и фоновое выполнение
│
├── Enum и Pattern Matching
│   ├── Перечисления (enum)
│   ├── Enhanced enums (с данными)
│   ├── Pattern matching (switch expression)
│   └── Sealed classes
│
├── Строки и интерполяция
│   ├── String операции
│   ├── Регулярные выражения
│   ├── String буферизация
│   └── Многострочные строки
│
└── JSON и Сериализация
    ├── Ручное декодирование/кодирование JSON
    ├── jsonDecode и jsonEncode
    ├── Использование пакета json_serializable
    └── Работа с моделями данных
```

**Практика:**
- 20+ практических задач по Dart
- Реализация простого калькулятора
- Парсинг JSON данных
- Работа с Future и Stream

#### 0.3 Введение во Flutter (12 часов)
```
├── Концепция виджетов
│   ├── Stateless vs Stateful виджеты
│   ├── Жизненный цикл виджета
│   ├── Build методы
│   └── Const конструкторы
│
├── Основная архитектура
│   ├── MaterialApp и основная структура
│   ├── Scaffold и основные компоненты
│   ├── Hot Reload и горячая перезагрузка
│   └── Структура проекта
│
├── Основные концепции
│   ├── Unidirectional data flow
│   ├── Immutability и final
│   ├── BuildContext
│   └── Widget key
│
├── Flutter лучшие практики
│   ├── Использование const везде
│   ├── Избегаем rebuild'ов
│   ├── Правильная организация кода
│   └── Лучшие практики производительности
│
└── Flutter анализ и отладка
    ├── Использование DevTools
    ├── Профилирование приложения
    ├── Отладка виджетов
    └── Логирование
```

**Практика:**
- Создание простого приложения со счётчиком
- Работа со State
- Использование DevTools для отладки

---

### 📁 **МОДУЛЬ 1: ФУНДАМЕНТАЛЬНЫЕ КОНЦЕПЦИИ** (2-3 недели)

**Цель:** Освоить базовые навыки создания пользовательских интерфейсов

#### 1.1 Встроенные Виджеты (20 часов)
```
├── Текстовые виджеты
│   ├── Text и RichText
│   ├── TextField и TextFormField
│   ├── Стили текста
│   └── Обработка ввода текста
│
├── Кнопки и интерактивные элементы
│   ├── ElevatedButton, TextButton, OutlinedButton
│   ├── IconButton и FloatingActionButton
│   ├── GestureDetector и InkWell
│   ├── Обработка нажатий
│   └── Визуальная обратная связь
│
├── Контейнеры и компоновка
│   ├── Container и его свойства
│   ├── Padding и Margin
│   ├── Decoration и BoxDecoration
│   ├── Border и BorderRadius
│   └── Shadow и Elevation
│
├── Изображения и иконки
│   ├── Image (network, asset, file)
│   ├── Icon и Icons
│   ├── SVG изображения
│   ├── Обработка ошибок загрузки
│   └── Кэширование изображений
│
├── Списки и сетки
│   ├── ListView и типы (builder, separated)
│   ├── GridView и типы
│   ├── ListTile и Card
│   ├── Бесконечная прокрутка
│   └── Refresh и Pull-to-refresh
│
├── Диалоги и поп-апы
│   ├── AlertDialog
│   ├── SimpleDialog
│   ├── BottomSheet и ModalBottomSheet
│   ├── Snackbar и Toast
│   └── Custom диалоги
│
├── Прогресс и состояние
│   ├── CircularProgressIndicator
│   ├── LinearProgressIndicator
│   ├── FutureBuilder и StreamBuilder
│   ├── Скелетные загрузчики
│   └── Обработка состояния загрузки
│
└── Другие полезные виджеты
    ├── Checkbox и Radio
    ├── Switch и ToggleButtons
    ├── Slider и RangeSlider
    ├── Chip и InputChip
    └── AppBar и TabBar
```

**Практика:**
- Создание различных вариантов кнопок и элементов
- Работа со списками (ListView с 1000+ элементов)
- Создание форм ввода
- Диалоги и поп-апы

#### 1.2 Система Компоновки (18 часов)
```
├── Основные Layout виджеты
│   ├── Row и горизонтальная компоновка
│   ├── Column и вертикальная компоновка
│   ├── Stack и наложение элементов
│   ├── Positioned и абсолютное позиционирование
│   └── Expanded и Flexible
│
├── Продвинутые Layouts
│   ├── SingleChildScrollView и прокрутка
│   ├── CustomScrollView и Sliver виджеты
│   ├── SliverAppBar и коллапсирующие App Bars
│   ├── SliverList и SliverGrid
│   ├── NestedScrollView
│   └── PageView и горизонтальная прокрутка
│
├── Размеры и Space
│   ├── МедиаQuery и размеры экрана
│   ├── Aspect Ratio
│   ├── SizedBox и управление размерами
│   ├── Spacer и распределение пространства
│   └── FractionallySizedBox
│
├── Выравнивание и распределение
│   ├── MainAxisAlignment и CrossAxisAlignment
│   ├── TextAlign и TextDirection
│   ├── Alignment и выравнивание
│   ├── Center и центрирование
│   └── Baseline и выравнивание по базовой линии
│
├── Адаптивный и Responsive дизайн
│   ├── Разные layouts для разных ориентаций
│   ├── Работа с OrientationBuilder
│   ├── LayoutBuilder и адаптивные компоненты
│   ├── Breakpoints и media query
│   └── Работа с кроссплатформенными размерами
│
├── Transform и Effects
│   ├── Transform и масштабирование
│   ├── Rotation и повороты
│   ├── Opacity и прозрачность
│   ├── ClipPath и ClipRRect
│   └── BackdropFilter и размытие
│
└── Практические примеры компоновок
    ├── Instagram-подобный layout
    ├── Twitter-подобный feed
    └── Сложные кастомные layouts
```

**Практика:**
- Создание адаптивного дизайна для телефонов и планшетов
- Создание сложных layouts (Instagram, Airbnb подобные)
- Работа с прокруткой и Sliver
- Построение PageView приложения

#### 1.3 Навигация (14 часов)
```
├── Базовая Навигация
│   ├── Navigator и Push/Pop
│   ├── Named Routes
│   ├── Route параметры
│   ├── Обработка аппаратной кнопки "назад"
│   └── WillPopScope
│
├── Продвинутая Навигация
│   ├── GoRouter (современный подход)
│   ├── Nested Navigation
│   ├── Глубокие ссылки (Deep Linking)
│   ├── Dynamic ссылки
│   └── URL обработка
│
├── Переходы между экранами
│   ├── PageRouteBuilder и кастомные переходы
│   ├── Transition анимации
│   ├── Shared элемент анимация (Hero)
│   ├── Переходы между приложениями
│   └── Обработка системных переходов
│
├── Управление Stack'ом
│   ├── Очистка стека маршрутов
│   ├── Замена маршрутов
│   ├── Обработка множественных стеков
│   └── Состояние при навигации
│
├── Интеграция с State Management
│   ├── Навигация с Provider
│   ├── Навигация с Riverpod
│   ├── Навигация с GetX
│   └── Передача состояния между экранами
│
└── Практические паттерны
    ├── Tab-based навигация
    ├── Drawer навигация
    ├── Bottom navigation bar
    └── Комбинированные стратегии навигации
```

**Практика:**
- Создание приложения с Tab навигацией
- Реализация Deep Linking
- Создание кастомных переходов
- Работа с Hero анимацией

#### 1.4 Стили и Темы (10 часов)
```
├── Material Design
│   ├── Material Design 3 (последняя версия)
│   ├── Color система
│   ├── Typography и текстовые стили
│   ├── Компоненты Material Design
│   └── Material Widgets
│
├── Cupertino Design (iOS)
│   ├── Cupertino компоненты
│   ├── iOS специфичные элементы
│   ├── Нативный iOS look and feel
│   └── CupertinoApp
│
├── Темы приложения
│   ├── ThemeData и создание тем
│   ├── Light и Dark темы
│   ├── Динамическое переключение тем
│   ├── Глобальные стили
│   └── Наследование тем
│
├── Кастомные стили
│   ├── TextStyle и создание стилей текста
│   ├── ButtonStyle для кнопок
│   ├── Custom颜色 палитры
│   ├── Custom Widgets с темами
│   └── Динамическая смена стилей
│
├── Fonts и Typography
│   ├── Встроенные шрифты
│   ├── Кастомные шрифты
│   ├── Google Fonts пакет
│   ├── Font Awesome иконки
│   └── Масштабирование текста
│
├── Размеры и Padding
│   ├── Consistent spacing
│   ├── Design system
│   ├── Темплейты размеров
│   └── Адаптивное масштабирование
│
└── Dark Mode
    ├── Автоматическая смена темы
    ├── Пользовательские настройки темы
    ├── Сохранение выбора темы
    └── Тестирование обеих тем
```

**Практика:**
- Создание собственной темы приложения
- Реализация переключения между Light и Dark режимами
- Использование Google Fonts
- Создание Design System для приложения

---

### 📁 **МОДУЛЬ 2: УПРАВЛЕНИЕ СОСТОЯНИЕМ** (3-4 недели)

**Цель:** Овладеть всеми современными подходами к управлению состоянием

#### 2.1 setState и основы управления состоянием (8 часов)
```
├── setState механизм
│   ├── Как работает setState
│   ├── Когда использовать setState
│   ├── Ограничения setState
│   ├── Производительность и rebuild'ы
│   └── Debug методы
│
├── Stateful Widgets
│   ├── Жизненный цикл (initState, build, dispose)
│   ├── Инициализация состояния
│   ├── Очистка ресурсов (dispose)
│   ├── Did change dependencies
│   └── Did update widget
│
├── ValueNotifier и ValueListenableBuilder
│   ├── Простое управление состоянием
│   ├── ValueListenableBuilder
│   ├── Combine различных ValueNotifier
│   └── Когда использовать ValueNotifier
│
├── Паттерны состояния
│   ├── Single source of truth
│   ├── Immutability
│   ├── Event based updates
│   └── Best practices
│
└── Практические примеры
    ├── Счётчик приложение
    ├── Форма с валидацией
    └── Real-time обновления
```

**Практика:**
- Создание счётчика с setState
- Форма регистрации с валидацией
- Работа с ValueNotifier

#### 2.2 Provider (16 часов)
```
├── Основы Provider
│   ├── Установка и конфигурация
│   ├── ChangeNotifier и notifyListeners
│   ├── Создание провайдеров
│   ├── Consumer и доступ к данным
│   └── MultiProvider
│
├── Типы Провайдеров
│   ├── Provider (простое значение)
│   ├── ChangeNotifierProvider (изменяемое состояние)
│   ├── StateNotifierProvider (продвинутое состояние)
│   ├── FutureProvider (асинхронные данные)
│   ├── StreamProvider (потоки данных)
│   ├── ProxyProvider (зависимость между провайдерами)
│   └── Family провайдеры (параметризованные)
│
├── Использование Consumer
│   ├── Consumer и Consumer2/3
│   ├── Selector для оптимизации rebuild'ов
│   ├── Ref и доступ к провайдерам в функциях
│   ├── watch, read, listen в Consumer
│   └── Обработка ошибок
│
├── Архитектура с Provider
│   ├── Разделение Model на классы
│   ├── Repository паттерн
│   ├── Dependency Injection
│   ├── Тестирование провайдеров
│   └── Best practices
│
├── Продвинутые техники
│   ├── Комбинирование провайдеров
│   ├── Асинхронные провайдеры
│   ├── Обработка ошибок и загрузки
│   ├── Кэширование и refresh
│   └── Отладка провайдеров
│
└── Интеграция с навигацией
    ├── Передача состояния между экранами
    ├── Global state management
    └── Screen-specific состояние
```

**Практика:**
- Создание приложения погоды с Provider
- Реализация Todo приложения
- Работа с FutureProvider для API запросов
- Обработка ошибок и загрузки

#### 2.3 Riverpod (16 часов)
```
├── Введение в Riverpod
│   ├── Почему Riverpod vs Provider
│   ├── Основные концепции
│   ├── Установка и миграция
│   ├── Ref и доступ к провайдерам
│   └── Преимущества
│
├── Типы Riverpod Провайдеров
│   ├── Provider (функциональные провайдеры)
│   ├── StateProvider (простое изменяемое состояние)
│   ├── StateNotifierProvider (продвинутое состояние)
│   ├── FutureProvider (асинхронные данные)
│   ├── StreamProvider (потоки)
│   ├── FamilyModifier (параметризованные)
│   ├── AsyncValue и обработка состояния
│   └── Select для оптимизации
│
├── Использование в Widgets
│   ├── ConsumerWidget
│   ├── ConsumerStatefulWidget
│   ├── HookConsumerWidget
│   ├── Ref в различных контекстах
│   ├── Обработка AsyncValue
│   └── Обработка ошибок
│
├── Продвинутые паттерны
│   ├── Зависимости между провайдерами
│   ├── Асинхронные зависимости
│   ├── Кэширование и invalidate
│   ├── FutureProvider с refresh
│   ├── StreamProvider patterns
│   └── Комбинирование данных
│
├── Интеграция с другими пакетами
│   ├── Riverpod + firebase
│   ├── Riverpod + http/dio
│   ├── Riverpod + hive/sqflite
│   ├── Riverpod + go_router
│   └── Лучшие практики интеграции
│
├── Тестирование с Riverpod
│   ├── ProviderContainer для тестов
│   ├── Мокирование провайдеров
│   ├── Тестирование async провайдеров
│   └── Unit тесты
│
└── Architeture с Riverpod
    ├── Clean Architecture
    ├── Repository паттерн
    ├── Use Cases
    ├── Dependency Injection
    └── Масштабируемая структура
```

**Практика:**
- Миграция приложения с Provider на Riverpod
- Создание комплексного приложения с Riverpod
- Работа с FutureProvider и обработка состояния
- Тестирование Riverpod провайдеров

#### 2.4 BLoC Паттерн (18 часов)
```
├── Основы BLoC (Business Logic Component)
│   ├── Что такое BLoC
│   ├── Event и State паттерны
│   ├── Поток: Event → BLoC → State
│   ├── Преимущества BLoC
│   └── Когда использовать BLoC
│
├── Flutter BLoC пакет
│   ├── BlocProvider и предоставление BLoC
│   ├── BlocBuilder для обновления UI
│   ├── BlocListener для side effects
│   ├── BlocConsumer для комбинирования
│   ├── MultiBlocProvider
│   └── Context расширения
│
├── Создание BLoC'ов
│   ├── Наследование от Bloc<Event, State>
│   ├── Объявление событий
│   ├── Объявление состояний
│   ├── Event handlers
│   ├── Обработка асинхронных операций
│   ├── Обработка ошибок
│   └── Логирование
│
├── Продвинутые BLoC паттерны
│   ├── Вложенные BLoC'и
│   ├── Зависимости между BLoC'ами
│   ├── Использование Repository в BLoC
│   ├── Service Locator для инъекции зависимостей
│   ├── Тестирование BLoC'ов
│   └── Debouncing и Throttling событий
│
├── Обработка состояния
│   ├── Начальное состояние
│   ├── Состояния загрузки
│   ├── Состояния успеха
│   ├── Состояния ошибки
│   ├── Состояния пустоты
│   └── Комбинированные состояния
│
├── Асинхронные операции
│   ├── Future обработка
│   ├── Stream обработка
│   ├── Event transformation (debounce, throttle, etc.)
│   ├── Отмена операций
│   └── Обработка ошибок
│
├── Архитектура с BLoC
│   ├── Clean Architecture слои
│   ├── Repository паттерн
│   ├── Data Sources (Remote, Local)
│   ├── Models и Entities
│   ├── Use Cases
│   └── Dependency Injection (GetIt)
│
├── Интеграция с навигацией
│   ├── Навигация из BLoC
│   ├── Передача данных между экранами
│   ├── Deep Linking с BLoC
│   └── Управление back stack
│
└── Практические паттерны
    ├── Authentication BLoC
    ├── Pagination с BLoC
    ├── Search и фильтрация
    ├── Обработка offline режима
    └── Real-time обновления
```

**Практика:**
- Создание Authentication BLoC
- Реализация Pagination BLoC'а
- Создание комплексного приложения с Clean Architecture и BLoC
- Тестирование BLoC'ов с mockito

#### 2.5 GetX и Другие Подходы (12 часов)
```
├── GetX основы
│   ├── RxController и Obx
│   ├── GetBuilder
│   ├── Reactive переменные (RxInt, RxString, etc)
│   ├── Bindable переменные
│   ├── GetConnect для API
│   └── GetX для навигации
│
├── Сравнение подходов
│   ├── setState vs Provider vs Riverpod vs BLoC vs GetX
│   ├── Когда использовать каждый подход
│   ├── Performance сравнение
│   ├── Кривая обучения
│   └── Боль точки каждого подхода
│
├── Выбор подхода для проекта
│   ├── Простые приложения
│   ├── Средние приложения
│   ├── Enterprise приложения
│   ├── Real-time приложения
│   └── Offline-first приложения
│
└── Миграция между подходами
    ├── От setState к Provider
    ├── От Provider к Riverpod
    ├── От BLoC к Riverpod
    └── Рефакторинг существующего кода
```

**Практика:**
- Сравнение реализации одного приложения на разных подходах
- Выбор оптимального подхода для различных сценариев

---

### 📁 **МОДУЛЬ 3: РАБОТА С СЕТЬЮ И API** (2-3 недели)

#### 3.1 HTTP Запросы (12 часов)
```
├── Пакет http
│   ├── GET запросы
│   ├── POST запросы с данными
│   ├── PUT, PATCH, DELETE запросы
│   ├── Headers и Authentication
│   ├── Query параметры
│   ├── Обработка ошибок
│   ├── Timeout и retry
│   └── Обработка больших файлов
│
├── REST API взаимодействие
│   ├── REST принципы
│   ├── Основные HTTP коды ошибок
│   ├── Обработка 4xx и 5xx ошибок
│   ├── Обработка сетевых ошибок
│   ├── JSON API паттерны
│   └── Версионирование API
│
├── Обработка ответов
│   ├── Парсинг JSON
│   ├── Обработка пустых ответов
│   ├── Обработка массивов
│   ├── Обработка вложенных объектов
│   ├── Обработка ошибок в ответе
│   └── Валидация данных
│
└── Оптимизация запросов
    ├── Кэширование ответов
    ├── Условные запросы (ETag, Last-Modified)
    ├── Pagination
    ├── Фильтрация и сортировка
    └── Compression (GZIP)
```

**Практика:**
- Создание API клиента с http пакетом
- Работа с публичным REST API (JSONPlaceholder, OpenWeather)
- Обработка ошибок и edge cases

#### 3.2 Dio Пакет (14 часов)
```
├── Основы Dio
│   ├── Создание и конфигурация Dio экземпляра
│   ├── GET, POST, PUT, DELETE запросы
│   ├── Общие параметры (baseUrl, headers, timeout)
│   ├── Interceptors и middleware
│   ├── Обработка ошибок
│   └── Retry и exponential backoff
│
├── Продвинутые возможности
│   ├── Загрузка и скачивание файлов
│   ├── Progress tracking для больших файлов
│   ├── Отмена запросов
│   ├── Multipart формы
│   ├── Streaming ответы
│   └── Authentication токены
│
├── Interceptors
│   ├── Логирование interceptor
│   ├── Error handling interceptor
│   ├── Retry interceptor
│   ├── Refresh token interceptor
│   ├── Custom interceptors
│   └── Цепочка interceptors
│
├── Обработка ошибок
│   ├── DioException типы
│   ├── Network errors
│   ├── Timeout errors
│   ├── Response errors
│   ├── Parse errors
│   └── Глобальная обработка
│
├── Кэширование
│   ├── HTTP кэширование
│   ├── Custom кэширование
│   ├── Условное кэширование
│   └── Cache invalidation
│
└── Интеграция с state management
    ├── Dio с Provider
    ├── Dio с Riverpod
    ├── Dio с BLoC
    └── Error handling в state management
```

**Практика:**
- Создание полнофункционального API клиента с Dio
- Реализация токена обновления (token refresh)
- Работа с Progress tracking
- Обработка различных типов ошибок

#### 3.3 JSON и Сериализация (10 часов)
```
├── JSON основы
│   ├── JSON структура и синтаксис
│   ├── JSON парсинг в Dart
│   ├── jsonDecode и jsonEncode
│   ├── Обработка ошибок при парсинге
│   └── Производительность парсинга
│
├── Модели данных
│   ├── Создание классов для JSON
│   ├── FromJson и ToJson методы
│   ├── Обработка nullable полей
│   ├── Обработка nested объектов
│   ├── Обработка массивов
│   └── Обработка enums
│
├── json_serializable пакет
│   ├── Annotations и конфигурация
│   ├── @JsonSerializable, @JsonKey
│   ├── Генерация кода с build_runner
│   ├── Custom JSON ключи
│   ├── Обработка типов
│   ├── Nullable поля в json_serializable
│   └── Наследование и composition
│
├── Freezed пакет
│   ├── Создание immutable моделей
│   ├── Автоматическая генерация кода
│   ├── Union types и pattern matching
│   ├── Copy with и модификация
│   ├── Интеграция с json_serializable
│   └── Обработка ошибок с Either
│
├── Обработка сложных JSON структур
│   ├── Вложенные объекты
│   ├── Динамические поля
│   ├── Полиморфные типы
│   ├── Custom deserializers
│   └── Версионирование моделей
│
└── Производительность и best practices
    ├── Минимизация парсинга
    ├── Потоковый парсинг (streaming JSON)
    ├── Кэширование моделей
    └── Тестирование моделей
```

**Практика:**
- Создание моделей с json_serializable
- Работа с freezed пакетом
- Обработка сложных JSON структур (вложенные, полиморфные)
- Создание расширяемой системы моделей

---

### 📁 **МОДУЛЬ 4: ЛОКАЛЬНОЕ ХРАНИЛИЩЕ ДАННЫХ** (2-3 недели)

#### 4.1 SharedPreferences (6 часов)
```
├── Основы SharedPreferences
│   ├── Когда использовать SharedPreferences
│   ├── Ограничения и возможности
│   ├── Простые типы (String, int, bool, double)
│   ├── Списки строк
│   ├── Асинхронность операций
│   └── Производительность
│
├── Практическое использование
│   ├── Сохранение пользовательских настроек
│   ├── Кэширование данных
│   ├── Сохранение токена аутентификации
│   ├── Сохранение темы приложения
│   ├── Сохранение языка локали
│   └── Сохранение состояния приложения
│
├── Обработка сложных типов
│   ├── Сохранение JSON строк
│   ├── Использование jsonEncode/jsonDecode
│   ├── Сохранение объектов
│   └── Миграция данных при обновлении
│
└── Best practices
    ├── Абстракция доступа (LocalStorage класс)
    ├── Обработка ошибок
    ├── Шифрование чувствительных данных
    └── Интеграция с state management
```

**Практика:**
- Реализация LocalStorage сервиса
- Сохранение и загрузка пользовательских настроек
- Кэширование API данных в SharedPreferences

#### 4.2 SQLite (16 часов)
```
├── Основы SQLite
│   ├── Когда использовать SQLite
│   ├── Реляционные базы данных
│   ├── SQL синтаксис (SELECT, INSERT, UPDATE, DELETE)
│   ├── CREATE TABLE и схема
│   ├── Foreign Keys и связи
│   ├── Индексы
│   └── Query оптимизация
│
├── Пакет sqflite
│   ├── Открытие и закрытие БД
│   ├── Миграции и version контроль
│   ├── Create, Read, Update, Delete операции
│   ├── Raw SQL запросы
│   ├── Транзакции
│   ├── Batch операции
│   └── Асинчность и потокизация
│
├── Работа с данными
│   ├── Маппинг данных в объекты
│   ├── CRUD операции
│   ├── Query фильтрация и сортировка
│   ├── Агрегатные функции (COUNT, SUM, AVG)
│   ├── Joins и связанные таблицы
│   ├── Pagination
│   └── Обработка ошибок
│
├── Миграции и версионирование
│   ├── onCreate и onUpgrade callbacks
│   ├── Миграция схемы при обновлении версии
│   ├── Backups и восстановление
│   ├── Data migration
│   └── Handling database corruption
│
├── Продвинутые техники
│   ├── Triggers и stored procedures
│   ├── Views
│   ├── Full-text search
│   ├── Synchronization с сервером
│   └── Conflict resolution
│
├── Тестирование с SQLite
│   ├── Использование in-memory БД для тестов
│   ├── Мокирование database
│   ├── Тестирование миграций
│   └── Seed данные для тестов
│
└── Интеграция с state management
    ├── Repository паттерн
    ├── Интеграция с Provider
    ├── Интеграция с Riverpod
    ├── Интеграция с BLoC
    └── Real-time обновления с Streams
```

**Практика:**
- Создание полной системы управления базой данных
- Реализация миграций
- CRUD операции с различными таблицами
- Работа с связями между таблицами
- Интеграция SQLite с state management

#### 4.3 Hive (12 часов)
```
├── Основы Hive
│   ├── Когда использовать Hive
│   ├── NoSQL vs SQLite
│   ├── Key-Value хранилище
│   ├── Быстродействие
│   ├── Простота использования
│   └── Платформы поддержки
│
├── Использование Hive
│   ├── Инициализация Hive
│   ├── Открытие и закрытие ящиков (boxes)
│   ├── Сохранение и получение данных
│   ├── Удаление данных
│   ├── Очистка ящика
│   └── Слежение за изменениями (valueListenable)
│
├── Модели и адаптеры
│   ├── Создание Hive моделей (@HiveType)
│   ├── Код генерация с build_runner
│   ├── Custom адаптеры
│   ├── Type IDs и управление версиями
│   └── Миграция данных
│
├── Продвинутые операции
│   ├── Запросы с фильтрацией
│   ├── Сортировка
│   ├── Индексирование для производительности
│   ├── Batch операции
│   ├── Транзакции
│   └── Сжатие данных
│
├── Шифрование
│   ├── Encrypted Hive box
│   ├── Управление ключами шифрования
│   ├── Безопасность данных
│   └── Performance с шифрованием
│
├── Интеграция с UI
│   ├── HiveBuilder для реактивного обновления
│   ├── Stream слежения
│   ├── ValueListenableBuilder
│   └── Integration с state management
│
└── Практические паттерны
    ├── Кэширование API ответов
    ├── Сохранение состояния приложения
    ├── Offline-first архитектура
    ├── Local analytics
    └── Draft сохранение
```

**Практика:**
- Создание хранилища с Hive
- Работа с encrypted boxes
- Реализация offline-first приложения
- Интеграция Hive с state management

#### 4.4 Firebase (14 часов)
```
├── Firebase Setup
│   ├── Создание Firebase проекта
│   ├── Конфигурация Android и iOS
│   ├── Инициализация Firebase в приложении
│   ├── Управление зависимостями
│   └── Обработка ошибок при инициализации
│
├── Firestore
│   ├── Структура Firestore (Collections и Documents)
│   ├── CRUD операции
│   ├── Query фильтрация и сортировка
│   ├── Paginating
│   ├── Real-time слушатели (Snapshots)
│   ├── Offline persistence
│   ├── Transactions
│   ├── Batch writes
│   └── Security Rules
│
├── Realtime Database
│   ├── JSON структура
│   ├── Чтение и запись данных
│   ├── Слушатели значений и изменений
│   ├── Query возможности
│   ├── Offline поддержка
│   ├── Приоритеты и сортировка
│   └── Security Rules
│
├── Authentication
│   ├── Email & Password аутентификация
│   ├── Social логин (Google, Facebook)
│   ├── Phone аутентификация
│   ├── Custom claims и роли
│   ├── Управление пользователем (профиль, email)
│   ├── Обработка ошибок аутентификации
│   └── Выход из аккаунта
│
├── Storage
│   ├── Загрузка файлов
│   ├── Скачивание файлов
│   ├── Progress tracking
│   ├── Удаление файлов
│   ├── Metadata
│   ├── Security Rules
│   └── Оптимизация изображений
│
├── Cloud Functions интеграция
│   ├── Вызов Cloud Functions
│   ├── Обработка ответов
│   ├── Обработка ошибок
│   └── Асинхронные операции
│
├── Analytics и Crashlytics
│   ├── Отслеживание событий
│   ├── Пользовательские события
│   ├── Crash reporting
│   ├── Performance monitoring
│   └── Remote config
│
└── Интеграция с state management
    ├── Firestore с Provider
    ├── Firestore с Riverpod
    ├── Real-time обновления
    ├── Offline sync
    └── Best practices
```

**Практика:**
- Создание приложения с Firebase Firestore
- Реализация аутентификации
- Загрузка и скачивание файлов
- Real-time обновления
- Offline функциональность

---

### 📁 **МОДУЛЬ 5: ПРОДВИНУТЫЙ UI/UX** (2-3 недели)

#### 5.1 Анимации (14 часов)
```
├── Основы анимаций
│   ├── AnimationController и Animation
│   ├── Curve и Easing функции
│   ├── Duration и Delay
│   ├── Repeat и ReverseMode
│   ├── Forward, Reverse, Stop операции
│   └── Жизненный цикл AnimationController
│
├── Тип анимаций
│   ├── Tween анимации (Tween, IntTween, ColorTween)
│   ├── Анимированные виджеты (AnimatedBuilder, AnimatedWidget)
│   ├── Implicit анимации (AnimatedContainer, AnimatedOpacity)
│   ├── Слизистые (Curved анимации)
│   ├── Chained анимации (последовательные)
│   └── Reverse анимации
│
├── Hero анимация
│   ├── Общие элементы между экранами
│   ├── Configuring Hero
│   ├── Custom Hero transitions
│   ├── Обработка ошибок Hero
│   └── Best practices
│
├── Transition анимации
│   ├── PageRouteBuilder
│   ├── Custom page transitions
│   ├── SlideTransition и другие встроенные
│   ├── Shared axis transitions
│   ├── Fade и Scale transitions
│   └── Комбинированные transitions
│
├── Physics симуляция
│   ├── Momentum и inertia
│   ├── Spring анимация
│   ├── Gravity симуляция
│   ├── Collision detection (基础)
│   └── Custom Physics
│
├── Gesture анимации
│   ├── Drag анимация
│   ├── Swipe жесты
│   ├── Fling анимация
│   ├── Parallax эффекты
│   └── Interactive анимации
│
├── Продвинутые техники
│   ├── Rag doll анимация
│   ├── Lottie animations
│   ├── Rive анимации
│   ├── FLARE (Rive) integration
│   └── Производительность анимаций
│
└── Практические примеры
    ├── Splash экран анимация
    ├── Loading анимация
    ├── Карточки с flip анимацией
    ├── List item reveal анимация
    └── Floating Action Button анимация
```

**Практика:**
- Создание различных типов анимаций
- Работа с Lottie и Rive анимациями
- Реализация Hero переходов
- Создание интерактивных анимаций

#### 5.2 Жесты и Интерактивность (10 часов)
```
├── Жесты (Gestures)
│   ├── GestureDetector
│   ├── Tap, Double-tap, Long press
│   ├── Drag и Drag update
│   ├── Scale gesture
│   ├── Rotation gesture
│   ├── Multi-finger gestures
│   ├── Custom gestureDetectors
│   └── Conflict resolution
│
├── Поведение жестов
│   ├── InkWell и Material ripple
│   ├── RawGestureDetector
│   ├── Gesture competition
│   ├── ScrollDirection detection
│   ├── Dismissible для swipe-to-delete
│   └── Reorderable list для drag-and-drop
│
├── Интерактивные компоненты
│   ├── Draggable и DragTarget
│   ├── Drag and drop UI
│   ├── Interactive forms
│   ├── Touchable feedback
│   └── Haptic feedback (вибрация)
│
├── Обработка ввода текста
│   ├── TextEditingController
│   ├── Focus и FocusNode
│   ├── Keyboard типы и actions
│   ├── Input validation
│   ├── Text selection
│   ├── Clipboard operations
│   └── Custom text input
│
└── Accessability (Доступность)
    ├── Semantic виджеты
    ├── Screen reader поддержка
    ├── High contrast modes
    ├── Font scaling
    └── Gesture alternatives для людей с ограничениями
```

**Практика:**
- Создание интерактивного UI с различными жестами
- Реализация drag-and-drop функционала
- Работа с текстовым вводом и валидацией
- Создание accessible приложения

#### 5.3 Кастомные Виджеты (12 часов)
```
├── Создание Custom Widgets
│   ├── Stateless custom widgets
│   ├── Stateful custom widgets
│   ├── Composition vs Inheritance
│   ├── Widget конвенции и best practices
│   ├── Widget скелет и структура
│   └── Документирование виджетов
│
├── RenderObject и Custom Painting
│   ├── CustomPaint и Canvas
│   ├── Drawing примитивы (lines, circles, paths)
│   ├── Painting и текстуры
│   ├── Gradient и шейдеры
│   ├── Text рендеринг
│   ├── Image обработка
│   └── Performance optimization
│
├── Advanced Custom Rendering
│   ├── RenderObject создание
│   ├── Layout и Size constraints
│   ├── Paint и hit testing
│   ├── Custom layout managers
│   ├── Multi-child layouts
│   └── Performance considerations
│
├── Widget Inheritance
│   ├── Наследование от существующих виджетов
│   ├── Переопределение методов
│   ├── Добавление функциональности
│   ├── Сохранение оригинального поведения
│   └── Widget composability
│
├── Theme и Styling Custom Widgets
│   ├── Наследование тем
│   ├── ThemeData использование
│   ├── CustomColors и CustomStyles
│   ├── Dark mode поддержка
│   └── Theme inheritance
│
└── Практические примеры
    ├── Custom rating widget
    ├── Custom chart widget
    ├── Custom calendar widget
    ├── Custom timeline
    └── Custom wave effect
```

**Практика:**
- Создание набора кастомных виджетов
- Рисование с Canvas
- Создание переиспользуемых компонентов
- Работа с RenderObject

#### 5.4 Адаптивный и Responsive Дизайн (10 часов)
```
├── Media Query
│   ├── Размеры экрана
│   ├── Ориентация (Portrait/Landscape)
│   ├── Pixel ratio (DPI)
│   ├── Safe area и notch handling
│   ├── Keyboard высота
│   └── System UI overlay
│
├── Responsive layouts
│   ├── Single column на мобильных
│   ├── Multi-column на планшетах
│   ├── Desktop layouts
│   ├── Breakpoints
│   ├── Гибкий дизайн
│   └── Fluid макеты
│
├── LayoutBuilder и Constraints
│   ├── Адаптивные компоненты
│   ├── Size constraints
│   ├── Context-aware widgets
│   ├── Responsive grid
│   └── Conditional rendering
│
├── OrientationBuilder
│   ├── Обработка ротации экрана
│   ├── Различные layouts для ориентаций
│   ├── Сохранение состояния при ротации
│   ├── Предпочтение ориентации
│   └── Lock/Unlock ориентация
│
├── Platform Detection
│   ├── iOS vs Android UI
│   ├── Platform-specific widgets
│   ├── Material vs Cupertino
│   ├── Кроссплатформенная согласованность
│   └── Platform channel использование
│
├── Доступность (Accessibility)
│   ├── Font scaling
│   ├── High contrast modes
│   ├── Screen readers
│   ├── Touch target размеры
│   └── Semantic widgets
│
└── Практические примеры
    ├── Приложение, работающее на телефонах, планшетах, десктопах
    ├── Адаптивная сетка
    ├── Flexible navigation
    ├── Responsive forms
    └── Multi-platform UI
```

**Практика:**
- Создание адаптивного приложения
- Работа с различными форм-факторами (телефон, планшет)
- Обработка ротации экрана
- Создание доступного интерфейса

---

### 📁 **МОДУЛЬ 6: ИНТЕГРАЦИЯ С НАТИВНЫМ КОДОМ** (2 недели)

#### 6.1 Platform Channels (12 часов)
```
├── Методические каналы
│   ├── MethodChannel для двусторонней коммуникации
│   ├── Вызов нативного кода из Dart
│   ├── Обработка результатов
│   ├── Обработка ошибок (PlatformException)
│   ├── Типизированные данные (String, int, bool, List, Map)
│   └── Timeout обработка
│
├── Event Channels
│   ├── EventChannel для потоков данных
│   ├── Слушание событий из нативного кода
│   ├── Управление подписками
│   ├── Отмена подписок
│   └── Error streams
│
├── Android Native Integration
│   ├── Kotlin (современный подход)
│   ├── Java (legacy)
│   ├── Реализация MethodChannel на Android
│   ├── Context и Activity доступ
│   ├── Жизненный цикл интеграции
│   ├── Асинчность в Android
│   ├── Thread безопасность
│   └── Обработка разрешений
│
├── iOS Native Integration
│   ├── Swift (современный подход)
│   ├── Objective-C (legacy)
│   ├── Реализация MethodChannel на iOS
│   ├── ViewController доступ
│   ├── Async операции
│   ├── Thread безопасность
│   ├── Memory management
│   └── Обработка разрешений
│
├── Bidirectional Communication
│   ├── Dart вызывает Native
│   ├── Native вызывает Dart
│   ├── Обмен данными
│   ├── State синхронизация
│   └── Complex workflows
│
├── Debugging Platform Channels
│   ├── Логирование в Dart
│   ├── Логирование в Native коде
│   ├── Использование Platform Channel инспектора
│   ├── Профилирование
│   └── Отладка Native кода
│
└── Практические примеры
    ├── Получение информации об устройстве
    ├── Вызов нативных диалогов
    ├── Работа с батареей и connectivity
    └── Интеграция с нативным фреймворком
```

**Практика:**
- Создание MethodChannel и EventChannel
- Взаимодействие с нативным кодом
- Обработка результатов и ошибок
- Получение информации об устройстве

#### 6.2 Разрешения и Доступ к функциям (10 часов)
```
├── Permission Handling
│   ├── Android разрешения (Manifest)
│   ├── iOS разрешения (Info.plist)
│   ├── Runtime permissions
│   ├── Пакет permission_handler
│   ├── Проверка разрешений
│   ├── Запрос разрешений
│   ├── Отклоненные разрешения
│   └── Обработка отсутствия разрешений
│
├── Камера и Медиа
│   ├── Camera плагин
│   ├── Захват фото
│   ├── Запись видео
│   ├── Image picker
│   ├── Video player
│   ├── Audio recording
│   ├── Audio playback
│   └── Gallery интеграция
│
├── Локация и GPS
│   ├── Geolocator плагин
│   ├── Получение текущей локации
│   ├── Отслеживание локации
│   ├── Точность и батарея оптимизация
│   ├── Background lokátion tracking
│   └── Обработка ошибок
│
├── Контакты и Календарь
│   ├── Contacts plugin
│   ├── Чтение контактов
│   ├── Создание контактов
│   ├── Calendar integratio
│   ├── Создание событий
│   └── Синхронизация
│
├── Сенсоры (Accelerometer, Gyroscope)
│   ├── Sensor Plus плагин
│   ├── Accelerometer данные
│   ├── Gyroscope данные
│   ├── Magnetometer данные
│   ├── Step counter
│   └── Приложения (игры, шагомер)
│
├── Bluetooth и NFC
│   ├── Bluetooth поиск устройств
│   ├── Bluetooth соединение
│   ├── Обмен данными
│   ├── NFC reading
│   ├── NFC writing
│   └── Mobile payment
│
└── Практические примеры
    ├── Приложение с камерой
    ├── GPS трекер
    ├── QR код сканер
    ├── Bluetooth device controller
    └── Health app с шагомером
```

**Практика:**
- Работа с камерой и фото
- Получение локации
- Доступ к контактам
- Работа с сенсорами

#### 6.3 Файловая система (8 часов)
```
├── Файловые операции
│   ├── path_provider для стандартных директорий
│   ├── DocumentsDirectory, ApplicationDocumentsDirectory
│   ├── TemporaryDirectory, ExternalStorageDirectory
│   ├── Чтение файлов
│   ├── Запись файлов
│   ├── Обновление файлов
│   ├── Удаление файлов
│   └── Обработка ошибок
│
├── Директории и структура
│   ├── Создание директорий
│   ├── Удаление директорий
│   ├── Перемещение файлов
│   ├── Копирование файлов
│   ├── Просмотр файлов в директории
│   └── Path работа
│
├── Большие файлы
│   ├── Streaming файлов
│   ├── Chunk обработка
│   ├── Memory оптимизация
│   ├── Progress tracking
│   └── Cancel операции
│
├── Document picker и File explorer
│   ├── Выбор файлов
│   ├── File picker
│   ├── Document picker
│   └── Обработка результатов
│
└── Platform различия
    ├── Android внешнее хранилище
    ├── iOS sandbox
    ├── File sharing
    └── iCloud sync
```

**Практика:**
- Работа с файловой системой
- Сохранение и загрузка документов
- Работа с большими файлами
- Интеграция с файловым менеджером

---

### 📁 **МОДУЛЬ 7: ТЕСТИРОВАНИЕ** (1-2 недели)

#### 7.1 Unit Тесты (10 часов)
```
├── Основы Unit Тестирования
│   ├── test пакет и структура
│   ├── test(), expect(), group()
│   ├── Test сутки и лучшие практики
│   ├── AAA паттерн (Arrange, Act, Assert)
│   ├── Naming convention для тестов
│   └── Test организация
│
├── Тестирование функций
│   ├── Простые функции
│   ├── Функции с параметрами
│   ├── Функции с исключениями
│   ├── Async функции
│   ├── Функции с побочными эффектами
│   └── Test cases и edge cases
│
├── Мокирование
│   ├── mockito пакет
│   ├── Creating mocks
│   ├── Установка expectations
│   ├── Verification
│   ├── Returning values
│   ├── Throwing exceptions
│   ├── Fake vs Mock
│   └── ArgumentMatchers
│
├── Тестирование Dart классов
│   ├── Тестирование логики класса
│   ├── Тестирование getters/setters
│   ├── Тестирование конструкторов
│   ├── Тестирование наследования
│   └── Тестирование миксинов
│
├── Coverage и качество
│   ├── Code coverage measurement
│   ├── Lcov и покрытие отчеты
│   ├── Target coverage %
│   ├── Testing best practices
│   └── Continuous Integration
│
└── Практические примеры
    ├── Тестирование валидаторов
    ├── Тестирование converters
    ├── Тестирование business logic
    └── Тестирование utilities
```

**Практика:**
- Написание комплексных unit тестов
- Использование mockito для мокирования
- Достижение хорошего покрытия (>80%)
- Тестирование async код

#### 7.2 Widget Тесты (12 часов)
```
├── Основы Widget Тестирования
│   ├── testWidgets() функция
│   ├── WidgetTester и методы
│   ├── pump() и pumpWidget()
│   ├── find() и Finder
│   ├── expect() для виджетов
│   └── Test окружение
│
├── Взаимодействие с UI
│   ├── tap() - нажатие кнопок
│   ├── enterText() - ввод текста
│   ├── drag() - перетаскивание
│   ├── pageBack() - навигация
│   ├── openDrawer() - открытие drawer
│   └── Other interactions
│
├── Проверка UI состояния
│   ├── Текст проверки
│   ├── Виджет наличие
│   ├── Свойства виджета
│   ├── Tree структура
│   ├── Size и position
│   └── Rendered output
│
├── Работа с Async UI
│   ├── FutureBuilder тестирование
│   ├── StreamBuilder тестирование
│   ├── pumpAndSettle()
│   ├── Async операции
│   └── Loading states
│
├── State Management Тестирование
│   ├── Testing Provider
│   ├── Testing Riverpod
│   ├── Testing BLoC
│   ├── Мокирование providers
│   └── Testing state transitions
│
├── Golden Tests
│   ├── Screenshot сравнение
│   ├── Visual regression testing
│   ├── UpdateGoldenFiles
│   ├── CI/CD integration
│   └── Multi-platform golden tests
│
├── Performance Тестирование
│   ├── Velocity мониторинг
│   ├── Frame rate проверка
│   ├── Rendering performance
│   └── Memory usage
│
└── Практические примеры
    ├── Тестирование форм
    ├── Тестирование навигации
    ├── Тестирование списков
    ├── Тестирование диалогов
    └── Тестирование анимаций
```

**Практика:**
- Написание widget тестов для различных компонентов
- Взаимодействие с UI в тестах
- Golden tests для визуальной регрессии
- Тестирование state management

#### 7.3 Integration Тесты (10 часов)
```
├── Основы Integration Тестирования
│   ├── integration_test пакет
│   ├── Сетап и конфигурация
│   ├── testWidgets() для integration
│   ├── WidgetTester методы
│   ├── Полное приложение тестирование
│   └── Real device vs emulator
│
├── Сценарии использования (User flows)
│   ├── Простой flow (login -> home)
│   ├── Сложный flow (multi-step)
│   ├── Error scenarios
│   ├── Edge cases
│   └── Network scenarios
│
├── Данные для тестирования
│   ├── Mocking backend API
│   ├── Fake server responses
│   ├── Test data seeds
│   ├── Fixtures и factories
│   └── Data cleanup
│
├── Device Testing
│   ├── Тестирование на эмуляторе
│   ├── Тестирование на физическом устройстве
│   ├── Разные размеры экрана
│   ├── Разные ОС версии
│   └── Locale и language testing
│
├── Performance и Stability
│   ├── Long-running tests
│   ├── Memory leaks
│   ├── Crash testing
│   ├── Network interruption
│   └── Device orientation change
│
├── CI/CD Integration
│   ├── GitHub Actions
│   ├── Firebase Test Lab
│   ├── Automated testing
│   ├── Test reports
│   └── Artifact сохранение
│
└── Практические примеры
    ├── E-commerce checkout flow
    ├── Authentication flow
    ├── Data sync flow
    ├── Offline mode testing
    └── Multi-screen navigation
```

**Практика:**
- Написание integration тестов для полных user flows
- Мокирование backend в integration тестах
- Тестирование на различных устройствах
- Настройка CI/CD для integration тестов

---

### 📁 **МОДУЛЬ 8: ПРАКТИЧЕСКИЕ ПРОЕКТЫ** (5-6 недель)

#### Проект 1: Приложение Погоды (Базовый уровень - 1 неделя)
```
Цель: Освоить основные концепции Flutter

Функционал:
├── Текущая погода в выбранном городе
├── Поиск города
├── 5-дневный прогноз
├── Иконки погоды и информация
├── LocalStorage для сохранения города
├── Простой UI с Material Design
├── Error handling для API запросов
└── Refresh функциональность

Tech Stack:
├── Flutter UI (Column, ListView, Card)
├── HTTP запросы (OpenWeather API)
├── SharedPreferences
├── setState для управления состоянием
├── JSON парсинг
└── Error handling

Обучаемые навыки:
├── REST API взаимодействие
├── JSON парсинг
├── LocalStorage
├── UI компоновка
├── Error handling
└── Асинхронное программирование
```

**Требования к проекту:**
- ✅ Рабочее приложение без крахов
- ✅ Правильное отображение погоды
- ✅ Сохранение выбранного города
- ✅ Минимум 80% code coverage для бизнес логики
- ✅ Документация (README с инструкциями)

#### Проект 2: Todo Приложение (Промежуточный уровень - 1.5 недели)
```
Цель: Овладеть state management и локальной БД

Функционал:
├── Создание/редактирование/удаление задач
├── Категории для задач
├── Приоритеты
├── Due dates
├── Фильтрация и сортировка
├── Поиск по задачам
├── Архивирование
├── Напоминания (basic)
├── Экспорт/импорт (JSON)
├── Темная тема
├── Gesture actions (swipe to delete, etc)
└── Анимированный UI

Tech Stack:
├── Riverpod для state management
├── SQLite для сложного хранилища
├── GoRouter для навигации
├── Freezed для моделей
├── json_serializable
├── flutter_riverpod + riverpod_generator
├── Animations
└── Testing

Обучаемые навыки:
├── Riverpod и state management
├── SQLite операции
├── Complex filtering/sorting
├── Animations
├── Навигация
├── Тестирование
└── Architecture паттерны
```

**Требования к проекту:**
- ✅ Все CRUD операции работают
- ✅ Фильтрация и поиск функциональны
- ✅ Плавная навигация и анимации
- ✅ Unit + Widget тесты (>70% coverage)
- ✅ Профессиональный UI/UX
- ✅ Полная документация
- ✅ Code следует clean architecture

#### Проект 3: E-Commerce Приложение (Продвинутый уровень - 2 недели)
```
Цель: Создать production-ready приложение с полной архитектурой

Функционал:
├── Просмотр каталога товаров
├── Поиск и фильтрация
├── Детали товара
├── Рейтинги и отзывы
├── Корзина покупок
├── Wishlist
├── Checkout процесс
├── Разные методы платежа
├── Заказы и история
├── Профиль пользователя
├── Адреса доставки
├── Push уведомления
├── In-app сообщения
├── Dark/Light тема
├── Мультиязычность (i18n)
├── Adapterive layout (phone/tablet)
└── Offline функциональность

Tech Stack:
├── Clean Architecture
├── BLoC + stream_transform для state management
├── Dio для API
├── Hive + SQLite
├── Firebase (Auth, Firestore, Storage)
├── GoRouter
├── Freezed + json_serializable
├── GetIt для DI
├── Unit + Widget + Integration тесты
├── Localization
├── Error handling и logging
└── Performance optimization

Обучаемые навыки:
├── Clean Architecture
├── BLoC паттерны
├── Complex state management
├── Firebase интеграция
├── Payment integration
├── Notifications
├── Localization
├── Performance optimization
├── Testing всех уровней
└── Deployment preparation
```

**Требования к проекту:**
- ✅ Production-ready код качество
- ✅ Clean Architecture соблюдена
- ✅ >80% test coverage
- ✅ Performance оптимизирован
- ✅ Полная документация
- ✅ GitHub с историей коммитов
- ✅ Могло бы быть выпущено в App Store/Play Store

#### Проект 4: Социальная Сеть (Комплексный уровень - 2-3 недели)
```
Цель: Создать полноценное социальное приложение

Функционал:
├── Аутентификация (Email, Google, Apple)
├── Профили пользователей
├── Создание постов (текст, фото, видео)
├── Лайки и комментарии
├── Следование/Unfollowing
├── Лента друзей (Feed)
├── Поиск пользователей
├── Private чаты (Real-time)
├── Груп чаты
├── Уведомления (Real-time)
├── Хэштеги
├── Сохранение постов
├── Управление блокировками
├── Двухфакторная аутентификация
├── Темы и персонализация
├── Мултиязычность
├── Адаптивный дизайн
├── Offline sync
└── Аналитика

Tech Stack:
├── Clean Architecture + MVVM
├── Riverpod + flutter_riverpod_generator
├── Firebase (Auth, Firestore, Storage, Messaging)
├── WebSockets для real-time чата
├── Hive + SQLite для локальной синхронизации
├── Image + Video обработка
├── GetIt для DI
├── GoRouter
├── Freezed + json_serializable
├── flutter_hooks
├── Comprehensive testing
├── CI/CD pipeline
├── Sentry для error tracking
├── Firebase Analytics
└── Proper logging

Обучаемые навыки:
├── Real-time базы данных
├── WebSocket коммуникация
├── Image/Video обработка
├── Complex architecture
├── Deep Linking
├── Push уведомления
├── User analytics
├── Error tracking
├── Scalable design
├── DevOps для Flutter
└── Production deployment
```

**Требования к проекту:**
- ✅ Enterprise-level кода
- ✅ Масштабируемая архитектура
- ✅ >85% test coverage
- ✅ Performance оптимизирован для роста
- ✅ Полная документация + API docs
- ✅ GitHub с профессиональной историей
- ✅ Готово для трудоустройства в portfolio
- ✅ Может быть выпущено на обе платформы

---

### 📁 **МОДУЛЬ 9: РАЗВЕРТЫВАНИЕ И ПУБЛИКАЦИЯ** (1-2 недели)

#### 9.1 iOS Развертывание (10 часов)
```
├── Подготовка к выпуску
│   ├── App Signing Certificates
│   ├── Provisioning Profiles
│   ├── App Identifiers
│   ├── Capabilities (Push, iCloud, etc)
│   ├── Version и Build number
│   └── Info.plist конфигурация
│
├── TestFlight
│   ├── Internal testing
│   ├── External testing
│   ├── Beta тестирование
│   ├── Feedback от тестеров
│   ├── Builds management
│   └── Regulations соблюдение
│
├── App Store Connect
│   ├── App creation
│   ├── App metadata (описание, скриншоты, иконки)
│   ├── Pricing и распределение
│   ├── Рейтинг контента
│   ├── Privacy policy и terms
│   └── App review гайдлайны
│
├── Подпись и Сертификаты
│   ├── Code signing процесс
│   ├── Certificates management
│   ├── Creating P12 files
│   ├── Fastlane для automation
│   └── CI/CD интеграция
│
├──審査 и Approval
│   ├── App Store Review процесс
│   ├── Частые причины отклонения
│   ├── Как ответить на rejection
│   ├── Appeal процесс
│   └── Лучшие практики для approval
│
├── Post-Release
│   ├── Monitoring crashes
│   ├── User reviews и ratings
│   ├── Analytics
│   ├── Updates и patches
│   └── Версионирование
│
└── Инструменты
    ├── Xcode
    ├── Apple App Store Connect
    ├── Fastlane
    ├── Firebase Console
    └── Third-party tools
```

**Практика:**
- Создание сертификатов подписи
- Конфигурирование provisioning profiles
- Загрузка на TestFlight
- Подготовка к App Store review
- Публикация на App Store

#### 9.2 Android Развертывание (10 часов)
```
├── Подготовка к выпуску
│   ├── Обновление версии
│   ├── Release build варианты
│   ├── ProGuard/R8 обфускация
│   ├── Resource shrinking
│   ├── Signing configuration
│   └── gradle конфигурация
│
├── Подпись APK/AAB
│   ├── Creating keystore
│   ├── Signing APK
│   ├── App Bundle (AAB) формат
│   ├── Signing configuration
│   ├── Key management
│   └── Fastlane для automation
│
├── Google Play Console
│   ├── Create app в Play Console
│   ├── App signing by Google
│   ├── App metadata (описание, скриншоты, иконки)
│   ├── Targeting и категория
│   ├── Rating контент
│   ├── Privacy policy
│   └── Pricing и распределение
│
├── Internal Testing Track
│   ├── Internal testing setup
│   ├── Добавление тестеров
│   ├── Build uploads
│   ├── Feedback процесс
│   └── Rollout стратегия
│
├── Beta и Production Tracks
│   ├── Closed beta (limited users)
│   ├── Open beta (wider audience)
│   ├── Staged rollout
│   ├── Full production release
│   ├── Monitoring по rollout
│   └── Quick rollback если проблемы
│
├── Play Store Review
│   ├── Google Play Review гайдлайны
│   ├── Частые причины отклонения
│   ├── Permissions и данные приватность
│   ├── Targeting контроль
│   └── Lучшие практики
│
├── Post-Release
│   ├── Crash monitoring (Firebase)
│   ├── User ratings и reviews
│   ├── ANR (App Not Responding) обработка
│   ├── Updates и patches
│   ├── Version management
│   └── Analytics мониторинг
│
└── Инструменты
    ├── Android Studio
    ├── Google Play Console
    ├── Fastlane
    ├── Firebase Console
    ├── Crashlytics
    └── Google Analytics
```

**Практика:**
- Создание keystore для подписи
- Сборка Release build
- Upload AAB в Play Console
- Condsideation testing
- Публикация на Google Play

#### 9.3 Advanced Deployment Topics (6 часов)
```
├── CI/CD для Flutter
│   ├── GitHub Actions workflow
│   ├── GitLab CI/CD
│   ├── Automated testing в CI
│   ├── Automated building
│   ├── Automated deployment
│   ├── Fastlane интеграция
│   ├── Secret management
│   └── Artifact management
│
├── Версионирование и Updates
│   ├── Semantic versioning
│   ├── Beta версии
│   ├── Hotfixes
│   ├── Rollback стратегия
│   ├── Staged rollout
│   ├── Feature flags
│   ├── Remote config
│   └── In-app updates (Android)
│
├── Мониторинг и Analytics
│   ├── Firebase Crashlytics
│   ├── Sentry
│   ├── Firebase Analytics
│   ├── Performance monitoring
│   ├── User behavior analytics
│   ├── Custom events
│   ├── Funnel анализ
│   └── A/B testing
│
├── Безопасность и Privacy
│   ├── SSL pinning
│   ├── Encryption
│   ├── Secure storage (Keystore, Keychain)
│   ├── GDPR compliance
│   ├── Permission best practices
│   ├── Data handling
│   ├── Secure API communication
│   └── Vulnerability scanning
│
├── Performance в Production
│   ├── Profiling на реальных устройствах
│   ├── Memory leaks detection
│   ├── Crash analytics
│   ├── Performance monitoring
│   ├── Optimization на основе data
│   ├── Heat maps
│   └── Benchmarking
│
└── Distribution Channels
    ├── App Store (Apple)
    ├── Google Play (Android)
    ├── Sideloading APK
    ├── Enterprise distribution
    ├── Windows/Web deployment
    └── Custom stores
```

**Практика:**
- Настройка GitHub Actions workflow
- Автоматизация тестирования и сборки
- Настройка Firebase Crashlytics
- Настройка Analytics
- Feature flags с Firebase Remote Config

---

## 📦 Дополнительные Ресурсы

### 🎁 Включено в Курс

```
📚 Лекции
├── 300+ видеолекций (50+ часов)
├── Записанные сессии
├── Screen-share примеры
├── Live coding sessions
└── Q&A сессии

📝 Материалы
├── Полные конспекты лекций
├── Шпаргалки по Dart и Flutter
├── API документация
├── Примеры кода (GitHub репо)
├── Диаграммы и схемы
└── Чеклисты

🧑‍💻 Проекты
├── 4 полных проекта (код + видео)
├── Проектные шаблоны
├── Best practices примеры
├── CI/CD конфигурации
└── Deployment гайды

🧪 Тесты и Задания
├── 50+ практических задач
├── Unit тесты для примеров
├── Widget тесты для UI
├── Integration тесты для flows
├── Code reviews и feedback
└── Автоматическая проверка

🛠️ Инструменты и Шаблоны
├── Flutter project templates
├── Boilerplate код
├── VS Code extensions recommendations
├── IDE configuration files
├── DevTools настройка
└── Pre-commit hooks

💬 Сообщество
├── Discord канал курса
├── Форум обсуждения
├── Еженедельные Q&A сессии
├── Peer code reviews
├── Помощь TA
└── Job board

📜 Сертификация
├── Курсовой сертификат
├── Portfolio разработка
├── GitHub achievements
└── LinkedIn рекомендации
```

### 🔗 Внешние Ресурсы

```
Официальная Документация
├── Flutter Docs: https://flutter.dev
├── Dart Documentation: https://dart.dev
├── Firebase: https://firebase.google.com/docs
└── Material Design: https://m3.material.io

Обучающие Платформы
├── DartPad (онлайн редактор): https://dartpad.dev
├── Flutter Studio: https://flutter.dartlang.org/learning/web
├── Riverpod Documentation: https://riverpod.dev
└── Bloc Library: https://bloclibrary.dev

Инструменты
├── VS Code: https://code.visualstudio.com
├── Android Studio: https://developer.android.com/studio
├── Xcode: https://developer.apple.com/xcode
├── DevTools: https://flutter.dev/docs/development/tools/devtools
└── GitHub: https://github.com

Пакеты и Библиотеки
├── Pub.dev (пакеты): https://pub.dev
├── Awesome Flutter: https://github.com/Solido/awesome-flutter
└── Flutter Packages (категории): https://pub.dev/packages
```

---

## 📊 Требования

### Минимальные системные требования

| Параметр | Требование |
|----------|-----------|
| **ОС** | Windows 7+, macOS 10.11+, Linux (Ubuntu 14.04+) |
| **RAM** | 4 GB (рекомендуется 8 GB) |
| **Диск** | 6 GB для Flutter + Android SDK, 2 GB для iOS SDK |
| **Flutter** | 3.0+ |
| **Dart** | 3.0+ (включен в Flutter) |
| **Java** | JDK 11+ (для Android) |
| **Xcode** | 12.0+ (для iOS, только macOS) |

### Рекомендуемое оборудование

- **Процессор**: Intel i5/i7 или AMD Ryzen 5/7 (4+ ядер)
- **RAM**: 16 GB
- **SSD**: 256+ GB
- **GPU**: Дискретная видеокарта (опционально, но полезна для эмуляторов)

### IDE и Редакторы

- **VS Code** (рекомендуется для новичков)
  - Extensions: Flutter, Dart, Awesome Flutter, Better Comments
  
- **Android Studio** (рекомендуется для разработки Android)
  - Все плагины включены по умолчанию
  
- **IntelliJ IDEA** (платная, полная функциональность)

---

## 🎯 Карта Обучения по Неделям

```
НЕДЕЛЯ 1-2: Основы (Модуль 0)
├── День 1-2: Установка и первое приложение
├── День 3-5: Основы Dart (переменные, функции)
├── День 6-7: Dart ООП и асинхронность
├── Практика: Создать калькулятор

НЕДЕЛЯ 3-5: UI Основы (Модуль 1.1-1.2)
├── День 1-3: Встроенные виджеты
├── День 4-6: Layout и компоновка
├── День 7: Проект: Pinterest-подобный layout
├── Практика: Различные UI компоненты

НЕДЕЛЯ 6-7: Навигация и Стили (Модуль 1.3-1.4)
├── День 1-3: Навигация (Navigator, GoRouter)
├── День 4-7: Темы и стили
├── Практика: Мультиэкранное приложение

НЕДЕЛЯ 8-11: State Management (Модуль 2)
├── Неделя 8: setState и основы
├── Неделя 9: Provider
├── Неделя 10: Riverpod или BLoC (выбирайте один)
├── Неделя 11: Integrating everything
├── Проект: Todo приложение

НЕДЕЛЯ 12-13: API и Сеть (Модуль 3)
├── День 1-4: HTTP и REST API
├── День 5-10: Dio и advanced запросы
├── День 11-14: JSON парсинг
├── Проект: Приложение погоды

НЕДЕЛЯ 14-15: Данные (Модуль 4)
├── День 1-2: SharedPreferences
├── День 3-8: SQLite
├── День 9-14: Hive или Firebase
├── Практика: Комбинация всех хранилищ

НЕДЕЛЯ 16-17: Advanced UI (Модуль 5)
├── День 1-4: Анимации
├── День 5-7: Жесты
├── День 8-10: Кастомные виджеты
├── День 11-14: Адаптивный дизайн

НЕДЕЛЯ 18-19: Нативная Интеграция (Модуль 6)
├── День 1-4: Platform channels
├── День 5-7: Разрешения и функции
├── День 8-14: Практические интеграции
├── Проект: Приложение с камерой

НЕДЕЛЯ 20: Тестирование (Модуль 7)
├── День 1-3: Unit тесты
├── День 4-7: Widget тесты
├── День 8-10: Integration тесты
├── День 11-14: Практика тестирования

НЕДЕЛЯ 21-27: Проекты (Модуль 8)
├── Неделя 21-22: Проект 1 (Погода)
├── Неделя 23-24: Проект 2 (Todo)
├── Неделя 25-27: Проект 3 (E-Commerce) ИЛИ
├── Неделя 25-30: Проект 4 (Социальная сеть)

НЕДЕЛЯ 28-30: Развертывание (Модуль 9)
├── День 1-5: iOS развертывание
├── День 6-10: Android развертывание
├── День 11-15: CI/CD и автоматизация
├── Финал: Публикация на обе платформы
```

**Итого: 30 недель (~7-8 месяцев интенсивного обучения)**

---

---

**Последнее обновление:** Январь 2026  
**Версия:** 1.0  
**Поддерживается на:** Flutter 3.0+, Dart 3.0+
