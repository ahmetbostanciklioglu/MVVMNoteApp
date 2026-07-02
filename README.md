<div align="center">

# 📝 MVVM Note App

**An Android note-taking app project built with Jetpack Compose and Material 3.**

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Material 3](https://img.shields.io/badge/Material%203-6E48AA?style=flat-square&logo=materialdesign&logoColor=white)](https://m3.material.io)
![Stars](https://img.shields.io/github/stars/ahmetbostanciklioglu/MVVMNoteApp?style=flat-square&color=6E48AA)
![Last Commit](https://img.shields.io/github/last-commit/ahmetbostanciklioglu/MVVMNoteApp?style=flat-square&color=4776E6)

</div>

## 📖 Overview

MVVM Note App is an Android application project scaffolded with Jetpack Compose and Material 3. It is set up as the foundation for a note-taking app following the MVVM architecture pattern, using a modern Kotlin + Gradle Kotlin DSL toolchain and edge-to-edge Compose UI. The project currently ships the base Compose setup (theming, activity, and preview) ready to be extended into the full note-taking feature set.

## ✨ Features

- 🎨 **Jetpack Compose UI** — declarative UI built entirely with Compose.
- 🌗 **Material 3 theming** — dynamic color support with light/dark themes defined in the `ui.theme` package.
- 📱 **Edge-to-edge display** — enabled via `enableEdgeToEdge()` for a modern immersive layout.
- ⚙️ **Gradle Kotlin DSL + version catalog** — dependencies managed through a `libs.versions.toml` catalog.
- 🧪 **Test scaffolding** — includes unit test and instrumented test entry points out of the box.

## 🚀 Getting Started

```bash
git clone https://github.com/ahmetbostanciklioglu/MVVMNoteApp.git
cd MVVMNoteApp
```

Then open the project in **Android Studio**, let **Gradle** sync the dependencies, and press **Run** (or `Shift + F10`) to launch it on an emulator or a connected device.

## 📋 Requirements

- **Android Studio** (latest stable recommended)
- **Android SDK** — `compileSdk` / `targetSdk` 35, `minSdk` 24 (Android 7.0+)
- **Kotlin** with Jetpack Compose
- **JDK 11**

## 🧑‍💻 Author

**Ahmet Bostancıklıoğlu** — [@ahmetbostanciklioglu](https://github.com/ahmetbostanciklioglu) · ahmetbostancikli@gmail.com

> ⭐ If this helped you, consider giving the repo a star!
