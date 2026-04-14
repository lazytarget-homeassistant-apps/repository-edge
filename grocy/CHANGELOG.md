# Changelog since v0.25.2
- Adds Grocy add-on migration guide and script (#12) 
- ⬆️ Update ghcr.io/hassio-addons/base Docker tag to v20.0.4 (#15)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>

This PR contains the following updates:

| Package | Type | Update | Change |
|---|---|---|---|
| [ghcr.io/hassio-addons/base](https://addons.community)
([source](https://redirect.github.com/hassio-addons/addon-base)) | |
patch | `20.0.1` → `20.0.4` |
| [ghcr.io/hassio-addons/base](https://addons.community)
([source](https://redirect.github.com/hassio-addons/addon-base)) | final
| patch | `20.0.1` → `20.0.4` | 
- ⬆️ Update PHP to v8.5.5-r1 (#16)

Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>

This PR contains the following updates:

| Package | Update | Change |
|---|---|---|
| alpine_3_23/php85 | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-ctype | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-exif | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-fileinfo | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-fpm | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-gd | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-iconv | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-intl | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-ldap | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-mbstring | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-openssl | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-pdo | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-pdo_sqlite | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-phar | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-simplexml | patch | `8.5.4-r0` → `8.5.5-r1` |
| alpine_3_23/php85-tokenizer | patch | `8.5.4-r0` → `8.5.5-r1` | 
- chore: expand renovate custom managers and package rules (#14)

## Summary
- add Renovate regex custom managers for Dockerfile and build.yaml image
tags
- add Renovate regex manager for Alpine package versions via Repology
- add package rules for digest pinning, datasource grouping, and
selective automerge

## Testing
- no runtime changes (configuration-only update) 
- chore: expand renovate custom managers and package rules 
- ci: pin reusable workflow refs to v2.2.0 (#13-fix) 
- ci: pin reusable workflow refs to v2.2 (#13)

## Summary
- pin all reusable GitHub Actions workflow references to 2.2
- replace floating refs from edge/main with tagged versions
- standardize workflow source to lazytarget-homeassistant-apps/workflows

## Why
Using pinned workflow versions improves reproducibility and avoids
unexpected behavior changes from moving branches.

## Files changed
- .github/workflows/ci.yaml
- .github/workflows/deploy.yaml
- .github/workflows/labels.yaml
- .github/workflows/lock.yaml
- .github/workflows/pr-labels.yaml
- .github/workflows/stale.yaml 
- ci: pin reusable workflow refs to v2.2

Replace floating workflow refs (edge/main) with pinned v2.2 tags.

This aligns CI, deploy, and repository automation workflows with the lazytarget-homeassistant-apps/workflows v2.2 release for consistent and reproducible runs. 
