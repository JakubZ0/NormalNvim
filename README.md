wget -q https://raw.githubusercontent.com/NormalNvim/installer/main/installer.sh && chmod +x installer.sh && ./installer.sh

arch deps:
paru -S --needed "luarocks" "python" "yazi" "fd" "git-delta" "grcov" "rustup" "yarn" "python-pytest" "gcc" "binutils" "dotnet-runtime" "dotnet-sdk" "aspnet-runtime" "mono" "jdk-openjdk" "dart" "kotlin" "elixir" "npm" "nodejs" "typescript" "make" "go" "nasm" "r" "nuitka" "python" "ruby" "perl" "lua" "pyinstaller" "swift-bin" "gcc-fortran" "fortran-fpm-bin" "doxygen" "ldoc" "ruby-yard"; yarn global add "jest" "jsdoc" "typedoc"; cargo install "cargo-nextest"; go install "golang.org/x/tools/cmd/godoc@latest"

Mason:
:MasonInstall ansible-language-server angular-language-server asm-lsp asmfmt bash-debug-adapter bash-language-server checkmake codelldb clangd cmakelint csharpier cucumber-language-server debugpy delve docker-compose-language-service dockerfile-language-server elixir-ls eslint-lsp fantomas findent firefox-debug-adapter fortls fsautocomplete golangci-lint golangci-lint-langserver gopls google-java-format helm-ls html-lsp java-test json-lsp jq jsonlint kotlin-debug-adapter kotlin-language-server ktlint lua-language-server marksman matlab-language-server neocmakelsp netcoredbg omnisharp perlnavigator php-debug-adapter phpactor php-cs-fixer phpstan rubocop pyright autopep8 rust-analyzer selene shellcheck shfmt svelte-language-server stylua taplo typescript-language-server yaml-language-server yamllint yamlfmt zls

Treesitter:
:TSInstall all


I know it's overkill but performance is still great
