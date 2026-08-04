# Fatcat

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fatcat is a versioned, user-editable open catalog of published research works maintained by the Internet Archive. It tracks bibliographic metadata, links papers to full-text copies, and preserves access to scholarly publications across millions of research works.

## API

- **Base URL:** https://api.fatcat.wiki/v0
- **Documentation:** https://guide.fatcat.wiki/http_api.html
- **API Reference:** https://api.fatcat.wiki/redoc
- **OpenAPI Spec:** https://raw.githubusercontent.com/internetarchive/fatcat/master/fatcat-openapi2.yml

## Authentication

Read operations are publicly accessible. Write operations require a Bearer token (macaroon format) obtained from an editor account. Accounts are created via OAuth2 through Internet Archive, ORCID, GitHub, or Wikimedia.

## Entity Types

- **Release** - Specific publications (articles, papers, books)
- **Work** - Abstract grouping of releases (same intellectual work, different editions)
- **Container** - Journals, conferences, book series
- **Creator** - Individuals or organizations (authors, editors)
- **File** - PDFs and other documents with verified checksums
- **Fileset** - Datasets and collections of files
- **Webcapture** - Archived web pages

## Identifier Lookup

The API supports lookup by a wide range of external identifiers including DOI, PMID, arXiv ID, ISBN-13, ISSN-L, ORCID, and more.

## Pricing

Free. No cost for any API usage. Funded by Internet Archive and the Andrew W. Mellon Foundation.

## Resources

- **Homepage:** https://fatcat.wiki/
- **Guide:** https://guide.fatcat.wiki/
- **GitHub:** https://github.com/internetarchive/fatcat
- **Community:** https://gitter.im/internetarchive/fatcat
- **QA Environment:** https://api.qa.fatcat.wiki/v0
