# Qualifi Site Design Comparison

## Files

- **`code-original.html`** - Original "Clean Square Luxury" design (Archivo Narrow + Inter)
- **`index-v2.html`** - New conversion-focused landing page design (Heebo font)

## Design Changes

### Typography
**Original:**
- Archivo Narrow (display/headlines)
- Inter (body text)
- Sharp, technical, condensed aesthetic

**New:**
- Heebo (all text)
- Cleaner, more readable, conversion-focused

### Visual Style
**Original:**
- True black (#000000) background
- Electric Blue (#00F0FF), Neon Green (#CCFF00), Hot Pink (#FF007F) accents
- Extremely sharp, 0px border radius everywhere
- Architectural, brutalist aesthetic
- "Ghost offset" depth effects

**New:**
- Black (#000000) background maintained
- Cyan (#22D3EE), Pink (#F472B6), Purple (#C084FC), Blue (#60A5FA), Red (#F87171) for colorful accents
- Minimal borders, white/20 opacity for subtle lines
- Simpler, cleaner aesthetic focused on conversion

### Layout & Structure
**Original (code-original.html):**
- Hero with positioning statement
- Revenue-First Philosophy section
- Three-Phase Architecture (Discovery, Strategy, Execution)
- Results by Numbers
- How We Work (4-phase process)
- Final CTA

**New (index-v2.html):**
- Hero with lead capture form (side-by-side layout)
- Problem/Solution section (3 common problems)
- How It Works (4-step process)
- Testimonials (3 client stories with results)
- Final CTA
- Better mobile responsiveness

### Conversion Optimization
**New design includes:**
- Prominent lead form in hero (above the fold)
- Social proof badges (500K+ leads, 15+ industries, 98% retention)
- Benefit-focused copy with checkmarks
- Real testimonials with specific results
- Trust signals (Secure, Fast Response, No Spam)
- Thank you state after form submission

### Technical Changes
**Original:**
- Complex Tailwind config with custom Material Design color palette
- Material Symbols icon font
- Custom animations and transitions
- React-like structure but static HTML

**New:**
- Simplified Tailwind config
- Inline SVG icons (no external dependencies)
- Pure HTML/CSS/JS (no React)
- Form submission handler with success state
- Smooth scroll for anchor links

## Recommendation

**Use `index-v2.html` for:**
- Lead generation campaigns
- Paid advertising landing pages
- Direct conversion goals
- When you need a proven landing page structure

**Use `code-original.html` for:**
- Brand/corporate site
- Establishing authority/positioning
- When aesthetic/design is the priority
- Portfolio/showcase purposes

## Next Steps

1. Test `index-v2.html` in browser
2. Connect form to actual lead capture (email, CRM, etc.)
3. Add tracking (Google Analytics, Meta Pixel, etc.)
4. Deploy to qlfirs.com or subdomain for testing
5. A/B test both designs to see which converts better
