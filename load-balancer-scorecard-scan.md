# Результаты сканирования OpenSSF Scorecard
## Репозиторий: LoadBalancer (ваш проект)

### Общая оценка: **1.2 / 10**

---

### Проверки с высокими баллами (10/10)

| Проверка | Балл | Детали |
|----------|------|--------|
| **Binary-Artifacts** | ✅ 10/10 | Бинарные артефакты не найдены |

---

### Проверки с проблемами (0/10)

| Проверка | Балл | Проблема |
|----------|------|----------|
| **Vulnerabilities** | 🔴 0/10 | **33 известные уязвимости** в зависимостях |
| **Code-Review** | 🔴 0/10 | 0 из 4 изменений прошли ревью |
| **Contributors** | 🔴 0/10 | Нет внешних контрибьюторов |
| **CII-Best-Practices** | 🔴 0/10 | Нет бейджа OpenSSF best practices |
| **Dependency-Update-Tool** | 🔴 0/10 | Нет Dependabot или аналогичного инструмента |
| **Fuzzing** | 🔴 0/10 | Фаззинг не настроен |
| **License** | 🔴 0/10 | Отсутствует файл лицензии |
| **Maintained** | 🔴 0/10 | Нет активности за последние 90 дней |
| **Pinned-Dependencies** | 🔴 0/10 | Зависимости не закреплены по хешу |
| **SAST** | 🔴 0/10 | Нет SAST-инструментов (CodeQL и т.п.) |
| **Security-Policy** | 🔴 0/10 | Отсутствует SECURITY.md |

---

### Не удалось проверить (Inconclusive)

| Проверка | Статус | Причина |
|----------|--------|---------|
| **Branch-Protection** | ❌ Ошибка | Токену не хватает прав `public_repo` для просмотра защиты веток |
| **CI-Tests** | ❓ Нет PR | В репозитории нет Pull Request'ов для анализа |
| **Dangerous-Workflow** | ❓ Нет workflow | GitHub Actions workflow не обнаружены |
| **Packaging** | ❓ Нет workflow | Нет workflow для публикации пакетов |
| **Signed-Releases** | ❓ Нет релизов | Подписанные релизы не найдены |
| **Token-Permissions** | ❓ Нет токенов | GitHub Actions токены не найдены |

---

### Анализ по закону Гудхарта

**Что измеряет результат:**
- `Vulnerabilities` — реальные уязвимости в зависимостях (0/10, **33 уязвимости**)
- `Code-Review` — реально ли есть ревью (0/10)

**Что измеряет только наличие активности/файлов:**
- `License` — наличие лицензии (0/10 — файла нет)
- `Security-Policy` — наличие SECURITY.md (0/10 — файла нет)
- `Maintained` — наличие коммитов (0/10 — нет активности)
- `Contributors` — наличие внешних контрибьюторов (0/10)

### Вывод из консоли
-------
Aggregate score: 1.2 / 10

Check scores:
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
|  SCORE  |          NAME          |               REASON                |                                               DOCUMENTATION/REMEDIATION                                               |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 10 / 10 | Binary-Artifacts       | no binaries found in the repo       | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#binary-artifacts       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | Branch-Protection      | internal error: error during        | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#branch-protection      |
|         |                        | branchesHandler.setup: internal     |                                                                                                                       |
|         |                        | error: githubv4.Query: Your         |                                                                                                                       |
|         |                        | token has not been granted the      |                                                                                                                       |
|         |                        | required scopes to execute this     |                                                                                                                       |
|         |                        | query. The 'rulesets' field         |                                                                                                                       |
|         |                        | requires one of the following       |                                                                                                                       |
|         |                        | scopes: ['public_repo'],            |                                                                                                                       |
|         |                        | but your token has only been        |                                                                                                                       |
|         |                        | granted the: [''] scopes. Please    |                                                                                                                       |
|         |                        | modify your token's scopes at:      |                                                                                                                       |
|         |                        | https://github.com/settings/tokens. |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | CI-Tests               | no pull request found               | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#ci-tests               |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | CII-Best-Practices     | no effort to earn an OpenSSF        | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#cii-best-practices     |
|         |                        | best practices badge detected       |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Code-Review            | Found 0/4 approved changesets       | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#code-review            |
|         |                        | -- score normalized to 0            |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Contributors           | project has 0 contributing          | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#contributors           |
|         |                        | companies or organizations --       |                                                                                                                       |
|         |                        | score normalized to 0               |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | Dangerous-Workflow     | no workflows found                  | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#dangerous-workflow     |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Dependency-Update-Tool | no update tool detected             | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#dependency-update-tool |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Fuzzing                | project is not fuzzed               | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#fuzzing                |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | License                | license file not detected           | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#license                |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Maintained             | 0 commit(s) and 0 issue             | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#maintained             |
|         |                        | activity found in the last 90       |                                                                                                                       |
|         |                        | days -- score normalized to 0       |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | Packaging              | packaging workflow not              | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#packaging              |
|         |                        | detected                            |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Pinned-Dependencies    | dependency not pinned by hash       | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#pinned-dependencies    |
|         |                        | detected -- score normalized        |                                                                                                                       |
|         |                        | to 0                                |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | SAST                   | no SAST tool detected               | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#sast                   |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Security-Policy        | security policy file not            | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#security-policy        |
|         |                        | detected                            |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | Signed-Releases        | no releases found                   | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#signed-releases        |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| ?       | Token-Permissions      | No tokens found                     | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#token-permissions      |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 0 / 10  | Vulnerabilities        | 33 existing vulnerabilities         | https://github.com/ossf/scorecard/blob/40bbc9c958aa66327fb026b2136f1951298ca0f8/docs/checks.md#vulnerabilities        |
|         |                        | detected                            |                                                                                                                       |
|---------|------------------------|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
