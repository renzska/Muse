# Sequoia Branch Note

The changes for macOS Sequoia compatibility have been implemented and are available in the `sequoia` branch.

## Changes Made:

1. **Deployment Target**: Updated from macOS 10.12 to macOS 12.0
2. **@available Annotations**: Updated from `OSX 10.12.2` to `macOS 12.0` 
3. **Swift Version**: Updated from Swift 3.0 to Swift 5.0
4. **App Version**: Updated from 2.0 to 2.1 
5. **README**: Added Sequoia compatibility note
6. **Comments**: Updated version references in code comments

All changes maintain backward compatibility while ensuring the app works with macOS Sequoia (macOS 15.x).

To use the Sequoia-compatible version, check out the `sequoia` branch:
```bash
git checkout sequoia
```