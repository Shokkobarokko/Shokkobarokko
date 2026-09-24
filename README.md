# Hi, I'm Avetis 👋

**iOS Developer** · building mobile apps with Swift

I’m focused on becoming a strong iOS engineer through hands-on projects, system design, algorithms, and deep understanding of Swift and UIKit.

---

## 🛠 Tech Stack

**Languages**

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square\&logo=swift\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square\&logo=csharp\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)

**iOS & UI**

![UIKit](https://img.shields.io/badge/UIKit-2C2C2E?style=flat-square\&logo=apple\&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D6EFD?style=flat-square\&logo=swift\&logoColor=white)

**Architecture & Development**

![MVVM](https://img.shields.io/badge/MVVM-181717?style=flat-square)
![async/await](https://img.shields.io/badge/async%2Fawait-F05138?style=flat-square\&logo=swift\&logoColor=white)
![Codable](https://img.shields.io/badge/Codable-181717?style=flat-square)
![URLSession](https://img.shields.io/badge/URLSession-181717?style=flat-square)

**Tools**

![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square\&logo=xcode\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![CocoaPods](https://img.shields.io/badge/CocoaPods-EE3322?style=flat-square\&logo=cocoapods\&logoColor=white)
![SPM](https://img.shields.io/badge/SPM-F05138?style=flat-square\&logo=swift\&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square\&logo=figma\&logoColor=white)

**Data & Persistence**

![SwiftData](https://img.shields.io/badge/SwiftData-2C2C2E?style=flat-square\&logo=apple\&logoColor=white)
![CoreData](https://img.shields.io/badge/CoreData-2C2C2E?style=flat-square\&logo=apple\&logoColor=white)
![Realm](https://img.shields.io/badge/Realm-39477F?style=flat-square\&logo=realm\&logoColor=white)

---

# 📱 Projects

## 🔧 Project 1 · Trackly

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square\&logo=apple)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square\&logo=swift)
![UIKit](https://img.shields.io/badge/UIKit-2C2C2E?style=flat-square\&logo=apple)

> **Trackly** — habit and activity tracking app built as a long-term iOS engineering project.

The project is focused not only on building features, but also on understanding how a real iOS application is structured, tested, persisted, and evolved.

### 🎯 Current Features

* Habit creation
* Habit editing
* Habit deletion
* Input validation
* Habit list with `UITableView`
* Persistent storage
* Stable habit identifiers
* Creation dates
* MVVM structure
* ViewModel → UI callbacks
* JSON encoding/decoding with `Codable`

### 🧠 Engineering Focus

Trackly is being developed step by step with focus on:

* Swift fundamentals
* Value vs reference semantics
* Protocols and extensions
* Optionals and error handling
* Closures and capture lists
* UIKit lifecycle
* `UITableView` and delegates
* Auto Layout
* MVVM
* Persistence
* Networking
* `async/await`
* Repository and Service layers
* Dependency Injection
* Unit and UI testing
* Data structures and algorithmic complexity
* Debugging and performance

### 🏗 Architecture

Current architecture:

```text
ViewController
      ↓
   ViewModel
      ↓
   Storage
      ↓
 UserDefaults
```

Planned evolution:

```text
ViewController
      ↓
   ViewModel
      ↓
   Repository
      ↓
 ┌───────────────┐
 │               │
NetworkService  LocalStorage
 │               │
URLSession     Persistence
```

### 📚 Engineering Decisions

The project is intentionally evolving from a simple implementation toward a more production-like architecture.

Some of the decisions explored during development:

* Why use MVVM?
* Why keep persistence outside the ViewController?
* Why use stable `UUID` identifiers?
* When is `UserDefaults` appropriate?
* When should persistence move to a database?
* When does a Repository layer become useful?
* When should Dependency Injection be introduced?
* How should networking and local storage be tested?

### 🚧 Roadmap

* 🔧 Habit completion tracking
* 🔧 Completion history
* 🔧 Better persistence layer
* 🔧 Repository architecture
* 🔧 Networking with `URLSession`
* 🔧 `async/await`
* 🔧 Loading / error / success states
* 🔧 Unit tests
* 🔧 UI tests
* 🔧 Dependency Injection
* 🔧 Performance improvements
* 🔧 Final documentation

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square\&logo=github\&logoColor=white)](PASTE_TRACKLY_REPOSITORY_URL_HERE)

---

## 🔧 Project 2 · SIGNAL

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square\&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.10-F05138?style=flat-square\&logo=swift)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D6EFD?style=flat-square\&logo=swift)

> **SIGNAL** — футуристичная новостная лента о технологиях в эстетике «improbable future». Чёрно-белый минимализм, тонкие линии, крупная типографика, редкие холодные акценты.

### 🎯 Концепция

Приложение загружает технологические новости из **NewsAPI.org**. Пользователь видит ленту с категориями Technology, AI, Space, Crypto и Science, может искать статьи, сохранять их в избранное и читать полностью.

### 🧠 Ключевые механики

* Лента новостей с пагинацией
* Pull-to-refresh
* Категории
* Полнотекстовый поиск
* Debounce поиска
* Офлайн-кэш последних статей
* Избранное
* Детальный экран
* WebKit / Safari
* WidgetKit
* Настройки приложения

### 🛠 Tech Stack

* **Swift 5.10+**
* **SwiftUI**
* **MVVM**
* **`@Observable`**
* **async/await**
* **URLSession**
* **SwiftData**
* **WidgetKit**
* **App Groups**
* iOS 17+
* Xcode 15+

### 🎨 Design System — "Improbable Future"

* Почти чёрный фон
* Минималистичные карточки
* Тёмно-синий акцент
* Тонкая типографика
* Моноширинные метки
* Нумерация новостей: `001`, `002`, `003`
* Теги категорий: `[ TECHNOLOGY ]`, `[ AI ]`
* Временные метки: `2026.06.11 / 14:32`

### 📱 Status

Implemented:

* ✅ Project setup
* ✅ Design system
* ✅ SwiftData container
* ✅ Network service
* ✅ Offline caching
* ✅ Feed
* ✅ Categories
* ✅ Article cards
* ✅ Detail screen
* ✅ Search with debounce
* ✅ Bookmarks
* ✅ Settings

In progress:

* 🔧 WidgetKit
* 🔧 Animations
* 🔧 Error handling
* 🔧 Final testing
* 🔧 README improvements

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Shokkobarokko/SIGNAL)

---

## 🔧 Project 3 · Capybara

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square\&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square\&logo=swift)
![UIKit](https://img.shields.io/badge/UIKit-code%20only-2C2C2E?style=flat-square\&logo=apple)

> **Capybara** — фокус-компаньон с виртуальной капибарой, который помогает бороться с телефонной зависимостью через игровую механику и социальную поддержку.

### 🎯 Концепция

Пользователь выбирает приложения, которые хочет ограничить, и устанавливает дневной лимит.

Если лимит превышен — здоровье виртуальной капибары падает. Чтобы восстановить питомца, пользователь может отправить запрос другу.

### 🧠 Ключевые механики

* Screen Time API
* `FamilyControls`
* `DeviceActivity`
* `ManagedSettings`
* Мониторинг использования
* Ограничение приложений
* Виртуальный питомец
* Глубокие ссылки
* История использования
* Графики
* Локальные уведомления
* Widget

### 🛠 Tech Stack

* **Swift**
* **UIKit**
* MVVM
* Delegates / Closures
* UserDefaults
* Codable
* UINavigationController
* UITabBarController
* Apple SDK
* iOS 16.4+

### 📱 Status

Implemented:

* ✅ Screen Time authorization
* ✅ App selection
* ✅ App blocking
* ✅ Usage monitoring
* ✅ Health system
* ✅ Capybara screen
* ✅ Deep links

In progress:

* 🔧 Statistics
* 🔧 Charts
* 🔧 Profile
* 🔧 Settings
* 🔧 Widget
* 🔧 Notifications

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Shokkobarokko/Capybara)

---

## 🔧 Project 4 · ButtonBook

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square\&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square\&logo=swift)
![UIKit](https://img.shields.io/badge/UIKit-2C2C2E?style=flat-square\&logo=apple)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D6EFD?style=flat-square\&logo=swift)

> **ButtonBook** — публичный дневник изучения кнопок на iOS.

40 кнопок от простых до сложных анимированных: 20 на UIKit и 20 на SwiftUI.

Каждая кнопка живёт в отдельном файле и сопровождается объяснением реализации.

### 📋 UIKit

`Plain` · `Filled` · `Outlined` · `Tinted` · `Gradient` · `Shadow` · `Icon+Text` · `Destructive` · `Scale Press` · `Bounce Press` · `Haptic` · `Highlight Ripple` · `Loading State` · `Countdown` · `Toggle` · `Pill Progress` · `Morphing` · `Glitch` · `Liquid Fill` · `Particles Burst`

### 📋 SwiftUI

`Plain` · `Filled` · `Outlined` · `ScalePress` · `SpringBounce` · `Shimmer` · `GlowPulse` · `Icon Animated` · `RotatingBorder` · `LoadingDots` · `Toggle Checkmark` · `MatchedGeometry` · `Ripple Tap` · `Countdown` · `PillProgress` · `Morphing Shape` · `Liquid Wave` · `3D Flip` · `Particle Burst` · `Metal Shader`

### 🛠 Tech Stack

* Swift
* UIKit
* SwiftUI
* Auto Layout
* ButtonStyle
* Canvas
* Metal
* Apple SDK

### 📱 Status

* ✅ Project structure
* 🔧 UIKit: 0/20
* 🔧 SwiftUI: 0/20

Each new button → separate commit + README explanation.

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Shokkobarokko/ButtonBook)

---

# 🎓 Teaching

Beyond mobile development, I teach programming to kids and teenagers.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![HTML](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![Scratch](https://img.shields.io/badge/Scratch-4D97FF?style=flat-square\&logo=scratch\&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square\&logo=unity\&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox%20Studio-E2231A?style=flat-square\&logo=roblox\&logoColor=white)

I believe that the earlier kids start thinking algorithmically, the better — so I make programming fun and practical.

---

# ⚔️ Coding Practice

I solve algorithmic challenges to improve my problem-solving skills and write better Swift code.

| Platform     | Progress                               |
| ------------ | -------------------------------------- |
| **CodeWars** | 7 kyu · 75+ kata solved                |
| **LeetCode** | 0+ problems solved · 30 days streak 🔥 |

<p align="left">
  <a href="https://www.codewars.com/users/Shokkobarokko">
    <img src="https://www.codewars.com/users/Shokkobarokko/badges/large" />
  </a>
</p>

*"Clean code, one kata at a time."*

---

# 📊 GitHub Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Shokkobarokko&show_icons=true&theme=dark&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shokkobarokko&layout=compact&theme=dark&hide_border=true" />
</p>

<p align="left">
  <img src="https://streak-stats.demolab.com?user=Shokkobarokko&theme=dark&hide_border=true" />
</p>

---

# 📬 Contact

[![Telegram](https://img.shields.io/badge/@Shokkobarokko-2CA5E0?style=flat-square\&logo=telegram\&logoColor=white)](https://t.me/Shokkobarokko)
