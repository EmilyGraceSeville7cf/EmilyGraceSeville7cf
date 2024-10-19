# Maisa Unbelievable 💕

<div align="center">

[![discourse](https://img.shields.io/badge/Ubuntu-cc4e0a?logo=discourse&logoColor=white)](https://discourse.ubuntu.com/u/emilygraceseville7cf/summary)
[![element](https://img.shields.io/badge/Element-@emilygraceseville7cf:matrix.org-0DBD8B?logo=element&labelColor=454545&logoColor=white)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/no-profile-link-supported.md)
[![wire](https://img.shields.io/badge/Wire-@emilygraceseville7cf-454545?logo=wire&labelColor=white&logoColor=black)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/no-profile-link-supported.md)
[![mastodon](https://img.shields.io/badge/Mastodon-744cc6?logo=mastodon&logoColor=white)](https://fosstodon.org/@EmilySeville7cfg)
[![bluesky](https://img.shields.io/badge/Bluesky-0285FF?logo=bluesky&logoColor=white)](https://bsky.app/profile/emilyseville7cf.bsky.social)

![whatsapp](https://img.shields.io/badge/+7%20999%20808%2009%2030-10B418?logo=whatsapp&logoColor=white)

**Google Chat** messenger is the recommended way to contact me, while **Bluesky**
to view my updates.
</div>

## About me

I am open source contributor and I am keen on administrating, scripting,
creating sites and presentations. It’s my life. I like to automate routine tasks
and not to do them manually. Currently I have the following skills (just the
most interesting tools are mentioned and some of their usages are explained):

- :computer: **programming, markup and configuration languages**:
  - `Fish` ([`💬`][fish_community]
  [`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/fish-use)
  [`📦`](https://github.com/fish-shell/fish-shell/pulls/EmilyGraceSeville7cf)):
    automating tasks for developed tools
  - `TinyScheme` ([`💬`][gimp_community]
  [`🖊️`](https://github.com/EmilyGraceSeville7cf/tinyscheme-library-scripts)):
    extending GIMP
  - `Go` ([`💬`][go_community]
  [`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/go-tools-use)):
    developing CLI, TUI and GUI applications
  - `JavaScript` ([`💬`][javascript_community]
    [`⭐`](https://github.com/stars/EmilyGraceSeville7cf/lists/javascript-tools-use)):
    developing VS Code extensions and Web Apps
  - `YAML` & `JSON` ([`📦`](https://github.com/SchemaStore/schemastore/pulls/EmilyGraceSeville7cf)):
    configuration languages for `Go` applications
  - `Markdown`: explaining developed tools
- :memo: **ides and editors**:
  - `Visual Studio Code` ([`💬`][vscode_community]): programming, writing tool explanations and
    configurations
  - `GIMP` ([`💬`][gimp_community]) & `Inkscape` ([`💬`][inkscape_community]):
    drawing images for developed tools
  - `Google Slides` ([`💬`][slides_community]) & `Microsoft PowerPoint` ([`💬`][powerpoint_community]):
    creating presentations
- :clock130: **vcs-tools**:
  - `Git` & `GitHub`: managing tool development

Legend:

- `💬`: community
- `⭐`: favorite tools
- `📦`: pull requests
- `🖊️`: personal scripts

[fish_community]: https://matrix.to/#/#fish-shell:matrix.org
[gimp_community]: https://discuss.pixls.us/tag/gimp
[go_community]: https://forum.golangbridge.org/
[javascript_community]: https://www.sitepoint.com/community/c/javascript/33
[inkscape_community]: https://inkscape.org/forums/
[vscode_community]: https://github.com/microsoft/vscode-discussions/discussions
[slides_community]: https://support.google.com/docs/threads?hl=en&thread_filter=(category:docs_slides)&sjid=18016765158418257400-EU
[powerpoint_community]: https://answers.microsoft.com/en-us/

<div align="center">

![gopher](./animated-jumping-gopher.gif)

</div>

## Placeholder syntax in my CLI tools 📖

Starting from 21 August 2024 I use the following placeholder syntax in all my
tools ([Go-inspired](https://pkg.go.dev/text/template)):

- `{{placeholder}}`: some arbitrary text with no constraints implied which
  should be exactly one CLI argument.
- `{{placeholder ...}}`: almost the same thing as the previous one, but here
  zero or more arguments are expected.
- `|` can be used inside double curly braces to provide more than one
  alternative for what can be placed instead of placeholder.

, where instead of `placeholder` any text can be written which explains what
should be put instead of CLI argument(s), but without spaces unless it's
explicitly permitted. This syntax is used just when no other default syntax is
mandated.

Examples:

```fish
command {{number}} # 1 number expected
command {{number..}} # 0 or more numbers expected
command {{number|strings...}} # one number or 0 or more string expected
```
