# Visual Studio Code (VS Code) Settings

![GitHub repo size](https://img.shields.io/github/repo-size/leugimkm/vscode-settings)

## Profiles

> [!TIP]
> Profiles allow you customize your development environment for different projects or tasks.
> For more details, visit this [link]("https://code.visualstudio.com/docs/editor/profiles").

- Base Python:
  - [settings.json](profiles/base_python/settings.json), [extensions.json](profiles/base_python/extensions.json),
    [snippets/python.json](profiles/base_python/snippets/python.json)
- Base Writer:
  - [settings.json](profiles/base_writer/settings.json), [extensions.json](profiles/base_writer/extensions.json)

> [!IMPORTANT]
> Keybindings to all profiles: [keybindings.json](/keybindings.json)

> [!NOTE]
>
> - Editor: [SauceCodePro NFM](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/SourceCodePro.zip)
> - Terminal: [CaskaydiaCove NFM](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/CascadiaCode.zip)
> - Extensions across all profiles.
>   - [VSCodeVim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim):
>     Vim emulator.
>   - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode):
>     An opinionated code formatter.
>   - [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols):
>     A simple file icon theme.

## Keybindings Overview

| Command                     | Key                    | Command id                                    |
|----------------------------:|:----------------------:|-----------------------------------------------|
| Go to Implementation        | `ctrl+space ctrl+i`    | `editor.action.goToImplementation`            |
| Show All Editors            | `ctrl+space ctrl+p`    | `workbench.action.showAllEditors`             |
| Execute Python Code         | `ctrl+alt+j`           | `python.execInTerminal`                       |
| Close Active Editor         | `ctrl+alt+j`           | `workbench.action.closeActiveEditor`          |
| Toggle Sidebar Visibility   | `ctrl+space ctrl+space`| `workbench.action.toggleActivityBarVisibility`|
| Toggle Statusbar Visibility | `ctrl+space ctrl+s`    | `workbench.action.toggleStatusbarVisibility`  |
| Quick Open Select Previous  | `ctrl+shift+k`         | `workbench.action.quickOpenSelectPrevious`    |
| Quick Open Select Next      | `ctrl+shift+j`         | `workbench.action.quickOpenSelectNext`        |
| Navigate Left               | `ctrl+h`               | `workbench.action.navigateLeft`               |
| Navigate Right              | `ctrl+l`               | `workbench.action.navigateRight`              |
| Navigate Up                 | `ctrl+k`               | `workbench.action.navigateUp`                 |
| Navigate Down               | `ctrl+j`               | `workbench.action.navigateDown`               |
| Toggle Sidebar Visibility   | `space e`              | `workbench.action.toggleSidebarVisibility`    |
| Previous Editor in Group    | `ctrl+shift+h`         | `workbench.action.previousEditorInGroup`      |
| Next Editor in Group        | `ctrl+shift+l`         | `workbench.action.nextEditorInGroup`          |
| Move Line Down              | `alt+j`                | `editor.action.moveLinesDownAction`           |
| Move Line Up                | `alt+k`                | `editor.action.moveLinesUpAction`             |
| Show Definition Hover       | `shift+k`              | `editor.action.showDefinitionPreviewHover`    |
| Scroll Left Hover           | `h`                    | `editor.action.scrollLeftHover`               |
| Scroll Right Hover          | `l`                    | `editor.action.scrollRightHover`              |
| Scroll Up Hover             | `k`                    | `editor.action.scrollUpHover`                 |
| Scroll Down Hover           | `j`                    | `editor.action.scrollDownHover`               |
| Close Active Editor         | `space d`              | `workbench.action.closeActiveEditor`          |
| Rename File                 | `r`                    | `renameFile`                                  |
| Copy File                   | `c`                    | `filesExplorer.copy`                          |
| Paste File                  | `p`                    | `filesExplorer.paste`                         |
| Cut File                    | `x`                    | `filesExplorer.cut`                           |
| Delete File                 | `d`                    | `deleteFile`                                  |
| New File                    | `a`                    | `explorer.newFile`                            |
| New Folder                  | `f`                    | `explorer.newFolder`                          |
| Open to Side                | `s`                    | `explorer.openToSide`                         |
| Split and Run Commands      | `shift+s`              | `runCommands`                                 |
| Open and Pass Focus         | `enter`                | `explorer.openAndPassFocus`                   |
