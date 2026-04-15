<div align="center">

# Awesome Modern CLI

A curated list of modern alternatives to classic command-line tools.

The terminal is having a renaissance. Faster, prettier, smarter tools are replacing the Unix classics you've used for decades. This list helps you find them.

[Contribute](CONTRIBUTING.md)

</div>

---

### Highlights

<p align="center">
<a href="https://github.com/sharkdp/bat"><b>bat</b></a> - A <code>cat</code> clone with syntax highlighting and Git integration
<br><br>
<img src="https://imgur.com/rGsdnDe.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/eza-community/eza"><b>eza</b></a> - A modern replacement for <code>ls</code> with colors, icons, and git integration
<br><br>
<img src="https://raw.githubusercontent.com/eza-community/eza/main/docs/images/screenshots.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/dandavison/delta"><b>delta</b></a> - A syntax-highlighting pager for git, diff, and grep output
<br><br>
<img src="https://user-images.githubusercontent.com/52205/86275526-76792100-bba1-11ea-9e78-6be9baa80b29.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/jesseduffield/lazygit"><b>lazygit</b></a> - A simple terminal UI for git commands
<br><br>
<img src="https://raw.githubusercontent.com/jesseduffield/lazygit/assets/staging.gif" width="600" />
</p>

<p align="center">
<a href="https://github.com/aristocratos/btop"><b>btop</b></a> - A resource monitor with beautiful TUI and extensive features
<br><br>
<img src="https://raw.githubusercontent.com/aristocratos/btop/main/Img/normal.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/junegunn/fzf"><b>fzf</b></a> - A general-purpose command-line fuzzy finder
<br><br>
<img src="https://raw.githubusercontent.com/junegunn/i/master/fzf-preview.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/ajeetdsouza/zoxide"><b>zoxide</b></a> - A smarter <code>cd</code> command that learns your habits
<br><br>
<img src="https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/contrib/tutorial.webp" width="600" />
</p>

<p align="center">
<a href="https://github.com/jesseduffield/lazydocker"><b>lazydocker</b></a> - The lazier way to manage everything Docker
<br><br>
<img src="https://user-images.githubusercontent.com/8456633/59972109-8e9c8480-95cc-11e9-8350-38f7f86ba76d.png" width="600" />
</p>

<p align="center">
<a href="https://github.com/starship/starship"><b>starship</b></a> - Minimal, blazing-fast, and infinitely customizable prompt for any shell
<br><br>
<img src="https://raw.githubusercontent.com/starship/starship/master/media/demo.gif" width="600" />
</p>

<p align="center">
<a href="https://github.com/sharkdp/hyperfine"><b>hyperfine</b></a> - A command-line benchmarking tool with statistical analysis
<br><br>
<img src="https://i.imgur.com/z19OYxE.gif" width="600" />
</p>

<p align="center">
<a href="https://github.com/orf/gping"><b>gping</b></a> - Ping, but with a graph
<br><br>
<img src="https://raw.githubusercontent.com/orf/gping/master/images/readme-example.gif" width="600" />
</p>

<p align="center">
<a href="https://github.com/BurntSushi/ripgrep"><b>ripgrep</b></a> - An extremely fast alternative to <code>grep</code> that respects gitignore
<br><br>
<img src="https://user-images.githubusercontent.com/200613/90223748-ecaeab80-de0e-11ea-9140-ac9219f5747c.gif" width="600" />
</p>

---

## Contents

<details>
<summary>Expand</summary>

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

</details>

---

## File Listing

> Replacements for `ls` and `tree`.

- [broot](https://github.com/Canop/broot) - A new way to see and navigate directory trees with fuzzy search. `Rust`
- [eza](https://github.com/eza-community/eza) - A modern, maintained replacement for ls with colors, icons, and git integration. `Rust`
- [lla](https://github.com/chaqchase/lla) - A fast ls alternative with a plugin system for extended functionality. `Rust`
- [lsd](https://github.com/lsd-rs/lsd) - The next gen ls command with pretty colors and file icons. `Rust`
- [pls](https://github.com/pls-rs/pls) - ls for the pros, with developer-friendly features and Nerd Font icons. `Rust`
- [tre](https://github.com/dduan/tre) - A tree command improved with git awareness and editor integration. `Rust`

**[⬆ back to top](#contents)**

## File Search

> Replacements for `find`.

- [fd](https://github.com/sharkdp/fd) - A simple, fast, and user-friendly alternative to find. `Rust`
- [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries. `Rust`

**[⬆ back to top](#contents)**

## File Management

> Replacements for `ranger`, `rm`, `cp`, and file managers.

- [clifm](https://github.com/leo-arch/clifm) - A command-line file manager that lives in the shell. `C`
- [f2](https://github.com/ayoisaiah/f2) - Cross-platform tool for fast, safe, and flexible batch renaming. `Go`
- [fclones](https://github.com/pkolaczk/fclones) - Efficient duplicate file finder and remover. `Rust`
- [fuc](https://github.com/supercilex/fuc) - Fast cp and rm commands for modern hardware. `Rust`
- [joshuto](https://github.com/kamiyaa/joshuto) - Ranger-like terminal file manager with vi keybindings. `Rust`
- [kondo](https://github.com/tbillington/kondo) - Find and delete software project build artifacts to reclaim disk space. `Rust`
- [lf](https://github.com/gokcehan/lf) - Fast, extensively customizable terminal file manager. `Go`
- [nnn](https://github.com/jarun/nnn) - The unorthodox terminal file manager, tiny and blazing fast. `C`
- [nomino](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort, and map. `Rust`
- [rip](https://github.com/nivekuil/rip) - A safe and ergonomic alternative to rm with a graveyard for recovery. `Rust`
- [superfile](https://github.com/yorukot/superfile) - Pretty and modern terminal file manager. `Go`
- [xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer. `Rust`
- [yazi](https://github.com/sxyazi/yazi) - Blazing fast terminal file manager with async I/O and image preview. `Rust`

**[⬆ back to top](#contents)**

## Text Search

> Replacements for `grep` and `ag`.

- [ast-grep](https://github.com/ast-grep/ast-grep) - Structural code search, lint, and rewriting using AST patterns. `Rust`
- [rare](https://github.com/zix99/rare) - Real-time regex-powered aggregation and analytics on the command-line. `Go`
- [ripgrep](https://github.com/BurntSushi/ripgrep) - An extremely fast alternative to grep that respects gitignore. `Rust`
- [ripgrep-all](https://github.com/phiresky/ripgrep-all) - ripgrep, but also searches PDFs, e-books, Office documents, zip, and archives. `Rust`
- [sig](https://github.com/ynqa/sig) - Interactive grep for streaming data. `Rust`
- [srgn](https://github.com/alexpovel/srgn) - A grep-like tool that understands source code syntax. `Rust`

**[⬆ back to top](#contents)**

## Text Processing

> Replacements for `sed`, `awk`, `cut`, and `uniq`.

- [choose](https://github.com/theryangeary/choose) - A human-friendly and fast alternative to cut and awk. `Rust`
- [grex](https://github.com/pemistahl/grex) - Generate regular expressions from user-provided test cases. `Rust`
- [hck](https://github.com/sstadick/hck) - A faster and more featureful drop-in replacement for cut. `Rust`
- [rargs](https://github.com/lotabout/rargs) - xargs + awk with pattern matching support. `Rust`
- [runiq](https://github.com/whitfin/runiq) - Efficient way to filter duplicate lines from unsorted input. `Rust`
- [ruplacer](https://github.com/your-tools/ruplacer) - Find and replace text across multiple source files. `Rust`
- [scooter](https://github.com/thomasschafer/scooter) - Interactive find and replace in the terminal. `Rust`
- [sd](https://github.com/chmln/sd) - An intuitive find-and-replace CLI, a simpler sed alternative. `Rust`

**[⬆ back to top](#contents)**

## Text Viewing

> Replacements for `cat`, `less`, and `hexdump`.

- [bat](https://github.com/sharkdp/bat) - A cat clone with syntax highlighting and Git integration. `Rust`
- [fblog](https://github.com/brocode/fblog) - Small command-line JSON log viewer with smart formatting. `Rust`
- [glow](https://github.com/charmbracelet/glow) - Render markdown beautifully in the terminal. `Go`
- [hexyl](https://github.com/sharkdp/hexyl) - A command-line hex viewer with colored output. `Rust`
- [lnav](https://lnav.org/) - An advanced log file viewer with automatic format detection. `C++`
- [mdcat](https://github.com/swsnr/mdcat) - Render Markdown in the terminal with syntax highlighting, links, and inline images. `Rust`
- [tailspin](https://github.com/bensadeh/tailspin) - A log file highlighter that works out of the box. `Rust`

**[⬆ back to top](#contents)**

## Text Editors

> Modern terminal-based editors.

- [amp](https://github.com/jmacdonald/amp) - A complete text editor for your terminal inspired by Vi/Vim. `Rust`
- [edit](https://github.com/microsoft/edit) - A simple terminal text editor from Microsoft, paying homage to MS-DOS Editor. `Rust`
- [helix](https://github.com/helix-editor/helix) - A post-modern modal text editor with built-in LSP and tree-sitter. `Rust`
- [kakoune](https://github.com/mawww/kakoune) - Modal editor with multi-selection first design. `C++`
- [Lapce](https://github.com/lapce/lapce) - A lightning-fast and powerful code editor with native GUI. `Rust`
- [micro](https://github.com/micro-editor/micro) - A modern and intuitive terminal-based text editor, replaces nano. `Go`
- [neovim](https://github.com/neovim/neovim) - Vim-fork focused on extensibility and usability with Lua plugin system. `C`
- [ox](https://github.com/curlpipe/ox) - An independent terminal text editor, simple and practical. `Rust`
- [zed](https://github.com/zed-industries/zed) - A high-performance multiplayer code editor from the creators of Atom. `Rust`

**[⬆ back to top](#contents)**

## JSON / YAML / CSV

> Replacements for `jq`, data viewers, and structured data tools.

- [csvlens](https://github.com/YS-L/csvlens) - A TUI CSV file viewer, like less but made for tabular data. `Rust`
- [dasel](https://github.com/tomwright/dasel) - Query and modify JSON, YAML, TOML, and XML from the command line. `Go`
- [dyff](https://github.com/homeport/dyff) - A diff tool for YAML files with semantic awareness. `Go`
- [fx](https://github.com/antonmedv/fx) - Terminal JSON viewer and processor with interactive mode. `Go`
- [gron](https://github.com/tomnomnom/gron) - Make JSON greppable by flattening it to discrete assignments. `Go`
- [jless](https://github.com/PaulJuliusMartinez/jless) - A command-line JSON viewer with vim-like navigation. `Rust`
- [jnv](https://github.com/ynqa/jnv) - Interactive JSON filter using jq expressions with live preview. `Rust`
- [jq](https://github.com/jqlang/jq) - The original lightweight command-line JSON processor. `C`
- [jsongrep](https://github.com/micahkepe/jsongrep) - Fast search tool for JSON, YAML, and TOML with path query syntax. `Rust`
- [qsv](https://github.com/dathere/qsv) - A high-performance CSV toolkit, xsv fork with 34+ extra commands. `Rust`
- [sc-im](https://github.com/andmarti1424/sc-im) - A vim-like spreadsheet calculator for the terminal. `C`
- [Tabiew](https://github.com/shshemi/tabiew) - Lightweight TUI to view and query CSV, TSV, and Parquet files. `Rust`
- [visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data. `Python`
- [xq](https://github.com/sibprogrammer/xq) - XML and HTML beautifier and content extractor. `Go`
- [xsv](https://github.com/BurntSushi/xsv) - A fast CSV command line toolkit for slicing, indexing, and searching. `Rust`
- [yq](https://github.com/kislyuk/yq) - jq wrapper for YAML, XML, and TOML documents. `Python`

**[⬆ back to top](#contents)**

## Shell & Prompt

> Modern shells and prompt customization.

- [elvish](https://github.com/elves/elvish) - An expressive shell with a real programming language built-in. `Go`
- [fish](https://github.com/fish-shell/fish-shell) - The user-friendly command-line shell with autosuggestions. `Rust`
- [nushell](https://github.com/nushell/nushell) - A new type of shell with structured data pipelines. `Rust`
- [oh-my-posh](https://ohmyposh.dev) - A prompt theme engine for any shell with extensive themes. `Go`
- [starship](https://github.com/starship/starship) - Minimal, blazing-fast, and infinitely customizable prompt for any shell. `Rust`

**[⬆ back to top](#contents)**

## Shell History

> Replacements for `ctrl+r` history search.

- [atuin](https://github.com/atuinsh/atuin) - Magical shell history stored in a SQLite database with optional encrypted sync. `Rust`
- [mcfly](https://github.com/cantino/mcfly) - Fly through shell history with intelligent context-aware search. `Rust`

**[⬆ back to top](#contents)**

## Navigation

> Replacements for `cd` and directory jumping.

- [autojump](https://github.com/wting/autojump) - A cd command that learns from your navigation patterns. `Python`
- [tere](https://github.com/mgunyho/tere) - A faster alternative to cd + ls for navigating directories. `Rust`
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A smarter cd command that learns your habits. `Rust`

**[⬆ back to top](#contents)**

## Fuzzy Finding

> Interactive filtering and selection tools.

- [fzf](https://github.com/junegunn/fzf) - A general-purpose command-line fuzzy finder. `Go`
- [skim](https://github.com/skim-rs/skim) - A general-purpose fuzzy finder in Rust, similar to fzf. `Rust`
- [television](https://github.com/alexpasmantier/television) - A blazing fast general-purpose fuzzy finder TUI. `Rust`

**[⬆ back to top](#contents)**

## Version Control

> Git TUIs and enhanced git workflows.

- [gh-dash](https://github.com/dlvhdr/gh-dash) - A beautiful TUI dashboard for GitHub pull requests and issues. `Go`
- [git-cliff](https://github.com/orhun/git-cliff) - A highly customizable changelog generator following Conventional Commits. `Rust`
- [git-extras](https://github.com/tj/git-extras) - Git utilities like repo summary, changelog, and commit percentages. `Shell`
- [gita](https://github.com/nosarthur/gita) - Manage multiple git repos side by side. `Python`
- [gitui](https://github.com/gitui-org/gitui) - Blazing fast terminal client for git. `Rust`
- [jj](https://github.com/jj-vcs/jj) - A Git-compatible VCS with simpler CLI, first-class conflicts, and auto-rebasing. `Rust`
- [lazygit](https://github.com/jesseduffield/lazygit) - A simple terminal UI for git commands. `Go`
- [onefetch](https://github.com/o2sh/onefetch) - Command-line Git information tool showing repo stats. `Rust`
- [sapling](https://github.com/facebook/sapling) - A scalable, user-friendly source control system from Meta. `Rust`
- [serie](https://github.com/lusingander/serie) - A rich git commit graph viewer for the terminal. `Rust`
- [soft-serve](https://github.com/charmbracelet/soft-serve) - A tasty, self-hostable Git server for the command line. `Go`
- [tig](https://github.com/jonas/tig) - Text-mode interface for git with browse and blame modes. `C`

**[⬆ back to top](#contents)**

## Diff Tools

> Better alternatives to `diff`.

- [delta](https://github.com/dandavison/delta) - A syntax-highlighting pager for git, diff, and grep output. `Rust`
- [difftastic](https://github.com/Wilfred/difftastic) - A structural diff that understands syntax across 30+ languages. `Rust`

**[⬆ back to top](#contents)**

## System Monitoring

> Replacements for `top`, `htop`, and system info tools.

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool showing per-process usage. `Rust`
- [bottom](https://github.com/ClementTsang/bottom) - A cross-platform graphical process/system monitor. `Rust`
- [btop](https://github.com/aristocratos/btop) - A resource monitor with beautiful TUI and extensive features. `C++`
- [fastfetch](https://github.com/fastfetch-cli/fastfetch) - A fast system information tool, neofetch replacement. `C`
- [glances](https://github.com/nicolargo/glances) - An eye on your system with a top/htop alternative and web mode. `Python`
- [gotop](https://github.com/xxxserxxx/gotop) - Terminal-based graphical activity monitor. `Go`
- [kmon](https://github.com/orhun/kmon) - Linux Kernel Manager and Activity Monitor. `Rust`
- [macmon](https://github.com/vladkens/macmon) - Sudoless performance monitoring for Apple Silicon. `Rust`
- [nvtop](https://github.com/Syllo/nvtop) - GPU process monitoring for AMD, Intel, and NVIDIA. `C`
- [procs](https://github.com/dalance/procs) - A modern replacement for ps written in Rust. `Rust`
- [systeroid](https://github.com/orhun/systeroid) - A more powerful alternative to sysctl with a terminal UI. `Rust`
- [zenith](https://github.com/bvaisvil/zenith) - In-terminal graphical metrics with CPU, GPU, network, and disk charts. `Rust`

**[⬆ back to top](#contents)**

## Process Management

> Replacements for `nohup`, `bg`, and `kill`.

- [mprocs](https://github.com/pvolok/mprocs) - Run multiple commands in parallel and view their output in a TUI. `Rust`
- [pik](https://github.com/jacek-kurlit/pik) - TUI tool to find and kill processes interactively. `Rust`
- [process-compose](https://github.com/F1bonacc1/process-compose) - A scheduler and orchestrator for non-containerized processes with TUI. `Go`
- [pueue](https://github.com/nukesor/pueue) - Manage long-running shell commands with a daemon and TUI. `Rust`

**[⬆ back to top](#contents)**

## Disk Usage

> Replacements for `du` and `df`.

- [diskonaut](https://github.com/imsnif/diskonaut) - Terminal visual disk space navigator. `Rust`
- [dua-cli](https://github.com/Byron/dua-cli) - Disk usage analyzer with interactive navigation. `Rust`
- [duf](https://github.com/muesli/duf) - A better df alternative with color-coded output and filtering. `Go`
- [dust](https://github.com/bootandy/dust) - A more intuitive version of du with visual output. `Rust`
- [gdu](https://github.com/dundee/gdu) - Fast disk usage analyzer with console interface. `Go`
- [ncdu](https://dev.yorhel.nl/ncdu) - A disk usage analyzer with an ncurses interface. `Zig`

**[⬆ back to top](#contents)**

## Network Tools

> Replacements for `ping`, `traceroute`, and network diagnostics.

- [gping](https://github.com/orf/gping) - Ping, but with a graph. `Rust`
- [miniserve](https://github.com/svenstaro/miniserve) - Serve files over HTTP from the terminal with a single command. `Rust`
- [netscanner](https://github.com/Chleba/netscanner) - A TUI network scanner. `Rust`
- [sniffnet](https://github.com/GyulyVGC/sniffnet) - Monitor your network traffic easily with a cross-platform TUI. `Rust`
- [termshark](https://github.com/gcla/termshark) - A terminal UI for tshark, inspired by Wireshark. `Go`
- [trippy](https://github.com/fujiapple852/trippy) - A network diagnostic tool combining ping and traceroute with rich TUI. `Rust`

**[⬆ back to top](#contents)**

## HTTP Clients

> Replacements for `curl` and `wget`.

- [aria2](https://github.com/aria2/aria2) - Ultra-fast download utility supporting HTTP, FTP, BitTorrent, and Metalink. `C++`
- [curlie](https://github.com/rs/curlie) - The power of curl, the ease of use of httpie. `Go`
- [httpie](https://github.com/httpie/cli) - A modern, user-friendly command-line HTTP client for the API era. `Python`
- [xh](https://github.com/ducaale/xh) - A friendly and fast tool for sending HTTP requests, an HTTPie reimplementation. `Rust`

**[⬆ back to top](#contents)**

## API Testing

> Replacements for Postman and API debugging tools.

- [ATAC](https://github.com/Julien-cpsn/ATAC) - A feature-full TUI API client, free, offline, and account-less. `Rust`
- [HTTP Prompt](https://github.com/httpie/http-prompt) - An interactive HTTP client with autocomplete and syntax highlighting. `Python`
- [posting](https://github.com/darrenburns/posting) - A powerful HTTP client that lives in your terminal. `Python`

**[⬆ back to top](#contents)**

## DNS Tools

> Replacements for `dig` and `nslookup`.

- [doggo](https://github.com/mr-karan/doggo) - Command-line DNS client for humans with color-coded output. `Go`

**[⬆ back to top](#contents)**

## Benchmarking

> Replacements for `time` and load testing tools.

- [hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool with statistical analysis. `Rust`
- [oha](https://github.com/hatoo/oha) - HTTP load generator with a real-time TUI. `Rust`

**[⬆ back to top](#contents)**

## Compression

> Replacements for `tar`, `gzip`, and `unzip`.

- [crabz](https://github.com/sstadick/crabz) - Multi-threaded compression and decompression CLI tool. `Rust`
- [ouch](https://github.com/ouch-org/ouch) - Painless compression and decompression, smart format detection. `Rust`

**[⬆ back to top](#contents)**

## File Transfer

> Replacements for `scp` and `rsync`.

- [croc](https://github.com/schollz/croc) - Easily and securely send things from one computer to another. `Go`
- [portal](https://github.com/SpatiumPortae/portal) - Send files between computers through an encrypted peer-to-peer tunnel. `Go`
- [rclone](https://github.com/rclone/rclone) - Sync files with any cloud provider, an rsync for cloud storage. `Go`
- [termscp](https://github.com/veeso/termscp) - TUI file transfer and explorer with SCP, SFTP, FTP, and S3 support. `Rust`

**[⬆ back to top](#contents)**

## Terminal Emulators

> Modern GPU-accelerated terminal emulators.

- [alacritty](https://github.com/alacritty/alacritty) - A cross-platform, GPU-enhanced terminal emulator focused on speed. `Rust`
- [Ghostty](https://github.com/ghostty-org/ghostty) - Fast, feature-rich, cross-platform terminal emulator with native platform UI. `Zig`
- [rio](https://github.com/raphamorim/rio) - A hardware-accelerated GPU terminal emulator powered by WebGPU. `Rust`
- [Warp](https://github.com/warpdotdev/Warp) - AI-powered modern terminal with structured command history and IDE-like features. `Rust`
- [wezterm](https://github.com/wezterm/wezterm) - A GPU-accelerated terminal emulator and multiplexer with Lua config. `Rust`

**[⬆ back to top](#contents)**

## Terminal Multiplexers

> Replacements for `tmux` and `screen`.

- [tmux](https://github.com/tmux/tmux) - The classic terminal multiplexer with extensive plugin ecosystem. `C`
- [zellij](https://github.com/zellij-org/zellij) - A terminal workspace with batteries included, a tmux alternative. `Rust`

**[⬆ back to top](#contents)**

## Task Runners

> Replacements for `make` and build tools.

- [bacon](https://github.com/Canop/bacon) - Background code checker, designed for Rust but works for any language. `Rust`
- [entr](https://github.com/eradman/entr) - Run arbitrary commands when files change. `C`
- [just](https://github.com/casey/just) - A handy command runner for project-specific tasks, a modern make. `Rust`
- [watchexec](https://github.com/watchexec/watchexec) - Execute commands in response to file modifications. `Rust`

**[⬆ back to top](#contents)**

## Version Managers

> Replacements for `nvm`, `pyenv`, and `asdf`.

- [fnm](https://github.com/Schniz/fnm) - Fast Node Manager, a cross-platform nvm replacement. `Rust`
- [mise](https://github.com/jdx/mise) - A polyglot tool version manager and task runner, asdf replacement. `Rust`
- [volta](https://github.com/volta-cli/volta) - JavaScript toolchain manager that pins exact versions per project. `Rust`

**[⬆ back to top](#contents)**

## JS / TS Toolchain

> Modern JavaScript and TypeScript build tools and runtimes.

- [Bun](https://github.com/oven-sh/bun) - All-in-one JavaScript runtime, bundler, test runner, and package manager. `Zig`
- [Deno](https://github.com/denoland/deno) - A secure JavaScript/TypeScript runtime with built-in tooling. `Rust`
- [oxc](https://github.com/oxc-project/oxc) - A high-performance collection of JS/TS tools, 50-100x faster than ESLint. `Rust`
- [SWC](https://github.com/swc-project/swc) - A super-fast TypeScript/JavaScript compiler, replaces Babel. `Rust`
- [Turborepo](https://github.com/vercel/turborepo) - High-performance build system for JavaScript/TypeScript monorepos. `Rust`

**[⬆ back to top](#contents)**

## Static Site Generators

> Build static websites from templates and content.

- [hugo](https://github.com/gohugoio/hugo) - The world's fastest static site generator with multi-language support. `Go`
- [zola](https://github.com/getzola/zola) - A fast static site generator in a single binary with built-in Sass and syntax highlighting. `Rust`

**[⬆ back to top](#contents)**

## Container Tools

> Docker TUIs and container management.

- [ctop](https://github.com/bcicen/ctop) - Top-like interface for container metrics. `Go`
- [dive](https://github.com/wagoodman/dive) - Tool for exploring each layer in a Docker image. `Go`
- [lazydocker](https://github.com/jesseduffield/lazydocker) - The lazier way to manage everything Docker. `Go`
- [nerdctl](https://github.com/containerd/nerdctl) - Docker-compatible CLI for containerd with Compose and rootless support. `Go`
- [oxker](https://github.com/mrjackwills/oxker) - A simple TUI to view and control Docker containers. `Rust`

**[⬆ back to top](#contents)**

## Kubernetes

> kubectl alternatives and K8s TUIs.

- [k9s](https://github.com/derailed/k9s) - TUI for managing Kubernetes clusters. `Go`
- [kdash](https://github.com/kdash-rs/kdash) - A simple and fast dashboard for Kubernetes. `Rust`

**[⬆ back to top](#contents)**

## Database Clients

> Replacements for `psql`, `mysql`, and database GUIs.

- [harlequin](https://github.com/tconbeer/harlequin) - The SQL IDE for your terminal. `Python`
- [iredis](https://github.com/laixintao/iredis) - Redis client with autocompletion and syntax highlighting. `Python`
- [lazysql](https://github.com/jorgerojas26/lazysql) - A cross-platform TUI database management tool. `Go`
- [mycli](https://github.com/dbcli/mycli) - MySQL client with autocompletion and syntax highlighting. `Python`
- [pgcli](https://github.com/dbcli/pgcli) - Postgres client with autocompletion and syntax highlighting. `Python`
- [rainfrog](https://github.com/achristmascarl/rainfrog) - Database management TUI for Postgres, MySQL, and SQLite. `Rust`
- [usql](https://github.com/xo/usql) - Universal command-line SQL client with autocompletion. `Go`

**[⬆ back to top](#contents)**

## Security Tools

> Password managers, encryption, and security utilities.

- [cotp](https://github.com/replydev/cotp) - Encrypted command-line TOTP/HOTP authenticator. `Rust`
- [feroxbuster](https://github.com/epi052/feroxbuster) - A fast, simple, recursive content discovery tool. `Rust`
- [flawz](https://github.com/orhun/flawz) - A terminal UI for browsing security vulnerabilities (CVEs). `Rust`
- [gopass](https://github.com/gopasspw/gopass) - Fully-featured password manager compatible with pass. `Go`
- [gpg-tui](https://github.com/orhun/gpg-tui) - A terminal user interface for GnuPG. `Rust`
- [rage](https://github.com/str4d/rage) - A simple, modern, and secure file encryption tool (age implementation). `Rust`

**[⬆ back to top](#contents)**

## Calculator

> Replacements for `bc` and `calc`.

- [fend](https://github.com/printfn/fend) - Arbitrary-precision unit-aware calculator. `Rust`
- [kalker](https://github.com/PaddiM8/kalker) - Scientific calculator with math-like syntax, complex numbers, and vectors. `Rust`

**[⬆ back to top](#contents)**

## Documentation

> Man page alternatives and documentation tools.

- [cheat](https://github.com/cheat/cheat) - Create and view interactive cheatsheets on the command-line. `Go`
- [mdBook](https://github.com/rust-lang/mdBook) - Create books from Markdown, like GitBook but in Rust. `Rust`
- [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line. `Rust`
- [tealdeer](https://github.com/tealdeer-rs/tealdeer) - A very fast tldr client with offline caching. `Rust`
- [tectonic](https://github.com/tectonic-typesetting/tectonic) - A self-contained TeX/LaTeX engine that downloads packages on demand. `C`
- [thefuck](https://github.com/nvbn/thefuck) - Corrects your previous console command when you mistype. `Python`
- [tldr](https://github.com/tldr-pages/tldr) - Simplified man pages with practical examples. `Multi`
- [Typst](https://github.com/typst/typst) - A modern markup-based typesetting system, a LaTeX alternative. `Rust`

**[⬆ back to top](#contents)**

## Presentation

> Terminal-based presentation tools.

- [presenterm](https://github.com/mfontanini/presenterm) - A terminal slideshow tool that renders Markdown presentations. `Rust`
- [slides](https://github.com/maaslalani/slides) - Terminal-based presentation tool using Markdown. `Go`

**[⬆ back to top](#contents)**

## Media

> Music players, image viewers, and media tools.

- [asciinema](https://github.com/asciinema/asciinema) - Record and share terminal sessions as lightweight text. `Rust`
- [freeze](https://github.com/charmbracelet/freeze) - Generate images of code and terminal output. `Go`
- [ncspot](https://github.com/hrkfdn/ncspot) - Cross-platform ncurses Spotify client. `Rust`
- [oxipng](https://github.com/oxipng/oxipng) - Multithreaded lossless PNG optimizer. `Rust`
- [pastel](https://github.com/sharkdp/pastel) - Generate, analyze, convert, and manipulate colors. `Rust`
- [spotify-player](https://github.com/aome510/spotify-player) - A Spotify player in the terminal with full feature parity. `Rust`
- [termusic](https://github.com/tramhao/termusic) - A terminal music player. `Rust`
- [vhs](https://github.com/charmbracelet/vhs) - Write terminal GIFs as code for documentation and demos. `Go`
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - Download videos from YouTube and other sites, a youtube-dl fork. `Python`

**[⬆ back to top](#contents)**

## Messaging

> Terminal-based chat and email clients.

- [aerc](https://aerc-mail.org/) - A pretty good email client for the terminal. `Go`
- [gomuks](https://github.com/gomuks/gomuks) - A Matrix client for the terminal. `Go`
- [himalaya](https://github.com/pimalaya/himalaya) - CLI email client supporting IMAP, JMAP, and Maildir with scriptable interface. `Rust`
- [iamb](https://iamb.chat) - A Matrix client for Vim addicts. `Rust`
- [newsboat](https://github.com/newsboat/newsboat) - An RSS/Atom feed reader for the text console. `C++`

**[⬆ back to top](#contents)**

## Productivity

> Task managers, clipboard, calendars, and shell utilities.

- [calcure](https://github.com/anufrievroman/calcure) - Modern TUI calendar and task manager. `Python`
- [Clipboard](https://github.com/Slackadays/Clipboard) - Cut, copy, and paste anything from the terminal. `C++`
- [clipse](https://github.com/savedra1/clipse) - TUI clipboard manager. `Go`
- [envio](https://github.com/humblepenguinn/envio) - Modern environment variable manager with encrypted profiles. `Rust`
- [espanso](https://github.com/espanso/espanso) - A cross-platform text expander. `Rust`
- [gum](https://github.com/charmbracelet/gum) - A tool for glamorous shell scripts with prompts, spinners, and input widgets. `Go`
- [mods](https://github.com/charmbracelet/mods) - AI on the command line, pipe stdin to LLMs and get structured output. `Go`
- [nb](https://github.com/xwmx/nb) - A note-taking, bookmarking, and knowledge base application. `Shell`
- [topgrade](https://github.com/topgrade-rs/topgrade) - Upgrade all your tools at once. `Rust`

**[⬆ back to top](#contents)**

## Code Counting

> Replacements for `cloc` and `wc -l`.

- [scc](https://github.com/boyter/scc) - A very fast accurate code counter with complexity calculations. `Go`
- [tokei](https://github.com/XAMPPRocky/tokei) - Count lines of code quickly and accurately across many languages. `Rust`

**[⬆ back to top](#contents)**

## Spelling & Linting

> Code quality tools for the terminal.

- [biome](https://github.com/biomejs/biome) - A fast formatter and linter for web projects, replaces ESLint + Prettier. `Rust`
- [ruff](https://github.com/astral-sh/ruff) - An extremely fast Python linter and formatter. `Rust`
- [typos](https://github.com/crate-ci/typos) - Source code spell checker that finds and corrects common misspellings. `Rust`
- [uv](https://github.com/astral-sh/uv) - An extremely fast Python package and project manager. `Rust`

**[⬆ back to top](#contents)**

## Tunneling

> Replacements for `ngrok` and port forwarding tools.

- [bore](https://github.com/ekzhang/bore) - A simple CLI tool for exposing local ports to the internet. `Rust`
- [rathole](https://github.com/rathole-org/rathole) - A lightweight, high-performance reverse proxy for NAT traversal. `Rust`

**[⬆ back to top](#contents)**

## Web

> Browsers, proxies, and web utilities.

- [browsh](https://github.com/browsh-org/browsh) - A fully interactive, modern text-based browser. `Go`
- [carbonyl](https://github.com/fathyb/carbonyl) - Chromium running inside your terminal. `Rust`
- [mitmproxy](https://www.mitmproxy.org) - A free, interactive HTTPS proxy for debugging and testing. `Python`
- [monolith](https://github.com/Y2Z/monolith) - Save complete web pages as a single HTML file with all assets embedded. `Rust`

**[⬆ back to top](#contents)**

## Miscellaneous

> Tools that defy easy categorization but are too good to leave out.

- [GQL](https://github.com/amrdeveloper/gql) - A SQL-like query language for .git repositories. `Rust`
- [httm](https://github.com/kimono-koans/httm) - Interactive file-level Time Machine-like tool for ZFS/btrfs. `Rust`
- [prqlc](https://github.com/PRQL/prql) - PRQL compiler, a pipelined modern alternative to SQL. `Rust`
- [rustic](https://github.com/rustic-rs/rustic) - Fast, encrypted, deduplicated backups, a restic alternative. `Rust`
- [uutils coreutils](https://github.com/uutils/coreutils) - Cross-platform Rust rewrite of the GNU coreutils (adopted by Ubuntu). `Rust`
- [vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight Bitwarden server implementation. `Rust`
- [wttr.in](https://github.com/chubin/wttr.in) - The right way to check the weather from the terminal. `Python`

**[⬆ back to top](#contents)**

---

## Resources

- [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) - A curated list of command line apps.
- [awesome-shell](https://github.com/alebcay/awesome-shell) - A curated list of awesome command-line frameworks, toolkits, guides, and gizmos.
- [awesome-tuis](https://github.com/rothgar/awesome-tuis) - List of projects that provide terminal user interfaces.
- [Charm](https://charm.land) - Tools to make the command line glamorous (bubbletea, lipgloss, glow, etc.).
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - Master the command line in one page.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
