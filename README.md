# Academic website template

A small Jekyll website for an academic personal page, based on the layout of the source website. It includes an About page, a Research page with an optional expandable abstract, a profile photo, and a CV link.

## Open a quick preview

Double-click `preview.html`. It opens directly in Safari, Chrome, or another browser without installing anything. This is a static copy of the site's actual rendered About page and compiled theme CSS. Use the navigation bar to open the separate Research page (`research-preview.html`) or the CV.

This is a standalone preview, so edits to the Jekyll files do not automatically update it. Use the local Jekyll instructions below when you want to preview the exact publishable site.

## Customize it

1. Edit `_config.yml` and replace every placeholder such as `Your Name`, `YOUR-USERNAME`, `YOUR-X-HANDLE`, `YOUR-LINKEDIN-HANDLE`, `Field`, and `University`.
2. Rewrite `_pages/about.md` with your biography and research interests.
3. Replace the sample entries in `_pages/research.md` with your papers.
4. Replace `images/profile.jpg` with your own photo, keeping the same filename.
5. Replace `pdfs/CV.pdf` with your own CV, keeping the same filename.
6. Search once more for placeholders before publishing:

   ```bash
   rg -n "Your Name|YOUR-USERNAME|YOUR-X-HANDLE|YOUR-LINKEDIN-HANDLE|Field|University|Paper Title|Coauthor Name|your.email"
   ```

The included `profile.jpg` and `CV.pdf` are example assets intentionally retained from the source site. Replace them before sharing or publishing a personalized copy.

## Preview locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000> in a browser. Restart Jekyll after changing `_config.yml`.

## Publish with GitHub Pages

1. Create a public GitHub repository named `YOUR-USERNAME.github.io`.
2. Copy the contents of this folder into that repository.
3. Set `url` and `repository` in `_config.yml` to your GitHub username and repository.
4. Commit and push to the repository's default branch.
5. In the repository settings, enable GitHub Pages using that branch if it is not enabled automatically.

For a custom domain, add a file named `CNAME` at the repository root containing only the domain name, then update `url` in `_config.yml`.

## Research entry format

The Research page mirrors the source site's four-entry Work in Progress section. Duplicate or remove entries as needed. Each entry can contain:

- paper title;
- coauthors;
- links to a paper, slides, code, or data;
- an optional abstract button and abstract text.

## License

This template is available under the MIT License. The layout retains attribution to Jekyll, AcademicPages, and Minimal Mistakes in the footer.
