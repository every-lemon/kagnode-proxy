# 5.0.5 (unreleased)

- Fixed for 5.0.5

## 5.0.4 — release preparation

- Rename the visible product name from KagNode. PM to KagNode. Proxy in the interface, login, page titles, documentation and artwork text. The GitHub repository is `kagnode-proxy`; package names, the `kagnode-pm` command, installed paths, API paths, signed manifests and published release assets keep their compatibility identifiers.

## 5.0.3

- Adopt Core form dialogs with one close control and guarded Cancel behavior.
- Add bounded node-side TCP upstream reachability with permission, revision, capability and rate-limit checks.
- Report connectivity separately from application health; no HTTP request or root helper is used for probes.

# 5.0.2

- Replace raw proxy editing with grouped routing, upstream, TLS, access and advanced controls; preserve weighted/backup peers and existing settings.
- Add route/domain/upstream filtering, published/draft status, retired-route restoration and revision history.
- Review added, changed and removed routes before publication; bind the UI review to an atomic frozen server snapshot, retain exact-request replay and block overlapping publications.
- Show publication progress and distinguish confirmed activation from uncertain outcomes.
- Reissue existing Let's Encrypt staging lineages when production is requested, and reject untrusted public-authority production chains before selecting them.
- Report known Nginx pre-activation validation rejection as failed, preserving traffic and allowing a corrected draft without an uncertainty hold. Genuine interrupted/unknown outcomes still require inspection.
- Return a clear forbidden response for expired/cross-origin CSRF forms.

# 5.0.1

- Rename the public repository to `every-lemon/kagnode-pm` and current product presentation to KagNode. PM, retaining installed service/data compatibility identifiers.
- Use canonical Core 5.0.10 login, sidebar and account templates; add permission-filtered quick search and real draft/activity overview data.
- Discover existing proxy configuration read-only, report unsupported inheritance/security settings and revalidate selected imports before creating drafts.
- Add explicit engine capability/configuration previews without claiming unqualified native activation.
- Separate ACME authority selection from validation, and add encrypted queued PEM uploads with explicit trust, hostname checks and reviewed replacement activation.
- Publish the typed native setup field contract and normalize its CLI health response.

# Changelog

## Unreleased — target 5.0.0

New independent Rust implementation. Development and qualification are in progress; no stable release or live migration is represented by this entry.

### Native migration verification

- Preserve the existing TLS management listener and imported ACME certificate lineages during reviewed migration.
- Correct the KagNode OAuth installation origin and preserve recovery holds when no queued job can run.
- Add fresh-node inspection and audited recovery acknowledgements without replaying uncertain operations.
- Resolve merged-/usr package ownership and batch service inspection for smaller systems.
- Execute removal-only APT transactions without an unnecessary archive-download phase.
- Maintain the combined installation’s local fleet credentials before expiry.
