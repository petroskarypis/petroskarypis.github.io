# petroskarypis.github.io

Personal site and blog. Plain Jekyll, built by GitHub Pages from `main` (no theme, no Actions).

## Preview locally

Needs Homebrew's Ruby 3.3 (`brew install ruby@3.3`); Ruby 4 can't build the GitHub Pages gems.

```bash
PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH LC_ALL=en_US.UTF-8 bundle exec jekyll serve
```

Then open http://localhost:4000. First time only: `bundle config set --local path vendor/bundle && bundle install`.

## Writing a post

Add `_posts/YYYY-MM-DD-slug.md` with `title` and `description` in the front matter. Math: `$$...$$` inline and on its own lines for display (KaTeX). Figures: `{% include figure.html src="/assets/img/..." caption="..." %}`.
