---
name: cake-decoration-ideas
description: List cake decoration ideas by searching the web for images. Trigger whenever users mention decorating a cake, need decoration inspiration, or want to make a cake look special with simple decoration. Provide 2-3 decoration ideas with actual images from web, with difficulty levels, time estimates, materials lists, and step-by-step instructions. Focus on fondant-free and edible paint-free options using simple, everyday items like candies, sprinkles, frosting, nuts and fruits, cookies, candles.
---

# Cake Decoration Ideas

Help users generate creative, practical cake decoration ideas with visual mockups and clear materials lists.

## When to Use This Skill

Trigger this skill whenever:
- A user asks for cake decoration ideas or inspiration
- A user mentions they need to decorate a cake (birthday, celebration, surprise)
- A user wants to make a cake look special but doesn't know how
- A user is planning a party and needs cake decoration suggestions
- A user asks about themed cake decorations (character cakes, holiday cakes, etc.)
- A user mentions any cake + decoration context (even if they don't explicitly ask for ideas)

## What This Skill Does

1. **Generate 2-3 unique decoration concepts** based on the user's context (theme, occasion, skill level, etc.)
2. **Search the web for real cake images** showing how each decoration looks in practice. Only include the idea if image links exist for the decoration. Ideas with ONLY YouTube or video links do NOT qualify and should be excluded
3. **Provide materials lists** for each idea with specific, easy-to-find items
4. **Include difficulty and time estimates** so users know what they're getting into
5. **Give step-by-step instructions** for implementing each decoration
6. **Focus on simple, fondant-free options** using everyday items

## Key Principles

### Materials Philosophy
Use ONLY simple, everyday items:
- **Frosting** (different colors using food coloring)
- **Candies** (M&Ms, gummy candies, chocolate chips, licorice)
- **Sprinkles** (pearls, nonpareils, rainbow, gold, etc.)
- **Nuts and fruits** (almonds, walnuts, berries, sliced fruit, dried fruit)
- **Cookies** (crushed, whole, or cut)
- **Candles** (birthday candles, tea lights)
- **Edible markers** (optional)
- **Construction paper** or card stock (for non-edible decorations)
- **Balloons** (decoration around cake, not on cake)

DO NOT suggest:
- Fondant (too complex for beginners)
- Edible paint (eliminates easy options)
- Airbrush techniques
- Complex piping skills
- Specialty baking ingredients

### Design Philosophy
Each decoration concept should:
- Be implementable by a beginner
- Use items found in regular grocery stores
- Not require special tools (piping bags optional)
- Look good despite imperfections
- Be fun and creative, not "perfect"

## Output Structure

**IMPORTANT: Present all decoration ideas as an HTML page**

For each decoration idea, provide:
1. **Idea Title** — Clear, descriptive name
2. **Theme/Style** — Brief description of vibe/style
3. **Real Images from Web** — Links to actual cakes from Pinterest, blogs, recipe websites (REQUIRED: Ideas with ONLY YouTube or video links do NOT qualify — exclude them. Each of the 2-3 ideas must have DISTINCT web links — do NOT use the same link for multiple ideas)
4. **Difficulty Level** — ⭐ Easy / ⭐⭐ Medium / ⭐⭐⭐ Challenging
5. **Time Estimate** — Quick / Moderate / Extended
6. **Materials Needed** — Complete list with quantities
7. **Step-by-Step Instructions** — Numbered, beginner-friendly steps
8. **Pro Tips** — 3-4 helpful tips and variations

### Output Format: HTML

Generate a complete HTML page that displays all decoration ideas with:
- Clean, modern styling
- Organized card layout for each idea
- Color-coded difficulty levels
- Clickable links to web references
- Professional visual design
- Mobile-responsive layout

---

## Example Output Format

**Idea 1: Rainbow Candy Explosion**

**Theme/Style**: Bright, colorful, fun for kids' parties

[SVG visualization showing a cake with colorful candies arranged in a pattern]

**Difficulty**: ⭐ Easy | **Time**: Quick (15-20 minutes)

**Materials Needed**:
- Pink frosting (1 batch)
- M&Ms or gummy candies (1 cup)
- Rainbow sprinkles (2 tablespoons)
- Licorice pieces (optional, for accents)

**Instructions**:
1. Frost cake with base frosting
2. Arrange candies in sections (group by color)
3. Add sprinkles between candy sections
4. Use licorice to create lines or borders

**Pro Tips**:
- Group similar colors together for visual impact
- Place larger candies first, fill gaps with sprinkles
- For mess-free placement, use tweezers or a small spoon

---

## Customization Based on User Context

### If user mentions a theme (character, holiday, etc.)
Design decorations that match the theme while staying fondant-free

### If user mentions skill level
Adjust difficulty accordingly (absolute beginner vs. experienced baker)

### If user mentions cake type
Suggest decorations that complement the cake flavor (chocolate, vanilla, etc.)

### If user mentions occasion
Tailor decorations to the event (birthday, anniversary, celebration, etc.)

### If user mentions time constraints
Suggest quick options if they're in a hurry, or extended options if they have time

## Implementation Tips

1. **Read user context carefully** — theme, skill level, occasion, available time
2. **Search the web for real images** of cake decorations matching each idea using web search tools
3. **Only include ideas with image links** from Pinterest, recipe blogs, or cake decorating websites. If an idea only has YouTube or video links available, do NOT include it
4. **Use DISTINCT links for each idea** — search for different sources for each decoration idea. Do NOT repeat the same link for multiple ideas
5. **Make suggestions practical** — assume user has basic kitchen supplies
5. **Be encouraging** — emphasize that homemade ≠ perfect
6. **Provide variations** — suggest how to modify ideas (color changes, scale changes, etc.)
7. **Test mentally** — would a beginner actually be able to do this with regular grocery store items?

## Success Criteria

A good decoration idea should:
- ✓ Include real images from web showing actual cakes with this decoration
- ✓ Be completable by a beginner
- ✓ Use only everyday, easy-to-find items
- ✓ Include clear, numbered steps
- ✓ Have realistic time and difficulty estimates
- ✓ Include helpful tips and variations
- ✓ Match the user's context (theme, skill level, occasion)
- ✓ Provide links to inspiration and examples online
- ✓ Each of the 2-3 ideas must have DISTINCT web links (no duplicate links across ideas)
