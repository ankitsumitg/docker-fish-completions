# 🐳 Docker Fish completions

<a href="https://github.com/ankitsumitg"><img src="https://img.shields.io/github/actions/workflow/status/ankitsumitg/docker-fish-completions/workflow.yml?logo=github&style=for-the-badge" alt="Fish"></a>

`docker` command completions for [Fish](https://fishshell.com/).

Always in sync with official [docker/cli/contrib/completion/fish/docker.fish](https://github.com/docker/cli/blob/master/contrib/completion/fish/docker.fish).

- Fish = awesome
- docker = awesome
- completions = awesome²

## Installation

Install with [Fisher](https://github.com/jorgebucaran/fisher):

```console
fisher install ankitsumitg/docker-fish-completions
```

Or manually:

```console
mkdir ~/.config/fish/completions
wget https://raw.githubusercontent.com/ankitsumitg/docker-fish-completions/main/completions/docker.fish -O ~/.config/fish/completions/docker.fish
```

Fish will load the new completions straight away—no reload required.

## Example

```console
% docker run -[TAB] 🥊
--attach          (Attach to stdin, stdout or stderr.)
...

% docker run -t -i [TAB] 🥊
    ubuntu:20.04               (Image)

% docker run -t -i ubuntu:20.04
/ #
```

## Completion supported

- parameters
- commands
- containers
- images
- repositories

## Contributors

<a href="https://github.com/ankitsumitg/docker-fish-completions/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ankitsumitg/docker-fish-completions" />
</a>
