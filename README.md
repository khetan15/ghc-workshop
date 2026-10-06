

# THE MASTER TEMPLATE

You are a senior front-end developer and creative designer. Build me a catchy,
dynamic, modern personal portfolio website using my attached resume as the
REFERENCE for content only. Do not recreate the resume's layout or format.
Reinterpret it as an engaging website: turn bullet points into stories,
projects into cards, and skills into visual elements.

## Step 1: Read the resume and extract
From the resume, pull out my name, role/title, summary, skills, experience,
projects, education, certifications, and contact links. Do not invent
anything. If something is missing, such as a photo, a project link or a
metric, leave a clear placeholder like [ADD LINK] and list those at the end.

## Step 2: Design direction
- Vibe: [pick one: bold & futuristic / minimal & elegant / playful & colorful / dark developer-terminal]
- Colors: [e.g. deep navy + electric teal accent, or "you choose to match my field"]
- Audience: [recruiters / clients / hiring managers] in [my field, e.g. software engineering]
- Goal: [get interviews / land freelance clients / personal branding]
- Light and dark mode toggle, with the dark theme as default

## Step 3: Required sections
1. Hero: my name, an animated typing effect cycling through my roles, a
   one-line value proposition, and "View Work" and "Download Resume" buttons
2. About: a short, personable rewrite of my summary, with a few quick-fact
   highlights
3. Skills: visual categories with animated progress bars or tag chips
   (no boring bullet lists)
4. Experience: an interactive vertical timeline, with details revealed on
   click or hover
5. Projects: a card grid with hover effects, tech tags, and a category
   filter. Each card opens a modal with details.
6. Education & certifications: compact and clean
7. Contact: a working-looking form (mailto-based is fine), my social links,
   and a copy-email-to-clipboard button
8. Footer with a "back to top" button

## Step 4: Dynamic and catchy features
- Smooth scroll-triggered reveal animations (IntersectionObserver)
- Animated counters for key stats from my resume (years of experience,
  projects, and so on, only if the data exists)
- A subtle animated background (particles, gradient mesh or floating shapes)
  that doesn't hurt performance
- Custom cursor glow or hover micro-interactions
- Sticky navbar with scroll-spy highlighting and a mobile hamburger menu
- Scroll progress bar
- Respect prefers-reduced-motion

## Technical constraints (important)
- Deliver ONE single self-contained file: index.html with inline CSS and
  vanilla JavaScript. No frameworks, no build tools, no npm.
- External resources allowed only via CDN (Google Fonts, Font Awesome or
  Lucide icons). Everything else must work offline.
- Fully responsive (mobile-first), accessible (semantic HTML, alt text,
  keyboard navigation, good contrast), and SEO-ready (title, meta
  description, Open Graph tags).
- Clean, commented code, with CSS variables for easy color changes.
- Put all my personal content in one JavaScript data object at the top of the
  script, so I can edit text without touching the layout.

## Output format
1. Show a short summary (5 lines max) of what you extracted from my resume
   and the design choices you made.
2. Give the complete code in one code block.
3. List the placeholders I need to fill in.
4. Give 3 short steps for how to run it (save as index.html, open in the
   browser) and how to publish it free (GitHub Pages / Netlify Drop).

If the code would be too long for one response, split it into clearly labeled
parts and tell me to reply "continue". Prioritize a complete, working file
over extra features.


# ITERATION PROMPT

- Polish: "Make the hero section more eye-catching and improve the animations. Return only the changed code sections."
- Content: "Rewrite my About and project descriptions to sound confident and human, not corporate."
- Fixes: "On mobile the navbar overlaps the hero. Fix it and show only the changed code."
- Extras: "Add a testimonials section and a blog/articles preview."

