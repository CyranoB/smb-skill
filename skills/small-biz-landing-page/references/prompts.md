# Small Business Landing Page — Reference Prompts

This document is the reference guide for the `small-biz-landing-page` skill. Use it to detect business type, guide the interview, and generate the outline. It is read during execution — it is not shown to the user.

## Table of Contents

- [Business Archetype Detection](#business-archetype-detection)
- [Interview Questions](#interview-questions)
- [Landing Page Outline Format](#landing-page-outline-format)
- [Business Type Adaptations](#business-type-adaptations)
- [Copy Tone Guidelines](#copy-tone-guidelines)

---

## Business Archetype Detection

After the user describes their business, classify it into one of these archetypes. Use the archetype to select conditional interview questions and adapt the landing page outline.

| Archetype | Examples | Key Trait |
|---|---|---|
| **Home / Personal Services** | Babysitter, house cleaner, dog walker, nanny, pet sitter, errand runner, elderly companion, house sitter, personal organizer, moving helper | Goes to the customer's location; schedule-based availability |
| **Skilled Trades** | Plumber, electrician, HVAC, roofer, handyman, painter, locksmith, pressure washer, carpet cleaner, window cleaner, fence installer, appliance repair | Licensed/insured work; emergency and scheduled jobs |
| **Retail / Storefront** | Salon, barbershop, bakery, boutique, florist, dry cleaner | Fixed location with walk-in or appointment hours |
| **Food & Beverage** | Restaurant, cafe, food truck, caterer, meal prep, juice bar | Menu-driven; dine-in, takeout, delivery, or catering |
| **Professional Services** | Accountant, lawyer, consultant, real estate agent, bookkeeper, notary, translator, resume writer, virtual assistant | Expertise-based; appointments or project engagements |
| **Fitness / Wellness** | Personal trainer, yoga studio, massage therapist, chiropractor, nutritionist, acupuncturist, physical therapist, meditation teacher, prenatal coach | Class schedules, memberships, certifications |
| **Teaching / Lessons** | Piano teacher, math tutor, language tutor, music instructor, art teacher, driving instructor, swim instructor, SAT prep tutor, coding instructor, dance teacher | Skill-based instruction sold per session or package; in-person, at student's location, or virtual |
| **Creative / Events** | Photographer, videographer, DJ, event planner, face painter, balloon artist, makeup artist, calligrapher, illustrator, tattoo artist | Portfolio-driven; booked for specific occasions or projects; visual work samples are critical |

If a business straddles two archetypes, pick the one that best matches their primary revenue model. If truly ambiguous, ask a natural question like: "Are you primarily teaching a skill to individuals, creating work for events/clients, or something else?" — then classify from their answer.

---

## Interview Questions

### Round 1 — Universal (always ask)

1. What is your business name?
2. What does your business do? *(Use this answer to detect the archetype.)*
3. What area do you serve? *(City, neighborhood, radius, or "customers come to us.")*
4. Who is your ideal customer? *(Age range, situation, need — whatever comes naturally.)*
5. What makes you different from your competitors? *(Even one thing is fine.)*

### Round 2 — Archetype-Specific

After detecting the archetype, ask the relevant follow-ups below. Skip any question the user already answered in round 1.

**Home / Personal Services**
- How many years of experience do you have?
- Do you have any certifications, background checks, or special training?
- What is your typical availability? (Weekdays, evenings, weekends?)

**Skilled Trades**
- Are you licensed, insured, or bonded?
- Do you offer emergency or after-hours service?
- Do you work with residential, commercial, or both?
- What are your top 3-5 services?

**Retail / Storefront**
- What are your hours of operation?
- Do you take walk-ins, appointments, or both?
- Do you have any signature products or services?

**Food & Beverage**
- What type of cuisine or food do you serve?
- Do you offer dine-in, takeout, delivery, catering, or a combination?
- What are your hours?
- Would you like to feature menu highlights on the page?

**Professional Services**
- What are your specialties or practice areas?
- Do you offer a free initial consultation?
- What credentials or certifications should visitors know about?

**Fitness / Wellness**
- Do you run on a class schedule or by appointment?
- What certifications do you hold?
- Do you offer packages, memberships, or drop-in rates?
- Do you work in-person, virtually, or both?

**Teaching / Lessons**
- What subjects or skills do you teach?
- What ages or levels do you work with? (Beginners, advanced, kids, adults?)
- Do you teach in-person, online, or both?
- Where do lessons happen? (Your home, student's home, a studio, online?)
- What is your teaching background or qualifications?
- Do you offer trial lessons?

**Creative / Events**
- What type of work do you specialize in? (Weddings, portraits, corporate, parties, etc.)
- Do you have a portfolio or sample work you'd like to highlight?
- How far in advance do clients typically book you?
- Do you offer packages or custom quotes?
- What's your coverage area for events?

### Round 2 — Optional (offer to all archetypes)

- Do you want to include pricing on your page?
- Do you have testimonials or reviews you'd like to feature?
- Any awards, certifications, or credentials to highlight?
- What is the main action you want visitors to take? *(Call, book online, fill out a form, visit your location?)*

### Interview Delivery

- Present round 1 questions as a conversational group, not a numbered checklist.
- If the user volunteers a lot of information upfront, acknowledge it and only ask what's still missing.
- Keep round 2 short — 3-5 follow-up questions plus the optional ones. Don't overwhelm.
- If the user is unsure about an answer, help them with examples from their archetype (e.g., "Most plumbers highlight licensed & insured, free estimates, and same-day service — does any of that apply to you?").

**After the interview:** Once you have sufficient answers from both rounds — or if the user provided enough information upfront — proceed directly to Phase 2 outline generation. Do not ask for permission to proceed. Do not summarize the interview back to the user.

---

## Landing Page Outline Format

Generate each section using the template below. Adapt, skip, or merge sections based on the business type adaptation table.

### General template per section

```
## [Number]. [Section Name]
> Purpose: [Why this section exists — what job it does for the visitor]

**Headline:** [Suggested headline text — benefit-first, in the business owner's voice]
**Subheadline:** [One sentence expanding on the headline]
**Content:**
- [Bullet points describing what goes in this section]
- [Use the owner's actual details, not placeholders]
**CTA:** [Call-to-action text and action type, if applicable]
```

### Section specifications

#### 1. Hero / Above the Fold

> Purpose: Immediately tell visitors what the business does, where, and what to do next.

- **Headline:** Business name + core value proposition. Include the service area. Example: "Austin's Most Trusted Plumber Since 2008"
- **Subheadline:** One sentence expanding on the promise or the customer benefit.
- **Trust signals:** 2-3 quick badges — years in business, license/certification, star rating, number of customers served.
- **Primary CTA:** The single most important action. Use a strong verb: "Call Now," "Book Online," "Get a Free Quote," "Schedule a Visit."
- **Location callout:** "Serving [Area]" — critical for local businesses and local SEO.

#### 2. Services / What We Do

> Purpose: Show the range of offerings so visitors can self-qualify.

- **Format:** 3-6 services, each with a name and 1-2 sentence description.
- **Guidance:** Lead with the most popular or profitable service. Be specific — "Drain Cleaning & Sewer Repair" is better than "Plumbing Services."
- **Archetype variations:**
  - Food & Beverage → "Our Menu" or "Menu Highlights" with 4-6 signature items
  - Retail/Storefront → "Our Services" with pricing if the owner opted in
  - Home Services → List the specific services offered (e.g., "Infant care (0-12 months)," "After-school pickup," "Overnight stays")

#### 3. About / Our Story

> Purpose: Build trust through human connection. Small businesses win on personality.

- **Content:** Owner's name, how long they've been doing this, what makes them passionate about the work, any family or community angle.
- **Voice:** First person. "I started this business because…" is more effective than "Founded in 2015, XYZ Corp…"
- **Photo suggestion:** Recommend the owner include a photo of themselves or their team at work.

#### 4. Why Choose Us / Trust Builders

> Purpose: Overcome the "why not pick the first Google result" objection.

- **Format:** 3-4 differentiators as benefit-focused bullet points.
- **Pull from:** The owner's answer to "what makes you different" plus archetype-appropriate trust signals.
- **Examples by archetype:**
  - Trades: "Licensed & Insured," "Same-Day Service," "Free Estimates," "10-Year Warranty"
  - Home Services: "Background Checked," "CPR Certified," "Flexible Scheduling"
  - Professional: "15 Years of Experience," "Free Initial Consultation," "Specializing in [Niche]"
  - Food: "Locally Sourced Ingredients," "Family Recipes Since 1995," "4.8★ on Google"
  - Teaching: "10+ Years Teaching Experience," "Conservatory-Trained," "95% of Students Pass Their Exam," "Free Trial Lesson"
  - Creative/Events: "500+ Events Photographed," "Featured in [Publication]," "Award-Winning Portfolio," "Same-Week Turnaround"

#### 5. Testimonials / Social Proof

> Purpose: Let other customers do the selling.

- **Format:** 2-3 testimonial blocks. Each has: customer first name, context (neighborhood or service used), and a short quote.
- **If the owner provided testimonials:** Use them verbatim.
- **If not:** Provide placeholder structure with coaching: "A strong testimonial mentions a specific result — e.g., 'Mike fixed our furnace in two hours on a Sunday. Lifesaver.' Ask 2-3 happy customers for a quick quote."
- **Bonus:** If the business has Google/Yelp reviews, suggest embedding a star rating + review count.

#### 6. Service Area / Location

> Purpose: Help visitors confirm "do they serve my area?" Critical for local SEO.

- **Storefront businesses:** Physical address, embedded map suggestion, parking/transit notes.
- **Mobile/on-site services:** List of neighborhoods, cities, or zip codes served. "We come to you" messaging.
- **Radius-based:** "Serving a [X]-mile radius around [City]."
- **Multiple locations:** List each with address and hours.

#### 7. Hours & Availability

> Purpose: Reduce friction — visitors need to know when they can reach you.

- **Include for:** Retail/storefront, food & beverage, and any business with set hours.
- **Skip for:** Babysitters, consultants, photographers, and other by-appointment businesses. Instead, fold availability into the CTA: "Book a time that works for you."
- **Format:** Simple day-by-day hours table. Note holidays or seasonal changes. Add "Call for emergency service" for trades that offer it.

#### 8. Pricing

> Purpose: Set expectations and pre-qualify visitors.

- **Include only if** the owner opted in during the interview.
- **If opted in:** "Starting at" pricing, package tiers, or service-by-service rates. Keep it simple.
- **If opted out:** Replace this section with a **"Get a Free Quote" CTA block** — headline, one-liner about easy quoting, and a call/form CTA.
- **Archetype defaults:**
  - Trades → "Free Estimates" CTA (most trades don't show prices)
  - Professional → "Free Consultation" CTA
  - Fitness → Show package/membership pricing (expected in this industry)
  - Food → Link to full menu or show price ranges

#### 9. FAQ

> Purpose: Handle objections, reduce support calls, help SEO.

- **Format:** 4-6 question-and-answer pairs.
- **Always consider these defaults:**
  - "What areas do you serve?"
  - "How do I book / schedule?"
  - "What forms of payment do you accept?"
  - "Are you licensed / insured?" (if applicable)
- **Archetype-specific FAQs:**
  - Trades: "Do you offer free estimates?" "Are you available for emergencies?" "Do you guarantee your work?"
  - Food: "Do you take reservations?" "Do you offer catering?" "Can you accommodate dietary restrictions?"
  - Home Services: "Are you background checked?" "What ages do you work with?" "What's your cancellation policy?"
  - Fitness: "Do I need to bring my own equipment?" "Do you offer trial sessions?" "Can I freeze my membership?"
  - Professional: "What does a typical engagement look like?" "Do you offer payment plans?"
  - Teaching: "Do you offer a free trial lesson?" "What ages do you teach?" "How long is a typical lesson?" "What should my child bring to the first lesson?" "Do you prepare students for exams or recitals?"
  - Creative/Events: "How far in advance should I book?" "Do you require a deposit?" "What's the turnaround time?" "Do you travel to my location?" "What happens if the event is rained out?"

#### 10. Contact / Final CTA

> Purpose: Convert. This is the last chance.

- **Phone number:** Prominent, click-to-call on mobile. Most small business customers still prefer to call.
- **Email address**
- **Contact form suggestion:** Name, phone, brief message. Keep it short — long forms kill conversions.
- **Physical address:** If applicable (storefront businesses).
- **Social media links:** If the business is active on social.
- **CTA:** Repeat the hero CTA. Same verb, same energy.

#### 11. Footer

> Purpose: Housekeeping and secondary navigation.

- Business name, address, phone, email
- Social media icon links
- License or registration numbers (if applicable)
- "Proudly serving [Area]"
- Copyright line

---

## Business Type Adaptations

Quick-reference table for which sections to include and how to adapt them.

| Section | Home Services | Trades | Retail / Storefront | Food & Bev | Professional | Fitness | Teaching | Creative / Events |
|---|---|---|---|---|---|---|---|---|
| **Hero CTA** | "Book Now" / "Contact Me" | "Call Now" / "Get a Free Quote" | "Visit Us" / "Book an Appointment" | "View Menu" / "Order Now" | "Schedule a Consultation" | "Join Now" / "Book a Class" | "Book a Lesson" / "Schedule a Free Trial" | "View Portfolio" / "Book Your Date" |
| **Services** | Specific service list | Top 3-5 services | Services + pricing optional | Menu highlights | Practice areas | Class types / offerings | Subjects, levels, lesson formats | Specialties with package descriptions |
| **Hours** | Skip (by availability) | Emergency note + "Call anytime" | Full hours table | Full hours table | By appointment note | Class schedule | By appointment / schedule availability | Skip (booking-based) |
| **Pricing** | Optional | "Free Estimates" CTA | Show if provided | Menu with prices | "Free Consultation" CTA | Packages / memberships | Per-lesson + package rates | Package tiers or "Request a Quote" CTA |
| **Credentials** | Background check, certifications | License, insurance, bonding | Awards, years in business | Health permits, awards | Degrees, bar admission, certifications | Certifications, specializations | Degrees, teaching certs, performance experience | Awards, publications, notable clients |
| **Social Proof** | Parent reviews, references | Before/after, Google reviews | Yelp/Google reviews, awards | Food critic quotes, reviews | Case results, client testimonials | Transformation stories, reviews | Student/parent testimonials, student achievements | Client testimonials, "as seen in" press mentions |
| **FAQ focus** | Availability, cancellation, ages | Estimates, emergencies, warranty | Walk-ins, returns, gift cards | Reservations, dietary, catering | Process, fees, timeline | Trials, equipment, cancellation | Trial lessons, cancellation, what to bring, progress | Booking timeline, deposits, turnaround, travel fees |

---

## Copy Tone Guidelines

### Voice
- Write like a friendly neighbor, not a corporation.
- Use "I" for sole proprietors, "we" for teams. Never "the company" or "the firm."
- Short sentences. Plain words. No jargon.

### Local SEO
- Work the city or area name into headlines and body copy naturally.
- Example: "Trusted Plumbing in North Austin" — not "Trusted Plumbing Services for Residential and Commercial Clients."

### CTAs
- Lead with action verbs: **Call, Book, Get, Schedule, Visit, Order.**
- Avoid weak CTAs like "Learn More," "Submit," or "Click Here."
- Include the phone number directly in CTA text when relevant: "Call (512) 555-0123."

### Assumptions
- When the owner didn't provide specific information, make reasonable assumptions and flag them clearly: *"[Assumption: You serve the greater Austin metro — adjust if this is different.]"*
- Never invent testimonials. Use placeholder structure instead.
