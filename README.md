# Vibrant Academy SS2 — HTML & CSS Teaching Edition

A **beginner-friendly, no-JavaScript** version of the Vibrant Academy SS2 class website. The goal is to learn how real HTML and CSS work by building one class yearbook together.

## What is included?
- `index.html` — original green-and-yellow class homepage, with rectangular student cards written as HTML.
- `style.css` — all page styles, including responsive layouts and circular biography photos.
- `story-jordan-a.html` and five other `story-*.html` files — individual story pages with circular portraits and magazine-style flowing biographies.
- `LESSON_PLAN.md` — an approachable classroom plan and group activities.

**There is no Bootstrap, JavaScript, backend, or database.** The student directory is written directly in the HTML. The former live search box is replaced with a directory label because live filtering needs scripting or a backend. On mobile, a native HTML `<details>` menu replaces JavaScript.

## How to run it
1. Download the repository (Code → Download ZIP), or clone it.
2. Open `index.html` directly in Chrome or another browser.
3. Click a classmate's **Read My Story** link to open a separate biography page.
4. Edit the page in VS Code, save, and refresh your browser to see your changes.

## Your first HTML edits
1. In `index.html`, find one `<article class="student-card">` block.
2. Replace the example student's name, role, hobby, and short quote.
3. Change the link to the corresponding `story-....html` file.
4. Open that story file and update the `<h1>`, `<p>`, and photo.
5. To use a photo, create an `images` folder, add an approved image file, and replace the initials placeholder with `<img src="images/name.jpg" alt="Portrait of Name">`.
6. Try changing colors and padding in `style.css`.

## Five group roles
- Design: layout sketches, typography, palette.
- Development: edit the HTML and CSS.
- Photography: organize permission-approved photographs.
- Writing: biographies and text.
- Testing/Presentation: test links, mobile sizes, check privacy and demonstrate the result.

## Safety
Only use student photographs and identifying details after appropriate school and parent/guardian permission. Keep the project private until cleared for publication.

## Relationship to the original website
This teaching edition was generated from the full-featured class showcase and keeps its basic design. The original `main` branch is unchanged. This edition is intentionally manual; a student portal and backend can be added in a later phase.
