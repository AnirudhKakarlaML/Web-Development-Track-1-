# Web Development Track 1: HTML & CSS

My practice repository for learning web development from scratch, following the **Apna College Delta** course.
Each file practices one concept. The folders are in the order I learned them.

**Status:** HTML fundamentals ✅ complete · CSS fundamentals 🚧 in progress

---

## Repository structure

```text
Web-Development-Track-1-/
├── 01-html-basics/               Page structure, headings, text tags, entities, Emmet
├── 02-block-and-inline/          <div>, <span>, block vs inline elements
├── 03-links-lists-images-media/  Anchors, lists, images, video
├── 04-semantic-html/             <header>, <nav>, <main>, <section>, <footer>
├── 05-tables/                    Tables, <thead>/<tbody>, rowspan & colspan
├── 06-forms/                     Inputs, labels, buttons, checkbox, radio, select, range, textarea
├── 07-css-basics/                One folder per mini page (HTML + its CSS): colors, selectors, pseudo-classes
├── 08-box-model-and-layout/      Box model (height, width, padding, borders, margin), display, % units, then positioning, Flexbox
└── projects/                     Complete pages built from everything above
```

---

## 01 · HTML Basics

| File | What it practices |
|---|---|
| [first-page.html](01-html-basics/first-page.html) | My very first HTML file: paragraphs and headings (started 9 Aug) |
| [boilerplate.html](01-html-basics/boilerplate.html) | Standard boilerplate: `<!DOCTYPE html>`, `<head>`, `<body>` |
| [headings-practice.html](01-html-basics/headings-practice.html) | Headings and paragraphs exercise |
| [text-formatting-tags.html](01-html-basics/text-formatting-tags.html) | `<b>`, `<i>`, `<br>`, comments |
| [html-not-case-sensitive.html](01-html-basics/html-not-case-sensitive.html) | HTML tags are not case sensitive (mini profile page) |
| [html-entities.html](01-html-basics/html-entities.html) | Entities such as `&lt;` and `&gt;` |
| [superscript-subscript.html](01-html-basics/superscript-subscript.html) | `<sup>` and `<sub>` |
| [superscript-subscript-practice.html](01-html-basics/superscript-subscript-practice.html) | Pythagoras theorem and glucose formula |
| [horizontal-rule.html](01-html-basics/horizontal-rule.html) | `<hr>` |
| [emmet-shortcuts.html](01-html-basics/emmet-shortcuts.html) | Emmet abbreviations in VS Code |

## 02 · Block & Inline Elements

| File | What it practices |
|---|---|
| [div.html](02-block-and-inline/div.html) | `<div>` as a block container |
| [span.html](02-block-and-inline/span.html) | `<span>` as an inline container |
| [inline-vs-block.html](02-block-and-inline/inline-vs-block.html) | Inline vs block behaviour |

## 03 · Links, Lists, Images & Media

| File | What it practices |
|---|---|
| [anchor-tags.html](03-links-lists-images-media/anchor-tags.html) | `<a href>` links to other sites |
| [lists-and-attributes.html](03-links-lists-images-media/lists-and-attributes.html) | Ordered and unordered lists with attributes |
| [image.html](03-links-lists-images-media/image.html) | `<img>` with `src` and `alt` |
| [image-practice.html](03-links-lists-images-media/image-practice.html) | Numbered list of fruits with links to their images |
| [video.html](03-links-lists-images-media/video.html) | `<video>` with controls |

## 04 · Semantic HTML

| File | What it practices |
|---|---|
| [semantic-tags.html](04-semantic-html/semantic-tags.html) | `<header>`, `<nav>`, `<main>`, `<footer>` |
| [portfolio-semantic-markup.html](04-semantic-html/portfolio-semantic-markup.html) | A portfolio page built with semantic tags |

## 05 · Tables

| File | What it practices |
|---|---|
| [tables.html](05-tables/tables.html) | `<table>`, `<tr>`, `<th>`, `<td>`, `<caption>` |
| [table-semantics.html](05-tables/table-semantics.html) | `<thead>` and `<tbody>` |
| [rowspan-colspan.html](05-tables/rowspan-colspan.html) | Merging cells with `rowspan` and `colspan` |

## 06 · Forms

| File | What it practices |
|---|---|
| [form-inputs.html](06-forms/form-inputs.html) | Text, password, number, time and color inputs |
| [labels-and-placeholders.html](06-forms/labels-and-placeholders.html) | Matching `<label for>` to an input `id`; `placeholder` |
| [signup-and-youtube-search.html](06-forms/signup-and-youtube-search.html) | Sign-up form, plus a form that searches YouTube |
| [google-search-form.html](06-forms/google-search-form.html) | A form that sends a search request to Google |
| [buttons.html](06-forms/buttons.html) | Default, `type="button"` and `type="reset"` buttons |
| [checkbox.html](06-forms/checkbox.html) | Checkboxes |
| [radio-buttons.html](06-forms/radio-buttons.html) | Grouping radio buttons with `name` |
| [dropdown.html](06-forms/dropdown.html) | `<select>` and `<option>` |
| [range.html](06-forms/range.html) | Range slider |
| [textarea.html](06-forms/textarea.html) | `<textarea>` |

## 07 · CSS Basics

Each folder is a small page with its own `index.html` and `style.css`.

| Folder | What it practices |
|---|---|
| [tech-club/](07-css-basics/tech-club/) | Linking an external stylesheet; styling headings, paragraphs and links; font size, weight, alignment, letter spacing, line height |
| [logo/](07-css-basics/logo/) | Text logo ("apna college"): HEX colors, font family, text transform |
| [help-card/](07-css-basics/help-card/) | Element selectors; `color` and `background-color` |
| [rgb-hex-colors/](07-css-basics/rgb-hex-colors/) | RGB and HEX color values |
| [developer-profile/](07-css-basics/developer-profile/) | A developer profile card using everything learned so far |
| [focus-mode/](07-css-basics/focus-mode/) | A full practice page: colors, fonts, spacing, text decoration and links |
| [selectors/](07-css-basics/selectors/) | Quora-style page: universal (`*`), element, grouped (`h1,h3`), id (`#login`) and class (`.follow`) selectors |
| [selectors/PracticeQs.html](07-css-basics/selectors/PracticeQs.html) | Practice: Facebook-style header styled with id (`#searchbtn`) and class (`.userbtn`) selectors (uses `style1.css`) |
| [selectors/selectorstype.html](07-css-basics/selectors/selectorstype.html) | Combinators and attribute selectors: descendant (`p a`), sibling (`p+h3`), child (`span>button`), attribute (`input[type="text"]`), plus `:nth-of-type()` (uses `selectorstype.css`) |
| [selectors/pseudoclass.html](07-css-basics/selectors/pseudoclass.html) | Pseudo-classes: `:hover`, `:active`, and `:checked` on radio buttons (uses `pseudoclass.css`) |
| [selectors/studentdashboard.html](07-css-basics/selectors/studentdashboard.html) | **Mini project: Student Dashboard.** Combines id, class, child (`.card > h2`), adjacent (`h2+p`) and general sibling (`h2~p`) selectors with `:hover`, `:active`, `:first-child`, `:last-child` and `:nth-of-type()` |
| [selectors/pseudoelement.html](07-css-basics/selectors/pseudoelement.html) | Pseudo-elements (`::first-letter`, `::first-line`, `::selection`) and **cascade & specificity**: same-specificity rules (last one wins, even across two stylesheets), inline style, and `!important` (uses `pseudoelement.css` + `pseudoelement1.css`) |
| [css-part2-test/](07-css-basics/css-part2-test/) | **CSS Part 2 test: Developer Dashboard.** Element, grouped, descendant (`.task p`), adjacent (`h3+p`) and general sibling (`#tasks h2~article`) selectors |
| [study-portal/](07-css-basics/study-portal/) | **Mini project: Student Study Portal.** All selectors together: id, class, child, adjacent and general sibling, attribute (`[data-status="active"]`, `input[type="email"]`, `a[href^="https"]`), pseudo-classes (`:hover`, `:focus`, `:checked`, `:disabled`, `:first-child`, `:last-child`) and pseudo-elements (`::before`, `::first-letter`) |
| [inheritance/](07-css-basics/inheritance/) | **Inheritance:** forcing form controls (`input`, `button`) to take their parent's background with `inherit` (uses `inheritance.css`) |

## 08 · Box Model & Layout

| Folder | What it practices |
|---|---|
| [borders-and-padding/](08-box-model-and-layout/borders-and-padding/) | `height`/`width`, padding (per side and shorthand with 1–4 values), borders (`border-width`/`style`/`color`, `border` shorthand, per-side borders) and `border-radius` |
| [margin/](08-box-model-and-layout/margin/) | Margin with 1–4 values, revising padding and border shorthands (uses `margin.css`) |
| [display-inline-block/](08-box-model-and-layout/display-inline-block/) | `display`: `inline` vs `block` vs `inline-block`; why height, width and vertical padding/margin don't apply to inline elements (uses `inlineblock.css`) |
| [percentage-units/](08-box-model-and-layout/percentage-units/) | `%` units: width and margin as a percentage of the parent (uses `percentageunit.css`) |
| [traffic-light/](08-box-model-and-layout/traffic-light/) | **Mini project: Traffic Light.** Nested boxes with margin and `border-radius: 50%` circles (uses `trafficlight.css`) |

---

## Projects

| Project | Description |
|---|---|
| [html-portfolio](projects/html-portfolio/) | **HTML-only portfolio.** Header and navigation, About, Skills, Education table, Projects, course registration form and Contact. Uses semantic tags, internal links with IDs, forms and `mailto:` links. |
| [portfolio-first-draft.html](projects/portfolio-first-draft.html) | My first attempt at a personal page, made before the full portfolio |

---

## Progress log

- **Aug:** Started web development. Covered HTML structure, headings, paragraphs, lists, links and images.
- **Early Sep:** Block/inline elements, entities, Emmet, semantic HTML, video.
- **Sep (tables & forms):** Tables with `rowspan`/`colspan`, all main form inputs, labels and placeholders.
- **Sep 23:** Checkbox, radio, range, select, textarea. Finished the **HTML-only portfolio** project. HTML fundamentals complete.
- **Sep 24 onwards:** CSS fundamentals. External stylesheets, selectors, named/RGB/HEX colors, typography properties.
- **Oct 1:** CSS Part 2 done: combinators, attribute selectors, pseudo-classes, pseudo-elements, specificity. Built the **CSS Part 2 test** and the **Student Study Portal** mini project.
- **Oct 2:** Inheritance (`inherit`) and the start of the box model: height, width, padding, borders and border-radius.
- **Oct 3:** Margin, `display` (inline / block / inline-block) and percentage units. Built the **Traffic Light** mini project.

## Learning approach

1. Learn one concept.
2. Write the code myself in a separate practice file.
3. Combine concepts into a complete project.

## Next up

- [x] CSS box model: height, width, padding, borders, margin
- [x] Display: inline, block, inline-block
- [ ] Units (em, rem, vh, vw), positioning and Flexbox
- [ ] Style the HTML portfolio with CSS
- [ ] JavaScript fundamentals
