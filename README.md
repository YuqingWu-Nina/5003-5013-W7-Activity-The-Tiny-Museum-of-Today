# The Tiny Museum of Today

**Course activity:** Designing the Structure and Style of an Interactive Experience  
**Group members:** Add names here

## Project idea

The Tiny Museum of Today is a small digital gallery for ordinary moments that people may otherwise forget. Instead of asking users to write a long journal entry, the website presents small moments as museum exhibits. A color, sound, object, or short sentence can become something worth keeping.

Our purpose is to make reflection feel light and playful. The project treats everyday details as meaningful without making the user complete a serious or complicated task.

## Live demo

[Open the demo](https://yuqingwu-nina.github.io/5003-5013-W7-Activity-The-Tiny-Museum-of-Today/The%20Tiny%20Museum%20of%20Today.html)

The demo is publicly available through GitHub Pages.

## What the user sees

The page is organized in this order:

1. A title and short introduction explain the museum idea.
2. A curator's note gives the page a warm, gallery-like voice.
3. Category labels show possible exhibit types: colors, sounds, objects, and words.
4. Four sample exhibit cards show how a small moment can be displayed. Each card has an “A closer look” section that can be expanded.
5. A final “New Acquisition” section suggests how a user could add their own exhibit in a future version.

## Design choices

We used a soft paper background, thin borders, gallery labels, and framed artwork to make the page feel like a tiny personal museum. The colors are warm and calm rather than bright or busy. Each exhibit has a different illustrated image so the gallery feels varied while still following one visual system.

We used headings, sections, articles, buttons, labels, and `details` elements to keep the HTML structure clear. Each exhibit is an `article`, so it can be understood as one separate item in the collection.

## Current version: HTML and CSS only

This version does not include JavaScript. The category labels, “Need a prompt?” button, and “Add today's exhibit” button are visual placeholders for future interactions. They help show how the experience could grow, but they do not perform actions in the current static version.

The “A closer look” sections use the built-in HTML `details` element, so visitors can open and close them without JavaScript.

## Future interaction ideas

In a later JavaScript version, a visitor could:

- Select a category to filter the visible exhibits.
- Click “Need a prompt?” to receive a small reflection question.
- Add a title, category, short label, and optional image for a new exhibit.

For example, a user could add an exhibit called “Blue at 6:14 PM” and describe it as “the library window.”

## Files

```text
The Tiny Museum of Today/
├── The Tiny Museum of Today.html  # structure and content
├── The Tiny Museum of Today.css   # layout, colors, and exhibit artwork
└── README.md                      # project documentation
```

## How to view locally

Open `The Tiny Museum of Today.html` in a browser. No installation, framework, or JavaScript is needed.

## AI learning and reflection

We used AI as a brainstorming and design-support tool. We first explored ideas that were practical but still playful, then chose the museum concept because it gave the user a clear purpose: save one ordinary moment from the day.

AI helped us turn the concept into a page structure and suggest visual directions such as exhibit cards, paper textures, labels, and gallery framing. We kept the idea small and changed the first version into a static HTML/CSS page because the assignment focuses on structure and style. This helped us focus on hierarchy, spacing, semantic HTML, and the user journey before adding functionality.

## Limitations

The current page uses example exhibits only. It does not save personal entries, accept real images, or filter categories yet. Those are future possibilities rather than completed features.
