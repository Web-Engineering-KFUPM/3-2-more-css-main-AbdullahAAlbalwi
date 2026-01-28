# 3-2-More-CSS-main — Feedback

## Submission

- **Lab:** 3-2-More-CSS-main
- **Deadline (Riyadh / UTC+03:00):** 2026-01-28T23:59:00+03:00
- **Last commit time (from git log):** 2026-01-28T12:34:58+03:00
- **Submission marks:** **20/20** (On time)


## Files Checked

- HTML: ✅ D:\NotSortedYet\New folder\3-2-more-css-main-AbdullahAAlbalwi\index.html
- CSS: ✅ D:\NotSortedYet\New folder\3-2-more-css-main-AbdullahAAlbalwi\styles.css

---

## TODO-by-TODO Feedback

### TODO 0: HTML links styles.css in <head> — **6/6**

**Checklist**
- ✅ Has <head> section
- ✅ Has <link rel="stylesheet" href="styles.css"> (or "./styles.css") inside <head>

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 1: :root variables + global box-sizing reset (*) — **14/14**

**Checklist**
- ✅ Has :root { ... } (or html { ... }) rule for CSS variables
- ✅ Defines --brand: #2563eb
- ✅ Defines --brand-dark: #1d4ed8
- ✅ Has * (or *, *::before, *::after) rule for global reset
- ✅ Global reset sets box-sizing: border-box

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 2: Header/Footer background + .tagline muted — **8/8**

**Checklist**
- ✅ Has .site-header and .site-footer rule(s)
- ✅ .site-header/.site-footer background uses var(--card) (background or background-color)
- ✅ Has .tagline { ... } rule
- ✅ .tagline color uses var(--muted)

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 3: .color-demo notes + .bg-sample block styling — **16/16**

**Checklist**
- ✅ Has .color-demo .color-note { ... } rule
- ✅ .color-note sets color: var(--brand)
- ✅ .color-note sets font-weight to bold/600+
- ✅ Has .color-demo .muted { ... } rule
- ✅ .muted sets color: var(--muted)
- ✅ .muted sets font-size around 0.95rem (accept 0.9–1rem or close px)
- ✅ Has .bg-sample { ... } rule
- ✅ .bg-sample sets width: 100%
- ✅ .bg-sample sets min-height >= 80px
- ✅ .bg-sample sets padding around 0.75rem (or 12px)
- ✅ .bg-sample sets margin-block around 0.75rem (or margin-top/bottom)
- ✅ .bg-sample sets a border-radius (any value)
- ✅ .bg-sample sets text color to white (#fff/white)
- ✅ .bg-sample sets linear-gradient background including var(--brand)

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 4: Inline labels (.inline-label, .inline-label.alt) — **10/10**

**Checklist**
- ✅ Has .inline-label { ... } rule
- ✅ .inline-label sets display to inline-block (or inline-flex)
- ✅ .inline-label sets padding: 0.25rem 0.5rem (or close px)
- ✅ .inline-label sets a 1px solid border with rgba(0,0,0,0.18) (or border-color)
- ✅ Has .inline-label.alt { ... } rule
- ✅ .inline-label.alt uses a different border style (e.g., dashed)

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 5: Typography for .copy .title and .copy .intro — **10/10**

**Checklist**
- ✅ Has .copy .title { ... } rule
- ✅ .copy .title sets font-size using rem
- ✅ .copy .title sets font-weight 600–700 (or bold)
- ✅ .copy .title sets text-transform: capitalize
- ✅ Has .copy .intro { ... } rule
- ✅ .copy .intro sets font-style: italic
- ✅ .copy .intro increases line-height (>= 1.6)
- ✅ .copy .intro sets margin-top: 0.25rem (or 4px)

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 6: Flex toolbar/buttons + product grid/items — **12/12**

**Checklist**
- ✅ Has .toolbar { ... } rule
- ✅ .toolbar uses display:flex (or inline-flex)
- ✅ .toolbar uses justify-content: space-between
- ✅ .toolbar uses align-items: center
- ✅ .toolbar has a gap
- ✅ Has .btn { ... } rule
- ✅ .btn sets padding
- ✅ .btn removes border (border: none or 0)
- ✅ Has .btn:hover { ... } rule for hover feedback
- ✅ Has .product-grid { ... } rule
- ✅ .product-grid sets display:flex
- ✅ .product-grid sets flex-wrap: wrap
- ✅ .product-grid sets gap: 0.75rem (or 12px)
- ✅ .product-grid sets margin-top: 0.75rem (or 12px)
- ✅ Has .product-grid .item { ... } rule
- ✅ .item flexible sizing (flex: 1 1 140px OR grow/shrink/basis OR min-width:140px)
- ✅ .item sets min-height >= 90px
- ✅ .item sets a soft background
- ✅ .item sets border-radius (any value)
- ✅ .item centers content using flexbox
- ✅ .item sets font-weight 700 (or bold)

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 7: .static-box visibility styling — **4/4**

**Checklist**
- ✅ Has .static-box { ... } rule
- ✅ .static-box sets padding: 0.5rem 0.75rem (or close px)
- ✅ .static-box sets border-radius: 10px
- ✅ .static-box sets background rgba(0,0,0,0.05)
- ✅ .static-box sets margin-bottom: 0.5rem

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- HTML comments are ignored (examples in comments do NOT count).
- CSS comments are ignored (examples in comments do NOT count).
- Checks are intentionally light: they look for key selectors and the presence of key properties.
- CSS rules can be in ANY order, and repeated selectors/properties are allowed.
- Accepted alternatives include:
  - `background` or `background-color`
  - `white` or `#fff` or `#ffffff`
  - `inline-block` or `inline-flex` where appropriate
  - spacing: `0.75rem` ~ `12px`, `0.5rem` ~ `8px`, `0.25rem` ~ `4px`
  - `margin-block` may be replaced by `margin-top` and `margin-bottom`
- Missing required items reduce marks proportionally within that TODO.
