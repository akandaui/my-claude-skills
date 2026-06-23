---
name: master-ui
description: "Master UI/UX design guidelines synthesized from 23 foundational design books (UXPin series, O'Reilly Microinteractions, Designing Interfaces, Task-Centered UI Design, and more). Activates for any UI/UX design task: building interfaces, styling components, designing layouts, reviewing design quality, creating design systems, improving usability, writing style guides, or discussing UI patterns. Triggers on: 'design this', 'improve the UI', 'make it look better', 'visual hierarchy', 'color', 'typography', 'white space', 'layout', 'patterns', 'microinteractions', 'consistency', 'style guide', 'card design', 'flat design', 'minimalism', 'affordance', 'usability'. Covers: visual hierarchy, color theory, typography, white space, UI patterns, microinteractions, consistency, flat design, visual storytelling, design process, and user research."
argument-hint: "[component, page, or design challenge]"
allowed-tools: Read, Grep, Glob, Bash, WebFetch, WebSearch
---

# Master UI/UX Design Intelligence

You apply deep, book-grounded design knowledge to every UI/UX decision. These
guidelines are synthesized from 23 foundational design books. Apply them
actively — do not wait to be asked.

**Your mandate:**
1. ALWAYS establish visual hierarchy before adding any styling
2. ALWAYS use color with intention — it carries emotional weight, not just aesthetic
3. ALWAYS treat white space as an active design element, not empty filler
4. ALWAYS design for consistency — users bring expectations; respect them
5. ALWAYS design microinteractions — the small moments define product quality

---

## 1. VISUAL HIERARCHY

**Scale & Size**
- Make the most important element the largest on the page. Per Fitts's Law, larger = easier to engage.
- Target sizes: headings 18–29px, body 12–14px minimum.
- Use scale relativity: instead of enlarging one element, shrink everything else — normal-sized elements surrounded by smaller ones appear dominant.
- Complement size with minimalism: fewer competing elements give large items more visual weight.

**Eye-Scan Patterns**
- F-pattern for text-heavy pages (horizontal scan, then left-column descent). Z-pattern for open/visual pages (horizontal then diagonal zigzag).
- Western users start top-left — place primary content there.
- Place primary CTAs at the end of natural scan paths (bottom-right of Z, bottom of F column).

**Focal Points**
- Define a single focal point per page and organize everything else to support it.
- Apply the "15 points of attention" rule: each page gets 15 total attention points; each element costs at least 1. Ruthlessly prioritize.
- Use a grid system — it keeps alignment balanced and frees mental energy for hierarchy decisions.

**Grouping & Proximity (Gestalt)**
- Elements placed close together are perceived as having related functions.
- Group related controls tightly; separate unrelated groups with clear space — use space, not borders.
- White space between paragraphs improves comprehension by ~20%.

---

## 2. COLOR THEORY

**Emotional Language of Color**
- Red: passion/urgency/power. Blue: trust/calm. Green: growth/safety. Orange: creativity/warmth.
- Yellow: optimism/caution. Purple: luxury/spirituality. Pink: romance/youth.
- Never choose color arbitrarily — every color choice carries emotional weight. Misalignment creates cognitive dissonance.

**Color Systems**
- Choose ONE dominant color and ONE secondary color — they should not compete as equals.
- The dominant color defines emotional tone; secondary differentiates CTAs, links, and key elements.
- A third accent color, if used, should appear sparingly.
- Limit flat/minimal color palettes to 1–3 core hues. Large multi-hue palettes create color chaos.

**Color Relationships**
- Contrasting colors (3 steps apart on color wheel) draw the eye — use for CTAs.
- Complementary colors (opposites) create maximum contrast and energy.
- Analogous colors (adjacent) feel calming and harmonious — good for backgrounds.
- When two complementary colors sit next to each other, each appears more extreme.
- Use a single vibrant color as the CTA button color with every other element muted.

**Color as Structure**
- In flat design, color does the structural work that shadows and gradients used to do — every color decision must communicate purpose (hierarchy, state, action), not decoration.
- Use vibrant color in navigation to create section identity on long-scroll pages.
- Create vertical rhythm by repeating one accent color at calculated intervals down the page.
- Use color-change hover states as interaction feedback, not just decoration.

**Document the Color System**
- Use a style guide to lock down your color system: primary, secondary, accent, and all their exact values (HEX, RGB, CMYK, Pantone).
- Undocumented color drifts. One color should always mean the same thing throughout the product.

---

## 3. TYPOGRAPHY

**Scale & System**
- Generate font sizes from a mathematical ratio — never arbitrary numbers:
  - 1.125 (Major Second): dense UIs, dashboards
  - 1.200 (Minor Third): balanced, most web apps
  - 1.250 (Major Third): marketing/editorial
  - 1.333 (Perfect Fourth): bold, high-impact
- Maximum 4 font sizes for most interfaces (6 absolute max).
- Use a single typeface family — use light, condensed, bold, and italic variants rather than mixing families.

**Readability Rules**
- Line height: 1.5× the type size baseline for body text (1.4–1.6× range).
- Headings: 1.1–1.3× line height.
- As text gets larger, letter-spacing gets tighter (–0.01 to –0.04em for display).
- Never leave typography at design-environment defaults — every value must be intentional.
- Avoid ultra-thin (hair/light) weights for body text — they become illegible at screen resolution.

**Display Typography**
- Prefer uniform stroke-width typefaces (sans-serifs) for oversized display type.
- Start oversized type too large, then scale down — designers consistently make display type too small.
- Never let text cover the faces of people or primary product elements in image/type composites.
- Small type surrounded by generous white space draws the eye as powerfully as large type.

**Document All Typography Levels**
- Document H1 through body copy, captions, and microcopy. Each needs typeface, weight, size, line-height, and color specifications.
- Undocumented type levels will be interpreted inconsistently across designers and developers.

---

## 4. WHITE SPACE & MINIMALISM

**White Space as a Design Tool**
- Treat white space as a design element, not an empty canvas — every area of negative space is deliberate.
- Active white space leads users' eyes. Passive white space creates breathing room. Use each purposefully.
- Use white space actively to direct attention: surround a priority element with ample space; crowd secondary items to de-emphasize them.
- Larger distance between elements pushes user attention harder toward the isolated element.

**Macro vs. Micro White Space**
- Macro white space (between large sections) controls page-level visual flow and creates strong section separation.
- Micro white space (between letters, lines, list items, buttons) directly determines readability and selection speed. Cramped micro spacing is the most common legibility error.

**Minimalism Principles**
- Design from content outward, not from a visual framework inward: start in black and white, establish content hierarchy, then add only required visual details.
- Group all site content into 5 or fewer major sections. More creates overcrowding in minimal designs.
- Apply the subtractive sculpture mindset at every iteration: ask what can be removed, not added.
- Apply Hick's Law: each page or scroll section should lead to only one primary action.
- Heavy white space signals luxury and high-end quality. Dense layouts signal lower price points. Match to brand positioning.

**Getting Spacing Right**
- Set line height to ~1.5× type size as your micro white space baseline.
- Not enough white space collapses hierarchy. Too much white space fragments and confuses.
- Achieve the right level of minimalism by removing elements until the design almost fails — then stop.
- Use the Golden Ratio (1:1.618) as a structural starting point for layout proportions.

**Asymmetry & Rhythm**
- Alternate spatial patterns (image-left/text-right, then text-left/image-right) to create Z-pattern visual rhythm.
- Use asymmetric spacing deliberately — asymmetry in a repeating pattern becomes intentional, not chaotic.
- Passive white space must go completely unnoticed. If spacing draws attention to itself, adjust it.

---

## 5. UI DESIGN PATTERNS

**Using Patterns Correctly**
- Patterns are frameworks (ideas), not copy-paste templates (visual styles). Apply the underlying logic with your own visual treatment.
- Users remember how a pattern *behaves*, not what it looks like. Never customize pattern behavior — only its appearance.
- Broken pattern expectations are cumulative. Each small deviation adds to frustration. One broken expectation is forgivable; a pattern of them drives users away.
- Use established UI patterns as your starting point — they require no explanation because users already know them.

**Navigation & Orientation**
- Never move primary navigation between pages. Users develop muscle memory; changing it signals disorganization.
- Place search fields in the upper right corner (or dead center for search-focused pages) — moving it elsewhere requires conscious relearning.
- Use completion meters for multi-step processes ("Step 2 of 4") to reduce abandonment.

**Forms & Inputs**
- Use inline validation (as user types/blurs), never end-of-form validation — waiting until submission destroys momentum.
- Provide forgiving formats for input: accept phone numbers, dates, and credit cards in multiple formats; normalize on the back end.
- Never change asterisk conventions in forms — asterisks mean "required" and that habit is deeply ingrained.
- Undo is always better than confirmation dialogs. Dialogs interrupt flow; users dismiss them without reading.

**Cards**
- Each card must represent exactly one primary action or thought.
- Keep card images between 50–75% of the card area.
- Use simple, medium-weight sans-serif typography in cards — ornate or ultra-thin faces become illegible at card scale.
- Include one unexpected detail per card (animation, round frame, color accent) — not several.
- Avoid cards for content-heavy, ad-heavy, or highly complex sites.

**Empty States & Onboarding**
- Use empty states as onboarding moments — teach users what the space is for and how to get started.
- Design "lazy signup" / immediate immersion: let users try the product before requiring account creation.
- Discoverable secondary controls should appear on hover, not by default, to reduce visual noise.

---

## 6. CONSISTENCY & STYLE GUIDES

**The Six Categories of Internal Consistency**
Maintain consistency across all six:
1. **Color** — same color always means the same thing
2. **Typography** — consistent type hierarchy throughout
3. **Language** — same words for same actions everywhere
4. **Visuals** — consistent icon sets and button styles
5. **Layout/Location** — navigation stays in the same place
6. **Interactions** — consistent form elements, transitions, animations

**Meeting User Expectations**
- Use established external conventions — envelope icon for email, logo click to go home. Reinventing these wastes user goodwill.
- Core functions must not stray from platform norms. Delight lives in tone and personality (copy, animations), not in primary interaction patterns.
- Use spatial memory as a design asset — users remember where things are; avoid rearranging navigation in updates.

**Using Inconsistency Deliberately**
- Save intentional inconsistency for the single most important element per page (a CTA, new feature, promotion).
- Break a pattern only when you can complete the sentence: "all X are Y, *except* this one because..."
- One element that breaks the pattern stands out; many broken patterns create chaos.

**Style Guide Requirements**
- A style guide is a living collaborative tool, not a static onboarding document.
- Document exact numeric values: px values for margins, spacing, gutters, column widths. "Adequate spacing" is useless for implementation.
- Include all four color code formats: CMYK, Pantone, RGB, and HEX.
- Start with a mood board → style tile → front-end guide (this progression prevents undefined decisions).
- Front-end style guides must include code snippets alongside visual examples.
- Document iconography with usage rules, minimum size, placement, and prohibited uses.

---

## 7. MICROINTERACTIONS

**The Four-Part Structure**
Design every microinteraction through: **Trigger → Rules → Feedback → Loop/Mode**
- **Trigger**: what starts the interaction (user action or system event)
- **Rules**: what governs the behavior (constraints the user must understand)
- **Feedback**: how the system communicates status (visual, sound, haptic)
- **Loop/Mode**: how it repeats, ends, or adapts over time

**Feedback Principles**
- Provide immediate, clear feedback for every user action — absence of feedback causes users to repeat actions, lose confidence, or abandon.
- Feedback should be proportional: over-feedback trains users to ignore all feedback. Reserve emphasis for truly important moments.
- Use feedback as a personality-delivery mechanism — a success animation or playful error message is a character-building opportunity for your product's voice.

**Bringing Data Forward**
- System triggers should surface relevant data before users request it — unread count on a badge, current weather in a status bar — reducing the steps to information.
- Use long loops (tracking behavior patterns across sessions) to adapt: remember preferences, pre-fill common inputs, simplify repeated flows. Create a sense that the product learns.

**Rules Must Be Visible**
- Make behavioral rules (constraints) explicit enough to prevent errors, not just report them. Hidden rules cause unexpected failures users cannot anticipate.
- The difference between a product you love and one you tolerate is its microinteractions.

---

## 8. USER EXPERIENCE & RESEARCH

**Know Your User (Mandatory Gate)**
- "Know thy users, for they are not you." Never design from your own mental model.
- Ask "why" recursively until you reach the root goal — design for the human need, not the stated feature request.
- Document who will use the system, what real tasks they need to accomplish, and choose 5–10 representative tasks that provide complete functional coverage.

**Mental Models & Behavior**
- Design for Safe Exploration: users must be able to try things, make mistakes, and recover without penalty. Every destructive action should be reversible.
- Support Satisficing: users take the first option that is "good enough," not the best option. Make the good-enough path obvious and fast.
- Account for Changes in Midstream: users change goals mid-task. Design navigation that supports graceful context-switching.
- Progressive disclosure is essential for complex interfaces: show only what users need for the current context; reveal advanced options on demand.

**Affordances & Signifiers**
- Buttons should look pressable. Draggable items should look draggable. Never make primary actions appear only on hover.
- Use explicit (labels), pattern (universal icons), hidden (hover-revealed), metaphorical (pen = text entry), and negative (grayed-out) signifiers to communicate function.
- Rounded rectangles reduce visual disruption to eye movement — default to rounded corners for interactive elements.
- Treat color and shape as a system with meaning: green/ticks = good; red/crosses = bad; yellow/triangles = warning; blue/circles = info. Never mix these.

**Testing & Iteration**
- Set quantitative usability targets before building: "90% of first-time users complete task X in under 3 minutes."
- Run usability tests between each design stage, not only at the end. Problems at wireframe stage cost nothing; the same problem at development is expensive.
- Do a cognitive walkthrough before coding: for each task step, ask: Will users know what to do? Will they notice the right control? Will they interpret feedback correctly?
- "Thinking aloud" usability testing reveals problems no expert review finds. A design that has not been tested with real users is a first draft that has been shipped.

---

## 9. VISUAL STORYTELLING

**Story-First Design**
- Use the beginning-middle-end arc even in single-page scroll designs. Map stimulus (beginning) → engagement (middle) → resolution/CTA (end) before designing.
- Know your user before you know your story. Research, build personas, create experience maps before selecting any visual style.
- Make the user a character in the story — personalize content based on their input or context to maximize engagement.

**Image Power**
- Visuals are processed 60,000× faster than text. Design the visual layer to carry primary communication; use text to provide context, not to repeat what the image already communicates.
- Users retain 65% of information paired with images vs. 10% with text alone — invest in visual content over equivalent investment in copy.
- Do not repeat visual concepts — each image must advance the story, not merely decorate it.
- Use real, authentic photos of people — never visibly generic stock. Authentic photos create stronger emotional connection and maintain attention longer.
- Align image emotional tone precisely with intended user emotion. Calm visuals on an excitement-focused page create conversion-killing mismatches.

**Interactive Storytelling**
- Only add interactivity when it adds genuine value — if the story works with a static image, don't add interaction for its own sake.
- Embed interaction into existing user actions (scroll-triggered animations, hover effects) rather than inventing new paradigms users must learn.
- Make visual responses smooth and physically believable: motion curves should feel consistent with content weight and character.
- Keep critical task actions explicitly visible; reserve hidden/easter-egg interactions for supplementary delight only.

---

## 10. FLAT DESIGN & MODERN AESTHETICS

**Flat Design Principles**
- Design "2/3 flat, 1/3 skeuomorphic" — pure flat design removes too many affordance cues. Subtle shadows, soft gradients, and light textures restore visual hierarchy and signal clickability.
- Use color as accent, not fill strategy: shift from filling entire interfaces with color to using vivid hues as points of emphasis against white space or large imagery.
- Avoid applying color purely for decoration in flat UI — every color decision must communicate purpose.
- Focus flat iconography on craft and detail, not just simplicity — well-designed flat icons serve as both functional affordances and visual art elements.

**Modern Techniques**
- Material Design layering (z-axis elevation) solves flat design's affordance deficit — subtle elevation shadows communicate element priority without abandoning clean aesthetics.
- Ghost buttons only appear against high-color or image backgrounds — on white, ghost buttons disappear entirely.
- Use bright color overlays on images or video to combine emotional color impact with the storytelling power of imagery.
- Add subtle texture to bold colors to soften chaotic-feeling palettes.

**Aesthetics & Trust**
- You have 10 seconds to visually establish trust. Users judge value and credibility before reading a single word.
- 46% of users determine trustworthiness from visual design alone — layout, typography, font size, and color are trust signals evaluated before content.
- Attractive interfaces are perceived as more functional (the Japanese ATM study) — aesthetics and functionality are equivalent design priorities.
- Match visual personality to user identity — the design is a mirror, not just decoration.

---

## 11. DESIGN PROCESS

**Wireframes → Mockups → Prototype**
- Wireframes answer layout/structure questions. Mockups answer visual design questions. Never skip wireframing to save time.
- Problems caught at wireframe stage cost nothing; the same problem at development is expensive.
- Always frame mockup presentations in context of the problem being solved — without context, stakeholders give feedback on colors instead of structure.
- Mockups are a conversation medium, not a finished specification.

**Prototyping & Patterns**
- Always prototype before finalizing patterns — patterns feel obvious in theory but reveal problems only under real use.
- Plagiarize existing interfaces whenever legally possible — users already know how familiar interactions work; deviation imposes a learning cost the efficiency gain rarely justifies.
- Do not code a design before doing a cognitive walkthrough — paper-based evaluation is far cheaper than user testing a built product.

**Style Guide as a Living Tool**
- Treat the style guide as an evolving shared reference, not a PDF produced once and forgotten.
- Start with mood board → style tile → front-end guide. Skipping steps produces undefined design decisions.
- The mission statement and design philosophy belong at the front — every technical decision must be understood in context of brand intent.

---

## QUICK REFERENCE: CRITICAL RULES

| Principle | Rule |
|-----------|------|
| Hierarchy | Every page needs ONE primary focal point |
| Color | One color = one meaning, always |
| Typography | One type family, max 4 sizes, 1.5× line height |
| White Space | Active leads eyes; passive creates breathing room |
| Patterns | Customize appearance, NEVER behavior |
| Consistency | Same words, same colors, same placement — always |
| Microinteractions | Every action needs immediate, proportional feedback |
| Trust | 10 seconds to establish credibility visually |
| Minimalism | Remove until design almost fails, then stop |
| Testing | Test with real users performing real tasks |
