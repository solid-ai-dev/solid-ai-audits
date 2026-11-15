# solid-ai-audits

Dated reviews of
[solid-ai-templates](https://github.com/solid-ai-dev/solid-ai-templates):
360 audits, template-quality reports and agent-perspective reviews.

The efficacy benchmark's round reports live with the benchmark, in
[solid-ai-benchmark](https://github.com/solid-ai-dev/solid-ai-benchmark).

## Layout

| Path                           | Holds                                |
| ------------------------------ | ------------------------------------ |
| `reports/YYYY-MM-DD-360.md`    | A 360 audit                          |
| `reports/YYYY-MM-DD-<kind>.md` | Any other review, named for its kind |

- A report is a record of its date; it is never edited after it merges
- A report links into the templates at a fixed commit, so its links read
  the tree it assessed
- Add a report by pull request; file an issue in the templates repo for
  every actionable finding, and reference it from the report

## History

The reports up to 2026-10-24 were kept in the templates repo's
`docs/audits/` until
[9f6b6afa](https://github.com/solid-ai-dev/solid-ai-templates/tree/9f6b6afa0ce876f0d70619faa24fc9dc16cfe6ce/docs/audits).

## License

[MIT](LICENSE)
