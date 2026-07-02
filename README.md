# IntelliJ Keybindings (Pure Config)

This is a pure-configuration Visual Studio Code extension that provides IntelliJ IDEA keybindings.

## Why this extension?

Unlike other IntelliJ keybinding extensions, this one is **100% declarative**. It contains no executable code, no activation scripts, and zero telemetry. It is completely safe and incapable of phoning home. It only uses the standard `contributes.keybindings` capability built into VS Code.

## Supported Platforms

Currently optimized for **Windows and Linux**. YMMV on MAC.

## How to Use

Because this is a pure configuration extension, you have two options for using these keybindings:

### Option 1: Install the Extension (Recommended)
1. Download a packaged `.vsix` file or install it from the extension marketplace.
2. In VS Code, go to the Extensions view (`Ctrl+Shift+X`).
3. Click the `...` menu in the top right and select **Install from VSIX...**
4. Select the downloaded extension.

### Option 2: Copy Keybindings Manually
If you don't even want the extension wrapper, you can copy the raw JSON bindings directly into your user settings:
1. Open the [package.json](package.json) file in this repository.
2. Copy the contents of the `contributes.keybindings` array.
3. In VS Code, press `Ctrl+Shift+P` (or `F1`) and run **Preferences: Open Keyboard Shortcuts (JSON)**.
4. Paste the array inside that file.

## Alternatives

If you want more functionality such as macOS support, chained chords, and platform-specific overrides, and don't mind executable code running, use [kasecato/vscode-intellij-idea-keybindings](https://github.com/kasecato/vscode-intellij-idea-keybindings) instead.

## License

MIT

