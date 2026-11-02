# Source SBOM

**Initial source snapshot, not a release report.** Source commit `8fb433d6cd6a71940f51b5724663ec0c75bf0b62` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/ggmorse `8fb433d6cd6a71940f51b5724663ec0c75bf0b62`

- sbom:role: source-root
- sbom:git-commit: 8fb433d6cd6a71940f51b5724663ec0c75bf0b62
- sbom:git-tree: 67cfffd000c523627de2ea37e2f8a0f23aff0360
- sbom:source-repository: https://github.com/wave-owl/ggmorse
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "1f0a52b2ca90c54bf0a55915fbe6ab412a9c514b8ec2be71ca272be812d7d838"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/ggmorse | 8fb433d6cd6a71940f51b5724663ec0c75bf0b62 | source-root | unresolved; manual review required |
| Git | unresolved | conditional-build-requirement | unresolved |
| Threads | unresolved | conditional-build-requirement | unresolved |
| Threads | unresolved | conditional-build-requirement | unresolved |
| SDL2 | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| OpenGL | unresolved | conditional-build-requirement | unresolved |
| ocornut/imgui | 3f26a07ee1813cecaa87253436149e28fc11dc4e | gitlink | unresolved; manual review required |
| Conditional source requirements declared by CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/ggmorse-from-file/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/ggmorse-gui/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/ggmorse-to-file/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/malloc-count/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/third-party/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by examples/third-party/imgui/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by src/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by tests/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Threads | unresolved | conditional-build-runtime-requirement | unresolved |
| Optional example SDL2/OpenGL | unresolved | conditional-build-runtime-requirement | unresolved |
| actions/checkout | v1 | Syft source/package discovery | unresolved |
| tracked-source/.github/workflows/build.yml | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
