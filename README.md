# Jay Goradia — research website

Static website for https://jgoradia3.github.io. No dependencies or build step.

## Publish
1. Sign into GitHub as **jgoradia3**.
2. Create a **public** repository named **jgoradia3.github.io**. Initialize with a README.
3. Upload the contents of this directory to the repository root (not the enclosing research-site folder). Replace the initial README with this one.
4. In Settings → Pages, select **Deploy from a branch**, then **main** and **/ (root)**, and Save.
5. Wait for the Pages deployment to finish, then visit https://jgoradia3.github.io.

Alternatively, after creating the repository, ask Codex to upload these prepared files through the connected GitHub account.

## Maintenance
- Add the approved arXiv link to the article page when available. No PDF or unpublished manuscript is bundled.
- Confirm the IEEE author list, DOI, volume, issue, and pages against your publisher record before publishing. Metadata was found in a third-party bibliographic record; IEEE's page could not be read during preparation.
- The overview is a paraphrase, not the official abstract. Replace or expand it using the actual manuscript. Detailed contributions, results, and limitations were deliberately not invented.
- Current selected work: IEEE article, verified RSAC blog post, and ScopedAct. This is not a complete publication list.
- Add a citation_pdf_url meta tag only when a real permitted full-text PDF URL exists.
- Keep the published DOI citation as the suggested citation when linking a manuscript version.
- No private email, analytics, external font dependencies, or tracking scripts are included.

## Discoverability
The site includes descriptive HTML, canonical links, social metadata, Google Scholar citation metadata on the article page, robots.txt, and sitemap.xml. After launch, verify the site in Google Search Console and submit sitemap.xml. Indexing and citations are not guaranteed.

## Preview locally
Run `python3 -m http.server 8000` in this directory and open http://localhost:8000.

## Content sources
- User-provided Google Scholar profile: https://scholar.google.com/citations?user=P0TssKQAAAAJ&hl=en
- User-provided IEEE article: https://ieeexplore.ieee.org/document/11743312
- Bibliographic record: https://eurekamag.com/research/111/987/111987771.php
- RSAC publication and author identity: https://www.rsaconference.com/library/blog/the-new-cti-blind-spot-ai-agents-and-non-human-identities
- ScopedAct README and research mapping: https://github.com/jgoradia3/scopedact
