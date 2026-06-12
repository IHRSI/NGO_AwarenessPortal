# InAmigos Foundation – Awareness Webpage
## Implementation Plan (for LLM/Developer to Build)

---

## 1. Project Brief

Build a single-page awareness website for **InAmigos Foundation**, a registered NGO. The site should be clean, basic-but-good-looking, structured, and require minimal effort while covering all required sections accurately.

**Tech stack:** HTML5, CSS3, vanilla JavaScript (only if needed for small enhancements like smooth scroll, mobile menu, or counters). No frameworks.

---

## 2. Research Findings (Verified Facts to Use)

- **Founded:** September 23, 2020, by **Mr. Govind Shukla (Founder & CEO)**
- **Legal status:** Section 8 Registered Non-Profit, Licensed by the Central Government, based in Bilaspur, Chhattisgarh
- **Certifications:** 80G & 12A Certified, CSR-1 Registered, NGO DARPAN (NITI Aayog), IAF ISO 9001:2015 Certified
- **Recognition / Credibility:**
  - Top 5 Best NGOs of the Year 2025 – Awarded by the Mayor of Delhi
  - SPJIMR SICA Finalist 2025
  - Founder honored by a Member of Parliament (Rajya Sabha)
  - 5+ year Internshala partner, onboarded 1 Lakh+ interns, ranked Top Employer on Internshala
- **Impact stats (from official site):** 200+ Volunteers, 28 States, 6 Causes, 50,000+ Beneficiaries
- **Tagline / Goal:** "Uniting Minds for A Change"
- **Address:** Ward No. 5, Gram Post, Sipat Ujwal Nagar, Bilaspur, Chhattisgarh – 495555
- **Contact:** inamigosfoundation@gmail.com | +91 626 730 9902
- **Social links:**
  - Instagram: instagram.com/inamigos
  - LinkedIn: linkedin.com/company/inamigos-foundation
  - YouTube: youtube.com/@inamigosfoundation
- **CTA links:**
  - Donate: https://rzp.io/l/kWQ87HP
  - Volunteer signup: https://forms.gle/AB4c1hLaDDmtrKGU7

### 6 Core Projects (use exactly these names + one-line descriptions)
1. **Seva** – Helping those in need with food, clothes, and essentials
2. **Bachpanshala** – Providing education and care to underprivileged children
3. **Jeev** – Rescuing and supporting animals
4. **Udaan** – Empowering women with skills and opportunities
5. **Prakriti** – Protecting the environment through clean-up drives and plantation
6. **Vikas** – Helping youth grow through internships and skill-building

---

## 3. Page Structure (Single Page, Top-to-Bottom)

| # | Section | Content Requirements |
|---|---------|----------------------|
| 1 | **Navbar** | Logo/name, sticky nav, links to About / Projects / Impact / Gallery / Contact, one CTA button (Volunteer), mobile hamburger menu |
| 2 | **Hero** | Headline using tagline "Uniting Minds for A Change", short intro sentence about the NGO and its 6 projects, two CTA buttons: "Become a Volunteer" and "Donate Now" |
| 3 | **About Us** | Founding story (date, founder name, location), legal/registration status (Section 8, Central Govt licensed), certifications list (80G, 12A, CSR-1, NGO DARPAN, ISO 9001:2015), short mission statement |
| 4 | **Recognition / Trust Badges** | Display as small badge/cards: Top 5 NGO 2025 (Mayor of Delhi), SPJIMR SICA Finalist 2025, Founder honored by Rajya Sabha MP, Internshala 5+ yr partner & 1 Lakh+ interns, Top Employer on Internshala |
| 5 | **Impact Stats** | 4 stat counters: 200+ Volunteers, 28 States, 6 Causes, 50,000+ Beneficiaries (optional simple count-up animation) |
| 6 | **Our Projects** | 6 cards, one per project, each with an icon/emoji, project name, one-line description (from list above) |
| 7 | **Social Impact Statement** | Short paragraph connecting all 6 projects to overall outcomes (education, welfare, environment, women & youth empowerment) and the scale (28 states, 50,000+ lives) |
| 8 | **Gallery** | Image grid (4–6 images) representing the projects/causes — use placeholder or royalty-free images by theme until real photos are added |
| 9 | **Call To Action** | Repeat Volunteer + Donate buttons, plus links to Instagram, LinkedIn, YouTube |
| 10 | **Footer** | NGO name, address, email, phone, registration tags (#InAmigos, NGO DARPAN, CSR-1, 80G & 12A), copyright line |

---

## 4. Design Guidelines

- **Color palette:** Green (primary, NGO/eco feel) + Orange/Yellow (accent, energy/CTA), neutral light background, dark text
- **Typography:** Clean sans-serif (system font stack), large readable headings, generous line-height
- **Layout:** CSS Grid/Flexbox for cards and galleries; max-width container (~1200px) centered
- **Responsiveness:** Mobile-first; navbar collapses to hamburger menu on small screens; project cards and gallery reflow to single column on mobile
- **Visual hierarchy:** Section titles centered, consistent padding/spacing between sections, hover effects on cards/buttons for interactivity
- **Imagery:** Use a hero background image, project icons (emoji or simple line icons), and a gallery grid

---

## 5. Optional JS Enhancements (only if it improves output without much effort)

- Smooth scroll for nav links
- Mobile menu toggle (hamburger open/close)
- Animated number count-up for impact stats when scrolled into view

---

## 6. Build Steps

1. Create `index.html` with semantic structure following section order in Table 1
2. Create `style.css` implementing the design guidelines (palette, layout, responsiveness)
3. (Optional) Create `script.js` for the small JS enhancements listed above
4. Populate all text content using the verified facts in Section 2 — do not invent statistics or claims
5. Add placeholder images for gallery/hero (to be swapped with real Instagram/Gallery photos later)
6. Test responsiveness at mobile, tablet, and desktop widths
7. Validate all external links (donation, volunteer form, social profiles) point to the correct URLs listed in Section 2

---

## 7. Post-Launch Suggestions

- Replace placeholder gallery images with real photos from InAmigos' Instagram and official Gallery page
- Add a founder photo + short quote in the About section
- Add a testimonials/volunteer spotlight section if more content is gathered later
- Deploy via GitHub Pages or Netlify
