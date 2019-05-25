# Ansible Visual Studio Code

An ansible role that installs [Visual Studio Code](https://code.visualstudio.com/).

List extensions with `code --list-extensions`.

## Configuration

Variable                  | Description                                                                                      | Default value
:---                      | :---                                                                                             | :---
`vscode_extensions`       | List of extensions to install.                                                                   | `[]`
`vscode_extensions_file`  | File from which to read the extensions to install (one by line) if `vscode_extensions` is empty. |
`vscode_homebrew_user`    | Homebrew user to install Visual Studio Code with.                                                | The value of the `homebrew_user` or `user` variable.
`vscode_macos_key_repeat` | Whether to enable key repeat on macOS.                                                           | `true` (will apply configuration only on macOS).
