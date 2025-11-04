# 🧠 analyses-options.yaml (Flutter Project)

A structured and flexible YAML configuration file for managing **analysis options** in Flutter projects.  
This setup helps enforce consistent code style, lint rules, and project-wide analysis settings. ✨

---

## 🚀 Overview

In Flutter (and Dart), the `analysis_options.yaml` file defines:
- 🧩 **Lint rules** (code quality & formatting)
- ⚙️ **Analyzer settings**
- 🧠 **Error and warning behaviors**
- 🏗️ **Custom configurations** for teams or projects

The goal is to keep your Flutter codebase **clean**, **maintainable**, and **consistent** across developers.

---

## 📂 File Structure

```
.
├── lib/
├── test/
├── pubspec.yaml
├── analysis_options.yaml   # 👈 This file
└── README.md
```

---

## 🧾 Example Configuration

```yaml
include: package:flutter_lints/flutter.yaml

linter:
  rules:
    avoid_print: true
    prefer_const_constructors: true
    use_key_in_widget_constructors: true
    always_use_package_imports: true

analyzer:
  exclude:
    - '**/*.g.dart'
    - '**/*.freezed.dart'
```

> 💡 This ensures your project follows clean architecture and consistent linting rules across your team.

---

## 🧠 Key Concepts

| Concept | Description |
|----------|-------------|
| **Linter Rules** | Define how strict or flexible your coding style is. |
| **Analyzer Configs** | Control what files are analyzed or ignored. |
| **Project Consistency** | Keep every developer aligned on the same standards. |

---

## 🧰 Tools Used

- 🐦 **Flutter SDK**
- 🧩 **flutter_lints**
- 🧹 **Dart Analyzer**

---

## ⚙️ How to Use

1. Add the configuration file to the root of your project.  
2. Run Flutter analyzer:  
   ```bash
   flutter analyze
   ```
3. Fix or refactor code based on suggestions and rules.  

---

## 🖼️ Example Screenshot

*(You can replace these placeholders with real ones later)*  

![Flutter Lint Example](<img width="1395" height="367" alt="image" src="https://github.com/user-attachments/assets/64fb6216-6099-470c-b8fa-41f24f0045a6" />
)

---

## 💬 About This Project

This repo was created after a company presentation on how to structure and use `analysis_options.yaml` in Flutter projects — aiming to share **best practices**, **clean code habits**, and **team alignment**. 🧑‍💻

---

## 🌟 Author

👤 **Mostafa Awad**  
📫 [LinkedIn](https://www.linkedin.com/in/awad-flutter-dev/)  
💻 [GitHub](https://github.com/Mostafa3wad)

---

## 🪄 License

Open source — feel free to fork, modify, and adapt for your Flutter projects. 🚀

---

✨ *“Clean code starts with clean analysis rules.”*
