# Contribution Guidelines

Thank you for your interest in contributing to **Awesome Developer Learning Roadmaps**! This is a premium, community-driven resource, and we rely on contributors like you to keep it accurate, high-quality, and up-to-date.

We optimize for **trust, readability, and long-term maintainability** over quantity. Please read these guidelines carefully before contributing.

---

## 1. Curation Standards

We do NOT accept every link. To be included in this repository, a resource must be:

- **Authoritative:** Coming from a trusted organization (e.g., universities, major tech companies) or a widely respected community platform (e.g., Roadmap.sh, OSSU).
- **Structured:** It must be an actual roadmap or a structured curriculum, not just a random blog post or a single tutorial video.
- **High Quality:** The content must be accurate, up-to-date, and pedagogically sound.
- **Unique:** We do not want 10 different roadmaps for the exact same topic unless they offer significantly different learning styles (e.g., video-based vs text-based, or university-style vs bootcamp-style).

## 2. How to Contribute

You can contribute in several ways:
- **Adding a new roadmap:** Propose a high-quality resource that is currently missing.
- **Fixing broken links:** Help us maintain the repository by reporting or fixing dead links.
- **Improving metadata:** Update the "Last Updated" year, refine the "Difficulty", or improve the descriptions.

---

## 3. Adding a New Roadmap

1. **Open an Issue First:** Before writing any code, open an issue using the "New Roadmap" template to propose the resource. This allows us to discuss its inclusion and prevents you from doing wasted work.
2. **Format:** All roadmaps must be added to the markdown tables in the appropriate `<details>` section.
3. **Table Structure:**
   ```markdown
   | [Roadmap Name](URL) | 🟢 Beginner | 2–4 Months | 🌐 Website | 2024 | ⭐⭐⭐⭐⭐ | A concise description. |
   ```

### Metadata Guide
- `Difficulty`: Use emojis (🟢 Beginner, 🟡 Intermediate, 🟠 Advanced, 🔴 Expert). Combinations are allowed (e.g., 🟢 Beginner → 🟠 Advanced).
- `Estimated Time`: A realistic time estimate (e.g., `2–4 Months`). If unknown, use `—`.
- `Resource Type`: Use emojis:
  - 🌐 Website
  - 📂 GitHub
  - 📄 PDF
  - 🎥 Video
  - 📚 Documentation
  - 🎓 Course
  - 🛠 Interactive
- `Last Updated`: The most recent year the source was updated (e.g., `2024`). Do not invent dates; if unknown, use `—`.
- `Rating`: Use stars (e.g. ⭐⭐⭐⭐⭐) based on community consensus and quality.
- `Description`: A concise (1-2 sentence) description of *why* this resource is valuable.

---

## 4. Submitting a Pull Request (PR)

1. Fork the repository and create your branch from `main`.
2. Make your changes.
3. Ensure your markdown tables are aligned properly. Do not break the table formatting.
4. Fill out the Pull Request Template completely.
5. Submit the PR.

**Note:** We use automated GitHub Actions to lint markdown and check for broken links. Ensure your PR passes these checks before requesting a review.

Thank you for making this awesome list better!
