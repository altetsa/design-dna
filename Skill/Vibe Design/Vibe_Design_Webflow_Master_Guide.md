---
title: "Мастер-руководство по экосистеме Vibe Design & Webflow Agent Skills"
tags: [vibe-design, webflow, shadcn, stitch, gsap, mcp, skills, catalog, guide]
date: 2026-07-31
status: ✅ Активен
category: "Vibe Design / Webflow"
---

# 🚀 Vibe Design & Webflow — Единое Мастер-Руководство

Данный документ представляет собой **объединенное супер-руководство**, содержащее общую архитектуру и навигацию экосистемы **Vibe Design**, а также исчерпывающий реестр **28 Webflow Agent Skills**, MCP-серверов, компонентов Shadcn/ui, GSAP-анимаций и нейро-инструментов Google Labs Stitch.

---

## 🧭 1. Глобальная Навигация по Экосистеме Vibe Design

- 🌐 **[Раздел Webflow](file:///root/obsidian/Vibe Design/Webflow/)**: Реестр 28 скиллов, CMS, DevLink и автоматизация.
- 🎨 **[Раздел Shadcn/ui](file:///root/obsidian/Vibe Design/Skills/Shadcn/)**: [[Skills/Shadcn/Shadcn_Skills_Master_Index|Каталог 5 Shadcn Скиллов]] & Обзор Shadcn/ui
- 💎 **[Раздел DESIGN.md (74 Бренда)](file:///root/obsidian/Vibe Design/Design_MD/)**: [[Design_MD/Design_MD_Systems_Index|Каталог 74 Дизайн-Систем (Linear, Stripe, Vercel, Apple, etc.)]]
- 🚀 **[Раздел AI SaaS & LaunchKit](file:///root/obsidian/Vibe Design/AI_SaaS/)**: [[AI_SaaS/AI_SaaS_Master_Index|Архитектура LaunchKit, Auth, Billing и AI-Wiring]]
- ✨ **[Раздел UI/UX Pro Max](file:///root/obsidian/Vibe Design/Skills/UI_UX_Pro_Max/)**: [[Skills/UI_UX_Pro_Max/UI_UX_Pro_Max_Master_Index|Design Intelligence (57 стилей, 95 палитр, 56 шрифтов, 29 лендингов)]]
- 📁 **[Раздел General](file:///root/obsidian/Vibe Design/General/)**: Пайплайны верстки и архитектура.
- 🎨 **[Раздел Figma MCP & Webflow Pipeline](file:///root/obsidian/Vibe Design/Figma/)**: [[Figma/Figma_MCP_Guide_and_Integration|Спецификация Figma MCP]] & [[General/Figma_to_Webflow_Client_First_Pipeline|Пайплайн Figma ➔ Webflow Client-First]]
- ⚡ **[Раздел GSAP Animations](file:///root/obsidian/Vibe Design/Skills/GSAP/)**: [[Skills/GSAP/GSAP_Skills_Master_Index|GreenSock (8 Скиллов: ScrollTrigger, Timelines, React, SplitText, 60fps)]]
- 🎨 **[Раздел Google Labs Stitch](file:///root/obsidian/Vibe Design/Skills/Stitch/)**: [[Skills/Stitch/Stitch_Skills_Master_Index|Stitch (15 Скиллов: React Components, Design System, Prompt, Remotion, UI)]]

---

## 🌐 2. Webflow Agent Skills — Системный Реестр и Документация

**Конфигурация и расположение в системе:**
- **Исполняемые файлы скиллов (CLI):** `/root/.agent/skills/`
- **Документация и справочники Obsidian:** `/root/obsidian/Vibe Design/Webflow/Skills/`
- **MCP Сервер:** `@webflow/mcp-server` в `/root/mcp_config.json`

### 📚 Полный Реестр 28 Webflow Скиллов

| № | Название скилла | CLI Имя Скилла | Категория | Документ в Obsidian |
| :-: | :--- | :--- | :--- | :--- |
| 1 | **Accessibility Audit** | `accessibility-audit` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Accessibility_Audit\|Accessibility Audit]] |
| 2 | **Asset Audit** | `asset-audit` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Asset_Audit\|Asset Audit]] |
| 3 | **Bulk CMS Update** | `bulk-cms-update` | CMS Management | [[Webflow/Skills/CMS_Management/Bulk_Cms_Update\|Bulk CMS Update]] |
| 4 | **CMS Best Practices** | `cms-best-practices` | CMS Management | [[Webflow/Skills/CMS_Management/Cms_Best_Practices\|CMS Best Practices]] |
| 5 | **CMS Collection Setup** | `cms-collection-setup` | CMS Management | [[Webflow/Skills/CMS_Management/Cms_Collection_Setup\|CMS Collection Setup]] |
| 6 | **Client-First Naming (Finsweet)** | `client-first-naming` | Client-First | [[Webflow/Skills/Client_First/Client_First_Naming\|Client-First Naming]] |
| 7 | **Code Component Command** | `code-component-command` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Code_Component_Command\|Code Component Command]] |
| 8 | **Component Audit** | `component-audit` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Component_Audit\|Component Audit]] |
| 9 | **Component Scaffold** | `component-scaffold` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Component_Scaffold\|Component Scaffold]] |
| 10 | **Convert Component** | `convert-component` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Convert_Component\|Convert Component]] |
| 11 | **Custom Code Management** | `custom-code-management` | Designer & Integrations | [[Webflow/Skills/Designer_and_Integrations/Custom_Code_Management\|Custom Code Management]] |
| 12 | **Deploy Guide** | `deploy-guide` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Deploy_Guide\|Deploy Guide]] |
| 13 | **Designer Extension Command** | `designer-extension-command` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Designer_Extension_Command\|Designer Extension Command]] |
| 14 | **Designer Tools** | `designer-tools` | Designer & Integrations | [[Webflow/Skills/Designer_and_Integrations/Designer_Tools\|Designer Tools]] |
| 15 | **DevLink Command** | `devlink-command` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Devlink_Command\|DevLink Command]] |
| 16 | **Figma To Webflow** | `figma-to-webflow` | Designer & Integrations | [[Webflow/Skills/Designer_and_Integrations/Figma_To_Webflow\|Figma To Webflow]] |
| 17 | **Flowkit Naming** | `flowkit-naming` | Client-First | [[Webflow/Skills/Client_First/Flowkit_Naming\|Flowkit Naming]] |
| 18 | **Link Checker** | `link-checker` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Link_Checker\|Link Checker]] |
| 19 | **Local Dev Setup** | `local-dev-setup` | Code Components & Dev | [[Webflow/Skills/Code_Components_and_Dev/Local_Dev_Setup\|Local Dev Setup]] |
| 20 | **Pre Deploy Check** | `pre-deploy-check` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Pre_Deploy_Check\|Pre Deploy Check]] |
| 21 | **Review Comments** | `review-comments` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Review_Comments\|Review Comments]] |
| 22 | **Safe Publish** | `safe-publish` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Safe_Publish\|Safe Publish]] |
| 23 | **Site Activity** | `site-activity` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Site_Activity\|Site Activity]] |
| 24 | **Site Audit** | `site-audit` | Audits & Quality | [[Webflow/Skills/Audits_and_Quality/Site_Audit\|Site Audit]] |
| 25 | **Troubleshoot Deploy** | `troubleshoot-deploy` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Troubleshoot_Deploy\|Troubleshoot Deploy]] |
| 26 | **Webflow CLI Troubleshooter** | `webflow-cli-troubleshooter` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Webflow_Cli_Troubleshooter\|Webflow CLI Troubleshooter]] |
| 27 | **Webflow Cloud Command** | `webflow-cloud-command` | Deployment & CLI | [[Webflow/Skills/Deployment_and_CLI/Webflow_Cloud_Command\|Webflow Cloud Command]] |
| 28 | **Webflow Compress CMS Image** | `webflow-compress-cms-image` | CMS Management | [[Webflow/Skills/CMS_Management/Webflow_Compress_Cms_Image\|Webflow Compress CMS Image]] |
| 29 | **WFU MCP Getting Started** | `wfu-mcp-getting-started` | Designer & Integrations | [[Webflow/Skills/Designer_and_Integrations/Wfu_Mcp_Getting_Started\|WFU MCP Getting Started]] |

---

## 🛠️ 3. Описание Функциональных Категорий Webflow

### 📝 CMS & Контент:
- **`bulk-cms-update`** — Массовое создание/обновление элементов CMS с валидацией и предпросмотром изменений.
- **`cms-collection-setup`** — Проектирование структур баз данных, полей и связей («1-to-1», «many-to-many»).
- **`cms-best-practices`** — Экспертные руководства по архитектуре и оптимизации загрузки CMS.
- **`webflow-compress-cms-image`** — Автоматическое сжатие изображений в CMS с конвертацией в WebP/AVIF.

### 🎨 Дизайн, Figma & Стилизация:
- **`figma-to-webflow`** — Прямой перенос макетов и элементов из Figma в элементы Webflow.
- **`designer-tools`** — Создание секций, лейаутов и верстки на холсте Webflow Designer.
- **`flowkit-naming`** & **`client-first-naming`** — Присвоение имен классов по методологиям Flowkit и Finsweet Client-First (v2/v3).
- **`custom-code-management`** — Безопасное внедрение кастомного JavaScript/CSS кода на страницы сайта.

### ⚛️ React & DevLink Интеграции:
- **`devlink-command`** — Экспорт элементов Webflow в чистый React / Next.js код через Webflow DevLink.
- **`code-component-command`** & **`convert-component`** — Разработка и конвертация React-компонентов для Webflow Designer.
- **`component-audit`** & **`component-scaffold`** — Аудит и создание шаблонов компонентов.
- **`local-dev-setup`** — Инициализация локальной среды для разработки веб-компонентов.

### 🔍 Аудит, SEO & Безопасный Деплой:
- **`accessibility-audit`** — Проверка сайта по стандарту WCAG 2.1 (контрастность, кнопки, фокус, формы).
- **`asset-audit`** & **`link-checker`** — Аудит SEO ассетов (alt-теги) и поиск битых ссылок.
- **`site-audit`** & **`site-activity`** — Общий анализ здоровья сайта и просмотр логов изменений.
- **`safe-publish`** — Безопасная публикация сайта с предварительной генерацией diff-отчета.
- **`webflow-cloud-command`**, **`deploy-guide`** & **`webflow-cli-troubleshooter`** — Деплой на Webflow Cloud и отладка CLI.

---

## 🎨 4. Разработка UI-компонентов Shadcn/ui (5 Скиллов + MCP)

### 🔍 Поиск и Открытие компонентов:
- **`shadcn-component-discovery`** — Поиск компонентов и блоков по всем сторонним реестрам (Magic UI, Aceternity, Animate UI, Tailark, UI Elements) до написания кода с нуля.

### ⚙️ Установка & Контекст проекта:
- **`shadcn` (Core)** — Считывание `components.json`, подстройка под тему Tailwind CSS и выполнение установки компонентов `npx shadcn add`.

### 🛡️ Ревью и Улучшение Кода:
- **`shadcn-component-review`** — Ревью созданных компонентов на отступы, темы, data-слоты и доступность.
- **`shadcn-improve`** — Глубокий аудит кодовой базы UI и составление пошаговых планов рефакторинга.
- **`migrate-radix-to-base`** — Перевод компонентов с примитивов Radix UI на новые примитивы Base UI.

---

## 🎨 5. Google Labs Stitch Skills (15 Скиллов)

### 🎨 Design & Generation:
- **`stitch-generate-design`** — Генерация экранов и макетов по промптам и изображениям.
- **`stitch-code-to-design`** — Преобразование кода React/HTML в веб-дизайн Stitch.
- **`stitch-extract-design-md`** — Автоматическое извлечение токенов дизайна в формат `DESIGN.md`.
- **`stitch-manage-design-system`** — Управление дизайн-системами, палитрами и шрифтами.
- **`stitch-extract-static-html`** — Извлечение статического HTML со встроенными ресурсами.
- **`stitch-upload-to-stitch`** — Загрузка локальных страниц, логотипов и документов в проект Stitch.

### 💻 Build & React Components:
- **`stitch-react-components`** — Конвертация дизайнов Stitch в модульные Vite + React компоненты.
- **`stitch-react-vite-dashboard`** — Генерация дашбордов на React + Vite + TanStack Query.
- **`stitch-shadcn-ui`** — Интеграция верстки интерфейсов на базе shadcn/ui.
- **`stitch-react-native`** — Конвертация интерфейсов в компоненты React Native.
- **`stitch-remotion`** — Создание интерфейсных видеороликов и видеоанимаций в Remotion.

### ⚙️ Quality & Prompt Engineering:
- **`stitch-taste-design`** — Оценка и авто-исправление эстетики дизайна по стандартам anti-generic UI.
- **`stitch-enhance-prompt`** — Обогащение промптов перед генерацией UI.
- **`stitch-stitch-loop`** — Автономный цикл итеративного улучшения дизайна.
- **`stitch-design-md`** — Синтез семантических дизайн-систем.

---

## 💡 6. Пример Сквозного Сценария (Figma ➔ Webflow ➔ React/shadcn ➔ Stitch)

1. **Импорт макета**: Перенос макета из Figma в Webflow через `figma-to-webflow`.
2. **Стилизация и CMS**: Применение нейминга `client-first-naming` / `flowkit-naming` и наполнение коллекций через `bulk-cms-update`.
3. **Аудит**: Запуск `accessibility-audit` и `link-checker`.
4. **Конвертация в React**: Экспорт компонентов через `devlink-command` или `code-component-command`.
5. **Stitch & Shadcn UI**: Генерация и доработка компонентов через `stitch-react-components` и `shadcn-component-review`!

---

## ⚡ 7. Как вызывать Webflow & Vibe Design Skills через ИИ

Каждый скилл автоматически задействуется при описании соответствующей задачи в диалоге:
- **Аудит доступности**: *"Запусти accessibility audit для моего сайта Webflow"*
- **Массовое обновление CMS**: *"Обнови 10 постов в коллекции Блог"*
- **Файлы и верстка Figma**: *"Перенеси макет из Figma в Webflow"*
- **Деплой и публикация**: *"Проверь пре-деплой чек-лист и опубликуй сайт через safe-publish"*
