# Hi, I'm Avetis 👋

**iOS Developer** · crafting mobile experiences with Swift

---

## 🛠 Tech Stack

**Languages**

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Frameworks & UI**

![SwiftUI](https://img.shields.io/badge/SwiftUI-0D6EFD?style=flat-square&logo=swift&logoColor=white)
![UIKit](https://img.shields.io/badge/UIKit-2C2C2E?style=flat-square&logo=apple&logoColor=white)

**Tools**

![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CocoaPods](https://img.shields.io/badge/CocoaPods-EE3322?style=flat-square&logo=cocoapods&logoColor=white)
![SPM](https://img.shields.io/badge/SPM-F05138?style=flat-square&logo=swift&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

**Databases**

![CoreData](https://img.shields.io/badge/CoreData-2C2C2E?style=flat-square&logo=apple&logoColor=white)
![Realm](https://img.shields.io/badge/Realm-39477F?style=flat-square&logo=realm&logoColor=white)

---

## 📱 Projects

> Currently working on two iOS apps. Details coming soon.

### 🔧 Project 1 · Bara

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square&logo=swift)
![UIKit](https://img.shields.io/badge/UIKit-code%20only-2C2C2E?style=flat-square&logo=apple)

> **Bara** — фокус-компаньон с виртуальной капибарой. Помогает бороться с телефонной зависимостью через игровую механику и социальную поддержку.

#### 🎯 Концепция

Вы выбираете приложения, которые хотите ограничить (YouTube, Instagram, игры), и устанавливаете дневной лимит. Если лимит превышен – здоровье капибары падает. Чтобы «простить» себе превышение и восстановить питомца, нужно отправить запрос другу. Друг нажимает на ссылку – и капибара снова здорова.

#### 🧠 Ключевые механики

- Мониторинг времени через **ScreenTime API** (`FamilyControls`, `DeviceActivity`)
- Принудительная блокировка приложений (`ManagedSettings`)
- Виртуальный питомец с динамическим здоровьем
- «Прощение» через друзей (глубокие ссылки)
- История использования и графики
- Локальные уведомления и виджет (в плане)

#### 🛠 Tech stack

- **Swift** + **UIKit** (всё кодом, без Storyboard)
- **MVVM** + делегаты / замыкания
- Хранение: `UserDefaults` + `Codable`
- Навигация: `UINavigationController` + `UITabBarController`
- Только Apple SDK (без сторонних библиотек)
- iOS 16.4+

#### 📱 Текущий статус

Проект находится в активной разработке. Реализованы:
- ✅ Авторизация ScreenTime и выбор приложений
- ✅ Применение блокировки
- ✅ Мониторинг использования и падение здоровья
- ✅ Экран капибары с полоской здоровья
- ✅ Генерация ссылок на прощение через Deep Links

В работе:
- 🔧 Статистика и графики
- 🔧 Профиль и настройки
- 🔧 Виджет и уведомления

[![GitHub](https://img.shields.io/badge/Репозиторий-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shokkobarokko/Bara)


---

### 🔧 Project 2 · ButtonBook

![Status](https://img.shields.io/badge/status-in%20development-orange?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS-lightgrey?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-5.9-F05138?style=flat-square&logo=swift)
![UIKit](https://img.shields.io/badge/UIKit-2C2C2E?style=flat-square&logo=apple)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D6EFD?style=flat-square&logo=swift)

> **ButtonBook** — публичный дневник изучения кнопок на iOS. 40 кнопок от простых до сложных анимированных: 20 на UIKit и 20 на SwiftUI. Каждая кнопка = отдельный файл + подробное объяснение.

#### 🎯 Концепция

Это учебный репозиторий, где я документирую процесс создания разных видов кнопок. Каждая кнопка живёт в своей папке с кодом и `README.md`. Главный README содержит таблицу всех 40 кнопок с уровнями сложности и ссылками.

#### 📋 Список кнопок (частично)

**UIKit (20 шт.):**
`Plain` · `Filled` · `Outlined` · `Tinted` · `Gradient` · `Shadow` · `Icon+Text` · `Destructive` · `Scale Press` · `Bounce Press` · `Haptic` · `Highlight Ripple` · `Loading State` · `Countdown` · `Toggle` · `Pill Progress` · `Morphing` · `Glitch` · `Liquid Fill` · `Particles Burst`

**SwiftUI (20 шт.):**
`Plain` · `Filled` · `Outlined` · `ScalePress` · `SpringBounce` · `Shimmer` · `GlowPulse` · `Icon Animated` · `RotatingBorder` · `LoadingDots` · `Toggle Checkmark` · `MatchedGeometry` · `Ripple Tap` · `Countdown` · `PillProgress` · `Morphing Shape` · `Liquid Wave` · `3D Flip` · `Particle Burst` · `Metal Shader`

#### 🛠 Tech stack

- **Swift** 5.9+ · **UIKit** + **SwiftUI**
- Только Apple SDK (без сторонних библиотек)
- iOS 16+ (iOS 17+ для Metal шейдера)
- Auto Layout кодом · ButtonStyle · Canvas · Metal

#### 📱 Текущий статус

Проект запущен, структура создана. Постепенно добавляю кнопки:
- ✅ Подготовка проекта (структура папок, SceneDelegate)
- 🔧 UIKit: 0/20 (начинаю с Plain)
- 🔧 SwiftUI: 0/20

Каждая новая кнопка → новый коммит + README с объяснением.

[![GitHub](https://img.shields.io/badge/Репозиторий-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Shokkobarokko/ButtonBook)

---

## 🎓 Teaching

Beyond mobile dev, I teach programming to kids and teenagers.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)
![Scratch](https://img.shields.io/badge/Scratch-4D97FF?style=flat-square&logo=scratch&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox%20Studio-E2231A?style=flat-square&logo=roblox&logoColor=white)

I believe that the earlier kids start thinking algorithmically, the better — so I make it fun.

---

## ⚔️ Coding Practice

I solve algorithmic challenges daily to sharpen my problem-solving skills and write better Swift code.

| Platform | Progress |
|----------|---------|
| **CodeWars** | 7 kyu · 75+ kata solved |
| **LeetCode** | 0+ problems solved · 30 days streak 🔥 |

<p align="left">
  <a href="https://www.codewars.com/users/Shokkobarokko">
    <img src="https://www.codewars.com/users/Shokkobarokko/badges/large" />
  </a>
</p>

*"Clean code, one kata at a time."*

---

## 📊 GitHub Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Shokkobarokko&show_icons=true&theme=dark&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shokkobarokko&layout=compact&theme=dark&hide_border=true" />
</p>

<p align="left">
  <img src="https://streak-stats.demolab.com?user=Shokkobarokko&theme=dark&hide_border=true" />
</p>

---

## 📬 Contact

[![Telegram](https://img.shields.io/badge/@Shokkobarokko-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Shokkobarokko)
