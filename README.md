# Stitch UI Design Guide

Two practical, bilingual (English / Arabic) guides for designing app interfaces with **Google Stitch**, the AI tool that turns text descriptions into UI screens.

They cover how Stitch actually works (one screen at a time), how to write prompts that give predictable results, and how to keep a whole app visually consistent. Everything is written from hands-on experiments with Stitch.

> **Not affiliated with Google.** Stitch is a Google product. These guides are independent, unofficial notes. Stitch changes quickly, so check the [official documentation](https://stitch.withgoogle.com/docs) for the latest behavior.

---

## What's in this repository

| File | Pages | What it is |
|---|---|---|
| [`Stitch_UI_Design_Guide.pdf`](./Stitch_UI_Design_Guide.pdf) | 27 | The full guide: how Stitch works, prompt methods and templates, design-system consistency, and worked experiments. |
| [`Stitch_Prompt_Guide.pdf`](./Stitch_Prompt_Guide.pdf) | 11 | A short quick reference: the prompts you reach for most often, with examples. |

**Suggested order:** read the quick reference first (about 10 minutes), then use the full guide when you want to build a complete app.

---

## Stitch UI Design Guide (27 pages)

1. **Introduction**: what Stitch is and how to start
2. **How Stitch works**: the screen-by-screen model
3. **Building a full app**: from the first screen to a complete flow
4. **The engineering prompt**: a structured way to describe screens
5. **Practical prompt templates**: ready-to-adapt prompts
6. **Design system and consistency**: colors, type and components across screens
7. **Navigation bar consistency**: fixing mismatched bars between screens
8. **Personal experiment #1**: AI Study Copilot
9. **Personal experiment #2**: TravelMate AI
10. **Aether Vault**: a full app designed with Stitch
11. **Advanced design guideline**: a reusable guideline system
12. **Bottom navigation, deep dive**
13. **Sources and references**

## Stitch Prompt Guide (11 pages)

1. **Start your project**: broad idea or specific details, and setting the "vibe"
2. **Refine screen by screen**: one or two changes per prompt
3. **Control the theme**: colors, fonts and borders
4. **Modify images**: general and specific image changes
5. **Change the app language**
6. **Pro tips**
7. **Engineering prompt**
8. **Advanced prompt examples**

---

## A taste of the method

A structured first prompt names the product, the screen, the components, the colors and one word for the feel:

```text
Fitness app for young adults.
Screen: Home.
Components: greeting header, workout card, bottom nav bar.
Colors: dark background #1A1A2E, blue #3A86FF.
Vibe: minimal, motivational.
```

Then refine it one small change at a time, for example: *"On the homepage, add a search bar to the header."* Keeping each prompt to one or two changes is the golden rule in the quick reference.

---

## Who this is for

- Frontend developers and designers who want to prototype interfaces quickly with AI
- Students and beginners who are new to AI-assisted UI design
- Anyone who wants repeatable prompts instead of trial and error

## Sources and credits

The guides were compiled from:

- Stitch's official documentation (stitch.withgoogle.com/docs)
- A community Stitch prompt guide
- My own experiments with Stitch

I prepared them with AI assistance (conversations with Gemini, ChatGPT and Claude) and reviewed the content myself.

## Author

**Rebhe Ibrahim**, Frontend Engineer (React, Next.js, TypeScript)

- Portfolio: <https://rebhe-dev.netlify.app>
- GitHub: <https://github.com/rebhi-2002>
- Email: rebheibrahim@gmail.com

## Copyright

© 2026 Rebhe Ibrahim. All rights reserved, as stated in the documents. You are welcome to read and share the link to this repository; please do not republish the guides as your own.
