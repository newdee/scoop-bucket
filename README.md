# scoop-bucket

[Scoop](https://scoop.sh) bucket for newdee's programs.

```powershell
scoop bucket add newdee https://github.com/newdee/scoop-bucket
scoop install unifyterm
```

| Program | What it is |
|---|---|
| [unifyterm](https://github.com/newdee/unifyterm) | One terminal for Windows, macOS and Linux: the same Unix commands everywhere |

`scoop update unifyterm` takes a new version. The manifests follow each program's own repository: a workflow here copies them every 6 hours, after installing each new version on Windows.