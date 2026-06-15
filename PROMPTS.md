# AI Prompts Used - Sprint 12 Library Kiosk Project

i tried to build most of this myself by referring to MDN docs and my previous sprint notes. only went to AI when i was genuinely stuck on something specific.

---

## Prompt 1

**what i asked:**
"what is the exact syntax for localStorage.getItem and how to parse it"

**why i asked:**
i knew localStorage existed and i had seen it before but i kept getting null when i tried to read the data. wasnt sure if i had to parse it manually or if it came back as an object already.

**what i used from it:**
just the JSON.parse part. the rest of the DOMContentLoaded and array setup i wrote myself.

---

## Prompt 2

**what i asked:**
"does e.preventDefault() stop the page from refreshing on form submit"

**why i asked:**
i added the submit listener myself but the page kept reloading and clearing everything. i had a feeling it was something small i was missing. just wanted to confirm.

**what i used from it:**
just confirmed my understanding. one line fix.

---

## Prompt 3

**what i asked:**
"how does event delegation work on a tbody"

**why i asked:**
i tried adding onclick directly to the delete buttons but it wasnt working because the rows are added dynamically after page load. i remembered from class that there was a way to listen on the parent element but i forgot the exact approach.

**what i used from it:**
the concept of listening on the parent and checking e.target. i wrote the actual filter and re-render logic myself.

---

## overall

most of the HTML structure, the CSS styling, the renderTable function and the localStorage save logic i figured out myself by trial and error and checking MDN. AI was only useful for the 3 specific things above where i was going in circles.

