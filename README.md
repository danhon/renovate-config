# renovate-config

The shared [Renovate](https://docs.renovatebot.com/) preset for Dan's
self-hosted apps. A repo uses it with a `renovate.json` of:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>danhon/renovate-config"]
}
```

plus `ignoreDeps` for any image the repo builds itself. The rules are in
`default.json`, each with its reason. Nothing automerges.
