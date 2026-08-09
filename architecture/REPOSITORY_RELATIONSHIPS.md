# `cliptown-test` repository relationships

Generated from reviewed policy and the current **public** repository inventory.

- Public repositories declared: **14**
- Private repository names withheld: **7**
- Relationship edges: **20**

## Repository roles

| Repository | Role | Lifecycle |
|---|---|---|
| [`.github`](https://github.com/cliptown-test/.github) | `organization_governance` | `active` |
| [`api-contract-e2e`](https://github.com/cliptown-test/api-contract-e2e) | `interfaces` | `active` |
| [`cli-contract-e2e`](https://github.com/cliptown-test/cli-contract-e2e) | `interfaces` | `active` |
| [`clients-dart-consumer`](https://github.com/cliptown-test/clients-dart-consumer) | `client_sdk` | `active` |
| [`clients-rust-consumer`](https://github.com/cliptown-test/clients-rust-consumer) | `client_sdk` | `active` |
| [`clients-typescript-consumer`](https://github.com/cliptown-test/clients-typescript-consumer) | `client_sdk` | `active` |
| [`android-clipboard-emulator-e2e`](https://github.com/cliptown-test/android-clipboard-emulator-e2e) | `end_to_end_tests` | `active` |
| [`clipboard-security-e2e`](https://github.com/cliptown-test/clipboard-security-e2e) | `end_to_end_tests` | `active` |
| [`desktop-clipboard-e2e`](https://github.com/cliptown-test/desktop-clipboard-e2e) | `end_to_end_tests` | `active` |
| [`ios-clipboard-simulator-e2e`](https://github.com/cliptown-test/ios-clipboard-simulator-e2e) | `end_to_end_tests` | `active` |
| [`memebank-image-interop-e2e`](https://github.com/cliptown-test/memebank-image-interop-e2e) | `end_to_end_tests` | `active` |
| [`offline-sync-e2e`](https://github.com/cliptown-test/offline-sync-e2e) | `end_to_end_tests` | `active` |
| [`ui-device-matrix-e2e`](https://github.com/cliptown-test/ui-device-matrix-e2e) | `end_to_end_tests` | `active` |
| [`web-extension-clipboard-e2e`](https://github.com/cliptown-test/web-extension-clipboard-e2e) | `end_to_end_tests` | `active` |

## Declared edges

| From | Relationship | To | Status/basis |
|---|---|---|---|
| `cliptown-test/.github` | `governs` | `cliptown-test/android-clipboard-emulator-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/api-contract-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/cli-contract-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/clients-dart-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/clients-rust-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/clients-typescript-consumer` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/clipboard-security-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/desktop-clipboard-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/ios-clipboard-simulator-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/memebank-image-interop-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/offline-sync-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/ui-device-matrix-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/.github` | `governs` | `cliptown-test/web-extension-clipboard-e2e` | `inferred` / `role-convention`: organization defaults, safety, and relationship declarations |
| `cliptown-test/clients-dart-consumer` | `generated_from` | `cliptown-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `cliptown-test/clients-dart-consumer` | `generated_from` | `cliptown-test/cli-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `cliptown-test/clients-rust-consumer` | `generated_from` | `cliptown-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `cliptown-test/clients-rust-consumer` | `generated_from` | `cliptown-test/cli-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `cliptown-test/clients-typescript-consumer` | `generated_from` | `cliptown-test/api-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `cliptown-test/clients-typescript-consumer` | `generated_from` | `cliptown-test/cli-contract-e2e` | `inferred` / `role-convention`: SDK bindings derive from canonical contracts |
| `organization://cliptown-test` | `packaged_via` | `platform://zed-pkg` | `platform-default` / `platform-policy`: Zed resolves artifacts while submodules compose editable source |

## Composition, service, and observability contract

Git submodules compose editable source; Zed packages resolve packages/artifacts; dual-managed commits must match. Production deploys immutable image digests, not runtime source builds. Cross-service access uses APIs/SDKs/events rather than another service database. MCP uses the product API/SDK. Services emit OpenTelemetry traces, bounded metrics, and correlated structured logs.

## Privacy boundary

This public registry deliberately omits private repository names and edges; the count above makes the boundary explicit.
