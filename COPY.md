# Vult Labs - Master Copy

Source of truth for all site copy. Update here first, then sync to code.

---

## Global

**Brand:** Vult  
**Legal entity:** Vult, LLC  
**Location:** San Antonio, Texas  
**Email:** ops.vult@gmail.com  
**Year:** 2026  

**Social**
- LinkedIn: https://www.linkedin.com/company/vultlabs
- Instagram: https://www.instagram.com/vultlabs
- YouTube: https://www.youtube.com/@vultlabs

---

## Home (`/`)

**Page title:** Vult Labs (default)

### Hero

**Headline:** Make it undeniable.

**Lead:** Cinematic reconstructions of crashes and injuries built from verified case data for the courtroom.

**CTA:** Discuss Your Case → (opens case modal)

### About Section

**Kicker:** About

**Headline:** The difference is in the frame.

**Description:** Each frame begins with verified case data and is shaped by the craft of our production studio. The result is visual evidence that clarifies complex events and holds under scrutiny in mediation and trial.

**CTA:** Learn More → /about

### Work: Crash Card

**Title:** Crash.

**Description:** Vehicle dynamics, roadway evidence, and expert analysis reconstructed into a clear visual account of the collision.

**Link:** /work/crash

### Work: Medical Card

**Title:** Medical.

**Description:** Anatomy, trauma, and treatment translated into clear visual explanations of the injury.

**Link:** /work/medical

---

## About (`/about`)

**Page title:** About | Vult Labs  
**Meta description:** Vult builds cinematic litigation visuals that turn complex accidents, injuries, and technical failures into clear visual evidence.

### Hero

**Headline:** About Vult.

### Metadata

| Label | Value |
|-------|-------|
| Produced by | Vult |
| Studio | San Antonio, Texas |
| Focus | Crash Reconstruction, Collision Visualization, Cinematic Case Visualization |
| Social | LinkedIn, Instagram, YouTube |

### Description

Vult is a production studio that develops cinematic crash and medical visualizations for litigation. The studio translates complex case materials into clear visual narratives.

Projects are built from verified evidence including accident reports, vehicle data, medical records, imaging, and expert analysis. These materials are reconstructed through a cinematic production process to clarify how events unfolded and how injuries occurred.

Each reconstruction is developed in collaboration with attorneys and subject-matter experts to ensure the work remains accurate, defensible, and clear in mediation and trial.

**CTA:** Discuss Your Case → (opens case modal)

---

## Crash (`/work/crash`)

**Page title:** Crash | Vult Labs  
**Meta description:** Cinematic crash reconstruction visuals. Stills and motion built from verified data, structured for the courtroom.

### Hero

**Headline:** Crash.

### Metadata

| Label | Value |
|-------|-------|
| Focus | Crash Reconstruction, Collision Visualization, Vehicle Dynamics |
| Motion | Crash reconstruction animation, Vehicle movement and timing, Collision sequence playback, Camera-driven crash views |
| Stills | Impact moment frames, Vehicle position diagrams, Scene overview visuals, Exhibit-ready crash frames |

**Note:** Projects may include motion, stills, or a combination of both.

### Description

Crash reconstructions translate crash data and expert findings into clear visual accounts of how the collision occurred.

Each project begins with verified case materials and expert analysis. These elements are reconstructed through the craft of our studio to show how the collision occurred and why it matters.

**CTA:** Discuss Your Case → (opens case modal)

---

## Medical (`/work/medical`)

**Page title:** Medical | Vult Labs  
**Meta description:** Precise medical-legal visuals that translate injury data into clear, compelling courtroom evidence.

### Hero

**Headline:** Medical.

### Metadata

| Label | Value |
|-------|-------|
| Focus | Medical Visualization, Anatomical Reconstruction, Injury Mechanisms |
| Motion | Injury mechanism animation, Anatomy in motion, Procedure explanation visuals, Step-by-step injury sequences |
| Stills | Anatomical injury frames, Medical exhibit visuals, Procedure illustrations, Injury detail diagrams |

**Note:** Projects may include motion, stills, or a combination of both.

### Description

Medical visualizations translate anatomy and injury into clear visual explanations of how trauma occurred.

Working from medical records, imaging, and expert input, we create visuals that help attorneys and juries quickly understand what happened to the body.

**CTA:** Discuss Your Case → (opens case modal)

---

## Contact (`/contact`)

**Page title:** Contact | Vult Labs  
**Meta description:** Start a case discussion with Vult. Crash reconstruction and medical visualization for litigation.

### Header

**Headline:** Discuss Your Case.

**Intro:** Vult produces cinematic crash and medical visualizations for litigation and mediation. If you have a case that could benefit from clear visual evidence, submit a case inquiry below.

### Form Fields

| Field | Type | Required | Placeholder |
|-------|------|----------|-------------|
| First Name | text | no | |
| Last Name | text | no | |
| Email | email | yes | your@email.com |
| Law Firm / Organization | text | no | |
| Case Type | radio | no | Crash Reconstruction / Medical Visualization / Other |
| Case Overview | textarea | no | Short description of the case or visualization needed. |
| Supporting material | file upload | no | |

**Submit button:** Submit Case

### Confirmation

**Headline:** Thank You

**Description:** Your case inquiry has been received. We will follow up shortly.

---

## Privacy Policy (`/privacy`)

**Page title:** Privacy Policy | Vult Labs  
**Meta description:** Vult, LLC privacy policy.  
**Last updated:** March 7, 2026

### Hero

**Headline:** Privacy Policy

### Body

Vult, LLC ("Vult," "we," "our," or "us") respects your privacy and is committed to protecting the information you share with us through this website. This Privacy Policy explains what information may be collected through the site, how it is used, and how it is protected.

#### Information We Collect

**Information You Provide**

If you contact us through the website or email, we may collect information you voluntarily provide, such as:

- Name
- Email address
- Organization or law firm
- Case inquiry information
- Any additional information you choose to include in your message

Please do not submit confidential, privileged, or sensitive case materials through the website contact form.

**Automatically Collected Information**

When visiting the website, certain technical information may be collected automatically, including:

- IP address
- Browser type and version
- Device information
- Pages visited
- Date and time of visits
- Referral source

This information is used to understand website usage and maintain site performance and security.

#### How We Use Information

Information collected through the website may be used to:

- Respond to inquiries and case discussions
- Evaluate potential projects
- Improve website functionality and performance
- Maintain security and prevent misuse of the site

We do not sell, rent, or share personal information with third parties for marketing purposes.

#### Data Security

Reasonable administrative and technical measures are used to protect information submitted through the website. However, no method of transmission over the internet can be guaranteed to be completely secure.

#### Third-Party Services

The website may use third-party services such as hosting providers, analytics tools, or embedded media platforms. These services may collect limited technical information in accordance with their own privacy policies.

#### External Links

This website may contain links to external websites. Vult is not responsible for the privacy practices or content of those sites.

#### Your Rights

You may contact us to request access to, correction of, or deletion of personal information you have submitted through this website.

#### Changes to This Policy

This Privacy Policy may be updated periodically. Any changes will be posted on this page with an updated revision date.

#### Contact

For questions regarding this Privacy Policy, please contact:

Vult, LLC  
San Antonio, Texas  
ops.vult@gmail.com

---

## Case Modal (global component)

Multi-step modal triggered by "Discuss Your Case" CTAs across the site.

### Step 1: Email

**Headline:** Discuss Your Case  
**Description:** Enter your email to begin a case discussion with Vult.  
**Field:** Email (required, placeholder: your@email.com)  
**Button:** Proceed

### Step 2: Contact

**Headline:** Your Information  
**Fields:** First Name, Last Name, Law Firm / Organization  
**Button:** Proceed

### Step 3: Case Type

**Headline:** Case Type  
**Options:** Crash Reconstruction / Medical Visualization / Other  
**Button:** Proceed

### Step 4: Case Overview

**Headline:** Case Overview  
**Field label:** Short description of the case or visualization needed.  
**File upload label:** Supporting material (optional)  
**Button:** Submit Case

### Step 5: Confirmation

**Headline:** Thank You  
**Description:** Your case inquiry has been received. We will follow up shortly.

---

## Footer (global component)

### Column 1: Vult

**Links:**
- About → /about
- Crash → /work/crash
- Medical → /work/medical

**Fineprint:**
© 2026 Vult, LLC.  
All rights reserved  
Privacy Policy → /privacy

### Column 2: Connect

- LinkedIn → https://www.linkedin.com/company/vultlabs
- YouTube → https://www.youtube.com/@vultlabs

### Column 3: Case Inquiries

**Body:** Vult produces cinematic crash and medical visualizations used in litigation and mediation.

**CTA:** Discuss Your Case → /contact
