# Dumpr

Jekyll-powered landing and docs site for **Dumpr** — an iOS app that
turns one rambling brain dump into clean items in your reminders and
calendar.

Hosted via GitHub Pages at <https://dumpr.agnticstudio.com>.

## Pages

- `/` — home / marketing page (`index.md`)
- `/onboarding/` — getting-started guide
- `/manual/` — user manual
- `/privacy/` — privacy policy
- `/eula/` — end-user licence agreement
- `/dump/` — share-dump receiver fallback (static HTML; preserved as-is)
- `/.well-known/apple-app-site-association` — Apple Universal Link verification

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

Requires Ruby 3.x and Bundler. Run `gem install bundler` if needed.
