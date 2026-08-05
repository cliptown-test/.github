# cliptown-test

Independent acceptance organization for **cliptown**.

Clipboard fidelity, SDK/API, UI, extension, sync, device coverage, and Memebank interoperability.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `mobile-clipboard-emulators` | mobile/emulator | `ready` | `matrix` |
| `desktop-clipboard-e2e` | desktop E2E | `ready` | `matrix` |
| `web-clipboard-api` | browser E2E | `ready` | `matrix` |
| `memebank-image-interop` | interoperability | `ready` | `matrix` |
| `rich-content-fidelity` | interoperability | `ready` | `matrix` |
| `cross-device-sync-conflicts` | synchronization | `ready` | `matrix` |
| `clients-api-contract` | SDK consumer | `ready` | `matrix` |
| `ui-accessibility-visual` | UI/accessibility | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: cliptown-test-project](https://github.com/orgs/cliptown-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcomcliptown-test-8157daa8a324)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->
