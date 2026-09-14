# EEC

A personal Claude Code plugin marketplace, currently hosting one plugin: `ecc-skills`, a
collection of 292 reusable skills vendored from [affaan-m/ECC](https://github.com/affaan-m/ECC).

## Using these skills in a future project

In any Claude Code session (mobile, web, or CLI), run once per machine/account:

```
/plugin marketplace add BG-Guy/EEC
/plugin install ecc-skills@eec
```

That installs the skills at user scope, so they're available in every future project
automatically — no need to copy files into each new repo. To update after this repo changes:

```
/plugin update ecc-skills
```
