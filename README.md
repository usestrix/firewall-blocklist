# firewall-blocklist

Malicious package versions found by Strix's own scanning of new releases & public reports, plus those from
[ossf/malicious-packages](https://github.com/ossf/malicious-packages) & [OSV.dev](https://osv.dev).
Generated; don't edit.

One file per registry. Each row is tab-separated:
`<package> <version> <advisory id> <advisory URL>`.
The version is exact, `>=<version>`, or `*` for every version.
