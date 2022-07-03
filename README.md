🐳 Docker fish completions 🐟
==============================

docker command completion for the fish shell.

Always in sync-up with [docker/cli/contrib/completion/fish/docker.fish](https://github.com/docker/cli/blob/master/contrib/completion/fish/docker.fish)

- fish = awesome
- docker = awesome
- completion = awesome²

Status
-------
<a href="https://github.com/ankitsumitg"><img src="https://img.shields.io/github/workflow/status/ankitsumitg/docker-fish-completions/pull-fish-competions-from-docker?logo=github&style=for-the-badge" alt="Fish"></a>


Installation
------------
    mkdir ~/.config/fish/completions
    wget https://raw.githubusercontent.com/ankitsumitg/docker-fish-completions/main/docker.fish -O ~/.config/fish/completions/docker.fish

### [Fisher Plugin](https://github.com/jorgebucaran/fisher)

    fisher install ankitsumitg/docker-fish-completions

fish will show up the new completions straight away, no reload necessary.
    
Example
-------
    % docker run -[TAB]
    --attach          (Attach to stdin, stdout or stderr.)
    ...

    % docker run -t -i [TAB]
        ubuntu:20.04               (Image)

    % docker run -t -i ubuntu:20.04
    / #

Completion supported
--------------------
- parameters
- commands
- containers
- images
- repositories
