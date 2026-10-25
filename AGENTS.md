# AGENTS.md

Rules for this repository: the community health files of the
[vcs-python](https://github.com/vcs-python) organization. GitHub applies a file
here to every repository in the organization that has none of its own, so one
change here changes all of those repositories.

Follow the conventions already in the tree, and keep a change scoped to what was
asked for.

## What is here

Organization defaults that GitHub reads, and the policies they link to:

| Path | What it is |
| --- | --- |
| [PULL_REQUEST_TEMPLATE.md](PULL_REQUEST_TEMPLATE.md) | The pull request template of every repository without its own |
| [AI_POLICY.md](AI_POLICY.md) | How the vcs-python projects treat AI tools, which the template links |
| [README.md](README.md) | What the repository is for |

## Which policy applies

- Documentation, user-facing text, and commit messages: [WRITING.md](WRITING.md)
- Use of AI tools, issues, and pull requests from contributors:
  [AI_POLICY.md](AI_POLICY.md)

Each file is the single home for its subject.

## Change discipline

- Make the smallest coherent change that solves the verified problem.
- Check which repositories a change reaches before making it: a repository with
  its own copy of a file ignores the default here.
- Keep a rule that only one repository needs in that repository.
- Use absolute links in any file GitHub shows in another repository, such as a
  template. A relative link there resolves against that repository.
- Check that every link answers and every anchor exists before committing.
- Keep WRITING.md identical to
  [libtmux/.github's](https://github.com/libtmux/.github/blob/HEAD/WRITING.md),
  and change it in every organization's .github repository together.

## References

- [Creating a default community health
  file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [vcspull](https://vcspull.git-pull.com/)
- [libvcs](https://libvcs.git-pull.com/)
- [g](https://g.git-pull.com/)
