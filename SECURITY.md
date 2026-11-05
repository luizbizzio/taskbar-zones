# Security Policy

## Supported versions

Security fixes are provided for the latest release of **Taskbar Zones** when needed. Older versions may not receive fixes.

| Version | Supported |
| --- | --- |
| Latest release (1.0.0) | Yes |
| Older versions | No |

## Report a vulnerability

Please **do not share security vulnerabilities in public issues or discussions**.

To report a security issue privately:

1. Open the [Taskbar Zones repository](https://github.com/luizbizzio/taskbar-zones).
2. Go to **Security** and select **Report a vulnerability**, if available.
3. Explain the issue, the Windows version, the Taskbar Zones version, and how to reproduce it.
4. Include logs or screenshots if they help, but remove personal information first.

If private reporting is not available, open a public issue **only to request a private contact method**. Do not include details of the vulnerability.

Reports will be reviewed, and confirmed issues may be fixed in a future release. Please allow time for investigation before public disclosure.

## Security notes

- Taskbar Zones runs inside Windows Explorer through Windhawk and changes the taskbar layout. Bugs may affect Explorer stability.
- Install Windhawk and Taskbar Zones only from sources you trust. Review the source code before installing if you have concerns.
- Keep Windows, Windhawk, and Taskbar Zones updated.
- Do not run other taskbar layout mods that change the same buttons at the same time. This can cause conflicts.

For normal bugs or feature requests, use [GitHub Issues](https://github.com/luizbizzio/taskbar-zones/issues).
