# Visual Studio Code Hugo snippets

Snippets for [Hugo's Go templates](https://gohugo.io/templates/introduction/).

Based on [Atom text snippets for Hugo](https://github.com/holehan/atom-hugo-snippets) and inspired by [regisphilibert/Sublime-Hugo-Snippets](https://github.com/regisphilibert/Sublime-Hugo-Snippets)

## Installation

Download the [latest release](https://github.com/holehan/vscode-hugo-snippets/releases) and install the VSIX extension file using _Command Palette_ -> _Extensions: Install from VSIX..._

## Usage

Make sure to use "Golang HTML Template (gohtml)" as a language type within VS Code.

## Available snippets

| Snippet            | Tab trigger   | Output                                  |
| :----------------- | :------------ | :-------------------------------------- |
| Curlies            | **x**         | `{{ }}`                                 |
| Dot                | **dot**       | `{{ . }}`                               |
| If                 | **if**        | `{{ if }} {{ end }}`                    |
| If/Else            | **ife**       | `{{ if }} {{ else }} {{ end }}`         |
| If/Else if         | **ifei**      | `{{ if }} {{ else if }} {{ end }}`      |
| With               | **with**      | `{{ with }} {{ end }}`                  |
| With/Else          | **withe**     | `{{ with }} {{ else }} {{ end }}`       |
| Range              | **range**     | `{{ range }} {{ end }}`                 |
| Partial            | **partial**   | `{{ partial "" . }}`                    |
| Block              | **block**     | `{{ block "main" . }} {{ end }}`        |
| Block define       | **define**    | `{{ define "block" }} {{ end }}`        |
| Comment            | **comment**   | `{{/* */}}`                             |
| Variable           | **var**       | `{{ $var := what }}`                    |
| Scratch Set        | **srset**     | `{{ $.Scratch.Set "" }}`                |
| Scratch Add        | **sradd**     | `{{ $.Scratch.Add "" }}`                |
| Scratch Get        | **srget**     | `{{ $.Scratch.Get "" }}`                |
| Scratch Set In Map | **srmap**     | `{{ $.Scratch.SetInMap "" "" "" }}`     |
| Scratch Sort Map   | **srsortmap** | `{{ $.Scratch.GetSortedMapValues "" }}` |
| Debug              | **debug**     | `{{ printf "%#v" }}`                    |
