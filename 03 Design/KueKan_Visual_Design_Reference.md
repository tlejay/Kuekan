# KueKan Visual Design Reference Board
**Comprehensive visual identity and design system guidelines**
**Date:** January 2, 2026
**Version:** 1.0

---

## Brand Identity

### Brand Name
**KueKan (คือกัน)**
- **Meaning:** "Let's Together" / "We Are One"
- **Phonetic:** Keu-Kan
- **Logo Treatment:** Modern Thai typography with teal accent
- **Tagline:** "เชื่อมคน สร้างเมือง" (Connecting People, Building City)

### Brand Personality
- **Vibrant**: Energetic and full of life, like Korat's bustling markets
- **Trustworthy**: Official government partnership, enterprise-grade
- **Inclusive**: Accessible to all ages and tech literacy levels
- **Community-Focused**: Celebrating togetherness and local pride
- **Rewarding**: Achievement-oriented, celebrating progress

---

## Color System (Complete Palette)

### Primary Colors

**Brand Teal - #00B8A9**
- RGB: (0, 184, 169)
- Usage: Primary buttons, headers, active states, mission icons
- Psychology: Growth, community, freshness, prosperity
- Thai Cultural Connection: Represents natural beauty of Korat's landscapes

**Brand Gold - #FFD93D**
- RGB: (255, 217, 61)
- Usage: Point badges, rewards, achievements, tier icons
- Psychology: Value, reward, success, prestige
- Thai Cultural Connection: Gold represents prestige and prosperity in Thai culture

**Accent Coral - #FF6B6B**
- RGB: (255, 107, 107)
- Usage: Call-to-action accents, limited-time offers, urgent notifications
- Psychology: Energy, excitement, action
- Thai Cultural Connection: Warm, inviting, market energy

### Secondary Colors

**Success Green - #6BCB77**
- RGB: (107, 203, 119)
- Usage: Success messages, completed missions, confirmation states
- Accessibility: AA compliant on white background

**Warning Orange - #FFA502**
- RGB: (255, 165, 2)
- Usage: Warning messages, expiring coupons, attention needed
- Accessibility: AA compliant on white background

**Error Red - #E63946**
- RGB: (230, 57, 70)
- Usage: Error messages, failed transactions, critical alerts
- Accessibility: AA compliant on white background

**Info Aqua - #4ECDC4**
- RGB: (78, 205, 196)
- Usage: Informational messages, tips, help sections
- Accessibility: AA compliant on white background

### Neutral Colors

**Background - #F8F9FA**
- RGB: (248, 249, 250)
- Usage: Main app background, section backgrounds
- Note: Very light gray, provides subtle contrast without harshness

**Surface - #FFFFFF**
- RGB: (255, 255, 255)
- Usage: Cards, modals, content containers
- Note: Pure white for maximum clarity

**Text Primary - #2D3436**
- RGB: (45, 52, 54)
- Usage: Main body text, headings
- Accessibility: AAA compliant on white background (13.9:1)

**Text Secondary - #636E72**
- RGB: (99, 110, 114)
- Usage: Supporting text, captions, metadata
- Accessibility: AA compliant on white background (5.8:1)

**Border - #DFE6E9**
- RGB: (223, 230, 233)
- Usage: Card borders, dividers, input fields
- Note: Subtle separation without heavy lines

### Admin Console Colors

**Admin Navy - #2C3E50**
- RGB: (44, 62, 80)
- Usage: Admin dashboard primary color, professional sections
- Psychology: Trust, authority, professionalism

**Data Blue - #3498DB**
- RGB: (52, 152, 219)
- Usage: Charts, graphs, data visualization

**Data Purple - #9B59B6**
- RGB: (155, 89, 182)
- Usage: Secondary data series

**Data Orange - #E67E22**
- RGB: (230, 126, 34)
- Usage: Highlight data, trends

### Gradient Definitions

**Primary Button Gradient**
```css
background: linear-gradient(135deg, #00B8A9 0%, #008B82 100%);
```

**Gold Coin Gradient**
```css
background: linear-gradient(135deg, #FFD93D 0%, #F7B731 50%, #FFD93D 100%);
box-shadow: 0 4px 12px rgba(255, 217, 61, 0.4);
```

**Tier Badge Gradients**
```css
/* Standard Tier - Silver */
background: linear-gradient(135deg, #BDC3C7 0%, #95A5A6 100%);

/* Exclusive Tier - Gold */
background: linear-gradient(135deg, #FFD93D 0%, #F7B731 100%);

/* VIP Tier - Platinum */
background: linear-gradient(135deg, #E8E8E8 0%, #C0C0C0 50%, #E8E8E8 100%);
```

---

## Typography System

### Font Families

**Thai Typography**

```
Primary Thai Font: "Prompt", sans-serif
- Weights: Regular (400), Medium (500), SemiBold (600), Bold (700)
- Google Fonts: https://fonts.google.com/specimen/Prompt
- Characteristics: Modern, friendly, excellent readability
- Best for: Headings, UI labels, call-to-actions

Body Thai Font: "Sarabun", sans-serif
- Weights: Regular (400), Medium (500)
- Google Fonts: https://fonts.google.com/specimen/Sarabun
- Characteristics: Clean, professional, great for long-form
- Best for: Body text, descriptions, content

Numbers Thai Font: "Kanit", sans-serif
- Weights: SemiBold (600), Bold (700)
- Google Fonts: https://fonts.google.com/specimen/Kanit
- Characteristics: Strong, clear numerals
- Best for: Point displays, statistics, KPIs
```

**English Typography**

```
Primary English Font: "Poppins", sans-serif
- Weights: Regular (400), Medium (500), SemiBold (600), Bold (700)
- Google Fonts: https://fonts.google.com/specimen/Poppins
- Best for: Headings, labels

Body English Font: "Inter", sans-serif
- Weights: Regular (400), Medium (500)
- Google Fonts: https://fonts.google.com/specimen/Inter
- Best for: Body text, UI elements

Monospace: "Roboto Mono", monospace
- Best for: Code, transaction IDs, system information
```

### Type Scale

**Mobile (Customer App)**
```
Display: 32px / 2rem - Kanit Bold (for point balances)
H1: 24px / 1.5rem - Prompt SemiBold (page titles)
H2: 20px / 1.25rem - Prompt SemiBold (section headers)
H3: 18px / 1.125rem - Prompt Medium (card titles)
Body: 16px / 1rem - Sarabun Regular (main content)
Small: 14px / 0.875rem - Sarabun Regular (captions, metadata)
Tiny: 12px / 0.75rem - Sarabun Regular (fine print)
```

**Desktop (Admin Console)**
```
Display: 48px / 3rem - Poppins Bold
H1: 32px / 2rem - Poppins SemiBold
H2: 24px / 1.5rem - Poppins SemiBold
H3: 20px / 1.25rem - Poppins Medium
Body: 16px / 1rem - Inter Regular
Small: 14px / 0.875rem - Inter Regular
```

### Line Height

```
Headings (Thai): 1.4 (to accommodate Thai diacritics)
Headings (English): 1.2
Body (Thai): 1.6 (essential for readability)
Body (English): 1.5
UI Elements: 1.4
```

### Letter Spacing

```
Headings: -0.02em (slightly tighter)
Body: 0 (default)
Uppercase Labels: 0.08em (tracking for readability)
Numbers: -0.01em (tighter for cohesion)
```

---

## Spacing System

### Base Unit: 4px

```
4px   - xs   - Tight spacing, icon padding
8px   - sm   - Compact spacing
12px  - md   - Standard spacing between related elements
16px  - lg   - Card padding, section spacing
24px  - xl   - Major section gaps
32px  - 2xl  - Screen padding, large gaps
48px  - 3xl  - Hero section spacing
64px  - 4xl  - Major layout sections
```

### Component Spacing

**Cards**
- Padding: 16px
- Gap between cards: 12px
- Border radius: 16px

**Buttons**
- Padding: 12px 24px (medium)
- Padding: 16px 32px (large)
- Padding: 8px 16px (small)
- Gap between buttons: 12px

**Form Elements**
- Label margin-bottom: 8px
- Input padding: 12px
- Field gap: 16px

**Lists**
- Item padding: 12px 16px
- Gap between items: 8px
- Divider: 1px solid #DFE6E9

---

## Component Design Patterns

### Buttons

**Primary Button**
```
Background: Gradient teal (#00B8A9 to #008B82)
Text: White, Prompt SemiBold, 16px
Padding: 12px 24px
Border-radius: 24px (fully rounded)
Shadow: 0 4px 12px rgba(0, 184, 169, 0.3)
Hover: Scale 1.02, deeper shadow
Active: Scale 0.98
```

**Secondary Button**
```
Background: Transparent
Border: 2px solid #00B8A9
Text: #00B8A9, Prompt SemiBold, 16px
Padding: 10px 22px (accounting for border)
Border-radius: 24px
Hover: Background #F0FFFE (teal tint 5%)
Active: Background #E0FFF9
```

**Icon Button**
```
Size: 48x48px (touch target)
Icon size: 24x24px
Border-radius: 50% (circular)
Background: Transparent
Hover: Background #F0FFFE
Active: Ripple effect
```

### Cards

**Standard Card**
```
Background: #FFFFFF
Border: 1px solid #DFE6E9 (optional)
Border-radius: 16px
Padding: 16px
Shadow: 0 2px 8px rgba(0, 0, 0, 0.08)
Hover: Shadow 0 4px 16px rgba(0, 0, 0, 0.12)
```

**Mission Card**
```
Background: #FFFFFF
Border-radius: 16px
Padding: 0 (image fills top)
Shadow: 0 2px 12px rgba(0, 0, 0, 0.1)
Structure:
  - Image section (ratio 16:9, border-radius top)
  - Content section (padding 16px)
  - Badge overlays (position absolute)
```

**Reward Card**
```
Background: #FFFFFF
Border-radius: 12px
Padding: 12px
Shadow: 0 2px 8px rgba(0, 0, 0, 0.08)
Grid: 2 columns on mobile
Structure:
  - Product image (1:1 ratio)
  - Title
  - Point cost badge
  - Merchant name
```

### Badges

**Point Badge**
```
Background: Gold gradient
Text: #2D3436, Kanit Bold, 16px
Padding: 6px 12px
Border-radius: 16px
Icon: Coin icon 20x20px
Shadow: 0 2px 6px rgba(255, 217, 61, 0.4)
```

**Status Badge**
```
Small pill-shaped badges
Padding: 4px 8px
Border-radius: 12px
Font: Sarabun Medium, 12px

Variants:
- New: Background #4ECDC4, Text white
- Limited: Background #E63946, Text white
- Hot: Background #FFA502, Text white
- Completed: Background #6BCB77, Text white
```

**Tier Badge**
```
Circular or shield-shaped
Size: 64x64px (profile), 32x32px (inline)
Gradient background based on tier
Icon/text overlay in white
Subtle glow effect for VIP tier
```

### Form Elements

**Text Input**
```
Background: #FFFFFF
Border: 2px solid #DFE6E9
Border-radius: 12px
Padding: 12px 16px
Font: Sarabun Regular, 16px
Focus: Border color #00B8A9, shadow 0 0 0 4px rgba(0, 184, 169, 0.1)
Error: Border color #E63946
Success: Border color #6BCB77
```

**Dropdown/Select**
```
Same as text input
Chevron icon on right
Padding-right: 40px (space for icon)
```

**Checkbox/Radio**
```
Size: 24x24px
Border: 2px solid #636E72
Border-radius: 4px (checkbox), 50% (radio)
Checked: Background #00B8A9, white checkmark
```

### Navigation

**Bottom Navigation (Mobile)**
```
Height: 64px
Background: #FFFFFF
Border-top: 1px solid #DFE6E9
Shadow: 0 -2px 8px rgba(0, 0, 0, 0.08)
Items: 4-5 items max
Icon size: 24x24px
Label: Sarabun Regular, 12px
Active: Icon and text in #00B8A9
Inactive: #636E72
```

**Tab Bar**
```
Background: #FFFFFF
Border-bottom: 2px solid #DFE6E9
Height: 48px
Items: Scrollable horizontal
Active indicator: 3px bottom border #00B8A9
Font: Prompt Medium, 16px
```

---

## Iconography

### Icon Style
- Line icons (2px stroke weight)
- Rounded line caps and joins
- 24x24px base size (scale to 20px, 32px as needed)
- Consistent visual weight
- Simple, recognizable shapes

### Icon Categories & Examples

**Navigation Icons**
- Home: House outline
- Mission: Target/flag
- Rewards: Gift box
- Profile: User circle

**Mission Type Icons**
- Location: Map pin
- Purchase: Shopping bag
- Action: Checkmark in circle
- Time: Clock

**Status Icons**
- Success: Checkmark circle (filled)
- Error: X circle (filled)
- Warning: Exclamation triangle
- Info: i circle

**Action Icons**
- Scan: QR code outline
- Share: Share arrow
- Filter: Funnel
- Search: Magnifying glass

**Tier Icons**
- Standard: Single star
- Exclusive: Double star
- VIP: Crown

### Icon Colors
- Default: #636E72 (secondary text)
- Active: #00B8A9 (brand teal)
- Success: #6BCB77
- Warning: #FFA502
- Error: #E63946

---

## Photography Guidelines

### Image Style

**Mission & Location Photography**
- Natural lighting, bright and inviting
- Wide angles for landmarks
- Include people when possible (community feel)
- Golden hour lighting preferred
- High saturation for vibrancy
- Sharp focus, professional quality

**Product Photography (Rewards)**
- Natural, unpolished aesthetic
- Wood, textile, or neutral backgrounds
- Soft natural lighting
- Close-up details showing craftsmanship
- Context shots (products in use)
- Authentic OTOP style

**People Photography**
- Diverse age representation (18-65+)
- Genuine smiles and interactions
- Thai cultural context
- Modern yet authentic styling
- Community and togetherness themes

### Image Specifications

**Mission Cards**
- Aspect ratio: 16:9
- Minimum size: 1200x675px
- Format: WebP (fallback JPG)
- Compression: 85% quality
- Alt text in Thai required

**Reward Products**
- Aspect ratio: 1:1 (square)
- Minimum size: 800x800px
- Format: WebP (fallback JPG)
- White or natural background
- Multiple angles preferred

**Hero Banners**
- Aspect ratio: 2:1 (mobile), 3:1 (desktop)
- Minimum size: 1600x800px (mobile)
- Overlay gradient for text readability
- Key subject in center third

---

## Illustration Style

### Characteristics
- Flat 2D style with slight texture
- Rounded, friendly shapes
- Limited detail (iconic, not realistic)
- Brand color palette
- Subtle shadows for depth
- Inclusive representation of Thai people

### Use Cases
- Empty states
- Onboarding flows
- Achievement badges
- Error/success messages
- Feature explanations

### Examples Needed
- Character illustrations (diverse Thai people)
- Mission completion celebrations
- Reward redemption success
- Location landmarks (simplified)
- Point/coin illustrations

---

## Animation & Motion

### Principles
- **Purposeful**: Every animation serves a function
- **Quick**: 200-300ms for most interactions
- **Smooth**: Ease-out for entrances, ease-in for exits
- **Delightful**: Celebrate achievements with flair

### Animation Catalog

**Point Earning Animation**
```
Duration: 500ms
Sequence:
1. Coin appears at bottom (scale 0 to 1.2, 200ms, ease-out)
2. Coin shrinks to 1.0 (100ms, ease-in-out)
3. Coin flies to pocket icon (200ms, cubic-bezier)
4. Point number updates with count-up animation
```

**Mission Complete Animation**
```
Duration: 800ms
Sequence:
1. Checkmark appears (scale 0 to 1, 200ms)
2. Card highlights with green tint (200ms)
3. Confetti burst from center (400ms)
4. +Points badge flies to pocket
```

**Card Tap Interaction**
```
Duration: 100ms
Effect: Scale 0.98 on press, return to 1.0 on release
Timing: ease-in-out
```

**Loading States**
```
Skeleton screens: Pulse animation (1.5s loop)
Spinner: Rotate 360deg (800ms loop, linear)
Progress bar: Smooth fill (cubic-bezier)
```

**Page Transitions**
```
Duration: 250ms
Mobile: Slide from right (new page), slide to right (back)
Tabs: Fade transition (200ms)
Modals: Scale from 0.9 to 1.0 + fade in
```

### Micro-interactions

**Button Press**
- Scale: 0.98
- Duration: 100ms
- Add subtle shadow shift

**Toggle Switch**
- Slide: 200ms ease-in-out
- Background color transition: 150ms
- Thumb movement: follows slide

**Input Focus**
- Border color: 200ms ease
- Shadow: 150ms ease
- No layout shift

**Notification Toast**
- Slide in from top: 300ms ease-out
- Stay: 3 seconds
- Slide out: 200ms ease-in
- Auto-dismiss or swipe away

---

## Responsive Breakpoints

```
Mobile Small:   320px - 374px (iPhone SE)
Mobile Medium:  375px - 413px (iPhone 13, standard)
Mobile Large:   414px - 767px (iPhone Pro Max, small tablets)
Tablet:         768px - 1023px (iPad)
Desktop Small:  1024px - 1279px (Small laptops)
Desktop Large:  1280px+ (Standard desktop)
```

### Layout Adaptations

**Mobile (< 768px)**
- Single column layout
- Bottom navigation
- Full-width cards
- Stacked forms
- Hamburger menus

**Tablet (768px - 1023px)**
- 2-column grids where appropriate
- Side navigation (admin only)
- Wider cards with more padding
- Horizontal tabs visible

**Desktop (1024px+)**
- Multi-column dashboards
- Sidebar navigation
- Data-dense layouts
- Hover states active
- Keyboard shortcuts enabled

---

## Accessibility Standards

### WCAG Compliance
- Level: AA minimum (AAA preferred)
- Color contrast: 4.5:1 for body text, 3:1 for large text
- Touch targets: Minimum 44x44px
- Focus indicators: Visible, high contrast
- Alt text: Required for all images
- Semantic HTML: Proper heading hierarchy

### Thai Language Accessibility
- Line-height minimum 1.6 for Thai text
- Font size minimum 16px for body text
- Support screen readers with Thai language
- Proper word breaking for Thai
- Unicode normalization for Thai characters

### Keyboard Navigation
- All interactive elements keyboard accessible
- Tab order logical and predictable
- Skip navigation links
- Escape to close modals
- Arrow keys for carousels/sliders

### Screen Reader Optimization
- ARIA labels in Thai
- Role attributes for custom components
- Live regions for dynamic content
- Descriptive link text
- Form label associations

---

## Design Tokens (For Developers)

### Export Format: CSS Custom Properties

```css
:root {
  /* Colors */
  --color-brand-teal: #00B8A9;
  --color-brand-gold: #FFD93D;
  --color-accent-coral: #FF6B6B;

  --color-success: #6BCB77;
  --color-warning: #FFA502;
  --color-error: #E63946;
  --color-info: #4ECDC4;

  --color-bg-main: #F8F9FA;
  --color-surface: #FFFFFF;
  --color-text-primary: #2D3436;
  --color-text-secondary: #636E72;
  --color-border: #DFE6E9;

  /* Typography */
  --font-thai-heading: 'Prompt', sans-serif;
  --font-thai-body: 'Sarabun', sans-serif;
  --font-thai-number: 'Kanit', sans-serif;
  --font-english-heading: 'Poppins', sans-serif;
  --font-english-body: 'Inter', sans-serif;

  /* Font Sizes */
  --text-display: 2rem;
  --text-h1: 1.5rem;
  --text-h2: 1.25rem;
  --text-h3: 1.125rem;
  --text-body: 1rem;
  --text-small: 0.875rem;
  --text-tiny: 0.75rem;

  /* Spacing */
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 12px;
  --space-lg: 16px;
  --space-xl: 24px;
  --space-2xl: 32px;
  --space-3xl: 48px;
  --space-4xl: 64px;

  /* Border Radius */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: 0 2px 4px rgba(0, 0, 0, 0.08);
  --shadow-md: 0 2px 8px rgba(0, 0, 0, 0.08);
  --shadow-lg: 0 4px 16px rgba(0, 0, 0, 0.12);
  --shadow-xl: 0 8px 24px rgba(0, 0, 0, 0.16);

  /* Transitions */
  --transition-fast: 150ms ease;
  --transition-base: 200ms ease;
  --transition-slow: 300ms ease;
}
```

---

## Thai Cultural Design Elements

### ลายไทย (Thai Patterns)
- Use subtly in backgrounds (5% opacity)
- Prefer simple, recognizable patterns
- Common motifs: ลายกนก (flame pattern), ลายพุ่มข้าวบิณฑ์ (floral)
- Color: Gold (#FFD93D) or Teal (#00B8A9)
- Placement: Headers, card backgrounds, dividers

### Color Symbolism
- **Gold/Yellow**: Royalty, prosperity, Monday
- **Green**: Nature, growth, prosperity, Wednesday
- **Blue**: Loyalty, stability, Friday
- **Red**: Energy, auspiciousness (use carefully)

### Respectful Imagery
- Avoid placing logos/text on heads in photos
- Respect royal imagery protocols (no casual use)
- Use proper Thai honorifics (คุณ, ท่าน)
- Buddhist imagery (if any) treated respectfully

### Korat-Specific Elements
- Dan Kwian pottery patterns (local craft)
- Phimai stone texture references
- Local silk patterns (matmee)
- Korat cat imagery (if appropriate)

---

## Component Library Checklist

When building in Stitch, ensure these components are created:

### Atoms (Basic Elements)
- [ ] Buttons (primary, secondary, icon, text)
- [ ] Input fields (text, number, tel, email)
- [ ] Labels and captions
- [ ] Icons (all categories)
- [ ] Badges (point, status, tier)
- [ ] Avatars
- [ ] Dividers
- [ ] Loading spinners

### Molecules (Component Groups)
- [ ] Search bar
- [ ] Filter chips
- [ ] Tab navigation
- [ ] Breadcrumbs
- [ ] Alert messages
- [ ] Toast notifications
- [ ] Empty states
- [ ] Form groups

### Organisms (Complex Components)
- [ ] Navigation bars (top, bottom, side)
- [ ] Mission cards (all types)
- [ ] Reward cards
- [ ] User profile header
- [ ] Point balance display
- [ ] Transaction list items
- [ ] Dashboard stat cards
- [ ] Data visualization charts

### Templates (Page Layouts)
- [ ] Customer app home
- [ ] Mission center
- [ ] Reward catalog
- [ ] User profile
- [ ] Partner scanner
- [ ] Partner dashboard
- [ ] Admin dashboard
- [ ] Mission management

---

## Brand Voice & Microcopy

### Tone of Voice
- **Encouraging**: "เยี่ยมมาก! คุณทำสำเร็จแล้ว" (Great! You did it)
- **Friendly**: "มาทำภารกิจใหม่กันไหม?" (Shall we do a new mission?)
- **Clear**: "สแกน QR Code เพื่อรับแต้ม" (Scan QR Code to receive points)
- **Motivating**: "อีกนิดเดียวก็เป็น VIP!" (Almost VIP!)

### Button Copy Examples
- "ทำภารกิจ" (Do Mission)
- "แลกเลย" (Redeem Now)
- "ดูรายละเอียด" (View Details)
- "สแกน QR" (Scan QR)
- "บันทึก" (Save)
- "ยกเลิก" (Cancel)

### Error Messages
- Friendly, not blaming
- Provide solution
- Example: "ขออภัย ไม่สามารถเชื่อมต่อได้ กรุณาลองใหม่อีกครั้ง" (Sorry, cannot connect. Please try again)

### Success Messages
- Celebratory
- Clear outcome
- Example: "สำเร็จ! คุณได้รับ 50 แต้ม" (Success! You received 50 points)

---

## Files to Export from Stitch

1. **Screen Designs** (PNG, 2x)
   - Customer: Home, Missions, Rewards, Profile
   - Partner: Scanner, Dashboard
   - Admin: Dashboard, Mission Mgmt

2. **Component Library** (SVG where possible)
   - All reusable components
   - Icon set (24px, 32px, 48px)
   - Badges and labels

3. **Style Guide** (PDF/Figma)
   - Color palette
   - Typography scale
   - Spacing system
   - Component specs

4. **Design Tokens** (JSON/CSS)
   - Colors
   - Typography
   - Spacing
   - Shadows

5. **Prototype Flows** (Interactive)
   - User onboarding
   - Mission completion
   - Reward redemption
   - Partner scanning

6. **Assets** (Organized folder)
   - Logos
   - Icons
   - Illustrations
   - Patterns

---

## Quality Checklist

Before finalizing designs:

### Visual Quality
- [ ] All colors from approved palette
- [ ] Typography uses specified fonts
- [ ] Spacing follows 4px grid system
- [ ] Border radius consistent (16px cards, 24px buttons)
- [ ] Shadows applied correctly
- [ ] Thai text has adequate line-height (1.6)

### Accessibility
- [ ] Color contrast meets AA standard
- [ ] Touch targets minimum 44x44px
- [ ] Focus states visible
- [ ] Alt text planned for images
- [ ] Keyboard navigation considered

### Responsiveness
- [ ] Mobile-first design
- [ ] Tablet adaptation considered
- [ ] Desktop layout (for admin)
- [ ] Safe areas respected
- [ ] Breakpoints defined

### Thai Localization
- [ ] Thai fonts render properly
- [ ] Line-breaking works naturally
- [ ] Cultural elements respectful
- [ ] Copy is friendly and clear
- [ ] Numbers formatted correctly

### Brand Alignment
- [ ] Matches KueKan personality
- [ ] Represents government partnership
- [ ] Appeals to Thai users
- [ ] Suitable for age range 18-65+
- [ ] Encourages participation

---

**This reference board should guide all design decisions for KueKan platform.**

**Use in conjunction with:**
- `/03 Design/KueKan_Stitch_Design_Prompt_v1_2026-01.md` (Detailed prompts)
- `/03 Design/KueKan_Stitch_Quick_Start_Guide.md` (Fast implementation)

**Maintained by:** Stitch (KueKan Design Expert)
**Last Updated:** January 2, 2026
