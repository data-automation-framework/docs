> [!NOTE]
> This project is currently in an alpha state and should be considered unstable. Breaking changes will occur. This website is a work in progress, and any API or product descriptions are subject to change.
# Build system
The MSBuild project system is installed to: %localappdata%\CustomProjectSystems\Daf.Core

# Build system configuration priority order
When the build system is loading configuration settings, the following precedence order is used:

workspace (vscode) → user (vscode) → .dafproj (msbuild) → .dafproj.user (msbuild) → .props (msbuild)