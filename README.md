<p align="center">
  <img width="150" alt="Explyt logo" src="assets/explyt-logo.png">
</p>

<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent"><img src="https://img.shields.io/jetbrains/plugin/v/27979?label=version&logo=jetbrains&style=flat-square" alt="JetBrains Plugin Version"></a>
  <a href="https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent"><img src="https://img.shields.io/jetbrains/plugin/r/rating/27979?style=flat-square" alt="JetBrains Plugin Rating"></a>
  <a href="https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent"><img src="https://img.shields.io/jetbrains/plugin/d/27979?style=flat-square" alt="JetBrains Plugin Downloads"></a>
</p>

<h1 align="center">Explyt</h1>

<p align="center">
Stop Paying Tokens for Context Your IDE Already Knows. Let AI Drive Your JetBrains Tools Directly.
</p>

<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent">Install from JetBrains Marketplace</a>
  ·
  <a href="https://explyt.ai/docs/category/explyt-test">Docs</a>
  ·
  <a href="https://explyt.ai/docs/explyt-test/feature-matrix">Feature matrix</a>
  ·
  <a href="https://github.com/explyt/explyt/issues/new/choose">Support</a>
</p>

---

Explyt is an AI agent for JetBrains IDEs that fixes code with the project facts your IDE already knows.

It can run configured tests and builds, increase test coverage with coverage feedback, find where symbols are used, inspect connected library source code, debug with variable values, call stacks and execution paths, apply IDE refactorings, and review code with IDE static analysis — in supported IDEs.

## IDE-native workflows

### Debug bugs with runtime facts

[![Explyt debugs with runtime facts](assets/explyt-debugging-demo.gif)](assets/explyt-debugging-demo.mp4)

Instead of adding temporary logs, Explyt can run code under the debugger and inspect variable values, call stacks and execution paths before editing.

### Increase test coverage with IDE feedback

[![Explyt keeps adding tests until coverage reaches your target](assets/explyt-coverage-demo.gif)](assets/explyt-coverage-demo.mp4)

Instead of guessing which tests to write, Explyt runs tests with coverage, sees which lines are still uncovered, and keeps adding tests until coverage reaches your target — in supported IDEs.

### Change code safely with IDE refactorings

[![Explyt uses IDE refactorings](assets/explyt-safe-refactor-demo.gif)](assets/explyt-safe-refactor-demo.mp4)

Instead of search-and-replace, Explyt applies IDE refactorings such as safe rename across the project, changing symbols — not matching text.

### Review code with IDE static analysis

[![Explyt reviews code with IDE static analysis](assets/explyt-code-review-demo.gif)](assets/explyt-code-review-demo.mp4)

Instead of only checking the AI's diff by eye, Explyt reviews code with built-in code analysis and highlights errors, warnings and potential issues before you accept the change — in supported IDEs.

## Built for JetBrains projects

Explyt is strongest where the IDE already holds critical project knowledge:

<p>
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?logo=intellijidea&logoColor=white&style=flat-square" alt="IntelliJ IDEA">
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?logo=androidstudio&logoColor=white&style=flat-square" alt="Android Studio">
  <img src="https://img.shields.io/badge/PyCharm-21D789?logo=pycharm&logoColor=black&style=flat-square" alt="PyCharm">
  <img src="https://img.shields.io/badge/Rider-000000?logo=rider&logoColor=white&style=flat-square" alt="Rider">
  <img src="https://img.shields.io/badge/WebStorm-07C3F2?logo=webstorm&logoColor=black&style=flat-square" alt="WebStorm">
  <img src="https://img.shields.io/badge/GoLand-00ADD8?logo=go&logoColor=white&style=flat-square" alt="GoLand">
  <img src="https://img.shields.io/badge/PhpStorm-777BB4?logo=php&logoColor=white&style=flat-square" alt="PhpStorm">
</p>

- **IntelliJ IDEA and Android Studio**  
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=flat-square" alt="Java">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white&style=flat-square" alt="Kotlin">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white&style=flat-square" alt="Spring Boot">
  <img src="https://img.shields.io/badge/JUnit-25A162?logo=junit5&logoColor=white&style=flat-square" alt="JUnit">
  <img src="https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white&style=flat-square" alt="Gradle">
  <img src="https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white&style=flat-square" alt="Maven">  
  JUnit tests, Gradle/Maven builds, Spring Boot run setups, Spring profiles, classpaths, dependency versions, vulnerability search for Java/Kotlin, and test generation from real Spring executions.

- **PyCharm**  
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" alt="Python">
  <img src="https://img.shields.io/badge/virtualenv-3776AB?logo=python&logoColor=white&style=flat-square" alt="virtualenv">
  <img src="https://img.shields.io/badge/Coverage-2EA44F?style=flat-square" alt="Coverage">
  <img src="https://img.shields.io/badge/Debugger-6F42C1?style=flat-square" alt="Debugger">  
  Python interpreters, virtual environments, test runs, package code, coverage feedback, flaky-test analysis and runtime debugging.

- **Rider**  
  <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white&style=flat-square" alt=".NET">
  <img src="https://img.shields.io/badge/C%23-512BD4?logo=csharp&logoColor=white&style=flat-square" alt="C#">
  <img src="https://img.shields.io/badge/Builds_&_tests-2EA44F?style=flat-square" alt="Builds and tests">
  <img src="https://img.shields.io/badge/Debugger-6F42C1?style=flat-square" alt="Debugger">  
  .NET projects with configured run/debug setups, test runs, build-system support, connected dependency code and debugger-based investigation.

- **WebStorm**  
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square" alt="TypeScript">
  <img src="https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=white&style=flat-square" alt="npm">
  <img src="https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white&style=flat-square" alt="Jest">
  <img src="https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white&style=flat-square" alt="Vitest">
  <img src="https://img.shields.io/badge/Cypress-69D3A7?logo=cypress&logoColor=black&style=flat-square" alt="Cypress">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square" alt="Playwright">  
  npm, Jest, Vitest, Cypress and Playwright runs through the IDE, plus project-aware navigation, references, built-in code analysis and refactorings.

- **GoLand and PhpStorm**  
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white&style=flat-square" alt="Go">
  <img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=flat-square" alt="PHP">
  <img src="https://img.shields.io/badge/Code_navigation-0969DA?style=flat-square" alt="Code navigation">
  <img src="https://img.shields.io/badge/Refactoring-0969DA?style=flat-square" alt="Refactoring">
  <img src="https://img.shields.io/badge/Built--in_analysis-6F42C1?style=flat-square" alt="Built-in analysis">  
  Project-aware code navigation, references, built-in code analysis, refactorings and IDE-driven feedback for Go and PHP projects.

Some workflows depend on IDE and language support; see the [feature matrix](https://explyt.ai/docs/explyt-test/feature-matrix) for the current table.

## Installation

1. In your JetBrains IDE, open **Settings/Preferences → Plugins → Marketplace**, search for "Explyt AI Agent", or install directly from [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent).
2. Open your project and choose model access based on your setup; where supported, use Explyt-hosted models or your own API key (BYOK).
3. Ask Explyt to fix a failing test, debug a runtime issue, increase test coverage, review pull request or safely refactor code.

## For teams

Explyt works through JetBrains IDE actions, so code changes, test runs, debugger sessions and refactorings stay visible in the IDE for review. Model access options depend on your setup; where supported, teams can use Explyt-hosted models or their own API key. For team or security evaluation, email support@explyt.com.

## Links

- [Documentation](https://explyt.ai/docs/category/explyt-test)
- [Feature matrix](https://explyt.ai/docs/explyt-test/feature-matrix)
- [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/27979-explyt-ai-agent)
- [Other downloads](https://explyt.ai/download)

## Feedback and support

Report bugs, feature requests and quality issues through the [issue templates](https://github.com/explyt/explyt/issues/new/choose) or email support@explyt.com.

<sub>Explyt is a third-party plugin. It is not affiliated with, endorsed by, or sponsored by JetBrains.</sub>
