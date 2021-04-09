> [!NOTE]
> This project is currently in an alpha state and should be considered unstable. Breaking changes will occur. This website is a work in progress, and any API or product descriptions are subject to change.
# Build system configuration priority order
There are a few ways to override the default build configuration properties. When a property has been defined in multiple places, the below priority order is used:

Workspace (vscode) → user (vscode) → .daf (msbuild) → .daf.user (msbuild) → .props (msbuild)