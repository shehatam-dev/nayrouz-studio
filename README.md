# nayrouz-studio-site

Public pages for Nayrouz Studio, served by GitHub Pages at https://shehatam-dev.github.io/nayrouz-studio/.
They exist because Meta requires a public privacy policy, terms of service and data-deletion URL before
the "Nayrouz Studio Publisher" app (kids-printables `scripts/meta_post.py`) can be switched to Live mode.
Keep them true to what that script actually does: it publishes to our own Page and Instagram account and
reads our own posts for its duplicate check, and nothing else.

`posts/` holds pictures for Facebook/Instagram posts that aren't a single Etsy listing photo (a collage of
several designs, say): Instagram fetches a post's picture from a public URL, and these pages are that URL.
Each is referenced by a `posts/<slug>.toml` in kids-printables, whose comment says what it is made from.
Never replace a picture in place once its post is up; add a new file.
