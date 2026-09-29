# Moonlit Notes — Desktop Layout Guide

## 1. Design direction

Moonlit Notes adalah aplikasi personal journaling dan productivity dengan mood dreamy, warm, dan sedikit fairy-like. Tujuan desain adalah membuat pengguna merasa tenang, aman, dan pribadi saat menulis diary serta mengelola tugas.

Visual direction:
- background: warm dark plum / charcoal
- aksen warna: lavender dan warm gold
- typography: serif untuk headline, sans-serif untuk UI, dan serif/italic untuk accent
- mood: serene, cozy, dreamy, intimate
- layout: dashboard yang ramah, tidak terlalu penuh, dengan banyak ruang bernapas

## 2. Color palette

### Core colors
- background: #1D1E22
- card/panel: #2C2F36
- accent: #B68FBF
- accent/soft: #D9C5E7
- gold: #DAB86F
- golden highlight: #F0D99D
- text primary: #F3F3F3
- text secondary: #DADADA
- border: rgba(255,255,255,0.08)

### Usage
- background untuk ruang utama
- card untuk panel
- accent lavender untuk tombol utama
- gold untuk highlight, timer, mood, statistik kecil
- text utama putih/light gray agar nyaman dibaca

## 3. Typography system

### Font pairing
- Logo: Libre Baskerville, 32px
- Headline: Cormorant Garamond, 48–52px
- UI/menu: Inter, 16px
- Body text: Inter, 16px
- Diary text: Lora, 18–20px
- Button text: Inter SemiBold, 16px
- Accent quote: Caveat, 22px

### Type scale
- H1 / display: 48–52px
- H2 / section title: 32px
- H3 / card title: 24px
- Body: 16px
- Small label: 12–14px
- Button: 16px
- logo: 32px

## 4. Desktop layout structure

### Overall canvas
- width: 1440px
- height: 900px
- background: dark charcoal
- border radius: 18–20px

### Main app shell
- left sidebar: 260px width
- top bar: 72px height
- main content area: flexible

## 5. Sidebar design

### Sidebar size
- width: 260px
- background: dark charcoal
- border-right: 1px solid rgba(255,255,255,0.06)

### Sidebar items
- brand/logo at top left
- nav items vertically stacked
- active nav item with highlight background
- secondary text below for mini info

### Sidebar structure
1. Brand area
   - Logo: Moonlit Notes
   - small icon / moonmark at far left
2. Menu list
   - Moonroom
   - Diary
   - Little Notes
   - Little Plans
   - Moon Focus
   - Agenda
3. Quick stats panel
   - small card under menu
   - label: “2 free pages left”
   - secondary text

### Sidebar visual style
- padding left/right: 20px
- item height: 42px
- active item: lilac-ish background with lighter border
- label font: Inter 16px

## 6. Top bar design

### Top bar size
- height: 72px
- background: dark charcoal
- border bottom: 1px solid rgba(255,255,255,0.06)

### Top bar contents
- left: current page title or section label
- center: maybe search or slim status bar
- right: user avatar and action button

### Example top bar
- left: “Moonroom” or “Diary”
- right: avatar bubble + quick action button

## 7. Main content layout

### Layout grid
Use a 12-column grid with generous gutters.
- gutter: 24px
- card padding: 24px
- card radius: 18px

### Main content sections
- hero / dashboard summary at top
- quick cards row below
- journal card or diary preview
- focus summary card
- tasks + notes list

## 8. Page 1 — Moonroom dashboard

### Layout
- left main content area (large cards)
- right sidebar or secondary panel

### Section arrangement
1. top hero summary card
   - greeting text: “Good evening, little dreamer.”
   - accent font: Caveat, 22px
   - larger heading: Cormorant Garamond, 48px
2. quick stats row
   - cards for diary count, focus hours, tasks done, streak
3. diary preview card
   - large card with title and excerpt
4. note/task mini panel
   - list grouped by category
5. right panel
   - agenda list, mood summary, or upcoming focus timer

### Example sizing
- hero card: 700 x 220
- stats card: 220 x 120
- diary preview: 700 x 240
- side panel: 300 x 420

### Dashboard text example
- heading: “A quiet evening, little dreamer.”
- accent line: “Write your story before sleep.”
- buttons: “Open Diary”, “New Entry”, “View Plans”

## 9. Page 2 — Diary page

### Layout
- main content: diary book area, centered
- right or below: journal controls / mood + tags

### Diary structure
- book cover at top center or left aligned
- large area resembling book spread
- title field on top
- text editor with soft background
- mood selector below or on side
- toolbar on top of editor

### Diary book visual
- shape: rounded rectangle with subtle depth
- background: warm ivory or soft gray
- text color: dark charcoal
- page flip effect folded corners or soft hover shadow

### Diary controls panel
- mood chips
- font dropdown
- font size buttons
- save button
- delete button

### Suggested sizes
- book area: 820 x 620
- editor: 700 x 480
- sidebar control panel: 260 x 620

## 10. Page 3 — Little Notes

### Layout
- grid of note cards
- each card includes title, short text, timestamps
- pin icon on selected notes
- search field at top

### Card sizes
- width: 220–260px
- height: 180–220px
- radius: 18px
- padding: 18px

### Notes style
- warm muted colors
- small highlight badges
- sticky note look with shadows

## 11. Page 4 — Little Plans

### Layout
- top bar with filters: today, upcoming, completed
- task list with priority markers
- to-do item rows with checkbox and due date

### Item UI
- height: 54px
- left: checkbox circle
- middle: task title + category
- right: due date or priority color dot

## 12. Page 5 — Moon Focus

### Layout
- large timer centered
- circular progress indicator or countdown ring
- controls below: start, pause, reset
- task selection panel on side
- session history list under controls

### Timer style
- big number: 25:00 or 00:25:00
- accent gold for active countdown
- button group in lavender or muted tone

## 13. Page 6 — Agenda

### Layout
- weekly calendar style or simple list view
- event cards with date/time and category
- right panel for event details

### Event card style
- rounded rectangle
- time at left or top
- title and tags via small labels

## 14. Spacing system

Use a consistent spacing scale:
- 4px
- 8px
- 12px
- 16px
- 20px
- 24px
- 32px
- 40px
- 48px
- 64px

### Card padding
- small card: 16px
- medium card: 20px
- large card: 24px

## 15. Components guide

### Buttons
- primary: lavender background, white text
- secondary: soft muted gray or transparent
- hover: slightly darker lavender shade
- border radius: 14px
- padding: 12px 20px

### Cards
- background: dark panel
- border radius: 18px
- subtle shadow
- border: 1px solid transparent or low opacity

### Inputs
- border radius: 12px
- background: dark neutral
- border: 1px solid rgba(255,255,255,0.08)
- padding: 12px 14px

### Avatars or icons
- circular, 32–40px
- warm accent or neutral

## 16. Layout recommendation for Figma

### Frame naming
- Moonroom
- Diary
- Little Notes
- Little Plans
- Moon Focus
- Agenda
- Design System

### Suggested Figma structure
- Page 1: Moonroom
- Page 2: Diary
- Page 3: Little Notes
- Page 4: Little Plans
- Page 5: Moon Focus
- Page 6: Agenda
- Page 7: Design System

## 17. Keputusan penting

- Diary adalah fitur utama; jadikan desainnya paling menonjol
- Moonroom adalah halaman pertama yang paling penting untuk landing dashboard
- tombol utama tetap berwarna lavender
- 60–70% UI tetap dark dan clean, 30–40% aksen dreamy dipakai di quote, highlight, dan halaman diary
- jangan terlalu banyak dekorasi; cukup soft glow, pencahayaan, dan bayangan lembut

## 18. Next step

Setelah file ini siap, langkah berikutnya adalah:
1. buat wireframe di Figma untuk Moonroom
2. buat wireframe untuk Diary
3. buat Design System palette + typography
4. baru mulai coding frontend

Bila kamu mau, langkah berikutnya adalah aku bantu buatkan:
- wireframe Moonroom yang detail dan siap diterjemahkan ke Figma
- wireframe Diary yang detail
- struktur komponen untuk `Sidebar`, `Button`, `Card`, `Input`, dan `DiaryBook`.
