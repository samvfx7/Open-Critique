 ██████╗ ██████╗ ███████╗███╗   ██╗
██╔══██ ╗██╔══██╗██╔════╝████╗  ██║
██║   ██║ ██████╝█████╗.    ██╔██╗ ██║
██║   ██║ ██╔═══╝ ██╔══╝  ██║╚██╗██║
╚██████ ╔██║       ███████╗██║ ╚████║
 ╚═════╝ ╚═╝     ╚══════╝╚═╝  ╚═══╝

<div align="center">🔷 OpenCritique

Train smarter. Build habits. Make progress.

🏋️ Personalized Workouts · 🎯 Custom Habits · ⚡ XP Progression

An open-source Android fitness and habit-building app designed around consistency, simplicity, and personal growth.

</div>---

🌌 About

OpenCritique brings personalized fitness, daily habits, and gamified progression together in one streamlined experience.

The philosophy is simple: make progress easier to start, easier to track, and easier to maintain.

No unnecessarily complicated workout builders. No cluttered interfaces. Just a focused experience built to help you keep improving.

✨ Features

🏋️ Personalized Workouts

- 🎯 Programs tailored to individual goals, experience, and preferences.
- 🏠 Home workouts that require no equipment.
- 🧠 Automatic exercise selection based on onboarding preferences.
- ⏱️ Rest periods between exercises.
- 📋 Clear exercise instructions and focused workout sessions.

🎯 Custom Habits

- ➕ Create personal habits and routines.
- ⚡ Earn experience points for eligible activities.
- 🔥 Track streaks and consistency.
- 📈 Monitor progress over time.

🏆 Progression

- XP-based rewards for completed activities.
- Progress tracking and achievement milestones.
- Daily activity records.
- A progression system focused on consistency rather than perfection.

🎨 Premium Design

- Minimal, modern native Android UI.
- Carefully selected typography and balanced spacing.
- Compact layouts without oversized cards.
- Smooth transitions and responsive interactions.
- Thoughtful light and dark themes.
- Clear visual hierarchy that keeps the focus on the task.

🔒 Privacy First

- Privacy-conscious architecture.
- Local data storage where practical.
- Minimal unnecessary data collection.
- Transparent, open-source development.

Privacy protections depend on the actual implementation and any external integrations.

🧊 Design Principles

Principle| Philosophy
💎 Minimalism| Keep the interface focused.
🎯 Personalization| Adapt workouts to the user.
⚡ Performance| Prioritize responsive interactions.
🔒 Privacy| Respect personal data.
📈 Consistency| Make sustainable progress the goal.

🛠️ Technology Stack

Technology| Purpose
Kotlin| Primary programming language
Jetpack Compose| Native declarative UI
Material 3| UI foundations
Coroutines & StateFlow| Asynchronous operations and reactive state
Room| Local database persistence
Hilt| Dependency injection
Gradle| Build automation

🏗️ Architecture

OpenCritique uses a modular architecture designed to separate the UI from core business logic.

OpenCritique
├── app/
│   └── Android application and UI
├── domain/
│   └── Core business logic
└── Gradle build configuration

- ":app" — Android application, interface, and platform integrations.
- ":domain" — Core business rules, designed to remain independent of Android framework dependencies wherever practical.

🚀 Getting Started

Requirements

- JDK 17
- Android SDK Platform 36
- Android Studio or a compatible development environment
- An Android device or emulator

1. Clone the repository

git clone <repository-url>
cd OpenCritique-Android

2. Build the debug APK

./gradlew :app:assembleDebug

3. Run tests

./gradlew test

📦 APK Location

After a successful build:

app/build/outputs/apk/debug/

Replace "<repository-url>" with the actual Git repository URL.

🗺️ Roadmap

- [ ] Personalized workout onboarding
- [ ] Equipment-free home workout programs
- [ ] Automatic exercise selection
- [ ] Rest periods between exercises
- [ ] Custom habits and goals
- [ ] XP and progression system
- [ ] Streak and consistency tracking
- [ ] Progress history
- [ ] Refined premium UI
- [ ] Privacy-focused data architecture
- [ ] Comprehensive automated tests

This roadmap describes the intended direction. Not every feature is necessarily implemented yet.

🤝 Contributing

OpenCritique aims to encourage transparent development and community collaboration.

Potential contributions include:

- 🐛 Bug reports
- 💡 Feature suggestions
- 🎨 UI/UX improvements
- 🧪 Automated tests
- ⚙️ Performance and architecture improvements

Keep contributions focused, maintainable, and consistent with the project's design principles.

📄 License

OpenCritique is intended to be open source. The repository's actual license should be specified in a "LICENSE" file before redistribution.

---

<div align="center">🔷 OPENCRITIQUE

🏋️ Train · 🎯 Build · ⚡ Progress

Progress over perfection. 🚀

</div>
