# my_vsc_extensions
My regular used extensions
## Export your extensions to a shell file:
`code --list-extensions | sed -e 's/^/code --install-extension /' > my_vscode_extensions.sh`
## Install your extensions
`bash my_vscode_extensions.sh`
