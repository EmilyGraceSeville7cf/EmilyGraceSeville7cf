# Maisa Unbelievable 💕

<div align="center">

[![reddit](https://img.shields.io/badge/Reddit-FF4500?logo=reddit&logoColor=white)](https://www.reddit.com/user/EmilyGraceSeville7cf)
[![session](https://img.shields.io/badge/Session-004b44?logo=session&logoColor=white)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/qr-code-required.md)
[![signal](https://img.shields.io/badge/Signal-blue?logo=signal&logoColor=white)](https://signal.me/#eu/-xVbMeyDih_CE6JuCn-XuEtIbbXgv2H5M7WS7U_87KQeEycaT2hIiZYmFvuJVyAq)
[![element](https://img.shields.io/badge/Element-@emilygraceseville7cf:matrix.org-0DBD8B?logo=element&labelColor=454545&logoColor=white)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/no-profile-link-supported.md)
[![wire](https://img.shields.io/badge/Wire-@emilygraceseville7cf-454545?logo=wire&labelColor=white&logoColor=black)](https://github.com/EmilyGraceSeville7cf/EmilyGraceSeville7cf/blob/main/infos/no-profile-link-supported.md)
[![mastodon](https://img.shields.io/badge/Mastodon-744cc6?logo=mastodon&logoColor=white)](https://fosstodon.org/@EmilySeville7cfg)
[![bluesky](https://img.shields.io/badge/Bluesky-0285FF?logo=bluesky&logoColor=white)](https://bsky.app/profile/emilyseville7cf.bsky.social)

![whatsapp](https://img.shields.io/badge/+7%20999%20808%2009%2030-10B418?logo=whatsapp&logoColor=white)

**Google Chat** messenger is the recommended way to contact me.
</div>

## About me

I am a native russian speaker, open source contributor and I am keen on
administrating, scripting, creating sites and presentations. It’s my life. I
like to automate routine tasks and not to do them manually. Currently I have the
following skills (just the most interesting tools are mentioned and some of
their usages are explained):

- :computer: **programming, markup and configuration languages**:
  - `Fish`: automating tasks for developed tools
  - `TinyScheme`: extending GIMP
  - `Go`: developing CLI, TUI and GUI applications
  - `YAML` & `JSON`: configuration languages for `Go` applications
  - `Markdown`: explaining developed tools
- :memo: **ides and editors**:
  - `Visual Studio Code`: programming, writing tool explanations and
    configurations
  - `GIMP` & `Inkscape`: drawing images for developed tools
  - `OnlyOffice`: creating presentations about English and German
- :clock130: **vcs-tools**:
  - `Git` & `GitHub`: managing tool development

<div align="center">

![gopher](./animated-jumping-gopher.gif)

</div>

I support several projects and organizations such as (just the most interesting ones are mentioned):

<div align="center">

[![command-line-interface-pages](https://img.shields.io/badge/Command%20Line%20Interface%20Pages:%20organization-owner%20%26%20author-a32236?labelColor=ed425c&style=flat-square)](https://github.com/command-line-interface-pages)
[![better-emacs](https://img.shields.io/badge/Better%20Emacs:%20organization-owner%20%26%20author-a32236?labelColor=ed425c&style=flat-square)](https://github.com/emilyseville7cfg-better-emacs)
[![schemastore](https://img.shields.io/badge/SchemaStore:%20json%20schemas-contributor-a32236?labelColor=ed425c&style=flat-square)](https://github.com/SchemaStore/schemastore/pulls/EmilySeville7cfg) 

</div>

But now I mainly focused on [**[C]ommand [L]ine [I]nterface [P]ages**](https://github.com/command-line-interface-pages/prototypes/tree/main/clip-view) project:

![image](https://user-images.githubusercontent.com/42812113/220039936-52d78a9f-4ef5-4a2f-9bdc-29f43d885ea7.png)

which provides neat command help pages.

## How do I review pull requests? 👓

For the first 2 pages less than or equal 50 lines I provide detailed mistake expanations for all issues
with links to contributing guides how to fix them.

Other remaining pages are not scanned for problems.

## Placeholder syntax in my CLI tools

Starting from 29 december 2023 I use the following placeholder syntax in all my tools ([Go-inspired](https://pkg.go.dev/text/template)):

- `{{placeholder}}`: some arbitrary text with no constraints implied which should be exactly one CLI argument.
  If there are any they should be explicitly stated in the documentation.
  There is no standardized way for describing them.
- `{{placeholder ...}}`: almost the same thing as the previous one, but here one or more arguments are expected.
  If no arguments or some specific amount of them is required it should be explicitly stated in the documentation.
  With `|` ellipsis (`...`) can be used just ones, at the end, implying that all alternatives accept several arguments
  unless the opposite is stated.
  There is no standardized way for mentioning it.
- `|` can be used inside double curly braces to provide more than one alternative for what can be placed instead of placeholder.
  If some alternatives can be used just under certain circumstances, it should be explicitly stated in the documentation.
  There is no standardized way for mentioning it.

, where instead of `placeholder` any text can be written which explains what should be put instead of CLI argument(s),
but without spaces unless it's explicitly permitted.
