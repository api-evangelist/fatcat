# Fatcat

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
