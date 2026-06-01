# PackSmith 0.1.0

Initial release.

## Added

- Unity Editor window at `Tools > PackSmith`.
- Read-only asset-pack scan flow for prefabs, materials, textures, scenes, animations, audio, shaders, docs, and common package hygiene issues.
- Buyer verdict for imported packs: what blocks use, what may break visuals, what needs review, and what can be safely fixed.
- Review queue with repeated finding summaries, ignore-this-scan controls, finding navigation, asset ping, path copy, and finding-level reporting.
- Publisher QA Preflight for documentation, dependencies, compatibility disclosure, demo/sample signals, package hygiene, third-party notice risk, and store-readiness issues.
- Fix Plan export before safe fixes.
- Safe Fix confirmation for deterministic reversible issues.
- Rollback transactions outside `Assets`.
- Fix Proof export after safe fixes.
- Scan report and publisher QA exports.
- Support bundle generation.
- In-app bug and suggestion reporting with support-bundle fallback.
- Automatic update manifest check through xyflowinnovations.com.

## Known Limitations

- Unsafe fixes are not applied automatically.
- Publisher QA Preflight is a readiness helper, not Unity certification or guaranteed approval.
- No destructive unused-asset deletion in v1.
- Animation retargeting and frame-level animation quality analysis are not part of v1.
- Unreal, Godot, and non-Unity adapters are future expansion targets.
