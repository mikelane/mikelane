# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub profile repository that showcases Mike Lane's professional identity and technical expertise. The README.md in this repository appears on the GitHub profile page at https://github.com/mikelane.

## Repository Structure

```
.
├── README.md                   # Main profile page (appears on GitHub profile)
├── CLAUDE.md                   # This file - guidance for Claude Code
├── CUSTOMIZATION_IDEAS.md      # Ideas for further profile enhancements
├── LICENSE                     # MIT License
└── images/
    └── MikeLane.png           # Profile banner image (legacy)
```

## Profile Content Sections

The README.md contains the following sections:

1. **Animated Header** - Typing animation with name and title
2. **About Me** - Professional summary highlighting role at GDIT, education, and leadership focus
3. **Tech Stack** - Categorized badges emphasizing Python/Rust, TypeScript, Java, cloud, and AI/ML
4. **GitHub Stats** - Dynamic statistics, streak, and activity graph
5. **Current Work** - Active projects (dioxide, valid8r, pytest plugins)
6. **Featured Projects** - Flagship projects organized by category
7. **Philosophy** - Core beliefs about software engineering
8. **Contact** - Ways to connect

## Key Projects

### Flagship Projects (Recommended for Pinning)

1. **[dioxide](https://github.com/mikelane/dioxide)** - Rust-backed Python DI framework (PyO3, cross-platform)
2. **[valid8r](https://github.com/mikelane/valid8r)** - Functional programming validation with Maybe monad
3. **[reddit-get](https://github.com/mikelane/reddit-get)** - CLI tool (23 stars, most popular)
4. **[pytest-test-categories](https://github.com/mikelane/pytest-test-categories)** - Testing plugin based on Google SWE
5. **[cookiecutter-python-library](https://github.com/mikelane/cookiecutter-python-library)** - Modern Python template
6. **[cookiecutter-backend-service-aws](https://github.com/mikelane/cookiecutter-backend-service-aws)** - AWS CDK template

These projects showcase:
- Multi-language expertise (Python + Rust via PyO3)
- Framework/library design
- Developer tooling and productivity
- Testing best practices
- Cloud/Infrastructure as Code

## Making Changes

### Updating Professional Information

**Current Position:** Principal Software Engineer and Dev Lead at GDIT

When updating the profile, consider which sections need changes:

```bash
# For title/role changes, update:
# - Animated header typing text (line 2)
# - About Me section (line 16)
# - Current Work section (line 76)
```

### Adding or Removing Technologies

Tech stack badges use shields.io format:
```markdown
![TechName](https://img.shields.io/badge/TechName-HEXCOLOR?style=for-the-badge&logo=logoname&logoColor=white)
```

Find badge details at: https://shields.io/ and https://simpleicons.org/

### Updating "What I'm Currently Working On"

This section should be refreshed regularly (monthly/quarterly) to reflect current focus:
- Team leadership activities
- Technical projects
- Learning initiatives
- Mentoring efforts

### GitHub Stats Configuration

Stats are generated dynamically from these services:
- **GitHub Stats:** `github-readme-stats.vercel.app`
- **Streak Stats:** `github-readme-streak-stats.herokuapp.com`
- **Activity Graph:** `github-readme-activity-graph.vercel.app`

Current theme: `tokyonight` (can be changed in URL parameters)

To change themes, replace `theme=tokyonight` with: `dracula`, `radical`, `merko`, `gruvbox`, `onedark`, etc.

### Pinned Repositories

The profile references pinned repositories. To update:
1. Visit https://github.com/mikelane
2. Click "Customize your pins"
3. Select up to 6 repositories that showcase:
   - Technical leadership and architecture
   - Python developer tools and libraries
   - DevOps/Infrastructure work
   - AI/ML applications

## Committing Changes

Use conventional commit messages when updating:

```bash
# Content updates
docs: update current role to Principal Engineer at GDIT
docs: add new technology to tech stack
docs: refresh current work section

# Visual updates
style: change stats theme to dracula
style: add new badge for Rust

# Structural changes
feat: add certifications section
feat: add blog posts section
refactor: reorganize tech stack categories
```

## Advanced Customizations

See `CUSTOMIZATION_IDEAS.md` for:
- Custom banner creation
- Additional stats and visualizations
- Dynamic content automation with GitHub Actions
- Profile enhancement tools and generators

## Testing Changes Locally

Since this is a Markdown file for GitHub, preview changes:

1. **VS Code:** Install "Markdown Preview Enhanced" extension
2. **Command Line:** Use `grip` to preview GitHub-flavored markdown:
   ```bash
   pip install grip
   grip README.md
   # Visit http://localhost:6419
   ```
3. **Online:** Use https://dillinger.io/ or https://stackedit.io/

## Content Philosophy

The profile emphasizes:
- **Technical Leadership** - Architecture, decision-making, strategy at GDIT
- **Team Development** - Mentoring, culture, growing technical talent
- **Multi-Language Expertise** - Python (primary), Rust (PyO3), TypeScript, Java
- **Framework Design** - Building libraries (dioxide, valid8r) not just using them
- **Developer Tooling** - pytest plugins, cookiecutters, productivity tools
- **Testing Excellence** - TDD, Google SWE principles, 100% coverage standards
- **Clean Architecture** - Dependency injection, ports-and-adapters, SOLID

Keep content:
- **Professional but personable** - Show expertise and humanity
- **Data-driven** - Use stats and metrics to show activity
- **Current** - Update regularly as dioxide and valid8r evolve
- **Authentic** - Represent actual skills (Python best, TypeScript second, Java third, Rust fourth)

## Language Expertise Order

Per user assessment:
1. **Python** (best) - dioxide, valid8r, pytest plugins, cookiecutters, FastAPI
2. **TypeScript** (second) - Svelte/Sapper personal sites, full-stack work
3. **Java** (third) - Spring framework demos
4. **Rust** (fourth) - But production-level via dioxide (PyO3), zero2prod learning

Tech stack badges show Python + Rust together to highlight dioxide (flagship project).

## License

This repository is licensed under the MIT License (see LICENSE file).
