# Open-Source Toolkit — Self-Hosted / Clone-Based Repos


## 📋 טבלת סיכום / Summary

| # | קטגוריה / Category | ריפוז | מה זה נותן |
|---|---|:---:|---|
| 1 | [ניהול ידע / Knowledge Management](#sec-knowledge) | 7 | ויקי, בסיסי ידע, מחקר ותיעוד |
| 2 | [פרודוקטיביות / Productivity Apps](#sec-productivity) | 4 | חלופות Notion/Miro, לוחות לבנים, מצגות |
| 3 | [כלי פיתוח / Development Tools](#sec-dev-tools) | 3 | SDK, vector DB, מנוע חיפוש |
| 4 | [סוכני AI ואוטומציה / Agents, Automation & MCP](#sec-agents) | 7 | פלטפורמות סוכנים, workflows, MCP |
| 5 | [סוכני קוד / Coding Agents](#sec-coding) | 3 | סקילז ותשתיות לסוכני קוד |
| 6 | [וידאו ומדיה / Video & Media](#sec-video) | 6 | עריכה, הקלטת מסך, תמלול |
| 7 | [מכירות ו-CRM / Sales & CRM](#sec-sales) | 6 | CRM, תזמון, קמפייני מייל |
| 8 | [רשתות ושיווק / Social & Marketing](#sec-social) | 3 | תזמון רשתות, אימייל שיווקי |

> **סה"כ 39 ריפוז בטבלאות הראשיות** + 13 שסומנו כ-Quick-Install בסוף.

---

<a id="sec-knowledge"></a>
## 1 · 🧠 Knowledge Management / ניהול ידע

| Repo | תיאור | פריסה |
|---|---|---|
| [Docmost](https://github.com/docmost/docmost) | ויקי ומרכז מסמכים שיתופי (חלופה ל-Confluence/Notion), עם עריכה בזמן אמת, הרשאות וסביבות עבודה (spaces). מתאים לבסיס ידע פנימי או ללקוחות. | Docker |
| [Wiki.js](https://github.com/requarks/wiki) | מנוע ויקי מודרני מבוסס Node.js עם עורך Markdown/WYSIWYG, ניהול הרשאות ואימות ארגוני (SSO). | Docker |
| [Trilium (TriliumNext)](https://github.com/TriliumNext/Notes) | אפליקציית רישום היררכית לבניית בסיסי ידע אישיים/צוותיים גדולים, עם קישורים דו-כיווניים, Web Clipper וסקריפטים. | Clone / Docker |
| [Outline](https://github.com/outline/outline) | בסיס ידע וויקי לצוותים עם עריכה מהירה ונקייה, חיפוש חזק ואינטגרציות (Slack ועוד). מצוין לנהלים ו-Onboarding. | Docker |
| [SiYuan](https://github.com/siyuan-note/siyuan) | מערכת ניהול ידע (PKM) מבוססת בלוקים, local-first, עם Markdown/WYSIWYG וקישוריות דו-כיוונית. דגש על פרטיות. | Docker |
| [Memos](https://github.com/usememos/memos) | מערכת קלה ומהירה ל-Quick Capture של רעיונות, לינקים ולוגים, עם Markdown, תגיות וחיפוש. שכבת ידע קלת-משקל. | Docker |
| [Karakeep](https://github.com/karakeep-app/karakeep) | מערכת Self-Hosted לשמירת לינקים, notes ותמונות עם תיוג אוטומטי מבוסס AI וחיפוש חכם — מצוינת כמאגר Research. | Docker |

<a id="sec-productivity"></a>
## 2 · 🗂️ Productivity & Collaboration / פרודוקטיביות ושיתוף

| Repo | תיאור | פריסה |
|---|---|---|
| [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) | חלופת קוד-פתוח ל-Notion — מסמכים, בסיסי נתונים ולוחות משימות ויכולות AI. בנויה ב-Flutter/Rust, עם דגש על פרטיות. | Clone / Download |
| [AFFiNE](https://github.com/toeverything/AFFiNE) | סביבת עבודה "הכל-באחד" המשלבת מסמכים, לוח לבן (whiteboard) ובסיסי נתונים — חלופה ל-Notion+Miro. Local-first. | Docker |
| [Excalidraw](https://github.com/excalidraw/excalidraw) | לוח לבן וירטואלי לסקיצות, דיאגרמות ותרשימי ארכיטקטורה בסגנון כתב-יד. מצוין לסדנאות ואפיון פתרונות בייעוץ. | Docker |
| [Presenton](https://github.com/presenton/presenton) | מחולל מצגות מבוסס AI (חלופה ל-Gamma/Beautiful AI) עם ייצוא PPTX/PDF, תבניות משלכם, BYOK ו-MCP מובנה. | Docker / Download |

<a id="sec-dev-tools"></a>
## 3 · 🛠️ Development Tools / כלי פיתוח

| Repo | תיאור | פריסה |
|---|---|---|
| [Flutter](https://github.com/flutter/flutter) | ה-SDK של גוגל לבניית אפליקציות חוצות-פלטפורמה (מובייל, ווב, דסקטופ) מקוד יחיד. נפרס דרך הורדת/שיבוט ה-SDK. | SDK / Clone |
| [Qdrant](https://github.com/qdrant/qdrant) | מסד נתונים וקטורי (vector DB) בביצועים גבוהים — בסיס לחיפוש סמנטי ולמערכות RAG. | Docker / Clone |
| [SearXNG](https://github.com/searxng/searxng) | מנוע מטא-חיפוש בניהול עצמי ושומר פרטיות, שמאגד תוצאות ממקורות רבים. שכבת חיפוש נוחה לסוכני AI ולמחקר. | Docker |

<a id="sec-agents"></a>
## 4 · 🤖 AI Agents, Automation & MCP / סוכני AI, אוטומציה ו-MCP

| Repo | תיאור | פריסה |
|---|---|---|
| [n8n](https://github.com/n8n-io/n8n) | פלטפורמת אוטומציה ו-workflows חזותית עם מאות אינטגרציות ותמיכה ב-AI/סוכנים. מומלץ לפרוס עצמית ב-Docker.¹ | Docker |
| [Activepieces](https://github.com/activepieces/activepieces) | כלי אוטומציה בקוד פתוח (חלופה ל-Zapier) עם תמיכה מובנית ב-MCP ובסוכני AI. | Docker |
| [Dify](https://github.com/langgenius/dify) | פלטפורמה לבניית אפליקציות LLM וסוכני AI — RAG, workflows וכלים — עם ממשק ויזואלי (גם ללא מפתחים). | Docker |
| [LibreChat](https://github.com/danny-avila/LibreChat) | ממשק צ'אט בסגנון ChatGPT התומך במודלים מרובים, סוכנים, כלים ו-MCP. פריסה עצמית מאובטחת לארגון. | Docker |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | אפליקציית "הכל-באחד" להרצת צ'אט/RAG על המסמכים שלכם, עם סוכנים וכלים. אפליקציית דסקטופ או Docker. | Docker / Download |
| [Firecrawl](https://github.com/mendableai/firecrawl) | כלי scraping/crawling שממיר אתרים ל-Markdown/JSON מוכן ל-LLM. ניתן לפרוס עצמית כשכבת קלט לסוכנים ולמחקר.¹ | Docker |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | המונורפו הרשמי של שרתי MCP לדוגמה ולעיון (Anthropic/הקהילה). מקור מצוין ללמידה ולהתאמת שרתי MCP משלכם. | Clone |

<a id="sec-coding"></a>
## 5 · 💻 Coding Agents & AI Dev Skills / סוכני קוד וכלי פיתוח AI

| Repo | תיאור | פריסה |
|---|---|---|
| [gstack](https://github.com/garrytan/gstack) | אוסף "סקילז" ל-Claude Code שהופך אותו ל"צוות הנדסה" וירטואלי (מנהל, מעצב, מבקר קוד, QA, אבטחה ועוד). | Clone |
| [ponytail](https://github.com/DietrichGebert/ponytail) | כלל/סקיל לסוכני קוד שמכריח פתרונות מינימליים ("הסניור העצלן") — פחות קוד, זול ומהיר יותר. נטען מ-checkout לסוכנים כמו OpenCode. | Clone |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | פלטפורמת סוכן קוד אוטונומי (לשעבר OpenDevin) שכותב, מריץ ומתקן קוד. מורצת דרך Docker לשליטה מלאה. | Docker |

<a id="sec-video"></a>
## 6 · 🎬 Video, Media & Screen Recording / וידאו, מדיה והקלטת מסך

| Repo | תיאור | פריסה |
|---|---|---|
| [OBS Studio](https://github.com/obsproject/obs-studio) | תוכנת הקלטת מסך ושידור חי (streaming) מקצועית וחינמית — תקן דה-פקטו בתעשייה. מצוינת לוובינרים והדרכות. | Download / Clone |
| [ShareX](https://github.com/ShareX/ShareX) | כלי צילום מסך והקלטה ל-Windows עם OCR, annotation, שיתוף ואוטומציות מבוססות hotkeys. | Download / Clone |
| [OpenCut](https://github.com/OpenCut-app/OpenCut) | עורך וידאו בקוד פתוח (חלופה ל-CapCut) לווב/דסקטופ, ללא watermark וללא מנוי. | Docker / Clone |
| [Cap](https://github.com/CapSoftware/Cap) | חלופת קוד-פתוח ל-Loom להקלטה, עריכה ושיתוף מהיר של סרטוני מסך. אפליקציית דסקטופ + פריסה עצמית. | Download / Docker |
| [Open Recorder](https://github.com/imbhargav5/open-recorder) | מקליט מסך, צילומי מסך ועורך קל ל-macOS (Swift+Rust) עם רקעים, זום ומסגור. | Clone |
| [whisper.cpp](https://github.com/ggml-org/whisper.cpp) | מימוש C/C++ מהיר של מודל Whisper לתמלול דיבור, רץ מקומית ללא GPU. חלופת ה-clone ל-openai/whisper. | Clone |

<a id="sec-sales"></a>
## 7 · 📞 Sales, CRM & Outreach / מכירות, CRM ופנייה

| Repo | תיאור | פריסה |
|---|---|---|
| [Twenty](https://github.com/twentyhq/twenty) | CRM מודרני בקוד פתוח (חלופה ל-Salesforce/HubSpot) עם מודל דאטה גמיש, pipelines ואוטומציה. | Docker |
| [EspoCRM](https://github.com/espocrm/espocrm) | מערכת CRM מלאה ובוגרת לניהול לידים, אנשי קשר, הזדמנויות, קמפיינים ותמיכה. בסיס למערכת מכירות פנימית. | Docker / Clone |
| [Cal.com](https://github.com/calcom/cal.com) | תשתית תזמון פגישות בקוד פתוח (חלופה ל-Calendly) — מצוינת לתיאום שיחות חמות/דמו. | Docker |
| [Chatwoot](https://github.com/chatwoot/chatwoot) | מרכז שיחות רב-ערוצי (צ'אט חי, מייל, WhatsApp, טלגרם) לשירות ומכירות. חלופת קוד-פתוח ל-Intercom. | Docker |
| [Listmonk](https://github.com/knadh/listmonk) | מנהל רשימות תפוצה וקמפייני אימייל בביצועים גבוהים (binary יחיד ב-Go). חלופה ל-Mailchimp. | Docker / Clone |
| [Mautic](https://github.com/mautic/mautic) | פלטפורמת אוטומציית שיווק בוגרת — קמפייני מייל, ניקוד לידים, דפי נחיתה ורצפי nurture. | Docker / Clone |

<a id="sec-social"></a>
## 8 · 📣 Social Media & Marketing / רשתות חברתיות ושיווק

| Repo | תיאור | פריסה |
|---|---|---|
| [Postiz](https://github.com/gitroomhq/postiz-app) | תזמון וניהול רשתות חברתיות עם יכולות AI (חלופה ל-Buffer). עשרות פלטפורמות, ניתוחים ו-API לאוטומציה. | Docker |
| [Mixpost](https://github.com/inovector/mixpost) | פלטפורמת ניהול רשתות חברתיות בניהול עצמי (חלופה ל-Buffer) מבוססת Laravel — תזמון, פרסום וניתוח, ללא מנוי. | Docker / Clone |
| [Keila](https://github.com/pentacent/keila) | כלי קוד-פתוח לניהול Newsletter וקמפייני אימייל בניהול עצמי (Elixir), עם חיבור לספקי SMTP שונים. | Docker / Clone |

---

<a id="quick-install"></a>
## ⚡ Quick-Install / לא נכללו (התקנה מהירה)

הריפוז הבאים **לא** נכללו בטבלאות הראשיות כי הם זמינים בהתקנה מהירה דרך מנהל חבילות (`pip`/`npm`/`pipx`/`npx`/brew) ואינם מצריכים שיבוט של הריפו. הלינק והתיאור כאן למען הנוחות.

| Repo | תיאור | התקנה מהירה |
|---|---|---|
| [LangChain](https://github.com/langchain-ai/langchain) | פריימוורק לבניית אפליקציות מבוססות LLM ושרשראות/סוכנים. | `pip install langchain` / npm |
| [LangGraph](https://github.com/langchain-ai/langgraph) | ספריית תזמור (orchestration) לבניית סוכנים וגרפי-מצב מבוססי LLM. | `pip install langgraph` |
| [Agno](https://github.com/agno-agi/agno) | פריימוורק קליל לבניית סוכני AI מרובי-מודלים עם זיכרון וכלים. | `pip install agno` |
| [browser-use](https://github.com/browser-use/browser-use) | ספרייה שמאפשרת לסוכני AI לשלוט בדפדפן ולבצע משימות ווב. | `pip install browser-use` |
| [Whisper](https://github.com/openai/whisper) | מודל תמלול דיבור לטקסט (הכללנו במקום את **whisper.cpp** שמצריך שיבוט). | `pip install openai-whisper` |
| [Slidev](https://github.com/slidevjs/slidev) | כלי מצגות למפתחים מבוסס Markdown ו-Vue. | `npm init slidev@latest` |
| [OpenCode](https://github.com/sst/opencode) | סוכן קוד AI לטרמינל (חלופת קוד-פתוח ל-Claude Code). | `npm i -g opencode-ai` / brew |
| [Strix](https://github.com/usestrix/strix) | סוכני AI אוטונומיים לבדיקות אבטחה/פנטסט של אפליקציות. | `pipx install strix-agent` |
| [Graphify](https://github.com/Graphify-Labs/graphify) | סקיל לסוכני קוד שבונה "גרף ידע" מהקוד/מסמכים להבנה מהירה של פרויקט. | `pip install graphifyy` |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | פריימוורק ליצירת וידאו מ-HTML, בנוי לסוכני AI. | `npx skills add heygen-com/hyperframes` |
| [Aider](https://github.com/Aider-AI/aider) | AI Pair Programmer שעובד מול codebase קיים, Git, טסטים ו-linters. | `pip install aider-chat` |
| [Crush](https://github.com/charmbracelet/crush) | סוכן קוד לטרמינל (מבית Charm), חלופה מודרנית ל-CLI coding agents. | brew / npm / winget |
| [Playwright](https://github.com/microsoft/playwright) | פריימוורק אוטומציה ובדיקות דפדפן (שימושי גם ל-agents). | npm / pip / .NET / Java |

---

## ⭐ מאיפה להתחיל / Recommended Starting Stack

אם רוצים להתחיל מקבוצה קטנה עם החזר עסקי גבוה:

| עדיפות | Repo | למה |
|:---:|---|---|
| ⭐⭐⭐⭐⭐ | **n8n** | שכבת האוטומציה המרכזית כמעט לכל תהליך בארגון. |
| ⭐⭐⭐⭐⭐ | **Dify** | בניית אפליקציות/סוכני AI גם לצוותים שאינם מפתחים. |
| ⭐⭐⭐⭐⭐ | **Docmost / Outline** | בסיס ידע ארגוני, נהלים ו-Client Knowledge. |
| ⭐⭐⭐⭐⭐ | **Twenty** | בסיס ל-CRM/מכירות פנימי או מותאם. |
| ⭐⭐⭐⭐ | **Qdrant + Firecrawl** | תשתית RAG ו-Web Intelligence למחקר ולסוכנים. |
| ⭐⭐⭐⭐ | **LibreChat / AnythingLLM** | ממשק AI ארגוני מאובטח מעל המודלים שלכם. |
| ⭐⭐⭐⭐ | **Presenton** | מצגות ותוצרים ללקוחות באופן אוטומטי. |
| ⭐⭐⭐⭐ | **Postiz + Cap** | תוכן לרשתות, הדרכות ו-Client Updates. |

---

## 📝 צ'קליסט הערכה לפני אימוץ / Evaluation Checklist

לפני הכנסת ריפו כלשהו לסביבה ארגונית, כדאי לבדוק:

1. **רישיון (License)** — שימוש מסחרי והתאמות. שים לב במיוחד ל-**AGPL / BSL / Fair-Code** (למשל n8n, Firecrawl, AFFiNE, Cap, Postiz ב-AGPL).
2. **אבטחה** — Security Policy, CVEs, סיכוני dependencies ו-Supply Chain.
3. **Data Residency** — האם ניתן להריץ On-Prem / Private Cloud (רלוונטי מאוד לנתוני לקוחות בייעוץ).
4. **אימות והרשאות** — SSO / SAML / OAuth / RBAC.
5. **Extensibility** — APIs, Webhooks, Plugins, MCP.
6. **תחזוקה** — פעילות הריפו, releases, contributors וקהילה.
7. **מורכבות תפעולית** — כמה תשתית נדרשת בפועל להרצה ותחזוקה.

---

### הערות / Notes

**¹ החלטות גבוליות (Platforms):** ל-**n8n** ול-**Firecrawl** קיימת גם התקנה מהירה (npm/SDK), אך הן בטבלה הראשית כי הפריסה הארגונית שלהן היא שרת בניהול עצמי (Docker/Clone); ה-npm/SDK הם רק ה-quickstart או ה-client. אותו היגיון תקף ל-Excalidraw ול-AnythingLLM.

**מהרשימה המקורית שלך שהועברו ל-Quick-Install:** `strix` (pipx), `graphify` (pip) ו-`hyperframes` (npx/npm) — ניתנים להתקנה מהירה ולכן לפי הכלל שלך אינם בטבלאות הראשיות, אבל הושארו למטה עם לינק ותיאור.

**מהקטלוג הנוסף שצירפת** נוספו לרשימה הראשית (עומדים בקריטריון clone/self-host): **Memos, EspoCRM, Keila**. פריטים משם שנשארו ב-Quick-Install כי הם package-first: **Aider** (pip), **Crush** (brew/npm), **Playwright** (npm/pip), וכן **Cline / Roo Code** (תוספי IDE) ו-**Continue** (archived) — לא נכללו.

**החלפה:** `openai/whisper` (pip) הוחלף ב-`whisper.cpp` (clone/build) בקטגוריית הווידאו/מדיה, כדי לשמור על כלל ה-clone.
