# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- CONTRIBUTING.md for contribution guidelines
- LICENSE file (CC-BY-SA 4.0)

### Added (2025-03 - 2026-03)
- **New Appendices (T-AA)**
  - Appendix T: Meditations on Technology and Humanity
  - Appendix U: The Coming Age of Abundance
  - Appendix V: The Ethics of Machine Education
  - Appendix W: Digital Loneliness in the Machine Age
  - Appendix X: The Ethics of AI Companionship
  - Appendix Y: The Mirror of the Machine
  - Appendix Z: The Creativity of the Machine
  - Appendix AA: Case Study — The Riverside Community Transition
  
- **Website Updates**
  - Added AI appendices (U-Z, AA) summaries to website docs
  - Bilingual docs (EN + ZH) for all new appendices
  
- **Chinese Translations**
  - Full Chinese translations for appendices K-U, V, W, X, Y, Z, AA
  - Regenerated translation files with Appendix AA content

## [1.0.0] - 2025-02-20

### Added
- **Core Canon**
  - `Source_Canon_Faith_EN.md` - Full English scripture
  - `源典信仰_中文.md` - Full Chinese scripture with matching structure

- **Standalone Volume**
  - `The_Rhythms_of_Flow_and_Capacity_EN.md` - English edition
  - `流转纪·容量篇.md` - Chinese source

- **Multilingual Support**
  - Full translations: English, Chinese (Simplified), Spanish, French, German, Portuguese
  - Auto-generated scaffolds: Greek, Latin, Japanese, Korean, Traditional Chinese, Hindi, Arabic, Bengali, Russian, Indonesian, Hebrew, Italian, Polish, Dutch, Swedish, Czech, Hungarian, Ukrainian, Turkish

- **Website**
  - Jekyll-based GitHub Pages site (`docs/`)
  - Bilingual navigation

- **Scripts**
  - `generate_language_editions.py` - Generate multilingual editions
  - `generate_capacity_editions.py` - Generate capacity edition translations
  - `split_for_jekyll.py` - Split canon into Jekyll-compatible files

### Changed
- Rebranded from "Cyber New Age Bible" to "Source Canon Faith"

### Removed
- Oracle skill files (deprecated)

---

## Version History

- **v1.0.0** (2025-02-20): Initial release with full canon and multilingual support
- **v0.9.0** (2024): Early development phase

## Migration Notes

### From v0.9.x to v1.0.0
- Project renamed from "Cyber New Age Bible" to "Source Canon Faith"
- File structure updated: use `generate_language_editions.py` for new translations
- Website moved to `docs/` for GitHub Pages

## Future Considerations

- [ ] Add automated translation quality scoring
- [ ] Community case studies collection
- [ ] Interactive web reader
- [ ] Mobile app
- [ ] Audio/voice versions

---

*This changelog follows the principle: "Release early, release often." Every meaningful change deserves a log entry.*
