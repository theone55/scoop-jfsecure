# Scoop bucket for JFSecure

[JFSecure](https://secure.jfolio.org/) — secrets and snippets at a global hotkey, with an offline deniable vault.

```powershell
scoop bucket add jfsecure https://github.com/theone55/scoop-jfsecure
scoop install jfsecure/jfsecure
```

Runs the same per-user setup as the website (`%LOCALAPPDATA%\JFSecure`), so the app can update itself;
`scoop update jfsecure` works too. The `jfs` command is on PATH after the first start.
Vaults stay in `%APPDATA%\JFSecure` on uninstall.

This repo holds only the manifest; it is updated automatically by each JFSecure release.
