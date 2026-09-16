# Contributing to GoLangBooks

Thanks for helping keep this collection useful, navigable, and respectful of authors' rights.

## What belongs here

A contribution should be:

- focused on the Go programming language or its ecosystem;
- useful beyond a single short-lived release;
- complete enough to be a meaningful learning resource; and
- legally redistributable by this repository.

Please do not submit paid books, leaked copies, scraped material, duplicates, or files whose redistribution terms are unclear. When adding a resource, include its source and license or redistribution permission in the pull request description.

## Where files go

Choose the directory that best matches the book's primary subject:

| Directory | Use it for |
| --- | --- |
| `books/fundamentals/` | Language introductions, idioms, and general Go practice |
| `books/data-structures-and-patterns/` | Algorithms, data structures, and design patterns |
| `books/web-and-services/` | Web applications, APIs, and microservices |
| `books/systems-and-security/` | Systems programming, networking, and security |
| `books/architecture-and-advanced/` | Architecture, performance, and advanced production topics |

If a title crosses categories, place it under its strongest theme rather than adding duplicate copies.

## Naming convention

- Use lowercase kebab-case: `the-go-programming-language.pdf`.
- Keep the original format extension: `.pdf` or `.epub`.
- Add an edition suffix only when it distinguishes the title: `book-name-2e.epub`.
- Avoid author names, source-site prefixes, and marketing subtitles in filenames.

## Pull request checklist

1. Search [`docs/CATALOG.md`](docs/CATALOG.md) and the `books/` tree for duplicates.
2. Put the file in the correct topic directory and normalize its filename.
3. Add or update its entry in [`docs/CATALOG.md`](docs/CATALOG.md).
4. Explain the source and redistribution permission in the pull request.
5. Check that every changed Markdown link resolves locally.

Documentation-only improvements are welcome too. Keep changes focused, explain why they improve navigation or accuracy, and preview the rendered Markdown before submitting.
