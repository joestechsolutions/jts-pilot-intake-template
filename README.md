# jts-pilot-intake

The ZW Home Construction pilot intake form for Joe's Tech Solutions.

**Live:** https://joblas.github.io/jts-pilot-intake/

A simple HTML form wired to FormSubmit. Submissions go to `joe@joestechsolutions.com`.

## Files

- `index.html` — the 9-question intake form
- `thanks.html` — the post-submit confirmation page

## Editing

1. Edit the files locally
2. `git commit -am "..."`
3. `git push`

GitHub Pages auto-deploys on push to `main`. Changes go live in ~60 seconds.

## FormSubmit activation

The first submission to FormSubmit will email `joe@joestechsolutions.com` with a one-time activation link. Click it once. After that, every submission lands in the inbox as a formatted table.

## Future use

When clients 2-5 come online, copy this repo, swap the form fields, and update the FormSubmit endpoint. Or use the existing one with a `_subject` prefix to route by client.
