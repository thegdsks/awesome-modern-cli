<div align="center">

# Awesome Modern CLI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/thegdsks/awesome-modern-cli?style=for-the-badge&color=yellow)](https://github.com/thegdsks/awesome-modern-cli/stargazers)
[![Tools](https://img.shields.io/badge/tools-285+-green?style=for-the-badge)](#contents)
[![License](https://img.shields.io/badge/license-CC0-blue?style=for-the-badge)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/thegdsks/awesome-modern-cli?style=for-the-badge)](https://github.com/thegdsks/awesome-modern-cli/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/thegdsks/awesome-modern-cli/pulls)

A curated list of modern alternatives to classic command-line tools.

Faster, prettier, smarter replacements for the Unix utilities you use every day.

[What is this?](about.md) · [Contribution guide](CONTRIBUTING.md) · [Code of conduct](code-of-conduct.md)

</div>

---

## Contents

- [File Listing](#file-listing)
- [File Search](#file-search)
- [File Management](#file-management)
- [Text Search](#text-search)
- [Text Processing](#text-processing)
- [Text Viewing](#text-viewing)
- [Text Editors](#text-editors)
- [JSON / YAML / CSV](#json--yaml--csv)
- [Shell & Prompt](#shell--prompt)
- [Shell History](#shell-history)
- [Navigation](#navigation)
- [Fuzzy Finding](#fuzzy-finding)
- [Version Control](#version-control)
- [Diff Tools](#diff-tools)
- [System Monitoring](#system-monitoring)
- [Process Management](#process-management)
- [Disk Usage](#disk-usage)
- [Network Tools](#network-tools)
- [HTTP Clients](#http-clients)
- [API Testing](#api-testing)
- [DNS Tools](#dns-tools)
- [Benchmarking](#benchmarking)
- [Compression](#compression)
- [File Transfer](#file-transfer)
- [Terminal Emulators](#terminal-emulators)
- [Terminal Multiplexers](#terminal-multiplexers)
- [Task Runners](#task-runners)
- [Version Managers](#version-managers)
- [JS / TS Toolchain](#js--ts-toolchain)
- [Static Site Generators](#static-site-generators)
- [Container Tools](#container-tools)
- [Kubernetes](#kubernetes)
- [Database Clients](#database-clients)
- [Security Tools](#security-tools)
- [Calculator](#calculator)
- [Documentation](#documentation)
- [Presentation](#presentation)
- [Media](#media)
- [Messaging](#messaging)
- [Productivity](#productivity)
- [Code Counting](#code-counting)
- [Spelling & Linting](#spelling--linting)
- [Tunneling](#tunneling)
- [Web](#web)
- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
- [Star History](#star-history)

---

### Highlights

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/sharkdp/bat"><b>bat</b></a><br>
      <sub>cat with syntax highlighting</sub><br><br>
      <a href="https://github.com/sharkdp/bat"><img src="https://imgur.com/rGsdnDe.png" width="400" /></a>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/aristocratos/btop"><b>btop</b></a><br>
      <sub>beautiful system monitor</sub><br><br>
      <a href="https://github.com/aristocratos/btop"><img src="https://raw.githubusercontent.com/aristocratos/btop/main/Img/normal.png" width="400" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/jesseduffield/lazygit"><b>lazygit</b></a><br>
      <sub>terminal UI for git</sub><br><br>
      <a href="https://github.com/jesseduffield/lazygit"><img src="https://raw.githubusercontent.com/jesseduffield/lazygit/assets/staging.gif" width="400" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/dandavison/delta"><b>delta</b></a><br>
      <sub>syntax-aware diff viewer</sub><br><br>
      <a href="https://github.com/dandavison/delta"><img src="https://user-images.githubusercontent.com/52205/86275526-76792100-bba1-11ea-9e78-6be9baa80b29.png" width="400" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/starship/starship"><b>starship</b></a><br>
      <sub>customizable shell prompt</sub><br><br>
      <a href="https://github.com/starship/starship"><img src="https://raw.githubusercontent.com/starship/starship/master/media/demo.gif" width="400" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/junegunn/fzf"><b>fzf</b></a><br>
      <sub>fuzzy finder for everything</sub><br><br>
      <a href="https://github.com/junegunn/fzf"><img src="https://raw.githubusercontent.com/junegunn/i/master/fzf-preview.png" width="400" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/orf/gping"><b>gping</b></a><br>
      <sub>ping with a graph</sub><br><br>
      <a href="https://github.com/orf/gping"><img src="https://raw.githubusercontent.com/orf/gping/master/images/readme-example.gif" width="400" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/jesseduffield/lazydocker"><b>lazydocker</b></a><br>
      <sub>terminal UI for Docker</sub><br><br>
      <a href="https://github.com/jesseduffield/lazydocker"><img src="https://user-images.githubusercontent.com/8456633/59972109-8e9c8480-95cc-11e9-8350-38f7f86ba76d.png" width="400" /></a>
    </td>
  </tr>
</table>

<details>
<summary><b>More highlights</b> (eza, ripgrep, zoxide, hyperfine)</summary>
<br>
<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/eza-community/eza"><b>eza</b></a><br>
      <sub>modern ls replacement</sub><br><br>
      <a href="https://github.com/eza-community/eza"><img src="https://raw.githubusercontent.com/eza-community/eza/main/docs/images/screenshots.png" width="400" /></a>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/BurntSushi/ripgrep"><b>ripgrep</b></a><br>
      <sub>extremely fast grep</sub><br><br>
      <a href="https://github.com/BurntSushi/ripgrep"><img src="https://user-images.githubusercontent.com/200613/90223748-ecaeab80-de0e-11ea-9140-ac9219f5747c.gif" width="400" /></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/ajeetdsouza/zoxide"><b>zoxide</b></a><br>
      <sub>smarter cd</sub><br><br>
      <a href="https://github.com/ajeetdsouza/zoxide"><img src="https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/contrib/tutorial.webp" width="400" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/sharkdp/hyperfine"><b>hyperfine</b></a><br>
      <sub>command benchmarking</sub><br><br>
      <a href="https://github.com/sharkdp/hyperfine"><img src="https://i.imgur.com/z19OYxE.gif" width="400" /></a>
    </td>
  </tr>
</table>
</details>

---

## File Listing

> Replacements for `ls` and `tree`.

- [broot](https://github.com/Canop/broot) - A new way to see and navigate directory trees with fuzzy search.
- [eza](https://github.com/eza-community/eza) - A modern, maintained replacement for ls with colors, icons, and Git integration.
- [lla](https://github.com/chaqchase/lla) - A fast ls alternative with a plugin system for extended functionality.
- [lsd](https://github.com/lsd-rs/lsd) - The next gen ls command with pretty colors and file icons.
- [pls](https://github.com/pls-rs/pls) - The ls command for the pros, with developer-friendly features and Nerd Font icons.
- [tre](https://github.com/dduan/tre) - A tree command improved with Git awareness and editor integration.

## File Search

> Replacements for `find`.

- [fd](https://github.com/sharkdp/fd) - A simple, fast, and user-friendly alternative to find.
- [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.

## File Management

> Replacements for `ranger`, `rm`, `cp`, and file managers.

- [clifm](https://github.com/leo-arch/clifm) - A command-line file manager that lives in the shell.
- [f2](https://github.com/ayoisaiah/f2) - Cross-platform tool for fast, safe, and flexible batch renaming.
- [fclones](https://github.com/pkolaczk/fclones) - Efficient duplicate file finder and remover.
- [fuc](https://github.com/supercilex/fuc) - Fast cp and rm commands for modern hardware.
- [joshuto](https://github.com/kamiyaa/joshuto) - Ranger-like terminal file manager with vi keybindings.
- [kondo](https://github.com/tbillington/kondo) - Find and delete software project build artifacts to reclaim disk space.
- [lf](https://github.com/gokcehan/lf) - Fast, extensively customizable terminal file manager.
- [nnn](https://github.com/jarun/nnn) - The unorthodox terminal file manager, tiny and blazing fast.
- [nomino](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort, and map.
- [rip](https://github.com/nivekuil/rip) - A safe and ergonomic alternative to rm with a graveyard for recovery.
- [superfile](https://github.com/yorukot/superfile) - Pretty and modern terminal file manager.
- [xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer.
- [yazi](https://github.com/sxyazi/yazi) - Blazing fast terminal file manager with async I/O and image preview.

## Text Search

> Replacements for `grep` and `ag`.

- [ast-grep](https://github.com/ast-grep/ast-grep) - Structural code search, lint, and rewriting using AST patterns.
- [rare](https://github.com/zix99/rare) - Real-time regex-powered aggregation and analytics on the command-line.
- [ripgrep](https://github.com/BurntSushi/ripgrep) - An extremely fast alternative to grep that respects gitignore.
- [ripgrep-all](https://github.com/phiresky/ripgrep-all) - Ripgrep, but also searches PDFs, e-books, Office documents, zip, and archives.
- [sig](https://github.com/ynqa/sig) - Interactive grep for streaming data.
- [srgn](https://github.com/alexpovel/srgn) - A grep-like tool that understands source code syntax.

## Text Processing

> Replacements for `sed`, `awk`, `cut`, and `uniq`.

- [choose](https://github.com/theryangeary/choose) - A human-friendly and fast alternative to cut and awk.
- [grex](https://github.com/pemistahl/grex) - Generate regular expressions from user-provided test cases.
- [hck](https://github.com/sstadick/hck) - A faster and more featureful drop-in replacement for cut.
- [rargs](https://github.com/lotabout/rargs) - Xargs + awk with pattern matching support.
- [runiq](https://github.com/whitfin/runiq) - Efficient way to filter duplicate lines from unsorted input.
- [ruplacer](https://github.com/your-tools/ruplacer) - Find and replace text across multiple source files.
- [scooter](https://github.com/thomasschafer/scooter) - Interactive find and replace in the terminal.
- [sd](https://github.com/chmln/sd) - An intuitive find-and-replace CLI, a simpler sed alternative.

## Text Viewing

> Replacements for `cat`, `less`, and `hexdump`.

- [bat](https://github.com/sharkdp/bat) - A cat clone with syntax highlighting and Git integration.
- [fblog](https://github.com/brocode/fblog) - Small command-line JSON log viewer with smart formatting.
- [glow](https://github.com/charmbracelet/glow) - Render markdown beautifully in the terminal.
- [hexyl](https://github.com/sharkdp/hexyl) - A command-line hex viewer with colored output.
- [lnav](https://lnav.org/) - An advanced log file viewer with automatic format detection.
- [mdcat](https://github.com/swsnr/mdcat) - Render Markdown in the terminal with syntax highlighting, links, and inline images.
- [ov](https://github.com/noborus/ov) - A feature-rich terminal pager. Replaces less.
- [tailspin](https://github.com/bensadeh/tailspin) - A log file highlighter that works out of the box.

## Text Editors

> Modern terminal-based editors.

- [amp](https://github.com/jmacdonald/amp) - A complete text editor for your terminal inspired by Vi/Vim.
- [edit](https://github.com/microsoft/edit) - A simple terminal text editor from Microsoft, paying homage to MS-DOS Editor.
- [fresh](https://github.com/sinelaw/fresh) - A TUI code editor with IDE features like LSP, Git integration, and file tree.
- [helix](https://github.com/helix-editor/helix) - A post-modern modal text editor with built-in LSP and tree-sitter.
- [kakoune](https://github.com/mawww/kakoune) - Modal editor with multi-selection first design.
- [Lapce](https://github.com/lapce/lapce) - A lightning-fast and powerful code editor with native GUI.
- [micro](https://github.com/micro-editor/micro) - A modern and intuitive terminal-based text editor, replaces nano.
- [Neovim](https://github.com/neovim/neovim) - Vim-fork focused on extensibility and usability with Lua plugin system.
- [ox](https://github.com/curlpipe/ox) - An independent terminal text editor, simple and practical.
- [zed](https://github.com/zed-industries/zed) - A high-performance multiplayer code editor from the creators of Atom.

## JSON / YAML / CSV

> Replacements for `jq`, data viewers, and structured data tools.

- [csvlens](https://github.com/YS-L/csvlens) - A TUI CSV file viewer, like less but made for tabular data.
- [dasel](https://github.com/tomwright/dasel) - Query and modify JSON, YAML, TOML, and XML from the command line.
- [dyff](https://github.com/homeport/dyff) - A diff tool for YAML files with semantic awareness.
- [fx](https://github.com/antonmedv/fx) - Terminal JSON viewer and processor with interactive mode.
- [gron](https://github.com/tomnomnom/gron) - Make JSON greppable by flattening it to discrete assignments.
- [jaq](https://github.com/01mf02/jaq) - A jq clone focused on correctness, speed, and simplicity; a near drop-in replacement for `jq` for most queries.
- [jless](https://github.com/PaulJuliusMartinez/jless) - A command-line JSON viewer with vim-like navigation.
- [jnv](https://github.com/ynqa/jnv) - Interactive JSON filter using jq expressions with live preview.
- [jq](https://github.com/jqlang/jq) - The original lightweight command-line JSON processor.
- [jsongrep](https://github.com/micahkepe/jsongrep) - Fast search tool for JSON, YAML, and TOML with path query syntax.
- [qsv](https://github.com/dathere/qsv) - A high-performance CSV toolkit, xsv fork with 34+ extra commands.
- [sc-im](https://github.com/andmarti1424/sc-im) - A vim-like spreadsheet calculator for the terminal.
- [Tabiew](https://github.com/shshemi/tabiew) - Lightweight TUI to view and query CSV, TSV, and Parquet files.
- [visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data.
- [xq](https://github.com/sibprogrammer/xq) - XML and HTML beautifier and content extractor.
- [xsv](https://github.com/BurntSushi/xsv) - A fast CSV command line toolkit for slicing, indexing, and searching.
- [yq](https://github.com/kislyuk/yq) - Jq wrapper for YAML, XML, and TOML documents.

## Shell & Prompt

> Modern shells and prompt customization.

- [elvish](https://github.com/elves/elvish) - An expressive shell with a real programming language built-in.
- [fish](https://github.com/fish-shell/fish-shell) - The user-friendly command-line shell with autosuggestions.
- [nushell](https://github.com/nushell/nushell) - A new type of shell with structured data pipelines.
- [oh-my-posh](https://ohmyposh.dev) - A prompt theme engine for any shell with extensive themes.
- [starship](https://github.com/starship/starship) - Minimal, blazing-fast, and infinitely customizable prompt for any shell.

## Shell History

> Replacements for `ctrl+r` history search.

- [atuin](https://github.com/atuinsh/atuin) - Magical shell history stored in a SQLite database with optional encrypted sync.
- [mcfly](https://github.com/cantino/mcfly) - Fly through shell history with intelligent context-aware search.

## Navigation

> Replacements for `cd` and directory jumping.

- [autojump](https://github.com/wting/autojump) - A cd command that learns from your navigation patterns.
- [tere](https://github.com/mgunyho/tere) - A faster alternative to cd + ls for navigating directories.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A smarter cd command that learns your habits.

## Fuzzy Finding

> Interactive filtering and selection tools.

- [fzf](https://github.com/junegunn/fzf) - A general-purpose command-line fuzzy finder.
- [skim](https://github.com/skim-rs/skim) - A general-purpose fuzzy finder in Rust, similar to fzf.
- [television](https://github.com/alexpasmantier/television) - A blazing fast general-purpose fuzzy finder TUI.

## Version Control

> Git TUIs and enhanced Git workflows.

- [gh-dash](https://github.com/dlvhdr/gh-dash) - A beautiful TUI dashboard for GitHub pull requests and issues.
- [git-cliff](https://github.com/orhun/git-cliff) - A highly customizable changelog generator following Conventional Commits.
- [git-extras](https://github.com/tj/git-extras) - Git utilities like repo summary, changelog, and commit percentages.
- [gita](https://github.com/nosarthur/gita) - Manage multiple Git repos side by side.
- [gitui](https://github.com/gitui-org/gitui) - Blazing fast terminal client for Git.
- [jj](https://github.com/jj-vcs/jj) - A Git-compatible VCS with simpler CLI, first-class conflicts, and auto-rebasing.
- [lazygit](https://github.com/jesseduffield/lazygit) - A simple terminal UI for Git commands.
- [livediff](https://github.com/SoCkEt7/Livediff) - Real-time terminal file diff monitoring TUI.
- [onefetch](https://github.com/o2sh/onefetch) - Command-line Git information tool showing repo stats.
- [sapling](https://github.com/facebook/sapling) - A scalable, user-friendly source control system from Meta.
- [serie](https://github.com/lusingander/serie) - A rich Git commit graph viewer for the terminal.
- [soft-serve](https://github.com/charmbracelet/soft-serve) - A tasty, self-hostable Git server for the command line.
- [tig](https://github.com/jonas/tig) - Text-mode interface for Git with browse and blame modes.

## Diff Tools

> Better alternatives to `diff`.

- [delta](https://github.com/dandavison/delta) - A syntax-highlighting pager for Git, diff, and grep output.
- [difftastic](https://github.com/Wilfred/difftastic) - A structural diff that understands syntax across 30+ languages.

## System Monitoring

> Replacements for `top`, `htop`, and system info tools.

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool showing per-process usage.
- [bottom](https://github.com/ClementTsang/bottom) - A cross-platform graphical process/system monitor.
- [btop](https://github.com/aristocratos/btop) - A resource monitor with beautiful TUI and extensive features.
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) - A fast system information tool, neofetch replacement.
- [glances](https://github.com/nicolargo/glances) - An eye on your system with a top/htop alternative and web mode.
- [gotop](https://github.com/xxxserxxx/gotop) - Terminal-based graphical activity monitor.
- [kmon](https://github.com/orhun/kmon) - Linux Kernel Manager and Activity Monitor.
- [macmon](https://github.com/vladkens/macmon) - Sudoless performance monitoring for Apple Silicon.
- [nvtop](https://github.com/Syllo/nvtop) - GPU process monitoring for AMD, Intel, and NVIDIA.
- [procs](https://github.com/dalance/procs) - A modern replacement for ps written in Rust.
- [systeroid](https://github.com/orhun/systeroid) - A more powerful alternative to sysctl with a terminal UI.
- [zenith](https://github.com/bvaisvil/zenith) - In-terminal graphical metrics with CPU, GPU, network, and disk charts.

## Process Management

> Replacements for `nohup`, `bg`, and `kill`.

- [mprocs](https://github.com/pvolok/mprocs) - Run multiple commands in parallel and view their output in a TUI.
- [pik](https://github.com/jacek-kurlit/pik) - TUI tool to find and kill processes interactively.
- [process-compose](https://github.com/F1bonacc1/process-compose) - A scheduler and orchestrator for non-containerized processes with TUI.
- [pueue](https://github.com/nukesor/pueue) - Manage long-running shell commands with a daemon and TUI.

## Disk Usage

> Replacements for `du` and `df`.

- [diskonaut](https://github.com/imsnif/diskonaut) - Terminal visual disk space navigator.
- [dua-cli](https://github.com/Byron/dua-cli) - Disk usage analyzer with interactive navigation.
- [duf](https://github.com/muesli/duf) - A better df alternative with color-coded output and filtering.
- [dust](https://github.com/bootandy/dust) - A more intuitive version of du with visual output.
- [gdu](https://github.com/dundee/gdu) - Fast disk usage analyzer with console interface.
- [ncdu](https://dev.yorhel.nl/ncdu) - A disk usage analyzer with an ncurses interface.

## Network Tools

> Tools for network diagnostics, scanning, traffic analysis, and file serving/transfer.

- [copyparty](https://github.com/9001/copyparty) - Portable file server with resumable uploads, dedup, WebDAV, SFTP, FTP, TFTP, and media indexing.
- [gping](https://github.com/orf/gping) - Ping, but with a graph.
- [miniserve](https://github.com/svenstaro/miniserve) - Serve files over HTTP from the terminal with a single command.
- [netscanner](https://github.com/Chleba/netscanner) - A TUI network scanner.
- [nibble](https://github.com/backendsystems/nibble) - A fast local network scanner with hardware vendor detection and service names.
- [sniffnet](https://github.com/GyulyVGC/sniffnet) - Monitor your network traffic easily with a cross-platform TUI.
- [termshark](https://github.com/gcla/termshark) - A terminal UI for tshark, inspired by Wireshark.
- [trippy](https://github.com/fujiapple852/trippy) - A network diagnostic tool combining ping and traceroute with rich TUI.

## HTTP Clients

> Replacements for `curl` and `wget`.

- [aria2](https://github.com/aria2/aria2) - Ultra-fast download utility supporting HTTP, FTP, BitTorrent, and Metalink.
- [curlie](https://github.com/rs/curlie) - The power of curl, the ease of use of httpie.
- [httpie](https://github.com/httpie/cli) - A modern, user-friendly command-line HTTP client for the API era.
- [xh](https://github.com/ducaale/xh) - A friendly and fast tool for sending HTTP requests, an HTTPie reimplementation.

## API Testing

> Replacements for Postman and API debugging tools.

- [ATAC](https://github.com/Julien-cpsn/ATAC) - A feature-full TUI API client, free, offline, and account-less.
- [HTTP Prompt](https://github.com/httpie/http-prompt) - An interactive HTTP client with autocomplete and syntax highlighting.
- [posting](https://github.com/darrenburns/posting) - A powerful HTTP client that lives in your terminal.

## DNS Tools

> Replacements for `dig` and `nslookup`.

- [doggo](https://github.com/mr-karan/doggo) - Command-line DNS client for humans with color-coded output.

## Benchmarking

> Replacements for `time` and load testing tools.

- [hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool with statistical analysis.
- [oha](https://github.com/hatoo/oha) - HTTP load generator with a real-time TUI.

## Compression

> Replacements for `tar`, `gzip`, and `unzip`.

- [ouch](https://github.com/ouch-org/ouch) - Painless compression and decompression, smart format detection.

## File Transfer

> Replacements for `scp` and `rsync`.

- [croc](https://github.com/schollz/croc) - Easily and securely send things from one computer to another.
- [portal](https://github.com/SpatiumPortae/portal) - Send files between computers through an encrypted peer-to-peer tunnel.
- [rclone](https://github.com/rclone/rclone) - Sync files with any cloud provider, an rsync for cloud storage.
- [termscp](https://github.com/veeso/termscp) - TUI file transfer and explorer with SCP, SFTP, FTP, and S3 support.

## Terminal Emulators

> Modern GPU-accelerated terminal emulators.

- [alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-enhanced terminal emulator focused on speed.
- [Ghostty](https://github.com/ghostty-org/ghostty) - Fast, feature-rich, cross-platform terminal emulator with native platform UI.
- [rio](https://github.com/raphamorim/rio) - A hardware-accelerated GPU terminal emulator powered by WebGPU.
- [Warp](https://github.com/warpdotdev/Warp) - AI-powered modern terminal with structured command history and IDE-like features.
- [wezterm](https://github.com/wezterm/wezterm) - A GPU-accelerated terminal emulator and multiplexer with Lua config.

## Terminal Multiplexers

> Replacements for `tmux` and `screen`.

- [tmux](https://github.com/tmux/tmux) - The classic terminal multiplexer with extensive plugin ecosystem.
- [zellij](https://github.com/zellij-org/zellij) - A terminal workspace with batteries included, a tmux alternative.

## Task Runners

> Replacements for `make` and build tools.

- [bacon](https://github.com/Canop/bacon) - Background code checker, designed for Rust but works for any language.
- [entr](https://github.com/eradman/entr) - Run arbitrary commands when files change.
- [just](https://github.com/casey/just) - A handy command runner for project-specific tasks, a modern make.
- [watchexec](https://github.com/watchexec/watchexec) - Execute commands in response to file modifications.

## Version Managers

> Replacements for `nvm`, `pyenv`, and `asdf`.

- [fnm](https://github.com/Schniz/fnm) - Fast Node Manager, a cross-platform nvm replacement.
- [mise](https://github.com/jdx/mise) - A polyglot tool version manager and task runner, asdf replacement.
- [volta](https://github.com/volta-cli/volta) - JavaScript toolchain manager that pins exact versions per project.

## JS / TS Toolchain

> Modern JavaScript and TypeScript build tools and runtimes.

- [Bun](https://github.com/oven-sh/bun) - All-in-one JavaScript runtime, bundler, test runner, and package manager.
- [Deno](https://github.com/denoland/deno) - A secure JavaScript/TypeScript runtime with built-in tooling.
- [oxc](https://github.com/oxc-project/oxc) - A high-performance collection of JS/TS tools, 50-100x faster than ESLint.
- [SWC](https://github.com/swc-project/swc) - A super-fast TypeScript/JavaScript compiler, replaces Babel.
- [Turborepo](https://github.com/vercel/turborepo) - High-performance build system for JavaScript/TypeScript monorepos.

## Static Site Generators

> Build static websites from templates and content.

- [hugo](https://github.com/gohugoio/hugo) - The world's fastest static site generator with multi-language support.
- [zola](https://github.com/getzola/zola) - A fast static site generator in a single binary with built-in Sass and syntax highlighting.

## Container Tools

> Docker TUIs and container management.

- [ctop](https://github.com/bcicen/ctop) - Top-like interface for container metrics.
- [dive](https://github.com/wagoodman/dive) - Tool for exploring each layer in a Docker image.
- [lazydocker](https://github.com/jesseduffield/lazydocker) - The lazier way to manage everything Docker.
- [nerdctl](https://github.com/containerd/nerdctl) - Docker-compatible CLI for containerd with Compose and rootless support.
- [oxker](https://github.com/mrjackwills/oxker) - A simple TUI to view and control Docker containers.

## Kubernetes

> kubectl alternatives and Kubernetes TUIs.

- [k9s](https://github.com/derailed/k9s) - TUI for managing Kubernetes clusters.
- [kdash](https://github.com/kdash-rs/kdash) - A simple and fast dashboard for Kubernetes.
- [kubestellar-console](https://github.com/kubestellar/console) - Multi-cluster Kubernetes dashboard with AI-powered operations and real-time observability.
- [lfk](https://github.com/janosmiko/lfk) - Yazi-inspired, vim-like keyboard focused Lightning Fast Kubernetes navigator.

## Database Clients

> Replacements for `psql`, `mysql`, and database GUIs.

- [harlequin](https://github.com/tconbeer/harlequin) - The SQL IDE for your terminal.
- [iredis](https://github.com/laixintao/iredis) - Redis client with autocompletion and syntax highlighting.
- [lazysql](https://github.com/jorgerojas26/lazysql) - A cross-platform TUI database management tool.
- [mycli](https://github.com/dbcli/mycli) - MySQL client with autocompletion and syntax highlighting.
- [pgcli](https://github.com/dbcli/pgcli) - PostgreSQL client with autocompletion and syntax highlighting.
- [rainfrog](https://github.com/achristmascarl/rainfrog) - Database management TUI for PostgreSQL, MySQL, and SQLite.
- [usql](https://github.com/xo/usql) - Universal command-line SQL client with autocompletion.

## Security Tools

> Password managers, encryption, and security utilities.

- [cotp](https://github.com/replydev/cotp) - Encrypted command-line TOTP/HOTP authenticator.
- [feroxbuster](https://github.com/epi052/feroxbuster) - A fast, simple, recursive content discovery tool.
- [flawz](https://github.com/orhun/flawz) - A terminal UI for browsing security vulnerabilities (CVEs).
- [gopass](https://github.com/gopasspw/gopass) - Fully-featured password manager compatible with pass.
- [gpg-tui](https://github.com/orhun/gpg-tui) - A terminal user interface for GnuPG.
- [rage](https://github.com/str4d/rage) - A simple, modern, and secure file encryption tool (age implementation).

## Calculator

> Replacements for `bc` and `calc`.

- [fend](https://github.com/printfn/fend) - Arbitrary-precision unit-aware calculator.
- [kalker](https://github.com/PaddiM8/kalker) - Scientific calculator with math-like syntax, complex numbers, and vectors.

## Documentation

> Man page alternatives and documentation tools.

- [cheat](https://github.com/cheat/cheat) - Create and view interactive cheatsheets on the command-line.
- [mdBook](https://github.com/rust-lang/mdBook) - Create books from Markdown, like GitBook but in Rust.
- [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line.
- [tealdeer](https://github.com/tealdeer-rs/tealdeer) - A very fast tldr client with offline caching.
- [tectonic](https://github.com/tectonic-typesetting/tectonic) - A self-contained TeX/LaTeX engine that downloads packages on demand.
- [thefuck](https://github.com/nvbn/thefuck) - Corrects your previous console command when you mistype.
- [tldr](https://github.com/tldr-pages/tldr) - Simplified man pages with practical examples.
- [Typst](https://github.com/typst/typst) - A modern markup-based typesetting system, a LaTeX alternative.

## Presentation

> Terminal-based presentation tools.

- [presenterm](https://github.com/mfontanini/presenterm) - A terminal slideshow tool that renders Markdown presentations.
- [slides](https://github.com/maaslalani/slides) - Terminal-based presentation tool using Markdown.

## Media

> Music players, image viewers, and media tools.

- [asciinema](https://github.com/asciinema/asciinema) - Record and share terminal sessions as lightweight text.
- [freeze](https://github.com/charmbracelet/freeze) - Generate images of code and terminal output.
- [kew](https://codeberg.org/ravachol/kew) - A terminal music player that plays anything from your library with a single command.
- [ncspot](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client.
- [oxipng](https://github.com/oxipng/oxipng) - Multithreaded lossless PNG optimizer.
- [pastel](https://github.com/sharkdp/pastel) - Generate, analyze, convert, and manipulate colors.
- [spotify-player](https://github.com/aome510/spotify-player) - A Spotify player in the terminal with full feature parity.
- [termusic](https://github.com/tramhao/termusic) - A terminal music player.
- [vhs](https://github.com/charmbracelet/vhs) - Write terminal GIFs as code for documentation and demos.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Download videos from YouTube and other sites, a youtube-dl fork.

## Messaging

> Terminal-based chat and email clients.

- [aerc](https://aerc-mail.org/) - A pretty good email client for the terminal.
- [gomuks](https://github.com/gomuks/gomuks) - A Matrix client for the terminal.
- [himalaya](https://github.com/pimalaya/himalaya) - CLI email client supporting IMAP, JMAP, and Maildir with scriptable interface.
- [iamb](https://iamb.chat) - A Matrix client for Vim addicts.
- [newsboat](https://github.com/newsboat/newsboat) - An RSS/Atom feed reader for the text console.

## Productivity

> Task managers, clipboard, calendars, and shell utilities.

- [calcure](https://github.com/anufrievroman/calcure) - Modern TUI calendar and task manager.
- [Clipboard](https://github.com/Slackadays/Clipboard) - Cut, copy, and paste anything from the terminal.
- [clipse](https://github.com/savedra1/clipse) - TUI clipboard manager.
- [envio](https://github.com/humblepenguinn/envio) - Modern environment variable manager with encrypted profiles.
- [espanso](https://github.com/espanso/espanso) - A cross-platform text expander.
- [gum](https://github.com/charmbracelet/gum) - A tool for glamorous shell scripts with prompts, spinners, and input widgets.
- [mods](https://github.com/charmbracelet/mods) - AI on the command line, pipe stdin to LLMs and get structured output.
- [nb](https://github.com/xwmx/nb) - A note-taking, bookmarking, and knowledge base application.
- [topgrade](https://github.com/topgrade-rs/topgrade) - Upgrade all your tools at once.

## Code Counting

> Replacements for `cloc` and `wc -l`.

- [scc](https://github.com/boyter/scc) - A very fast accurate code counter with complexity calculations.
- [tokei](https://github.com/XAMPPRocky/tokei) - Count lines of code quickly and accurately across many languages.

## Spelling & Linting

> Code quality tools for the terminal.

- [biome](https://github.com/biomejs/biome) - A fast formatter and linter for web projects, replaces ESLint + Prettier.
- [ruff](https://github.com/astral-sh/ruff) - An extremely fast Python linter and formatter.
- [typos](https://github.com/crate-ci/typos) - Source code spell checker that finds and corrects common misspellings.
- [uv](https://github.com/astral-sh/uv) - An extremely fast Python package and project manager.

## Tunneling

> Replacements for `ngrok` and port forwarding tools.

- [bore](https://github.com/ekzhang/bore) - A simple CLI tool for exposing local ports to the internet.
- [rathole](https://github.com/rathole-org/rathole) - A lightweight, high-performance reverse proxy for NAT traversal.

## Web

> Browsers, proxies, and web utilities.

- [browsh](https://github.com/browsh-org/browsh) - A fully interactive, modern text-based browser.
- [carbonyl](https://github.com/fathyb/carbonyl) - Chromium running inside your terminal.
- [mitmproxy](https://www.mitmproxy.org) - A free, interactive HTTPS proxy for debugging and testing.
- [monolith](https://github.com/Y2Z/monolith) - Save complete web pages as a single HTML file with all assets embedded.

## Miscellaneous

> Tools that defy easy categorization but are too good to leave out.

- [GQL](https://github.com/amrdeveloper/gql) - A SQL-like query language for .git repositories.
- [httm](https://github.com/kimono-koans/httm) - Interactive file-level Time Machine-like tool for ZFS/btrfs.
- [prqlc](https://github.com/PRQL/prql) - PRQL compiler, a pipelined modern alternative to SQL.
- [rustic](https://github.com/rustic-rs/rustic) - Fast, encrypted, deduplicated backups, a restic alternative.
- [uutils coreutils](https://github.com/uutils/coreutils) - Cross-platform Rust rewrite of the GNU coreutils (adopted by Ubuntu).
- [vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight Bitwarden server implementation.
- [wttr.in](https://github.com/chubin/wttr.in) - The right way to check the weather from the terminal.

---

## Resources

- [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) - A curated list of command line apps.
- [awesome-shell](https://github.com/alebcay/awesome-shell) - A curated list of awesome command-line frameworks, toolkits, guides, and gizmos.
- [awesome-tuis](https://github.com/rothgar/awesome-tuis) - List of projects that provide terminal user interfaces.
- [Charm](https://charm.land) - Tools to make the command line glamorous (bubbletea, lipgloss, glow, etc.).
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - Master the command line in one page.

---

## Contributing

Contributions welcome! Read `CONTRIBUTING.md` first.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=thegdsks/awesome-modern-cli&type=Date)](https://star-history.com/#thegdsks/awesome-modern-cli&Date)
