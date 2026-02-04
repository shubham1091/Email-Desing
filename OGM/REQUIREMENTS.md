# KPA OGM Email Campaign - Requirements Document

**Project:** Keele Postgraduate Association Ordinary General Meeting Email Series  
**Date:** February 2025  
**Prepared by:** KPA Secretary  
**Status:** Planning Phase

---

## Project Overview

Design and develop a complete email campaign for the KPA Ordinary General Meeting (OGM) scheduled for February 18th, 2025. All emails must be professional, Outlook-compatible, and maintain consistent branding throughout the campaign.

---

## Meeting Details

- **Event:** Ordinary General Meeting (OGM)
- **Date:** Friday, 18th February 2025
- **Time:** 5:00 PM - 7:00 PM
- **Location:** WM0.01
- **Virtual Option:** Microsoft Teams (link sent 3 days before)
- **Motion Submission Period:** 5th February - 15th February 2025
- **Submission Email:** kpa.secretary@keele.ac.uk
- **In-Person Perks:** Pizza and drinks provided

---

## Technical Requirements

### Email Client Compatibility
- **Primary Target:** Microsoft Outlook (2016, 2019, Office 365)
- **Secondary:** Gmail, Apple Mail, Yahoo Mail
- **Mobile Responsive:** Yes

### Design Constraints
- [ ] **Layout:** Table-based HTML (no flexbox/grid)
- [ ] **CSS:** Inline styles only (no external stylesheets)
- [ ] **Width:** Maximum 600px for optimal display
- [ ] **Fonts:** Web-safe fonts only (Arial, Georgia, Verdana, Times New Roman)
- [ ] **Images:** Should work with images blocked (text-based design preferred)
- [ ] **Colors:** Solid colors
- [ ] **Animations:** None (Outlook doesn't support)
- [ ] **Testing:** Must test in Outlook, Gmail, and mobile

---

## Email Series Requirements

### 1. OGM Announcement Email
**Purpose:** Initial invitation to all postgraduate students  
**Send Date:** TBD (minimum 2 weeks before event)  
**Status:** ⏳ Pending Design

**Content Requirements:**
- [ ] Warm greeting to Keele Postgraduates
- [ ] Clear meeting details (date, time, location, virtual option)
- [ ] Explanation of OGM purpose and importance
- [ ] Call for motion submissions with deadline
- [ ] Mention of attachments (Motion Template + Example)
- [ ] In-person perks (pizza and drinks)
- [ ] Contact information
- [ ] Signature from KPA Secretary (Shalini)

**Attachments:**
- KPA General Meeting Motions Template
- Example Motion document

---

### 2. Motion Submission Reminder
**Purpose:** Midway reminder during submission period  
**Send Date:** ~16th February (mid-point of submission period)  
**Status:** ⏳ Not Started

**Content Requirements:**
- [ ] Brief reminder of OGM date
- [ ] Days remaining to submit motions
- [ ] Submission email and deadline
- [ ] Link to motion template (if hosted online)
- [ ] Encouragement to participate

---

### 3. Final Call for Motions
**Purpose:** Last chance reminder before deadline  
**Send Date:** 18th February (deadline day, morning)  
**Status:** ⏳ Not Started

**Content Requirements:**
- [ ] Urgent tone (professional, not panicked)
- [ ] Final hours to submit
- [ ] Quick recap of how to submit
- [ ] Deadline time (end of day/specific time)

---

### 4. Meeting Agenda & Teams Link
**Purpose:** Pre-meeting details with agenda and virtual link  
**Send Date:** 15th February (3 days before meeting)  
**Status:** ⏳ Not Started

**Content Requirements:**
- [ ] Meeting reminder (date, time, location)
- [ ] Microsoft Teams link
- [ ] Meeting agenda with submitted motions
- [ ] Instructions for in-person and virtual attendees
- [ ] Reminder about pizza/drinks for in-person
- [ ] Any pre-reading materials

---

### 5. Thank You & Meeting Minutes
**Purpose:** Post-meeting follow-up  
**Send Date:** Within 3-5 days after meeting  
**Status:** ⏳ Not Started

**Content Requirements:**
- [ ] Thank you message to attendees
- [ ] Meeting attendance summary
- [ ] Motions discussed and outcomes
- [ ] Action items and next steps
- [ ] Link to full minutes document
- [ ] Preview of next meeting/events

---

### 6. Motion Confirmation (Optional)
**Purpose:** Auto-reply when motion is received  
**Send Date:** Automated upon submission  
**Status:** ⏳ Optional - To Be Decided

**Content Requirements:**
- [ ] Confirmation of receipt
- [ ] Motion will be reviewed
- [ ] Timeline for agenda publication
- [ ] Contact for questions

---

## Branding & Design Specifications

### Color Scheme
**Status:** ✅ DEFINED (Based on KPA Brand Analysis)

The KPA aligns with Keele University's official color palette while maintaining professional maturity:

#### Primary Palette
- **Keele Blue (Primary):** `#271E3D`
  - CMYK: C100 M85 Y41 K40
  - RGB: R39 G30 B61
  - Use for: Headers, primary CTA buttons, authoritative text
  - Psychology: Establishment, depth, seriousness, institutional authority

- **Secondary Blue:** `#174872`
  - Lighter slate variant
  - Use for: Secondary sections, backgrounds, subtle divisions

- **Tertiary Blue (CTA):** `#005D8F`
  - Brighter, tech-forward blue
  - Use for: Call-to-action buttons, links, interactive elements

#### Accent Colors (Use Sparingly)
- **Heritage Red:** Pantone 1797
  - RGB: R217 G55 B33
  - CMYK: C0 M88 Y90 K8
  - Use for: Important highlights, urgent deadlines, breaking visual monotony

- **Heritage Green:** Pantone 7480
  - RGB: R47 G172 B104
  - CMYK: C75 M0 Y74 K0
  - Use for: Sustainability messaging, positive outcomes, success indicators

#### Neutral Palette
- **White:** `#FFFFFF` (for text on dark backgrounds, max contrast)
- **Light Gray:** `#F7F7F7` (for backgrounds, subtle sections)
- **Medium Gray:** `#718096` (for secondary text, captions)
- **Dark Gray:** `#2D3748` (for body text on light backgrounds)

#### Color Usage Guidelines
- **Header Backgrounds:** Keele Blue (#271E3D) to borrow institutional legitimacy
- **Body Backgrounds:** White or very light gray (#F7F7F7) to avoid heaviness
- **Important CTAs:** Tertiary Blue (#005D8F) for visibility and action
- **Urgent Messages:** Heritage Red sparingly for deadlines
- **White Space:** Critical - use generously to counterbalance dark blue's visual weight

### Typography
**Status:** ✅ DEFINED

#### Font Strategy
Following Keele University's dual-font approach while prioritizing Outlook compatibility:

**Primary Options (in order of preference):**
1. **Georgia** (serif) - Humanist, readable, web-safe
   - Use for: Headings, formal sections, heritage feel
   - Links to academic tradition

2. **Arial** (sans-serif) - Clean, universal, maximum compatibility
   - Use for: Body text, tables, data
   - Guaranteed rendering across all email clients

3. **Verdana** (sans-serif) - Alternative if Arial feels too generic
   - Use for: Body text alternative
   - Excellent screen readability

**Fallback Stack:**
```css
font-family: Georgia, 'Times New Roman', Times, serif; /* For headings */
font-family: Arial, Helvetica, sans-serif; /* For body */
```

**Size Hierarchy:**
- **Main Headline (H1):** 24-28px, Georgia, Bold, Keele Blue
- **Section Headings (H2):** 20-22px, Georgia, Bold, Keele Blue or Dark Gray
- **Sub-headings (H3):** 16-18px, Arial, Bold, Dark Gray
- **Body Text:** 14-16px, Arial, Regular, Dark Gray (#2D3748)
- **Secondary Text:** 12-14px, Arial, Regular, Medium Gray (#718096)
- **Line Height:** 1.5-1.7 for body text (optimal readability)

### Logo/Header Strategy
**Status:** ✅ DEFINED

**Approach: Text-Based Header with KPA Branding**

Given email client limitations and the need for reliable rendering:

- [ ] **Primary Header:** Text-based "KEELE POSTGRADUATE ASSOCIATION" in Georgia/Arial
  - Styled with Keele Blue background (#271E3D)
  - White text (#FFFFFF)
  - Letter-spacing for premium feel
  
- [ ] **Optional Logo:** If KPA has a simple vector logo
  - Must test with images disabled
  - Include alt text: "Keele Postgraduate Association"
  - Fallback to text if image doesn't load

- [ ] **Keele University Logo:** Not necessary in body
  - Already implied through color scheme and typography
  - Avoids clutter and maintains KPA independence

### Brand Archetype & Positioning
**Status:** ✅ DEFINED (from Brand Analysis)

**KPA Brand Archetype:** The Sage / The Caregiver
- **Not:** The Jester (undergraduate student union)
- **Not:** Generic bureaucracy
- **Is:** Mature, specialized, supportive expert

**Key Brand Values:**
1. **Specialist Expertise** - "Only separate postgraduate union in the UK"
2. **Four Pillars:** Education (🎓), Welfare (❤️), Community (👥), Democracy (🗣️)
3. **Independent but Aligned** - Registered charity, critical friend to university
4. **Mature & Professional** - Gin tastings, not cheap beer; networking, not nightclubs

### Tone of Voice
**Status:** ✅ DEFINED

**Primary Tone: Professional-Friendly**

Balance between:
- ✅ **Authoritative** when discussing governance, deadlines, official matters
- ✅ **Welcoming** when inviting participation, building community
- ✅ **Supportive** when referencing welfare, support services
- ✅ **Empowering** when discussing democracy, student voice

**NOT:**
- ❌ Overly casual/undergraduate playful
- ❌ Corporate-cold/bureaucratic
- ❌ Overly academic/dry

**Example Phrases:**
- "We invite you..." (inclusive, respectful)
- "Your voice matters" (empowering)
- "We're here to support" (caregiver positioning)
- "Join us for..." (community building)

---

## Content Assets Needed

### Documents to Attach/Reference
- [ ] KPA General Meeting Motions Template
- [ ] Example Motion document
- [ ] Previous OGM minutes (optional reference)

### Information Still Needed
- [ ] Exact time for motion submission deadline (end of day 19th Feb?)
- [ ] Microsoft Teams link (added 3 days before)
- [ ] Any specific motion formatting requirements
- [ ] Expected number of recipients
- [ ] Is there a KPA website or social media to link?

---

## Quality Checklist (Pre-Send)

### For Each Email
- [ ] Tested in Outlook Desktop
- [ ] Tested in Outlook Web
- [ ] Tested in Gmail
- [ ] Tested on mobile device
- [ ] All links working
- [ ] Spelling and grammar checked
- [ ] Personalization working (if applicable)
- [ ] Images have alt text
- [ ] Preview text optimized
- [ ] Subject line compelling and clear

### Accessibility
- [ ] Semantic HTML structure
- [ ] Alt text for all images
- [ ] Sufficient color contrast
- [ ] Readable without images
- [ ] Clear hierarchy with headings

---

## Timeline & Milestones

| Date | Milestone |
|------|-----------|
| TBD | Finalize design requirements |
| TBD | Complete email template designs |
| TBD | Test all emails across platforms |
| ~4th Feb | Send OGM Announcement |
| 13th Feb | Motion submission period opens |
| 16th Feb | Send Motion Reminder |
| 18th Feb | Send Final Call for Motions |
| 19th Feb | Motion submission deadline |
| 15th Feb | Send Agenda & Teams Link |
| 18th Feb | **OGM Event** |
| 21-23rd Feb | Send Thank You & Minutes |

---

## Questions for Stakeholder Review

1. **Email Series:** Do we need all 6 email types, or just a subset?
2. **Branding:** What colors should we use? Do we have official KPA/Keele brand guidelines?
3. **Logo:** Do we have a KPA logo to include in the header?
4. **Tone:** What level of formality is appropriate for our audience?
5. **Attachments:** Should we include download buttons for templates, or just mention them?
6. **Motion Deadline:** What exact time on 19th February is the deadline?
7. **Recipients:** Approximately how many students will receive these emails?
8. **Approval Process:** Who needs to approve emails before sending?
9. **Testing:** Do we have access to multiple email clients for testing?
10. **Previous Templates:** Are there any previous KPA email templates we should reference for consistency?

---

## Success Criteria

- [ ] Emails render correctly in all major email clients
- [ ] Professional appearance that reflects well on KPA
- [ ] Clear, easy-to-understand information
- [ ] High engagement rate (opens/clicks)
- [ ] Successful motion submissions received
- [ ] Good meeting attendance (in-person and virtual)
- [ ] Positive feedback from recipients
- [ ] Reusable templates for future OGMs

---

## Notes

- Original email from previous secretary provided as reference
- Focus on improving upon previous plain-text design
- Must balance aesthetics with Outlook compatibility
- Consider accessibility for all students
