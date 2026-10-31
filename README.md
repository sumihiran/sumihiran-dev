# sumihiran.dev

Source for [sumihiran.dev](https://sumihiran.dev). Built with Jekyll on GitHub Pages.

## Writing

Add `_posts/YYYY-MM-DD-slug.md`:

```yaml
---
title: Influence without authority
category: leadership   # leadership | engineering | innovation
description: One sentence for search and link previews.
# last_modified_at: 2026-11-20
# update_note: Reworded the intro.
---
```

Drafts go in `_drafts/`.

## Running locally

```bash
docker run --rm -it -p 4000:4000 -v "$PWD":/srv -v sumihiran-gems:/usr/local/bundle -w /srv ruby:3.3 sh -c "bundle install && bundle exec jekyll serve --drafts --host 0.0.0.0"
```

## License

© 2026 Nuwan Bandara. All rights reserved. You're welcome to link to posts and quote short excerpts with credit and a link back; see [LICENSE](LICENSE) for the details.

Font: [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), SIL Open Font License ([assets/fonts/OFL.txt](assets/fonts/OFL.txt)).
