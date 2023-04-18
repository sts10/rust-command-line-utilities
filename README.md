# A curated list of command-line utilities written in Rust

Note that I have not tried all of these personally and **cannot and do not vouch for all of the tools listed here**. In most cases, the descriptions below are copied directly from their code repos at the time I found them. Some projects may have been abandoned. Investigate before installing/using.

The ones I use regularly use are: bat, fd, fend, hyperfine, miniserve, ripgrep, just, cargo-audit and cargo-wipe. (I'm torn between dust and erdtree...)

## Unix-to-Rust replacements (or near-replacements)

|unix|rust                                               |stars                                                                                                |last release                                                                                                  |
|----|---------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
|cat |[bat       ](https://github.com/sharkdp/bat)       |![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/bat?style=flat-square&label=)       |![GitHub last release](https://img.shields.io/github/release-date/sharkdp/bat?style=flat-square&label=)       |
|cd  |[zoxide    ](https://github.com/ajeetdsouza/zoxide)|![GitHub Repo stars](https://img.shields.io/github/stars/ajeetdsouza/zoxide?style=flat-square&label=)|![GitHub last release](https://img.shields.io/github/release-date/ajeetdsouza/zoxide?style=flat-square&label=)|
|cp  |[xcp       ](https://github.com/tarka/xcp)         |![GitHub Repo stars](https://img.shields.io/github/stars/tarka/xcp?style=flat-square&label=)         |![GitHub last release](https://img.shields.io/github/release-date/tarka/xcp?style=flat-square&label=)         |
|df  |[lfs       ](https://github.com/Canop/lfs)         |![GitHub Repo stars](https://img.shields.io/github/stars/Canop/lfs?style=flat-square&label=)         |![GitHub last release](https://img.shields.io/github/release-date/Canop/lfs?style=flat-square&label=)         |
|diff|[delta     ](https://github.com/dandavison/delta)  |![GitHub Repo stars](https://img.shields.io/github/stars/dandavison/delta?style=flat-square&label=)  |![GitHub last release](https://img.shields.io/github/release-date/dandavison/delta?style=flat-square&label=)  |
|diff|[difftastic](https://github.com/Wilfred/difftastic)|![GitHub Repo stars](https://img.shields.io/github/stars/Wilfred/difftastic?style=flat-square&label=)|![GitHub last release](https://img.shields.io/github/release-date/Wilfred/difftastic?style=flat-square&label=)|
|du  |[dust      ](https://github.com/bootandy/dust)     |![GitHub Repo stars](https://img.shields.io/github/stars/bootandy/dust?style=flat-square&label=)     |![GitHub last release](https://img.shields.io/github/release-date/bootandy/dust?style=flat-square&label=)     |
|du  |[erdtree   ](https://github.com/solidiquis/erdtree)|![GitHub Repo stars](https://img.shields.io/github/stars/solidiquis/erdtree?style=flat-square&label=)|![GitHub last release](https://img.shields.io/github/release-date/solidiquis/erdtree?style=flat-square&label=)|
|find|[fd        ](https://github.com/sharkdp/fd)        |![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/fd?style=flat-square&label=)        |![GitHub last release](https://img.shields.io/github/release-date/sharkdp/fd?style=flat-square&label=)        |
|grep|[ripgrep   ](https://github.com/burntsushi/ripgrep)|![GitHub Repo stars](https://img.shields.io/github/stars/burntsushi/ripgrep?style=flat-square&label=)|![GitHub last release](https://img.shields.io/github/release-date/BurntSushi/ripgrep?style=flat-square&label=)|
|ls  |[exa       ](https://github.com/ogham/exa)         |![GitHub Repo stars](https://img.shields.io/github/stars/ogham/exa?style=flat-square&label=)         |![GitHub last release](https://img.shields.io/github/release-date/ogham/exa?style=flat-square&label=)         |
|ls  |[lsd       ](https://github.com/peltoche/lsd)      |![GitHub Repo stars](https://img.shields.io/github/stars/peltoche/lsd?style=flat-square&label=)      |![GitHub last release](https://img.shields.io/github/release-date/Peltoche/lsd?style=flat-square&label=)      |
|ps  |[procs     ](https://github.com/dalance/procs)     |![GitHub Repo stars](https://img.shields.io/github/stars/dalance/procs?style=flat-square&label=)      |![GitHub last commit](https://img.shields.io/github/release-date/dalance/procs?style=flat-square&label=)      |
|rm  |[rip       ](https://github.com/nivekuil/rip)      |![GitHub Repo stars](https://img.shields.io/github/stars/nivekuil/rip?style=flat-square&label=)      |![GitHub last release](https://img.shields.io/github/release-date/nivekuil/rip?style=flat-square&label=)      |
|sed |[sd        ](https://github.com/chmln/sd)          |![GitHub Repo stars](https://img.shields.io/github/stars/chmln/sd?style=flat-square&label=)          |![GitHub last release](https://img.shields.io/github/release-date/chmln/sd?style=flat-square&label=)          |

## Full list of Rust tools

**[atuin](https://github.com/ellie/atuin)**
"Magical shell history"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ellie/atuin?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ellie/atuin?style=flat)

**[bandwhich](https://github.com/imsnif/bandwhich)**
Terminal bandwidth utilization tool
<br>![GitHub Repo stars](https://img.shields.io/github/stars/imsnif/bandwhich?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/imsnif/bandwhich?style=flat)

**[bat](https://github.com/sharkdp/bat)**
A replacement for `cat` that provides syntax highlighting and other features.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/bat?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sharkdp/bat?style=flat)

**[bottom](https://github.com/ClementTsang/bottom)**
Yet another cross-platform graphical process/system monitor.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ClementTsang/bottom?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ClementTsang/bottom?style=flat)

**[broot](https://github.com/Canop/broot)**
A new way to see and navigate directory trees
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Canop/broot?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Canop/broot?style=flat)

**[choose](https://github.com/theryangeary/choose)**
A human-friendly and fast alternative to `cut` and (sometimes) `awk`
<br>![GitHub Repo stars](https://img.shields.io/github/stars/theryangeary/choose?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/theryangeary/choose?style=flat)

**[counts](https://github.com/nnethercote/counts)**
"A tool for ad hoc profiling"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/nnethercote/counts?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/nnethercote/counts?style=flat)

**[delta](https://github.com/dandavison/delta)**
A syntax-highlighting pager for git, `diff`, and grep output
<br>![GitHub Repo stars](https://img.shields.io/github/stars/dandavison/delta?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/dandavison/delta?style=flat)

**[difftastic](https://github.com/Wilfred/difftastic/)**
A syntax-aware diff
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Wilfred/difftastic?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Wilfred/difftastic?style=flat)

**[dog](https://github.com/ogham/dog)**
A command-line DNS client
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ogham/dog?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ogham/dog?style=flat)

**[dua](https://github.com/Byron/dua-cli)**
"View disk space usage and delete unwanted data, fast."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Byron/dua-cli?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Byron/dua-cli?style=flat)

**[dura](https://github.com/tkellogg/dura)**
"Dura is a background process that watches your Git repositories and commits your uncommitted changes without impacting HEAD, the current branch, or the Git index (staged files)."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/tkellogg/dura?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/tkellogg/dura?style=flat)

**[dust](https://github.com/bootandy/dust)**
"a more intuitive version of `du` in Rust"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/bootandy/dust?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/bootandy/dust?style=flat)

**[erdtree](https://github.com/solidiquis/erdtree)**
A multi-threaded file-tree visualizer and disk usage analyzer. (I usually use it as `et -l 1 -s size <DIR>`)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/solidiquis/erdtree?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/solidiquis/erdtree?style=flat)

**[exa](https://github.com/ogham/exa/)**
"A modern version of `ls`". Note: See [this discussion re: maintenance](https://github.com/ogham/exa/issues/1139). ([website](https://the.exa.website/))
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ogham/exa?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ogham/exa?style=flat)

**[fclones](https://github.com/pkolaczk/fclones)**
an "efficient duplicate file finder"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/pkolaczk/fclones?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/pkolaczk/fclones?style=flat)

**[fd](https://github.com/sharkdp/fd)**
"A simple, fast and user-friendly alternative to `find`"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/fd?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sharkdp/fd?style=flat)

**[felix](https://github.com/kyoheiu/felix)**
tui file manager with vim-like key mapping
<br>![GitHub Repo stars](https://img.shields.io/github/stars/kyoheiu/felix?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/kyoheiu/felix?style=flat)

**[ffsend](https://github.com/timvisee/ffsend)**
"Easily and securely share files from the command line. A fully featured Firefox Send client."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/timvisee/ffsend?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/timvisee/ffsend?style=flat)

**[frum](https://github.com/TaKO8Ki/frum)**
A modern Ruby version manager written in Rust
<br>![GitHub Repo stars](https://img.shields.io/github/stars/TaKO8Ki/frum?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/TaKO8Ki/frum?style=flat)

**[fselect](https://github.com/jhspetersson/fselect)**
"Find files with SQL-like queries"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/jhspetersson/fselect?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/jhspetersson/fselect?style=flat)

**[git-cliff](https://github.com/orhun/git-cliff)**
"A highly customizable Changelog Generator that follows Conventional Commit specifications"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/orhun/git-cliff?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/orhun/git-cliff?style=flat)

**[gptman](https://github.com/rust-disk-partition-management/gptman)**
"A GPT manager that allows you to copy partitions from one disk to another and more"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/rust-disk-partition-management/gptman?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/rust-disk-partition-management/gptman?style=flat)

**[grex](https://github.com/pemistahl/grex)**
A command-line tool and library for generating regular expressions from user-provided test cases
<br>![GitHub Repo stars](https://img.shields.io/github/stars/pemistahl/grex?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/pemistahl/grex?style=flat)

**[himalaya](https://github.com/soywod/himalaya)**
Command-line interface for email management
<br>![GitHub Repo stars](https://img.shields.io/github/stars/soywod/himalaya?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/soywod/himalaya?style=flat)

**[htmlq](https://github.com/mgdm/htmlq)**
Like jq, but for HTML. Uses CSS selectors to extract bits of content from HTML files.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/mgdm/htmlq?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/mgdm/htmlq?style=flat)

**[hyperfine](https://github.com/sharkdp/hyperfine)**
Command-line benchmarking tool
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/hyperfine?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sharkdp/hyperfine?style=flat)

**[inlyne](https://github.com/trimental/inlyne)**
"GPU powered yet browsless tool to help you quickly view markdown files"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/trimental/inlyne?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/trimental/inlyne?style=flat)

**[jless](https://github.com/PaulJuliusMartinez/jless)**
"command-line JSON viewer designed for reading, exploring, and searching through JSON data."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/PaulJuliusMartinez/jless?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/PaulJuliusMartinez/jless?style=flat)

**[joshuto](https://github.com/kamiyaa/joshuto)**
"ranger-like terminal file manager written in Rust"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/kamiyaa/joshuto?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/kamiyaa/joshuto?style=flat)

**[jql](https://github.com/yamafaktory/jql)**
A JSON query language CLI tool
<br>![GitHub Repo stars](https://img.shields.io/github/stars/yamafaktory/jql?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/yamafaktory/jql?style=flat)

**[just](https://github.com/casey/just)**
Just a command runner (seems like an alternative to `make`)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/casey/just?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/casey/just?style=flat)

**[legdur](https://hg.sr.ht/~cyplo/legdur)**
A "simple CLI program to compute hashes of large sets of files in large directory structures and compare them with a previous snapshot."

**[lemmeknow](https://github.com/swanandx/lemmeknow)**
Identify mysterious text or analyze hard-coded strings from captured network packets, malwares, and more.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/swanandx/lemmeknow?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/swanandx/lemmeknow?style=flat)

**[lfs](https://github.com/Canop/lfs)**
A Linux utility to get information on filesystems; like `df` but better
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Canop/lfs?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Canop/lfs?style=flat)

**[lsd](https://github.com/Peltoche/lsd)**
The next generation `ls` command (though personally I prefer `exa`)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Peltoche/lsd?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Peltoche/lsd?style=flat)

**[macchina](https://github.com/macchina-cli/macchina)**
Fast, minimal and customizable system information frontend.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/macchina-cli/macchina?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/macchina-cli/macchina?style=flat)

**[mdBook](https://github.com/rust-lang/mdBook)**
Create books from markdown files. Like Gitbook but implemented in Rust
<br>![GitHub Repo stars](https://img.shields.io/github/stars/rust-lang/mdBook?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/rust-lang/mdBook?style=flat)

**[mdcat](https://github.com/lunaryorn/mdcat)**
Fancy `cat` for Markdown
<br>![GitHub Repo stars](https://img.shields.io/github/stars/lunaryorn/mdcat?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/lunaryorn/mdcat?style=flat)

**[miniserve](https://github.com/svenstaro/miniserve)**
is "a CLI tool to serve files and dirs over HTTP". I use this as a replacement for `python -m http.server`.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/svenstaro/miniserve) ![GitHub last commit](https://img.shields.io/github/release-date/svenstaro/miniserve?style=flat)

**[monolith](https://github.com/y2z/monolith)**
Save complete web pages as a single HTML file
<br>![GitHub Repo stars](https://img.shields.io/github/stars/y2z/monolith?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/y2z/monolith?style=flat)

**[mprocs](https://github.com/pvolok/mprocs)**
Run multiple commands in parallel
<br>![GitHub Repo stars](https://img.shields.io/github/stars/pvolok/mprocs?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/pvolok/mprocs?style=flat)

**[ouch](https://github.com/ouch-org/ouch)**
"Painless compression and decompression for your terminal"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ouch-org/ouch?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ouch-org/ouch?style=flat)

**[pastel](https://github.com/sharkdp/pastel)**
A command-line tool to generate, analyze, convert and manipulate colors.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sharkdp/pastel?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sharkdp/pastel?style=flat)

**[pipr](https://github.com/Elkowar/pipr)**
"A tool to interactively write shell pipelines."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Elkowar/pipr?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Elkowar/pipr?style=flat)

**[procs](https://github.com/dalance/procs)**
A modern replacement for `ps` written in Rust
<br>![GitHub Repo stars](https://img.shields.io/github/stars/dalance/procs?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/dalance/procs?style=flat)

**[qsv](https://github.com/jqnatividad/qsv)**
CSVs sliced, diced & analyzed. (A fork of `xsv`)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/jqnatividad/qsv?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/jqnatividad/qsv?style=flat)

**[rargs](https://github.com/lotabout/rargs)**
xargs + awk with pattern matching support.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/lotabout/rargs?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/lotabout/rargs?style=flat)

**[rip](https://github.com/nivekuil/rip)**
A safe and ergonomic alternative to `rm`
<br>![GitHub Repo stars](https://img.shields.io/github/stars/nivekuil/rip?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/nivekuil/rip?style=flat)

**[ripgrep](https://github.com/BurntSushi/ripgrep)**
A faster replacement for GNU’s `grep` command. This tool is very good. See [ripgrep-all](https://github.com/phiresky/ripgrep-all) to search PDFs, E-Books, Office documents, zip, tar.gz, etc.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/BurntSushi/ripgrep?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/BurntSushi/ripgrep?style=flat)

**[ripsecrets](https://github.com/sirwart/ripsecrets)**
Find secret keys in your code before commiting them to git. I've contributed to this one!
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sirwart/ripsecrets?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sirwart/ripsecrets?style=flat)

**[rnr](https://github.com/ismaelgv/rnr)**
"A command-line tool to batch rename files and directories"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ismaelgv/rnr?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ismaelgv/rnr?style=flat)

**[ruff](https://github.com/charliermarsh/ruff)**
An extremely fast Python linter, written in Rust.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/charliermarsh/ruff?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/charliermarsh/ruff?style=flat)

**[ruplacer](https://github.com/your-tools/ruplacer)**
Find and replace text in source files
<br>![GitHub Repo stars](https://img.shields.io/github/stars/your-tools/ruplacer?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/your-tools/ruplacer?style=flat)

**[sd](https://github.com/chmln/sd)**
Intuitive find & replace CLI (`sed` alternative).
<br>![GitHub Repo stars](https://img.shields.io/github/stars/chmln/sd?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/chmln/sd?style=flat)

**[skim](https://github.com/lotabout/skim)**
A command-line fuzzy finder.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/lotabout/skim?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/lotabout/skim?style=flat)

**[tealdear](https://github.com/dbrgn/tealdeer)**
A very fast implementation of `tldr` in Rust.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/dbrgn/tealdeer?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/dbrgn/tealdeer?style=flat)

**[teehee](https://github.com/Gskartwii/teehee)**
"A modal terminal hex editor"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Gskartwii/teehee?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/Gskartwii/teehee?style=flat)

**[tin-summer](https://github.com/vmchale/tin-summer)**
Find build artifacts that are taking up disk space
<br>![GitHub Repo stars](https://img.shields.io/github/stars/vmchale/tin-summer?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/vmchale/tin-summer?style=flat)

**[tokei](https://github.com/XAMPPRocky/tokei)**
Count your (lines of) code, quickly
<br>![GitHub Repo stars](https://img.shields.io/github/stars/XAMPPRocky/tokei?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/XAMPPRocky/tokei?style=flat)

**[topgrade](https://github.com/topgrade-rs/topgrade)**
Upgrade all of your tools
<br>![GitHub Repo stars](https://img.shields.io/github/stars/topgrade-rs/topgrade?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/topgrade-rs/topgrade?style=flat)

**[watchexec](https://github.com/watchexec/watchexec)**
Execute commands in response to file modifications. (Note: See [cargo watch](https://github.com/watchexec/cargo-watch) if you want to watch a Rust project.)
<br>![GitHub Repo stars](https://img.shields.io/github/stars/watchexec/watchexec?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/watchexec/watchexec?style=flat)

**[xcp](https://github.com/tarka/xcp)**
An extended `cp`
<br>![GitHub Repo stars](https://img.shields.io/github/stars/tarka/xcp?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/tarka/xcp?style=flat)

**[xh](https://github.com/ducaale/xh)**
"Friendly and fast tool for sending HTTP requests"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ducaale/xh?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ducaale/xh?style=flat)

**[xplr](https://github.com/sayanarijit/xplr)**
"A hackable, minimal, fast TUI file explorer"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/sayanarijit/xplr?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/sayanarijit/xplr?style=flat)

**[xsv](https://github.com/BurntSushi/xsv)**
A fast CSV command line toolkit written in Rust.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/BurntSushi/xsv?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/BurntSushi/ripgrep?style=flat)

**[zoxide](https://github.com/ajeetdsouza/zoxide)**
A smarter `cd` command.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ajeetdsouza/zoxide?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ajeetdsouza/zoxide?style=flat)

### Calculators
**[eva](https://github.com/nerdypepper/eva)**
"a calculator REPL, similar to bc(1)"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/nerdypepper/eva?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/nerdypepper/eva?style=flat)

**[fend](https://github.com/printfn/fend)**
"Arbitrary-precision unit-aware calculator" ([Documentation](https://printfn.github.io/fend/documentation)). I prefer this calculator.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/printfn/fend?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/printfn/fend?style=flat)

**[Kalker](https://github.com/PaddiM8/kalker)**
"a calculator with math syntax that supports user-defined variables and functions, complex numbers, and estimation of derivatives and integrals"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/PaddiM8/kalker?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/PaddiM8/kalker?style=flat)

## Terminal emulators / terminal-related

**[Alacritty](https://github.com/alacritty/alacritty)**:
A cross-platform, OpenGL terminal emulator.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/alacritty/alacritty?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/alacritty/alacritty?style=flat)

**[Starship](https://starship.rs/)**:
Customizable prompt for any shell.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/starship/starship?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/starship/starship?style=flat)

**[Wezterm](https://github.com/wez/wezterm)**:
A GPU-accelerated cross-platform terminal emulator and multiplexer written by @wez and implemented in Rust
<br>![GitHub Repo stars](https://img.shields.io/github/stars/wez/wezterm?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/wez/wezterm?style=flat)

**[Zellij](https://github.com/zellij-org/zellij)**:
A terminal workspace with batteries included.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/zellij-org/zellij?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/zellij-org/zellij?style=flat)

## Text editors written in Rust

**[amp](https://github.com/jmacdonald/amp)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/jmacdonald/amp?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/zellij-org/zellij?style=flat)

**[helix](https://github.com/helix-editor/helix)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/helix-editor/helix?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/helix-editor/helix?style=flat)

**[kibi](https://github.com/ilai-deutel/kibi)**
"A text editor in ≤1024 lines of code, written in Rust"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/ilai-deutel/kibi?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/ilai-deutel/kibi?style=flat)

**[lapce](https://github.com/lapce/lapce)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/lapce/lapce?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/lapce/lapce?style=flat)

**[Ox](https://github.com/curlpipe/ox)**
An independent Rust text editor that runs in your terminal!
<br>![GitHub Repo stars](https://img.shields.io/github/stars/curlpipe/ox?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/curlpipe/ox?style=flat)

**[pepper](https://github.com/vamolessa/pepper)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/vamolessa/pepper?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/vamolessa/pepper?style=flat)

**[xi](https://github.com/xi-editor/xi-editor)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/zellij-org/zellij?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/zellij-org/zellij?style=flat)

**[zee](https://github.com/zee-editor/zee)**
<br>![GitHub Repo stars](https://img.shields.io/github/stars/zee-editor/zee?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/zee-editor/zee?style=flat)

See [this "Battle of the [Rust] text editors" post from 2022](https://matduggan.com/battle-of-the-text-editors/) or [this r/rust post](https://www.reddit.com/r/rust/comments/121l4ek/editors_written_in_rust/).

## Email clients
[himalaya](https://github.com/soywod/himalaya)
"Command-line interface for email management"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/soywod/himalaya?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/soywod/himalaya?style=flat)

## All core utils!?
Note that there is ["a cross-platform reimplementation of the GNU coreutils in Rust"](https://github.com/uutils/coreutils). I link it here for those interested, but I argue that it doesn't _quite_ fit into this project's goals.

## Tools to help working with Rust lang itself

**[bacon](https://github.com/Canop/bacon)**:
A background Rust code checker
<br>![GitHub Repo stars](https://img.shields.io/github/stars/Canop/bacon?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/printfn/fend?style=flat)

**[cargo watch](https://github.com/watchexec/cargo-watch)**:
Watches over your Cargo project's source.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/watchexec/cargo-watch?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/watchexec/cargo-watch?style=flat)

**[cargo-audit](https://github.com/RustSec/rustsec/tree/main/cargo-audit)**:
Audit Cargo.lock files for crates with security vulnerabilities reported to the RustSec Advisory Database. See also: [cargo-deny](https://github.com/EmbarkStudios/cargo-deny).

**[cargo-binstall](https://github.com/cargo-bins/cargo-binstall)**:
"Binary installation for [R]ust projects"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/cargo-bins/bargo-binstall?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/cargo-bins/cargo-binstall?style=flat)

**[cargo-cache](https://github.com/matthiaskrgr/cargo-cache)**
Display information on the cargo cache (`~/.cargo/` or `$CARGO_HOME`). Optional cache pruning.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/matthiaskrgr/cargo-cache?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/matthiaskrgr/cargo-cache?style=flat)

**[cargo-crev](https://github.com/crev-dev/cargo-crev)**:
A cryptographically verifiable code review system for the cargo (Rust) package manager.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/crev-dev/cargo-crev?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/crev-dev/cargo-crev?style=flat)

**[cargo-dist](https://github.com/axodotdev/cargo-dist)**:
"Shippable application packaging for Rust"
<br>![GitHub Repo stars](https://img.shields.io/github/stars/axodotdev/cargo-dist?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/axodotdev/cargo-dist?style=flat)

**[cargo-geiger](https://github.com/rust-secure-code/cargo-geiger)**:
Detects usage of unsafe Rust in a Rust crate and its dependencies.
<br>![GitHub Repo stars](https://img.shields.io/github/stars/rust-secure-code/cargo-geiger?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/rust-secure-code/cargo-geiger?style=flat)

**[cargo-wipe](https://github.com/mihai-dinculescu/cargo-wipe)**:
Cargo subcommand that recursively finds and optionally wipes all "target" or "node_modules" folders that are found in the current path. See also: [kondo](https://github.com/tbillington/kondo).
<br>![GitHub Repo stars](https://img.shields.io/github/stars/mihai-dinculescu/cargo-wipe?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/mihai-dinculescu/cargo-wipe?style=flat)

**[kani-verifier](https://github.com/model-checking/kani)**:
A "bit-precise model checker for Rust."
<br>![GitHub Repo stars](https://img.shields.io/github/stars/model-checking/kani?style=flat) ![GitHub last commit](https://img.shields.io/github/release-date/model-checking/kani?style=flat)

## Other lists of Rust command line utilities

- [lib.rs's list](https://lib.rs/command-line-utilities)
- ["Awesome Rust"](https://github.com/rust-unofficial/awesome-rust)
- [Awesome Alternatives in Rust](https://github.com/TaKO8Ki/awesome-alternatives-in-rust)

## Tips

### `exa` aliases I use in my `~/.bashrc`

```bash
if hash exa 2>/dev/null; then
    alias ls='exa'
    alias l='exa -l --all --group-directories-first --git'
    alias ll='exa -l --all --all --group-directories-first --git'
    alias lt='exa -T --git-ignore --level=2 --group-directories-first'
    alias llt='exa -lT --git-ignore --level=2 --group-directories-first'
    alias lT='exa -T --git-ignore --level=4 --group-directories-first'
else
    alias l='ls -lah'
    alias ll='ls -alF'
    alias la='ls -A'
fi
```

## Shameless plug: Tools that I've written in Rust

- [Tidy](https://github.com/sts10/tidy): A command-line tool for combining and cleaning large word list files.
- [Medic](https://github.com/sts10/medic): Check the "health" of passwords in a KeePass database
- [QRForge](https://github.com/sts10/qr-forge): Safely transform between 32-character TOTP secret keys and their QR codes

## Criteria for submitting a tool to this list

If you know of a Rust command line tool that you think would be a good fit for this list, open an issue or a PR. Note that I generally only consider projects that have **100 or more stars on GitHub**, which I'm hoping means that the program will be a bit battle-tested and ready for real-world use. I also reserve the right to reject submissions even if they meet this criteria.

You're of course welcome to fork this project and maintain your own list! Check the included LICENSE for more information.

<!-- Open an Issue or PR or let me know on [Mastodon](https://hachyderm.io/@schlink). -->
