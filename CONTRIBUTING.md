# Contributing to Aar-Act

The badge in the README linked here for a while before this file existed. It
does now, and this is what it should have said.

## What belongs here

Practices, guides and templates that an operator can read, understand and check
themselves. If a step cannot be verified by the person applying it, it is not
finished.

Write for a machine with constraints: limited bandwidth, older hardware, no
licence to renew, no vendor on call. A guide that only works with a fast link
and a support contract already has plenty of homes.

## Adding a guide

1. Write it in English in `practices/`, numbered: `NN-short-slug.md`.
2. Add the French version in `translations/`, carrying **the same number**, so
   the pair is obvious.
3. Update the table in `translations/README.md`.
4. Open a pull request. Keep it to one guide.

For a long guide, open an [issue](https://github.com/cyberaar/Aar-Act/issues)
first and agree the scope before writing it.

## House rules

- **French is written with full accents.** Unaccented French is a keyboard
  limitation, not a style.
- **No em dashes**, in either language. A comma, a colon or a full stop is
  almost always clearer.
- Commands are shown as they are actually run, with the distribution named when
  it matters. Debian and Ubuntu differ from Rocky and AlmaLinux often enough
  that "it depends" is not a useful instruction.
- Say what a change **costs**. A hardening step that breaks a workload is worth
  knowing about before it is applied, not after.

## Translations

A translation is not a word-for-word pass. Adapt the examples to a francophone
public sector context where that makes the guide clearer, and keep the technical
content identical to its source guide.

## License

By contributing you agree that your work is published under GPL-3.0, the licence
in [LICENSE](LICENSE).
