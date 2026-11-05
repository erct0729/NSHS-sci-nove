# SCI-NOVE — Google Sites Implementation Guide

**Project:** Science in Noveleta: Observation, Verification, and Exploration  
**Pilot audience:** Grade 11 General Science, Noveleta Senior High School  
**Package:** Responsive website prototype (`index.html`), optional embeddable Google Sites quiz (`google-sites-quiz-embed.html`), and this guide.

## 1. Preview the site

1. Extract the ZIP package to a folder.
2. Double-click **index.html** to open the standalone prototype in Chrome, Edge, or Firefox.
3. Test the Home, Learning Hub, Investigations, Challenge Lab, and About tabs.
4. Open a module; mark it complete. Open an investigation and download its field-note template. Try the five-question practice assessment.

The prototype has no web server requirement or third-party scripts. It has *not* been published under a school account.

## 2. Build a native Google Site — recommended for long-term classroom management

1. Open https://sites.google.com/new in the Google account authorized for this project.
2. Create a blank site and name it **SCI-NOVE | Science in Noveleta**.
3. Create **five top-level pages** using the **Pages** tab:
   - **Home** — project tagline, goal, Observe → Verify → Explore cycle, start buttons.
   - **Learning Hub** — module list, separate lesson pages or subpages, links to teaching resources.
   - **Investigations** — mission cards with directions and Google Docs/Drive worksheet links.
   - **Challenge Lab** — Google Forms quizzes and evidence-based mini-challenges.
   - **About SCI-NOVE** — learning rationale, teacher guide, privacy and safety notes.
4. Reproduce the content from `SITE_COPY_PACK.md` and the prototype. Add your own verified school logo, locally approved photographs, official instructional materials, and sources as available.
5. Add downloadable activity sheets from Google Drive. Check sharing permissions with a test learner account.
6. Make a **Google Form quiz** for classroom score collection and insert it with **Insert → Forms**. Ensure collection of student names, school identifiers, and responses follows school data-privacy rules.
7. Use **Preview** on phone and desktop, then **Publish**. Select appropriate public/restricted access based on school policy.

**Important:** Google Sites does not offer a one-click conversion of this HTML prototype into native, editable Google Sites pages. Its page builder and the HTML code are different editing systems. The native-pages approach is simplest to maintain for most teachers.

## 3. Embed the interactive quiz directly into Google Sites

A separate, copyable five-question sample widget is included as `google-sites-quiz-embed.html`.

1. Open the file with Notepad or another text editor (not just in a browser).
2. Select all and copy its content.
3. In Google Sites, open **Challenge Lab → Insert → Embed → Embed code**.
4. Paste the content, select **Next**, then **Insert**.
5. Resize the embed area so the five questions can be used comfortably. Preview and test submission on mobile and desktop.

This mini-quiz checks answers in the page and **does not save or send scores to a teacher**. For an official graded assessment, use Google Forms instead. Embedded scripts can behave differently in Google Sites' sandbox; verify in your own published site.

## 4. Option: Publish the full custom prototype, then embed it in Google Sites

If you want to keep this *exact* responsive design and navigation rather than recreate it:

1. Host `index.html` on a static website service (for example, GitHub Pages, Cloudflare Pages, or Netlify, subject to their current availability and terms).
2. Test the resulting HTTPS URL independently.
3. In Google Sites, use **Pages → Add → Full page embed**, or **Insert → Embed → URL**, and enter the hosted URL.
4. Test it again in Google Sites and confirm the host permits embedding. Not all sites allow iframe embedding.

**Note:** The native site is free to create using Google Sites; external hosts may have separate quotas or policies. The full HTML file should not be uploaded into Google Sites as a purported editable web page.

## 5. Suggested pilot learning flow (50–60 minutes)

- **5 minutes:** Show a Noveleta/Cavite-based scientific question and identify observations vs assumptions.
- **15 minutes:** Learners explore one Learning Hub module with teacher scaffolding.
- **20 minutes:** In small groups, learners choose a safe investigation and complete its observation/verification/exploration field notes (or use teacher-selected documents/photos).
- **10 minutes:** Learners complete the Challenge Lab or corresponding Google Form.
- **5–10 minutes:** Groups share a supported explanation and one limitation of their evidence.

For a real innovation study, record a baseline and comparable post-implementation evidence with approved instruments, account for learner accessibility, and document teacher revisions. The prototype does not claim to demonstrate improved learning outcomes by itself.

## 6. Privacy, safety, and evidence requirements

- All local situations are **illustrative prompts**. The prototype has no authentic field measurements or agency data.
- The prototype stores completion marks and the highest quiz score only in the **current browser's local storage**. It has no accounts, server database, or teacher dashboard. A shared device will share that device's saved progress unless cleared.
- Never enter learner names, assessment records, health information, or private school documents into publicly visible content.
- Obtain approval for school logos, photographs, investigations, and student work.
- No unsupervised experiments, chemical mixing, entry to waterways, or field sampling.
- Cite actual PAGASA, DENR, PHIVOLCS, or other agency data as appropriate when adding location-specific scientific claims. Include date range and measurement units.
- Review alignment with the current DepEd curriculum and your school's implementation policies before rollout.

## 7. Upgrade roadmap

**Pilot v1 (this package):** learning modules + guided local missions + self-check quiz.  
**Pilot v2:** native Google Sites resources, accessible Google Forms, Drive-linked LAS, and teacher-approved data sheets.  
**Pilot v3:** curated local datasets, educator review process, learning analytics through privacy-compliant Google Forms/Sheets, and documented pre/post evidence.

## Official Google Sites references

- Create a Google Site: https://support.google.com/sites/answer/6372878?hl=en
- Embed websites, HTML/CSS/JavaScript, Google Forms, and Drive files: https://support.google.com/sites/answer/90569?hl=en

These instructions should be checked against your account's current Google Workspace permissions and school policies.
