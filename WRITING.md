# Writing

This guide governs the text in this repository and its commit messages.
[AGENTS.md](AGENTS.md) owns how a change is made.

## Voice

Lead with the result or the reader's task. Use active voice, present tense,
concrete nouns, and short sentences. Assume no shared conversation history:
explain what a referenced issue or decision means, not just its identifier.

Describe observable behavior. Remove filler, marketing claims, emojis, and tool
signatures. Use sentence-case headings.

## Files GitHub shows elsewhere

A template or policy here is read inside other repositories. Write it so it
holds for every repository in the organization, and name a repository only when
the rule is about that repository. Link with absolute URLs.

## Markdown

Use CommonMark with blank lines around headings and lists. Wrap repository prose
at about 80 columns, except tables and long links. Do not hard-wrap GitHub
issue or pull request paragraphs. Exclude personal information and local
absolute paths from published text.

## Commits and pull requests

```text
Scope(type[detail]): concise description

why: Explanation of necessity or impact.

what:
- Specific changes made
- Focused on a single topic
```

The detail is optional. Keep subjects to 50 characters, excluding a trailing
`(#NN)`, and body lines to 72. Use an imperative verb phrase. Keep each commit
about one topic.

A pull request leads with the concrete problem and the resulting behavior, for
a reader who has not seen the conversation. Merge with a merge commit whose
subject ends in the pull request number, `Title (#NN)`, followed by `why:` and
`what:` sections.
