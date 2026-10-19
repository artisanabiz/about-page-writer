# Brand questions, SEO and AI assistants

An About page is where search engines and AI assistants look up *who a business is*. They reconcile it with the business's profiles and other sites, and they quote short, clear statements. Make the page easy to understand, easy to quote and consistent everywhere — in the site's own voice.

## The brand questions

Score the current page against these (answered / partly / missing), and make the new page answer every one the evidence supports:

1. **What is it?** Name + what kind of business.
2. **What does it do?** Main services or products, in the business's own words.
3. **For whom?** Typical customers or situations — and who it's *not* for, if known.
4. **Where?** City, area served, online/on-site.
5. **Since when?** Founding year or years of experience (with what it refers to).
6. **Who's behind it?** Founder(s), key people, roles, relevant qualifications.
7. **How does it work?** How working together starts and runs.
8. **How is pricing worked out?** The approach (fixed, by quote, packages) — never invented prices.
9. **Why trust it?** Proof: numbers, clients (with permission), reviews, registrations, credentials, case studies.
10. **What's different?** Real, specific reasons — often found in reviews, case studies, process or history.
11. **What next?** The concrete action with the real link, phone or email.

Questions 3, 7, 8 and 10 are the "decision" questions AI assistants need to *recommend* a business, not just describe it. Give them real substance.

## The opening (brand-facts lead)

First 2–4 sentences, in the site's voice, answer: **[Name] is a [what] for [whom] in [where], [since when], [what's different]**. Example: *"Brutăria Ana este o brutărie din Brașov care coace zilnic pâine cu maia, după rețetele bunicii Veta din Făgăraș."* No slogan-only openings; a slogan can sit above as a tagline.

## Key facts block

A short text list near the end (not an image), using the same values as the profiles:
- Name (and legal name if different), founded, founder(s)
- Location / area served
- Services
- Team size or key people (if public)
- Registrations / memberships (if relevant and verified)
- Contact

## Structure that's easy to quote

- **One H1** (e.g. "About [Name]" or the site's own heading style plus the name), **descriptive H2s** ("Who we work with", "How a project starts"). A creative heading can keep a plain sub-heading.
- **Self-contained paragraphs:** each makes sense if quoted alone; the first sentence carries the point. Use the name instead of "we" at the start of key paragraphs where it reads naturally.
- **Specific facts with context:** "80+ clients since 2023", "as of 2026" for numbers that change.
- **Proof next to the claim** it supports.
- **Named people** with roles; link to their profiles if they agree.
- **FAQ** with short, direct answers (see `faq-and-testimonials.md`).
- **Internal links** to services, portfolio/case studies and contact.
- **Same facts everywhere:** if a profile says something different, list the fix in Next steps.

## Title tag and meta description

- Title: `About [Name] | [what] in [where]` (about 60 characters), or the site's existing pattern.
- Meta description: 1–2 sentences answering what/for whom/where, plus the next step; only facts that appear on the page.

## Markup (optional, for the webmaster)

- Check for existing Organization/LocalBusiness markup first; give a merge note rather than a second block.
- Most specific accurate type (`LocalBusiness` subtype, `Organization`, or `ProfilePage` + `Person` for a one-person brand). Don't use `ProfessionalService` (deprecated in Schema.org). Stable `@id` (e.g. `https://example.com/#organization`), `url` = homepage, `sameAs` = the business's own profiles only, `email` plain.
- Only facts visible on the page; nothing private. Tell the owner to run Schema Markup Validator and Google's Rich Results Test; don't claim it's validated.
- Markup helps identify the business; it doesn't guarantee AI citations.

## Consistency report

Search engines and AI assistants compare what the business says about itself everywhere. Contradictions make them unsure. The report shows every place the business appears and what to fix.

**One table, one row per channel and fact that needs attention** (skip rows that already match):

| Channel | Priority | What it says now | Correct version | Who can fix it |
|---|---|---|---|---|

Sort by priority, high first.

- **Channels:** other pages of the website; the business's own profiles (Google Business Profile, LinkedIn, Facebook, Instagram, YouTube, TikTok); directory and map listings; review platforms; press and other third-party pages; the Google knowledge panel.
- **Facts to compare:** name (incl. legal name and spelling), address or area served, phone, email, website link, founding year, services, team/founder, key numbers, one-line description.
- **Who can fix it:**
  - *You* — your website and your own profiles.
  - *Claim or request* — listings you didn't create: claim the listing or use the platform's "suggest an edit" / correction form; for the knowledge panel, claim it or send feedback.
  - *Ask the publisher* — press and other sites: a short, polite correction request, only when the error matters (wrong contact details, wrong services, wrong name).
  - *Leave it* — old, historical or harmless mentions.
- **Priority:** *High* — the website itself, Google Business Profile, LinkedIn, and any listing that appears on the first page for the business name. *Medium* — other active directories and review platforms. *Low* — old articles and minor listings.
- **Careful with Google Business Profile:** never recommend removing a verified address or switching to a service area without the owner understanding it can affect local rankings — recommend checking it with whoever manages local SEO.
- If a profile couldn't be opened, add a row "not checked — paste the text" instead of guessing.

**Ready-to-paste descriptions** for the profiles that need fixing: same facts as the About page, written in the site's voice, paraphrased per channel (not copied word for word), within each platform's length (roughly: Google Business Profile description 750 characters, LinkedIn tagline 120 and About 2,000, Instagram bio 150, Facebook intro about 100 — check current limits). For Google Business Profile, open with "[Name] provides [service] to [location]".

The skill only recommends: it never edits profiles or contacts platforms or publishers.

## Irina's recommendations — required in final delivery

Use **“Recomandările Irinei”** for Romanian and **“Irina’s recommendations”** for English; translate the heading for other site languages. Include it in Next steps and in the comparison, outside the page copy intended for publication. The skill authorizes this editorial attribution; do not invent quotations, credentials or personal endorsements beyond these recommendations.

Tailor it to the actual gaps in this case. Review the eleven brand questions, people/roles, useful FAQ, authentic proof, key facts, internal links, title/meta and cross-channel consistency. Include optional structured data or implementation checks only when relevant, and label anything not inspected as unverified. Do not turn the list into an unrelated full-site SEO audit or require every business to have every possible section.

For each missing or incomplete item, give:
- what is missing, its status (awaiting answer / declined / not checked) and why it helps readers understand or assess this business;
- the exact facts, evidence or permission needed, with the question or a suggested section placement;
- what the owner/editor can add independently if they prefer not to continue with the skill.

Prioritize essential identity and decision information before optional enhancements. Keep unsupported answers, placeholder people and invented testimonials out of publishable copy, but retain their relevant completion actions here. Do not relist confirmed material as missing. If nothing material is missing, say so instead of manufacturing recommendations.

Close with an invitation in the site's register, for example:
> **RO:** Îți recomand să adaugi informațiile de mai sus pentru o pagină mai completă, utilă cititorilor și ușor de înțeles de motoarele de căutare și asistenții AI. Le putem integra prin skill sau le poți completa ulterior, direct cu persoana care îți editează site-ul.
> **EN:** I recommend adding the information above to make your page more complete, useful to readers and clear to search engines and AI assistants. We can integrate it with this skill, or you can add it later with your website editor.

Describe completeness for the business and audience, not a “perfect” page or a guaranteed SEO/AIO result. Recommendations are editorial guidance, not proof of rankings, citations or technical implementation.

## Checklist before delivery

- Every brand question the evidence supports is answered.
- The opening states who/what/for whom/where.
- Key facts match the profiles, or every mismatch is in the consistency report.
- Headings are descriptive; paragraphs stand alone; facts are text.
- Title and meta use only facts on the page.
