---
id: seed
title: "My Bali Dogs Rescue"
type: seed
status: draft
createdAt: "2026-03-31"
updatedAt: "2026-03-31"
---

<flex_block type="seed-header">
{
  "name": "My Bali Dogs Rescue",
  "tagline": "Giving Bali's abandoned dogs a second chance at life.",
  "description": "A digital sanctuary connecting compassionate humans with rescued street dogs. Adopt, donate, or volunteer to end the cycle of suffering.",
  "logo": null,
  "domain": "mybalidogsrescue.org",
  "inputType": "codebase"
}
</flex_block>

# My Bali Dogs Rescue

## 1. Vision

If you have ever walked through the bustling streets of Canggu or the quiet backroads of Ubud, you have seen them. The Bali Heritage Dogs. They are brilliant, resilient, and fiercely loyal, but they are also caught in a cycle of overpopulation that leads to immense suffering. A tourist sipping a coconut sees a limping dog and their heart breaks. An expat wants to adopt but doesn't know who to trust. A global animal lover wants to donate but needs to know their money is actually buying medicine, not administration.

The problem with animal rescue isn't a lack of compassion; it's a lack of connection and transparency. Existing shelter websites often feel like sad, guilt-inducing archives of suffering. They paralyze visitors with tragedy instead of empowering them with hope.

My Bali Dogs Rescue changes the narrative. This platform isn't just an informational website; it is a bridge between the street and the sofa. It takes the visceral, emotional reality of a dog sanctuary and translates it into a digital experience that inspires immediate action. 

For the tourist, it provides a seamless way to book a volunteer walking shift, turning a holiday into a meaningful experience. For the expat, it offers a transparent, joyful adoption gallery that highlights a dog's personality and recovery, not just their trauma. And for the global donor, it breaks down exactly what their money does—proving that $50 isn't just a donation, it is a life-saving sterilization surgery.

The tone is sun-drenched, hopeful, and grounded. It doesn't look like a Silicon Valley tech startup, nor does it look like a sterile veterinary clinic. It looks like Bali. It feels like stepping into the sanctuary at golden hour: warm light, wagging tails, and real people doing hard work with absolute love. We are telling the story of survival, and we are giving the world a way to be part of it.

<flex_block type="brand">
{
  "personality": ["warm", "hopeful", "grounded", "compassionate", "transparent"],
  "voiceAttributes": ["speaks with deep empathy but no guilt-tripping", "focuses on tangible impact", "celebrates the resilience of the dogs", "approachable and conversational"],
  "values": ["every life matters", "transparency in funding", "education over judgment", "community-driven rescue"],
  "visualMood": "Sun-drenched naturalism. Warm earth tones, lush rice-paddy greens, and the golden light of a Bali sunset. Candid photography of happy dogs. Generous whitespace that lets the stories breathe.",
  "references": ["High-end eco-tourism editorials", "National Geographic nature photography", "Modern, transparent non-profit platforms like Charity: Water"]
}
</flex_block>

---

## 2. Features

### The Adoption Gallery
This isn't a spreadsheet of inventory; it's a portrait gallery. A filterable, visually rich grid of Polaroid-style cards showcasing available dogs. Each card features a candid, high-quality photo, the dog's name, age, and a clear status badge (Available, Pending, Adopted). Tapping a card doesn't just show stats; it opens their story—their journey from a drainage ditch or a beach to the sanctuary, complete with before-and-after photos. It makes falling in love inevitable.

### Tangible Donation Engine
Donors suffer from impact-ambiguity. This feature solves that by tying exact dollar amounts to physical outcomes. The donation widget doesn't just ask for money; it offers a menu of impact: "$10 vaccinates a puppy," "$50 sterilizes a dog," "$100 funds full rehabilitation." Integrated seamlessly with Stripe for both one-time and monthly recurring donations, the checkout experience is frictionless, secure, and emotionally rewarding, ending with a video of happy dogs playing.

### Rescue Stories (CMS)
A beautifully typeset editorial blog that serves as the emotional core of the platform. Managed by sanctuary staff through a simple headless CMS, these articles share deep-dive rescue transformations, educational pieces on why sterilization matters, and volunteer spotlights. It builds long-term engagement and serves as a powerful SEO engine for terms like "Bali dog rescue" and "volunteer animal shelter Bali."

### Volunteer Planner & Map
Tourists want to help but often don't know how. This feature removes all friction. An embedded, custom-styled Google Map pinpoints the sanctuary relative to popular hubs like Ubud or Seminyak. Clear walking hours and volunteer guidelines are presented alongside a simple group-booking form. A "Get Directions" button seamlessly hands off to native mobile maps, turning a casual thought into a booked visit.

### Live Instagram Feed
Rescue work happens every single day, and the website needs to feel just as alive. A live, auto-refreshing grid pulls the latest 6 posts from the sanctuary's Instagram. This provides daily "proof of life," showcasing the day-to-day joy and chaos of the shelter, building social proof, and driving cross-platform follower growth.

### Virtual Sponsorships
For the international supporter who cannot physically adopt a dog, this feature allows them to become a guardian from afar. Users can select a specific "Sponsorship Only" dog (often seniors or those with special medical needs) and commit to a monthly recurring donation. In return, they receive a sponsor badge and dedicated monthly photo/video updates of their specific dog.

<flex_block type="feature-list">
{
  "core": [
    {
      "id": "f-001",
      "icon": "lucide:heart-handshake",
      "title": "Adoption Gallery",
      "summary": "A visually rich, filterable portrait gallery of available dogs, highlighting their unique personalities and rescue journeys."
    },
    {
      "id": "f-002",
      "icon": "lucide:circle-dollar-sign",
      "title": "Tangible Donations",
      "summary": "Stripe-powered checkout that ties specific dollar amounts to real-world outcomes, like vaccines and sterilizations."
    },
    {
      "id": "f-003",
      "icon": "lucide:book-open",
      "title": "Rescue Stories",
      "summary": "An editorial blog sharing deep-dive rescue transformations, educational content, and volunteer spotlights."
    },
    {
      "id": "f-004",
      "icon": "lucide:map-pin",
      "title": "Volunteer Planner",
      "summary": "Frictionless visit planning for tourists, featuring embedded maps, clear schedules, and group booking forms."
    }
  ],
  "supporting": [
    {
      "id": "f-005",
      "icon": "lucide:instagram",
      "title": "Live Social Feed",
      "summary": "Auto-refreshing grid of the latest Instagram posts, providing daily proof-of-life and community building."
    },
    {
      "id": "f-006",
      "icon": "lucide:shield-check",
      "title": "Virtual Sponsorship",
      "summary": "Monthly recurring support for specific special-needs dogs, complete with personalized photo and video updates."
    },
    {
      "id": "f-007",
      "icon": "lucide:mail",
      "title": "Impact Newsletter",
      "summary": "Simple, inline email capture to keep supporters engaged with monthly updates and urgent rescue needs."
    }
  ]
}
</flex_block>

---

## 3. Pages

The website is orchestrated to guide visitors from emotional discovery to tangible action, adapting its narrative based on whether the user is a local adopter, a visiting tourist, or an international donor.

The **Home Page** is the emotional hook. It opens with a cinematic, full-viewport looping video of happy dogs playing in the Bali sun, overlaid with the mission statement and dual CTAs ("Adopt a Friend" / "Donate Now"). As the user scrolls, animated impact counters tick upward, quantifying the lives saved. A horizontal, snap-scroll carousel showcases featured dogs, followed by a stark, clear donation widget that translates dollars into meals and medicine. The page closes with the live Instagram grid, proving the shelter is active and thriving today.

Navigating to **Adopt a Friend**, the user finds a comprehensive guide. It splits into two clear paths: the process for locals and the process for expats (which involves complex international flight logistics). Below this sits the full Dog Gallery. It's highly filterable (age, gender, status). Clicking a dog doesn't navigate away; it expands their card into a rich detail view with a photo carousel, their full rescue story, and a prominent "Apply to Adopt" button.

The **Donate & Support** page is a masterclass in transparency. It strips away the guilt and focuses on empowerment. Large cards visually break down the costs of running the sanctuary. A sticky Stripe widget on the right (or bottom on mobile) lets the user seamlessly toggle between one-time and monthly gifts, select an amount, and check out without leaving the page. It also includes alternative support methods: bank transfer details for locals and a physical wishlist (rice, bleach, old towels) for visitors.

The **Visit & Volunteer** page is highly practical, designed primarily for tourists viewing on mobile devices. It clearly lists walking hours versus general visiting hours. An embedded Google Map provides immediate spatial context, and a "Get Directions" button hands off to their phone's native map app. For larger groups or long-term volunteers, a clean, mobile-optimized form allows them to request a specific date.

Finally, **Rescue Stories (Blog)** is the educational and narrative hub. A large featured hero highlights the most recent miracle recovery. Below, a grid of articles covers everything from the critical importance of island-wide sterilization to heartwarming updates on dogs living their best lives in Europe.

<flex_block type="page-inventory">
{
  "pages": [
    { "route": "/", "name": "Home", "type": "marketing", "description": "The emotional entry point. Hero video, impact stats, featured dogs, and quick donation widget." },
    { "route": "/adopt", "name": "Adopt a Friend", "type": "app", "description": "The adoption hub. Process guidelines, filterable dog gallery, and detailed individual profiles." },
    { "route": "/support", "name": "Donate & Support", "type": "marketing", "description": "Financial and physical support. Impact breakdown, Stripe checkout, sponsorships, and wishlists." },
    { "route": "/visit-volunteer", "name": "Visit & Volunteer", "type": "marketing", "description": "Tourist integration. Maps, visiting hours, volunteer tasks, and group booking forms." },
    { "route": "/blog", "name": "Rescue Stories", "type": "content", "description": "Editorial hub. Transformation stories, educational articles, and volunteer spotlights." },
    { "route": "/blog/:slug", "name": "Story Detail", "type": "content", "description": "Immersive reading experience for individual articles with rich media." }
  ]
}
</flex_block>

---

## 4. Data

The data model for the sanctuary is structured to separate public-facing editorial content from private administrative inquiries, all managed without the need for a complex, heavy backend. 

At the center is the **Dogs** collection. These aren't just inventory items; they are individuals. A dog has standard attributes (name, age, gender, breed mix) but also critical operational flags (sterilized status) and adoption status (Available, Pending, Adopted, Sponsorship Only). Every dog has a rich text "story" that chronicles their rescue, and an array of images.

The **Blog Posts** collection houses the narrative content. These are categorized into Rescue Stories, Education, and Events. They carry author attributions, publication dates, and rich markdown content. Because SEO is critical for a non-profit relying on tourist discovery, each post generates its own metadata and OpenGraph images.

Finally, the **Contacts** collection captures the inbound intent. Whether it's an adoption application, a general inquiry, or a group volunteer request, these submissions are securely captured and routed. They track the submitter's details, the type of inquiry, and the specific message.

<flex_block type="data-model">
{
  "collections": [
    {
      "name": "Dogs",
      "icon": "lucide:dog",
      "description": "The residents of the sanctuary. Profiles containing their medical status, adoption readiness, and personal rescue journey.",
      "keyFields": ["name", "age", "gender", "status", "sterilized", "images", "story"],
      "relationships": ["inquiries → Contacts (Adoption applications reference a specific dog)"]
    },
    {
      "name": "Blog Posts",
      "icon": "lucide:newspaper",
      "description": "Editorial content designed to educate and inspire. Managed by staff to share updates and explain the importance of animal welfare.",
      "keyFields": ["title", "slug", "category", "author", "featured_image", "content", "publish_date"],
      "relationships": ["featured_dog → Dogs (Stories often link back to the dog's adoption profile)"]
    },
    {
      "name": "Contacts",
      "icon": "lucide:inbox",
      "description": "Inbound submissions from the public. Securely routes volunteer requests, donations queries, and adoption applications to the team.",
      "keyFields": ["name", "email", "type", "message", "timestamp"],
      "relationships": ["subject → Dogs (If type is 'Adoption')"]
    }
  ]
}
</flex_block>

---

## 5. Flows

### The Tangible Gift (Donation)
A user from London, scrolling Instagram, sees a post about a newly rescued puppy and clicks the link in bio, landing on the **Donate & Support** page. They are immediately presented with a grid showing exactly what their money does. They click "$50 - Sterilization Surgery." They toggle the switch from "One-Time" to "Monthly," deciding to sponsor a surgery every month. They click "Donate via Stripe." A secure checkout overlay appears; they use Apple Pay, completing the transaction in seconds. They are redirected to a success page featuring a joyful, slow-motion video of dogs running on the beach, and an automated email hits their inbox with a tax receipt and a photo of a recently sterilized dog. They feel incredible about where their money went.

### The Street to Sofa (Adoption Inquiry)
An expat living in Canggu decides it's time to get a dog. They visit the **Adopt a Friend** page. They filter the gallery to show "Female" and "Available." They spot *Luna*, a sweet-looking Bali Heritage mix. Clicking her card, they read the story of how she was found with a broken leg in a rice paddy and see her remarkable recovery photos. Emotionally invested, they click "Apply to Adopt." A clean, mobile-friendly form asks about their living situation, landlord approval, and experience with dogs. They submit it. The shelter admin gets an email, reviews the form, and replies via WhatsApp to schedule a meet-and-greet for that weekend.

### The Meaningful Holiday (Volunteer Discovery)
A tourist is sitting in their hotel in Ubud, looking for something impactful to do tomorrow morning. They Google "volunteer with dogs Bali" and land on the **Visit & Volunteer** page. They quickly scan the "Visitor Hours" and see that morning dog walking happens between 7:00 AM and 9:00 AM. They check the embedded Google Map and realize the sanctuary is only 15 minutes away. They tap "Get Directions," which seamlessly opens Gojek/Grab on their phone to estimate the ride. Realizing they have a group of four friends, they scroll down to the Group Visit form, quickly typing in their details and hitting send so the shelter knows to expect a small crowd tomorrow.

<flex_block type="flow">
{
  "id": "flow-tangible-donation",
  "title": "The Tangible Gift",
  "actor": "International Donor",
  "trigger": "Lands on /support with intent to help financially",
  "steps": [
    "Views the impact breakdown cards ($10, $20, $50, $100)",
    "Toggles frequency to 'Monthly'",
    "Selects the $50 (Sterilization) preset",
    "Clicks 'Donate via Stripe' and completes Apple Pay/Card checkout",
    "Redirected to joyful success page with video",
    "Receives automated email receipt with an impact story"
  ],
  "outcome": "A seamless, emotionally rewarding transaction that turns a one-time impulse into recurring revenue."
}
</flex_block>

<flex_block type="flow">
{
  "id": "flow-street-to-sofa",
  "title": "The Street to Sofa",
  "actor": "Local Expat",
  "trigger": "Browsing /adopt looking for a companion",
  "steps": [
    "Filters the dog gallery by 'Available' and views cards",
    "Clicks a specific dog (e.g., Luna) to read her rescue story",
    "Reviews medical stats (sterilized, vaccinated)",
    "Clicks 'Apply to Adopt' and fills out the application form",
    "Submits form; sees success message outlining the timeline",
    "Admin receives alert and initiates WhatsApp contact for a shelter visit"
  ],
  "outcome": "A dog finds a potential forever home, and the shelter vets a qualified applicant without administrative chaos."
}
</flex_block>

<flex_block type="flow">
{
  "id": "flow-meaningful-holiday",
  "title": "The Meaningful Holiday",
  "actor": "Tourist in Bali",
  "trigger": "Searching for ethical animal interactions near their hotel",
  "steps": [
    "Lands on the Visit & Volunteer page",
    "Reads the daily schedule and walking hours",
    "Interacts with the embedded Google Map to check distance",
    "Taps 'Get Directions' to open native navigation app",
    "Fills out the Group Visit form to notify the shelter of a party of 4",
    "Arrives the next morning ready to walk dogs"
  ],
  "outcome": "Tourists provide free labor (dog walking) and usually end up leaving a cash donation or buying merchandise on-site."
}
</flex_block>

---

## 6. Design

The visual identity of My Bali Dogs Rescue is built around sun-drenched naturalism. It rejects the sterile, clinical whites of a veterinary hospital and the depressing, dark tones of a traditional charity guilt-trip. Instead, the UI feels like Bali: lush, warm, and alive. 

The canvas is a warm, organic cream—like sun-bleached paper. Against this, the primary color is a rich, natural Sea Green, echoing the island's rice paddies and symbolizing healing and growth. For urgent actions—specifically the "Donate Now" buttons and heart icons—a Burnt Orange provides perfect contrast, capturing the energy of a Bali sunset. 

Typography pairs the geometric, highly approachable 'Outfit' for display headings with the eminently readable 'DM Sans' for body copy, ensuring that long rescue stories remain effortless to read, even on a phone screen glaring in the tropical sun. 

Cards use a "Polaroid" pattern: slightly elevated with soft, warm shadows, generous padding, and images that fill the top bounds. Corners are generously rounded (12px to 16px) because nature has no sharp edges. Interactions are buttery and smooth, with subtle hover lifts that make the interface feel tactile and responsive. 

Dark mode does not invert to a cold, developer-tool gray. It shifts to a deep, rich espresso brown. The green and orange accents lighten slightly to maintain perfect WCAG contrast while preserving the emotional warmth of the sanctuary at dusk.

<flex_block type="tokens">
{
  "category": "colors",
  "mode": "light",
  "tokens": {
    "--color-primary": "oklch(57% 0.12 150)",
    "--color-primary-hover": "oklch(52% 0.12 150)",
    "--color-primary-subtle": "oklch(92% 0.04 150)",
    "--color-accent": "oklch(65% 0.16 45)",
    "--color-accent-hover": "oklch(60% 0.16 45)",
    "--color-bg": "oklch(98% 0.01 80)",
    "--color-surface": "oklch(94% 0.02 80)",
    "--color-border": "oklch(88% 0.02 80)",
    "--color-text": "oklch(20% 0.01 80)",
    "--color-text-muted": "oklch(45% 0.02 80)",
    "--color-success": "oklch(65% 0.15 150)",
    "--color-warning": "oklch(75% 0.15 70)",
    "--color-danger": "oklch(60% 0.18 25)"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "colors",
  "mode": "dark",
  "tokens": {
    "--color-primary": "oklch(65% 0.12 150)",
    "--color-primary-hover": "oklch(70% 0.12 150)",
    "--color-primary-subtle": "oklch(35% 0.06 150)",
    "--color-accent": "oklch(70% 0.16 45)",
    "--color-accent-hover": "oklch(75% 0.16 45)",
    "--color-bg": "oklch(20% 0.015 65)",
    "--color-surface": "oklch(26% 0.015 65)",
    "--color-border": "oklch(35% 0.015 65)",
    "--color-text": "oklch(95% 0.01 80)",
    "--color-text-muted": "oklch(75% 0.01 80)",
    "--color-success": "oklch(70% 0.15 150)",
    "--color-warning": "oklch(80% 0.15 70)",
    "--color-danger": "oklch(65% 0.18 25)"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "typography",
  "tokens": {
    "--font-display": "'Outfit', system-ui, sans-serif",
    "--font-body": "'DM Sans', system-ui, sans-serif",
    "--font-mono": "'JetBrains Mono', monospace",
    "--font-size-xs": "0.75rem",
    "--font-size-sm": "0.875rem",
    "--font-size-base": "1rem",
    "--font-size-lg": "1.125rem",
    "--font-size-xl": "1.25rem",
    "--font-size-2xl": "1.5rem",
    "--font-size-3xl": "2rem",
    "--font-size-4xl": "2.5rem",
    "--font-size-5xl": "3.5rem",
    "--font-size-6xl": "4.5rem",
    "--font-weight-normal": "400",
    "--font-weight-medium": "500",
    "--font-weight-bold": "700",
    "--font-weight-extrabold": "800"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "spacing",
  "tokens": {
    "--space-1": "0.25rem",
    "--space-2": "0.5rem",
    "--space-3": "0.75rem",
    "--space-4": "1rem",
    "--space-6": "1.5rem",
    "--space-8": "2rem",
    "--space-12": "3rem",
    "--space-16": "4rem",
    "--space-24": "6rem"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "radii",
  "tokens": {
    "--radius-sm": "0.375rem",
    "--radius-md": "0.5rem",
    "--radius-lg": "0.75rem",
    "--radius-xl": "1rem",
    "--radius-2xl": "1.5rem",
    "--radius-full": "9999px"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "shadows",
  "tokens": {
    "--shadow-sm": "0 1px 2px oklch(20% 0.02 65 / 0.05)",
    "--shadow-md": "0 4px 12px oklch(20% 0.02 65 / 0.08), 0 1px 3px oklch(20% 0.02 65 / 0.04)",
    "--shadow-lg": "0 12px 32px oklch(20% 0.02 65 / 0.12), 0 4px 8px oklch(20% 0.02 65 / 0.06)"
  }
}
</flex_block>

<flex_block type="tokens">
{
  "category": "transitions",
  "tokens": {
    "--transition-fast": "150ms ease-out",
    "--transition-base": "250ms ease-out",
    "--transition-slow": "400ms cubic-bezier(0.4, 0, 0.2, 1)",
    "--ease-spring": "cubic-bezier(0.34, 1.56, 0.64, 1)"
  }
}
</flex_block>

### Component Patterns

**The Polaroid Dog Card:** 
The background uses `--color-surface` with a `--radius-xl` container. The top 60% is an edge-to-edge photo. The bottom 40% contains the dog's name (`--font-display`, `--font-weight-bold`), their age/gender (`--font-body`, `--color-text-muted`), and a status pill. On hover, the card lifts slightly (`transform: translateY(-4px)`) and the shadow deepens to `--shadow-lg`, inviting a click.

**The Donation Impact Widget:** 
A grid of preset amount buttons (`$10`, `$20`, `$50`). Unselected buttons are outlined with `--color-border`. When selected, the button fills with `--color-primary-subtle` and gains a thick `--color-primary` border. Below the grid, a dynamic text block updates to show exactly what the selected amount buys (e.g., "This sterilizes 1 dog"). The final CTA is always `--color-accent` (Orange), drawing the eye immediately.

**Microcopy Guide:**
- *Good:* "Meet Luna" | *Bad:* "View Details"
- *Good:* "Save a life today" | *Bad:* "Submit Payment"
- *Good:* "Find us in Ubud" | *Bad:* "Location Data"
- *Good:* "12 dogs are waiting for forever homes" | *Bad:* "Search Results: 12"

<flex_block type="mockup-html" id="landing-preview">
<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Bali Dogs Rescue</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=JetBrains+Mono:wght@400;500&family=Outfit:wght@400;500;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/@iconify/iconify@3/dist/iconify.min.js"></script>
  <style>
    :root, [data-theme="light"] {
      --color-primary: oklch(57% 0.12 150);
      --color-primary-hover: oklch(52% 0.12 150);
      --color-primary-subtle: oklch(92% 0.04 150);
      --color-accent: oklch(65% 0.16 45);
      --color-accent-hover: oklch(60% 0.16 45);
      --color-bg: oklch(98% 0.01 80);
      --color-surface: oklch(94% 0.02 80);
      --color-border: oklch(88% 0.02 80);
      --color-text: oklch(20% 0.01 80);
      --color-text-muted: oklch(45% 0.02 80);
      --color-success: oklch(65% 0.15 150);
      
      --font-display: 'Outfit', system-ui, sans-serif;
      --font-body: 'DM Sans', system-ui, sans-serif;
      --font-mono: 'JetBrains Mono', monospace;
      
      --space-1: 0.25rem; --space-2: 0.5rem; --space-3: 0.75rem; 
      --space-4: 1rem; --space-6: 1.5rem; --space-8: 2rem; 
      --space-12: 3rem; --space-16: 4rem; --space-24: 6rem;
      
      --radius-sm: 0.375rem; --radius-md: 0.5rem; --radius-lg: 0.75rem; 
      --radius-xl: 1rem; --radius-2xl: 1.5rem; --radius-full: 9999px;
      
      --shadow-sm: 0 1px 2px oklch(20% 0.02 65 / 0.05);
      --shadow-md: 0 4px 12px oklch(20% 0.02 65 / 0.08), 0 1px 3px oklch(20% 0.02 65 / 0.04);
      --shadow-lg: 0 12px 32px oklch(20% 0.02 65 / 0.12), 0 4px 8px oklch(20% 0.02 65 / 0.06);
      
      --transition-base: 250ms ease-out;
      --ease-spring: cubic-bezier(0.34, 1.56, 0.64, 1);
    }

    [data-theme="dark"] {
      --color-primary: oklch(65% 0.12 150);
      --color-primary-hover: oklch(70% 0.12 150);
      --color-primary-subtle: oklch(35% 0.06 150);
      --color-accent: oklch(70% 0.16 45);
      --color-accent-hover: oklch(75% 0.16 45);
      --color-bg: oklch(20% 0.015 65);
      --color-surface: oklch(26% 0.015 65);
      --color-border: oklch(35% 0.015 65);
      --color-text: oklch(95% 0.01 80);
      --color-text-muted: oklch(75% 0.01 80);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    
    body {
      font-family: var(--font-body);
      background-color: var(--color-bg);
      color: var(--color-text);
      line-height: 1.6;
      overflow-x: hidden;
      transition: background-color var(--transition-base), color var(--transition-base);
    }

    h1, h2, h3 {
      font-family: var(--font-display);
      font-weight: 700;
      line-height: 1.2;
    }

    a { text-decoration: none; color: inherit; }
    ul { list-style: none; }
    img { max-width: 100%; display: block; }

    /* Navbar */
    .nav {
      position: fixed;
      top: 0; width: 100%;
      background: color-mix(in oklch, var(--color-bg) 85%, transparent);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--color-border);
      z-index: 100;
      padding: var(--space-4) var(--space-6);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .nav-brand {
      display: flex;
      align-items: center;
      gap: var(--space-2);
      font-family: var(--font-display);
      font-weight: 800;
      font-size: 1.25rem;
      color: var(--color-primary);
    }

    .nav-brand .iconify { font-size: 1.5rem; }

    .nav-links {
      display: none;
      gap: var(--space-6);
      font-weight: 500;
      color: var(--color-text-muted);
    }

    @media(min-width: 768px) { .nav-links { display: flex; } }

    .nav-links a:hover { color: var(--color-primary); }

    .nav-actions {
      display: flex;
      align-items: center;
      gap: var(--space-4);
    }

    .theme-toggle {
      background: none; border: none;
      color: var(--color-text-muted);
      cursor: pointer;
      font-size: 1.25rem;
      padding: var(--space-1);
      border-radius: var(--radius-full);
      transition: background var(--transition-base);
    }
    
    .theme-toggle:hover { background: var(--color-surface); }

    /* Buttons */
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: var(--space-2);
      padding: var(--space-3) var(--space-6);
      border-radius: var(--radius-full);
      font-weight: 700;
      cursor: pointer;
      transition: all var(--transition-base);
      border: none;
      font-family: var(--font-display);
    }

    .btn-primary { background: var(--color-primary); color: white; }
    .btn-primary:hover { background: var(--color-primary-hover); transform: translateY(-2px); box-shadow: var(--shadow-md); }
    
    .btn-accent { background: var(--color-accent); color: white; }
    .btn-accent:hover { background: var(--color-accent-hover); transform: translateY(-2px); box-shadow: var(--shadow-md); }

    /* Hero */
    .hero {
      position: relative;
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: var(--space-6);
      margin-top: 70px;
    }

    .hero-bg {
      position: absolute;
      inset: 0;
      z-index: -2;
      background-image: url('https://images.unsplash.com/photo-1548199973-03cce0bbc87b?w=1600&q=80');
      background-size: cover;
      background-position: center;
    }

    .hero-overlay {
      position: absolute;
      inset: 0;
      z-index: -1;
      background: linear-gradient(to top, oklch(0% 0 0 / 0.8), oklch(0% 0 0 / 0.3));
    }

    .hero-content {
      max-width: 800px;
      color: white;
      animation: fadeUp 0.8s ease-out forwards;
    }

    .hero-title {
      font-size: clamp(2.5rem, 5vw, 4.5rem);
      font-weight: 800;
      margin-bottom: var(--space-4);
      text-shadow: 0 4px 12px rgba(0,0,0,0.5);
    }

    .hero-subtitle {
      font-size: clamp(1.125rem, 2vw, 1.5rem);
      margin-bottom: var(--space-8);
      opacity: 0.9;
    }

    .hero-ctas {
      display: flex;
      gap: var(--space-4);
      justify-content: center;
      flex-wrap: wrap;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Stats */
    .stats-section {
      padding: var(--space-12) var(--space-6);
      background: var(--color-primary);
      color: white;
      margin-top: calc(var(--space-8) * -1);
      position: relative;
      z-index: 10;
      border-radius: var(--radius-2xl) var(--radius-2xl) 0 0;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: var(--space-8);
      max-width: 1200px;
      margin: 0 auto;
      text-align: center;
    }

    .stat-num {
      font-family: var(--font-display);
      font-size: 3.5rem;
      font-weight: 800;
      margin-bottom: var(--space-2);
    }

    .stat-label {
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 1px;
      font-size: 0.875rem;
      opacity: 0.9;
    }

    /* Carousel */
    .carousel-section {
      padding: var(--space-24) var(--space-6);
      max-width: 1200px;
      margin: 0 auto;
    }

    .section-header {
      text-align: center;
      margin-bottom: var(--space-12);
    }

    .section-title {
      font-size: 2.5rem;
      color: var(--color-primary);
      margin-bottom: var(--space-4);
    }

    .carousel {
      display: flex;
      gap: var(--space-6);
      overflow-x: auto;
      padding-bottom: var(--space-8);
      scroll-snap-type: x mandatory;
      scrollbar-width: none;
    }
    
    .carousel::-webkit-scrollbar { display: none; }

    .dog-card {
      flex: 0 0 300px;
      background: var(--color-surface);
      border-radius: var(--radius-xl);
      overflow: hidden;
      scroll-snap-align: start;
      box-shadow: var(--shadow-sm);
      border: 1px solid var(--color-border);
      transition: transform var(--transition-base), box-shadow var(--transition-base);
    }

    .dog-card:hover {
      transform: translateY(-8px);
      box-shadow: var(--shadow-lg);
    }

    .dog-img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    .dog-info {
      padding: var(--space-6);
    }

    .dog-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: var(--space-2);
    }

    .dog-name { font-size: 1.5rem; }
    
    .dog-meta {
      color: var(--color-text-muted);
      font-size: 0.875rem;
      margin-bottom: var(--space-4);
      display: flex;
      gap: var(--space-2);
    }

    .status-badge {
      display: inline-block;
      padding: var(--space-1) var(--space-3);
      border-radius: var(--radius-full);
      font-size: 0.75rem;
      font-weight: 700;
      text-transform: uppercase;
      background: var(--color-success);
      color: white;
    }

    /* Donation Widget */
    .donate-section {
      background: var(--color-surface);
      padding: var(--space-24) var(--space-6);
    }

    .donate-container {
      max-width: 1000px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 1fr;
      gap: var(--space-12);
      align-items: center;
    }

    @media(min-width: 800px) { .donate-container { grid-template-columns: 1fr 1fr; } }

    .donate-widget {
      background: var(--color-bg);
      border-radius: var(--radius-2xl);
      padding: var(--space-8);
      box-shadow: var(--shadow-lg);
      border: 1px solid var(--color-border);
    }

    .amount-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: var(--space-3);
      margin: var(--space-6) 0;
    }

    .amount-btn {
      background: var(--color-surface);
      border: 2px solid var(--color-border);
      color: var(--color-text);
      padding: var(--space-3);
      border-radius: var(--radius-lg);
      font-family: var(--font-display);
      font-size: 1.25rem;
      font-weight: 700;
      cursor: pointer;
      transition: all var(--transition-base);
    }

    .amount-btn:hover {
      border-color: var(--color-primary);
      color: var(--color-primary);
    }

    .amount-btn.active {
      background: var(--color-primary-subtle);
      border-color: var(--color-primary);
      color: var(--color-primary);
    }

    .impact-text {
      text-align: center;
      color: var(--color-text-muted);
      font-weight: 500;
      margin-bottom: var(--space-6);
      min-height: 48px;
    }

  </style>
</head>
<body>

  <nav class="nav">
    <a href="#" class="nav-brand">
      <span class="iconify" data-icon="lucide:dog"></span>
      My Bali Dogs
    </a>
    <div class="nav-links">
      <a href="#">Adopt</a>
      <a href="#">Support</a>
      <a href="#">Visit</a>
      <a href="#">Stories</a>
    </div>
    <div class="nav-actions">
      <button class="theme-toggle" id="theme-toggle" aria-label="Toggle theme">
        <span class="iconify" data-icon="lucide:moon" id="theme-icon"></span>
      </button>
      <a href="#donate" class="btn btn-accent" style="padding: 0.5rem 1rem;">Donate</a>
    </div>
  </nav>

  <header class="hero">
    <div class="hero-bg"></div>
    <div class="hero-overlay"></div>
    <div class="hero-content">
      <h1 class="hero-title">Giving Bali's Abandoned Dogs a Second Chance.</h1>
      <p class="hero-subtitle">We rescue, rehabilitate, and rehome street dogs in Bali. Because every dog deserves to feel safe and loved.</p>
      <div class="hero-ctas">
        <a href="#adopt" class="btn btn-primary">
          <span class="iconify" data-icon="lucide:heart"></span> Adopt a Friend
        </a>
        <a href="#donate" class="btn btn-accent">
          <span class="iconify" data-icon="lucide:circle-dollar-sign"></span> Donate Now
        </a>
      </div>
    </div>
  </header>

  <section class="stats-section">
    <div class="stats-grid">
      <div>
        <div class="stat-num">347</div>
        <div class="stat-label">Dogs Rescued</div>
      </div>
      <div>
        <div class="stat-num">1,205</div>
        <div class="stat-label">Sterilizations</div>
      </div>
      <div>
        <div class="stat-num">189</div>
        <div class="stat-label">Happy Homes</div>
      </div>
    </div>
  </section>

  <section class="carousel-section" id="adopt">
    <div class="section-header">
      <h2 class="section-title">Waiting for Forever</h2>
      <p style="color: var(--color-text-muted); font-size: 1.125rem;">These beautiful souls are rehabilitated and ready for adoption.</p>
    </div>
    
    <div class="carousel">
      <!-- Dog 1 -->
      <div class="dog-card">
        <img src="https://images.unsplash.com/photo-1587300003388-59208cc962cb?w=600&q=80" alt="Luna" class="dog-img">
        <div class="dog-info">
          <div class="dog-header">
            <h3 class="dog-name">Luna</h3>
            <span class="status-badge">Available</span>
          </div>
          <div class="dog-meta">
            <span class="iconify" data-icon="lucide:info"></span> Female • 2 years
          </div>
          <button class="btn btn-primary" style="width: 100%; margin-top: var(--space-4);">Meet Luna</button>
        </div>
      </div>

      <!-- Dog 2 -->
      <div class="dog-card">
        <img src="https://images.unsplash.com/photo-1558788353-f76d92427f16?w=600&q=80" alt="Koda" class="dog-img">
        <div class="dog-info">
          <div class="dog-header">
            <h3 class="dog-name">Koda</h3>
            <span class="status-badge" style="background: var(--color-warning);">Pending</span>
          </div>
          <div class="dog-meta">
            <span class="iconify" data-icon="lucide:info"></span> Male • 3 years
          </div>
          <button class="btn btn-primary" style="width: 100%; margin-top: var(--space-4);">Meet Koda</button>
        </div>
      </div>

      <!-- Dog 3 -->
      <div class="dog-card">
        <img src="https://images.unsplash.com/photo-1543466835-00a7907e9de1?w=600&q=80" alt="Rio" class="dog-img">
        <div class="dog-info">
          <div class="dog-header">
            <h3 class="dog-name">Rio</h3>
            <span class="status-badge">Available</span>
          </div>
          <div class="dog-meta">
            <span class="iconify" data-icon="lucide:info"></span> Male • 6 months
          </div>
          <button class="btn btn-primary" style="width: 100%; margin-top: var(--space-4);">Meet Rio</button>
        </div>
      </div>
      
      <!-- Dog 4 -->
      <div class="dog-card">
        <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d?w=600&q=80" alt="Shadow" class="dog-img">
        <div class="dog-info">
          <div class="dog-header">
            <h3 class="dog-name">Shadow</h3>
            <span class="status-badge" style="background: var(--color-text-muted);">Adopted</span>
          </div>
          <div class="dog-meta">
            <span class="iconify" data-icon="lucide:info"></span> Male • 3 years
          </div>
          <button class="btn btn-primary" style="width: 100%; margin-top: var(--space-4); background: var(--color-surface); color: var(--color-text); border: 1px solid var(--color-border);">Read Story</button>
        </div>
      </div>
    </div>
  </section>

  <section class="donate-section" id="donate">
    <div class="donate-container">
      <div>
        <h2 class="section-title">Your Donation Changes Lives</h2>
        <p style="color: var(--color-text-muted); font-size: 1.125rem; margin-bottom: var(--space-6);">We receive no government funding. Every bowl of rice, every vaccination, and every surgery is paid for by people like you who refuse to look away.</p>
        <ul style="display: flex; flex-direction: column; gap: var(--space-4); margin-bottom: var(--space-8);">
          <li style="display: flex; align-items: center; gap: var(--space-3);">
            <span class="iconify" data-icon="lucide:check-circle-2" style="color: var(--color-primary); font-size: 1.5rem;"></span>
            <strong>$10</strong> provides a full vaccination pack.
          </li>
          <li style="display: flex; align-items: center; gap: var(--space-3);">
            <span class="iconify" data-icon="lucide:check-circle-2" style="color: var(--color-primary); font-size: 1.5rem;"></span>
            <strong>$20</strong> feeds a dog for an entire month.
          </li>
          <li style="display: flex; align-items: center; gap: var(--space-3);">
            <span class="iconify" data-icon="lucide:check-circle-2" style="color: var(--color-primary); font-size: 1.5rem;"></span>
            <strong>$50</strong> funds a life-saving sterilization surgery.
          </li>
        </ul>
      </div>
      
      <div class="donate-widget">
        <h3 style="margin-bottom: var(--space-2); text-align: center;">Make an Impact</h3>
        <p style="text-align: center; color: var(--color-text-muted); font-size: 0.875rem;">Select an amount to give securely via Stripe.</p>
        
        <div class="amount-grid">
          <button class="amount-btn" data-impact="Provides a full vaccination pack for a puppy."> $10 </button>
          <button class="amount-btn" data-impact="Feeds a rescue dog high-quality food for a month."> $20 </button>
          <button class="amount-btn active" data-impact="Funds a sterilization surgery to stop the cycle."> $50 </button>
        </div>
        
        <p class="impact-text" id="impact-text">Funds a sterilization surgery to stop the cycle.</p>
        
        <button class="btn btn-accent" style="width: 100%; padding: var(--space-4); font-size: 1.25rem;">
          Donate via Stripe
        </button>
      </div>
    </div>
  </section>

  <script>
    // Theme Toggle
    const themeToggle = document.getElementById('theme-toggle');
    const themeIcon = document.getElementById('theme-icon');
    const html = document.documentElement;

    themeToggle.addEventListener('click', () => {
      const currentTheme = html.getAttribute('data-theme');
      const newTheme = currentTheme === 'light' ? 'dark' : 'light';
      html.setAttribute('data-theme', newTheme);
      themeIcon.setAttribute('data-icon', newTheme === 'dark' ? 'lucide:sun' : 'lucide:moon');
    });

    // Donation Widget Interactivity
    const amountBtns = document.querySelectorAll('.amount-btn');
    const impactText = document.getElementById('impact-text');

    amountBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        amountBtns.forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        impactText.style.opacity = 0;
        setTimeout(() => {
          impactText.textContent = btn.getAttribute('data-impact');
          impactText.style.opacity = 1;
        }, 150);
      });
    });
  </script>
</body>
</html>
</flex_block>

---

## 7. Technical

The sanctuary's technical architecture is optimized for three specific realities: a global donor base that demands instant page loads, non-technical staff in Bali who need to update dog profiles easily, and a non-profit budget that requires low-to-zero fixed hosting costs.

<flex_block type="stack">
{
  "framework": { "name": "Astro", "why": "Ships zero JavaScript by default, making the site incredibly fast on 3G networks in Bali while maintaining perfect SEO for global donors." },
  "database": { "name": "Turso (LibSQL)", "why": "Edge-based SQLite that is absurdly fast, has a generous free tier, and easily handles the structured data of dog profiles and contacts." },
  "auth": { "name": "None required", "why": "This is a public-facing conversion and editorial site; no user accounts are necessary, removing massive overhead." },
  "hosting": { "name": "Vercel", "why": "Global edge CDN ensures the site loads instantly whether the visitor is in Seminyak, Sydney, or Seattle." },
  "payments": { "name": "Stripe Checkout", "why": "The gold standard for trust. Handles global currencies, recurring subscriptions, and PCI compliance off-site." },
  "cms": { "name": "Astro Content Collections", "why": "Allows staff to write Markdown files for dogs and blogs, which Astro compiles with strict type safety at build time." }
}
</flex_block>

This stack means there are almost no moving parts in production. The site is statistically generated (SSG) where possible. The only dynamic server-side interactions are form submissions (routed through Netlify Forms or Formspree) and Stripe webhook fulfillments. This guarantees near-100% uptime and zero maintenance headaches for the rescue team.

---

## 8. Content

The shelter has incredible stories, but they are currently trapped in the minds of the volunteers or scattered across social media. To build the emotional bridge that drives adoptions and donations, we need to structure and digitize these narratives.

**What We Have:**
The foundational architecture is in place. We have the content schemas for Dog Profiles and Blog Posts. We have a handful of initial dog profiles (Luna, Koda, Rio) with their basic stats and short rescue blurbs. We also have the structural site settings—visiting hours, sanctuary location, and preset donation impact descriptions. 

**What We Need:**
This site lives or dies on its photography and storytelling. A dog with a blurry, low-lit photo will sit in the sanctuary for months; a dog with a vibrant, golden-hour portrait will be adopted in a week.

<flex_block type="content-inventory">
{
  "have": [
    { "type": "schema", "source": "codebase", "notes": "Zod schemas for Astro content collections (Dogs, Blogs) are fully defined and type-safe." },
    { "type": "profiles", "source": "codebase", "notes": "Initial dog profiles (Luna, Koda, Rio, Shadow) with basic narrative text." },
    { "type": "copy", "source": "codebase", "notes": "Core mission statements, visiting hours, and impact breakdowns for donations." }
  ],
  "need": [
    { "type": "photography", "description": "High-resolution, golden-hour portraits of all available dogs. No cage bars in the photos; show them playing or resting in the grass." },
    { "type": "video", "description": "A high-quality 10-15 second looping video of happy dogs for the hero section (to replace the current placeholder)." },
    { "type": "copy", "description": "Long-form rescue stories for the blog. We need the gritty details of the rescue combined with the joy of the recovery." },
    { "type": "documents", "description": "A downloadable PDF 'Volunteer Guide' and 'Adoption Requirements' to link from the Visit and Adopt pages." },
    { "type": "copy", "description": "Automated email templates for Stripe donation receipts. They need to sound like they come from a human, not a robot." }
  ]
}
</flex_block>

**Voice & Tone Guide:**
- *Never say:* "Please help us, we are out of money and the dogs are starving." (Desperation causes fatigue).
- *Instead say:* "Your $50 donation buys 50 kilos of rice, keeping 20 dogs fed for a week. Join the pack." (Empowerment drives action).
- *Never say:* "Abandoned mutt looking for a home."
- *Instead say:* "A resilient Bali Heritage dog who survived the streets and is ready for the sofa."

---

## 9. Downstream Alerts
- ALERT: [Stripe Indonesia capabilities] → Ensure Stripe supports the specific payout requirements for an Indonesian NGO, or verify if the organization uses a foreign registered entity (e.g., an Australian or US 501c3) for fund collection.
- ALERT: [Instagram API stability] → The Instagram Basic Display API is notoriously brittle and deprecating. We need to confirm if we should use a robust third-party widget (like Elfsight) or rely heavily on the fallback static grid to prevent broken UI on the homepage.
- ALERT: [Astro Content vs CMS] → The current codebase uses Astro Content Collections (Markdown files). We need to confirm if the shelter staff is comfortable writing Markdown in GitHub, or if we need to wire up a visual headless CMS (like Sanity or Decap) for them before launch.