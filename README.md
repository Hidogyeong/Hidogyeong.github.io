# Dokyeong Kang — Academic Website

Personal academic website based on [AcademicPages](https://github.com/academicpages/academicpages.github.io).

Site URL: https://hidogyeong.github.io

The initial navigation contains Home (the site title), CV, and Publications. Google Scholar and GitHub are linked in the author sidebar.

## Edit content

| File | Content |
|---|---|
| `_config.yml` | Name, affiliation, avatar, and external profile links |
| `_pages/about.md` | Home-page introduction |
| `_data/cv.yml` | Education, research experience, and technical experience |
| `_data/publications.yml` | Shared publication entries used by Home, CV, and Publications |
| `_data/navigation.yml` | Navigation links |
| `files/` | Downloadable bibliography files and, when provided, a CV PDF |

See [SETUP_KO.md](SETUP_KO.md) for publication steps, [MAINTENANCE.md](MAINTENANCE.md) for updates, and [SOURCE_NOTES.md](SOURCE_NOTES.md) for content provenance and validation scope.

## Local Jekyll build

With a supported Ruby installation and Bundler:

```sh
bundle install
bundle exec jekyll serve
```

GitHub Pages can build this Jekyll site from `master` and the root folder. Enable **Settings → Pages → Deploy from a branch → master → /(root)**. The `Jekyll build` workflow also checks the site on pushes and pull requests; it validates the build but does not enable Pages by itself. The original AcademicPages sample biographies, papers, talks, posts, and sample files have been omitted.

The upstream license is preserved in [LICENSE](LICENSE), and the theme credit remains in the footer.
