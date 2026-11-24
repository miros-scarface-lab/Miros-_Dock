# Miros Dock

Miros Dock will contain two separate applications:

- **Android** — the mobile application in [`android/`](android/)
- **Windows** — the desktop application in [`windows/`](windows/)

Shared assets, API notes, or platform-independent documentation can go in [`shared/`](shared/).

## Repository layout

```text
android/     Android application and its platform-specific documentation
windows/     Windows application and its platform-specific documentation
shared/      Resources and documentation shared between applications
```

## Getting started

The platform directories are prepared for the application projects. Add each app's source code and build configuration to its corresponding directory. Once the frameworks and tools are chosen, update that platform's README with exact setup, build, and test commands.

Keep platform-specific code in its own directory. Put only genuinely shared resources or documentation in `shared/`.
