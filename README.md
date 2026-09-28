# Kang Lab Website

Official website source for the Kang Lab at Yonsei University.

## Master file

`index.html` is the current production source. Treat the `main` branch as the canonical version of the website.

## Maintenance rules

1. Keep the website in English.
2. Preserve the current **Plex + Warm + Dark** visual system on desktop and mobile.
3. Colors are managed through the existing CSS `:root` tokens. Do not casually change those tokens, and do not hardcode new component colors when an existing token can be used.
4. Preserve the current information architecture: Research · Publications · People · Contact.
5. Preserve the scientific framing: **Sense · Choose · Control**, with a broader physiology orientation and particular interest in GPCRs involved in itch, pain, and related sensory responses.
6. The GPCRome visualization is a **conceptual public-facing animation using synthetic data**. Do not replace it with unpublished receptor names, raw screening values, SEM values, or other confidential experimental data.
7. Desktop uses the Canvas version of the GPCRome animation. Mobile uses the SVG/CSS fallback for reliable rendering. Test both after animation changes.
8. When using AI/vibe coding, ask it to modify only the requested parts and preserve all unrelated content and styling.
9. Before publishing a change, check:
   - desktop layout
   - mobile layout
   - navigation links
   - external links
   - People names/photos
   - Publications formatting
   - Contact information
   - GPCRome animation
10. Make one focused Git commit per logical change with a clear message, e.g. `Add 2027 publication` or `Update graduate researcher profile`.

## Routine update workflow

1. Start from the latest `main`.
2. Make the requested change, manually or with an AI coding assistant.
3. Preview `index.html` on desktop and mobile.
4. Review the diff and confirm that unrelated sections were not changed.
5. Commit the change with a short descriptive message.
6. Push/merge to `main`.
7. Confirm that the published website still renders correctly.

## Content ownership

The PI is the content owner. The designated lab website maintainer may handle routine updates such as publications, member profiles, photos, links, and contact details. Major changes to research positioning, scientific claims, unpublished data, or the visual identity should be confirmed with the PI before publishing.

## Public-data rule

Never place passwords, API keys, unpublished raw data, confidential collaborator information, or private personal information in this repository or in frontend website code. Even when a repository is private, deployed HTML/CSS/JavaScript is delivered to website visitors and should be treated as public.

## Current public links

- Google Scholar: https://scholar.google.com/citations?user=3EMW0WgAAAAJ
- ORCID: https://orcid.org/0000-0001-9067-9050
