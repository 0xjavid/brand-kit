# Contributing to the Base Brand Kit

We appreciate community contributions that help keep the Base brand resources complete and up to date. This guide outlines how to propose changes while preserving consistency across the repo.

## Getting Started

1. Fork this repository and clone your fork locally.
2. Create a feature branch for your work: `git checkout -b feature/your-change`.
3. After committing changes, open a pull request against the `main` branch of the upstream repository.

## Adding or Updating Assets

- **File formats:** Prefer vector formats (SVG, PDF) for logos and illustrations. Provide web-friendly raster formats (PNG, WebP) only when necessary and ensure transparency and color accuracy are preserved.
- **Naming:** Use descriptive, kebab-case filenames that indicate the asset type, colorway, and medium (for example, `base-square-blue-digital.svg`).
- **Folder structure:** Place new assets alongside similar resources (e.g., `logo/Logotype/Digital/`). Create subfolders only when a new category is required.
- **Optimization:** Optimize SVGs by removing unnecessary metadata and reducing precision without changing visual output. Raster assets should be exported at multiple resolutions when appropriate.

## Updating Guides and Documentation

- Keep terminology consistent with the [Brand Guide](guides/brand-guide.pdf) and [Editorial Style Guide](guides/editorial-style-guide.md).
- When describing color palettes, typography, or logo usage, include rationale for changes and link to supporting assets or documentation.
- For Markdown documents, use relative links so they continue to work when browsed on GitHub and in downloaded archives.

## Style and Review Checklist

Before opening a pull request, double-check that:

- [ ] All new files pass a spell-check and render as expected.
- [ ] Image previews load correctly in the README and related guides.
- [ ] Large binaries (over 25 MB) are avoided or delivered through an external download link.
- [ ] The README or other documentation references any new guide you introduce.

Thank you for helping maintain the Base visual identity!
