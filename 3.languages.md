Support 3 languages: en, de, vi. 
Use proper i18n architecture with locale files, translation keys, manual language switcher, localized SEO metadata, correct lang attributes, and hreflang where relevant. 
Test language switching, fallback behavior, and rendering for all 3 locales with Vitest + React Testing Library.

Use translation files such as:
- locales/en/*.json
- locales/de/*.json
- locales/vi/*.json

Rules:
- No hardcoded UI text
- All text must come from translation keys
- Use consistent key naming
- Include fallback language handling
- Localize page title, meta description, CTA text, form labels, placeholders, errors, and alt text
