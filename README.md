# Vinci Code Releases

Public downloads, release notes and the retained reporting surface for Vinci
Code, the terminal coding agent. Current source and product development live
in [vinci-code-cli](https://github.com/getsimpledirect/vinci-code-cli).

## Install

Use Node.js 22.19 or newer and follow the
[canonical installation instructions](https://github.com/getsimpledirect/vinci-code-cli#installation).
The existing signed-release installer is:

```sh
curl -fsSL https://vinci.getsimpledirect.com/install | sh
```

Run `vinci`, use `/login` to configure an available provider, and inspect
`vinci --version` or `/version` for the installed version. Bringing your own
provider key does not require a Vinci account. Managed-service admission is
separate from installation and is not promised by this feed.

## Releases and compatibility

Browse [Releases](https://github.com/getsimpledirect/vinci-code-releases/releases)
for retained assets and notes. Current product release authority belongs to the
public source repository's protected workflow. Preserve existing asset links
and release consumers until their migration is verified; this repository does
not authorize a second build or signing process.

The installed product verifies its signed update manifest and archive hash.
To assess a particular update, inspect the artifact actually served and its
version; a green workflow or release listing is not download verification.

## Bugs, support and security

Use the [current support guide](https://github.com/getsimpledirect/vinci-code-cli/blob/main/SUPPORT.md)
for the right reporting destination. Existing reports here remain part of the
project history. Include your version, expected behavior, actual behavior and
a minimal reproduction that contains no private source, tokens or API keys.

For vulnerabilities, follow the
[current security policy](https://github.com/getsimpledirect/vinci-code-cli/blob/main/SECURITY.md).
Issues and attachments here are public.

## License and provenance

Vinci Code is based on [Pi](https://github.com/badlogic/pi-mono), copyright
© 2025 Mario Zechner. Pi and Vinci's published modifications retain the
[MIT license](LICENSE), including the Alpine Pacific Trading Inc. notice.
Artifact-specific third-party notices and trademark restrictions remain in
force. A software license is not a confidentiality or access-control mechanism.
