# Contributing guidelines

Thank you for your interest in contributing to this Hack Club-themed
Mkdocs theme! Even though this is not a HQ open-source project, we
want to support those using Mkdocs for their docs sites.

## Prerequisites / Preflight Check

- Read and agree to the [Community Code of Conduct][ccoc][^1] and the
[Linux DCO][dco][^2].
- Make sure Python 3.12+ and Pipenv + Poetry is installed in your
machine (or open this repo in [Codespaces] or via Remote Dev Containers)

[ccoc]: https://policies.recaptime.dev/code-of-conduct
[dco]: https://developercertificate.org/
[Codespaces]: https://codespaces.dev/lorebooks-wiki/mkdocs-hackclub
[Hack Club CoC]: https://hackclub.com/conduct/
[Contributor Convenant]: https://www.contributor-covenant.org/

[^1]: We also adopted [Hack Club CoC] alongside [Contributor Convenant], although sending mod reports should still go to `abuse@recaptime.dev`.
[^2]: Instead of doing a CLA, we opt to use the DCO for easy compliance as well as to track signatures via Git commit logs.

## Dev Setup

**For development**: Run `pipenv install` to install this theme for updating the
theme templates and plugins, as well as documentation.

**For packaging**: Run `poetry install` to get the dependencies installed. Currently,
you can't use this theme for `mkdocs serve` under `poetry run` for now.

## Coding style

- For indention, we use 2 spaces per level of indention (VS Code will usually use 4,
but you can adjust it on per-file basis if needed.)
  - For Mkdocs, you may need to use 4 spaces.
- For comments and Markdown, keep it below 90 characters per line, especially for those
reading the documentation files from source.

## Sending patches

We use the GitHub + GitLab flow for the handling patches/merge requests, although
we can also accept email patches over at sourcehut.

Don't forget to add yourself to the [`CONTRIBUTORS`](./CONTRIBUTORS) list to
properly credit your work. (You don't have to use your legal name there.)
