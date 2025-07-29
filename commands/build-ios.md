# Build and Fix errors

Build the <app-name> iOS app and automatically fix any build errors that occur.

## Instructions

1. Build the app using the appropriate Xcode MCP tools for iOS simulator
2. If build fails, attempt to fix common build errors automatically
3. Retry the build after applying fixes
4. Provide clear feedback on build status and any issues encountered

## Process

- Use `mcp__XcodeBuildMCP__build_sim_name_proj` to build for iOS simulator
- If build fails, attempt these fixes:
  - Clean derived data and build artifacts
  - Reset Swift Package Manager cache if applicable
  - Resolve package dependencies
  - Clean and rebuild the project
- Retry the build after applying fixes
- Report success or failure with appropriate next steps

## Build Configuration

- **Project**: 
- **Scheme**: 
- **Target**: iOS Simulator (iPhone 16)
- **Configuration**: 

Please proceed with building the app and fixing any errors that occur.