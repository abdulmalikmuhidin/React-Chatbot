## GitHub Copilot Chat

- Extension: 0.55.0 (prod)
- VS Code: 1.127.0 (4fe60c8b1cdac1c4c174f2fb180d0d758272d713)
- OS: win32 10.0.19045 x64
- GitHub Account: abdulmalikmuhidin

## Network

User Settings:

```json
  "http.systemCertificatesNode": true,
  "telemetry.telemetryLevel": "all",
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:

- DNS ipv4 Lookup: 140.82.121.6 (1 ms)
- DNS ipv6 Lookup: Error (10 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (5 ms)
- Electron fetch (configured): HTTP 200 (155 ms)
- Node.js https: HTTP 200 (641 ms)
- Node.js fetch: HTTP 200 (164 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:

- DNS ipv4 Lookup: 140.82.113.22 (1 ms)
- DNS ipv6 Lookup: Error (12 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (6 ms)
- Electron fetch (configured): HTTP 200 (231 ms)
- Node.js https: HTTP 200 (2179 ms)
- Node.js fetch: HTTP 200 (239 ms)

Connecting to https://proxy.individual.githubcopilot.com/_ping:

- DNS ipv4 Lookup: 4.225.11.192 (8 ms)
- DNS ipv6 Lookup: Error (7 ms): getaddrinfo ENOTFOUND proxy.individual.githubcopilot.com
- Proxy URL: None (4 ms)
- Electron fetch (configured): HTTP 200 (190 ms)
- Node.js https: HTTP 200 (601 ms)
- Node.js fetch: HTTP 200 (951 ms)

Connecting to https://mobile.events.data.microsoft.com/OneCollector/1.0?cors=true&content-type=application/x-json-stream (Electron fetch): HTTP 200 (281 ms)
Connecting to https://telemetry.individual.githubcopilot.com/telemetry (Node.js https): HTTP 200 (756 ms)
Connecting to https://default.exp-tas.com/vscode/ab (Node.js fetch): HTTP 200 (721 ms)

Number of system certificates: 79

## Notes

- Active fetcher: Electron fetch.
- For corporate networks also see: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).
