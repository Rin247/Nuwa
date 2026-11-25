# Nuwa — Offline Language Learning & Preservation App

Nuwa is an offline-first, ad-free language learning and indigenous language preservation application. Built with Kotlin, Jetpack Compose, Material 3, and a 100-language binding floor, Nuwa delivers spaced-repetition vocabulary learning, grammar guides, native audio pronunciation, and script handwriting practice — completely offline, with zero subscription paywalls or user tracking.

---

## 🌍 Key Features & Subsystem Breakdown

### 📚 100-Language Catalog & Dictionaries (`catalogs`)
- **Current**: 100 built-in offline language catalogs (major world languages, regional dialects, endangered and indigenous languages), IPA pronunciation guides, and offline dictionary lookup.
- **Planned / Roadmap**: Community dictionary importer, custom flashcard deck creator, and audio dictionary recorder.

### 🧠 Spaced-Repetition Learning System (`srs`)
- **Current**: Anki-style SuperMemo SM-2 spaced-repetition algorithm, daily review queue, multiple-choice quizzes, and listening exercises.
- **Planned / Roadmap**: Neural FSRS (Free Spaced Repetition Scheduler) integration, audio-only hands-free mode, and grammar pattern drills.

### ✍️ Script & Handwriting Recognition (`script`)
- **Current**: Stroke-order animations and interactive canvas tracing for CJK characters, Cyrillic, Arabic, Devanagari, and Greek scripts.
- **Planned / Roadmap**: Machine-learning offline stroke accuracy evaluator and custom character creation tool.

---

## 🏗️ Architecture & Technology Stack

- **Platform**: Android 13+ (minSdk 33, targetSdk 37).
- **UI & Layout**: Kotlin, Jetpack Compose, Material 3.
- **Data Engine**: Room local database + JSON 100-language catalog bundles (`shared/data/catalogs/`).
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
# Build Android Debug APK
cd android
./gradlew assembleDebug
```

---

## 📜 License

Nuwa is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
