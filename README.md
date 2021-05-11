# Logseq RFCs

Logseq RFC (request for comments) provides a consistent and controlled path for new features to enter the project. During the process, the author can gather feedbacks as soon as possible, while enhancing the design and implementation.

Since Logseq is not a code library or a pure tech product, its RFCs should be less formal and more flexible.

## When to create a RFC

Start this process if you intend to add a "substantial" feature to Logseq. Issues and feature request do not require an RFC.

## The Process

- Fork the repo http://github.com/logseq/rfcs
- Copy `0000-template.md` to `text/0000-my-feature.md` (where
  'my-feature' is descriptive. Don't assign an RFC number yet)
- Fill in the RFC
- Submit a pull request. As a pull request the RFC will receive design
  feedback from the larger community, and the author should be prepared
  to revise it in response.
- If the RFC gains broad support and the team's approval, the pull request will be merged and given a incremental number.
- Along the process, someone (need not be the RFC author) can provde implementation for the RFC.
- The team will accept the implementation when they decide it's ready to go.

**Logseq's RFC process owes its inspiration to the [React RFC process].**

[react rfc process]: https://github.com/react/rfcs
