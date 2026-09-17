# Maintaining this site

## Add a publication once

Add one entry to `_data/publications.yml`. Home, CV, and Publications read that same file. Keep the most relevant publication first for the Home page. Verify authors, venue, year, DOI, and publication status before adding a paper. Add a matching `.bib` file under `files/` if you expose a BibTeX link.

Google Scholar is linked as an external profile; changes here do not edit Scholar. Publication metadata is not scraped from Scholar at build time.

## Update the CV

Edit `_data/cv.yml` for education, research experience, and skills. Unknown dates and degrees were omitted from the initial version. A PDF can be added to `files/` and linked from the CV page after the full details are supplied. An uploaded PDF needs to be kept current separately.

## Change links and photo

Edit `author` in `_config.yml`. To show a public email, add an `email` field. To replace the initials, upload your photo under `images/` and change `author.avatar` to its filename.

## Template and deployment

This site is based on AcademicPages commit `c77da751a8124450d5fb818056c0cf081fea08e1`. Keep the upstream license and footer credit. Use the GitHub Pages build result as the final Jekyll integration check after the repository is created.
