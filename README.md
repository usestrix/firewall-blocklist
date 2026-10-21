# firewall-blocklist

Malicious package versions from [ossf/malicious-packages](https://github.com/ossf/malicious-packages),
including advisories in unmerged PRs. Generated; don't edit.

One file per registry. Each row is tab-separated:
`<package> <version> <advisory id> <advisory URL>`.
The version is exact, `>=<version>`, or `*` for every version.
