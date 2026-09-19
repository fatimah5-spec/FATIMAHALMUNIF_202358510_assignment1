# AI Usage Report

## Tools Used & Use Cases

**Claude (Anthropic)** was the primary AI tool used for this assignment.

- **Code generation** — Asked Claude to scaffold the initial project structure (HTML sections,
  CSS layout system, and JavaScript interactivity) following the assignment's required folder
  structure and content sections (About, Projects, Contact).
- **Documentation support** — Used Claude to draft the initial `README.md`,
  `technical-documentation.md`, and this AI usage report, which I then reviewed and edited.
- **UI/UX suggestions** — Asked for suggestions on responsive breakpoints, an accessible
  dark/light theme toggle pattern, and a simple client-side form validation approach.

> ✏️ **Personalize this section:** add the actual prompts/conversations you had, any other tools
> you used (e.g. GitHub Copilot for autocomplete, ChatGPT for debugging a specific error), and
> how each one specifically helped.

## Recommended AI Tools (from assignment brief)

- GitHub Copilot → Code completion & generation
- ChatGPT / Claude → Problem-solving & explanations
- Cursor → AI-powered code editor
- Replit → AI-assisted online IDE
- AWS CodeWhisperer → AI code generation

## Benefits & Challenges

**Benefits:**
- Got a working, responsive scaffold in place quickly, which left more time to focus on content
  and personalization rather than boilerplate setup.
- Helped surface patterns I hadn't used before (CSS custom properties for theming, `matchMedia`
  for OS theme detection, `aria-live` for accessible form feedback).

**Challenges:**
- AI-generated placeholder content (bio, project descriptions) needed to be replaced with real,
  accurate information about myself and my actual projects — it does not know these details.
- Had to double-check generated CSS breakpoints and JavaScript logic against real devices/DevTools
  to confirm the responsive behavior actually worked as intended.

> ✏️ **Personalize this section** with the specific difficulties or limitations *you*
> encountered while using AI tools on this assignment.

## Learning Outcomes

Working through this assignment with AI assistance helped reinforce:
- How CSS Grid and Flexbox combine to build a responsive, multi-section layout.
- How to structure vanilla JavaScript around `DOMContentLoaded` and keep feature code organized
  and commented.
- The importance of reviewing AI-generated code line by line rather than accepting it as-is,
  especially around accessibility (`alt` text, `aria-live`, focus states) and correctness (form
  validation logic).

> ✏️ **Personalize this section** with what *you* specifically learned — new concepts, tools, or
> workflow habits from this assignment.

## Responsible Use & Modifications

All AI-generated code and text in this repository was reviewed before being kept. Placeholder
content (name, bio, project descriptions, contact links, images) is clearly marked with
`✏️ edit-note` callouts in the site itself and TODO-style notes in this documentation, and is
being replaced with my own original content and understanding before submission. I did not
copy code from classmates or submit AI output unmodified — the structure, styling choices, and
content were reviewed, tested in the browser, and adjusted to reflect my own understanding of how
each piece works.
