### [Powerlevel10k](https://github.com/romkatv/powerlevel10k)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```shell
git clone https://github.com/dracula/powerlevel10k.git
```

#### Install manually

Download using the GitHub .zip download option and unzip them.

#### Activating theme

1. Install [Dracula for iTerm](https://draculatheme.com/iterm)
1. Install [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)
1. Install [powerlevel10k](https://github.com/romkatv/powerlevel10k)
1. Replace default configurations with contents in `./files`
    ```shell
    cd powerlevel10k.git
    cp ./files/.zshrc ~/.zshrc
    cp ./files/.p10k.zsh ~/.p10k.zsh
    ```