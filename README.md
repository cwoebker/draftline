# Draftline

A Markdown editor for iPhone and iPad that uses your GitHub repositories as
its file system. Open a repo, pick a branch, write, commit.

Built for people who publish from a repository: blogs on Jekyll, Hugo, Astro or
Eleventy, documentation sites, and plain notes in git.

- **Bytes you did not touch come back byte-identical.** Edit one paragraph and
  the commit shows one paragraph. Frontmatter, raw HTML, Liquid tags and
  anything else the editor cannot render are kept exactly as written and shown
  as chips, never rewritten.
- **Real commits on real branches.** Edits are kept per branch until you commit
  them with your own message. A commit is refused when the branch moved under
  you, so nothing is overwritten silently.
- **Works offline.** The last repository, branch, file tree and open file come
  back from the cache at launch. Edits wait until you are back online.
- **Knows about pull requests.** See the branch's pull request, its checks and
  deployments, and open the preview site in one tap.
- **Nothing leaves your device except to GitHub.** No analytics, no server of
  ours, no account to create.

[Available on the App Store](https://apps.apple.com/us/app/draftline-markdown-editor/id6809581821) for iPhone and iPad.

## Signing in

Sign in with GitHub through the Draftline GitHub App, or paste a fine-grained
personal access token. A token needs *Contents* read and write on the
repositories you want to edit; add *Pull requests*, *Checks* and *Deployments*
read to see the pull request row. Your credential is stored in the system
Keychain and sent only to GitHub.

## Support

Questions and bug reports are welcome — open an issue at
[cwoebker/draftline](https://github.com/cwoebker/draftline/issues). Please
include which device and version you are on.

- [Support](https://cwoebker.github.io/draftline/support.html)
- [Privacy policy](https://cwoebker.github.io/draftline/privacy.html)
